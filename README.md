<p align="center">
  <a href="https://www.perceptilabs.com">
  <img src="./pl_logo.png">
  </a>
</p>

# Weather Analysis Dataset
This dataset<sup>1</sup> contains 224x224-pixel images respresenting four different weather conditions: *cloudy*, *shine*, *sunrise*, and *rain*.

The data can be used to build and train an ML model that can determine weather conditions using image recognition. 

# Structure
This repo has the following structure:
* **/cloud**: images of scenes with cloudy skies.
* **/rain**: images of rainy scenes.
* **/shine**: images of sunny scenes.
* **/sunrise**: images of sunrises.
* **/weather_new_log.csv**: CSV file that enumerates the images for use in loading the data into PerceptiLabs. The enumerations are: cloud=0, rain=1, shine=2, sunrise=3.

The following shows a partial example of the data stored in the CSV file:

| image_path | target |
| ---------- | ------ |
| cloud/cloud_0.jpeg | 0 |
| rain/rain_208.jpeg | 1 |
| shine/shine_208.jpeg | 2 |
| sunrise/sunrise_212.jpeg | 3 |

# Community

Got questions, feedback, or want to join a community of machine learning practitioners working with exciting tools and projects? Check out our [Community](https://forum.perceptilabs.com/)!

<sup>1</sup> Dataset Credits: Ajayi, Gbeminiyi (2018), “Multi-class Weather Dataset for Image Classification”, Mendeley Data, V1, doi: 10.17632/4drtyfjtfy.1

