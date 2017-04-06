# url-loader-flow
A flow-friendly module that represents a URL Loader.

## Installation

```
npm install url-loader-flow
```

## Usage

This is not intended to be imported into any project, but instead referenced in one's `.flowconfig` file.

```
[options]
module.name_mapper='^.*\.svg$' -> 'url-loader-flow'
```

This can be used with any URL Loader module format such as `.svg`, `.jpg`, or `.png`
