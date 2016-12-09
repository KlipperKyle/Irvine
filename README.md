Irvine
========

Irvine is an experiment in minimalist GTK theming.

The GTK2 theme is for the most part done.  Up next: GTK 3.18 version.

Goals:

* Old-school look.  Prefer boxes and flat colors over curves and gradients.
* Take inspiration from Motif, NeXTSTEP, OneStepBack, and KDE's Phase theme
* Diamond-shaped radio boxes
* "Funky" scrollbar buttons
* Self-contained.  There should be no compiled theme engines.

Configurations I wish to support:

	| Y | Distro           | gtk2      | gtk3        | qt        |
	|---|------------------|-----------|-------------|-----------|
	| Y | Slackware 14.2   | 2.24.31   | 3.18.9      | 4.8.7     |
	| Y | Fedora 25        | 2         | 3.22.2 (?)  | 5.7.0 (?) |
	|   | Arch             | 2         | 3.22.2      | 5.7.0     |
	| Y | RHEL/CentOS 7    | 2         | 3.14.13 (?) | 4.8.5 (?) |
	|   | Ubuntu 16.10     | 2         | 3.20.3      | 5.6.1     |
	| Y | Ubuntu 16.04     | 2         | 3.18.9      | 5.5.1     |
	|   | Ubuntu 14.04     | 2         | 3.10.8      | 5.2.1     |
	|   | RHEL/CentOS 6    | 2.24.23   | ---         | 4.6.2     |

Things I do not want to support:

* Client-side window decorations
* GNOME 3 (changes too fast, and I don't use it)
