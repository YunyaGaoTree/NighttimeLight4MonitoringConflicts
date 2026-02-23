Developing an effective and efficient method for monitoring conflict zones with high temporal and spatial resolution can greatly benefit users in understanding ground situations to plan their humanitarian aid. 
Here, a general workflow was proposed as shown in the following figure. The workflow mainly includes the following steps:

1)	utilizes nighttime light satellite imagery (VIIRS-NPP) that can provide daily data for fast responses and early warning, https://eogdata.mines.edu/products/vnl/
2)	also makes use of Sentinel-1 data for general building damage assessment to locate specific area of interest (AOI), 
3)	purchases and preprocess VHR satellite imagery for the selected AOI, 
4)	uses advanced AI models (cite the paper of Sergiu if possible) to provide detailed building damage on the ground. 

<img width="1090" height="818" alt="image" src="https://github.com/user-attachments/assets/ef38c1a6-b0d0-4414-af33-72c2cada2860" />

The following content briefly shows an example in the Gaza Strip.
An armed conflict between Israel and Hamas-led Palestinian militant groups has been ongoing in the Gaza Strip and Israel since 7 October 2023. 
It is the most significant military engagement in the region since the Yom Kippur War in 1973. The following GIF shows how nighttime light changes monthly from January 2023 to May 2024. 
It can be easily observed that nighttime light was significantly reduced since October 2023. 
In the following months, nighttime light concentrated in a very small area, with the center of concentration migrating from the north to the middle of the Gaza Strip before becoming totally dark. 
This simple video indicates the migration of people during this conflict.
<img width="524" height="378" alt="image" src="https://github.com/user-attachments/assets/07fdcd50-d9d6-4939-94cb-855c8e941dd4" />

In the Step 1, we made a statistics analysis of the monthly average nighttime radiance in the Gaza Strip from 2014 to 2024. 
We can observe that nighttime radiance generally has seasonal changes, but there are two obvious drops in March 2017 and October 2023. 
The sudden drop in 2017 corresponds to reports that the number of Palestinians allowed to move in and out of Gaza declined significantly in 2017 compared to 2016. 
Source: https://www.ochaopt.org/content/palestinian-access-gaza-strip-declined-sharply-2017 

In the Step 2, we visualize active fire signals derived from VIIRS-NPP products in September 2023, October 2023, and November 2023. 
We can observe that while the press reported the formal conflict occurred on 7 October 2023, active fire signals were already present in September 2023. 
Although more efforts are needed to verify the effectiveness of the active fire products as an indicator for early warning of conflicts, they definitely show high potential. 

In the Step 3, we made a cross-check for the nighttime light data and field information, as shown in the following example. 
The left figure shows the active fire signal in May 2024, and the field information verified that there was a conflict in this region. 
The daily captured nature of VIIRS-NPP data and its derived products makes it a “near real-time alert system”, which can be very useful for humanitarian operations.

_“Between 10-11 May 2024, Israeli airstrikes targeted at least seven houses in Al-Sabra, Al-Zaytoun neighborhoods, as well as in Jabaliya and Beit Lahiya, 
resulting in multiple killings and injuries…On the evening of Saturday, 11 May, Israeli forces began a wide-scale ground invasion on Jabaliya and its refugee camp, 
following hours of issuing evacuation orders for residents and displaced people amidst intensive shelling and bombardment that targeted many homes and streets.”_
<img width="404" height="309" alt="image" src="https://github.com/user-attachments/assets/1cc0d806-a461-4e82-80ed-a85a646a4434" />

In the Step 4, we first used Sentinel-1 Imagery to generally detect damage on the ground. 
Then, users can select several AOIs for more details based on our advanced AI models based on purchased commercial VHR satellite imagery. By these two-step evaluation, 
we can provide users damage assessment results in a broad perspective and detailed information for specific areas for planning various humanitarian operations at a lower cost in a faster way. 

This workflow also have been tested in other conflict zones such as South Sudan, as shown below. 
A civil war between two major rival factions of the military government of Sudan began during Ramadan on 15 April 2023. 
Fighting has been concentrated around the capital city of Khartoum and the Darfur region. 
As of 5 July 2024, over 7.7 million were internally displaced, and more than 2.1 million others had fled the country as refugees, 
with many civilians in Darfur reported dead as part of the Masalit massacres.
<img width="1090" height="385" alt="image" src="https://github.com/user-attachments/assets/9d21d639-386b-4a28-b728-c4439a2ed6a7" />

**Conclusions
This is a very general workflow and proof of concept of nighttime light data together with Sentinel1 data and other potential datasets that can help monitor conflicts on the ground. 
Each step can be improved based on the needs.

Feel free to check this Google Earth App to interactively check the effects of NLT data for monitoring conflicts:
Interface:
https://ee-spacept.projects.earthengine.app/view/using-nightime-light-to-monitor-conflicts

Codes:
https://code.earthengine.google.com/33d724506e943fbd89294f64250d1a49
<img width="3801" height="1948" alt="image" src="https://github.com/user-attachments/assets/7e81d7be-82f4-468b-89ca-d61b945c3b30" />


The above work was done during the intership in Spacept (https://spacept.com/).
Currently I am Geospatial Developer in Vienna Austria but am always interested in the application of EO data for humanitarian operations.
I sincerely anyone who is interested in such topics feels free to contact me.
(Welcome to connect in LinkedIn: https://www.linkedin.com/in/yunya-gao-phd-9b72b1148/)





