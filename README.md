# SMCoordinator

## SETUP

1. Create New Folder on Desktop (or wherever you want to store ALL your SMC files), called SMCoordination .../Desktop/SMCoordination/
2. Download from goo.gl/g2Ndzx, and *PUT IT IN SMCoordination FOLDER*
- SMCoordinatorV1.py .../Desktop/SMCoordination/SMCoordinatorV1.py
- python-3.6.3-...(.pkg MacOSX)/(.exe Windows)

## Coordination
*Do this for every move*
1. From goo.gl/g2Ndzx, open SMCoordinatorV1.gsheet
2. File > Download as > Microsoft Excel (.xlsx)
3. Save file as {MOVE#}.xlsx to SMCoordination folder (e.g. the file for move 100 should be 100.xlsx)
4. Open {MOVE#}.xlsx and edit MC tab according to MC planning snd move requirements
5. File > Save As > {MOVE#}.csv (MS-DOS comma separated v)
6. It will prompt you saying you cannot save multiple sheets. Click Save Active Sheet then Continue
7. Open SMCoordinatorV1.py file in IDLE
8. Run > Run Module
9. Enter Move# (same as what you named the file in step 5.)
10. No errors should appear. If an error appears, it is most likely a decoding error of special symbols. Try opening the .csv file, erase contents of cells K13:K14 and L13:L14 (you will have to manually input these back into the itinerary)
- Save the .csv file again (Click OK and Continue to any dialogue boxes that appear)
11. After program has successfully run, you will be able to find an Itinerary{MOVE#}.html file in the SMCoordination folder. Open this file (it will open in one of your web browsers)
12. Copy and Paste the contents of the .html file into your Move Itinerary email
