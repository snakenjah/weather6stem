When using ParallaxMapping or CreateNormalChannel, be sure to set Sampler 
State otherwise there will be errors

If you use HDRP, import the file " LightDirectionForHDRP.UnityPackage"

Node "SSS" for "AmplifyShaderEditor" you can import from file 
"SSS_For_AmplifyShaderEditor" in folder " Nodes"

In version 4 or higher, there are bugs with variables float and color,
these nodes are not associated with these errors, if you remove all the 
variables "float" and "Gradient" then there will be no errors. We are waiting 
for the Shader graph developers to fix these errors.

!!! If the material becomes pink or does not work properly, open the shader
in the Shader Graph and click Save, the problem disappears