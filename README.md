# GoogleDrive


[![Build Status](https://travis-ci.com/tejasvaidhyadev/GoogleDrive.jl.svg?branch=master)](https://travis-ci.org/tejasvaidhyadev/GoogleDrive.jl)


## Introduction
GoogleDrive.jl provides support for downloading files from Google-Drive on top of Datadeps.

### Installation
The package can be installed by cloning git repo in .julia/dev/
```julia
~/.julia/dev> git clone <fork_repo_URL>
```


## Details

### `drive_download`

    `drive_download(URL, localdir)`


Download flie from Google drive.
The above function only Download file from google drive.

### `sheet_handler`
    
    `sheet_handler(long_url)`

Provide URL that can be use as link for registering in Datadeps

### `google_download`
     
    `google_download(URL, localdir)`
    
The function can be used to download file from google-drive,goole-sheets and HTTP downlaod method 

## Configuration
This package is build on top of [DataDeps.jl](https://github.com/oxinabox/DataDeps.jl).
To configure, e.g., where downloaded files save to, and read from (and to understand how that works),
see the DataDeps.jl readme.