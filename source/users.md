# Users

## Projects Using libESMTP

libESMTP has been around for some time and, as well as being part of many Linux
distributions, it has been adopted by a number of projects. Some of those are
listed below. libESMTP is also available in [FreeBSD Ports][BSD].

### Balsa

[Balsa][BAL], a highly configurable email client for Gnome was an early adopter
of libESMTP and its primary author contributed to libESMTP's development. It
may be obtained from [https://pawsa.fedorapeople.org/balsa/][BAL].

### esmtp

[esmtp][ESM] is a fully `sendmail` command line compatible Mail Submission
Agent.  Although the original project hosted at [Sourceforge][ESM] is now
unmaintained, it is maintained in various distributions, for instance Debian at
[https://tracker.debian.org/pkg/esmtp][DEB].
The original website for esmtp is at [http://esmtp.sourceforge.net/][ESM].

### OpenWrt

libESMTP is available as part of the [OpenWrt][WRT] Libraries at
[https://openwrt.org/packages/index/libraries][WRL].

### linknx

[Linknx][LNX] is a service aimed at interacting with KNX home automation
devices. It features a value cache to save bus bandwidth and exposes a rules
engine allowing to automate actions based on powerful logical conditions and
timers.  The GitHub page for linknx is at
[https://github.com/linknx/linknx][LNX].

### collectd

The `notify_email` plugin of [collectd][COL] uses libESMTP:

[https://collectd.org/wiki/index.php/Plugin:Notify_Email][CNE]

### syslog-ng

The `afsmtp` module of [syslog-ng][SYS] uses libESMTP.

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
[LNX]: https://github.com/linknx/linknx
[SYS]: https://www.syslog-ng.com/
[WRL]: https://openwrt.org/packages/index/libraries
[WRT]: https://openwrt.org/
