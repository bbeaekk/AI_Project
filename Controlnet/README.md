

---
![image](https://github.com/bbeaekk/AI_Project/blob/main/%ED%94%84%EB%A1%AC%ED%94%84%ED%8A%B8%20%ED%85%8C%EC%8A%A4%ED%8A%B8/00003-3598288129.png?raw=true)

parameters

prompt
```
Digital painting of A female toddler with ibory dress sitting on garden with flowers eatting a cookie by Stanley Artgerm Lau, artstation, 8k, extremely detailed, ornate, cinematic lighting, vivid
```
Steps: 20, Sampler: DPM++ 2M Karras, CFG scale: 7, Seed: 3598288129, Size: 512x512, Model hash: 6ce0161689, Model: v1-5-pruned-emaonly, Version: v1.8.0

---



![image](https://raw.githubusercontent.com/bbeaekk/AI_Project/03d1fd01a818ae09fdbe034778b00812bb131184/%ED%94%84%EB%A1%AC%ED%94%84%ED%8A%B8%20%ED%85%8C%EC%8A%A4%ED%8A%B8/image%20(3).png)

### ADetailer 사용 전후

![image](https://raw.githubusercontent.com/bbeaekk/AI_Project/03d1fd01a818ae09fdbe034778b00812bb131184/%ED%94%84%EB%A1%AC%ED%94%84%ED%8A%B8%20%ED%85%8C%EC%8A%A4%ED%8A%B8/image.png)


parameter
```
masterpiece,best quality,1boy,office
Negative prompt: lowres, bad anatomy, bad hands, text, error, missing fingers, extra digit, fewer digits, cropped, worst quality, low quality, normal quality, jpeg artifacts, signature, watermark, username, blurry, rough sketch,nsfw
```
Steps: 20, Sampler: DPM++ 2M Karras, CFG scale: 7, Seed: 2046436878, Size: 512x512, Model hash: 2d34a470c1, Model: manmaruMix_v30, VAE hash: df3c506e51, VAE: kl-f8-anime2.ckpt, Version: v1.8.0

---
inpaint
---

![image](https://raw.githubusercontent.com/bbeaekk/AI_Project/fdb75f12f4672ac1ae2a0f820aefb41f16f6f552/%ED%94%84%EB%A1%AC%ED%94%84%ED%8A%B8%20%ED%85%8C%EC%8A%A4%ED%8A%B8/image_Inpaint.png)

![image](https://raw.githubusercontent.com/bbeaekk/AI_Project/fdb75f12f4672ac1ae2a0f820aefb41f16f6f552/%ED%94%84%EB%A1%AC%ED%94%84%ED%8A%B8%20%ED%85%8C%EC%8A%A4%ED%8A%B8/image_Inpaint2.png
)

---

---
i2i
---

![image](https://raw.githubusercontent.com/bbeaekk/AI_Project/373b41f590f885d21c1a977a0bf2f69bb46cfab3/%ED%94%84%EB%A1%AC%ED%94%84%ED%8A%B8%20%ED%85%8C%EC%8A%A4%ED%8A%B8/%EA%B7%B8%EB%A6%BC1.png
)

![image](https://raw.githubusercontent.com/bbeaekk/AI_Project/373b41f590f885d21c1a977a0bf2f69bb46cfab3/%ED%94%84%EB%A1%AC%ED%94%84%ED%8A%B8%20%ED%85%8C%EC%8A%A4%ED%8A%B8/%EA%B7%B8%EB%A6%BC2.png
)

---
# Control Net

## Scribble Image

lineart, white background, masterpiece, extremely detailed thick line drawing, 1girl, hoodie, animal gloves, skirt, sneakers
Steps: 20, Sampler: DPM++ 2M Karras, CFG scale: 7, Seed: 1280110377, Size: 512x512, Model hash: cbfba64e66, Model: counterfeitV30_v30, VAE hash: df3c506e51, VAE: kl-f8-anime2.ckpt, Denoising strength: 0.4, ADetailer model: face_yolov8n.pt, ADetailer confidence: 0.3, ADetailer dilate erode: 4, ADetailer mask blur: 4, ADetailer denoising strength: 0.4, ADetailer inpaint only masked: True, ADetailer inpaint padding: 32, ADetailer version: 24.3.2, ControlNet 0: "Module: scribble_pidinet, Model: control_v11p_sd15_scribble [d4ba51ff], Weight: 1, Resize Mode: Resize and Fill, Low Vram: False, Processor Res: 512, Guidance Start: 0, Guidance End: 1, Pixel Perfect: False, Control Mode: Balanced, Hr Option: Both, Save Detected Map: True", Mask blur: 4, Inpaint area: Only masked, Masked area padding: 32, Version: v1.8.0

![image](https://raw.githubusercontent.com/bbeaekk/AI_Project/ea63711e80097475bb1fc3e75be748bb3a66ada8/Controlnet/1.png)

![image](https://raw.githubusercontent.com/bbeaekk/AI_Project/ea63711e80097475bb1fc3e75be748bb3a66ada8/Controlnet/2.png)

![image](https://raw.githubusercontent.com/bbeaekk/AI_Project/745940d411bef9e9b8f624bd62f934b3f637fb51/%ED%94%84%EB%A1%AC%ED%94%84%ED%8A%B8%20%ED%85%8C%EC%8A%A4%ED%8A%B8/3ed863717eb290d3df169ebdb70df75e.png
)

![image](https://raw.githubusercontent.com/bbeaekk/AI_Project/745940d411bef9e9b8f624bd62f934b3f637fb51/%ED%94%84%EB%A1%AC%ED%94%84%ED%8A%B8%20%ED%85%8C%EC%8A%A4%ED%8A%B8/2.png
)
![image](https://raw.githubusercontent.com/bbeaekk/AI_Project/745940d411bef9e9b8f624bd62f934b3f637fb51/%ED%94%84%EB%A1%AC%ED%94%84%ED%8A%B8%20%ED%85%8C%EC%8A%A4%ED%8A%B8/1.png
)