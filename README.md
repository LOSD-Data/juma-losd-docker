# Docker Juma Editor and Juma API (LOSD Version)

## Description

This is a docker image and files of the Juma Editor tool and Juma API that has been specialised for use in the LOSD publication platform.

## Usage

Build Image: ``docker image build -t juma_image .``

Run Container: ``docker run --name juma_container -p 8888:8888 -p8889:8889 -t juma_image``

- Juma Editor on port 8888

- Juma Api on port 8889

## License
This software is released under the [MIT license](http://opensource.org/licenses/MIT).

-----

## More information

Code based on the work developed by [Ademar Crotti Junior](https://www.scss.tcd.ie/~crottija/juma/).

To reference Juma please use the following:

A. Crotti Junior, C. Debruyne and D. O'Sullivan, "Juma Uplift: Using a Block Metaphor for Representing Uplift Mappings," 2018 IEEE 12th International Conference on Semantic Computing (ICSC), Laguna Hills, CA, 2018, pp. 211-218. Doi: 10.1109/ICSC.2018.00037.
