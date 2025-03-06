# Prediction of the next sunspots peak using Linear regression 

## The Solar Cycle
The sun goes through an 11 year cycle where after at the peak of every amplitude there is a rise in solar activity. There is a correlation between the number of sunspots and increase in the solar activity. Higher number of sunspots corresponds to increase in the solar activity and during the solar maximum we often have solar storms. During a solar storm there is an increased chances of solar flares and Coronal Mass Ejections(CMEs). Near Solar maximum the Sun produces 3 CMEs per day. These things can affect communication systems, navigation systems. power grid failures, satellites and spacecraft damage, etc. One Example of this is the Carrington Event. The Carrington Event is the most intense geomagnetic storm in the recorded history, peaking on 1-2 September 1859 during solar cycle 10. It created auroral displays that were reported globaly and caused sparking and even fires in the telegraph stations. The Auroras were visible even at the low latitude regions like China, Mexico, etc. The geomagnetic storm was most likely a result of a CME from sun colliding with Earth's Magnetosphere. This is why it becomes important to study and try to get a 'weather forecast' for sun. 

We are currently in the 25th cycle. The Last peak of this cycle happened in 2014 and the next peak is expected to be in 2025. This project tries to predict the next (25th) peak in the number of sunspots using previous data(1749-2024) of 24 peaks using the polar precursor method. 

## The polar precursor method:
The [polar precursor method](https://iopscience.iop.org/article/10.3847/1538-4357/abdbb4/meta#:~:text=The%20polar%20precursor%20method%20is,poles%20around%20the%20sunspot%20minimum.) is widely considered to be the most robust physically motivated method to predict the amplitude of an upcoming solar cycle. It is based on the observation of sunspot activity near the Sun's poles during the early phases of the cycle. During the Early stages of a solar cycle, sunspots typically appear near the Sun's equator. However, as the cycle progresses, sunspot activity shifts towards the poles. The Polar Precursor Method focuses on tracking the movement and appearance of sunspots at higher latitudes (closer to the poles) to estimate the intensity of the solar maximum (the peak of solar activity).

The method also looks at the magnetic fields at the Sun's poles. These fields provide valuable information about the Sun’s magnetic cycle, which is linked to the activity in sunspots. When the polar magnetic fields reverse, it can signal the approach of a solar maximum. Research has shown that the intensity of the solar maximum is often correlated with the strength of the magnetic fields at the Sun's poles. Stronger polar magnetic fields typically correlate with a stronger solar maximum, whereas weaker fields suggest a milder peak in solar activity.


**Data source:** https://www.sidc.be/SILSO/datafiles

