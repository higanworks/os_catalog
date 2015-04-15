# os_catalog

How does a human being detect platform by code ?


## references

- [Ohai plugins/platform](https://github.com/chef/ohai/tree/master/lib/ohai/plugins)
- [Specinfra helpers/detect_os](https://github.com/serverspec/specinfra/tree/master/lib/specinfra/helper/detect_os)

## Tree

d4dea3a3024002b54f6a0b7575aa1bfaa125f422

```
$ tree -L 3
.
├── README.md
├── darwin
│   └── 10.10
│       └── usr
├── linux
│   ├── amazon
│   │   └── 2014.09
│   ├── centos
│   │   ├── 5
│   │   ├── 6
│   │   └── 7
│   ├── cloudlinux
│   │   └── 6
│   ├── coreos
│   │   └── stable
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

