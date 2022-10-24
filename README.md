# stable-diffusion-webui-inspiration
This an extension for [stable-diffusion-webui](https://github.com/AUTOMATIC1111/stable-diffusion-webui)

Randomly display the pictures of the artist's or artistic genres typical style,  more pictures of this artist or genre is displayed after selecting .
So you don't have to worry about how hard it is to choose the right style of art when you create
![image](https://s6.jpg.cm/2022/10/22/PJYoNL.png)
you can filter artist's or  genres by keyword, collect the style to faveries, or shield the style you don't like.
you can also send the style name to the txt2img or img2img prompt. 

All the pictures is created by a script  named  "Create inspiration images" in txt2img page, the artists and  genres names come from the repository:
https://github.com/pharmapsychotic/clip-interrogator/tree/main/data

There about 6000 artists and art styles in these files. This takes server hours depending on your GPU type and how many pictures  you generate for each artist/style

You can also download generated pictures from here:

https://huggingface.co/datasets/yfszzx/inspiration

## Install
go to directory \<stable-diffusion-webui project path\>/extensions , run command:

`git clone https://github.com/yfszzx/stable-diffusion-webui-inspiration `

and restart your stable-diffusion-webui, then you can see the new tab "Inspiraion"

Run the "Create inspiration images" script in page "txt2img" to create images.

Or download zip file from [here](https://huggingface.co/datasets/yfszzx/inspiration/resolve/main/inspiration.zip) ,unzip this file to:

\<stable-diffusion-webui project path\>/extensions/stable-diffusion-webui-inspiration

 and restart webui, and enjoy the joy of creation!

 [See here for more install details]( https://github.com/AUTOMATIC1111/stable-diffusion-webui/wiki/Extensions)


