## Transformations in the Vertex Shader

This example applies a **scaling or rotation matrix** directly in the vertex shader.  
The transformation affects all vertices of the square uniformly, so the **entire square moves** without modifying the original vertex data in the VBO.  
This demonstrates how transformations can be applied on the GPU, keeping the vertex data unchanged on the CPU side.
