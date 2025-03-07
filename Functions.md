## Intro

## Material
### Standard
Metallic-Roughness Workflow
- BaseColor
- Metallic
- Roughness
- Emission
  - emission: emission color
  - emissionMap: map of emission 
- Alpha
- NormalMap
- Ior: index of refraction
- Transmission: extension
  > Note: specular refract of dielectric part
  - [ ] Note: Unfinished! No implement for raster and ray. As for path, we just use a trick way
  - transmission: transmission strength
  - transmissionMap
- Clearcoat: extension
  > Note: ior of coat is 1.5, so f0 is 0.04
  - clearcoat: coat strength
  - clearcoatRoughness
  - clearcoatNormal: normalMap of coat
- [ ] Sheen
- [ ] DiffuseTransmission
  > Note: fake SSS for standard material 

### Anisotropy
- [ ] Note: Unfinished! Need check for raster and ray for IBL. And for path, have not checked!
- Anisotropy
- AnisotropyDirection

### Irridescence
- [ ] Note: Unfinished! Need check for raster and ray for IBL. And for path, have not checked!
- Irridescence: irridescence strength
- IrridescenceMap
- IrridescenceIor
- IrridescenceThicknessMax
- IrridescenceThicknessMin
- IrridescenceThicknessMap
  
### Cloth
- [ ] Undo
  
### SSS
- [ ] Undo
  
### Hair
- [ ] Undo

## Lights
### HDR
- color
- factor
- [ ] direction
  
### Sun
> Note: Alse direction light, only one sun for scene
- direction
- color
- factor

### Point
- position
- color
- factor

### Spot
- [ ] Undo

### Area
- [ ] Undo

### IES
- [ ] Undo

## Shade
### Raster
- Opacity
- Transparent
- Skybox
- [ ] TAA

### Ray
- Opacity
- [ ] Transparent
- Shadow
- AO
- [ ] Denoise
  
### Path
- Opacity
- [ ] Transparent
- Shadow
- [ ] Firefly & Denoise

### Overlay
- Highlight 
- [ ] light & camera
- [ ] AABB
- [ ] ...


## Model
### gltf/glb
