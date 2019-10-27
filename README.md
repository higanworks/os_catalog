# os_catalog

How does a human being detect platform by code ?


## references

- [Ohai plugins/platform](https://github.com/chef/ohai/tree/master/lib/ohai/plugins)
- [Specinfra helpers/detect_os](https://github.com/serverspec/specinfra/tree/master/lib/specinfra/helper/detect_os)

## Tree

names based on os-release:ID

```
.
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
│   │   ├── 7
│   │   └── 8
│   ├── cloudlinux
│   │   └── 6
│   ├── coreos
│   │   └── stable
│   ├── debian
│   │   ├── 6
│   │   ├── 7
│   │   ├── 8
│   │   └── 9
│   ├── fedora_server
│   │   └── 29
│   ├── fedora_workstation
│   │   └── 30
│   ├── openSUSE
│   │   ├── 15
│   │   ├── 15.1
│   │   └── 42.3
│   ├── rhel
│   │   ├── 7
│   │   └── 8
│   ├── sles
│   │   ├── 12
│   │   ├── 12.1
│   │   ├── 12.2
│   │   ├── 12.3
│   │   ├── 15
│   │   └── 15.1
│   ├── sles_sap
│   │   ├── 12 -> 12.0.1
│   │   ├── 12.0.1
│   │   ├── 12.1 -> 12.1.0.1
│   │   ├── 12.1.0.1
│   │   ├── 12.2
│   │   └── 12.3
│   ├── tinycore
│   │   ├── 5
│   │   └── boot2docker
│   └── ubuntu
│       ├── 11.04
│       ├── 12.04
│       ├── 14.04
│       ├── 14.04.5
│       ├── 16.04.2
│       └── 18.04.1
├── README.md
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

