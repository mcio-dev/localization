# L10n

English | [中文](/README-zh.md)

Localization configuration files for MrXiaoM's plugins.

## How to use

Clone the repository, and find the plugin and language you want via folder structure below.

```
- mcio-dev/localization
  |- PluginName
     |- XX-XX (Language code)
        |- config.yml
        |- messages.yml
```

For example, I am a English speaker. And I want language files of [SweetMail](https://github.com/MrXiaoM/SweetMail). So I need to check files in `SweetMail/en-us/`.

> [!WARNING]
> 
> Do NOT just replace files. Because they may not the latest configuration files. You may miss something if you just replace without checking submit date.
> 
> Excluding `messages.yml`, you can replace message files freely because they will update fallback message automatically.

## Contributing

PRs welcome.

Welcome to submit your language to this repository to help users who do not speak Chinese! We can work together to overcome language barriers.
