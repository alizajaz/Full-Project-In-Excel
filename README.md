# Full-Project-In-Excel
Select All>Filter>Data Clean up time
1.DATA>REMOVE DUPLICATE 
2. Marital Status> Changing from M and S to Married and Single.
Select All>Ctrl h>replace M AND S with Married and Single.
For Income column>home>currently >tab to remove 0
For Age column>Insert new column first 
For AgeBracket=IF(L2<31,"Adolescent","Invalid")
=IF(L2>55,"Old",IF(L2>=31,"Middle Age",IF(L2<31,"Adolescent","Invalid")))
Pivot Table
1.make new sheet>rename Pivot Table>Analyze>pivot table>click one cell>go back to sheet (bike_buyer) select all>you can see pivot table sheet in new page 
