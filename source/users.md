# Users

## Projects Using libESMTP

libESMTP has been around for some time and, as well as being part of many Linux
distributions, it has been adopted by a number of projects. Some of those are
listed below. libESMTP is also available in [FreeBSD Ports][BSD].

### Balsa

[Balsa][BAL], a highly configurable email client for Gnome was an early adopter
of libESMTP and its primary author contributed to libESMTP's development.

### Apache Log4cxx

[Log4cxx][L4C] uses libESMTP since version 0.10.  Apache Log4cxx is a C++ port
of Apache Log4j.

### Sagan

[Sagan][SAG] is a log analysis engine. It was designed with a Security
Operations Center (SOC) in mind.

### esmtp

[esmtp][ESM] is a fully `sendmail` command line compatible Mail Submission
Agent.

Although the original project hosted at [Sourceforge][ESM] is now unmaintained,
it is maintained in various distributions, for instance [Debian][DEB].

### OpenWrt

libESMTP is available as part of the [OpenWrt][WRT] project's [Libraries][WRL].

### linknx

[Linknx][LNX] is a service aimed at interacting with KNX home automation
devices.

### collectd

The [notify_email][CNE] plugin of [collectd][COL] uses libESMTP.

### syslog-ng

The `afsmtp` module of [syslog-ng][SYS] uses libESMTP.

### Net::ESMTP

[Net::ESMTP][POD] wraps libESMTP for Perl.

### libESMTP for Vicare

[libESMTP for Vicare][VIC] wraps libESMTP for Vicare Scheme.

----

Please leave a comment on [issue #2][ISS] if your project uses libESMTP,
preferably with a link to the project web site. It's always good to know that
this work is useful to the community.


[BAL]: https://pawsa.fedorapeople.org/balsa/
[BSD]: https://www.freebsd.org/ports/
[CNE]: https://collectd.org/wiki/index.php/Plugin:Notify_Email
[COL]: https://collectd.org/
[DEB]: https://tracker.debian.org/pkg/esmtp
[ESM]: http://esmtp.sourceforge.net/
[ISS]: https://github.com/libesmtp/libESMTP/issues/ESM
[L4C]: https://logging.apache.org/log4cxx/latest_stable/
[LNX]: https://github.com/linknx/linknx
[POD]: https://metacpan.org/dist/Net-ESMTP/view/ESMTP.pod
[SAG]: https://github.com/quadrantsec/sagan
[SYS]: https://www.syslog-ng.com/
[VIC]: https://marcomaggi.github.io/docs/vicare-libesmtp.html
[WRL]: https://openwrt.org/packages/index/libraries
[WRT]: https://openwrt.org/
