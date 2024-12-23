# Level Design page

- Video [here](https://youtu.be/dV6S_11pyzo?si=87iaPPxGVMHSu4yb)
- Graveyard kit [here](https://kenney.nl/assets/graveyard-kit)

## Instructions

To set texture in CSGBox => NewStandardMaterial => Albedo -> Drag and drop to set photo in the texture. Image repeat in UV1.


## Formats

GLB (GL Transmission Format Binary) - A binary version of GLTF: open-source, Efficiently delivering 3D content over the web

- Encodes geometry, textures, animations, and materials in a single binary file
- Optimized for web and mobile applications, compact size
- works the best with godot

FBX (Filmbox): gaming, animation

- proprietary, transfer files between 3D software (like Maya, Blender, and 3ds Max)
- Supports animation (skeletons, rigging, keyframes, and morph targets).
- Complex hierarchical data support (e.g., multiple objects and animations in one file)

OBJ

- An open-source format, used for simple geometry storage and exchange.
- Stores vertex data, normals, texture coordinates, and polygon information.
- Supports geometry only, with basic material definitions through companion .mtl files.
- High compatibility with 3D modeling software.
- Often larger than GLB for simple geometry due to verbosity.

Here is the table in Markdown format:

### Comparison Summary

|                         |                                |                        |                          |
| ----------------------- | ------------------------------ | ---------------------- | ------------------------ |
| Feature                 | FBX                            | GLB                    | OBJ                      |
| **Animation Support**   | Full (rigging, keyframes)      | Full                   | None                     |
| **Material Support**    | Basic & Advanced               | Advanced (PBR support) | Basic                    |
| **Texture Embedding**   | Partial (external or internal) | Fully embedded         | Linked via `.mtl` file   |
| **File Size**           | Larger                         | Compact                | Moderate (verbose ASCII) |
| **Real-Time/AR/VR Use** | Moderate                       | Ideal                  | Limited                  |
| **Compatibility**       | Broad (proprietary)            | Wide (open standard)   | Extremely broad (simple) |

