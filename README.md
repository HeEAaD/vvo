# 🚏VVO

This is a list of API endpoints, libraries, apps, tools and anything else what's available to access data in the [Verkehrsverbund Oberelbe](https://www.vvo-online.de/de) network. This includes the [Dresdner Verkehrsbetriebe](https://www.dvb.de/de-de/).

This document is inspired by [derhuerst/vbb-modules](https://github.com/derhuerst/vbb-modules).



## Static Data

- [`stations.csv`](https://raw.githubusercontent.com/kiliankoe/vvo/master/stations.csv) - A list of all stations including coordinates.




## APIs

- [`widgets.vvo-online.de`](http://widgets.vvo-online.de) - Built for the [VVO widgets](https://www.vvo-online.de/de/service/widgets/index.cshtml) - No known (public) documentation ([yet?](https://github.com/kiliankoe/vvo/wiki))
- [`webapi.vvo-online.de`](https://webapi.vvo-online.de) - New API used by the mobile page - No known (public) documentation ([yet?](https://github.com/kiliankoe/vvo/wiki))
- [`EFA`](http://efa.vvo-online.de:8080) - "Classic" interface for trip requests - No known (public) documentation ([yet?](https://github.com/kiliankoe/vvo/wiki))
- [`Trias`](http://trias.vvo-online.de:9000/middleware/data/trias) - Brand new and still in the process of being implemented afaik - "Documentation" [here](https://www.vdv.de/431-2sds-v1.1.pdfx?forced=true)



## Libraries

Client libraries for various languages, sorted roughly by their feature set. Although the names are specific to the DVB, most if not all of them are compatible with everything in the VVO network.

- [`dvbjs`](https://github.com/kiliankoe/dvbjs) - Client library for Node.js
- [`dvbpy`](https://github.com/kiliankoe/dvbpy) - Client library for Python
- [`dresdner-verkehrsbetriebe`](https://github.com/offenesdresden/dresdner-verkehrsbetriebe) - Client library for Haskell
- [`DVB`](https://github.com/kiliankoe/DVB) - Client library for Swift
- [`dvbrb`](https://github.com/kiliankoe/dvbrb) - Client library for Ruby
- [`dvbgo`](https://github.com/kiliankoe/dvbgo) - Client library for Go
- [`dvb-rs`](https://github.com/hoodie/dvb-rs) - Client library for Rust




## Apps

A handful popular and widely-used/known apps in Dresden at least.

- [`DVB mobil`](https://www.dvb.de/de-de/fahrplan/dvb-mobil/) - Official, cross-platform
- [`Faplino`](https://play.google.com/store/apps/details?id=de.faplino) - Android
- [`FahrInfo Dresden`](https://itunes.apple.com/de/app/fahrinfo-dresden/id314790387?mt=8) - cross-platform
- [`Öffi`](https://play.google.com/store/apps/details?id=de.schildbach.oeffi) - Android




## Tools, UIs & Experiments

- [`Magic Mirror`](http://blog.thomas-bachmann.com/2016/02/magic-mirror-2-0-mit-gestensteuerung.html) - Shows current departure data (using [`dvbpy`](https://github.com/kiliankoe/dvbpy))
- [`alfred_dvb`](https://github.com/kiliankoe/alfred_dvb) - [Alfred](https://www.alfredapp.com) workflow for departure data (using [`dvbgo`](https://github.com/kiliankoe/dvbgo))
- [`Amazon Echo`](https://twitter.com/ubahnverleih/status/830079491523358721) - Tweet [@ubahnverleih](https://twitter.com/ubahnverleih) for more info
- [`catch-my-bus-python`](https://github.com/meepoSenpai/catch-my-bus-python) - GTK3 StatusIcon showing current departure data




Got any more info, details, links? Please don't hesitate to open an issue and/or PR 🙃
