# Full Stack Apps on AWS Project

## Getting Started

To start the development server locally, run the following command.

```bash
npm run dev
```

It turns out that the service endpoint fails for the image url example which is provided in the course instructions. This is due to an error with the `jimp` library.
But you can test the endpoint with this other [image](http://localhost:8082/filteredimage?image_url=https://upload.wikimedia.org/wikipedia/commons/1/15/Welsh_Springer_Spaniel.jpg).

## Elastic Beanstalk environment

You can find the beanstalk deployment at this URL

[http://fbi-image-processing-dev.us-east-1.elasticbeanstalk.com/](http://fbi-image-processing-dev.us-east-1.elasticbeanstalk.com/)

And you can try the [endpoint](http://fbi-image-processing-dev.us-east-1.elasticbeanstalk.com/filteredimage?image_url=https://upload.wikimedia.org/wikipedia/commons/1/15/Welsh_Springer_Spaniel.jpg) with the same image.
