# dump1090-fa (BPFV version) Debian/Raspbian packages

This is a fork of [dump1090-fa](https://github.com/FlightAware/dump1090)
customized for use within [BPFV](http://bpfv.net)'s
[SkyMon](http://skymon.bpfv.de) software.

It is designed to build as a Debian package.

## Building and installation

```bash
sudo bash -c "$(wget -O - https://raw.githubusercontent.com/MartinRusk/dump1090/master/install-dump1090-fa.sh)"
```

### Dependencies - bladeRF

bladeRF support is disabled by default

### Dependencies - rtlsdr

rltsdr support is enabled by default
