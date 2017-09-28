monitor
=======

The new Cuckoo Monitor. [Click here for documentation][docs].
If at first it doesn't compile, just try a second time!

Note that you'll need the `pyyaml` package, which may be installed as follows:
`pip install pyyaml`.

[docs]: http://cuckoo-monitor.readthedocs.org/en/latest/

running
=======

symbolic link into `$CWD/monitor/systaint`, then submit analysis using the parameter `--options='monitor=systaint'`