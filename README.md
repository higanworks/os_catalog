# os_catalog

How does a human being detect platform by code ?


## references

- [Ohai plugins/platform](https://github.com/chef/ohai/tree/master/lib/ohai/plugins)
- [Specinfra helpers/detect_os](https://github.com/serverspec/specinfra/tree/master/lib/specinfra/helper/detect_os)

## Tree

names based on os-release:ID

```
├── README.md
├── darwin
│   └── 10.10
│       └── usr
├── linux
│   ├── amzn
│   │   ├── 2014.09
│   │   └── 2015.03
│   ├── centos
│   │   ├── 5
│   │   ├── 6
│   │   └── 7
│   ├── cloudlinux
│   │   └── 6
│   ├── coreos
│   │   └── stable
│   ├── rhel
│   │   └── 7
│   ├── sles
│   │   └── 12
│   ├── tinycore
│   │   ├── 5
│   │   └── boot2docker
│   └── ubuntu
│       ├── 10.04
│       ├── 11.04
│       ├── 12.04
│       └── 14.04
└── solaris
    ├── oracle
    │   └── 11
    └── smartos
        └── 13
```

## Contributing

1. Fork it ( https://github.com/[my-github-username]/os_catalog/fork )
2. Commit your collection (`git commit -am 'Add some platform'`)
3. Push to the branch (`git push`)
4. Create a new Pull Request

## License

MIT.

