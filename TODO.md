# TODO

- Extend to 3D as per https://www.youtube.com/watch?v=ih20l3pJoeU
- End to panning & zoomon as per https://www.youtube.com/watch?v=ZQ8qtAizis4
  and https://www.youtube.com/watch?v=a8rM-CXBfK8 
- Use SDL_RenderLogicalSize to set device independent resolution for rendering.
  Makes SDL takes care of scale as window is resize
- Move methods in Transform2D.cs into Matrix2D and do Matrix2D.Rotation(theta) *
  Matrix2D.Scaling(size) and so on. These methods are static with overloaded *.
- Don't make individual points matrices. These should be vectors (so vector *
  matrix).
- Investigate new .NET 6/C# "static abstracts in interfaces" feature in relation
  to Matrix class. Does it allow using the Matrix class with int, double, float?