window.onload = function() {

var incomingData = [
{"id":1,"firstName":"Andre","lastName":"Pereira","email":"mail@gmail.com","phone":"777888"},
{"id":2,"firstName":"Julio","lastName":"Laranjeira","email":"mail@gmail.com","phone":"777888"},
{"id":3,"firstName":"Bruno","lastName":"Dias","email":"mail@gmail.com","phone":"777888"},
{"id":4,"firstName":"No Accounts","lastName":"No name","email":"mail@gmail.com","phone":"777888"}]

var table = document.getElementById("table"); //Change Me

//create table header
var row = table.insertRow(-1);
Object.entries( incomingData
[0] ).forEach(entry => {        
    var headerCell = document.createElement("TH");
    headerCell.innerHTML = entry[0];
    row.appendChild(headerCell);
});

//populate
for(i=0; i<incomingData
.length; i++){
        var row = table.insertRow(-1);
        Object.entries( incomingData
        [i] ).forEach(entry => {        
            var cell = row.insertCell();
            cell.innerHTML = entry[1];
        });
    }
};
