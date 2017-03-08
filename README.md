# TRAPPIST-1 K2 Quicklook

### Lightcurves made with k2p2 (raw photometry: https://arxiv.org/abs/1504.05199) and k2sc (detrending: https://github.com/OxES/k2sc)

This is an *extremely* preliminary stab at a K2 lightcurve of TRAPPIST-1 - we haven't manually gone through and checked everything is right - but we are motivated to release what we have now by rumours on social media of a TRAPPIST-1h discovery already. We will hopefully improve on this in future if there is interest and welcome feedback on this lightcurve.

GP fit to long cadence data via usual k2sc pipeline, taking centroids instead of WCS information though. GP fit to short cadence data using unpublished Aigrain+ method which divides it up into chunks, processes each one separately, and stitches together. All mistakes Ben Pope's entirely.

### Contributors: Rasmus Handberg, Tim White, Benjamin Pope, Suzanne Aigrain

If you like our work, please cite k2sc

    @article{Aigrain2016,
        arxivId = {1603.09167},
        author = {Aigrain, Suzanne and Parviainen, Hannu and Pope, Benjamin},
        keywords = {data analysis,methods,photometry,planetary systems,techniques},
        title = {{K2SC: Flexible systematics correction and detrending of K2 light curves using Gaussian Process regression}},
        url = {http://arxiv.org/abs/1603.09167},
        year = {2016}
    }

and k2p2

	@ARTICLE{2015ApJ...806...30L,
	   author = {{Lund}, M.~N. and {Handberg}, R. and {Davies}, G.~R. and {Chaplin}, W.~J. and 
		{Jones}, C.~D.},
	    title = "{K2P$^{2}${\mdash} A Photometry Pipeline for the K2 Mission}",
	  journal = {\apj},
	archivePrefix = "arXiv",
	   eprint = {1504.05199},
	 primaryClass = "astro-ph.SR",
	 keywords = {asteroseismology, methods: data analysis, stars: solar-type, techniques: image processing, techniques: photometric},
	     year = 2015,
	    month = jun,
	   volume = 806,
	      eid = {30},
	    pages = {30},
	      doi = {10.1088/0004-637X/806/1/30},
	   adsurl = {http://adsabs.harvard.edu/abs/2015ApJ...806...30L},
	  adsnote = {Provided by the SAO/NASA Astrophysics Data System}
	}
