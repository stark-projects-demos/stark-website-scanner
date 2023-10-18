# https://www.getstark.co Accessibility checker
This is a demo github project that shows how to run stark's accessibility scanner against your live website without the need of building a local project. This uses our github action which can be found [here](https://github.com/marketplace/actions/stark-accessibility-checker). 

We used a crawler to get hold of all the urls for our website and simply passed it to the `.github/workflows/starkflow.yml` file. 

We have a project on the Stark Web App and we continuously monitor accessibility issues for our website in this way. 

P.s A direct url scanner is on its way, and ways to run the cli locally with API tokens is also on its way. But till then, this solution works. 