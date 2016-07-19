[![Build Status](https://travis-ci.org/zezutom/proxy-log-generator.svg?branch=master)](https://travis-ci.org/zezutom/proxy-log-generator)
[![Coverage Status](https://coveralls.io/repos/github/zezutom/proxy-log-generator/badge.svg)](https://coveralls.io/github/zezutom/proxy-log-generator)
# Proxy Log Generator
This is based on a simple Python script which generates a fake web server log. Unsurprisingly, the script comes with a bunch of configuration options allowing to control data volumes and variety. The project has been inspired by some outstanding examples, see Resources for details. 

## Example Output
```
2016-07-15 22:34:48	181.42.40.22	Mozilla/5.0 (Macintosh; Intel Mac OS X 10_11_5) AppleWebKit/601.6.17 (KHTML, like Gecko) Version/9.1.1 Safari/601.6.17	clay.richard	http://www.raymondelliott.com/659.html	200	2718553
2016-07-15 22:40:36	58.75.187.70	Mozilla/5.0 (Windows NT 6.3; WOW64; rv:47.0) Gecko/20100101 Firefox/47.0	elisa.wilcox	https://www.kendall-sparks.com/839/193/287/766.jpg	302	986709
2016-07-15 22:46:29	104.213.217.249	Mozilla/5.0 (Macintosh; Intel Mac OS X 10_11_5) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/51.0.2704.84 Safari/537.36	thomas.henry	http://www.erika-hatfield.com/327/711/168/786.php	404	1822779
2016-07-15 22:52:00	7.46.154.248	Mozilla/5.0 (X11; Linux x86_64; rv:45.0) Gecko/20100101 Firefox/45.0	latasha.byers	https://www.shaun-dyer.com/888/187/252/296.jpg	200	4580341
2016-07-15 22:57:46	177.111.138.63	Mozilla/5.0 (Macintosh; Intel Mac OS X 10_10_5) AppleWebKit/601.6.17 (KHTML, like Gecko) Version/9.1.1 Safari/601.6.17	-	http://www.sheila-branch.com/530/766/327.html	404	606885
2016-07-15 23:02:51	60.141.239.58	Mozilla/5.0 (iPhone; CPU iPhone OS 9_3_2 like Mac OS X) AppleWebKit/601.1 (KHTML, like Gecko) CriOS/51.0.2704.104 Mobile/13F69 Safari/601.1.46	caroline.cole	https://www.michael-hampton.com/708/910.php	404	3818970
2016-07-15 23:08:29	37.113.174.59	Mozilla/5.0 (Windows NT 10.0) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/51.0.2704.103 Safari/537.36	mandy.gibson	https://www.arielberg.com/752/413/849/808.png	404	1055575
2016-07-15 23:14:25	108.180.117.206	Mozilla/5.0 (Macintosh; Intel Mac OS X 10_11_1) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/51.0.2704.103 Safari/537.36	isaiah.anderson	http://www.estebanfinley.com/380/46/277.html	404	2998959
2016-07-15 23:19:35	145.181.244.114	Mozilla/5.0 (Windows NT 6.1; WOW64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/50.0.2661.102 Safari/537.36	-	http://www.carolrocha.com/744.html	404	3960244
2016-07-15 23:25:28	83.90.177.209	Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/51.0.2704.106 Safari/537.36	-	https://www.lindsay-barron.com/932/685.html	200	159664
```
See [the full log file](examples/logfile.log).

## Usage
TODO (coming soon)

## Configuration
TODO (coming soon)

## Resources
* [Hortonworks' Hadoop Tutorials, Tutorial 12: Refining and Visualizing Server Log Data](https://github.com/hortonworks/hadoop-tutorials/blob/master/Sandbox/T12_Refining_and_Visualizing_Server_Log_Data.md)
* [Bitsinfo Log Generator](https://github.com/bitsofinfo/log-generator)
* [Paul Poputa-Clean's Ruby Log Generator](https://github.com/paulpc/LogGenerator)





