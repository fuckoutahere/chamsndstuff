# chamsndstuff for critical ops
first step download uabea https://github.com/nesrak1/UABEA
download dec version of critical ops
go to payload-.app-data-raw-assetbun--shaders
open shaders on uabea
heres the list of found stuff from before
shader docc.
particles_smokesphere.shader (outside layer of smoke)
pure_pbs.shader (hand chams)
pure_pbs_highlighted.shader (PLAYER CHAMS)
environment_lightmapped.shader (WALLS)
overlay_color.shader (flash) 
pure_pbs_alphaspec.shader (gun/knife chams)
particles_tracer.shader (gun tracer/bullet)
particles_alphablend.shader (inside layer of smoke)
skybox.shader (skybox)
for chams edit pure_pbs_highlighted.shader, set ztest from 4 to 8, set LOD from 0 to 1000, set culling from 2 to 0, set Geometry in commas to overlay, also to be safe zwrite and zclip to 0.
compress to lz4 and place back
![image](https://github.com/user-attachments/assets/8d41aba9-222f-4ff1-9c1a-dc013fe7668f)
how i got rid of grenades was by deleting them but you can also change values for there to not be a big diff to anti
"DELETE overlay_color.shader, particles_alphablend.shader, and particles_smokesphere.shader." 
you will need to find new stuff like molys etc.
