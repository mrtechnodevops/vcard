# vcard

issue not updating everyting 
go to folder /public/backend/js
change files admin-delete-query.js,user-delete-query.js
unction getUser(parameter) {
    "use strict";
    $("#status-modal").modal("show");
    var link = document.getElementById("user_id");
    link.getAttribute("href");
    link.setAttribute("href", '/vcard/public/admin/update-status?id=' + parameter);
