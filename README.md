# sos-enatos-results


## About data used at this work 

This work has been done by using open data from INGV.
At first, our aim was to process seismic data from SoS Enatos region.
With the sucess of our preliminary analysis, and having stablished a
method, we are extending our analysis to the Virgo Network.

Data available at: https://eida.ingv.it/en/ at the getdata section.
One can download each day by searching for MN-SENA and listing the 
specific channels.

The most efficient way to obtaining data is by using fdsnwsscripts.
The file [sos-enatos.sh](sos-enatos.sh) provides a way to download the
SoS-Enatos data for SENA stations and HHZ channel from 2022 to 2025.

We are very thankful for the the [fdsnwsscripts](https://github.com/GEOFN/fdsnws_scripts)
project because we could stablish a more uniform and efficient way to
obtain the data rather than just downloading file by file at the [eida getdata](https://eida.ingv.it/en/)

### Aknowledgments 

We are thankful for GEOFN for the project fdsnwsscripts, which gave us
a very efficient way to obtain uniform data.

The authors are also thankful to [LAB-CCAM](https://www.pgfis.ita.br/post/lab-ccam) for
providing the computational resources whenever was necessary.

### Authors

Assis-Santos R.<sup>1<sup>, Pinto F. A.<sup>2<sup>, Pompeia P. J.<sup>1<sup>, Melo C. A. M.<sup>2<sup>
<sup>1<sup>Instituto Tecnológico de Aeronáutica
<sup>2<sup>Universidade Federal de Alfenas