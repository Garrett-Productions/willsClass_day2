Map will make a copy of an array and apply our own twist to it... using a callback function that takes in each element of the array returning what we want to do to each element

Example of Map

const vacations = ["sayulita", "portland", "orange county"];
const vacationList = vacations.map( oneVacation => `<li>${oneVacation}</li>`);