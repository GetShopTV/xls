This is a Haskell library to parse Microsoft Excel workbook files. It parses
the xls file format (extension `.xls`) more specifically known as
`BIFF/Excel 97-2004`.

It provides a Conduit based streaming API. See the haddock documentation
for the API details.

It also provides a utility `xls2csv` to convert xls spreadsheets to csv.

The library is based on the C library [libxls](http://libxls.sourceforge.net/).
