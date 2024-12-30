# Sample of SSS based on LabPBR with MollyVX-Extension + texture pack

MollyVX implements SSS(subsurface scattering) for plants as internal process of the shader. This does not support anything other than plants.  
When turn ON Resource_Pack_SSS in the MollyVX-Extension settings, SSS based on LabPBR supplied by the texture pack will be enabled.

- non SSS (SubSurfaceScattering = OFF) with texture pack 'Groovy'  
  <img src="image/sss_sample/oak_groovy_sssOFF.jpg" height="300" align="top"> <img src="image/sss_sample/bamboo_groovy_sssOFF.jpg" height="400" align="top">  
- SSS by internal process of shader (*Default: SubSurfaceScattering = ON and Resource_Pack_SSS = OFF) with texture pack 'Groovy'  
  <img src="image/sss_sample/oak_groovy_internalsss.jpg" height="300" align="top"> <img src="image/sss_sample/bamboo_groovy_internalsss.jpg" height="400" align="top">  
- SSS based on LabPBR (SubSurfaceScattering = ON and Resource_Pack_SSS = ON) with texture pack 'Groovy'  
  <img src="image/sss_sample/oak_groovy_LabPBRsss.jpg" height="300" align="top"> <img src="image/sss_sample/bamboo_groovy_LabPBRsss.jpg" height="400" align="top">  
- Default (SubSurfaceScattering = ON and Resource_Pack_SSS = OFF) with texture pack 'HardTop-Vanillaccurate'  
  <img src="image/sss_sample/calcite_HardTop_default.jpg" height="400" align="top">  
- SSS based on LabPBR (SubSurfaceScattering = ON and Resource_Pack_SSS = ON) with texture pack 'HardTop-Vanillaccurate'  
  <img src="image/sss_sample/calcite_HardTop_LabPBRsss.jpg" height="400" align="top">  
