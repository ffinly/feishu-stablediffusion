# Feishu-Stablediffusion
🎭 由stablediffusion赋能的飞书图片生成类机器人

## Refer

-  [Hugging Face](https://huggingface.co/runwayml/stable-diffusion-v1-5)

```sh
curl https://api-inference.huggingface.co/models/runwayml/stable-diffusion-v1-5 \
	-X POST \
	-d '{"inputs": "Astronaut riding a horse"}' \
	-H "Authorization: Bearer api_org_xxxxxx"
```

1. 通过正反prompt生成图片；
2. 可以选择model（常用风格代表）；
3. 可以设置生成图片的size、step与seed；
4. 每张图片自带基本生成信息；

后续看时间加入img2img, controlnet等功能
