# golang-security-action

## What is it ?

golang-security-action is nothing more than a github action letting you run [gosec](https://github.com/securego/gosec): 
* **when** you want (on push, pull_request, etc...)
* **where** you want (by specifying the input `CODE_PATH`)
* **How** you want (by specifying your gosec json config file, through the `CONF_PATH` input)

## Inputs

Here is the inputs that can be added on your workflow file

| Input name    | Required      | Description |
| ------------- | ------------- |-------------|
| CODE_PATH     | **true**      | used to specify "where" gosec will look at |
| CONF_PATH     | **false**     | referring to the path of the gosec config file|

**WIP** (see  [entrypoint.sh](https://github.com/Ynniss/golang-security-action/blob/master/entrypoint.sh) )

## Contribute

Any PR will be appreciated :) ! 

## License
This project is using [MIT License](https://github.com/Ynniss/golang-security-action/blob/master/LICENSE).

golang-security-action is using [**gosec**](https://github.com/securego/gosec), which is licensed under [Apache License 2.0](https://github.com/securego/gosec/blob/master/LICENSE.txt)
