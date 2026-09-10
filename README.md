

# GAME_PROGRAM-EX--1
# EXP:1 Implementing various effects in a material such as emissive, roughness and metallic properties in Unreal Engine

## Aim
To implement and demonstrate various material effects in Unreal Engine, including emissive, roughness, and metallic properties, using the Material Editor.

## Procedure

1. **Create a New Material:**
   - Open Unreal Engine.
   - In the Content Browser, right-click and select **Material**.
   - Name it `M_EffectsDemo`.

2. **Apply Base Color:**
   - Open the material.
   - Add a **Vector Parameter** or **Constant3Vector** node and connect it to the **Base Color** input.

3. **Add Emissive Effect:**
   - Add a **Multiply** node.
   - Connect a **Constant3Vector** (for emissive color) and a **Scalar Parameter** (for intensity).
   - Connect the result to the **Emissive Color** input.

4. **Control Roughness:**
   - Add a **Scalar Parameter** node and connect it to the **Roughness** input.
   - Lower values = shinier surface, higher values = rougher surface.

5. **Control Metallic Property:**
   - Add a **Scalar Parameter** node and connect it to the **Metallic** input.
   - 0 = non-metal, 1 = fully metallic.

6. **Save and Apply Material:**
   - Save the material.
   - Apply it to any mesh in the scene (like a sphere or cube) to preview the results.
  
     
## Output

<img width="1011" height="806" alt="Screenshot 2026-09-09 151036" src="https://github.com/user-attachments/assets/e77c3bd1-393e-4630-a00b-cd789506b246" />
<img width="1033" height="683" alt="Screenshot 2026-09-09 151047" src="https://github.com/user-attachments/assets/be15fe1e-de46-49fc-8338-d7296e5c6081" />



## Result
Successfully implemented a material in Unreal Engine showcasing:
- Emissive glow using emissive color and intensity.
- Variable surface roughness to simulate different textures.
- Metallic appearance adjustment to reflect light like real-world metals.

This setup enables dynamic, realistic materials suitable for use in environments, characters, and VFX in Unreal Engine projects.

