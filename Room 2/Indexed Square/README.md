## Render a Square with an Index Buffer (EBO)

This example defines **4 unique vertices** and uses an **Element Buffer Object (EBO)** with indices `[0, 1, 2, 0, 2, 3]` to draw two triangles.  
By referencing vertices through indices, the square is rendered **without repeating vertex data**, making the process more efficient.  
This demonstrates how EBOs help reduce duplication and optimize rendering.
