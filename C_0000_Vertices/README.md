# Vertices

## Vertex Creation

Vertex creation requires at least one object to be in the scene because if an object is not selected, then you cannot enter **Edit Mode** to create new vertices. Also neither the "Add" list in Object Mode nor Edit Mode contains a "Vertex" option.

To create a single vertex from an Object/Mesh, enter **Edit Mode** and then select everything and then use the **Merge** operation.

While in **Edit Mode** with nothing selected, use `CTRL MOUSE-RIGHT` to create a vertex.

## Vertex Extrusion

### Extrude
NA

### Repeat

Properties:

  - Steps
  - Offset (X, Y, Z)
  - Scale Offset

### Spin

- Steps
- Use Duplicates
- Angle
- Auto Merge
- Flip Normals
- Center (X, Y, Z)
- Axis (X, Y, Z)

> NOTE: At least one Axis component must be a non-zero value even if it is a really small number.

**Create a Circle from Spin**

- Create a single vertex at the location (0, -1, 0)
- Select the vertex 
- Use the Spin operation with the properties:
  - Angle = 360

## Auto Merge

    Activate Tool and Workspace Settings > Options > Auto Merge

See 3DView_AutoMerge.png

# Further Reading
- [Modeling > Meshes > Editing > Vertex Tools](https://docs.blender.org/manual/en/latest/modeling/meshes/editing/vertex/index.html)

