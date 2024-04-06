# Axon Records MCT Export Update Tool

Add and edit charges from an Axon Records MCT export file. 

>Designed to be a single HTML file that can be run locally in a web browser. 

## Basic Features

- Automatically increment the MCT External ID
- Search and filter charges by any field
- Add, edit, duplicate, and delete charges
- Export the updated MCT file
- Paste charges from Excel or Google Sheets

### CRUD Operations

- Duplicate a charge in an existing MCT and edit the duplicated charge
- Add charges to an existing MCT export file
- Edit charges in an existing MCT export file
- Remove charges from an existing MCT export file


## How to Use

1. Download your existing MCT file from the Axon Records interface
2. Open the index.html file from the repo in you web browser
3. Select the MCT file you downloaded
4. Create, update, duplicate and edit, or delete charges
5. Export the updated MCT file
6. Upload the updated MCT file to Axon Records

## To-Do

- [x] When adding a charge, change the row color to indicate that the charge has been added or edited
- [ ] Add Axon data validation logic to each field
- [ ] Add column sorting
- [x] More explicit file export names
- [ ] Add dropdowns for unique values like NIBRS codes, Offense Categories, etc.
- [ ] Auto date options for the date fields (today, yesterday, max-possible, etc.)
- [x] Local Storage to retain the state even after the page refreshes
- [ ] Add check step to ensure that the MCT file is the correct format
  
## Known Bugs
- [ ] Inability to revert changes after paste operation

