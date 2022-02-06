# EarthquakeDataCenters
## Overview
The *SeedLink protocol* is a robust data transmission intended for use on the Internet or private circuits that support TCP/IP. The protocol is robust in that clients may disconnect and reconnect without losing data, in other words transmissions may be resumed as long as the data still exist in the servers buffer. Requested data streams may be limited to specific networks, stations, locations and/or channels. All data packets are 512-byte Mini-SEED records.
<br>(More information [here](https://www.seiscomp.de/doc/apps/seedlink.html))

The *FSDNWS-Station* provides access to station metadata and instrument specifics in FDSN StationXML format. Metadata can be selected on SEED network, station, location or channel identifiers in addition to spatiotemporal constraints. Metadata can be extracted at multiple levels of detail.
<br>(More information [here](http://www.fdsn.org/webservices/))

## List

### Seedlink
<table>
	<thead>
		<tr><th align="left">Name</th><th align="left">Host</th></tr>
	</thead>
	<tbody>
		<tr><td align="left">AusPass</td><td align="left">auspass.edu.au</td></tr>
		<tr><td align="left">BGR</td><td align="left">eida.bgr.de</td></tr>
		<tr><td align="left">CISMID</td><td align="left">www&#46;cismid.uni.edu.pe</td></tr>
		<tr><td align="left">ENS</td><td align="left">ephesite.ens.fr</td></tr>
		<tr><td align="left">GEOFON, GFZ</td><td align="left">geofon.gfz-potsdam.de</td></tr>
    		<tr><td align="left">GEONET</td><td align="left">link.geonet.org.nz</td></tr>
		<tr><td align="left">Geoscience Australia</td><td align="left">seis-pub.ga.gov.au</td></tr>
		<tr><td align="left">GSRAS (?)</td><td align="left">89.22.182.133</td></tr>
		<tr><td align="left">Helsinki</td><td align="left">finseis.seismo.helsinki.fi</td></tr>
		<tr><td align="left">Haiti</td><td align="left">ayiti.unice.fr</td></tr>
		<tr><td align="left">ICGC</td><td align="left">ws.icgc.cat</td></tr>
		<tr><td align="left">IDA Project</td><td align="left">rtserve.ida.ucsd.edu</td></tr>
		<tr><td align="left">IPGP</td><td align="left">rtserver.ipgp.fr</td></tr>
		<tr><td align="left">IRIS DMC</td><td align="left">rtserve.iris.washington.edu</td></tr>
		<tr><td align="left">IRIS Jamaseis</td><td align="left">jamaseis.iris.edu</td></tr>
		<tr><td align="left">ISNET - UNINA<br>Università degli Studi di Napoli Federico II</td><td align="left">185.15.171.86</td></tr>
		<tr><td align="left">LMU</td><td align="left">erde.geophysik.uni-muenchen.de</td></tr>
		<tr><td align="left">NIGGG</td><td align="left">195.96.231.100</td></tr>
		<tr><td align="left">NRCAN</td><td align="left">earthquakescanada.nrcan.gc.ca</td></tr>
		<tr><td align="left">OBSEBRE</td><td align="left">obsebre.es</td></tr>
		<tr><td align="left">OGS</td><td align="left">140.105.68.27</td></tr>
		<tr><td align="left">Oklahoma University</td><td align="left">rtserve.ou.edu</td></tr>
		<tr><td align="left">ORFEUS</td><td align="left">eida.orfeus-eu.org</td></tr>
		<tr><td align="left">PLSN (IGF Poland)</td><td align="left">213.135.33.194</td></tr>
		<tr><td align="left">Red Sìsmica de Puerto Rico</td><td align="left">161.35.236.45</td></tr>
		<tr><td align="left">Red Sìsmica Baru</td><td align="left">helis.redsismicabaru.com</td></tr>
		<tr><td align="left">RESIF</td><td align="left">rtserve.resif.fr</td></tr>
		<tr><td align="left">SANET</td><td align="left">147.213.113.73</td></tr>
		<tr><td align="left">RSIS</td><td align="left">rsis1.on.br</td></tr>
		<tr><td align="left">SCSN-USC<br>(South Carolina Seismic Network)</td><td align="left">eeyore.seis.sc.edu:6382</td></tr>
		<tr><td align="left">Seisme IRD</td><td align="left">rtserve.ird.nc</td></tr>
		<tr><td align="left">Staneo</td><td align="left">vibrato.staneo.fr</td></tr>
		<tr><td align="left">SNAC NOA</td><td align="left">snac.gein.noa.gr</td></tr>
		<tr><td align="left">TexNet</td><td align="left">rtserve.beg.utexas.edu</td></tr>
		<tr><td align="left">Unical<br>Universita Della Calabria</td><td align="left">www&#46;sismocal.org</td></tr>
		<tr><td align="left">UNITS<br>Università degli studi di Trieste</td><td align="left">rtweb.units.it</td></tr>
		<tr><td align="left">UNIV-AG<br>Université des Antilles</td><td align="left">seedsrv0.ovmp.martinique.univ-ag.fr</td></tr>
		<tr><td align="left">Universidad de Colima</td><td align="left">148.213.24.15</td></tr>
		<tr><td align="left">UPR</td><td align="left">worm.uprm.edu</td></tr>
		<tr><td align="left">USGS</td><td align="left">cwbpub.cr.usgs.gov</td></tr>
		<tr><td align="left">USP-IAG</td><td align="left">seisrequest.iag.usp.br</td></tr>
		<tr><td align="left">ZAMG</td><td align="left">195.96.231.100</td></tr>
	</tbody>
</table>

***Note**: seedlink port is 18000*

### FDSNWS
<table>
	<thead>
		<tr><th align="left">Name</th><th align="left">Link</th></tr>
	</thead>
	<thead>
		<tr><th colspan="2" align="center">Americas</th></tr>
	</thead>
	<tbody>
		<tr><td align="left">IRIS DMC</td><td align="left">http://service.iris.edu/fdsnws/station/1/</td></tr>
		<tr><td align="left">NCEDC</td><td align="left">http://service.ncedc.org/fdsnws/station/1</td></tr>
		<tr><td align="left">SCEDC</td><td align="left">http://service.scedc.caltech.edu/fdsnws/station/1/</td></tr>
		<tr><td align="left">TexNet</td><td align="left">http://rtserve.beg.utexas.edu/fdsnws/station/1/</td></tr>
		<tr><td align="left">USP-IAG</td><td align="left">http://seisrequest.iag.usp.br/fdsnws/station/1/</td></tr>
		<tr><td align="left">Raspberry Shake</td><td align="left">https://fdsnws.raspberryshakedata.com/fdsnws/station/1</td></tr>
	</tbody>
	<thead>
		<tr><th colspan="2" align="center">Asia</th></tr>
	</thead>
	<tbody>
		<tr><td align="left">BMKG</td><td align="left">https://geof.bmkg.go.id/fdsnws/station/1/</td></tr>
	</tbody>
	<thead>
		<tr><th colspan="2" align="center">Europe</th></tr>
	</thead>
	<tbody>
		<tr><td align="left">BGR</td><td align="left">http://eida.bgr.de/fdsnws/station/1/</td>
		<tr><td align="left">KNMI</td><td align="left">http://rdsa.knmi.nl/fdsnws/station/1/</td>
		<tr><td align="left">KOERI</td><td align="left">http://eida-service.koeri.boun.edu.tr/fdsnws/station/1/</td>
		<tr><td align="left">ETHZ</td><td align="left">http://eida.ethz.ch/fdsnws/station/1/</td>
   		<tr><td align="left">GEOFON, GFZ</td><td align="left">http://geofon.gfz-potsdam.de/fdsnws/station/1/</td></tr>
		<tr><td align="left">ICGC</td><td align="left">http://ws.icgc.cat/fdsnws/station/1/</td>
		<tr><td align="left">IPGP</td><td align="left">http://eida.ipgp.fr/fdsnws/station/1/</td>
		<tr><td align="left">INGV</td><td align="left">http://webservices.ingv.it/fdsnws/station/1/</td>
		<tr><td align="left">LMU</td><td align="left">http://erde.geophysik.uni-muenchen.de/fdsnws/station/1/</td>
		<tr><td align="left">NIEP</td><td align="left">http://eida-sc3.infp.ro/fdsnws/station/1/</td>
		<tr><td align="left">NOA</td><td align="left">http://eida.gein.noa.gr/fdsnws/station/1/</td>
		<tr><td align="left">ORFEUS</td><td align="left">http://www.orfeus-eu.org/fdsnws/station/1/</td>
		<tr><td align="left">RESIF</td><td align="left">http://ws.resif.fr/fdsnws/station/1/</td>
		<tr><td align="left">SNAC NOA</td><td align="left">http://snac.gein.noa.gr:8080/fdsnws/station/1/</td>	
	</tbody>
	<thead>
		<tr><th colspan="2" align="center">Oceania</th></tr>
	</thead>
	<tbody>
		<tr><td align="left">AusPass</td><td align="left">http://auspass.edu.au:8080/fdsnws/station/1/</td></tr>
	</tbody>
	
</table>
