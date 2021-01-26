# ServerspecStudy
Studying is fun for me. Serverspec.

## Install

```
bundle install --path vendor/bundle
bundle exec serverspec-init
```

## Prepare

### sudo password set to environment variable

```
export SUDO_PASSWORD=xxxxxxxx
```

## Testing

```
bundle exec rake
```

## Results

```

Package "httpd"
  is expected to be installed

Service "httpd"
  is expected to be enabled
  is expected to be running

Port "80"
  is expected to be listening

Finished in 1.76 seconds (files took 9.66 seconds to load)
4 examples, 0 failures
```


# Reference Link

## My Notion's Page

https://www.notion.so/yusukeono/Serverspec-3cf796df5ee94e118774cd30fb938162
