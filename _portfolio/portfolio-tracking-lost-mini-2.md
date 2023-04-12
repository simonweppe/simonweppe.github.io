---
title: "Tracking a lost racing sail yacht with OpenDrift"
excerpt: "Using a dispersion model OpenDrift with ocean and wind data to backtrack a lost Mini6.50 off the coast of Portugal <br/><img src='/images/mini650.png'>"
collection: portfolio
---

<img src='/images/mini650.png'/>

The racing yacht Jolly Rogers, a MINI 6.50, had to be abandoned off Spain’s Cape Finisterre during a leg of the MiniTransat Race.

The yacht was considered lost at sea until a sighting provided a position. Preparations were made to start a salvage operation. The weather was closing in, however, with forecasts promising strong winds and wave heights in excess of 6 m. 

To support the search operation, we modelled the predicted drift of the vessel using the open-source ocean trajectory model [OpenDrift](https://github.com/OpenDrift/opendrift), continuously updating our drift predictions as new forecast cycles became available. To account for the uncertainties in both forecasts and the drifting behaviour of the boat, we ran simulations accounting for different "windage" (i.e. how fast the boat drifts relative to wind), and using forecasts from different sources.

We found a large variability in the predicted tracks depending on which current and wind dataset were used. For the area, MERCATOR currents and the ECMWF winds yielded the best predictions. The yacht was found 2-3 miles from the location we predicted, which is very encouraging given the many uncertainties.

More details [here](https://www.metocean.co.nz/news/tracking-a-lost-sailing-yacht) and [here](https://www.mercator-ocean.eu/en/news/a-lost-sailing-yacht-was-founded-thanks-to-metocean-solutions-using-copernius-marine-service/) 