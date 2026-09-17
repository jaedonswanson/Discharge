[**A quick, simple, and effective way to measure discharge in small headwater streams.**](https://goosefflab.wordpress.com/2012/07/26/measuring-discharge-with-conservative-tracers/)
# Background
- The basis for these methods is measuring the dilution of a conservative tracer of a known volume.
- "[[Terms#Slug|Slug Injection]]" of known mass of NaCl is dumped into stream, which then disassociates near instantly.
	- As the tracer moves downstream, a concentration-time profile known as a break-through-curve (BTC) is recorded by sampling through time at a single downstream monitoring location
- Then discharge is calculated by: $Q = \frac {M}{\int_0^t C(t)}$
		- $Q =$ Discharge ($\frac {M^3}{T}$)
		- $M =$ mass of injectate(M)
		- $C =$ concentration ($\frac{M}{L^3}$)
		-  $t =$ time
	- The denominator is the integration of the BTC, known as the zeroth moment
	- More info at [USGS](http://pubs.usgs.gov/twri/twri3-a16/)
## Assumptions:
- All injected mass was recovered at the downstream sampling location
- The tracer is completely mixed across the channel
# Field Methods
1. Launch conductivity loggers to continuously sample at the downstream location.
	1. By continuously sampling conductivity we can convert to NaCl concentration using the established relationship
	2. Frequency of logging depends on length and size of stream, they used 2 seconds
		1. It is ***very important*** to sync time on data logger to time on wristwatch
2. After logger is launched and logging, tie a bright piece of flagging to the logger
	1. Logger measurements should be made at $\approx 50\%$ water depth
	2. ***Record river location of the downstream sampling site***
3. Once downstream site is all set, move to injection location and mix injectate.
4. Quickly pour the bucket of dissolved tracer across the width of the stream
	1. ***Record the time***
5. Immediately after pouring injectate into the stream, rinse both bucket and mixing stick in stream
	1. This ensures all NaCl mass gets into stream
6. Wait for injection to completely pass the downstream location (stream concentration returns to ambient conditions)
	1. Bringing a handheld conductivity logger into the field is an easy way to tell if the stream has returned to ambient conditions
7. The data collection is now done, and can be processed using [Excel](file:/~/Desktop/School/MS/Thesis/Research/Discharge/tracer_discharge.xlsx)




