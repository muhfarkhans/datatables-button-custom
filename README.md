# Datatables Button Custom

## List new

1. Format cell to Rupiah (IDR)
   using **68** as a style code
   ex usage:

   ```js
   customize: function (xlsx, row) {
       var sheet = xlsx.xl.worksheets['sheet1.xml'];
       $('row c[r^="E"]', sheet).attr('s', 68);
   }
   ```
