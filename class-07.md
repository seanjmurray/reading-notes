# Reading-07

## Tables

In HTML you sometimes will want to show data as a table. You can build a a table to fit any data into it as needed.

        <table>
          <tr>
            <td></td>
            <td></td>
            <td></td>
          </tr>
        </table>

This would make a table with 1 row and 3 cells per row. you can have that content dynamically fill. You can use the colspan to fill make your cell span across multiple.  Rowspan will do the dame way but across rows.           
            
             <table>
               <tr>
                <td colspan="2"></td>
                <td></td>
                <td rowspan="2"></td>
              </tr>
              <tr>
                <td></td>
                <td></td>
                <td></td>
              </tr>
            </table>