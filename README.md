# pi-compute-device

A portable device built with the Raspberry Pi Compute module.

## Installation

The schematics project is done in KiCad, free and available to most common
platforms. More information on how to download and install KiCad can be found in
its [official download page][download-kicad].

## Usage

Clone the sources and browse the package folder. The KiCad project is located in
`kicad-project/pi-compute-device.pro`.

```bash
git clone https://github.com/marcbperez/pi-compute-device
cd pi-compute-device
```

## Testing

There is no testing in place for this project yet.

## Troubleshooting

The [issue tracker][issue-tracker] intends to manage and compile bugs,
enhancements, proposals and tasks. Reading through its material or reporting to
its contributors via the platform is strongly recommended.

## Contributing

This project adheres to [Semantic Versioning][semver] and to certain syntax
conventions defined in [.editorconfig][editorconfig]. To get a list of changes
refer to the [CHANGELOG][changelog]. Only branches prefixed by *feature-*,
*hotfix-*, or *release-* will be considered:

  - Fork the project.
  - Create your new branch: `git checkout -b feature-my-feature develop`
  - Commit your changes: `git commit -am 'Added my new feature.'`
  - Push the branch: `git push origin feature-my-feature`
  - Submit a pull request.

## Credits

This project is created by [marcbperez][author] and maintained by its
[author][author] and contributors.

## License

This project is licensed under the [Apache License Version 2.0][license].

[author]: https://marcbperez.github.io
[issue-tracker]: https://github.com/marcbperez/pi-compute-device/issues
[editorconfig]: .editorconfig
[changelog]: CHANGELOG.md
[license]: LICENSE
[semver]: http://semver.org
[download-kicad]: http://kicad-pcb.org/download/
