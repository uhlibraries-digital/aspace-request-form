# ArchivesSpace Request Form

A [ArchivesSpace](https://github.com/archivesspace/archivesspace) plugin to add a custom message to the request form

## Install

Please make backups of all your plugins before installing. It is assumed you have the latest version of ArchivesSpace already installed.

Installation:

1) Download the Request Form plugin

```
$ cd /path/to/archivesspace/plugins
$ git clone https://github.com/uhlibraries-digital/aspace-request-form.git request-form
```

2) Update ArchivesSpace `config/config.rb` and add `request-form` to `AppConfig[:plugins]`. You might have to uncomment this line (remove `#`) if this is the first time installing a plugin. [Read more](http://archivesspace.github.io/archivesspace/user/archivesspace-plug-ins-readme/) about ArchivesSpace Plugin-ins.

```
AppConfig[:plugins] = ['request-form']
```

3) Restart ArchivesSpace

## Development

Information on making plug-ins for ArchivesSpace is at http://archivesspace.github.io/archivesspace/user/archivesspace-plug-ins/.

## Contributing

When contributing to this repository, please first discuss the change you wish to make via issue, email, or other method with the Digital Asset Management Team before making a change.

### Pull Request Process

1) Fork this repository before making any changes
2) Ensure you have pulled changes from this repository, or upsteam, if you have previously forked this repository
3) Ensure that any local development dependencies are removed
4) Make a pull request to this repository
5) Notify the Digital Asset Management Team a pull request was made with the change