# Bounding Box Editor for Unity

The Bounding Box Editor is a Unity tool designed to streamline the process of editing bounding boxes for meshes in a prefab. This tool is especially useful for adjusting Skinned Mesh Renderers and Mesh Filters, allowing you to globally modify the center and extent of bounding boxes.

---

## Features
- **Global Adjustments**: Modify the center and extent of all bounding boxes under a selected prefab.
- **Supports Multiple Mesh Types**: Works seamlessly with both Skinned Mesh Renderers and Mesh Filters.
- **Batch Editing**: Adjust all meshes in a prefab simultaneously for consistency and efficiency.

---

## How to Use
1. **Import the Script**:
   - You can either directly add the `BoundingBoxEditor.cs` script to a folder named `Editor` in your Unity project, or import the `.unitypackage` file provided.

2. **Open the Tool**:
   - In the Unity Editor, navigate to `Tools > Bounding Box Editor`.

3. **Select a Prefab**:
   - Drag and drop the desired prefab into the tool's interface.

4. **Adjust Bounding Boxes**:
   - Modify the center and extent values in the tool to update all bounding boxes under the prefab.

---

## Requirements
- Unity 2020.3 or newer.
- A Unity project with prefabs containing Skinned Mesh Renderers or Mesh Filters.

---

## Example Use Case
Adjusting bounding boxes is critical for ensuring accurate collision detection, lighting, and other mesh-related operations. Use this tool to:
- Optimize bounding boxes for imported prefabs.
- Standardize bounding box dimensions across multiple meshes.

---

## Contributing
Contributions, issues, and feature requests are welcome! Feel free to fork the repo and submit pull requests.

---

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
