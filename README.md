# Image classifier on [Render](https://render.com) :bear:

This repo can be used as a starting point to deploy [fast.ai](https://github.com/fastai/fastai) models on Render.

Check my image classifier at https://fastai-v3.onrender.com. Test it out with bear images!

You can test your changes locally by installing Docker and using the following command:

```
docker build -t fastai-v3 . && docker run --rm -it -p 5000:5000 fastai-v3
```

## Othe resources

The guide for production deployment to Render is at https://course.fast.ai/deployment_render.html.

Please use [Render's fast.ai forum thread](https://forums.fast.ai/t/deployment-platform-render/33953) for questions and support.
