# MySQL-DB-Connector
Library for simpler and easier MySQL database actions

# Classes:
 - DatabaseConnectionFacade (For handling connection)
 - DatabaseReadFacade (For handling reading from table)
   
   - CellReader (For cell related reading)
     - ReadCellValue
     - ReadCellColumnType
     - IsCellNull
     - ReadCellValueAsync
     - ReadCellColumnTypeAsync
     - IsCellNullAsync
   
   - RowReader (For row related reading)
     - ReadRowValues
     - ReadRowColumnTypes
     - ReadRowValuesAsync
     - ReadRowColumnTypesAsync
   
   - ColumnReader (For column related reading)
     - GetColumnCount
     - GetColumnCountAsync
   
   - TableReader (For table related reading)
     - ReadTable (out columns, rows, columnTypes or as DataTable)
     - GetRowCount
     - ReadTableAsync
     - GetRowCountAsync
    
 - DatabaseWriteFacade (For handling writing from table)
   
   - Writer (For custom writing methods)
     - Query
     - QueryAsync
   
   - CellWriter (For cell related writing)
     - UpdateCell
     - InsertCell
     - UpdateCellAsync
     - InsertCellAsync
   
   - RowWriter (For row related writing)
     - UpdateRow
     - InsertRow
     - RemoveRow
     - UpdateRowAsync
     - InsertRowAsync
     - RemoveRowAsync
