![image](https://github.com/user-attachments/assets/4969c74c-2f99-4cec-8208-831246db321c)# EXP-01: Implementing various effects in a material such as emissive, roughness and metallic properties in Unreal Engine.
## Date: 5/3/25
## Aim:
To implement various effects in a material such as emissive, roughness and metallic
properties in Unreal Engine.

## Procedure:
1.Create a New Material:
Open Unreal Engine.
In the Content Browser, right-click and select Material.
Name it M_EffectsDemo.
Apply Base Color:

2.Open the material.
Add a Vector Parameter or Constant3Vector node and connect it to the Base Color input.
Add Emissive Effect:

3.Add a Multiply node.
Connect a Constant3Vector (for emissive color) and a Scalar Parameter (for intensity).
Connect the result to the Emissive Color input.

4.Control Roughness:
Add a Scalar Parameter node and connect it to the Roughness input.
Lower values = shinier surface, higher values = rougher surface.

5.Control Metallic Property:
Add a Scalar Parameter node and connect it to the Metallic input.
0 = non-metal, 1 = fully metallic.

6.Save and Apply Material:
Save the material.
Apply it to any mesh in the scene (like a sphere or cube) to preview the results.

## Output:
![image](https://github.com/user-attachments/assets/0f63ce05-46de-41ad-8e29-2a875b99d853)

![image](https://github.com/user-attachments/assets/cb1d4804-767b-4ba3-96f0-92f5b4b177d2)


## Result:
Implementing various effects in a material such as emissive, roughness and metallic properties in Unreal Engine was done successfully.
