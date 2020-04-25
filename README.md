# Some important notes

## Data schema

### Helpfully fields

- createdBy / owner: user who logged in to the application that creates the document, read-only, it is created automatically with the creation of the document.
- createdAt: creation date, read only, it is created automatically with the creation of the document.
- updatedBy: the user is logged in to the application that updates the document, it can be updated, it is automatically updated with the updated document.
- updatedAt: date of the last update, it can be updated, it is automatically updated with the updated document.
- active: a value indicating whether the document can be used, can be updated, must be true by default. (active: false, can be used to not delete the document)
