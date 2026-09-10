# Conor Manning's Resume

My resume, as code and tracked in git.


## Why?
I was complaining about having to keep up with source file documents when updating a resume and was trying to think of a better way to maintain and then I found [YAMLResume](https://yamlresume.dev/) and fell in love.

It seemed like a perfect fit for someone who worked as a DevOps Engineer. 


### Prerequisites
If you are just looking for my resume to look at, then you need not go any further. A current version of ![my resume](./current.pdf) can be found in this repository.

If you came to snoop and would like to build my resume yourself, then you will either need one of the following:
- Docker V23 or higher
- [Task](https://taskfile.dev/)
- This repository
```
git clone https://github.com/conorwithonen/cv.git conormanning-cv
cd conormanning-cv
```

### Building via Task

1. Run build
```sh
task build
```
This will generate a new PDF file in ./output/ with the format `conor-manningYYYYMMDD.pdf` that can be opened in your favorite pdf viewer.

## Validating the Resume YAML

Explain what these tests test and why

```sh
task validate
```


## Deployment

- TODO: Github pipeline to update the `current.pdf` on merge.

## Built With

* [YAMLResume](https://yamlresume.dev/) - The predominate bulk of this project
* [Task](https://taskfile.dev/) - Make substitute from my normal workflow


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Current Resume
![Current Resume](./current.pdf)
