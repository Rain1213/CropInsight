# **CROP-INSIGHT**

Agriculture plays a huge role in shaping livelihoods in India. As per 2018, agriculture employed more than 50℅ of the Indian work forces and contributed 17–18% to country's GDP. Agriculture is primary source of livelihood for 58% population in India. Farmers in India try to grow crops that have the highest price in the market. It is quite understandable seeing how majority of them barely earn enough to sustain themselves. However, in the long run it puts quite a strain on the farming land and will certainly decrease net profit in the years to come. Using CRS we wish to make the farmers realize how smart crop selection will help grow profits over time.

The application will recommend users what to grow based on where the user lives, soil type, weather patterns etc. It will also helps users calculate overall expenses and make user aware of current market prices.
<br/><br/>

## **SCOPE**
* We plan to restrict the application for farmers belonging to the state of Gujarat. 
* Prices in agriculture domain are ever fluctuating. It will be difficult to finance to a very precise amount. We expect an error margin of around 5%.
* The application will be available in English and Gujarati.
* Farmer with a smartphone will be able to use our application.
* Application works perfectly fine with unstable internet connectivity.
<br/><br/>

## **SOFTWARE DESIGN**

### **DISTRICT**
User’s Current location and district would be fetched.
If user is not of Gujarat state of India, user will be notified by alert message. This functionality will only work once location access is given to the application by the user.

<img align="center" alt="location" width="30%" src="https://github.com/Rain1213/CropInsight/blob/master/pics/MapView.PNG?raw=true" />
<br/><br/>

### **RECOMMENDATION FRAGMENT**
The District's values are passed to this fragment. In case location is turned off, user can manually enter any district/city name as long as its in the state of Gujarat. Recommendation Fragment as the name suggests will return back the best recommended crop that can be grown in that area, along with some additional info.

<img align="center" alt="Recommendation1" width="30%" src="https://github.com/Rain1213/CropInsight/blob/master/pics/Rec1.PNG?raw=true" />
<img align="center" alt="Recommendation2" width="30%" src="https://github.com/Rain1213/CropInsight/blob/master/pics/Rec2.PNG?raw=true" />
<br/><br/>

### **BUDGET TRACKER FRAGMENT**
You can pass on the values you just got from Recommendation Fragment into the Budget Tracker. If you do pass values, you would see fields like 'Buying Price', 'Seed Rate Ratio' and 'Seed Yield Ratio' already filled. Now all that the user has to do is to fill in rest of the details like Fertilizer Costs, Labour Costs, Water and Electricity Cost and the Size of the land in hectars. Total Budget and Income generated will be calculated and displayed in ruppees at the bottom of the screen.

<img align="center" alt="Budget1" width="30%" src="https://github.com/Rain1213/CropInsight/blob/master/pics/budget1.PNG?raw=true" />
<img align="center" alt="Budget2" width="30%" src="https://github.com/Rain1213/CropInsight/blob/master/pics/budget2.PNG?raw=true" />
<img align="center" alt="Budget3" width="30%" src="https://github.com/Rain1213/CropInsight/blob/master/pics/budget3.PNG?raw=true" />
<br/><br/>

### **CROP ROTATION FRAGMENT**
A common understanding is that its an unhealthy practice as farmers to grow the same crop time after time-again and again. To tackle this rhe crop rotation fragment will take in the value of your last crop planted and will return a new crop that will grow best in the same conditions where your previous crop had been grown.

<img align="center" alt="Rotation1" width="30%" src="https://github.com/Rain1213/CropInsight/blob/master/pics/rotation1.PNG?raw=true" />
<img align="center" alt="Rotation2" width="30%" src="https://github.com/Rain1213/CropInsight/blob/master/pics/rotation2.PNG?raw=true" />
<br/><br/>

### **GOVT. PROGRAMS FRAGMENT**
The application will also display different Programms (yojanas) launched under govt initiatives in order to help support Agriculture Industry. A link would also be provided to access the official website.

<img align="center" alt="govt1" width="30%" src="https://github.com/Rain1213/CropInsight/blob/master/pics/govt1.PNG?raw=true" />
<img align="center" alt="govt2" width="30%" src="https://github.com/Rain1213/CropInsight/blob/master/pics/govt2.PNG?raw=true" />
<br/><br/>
