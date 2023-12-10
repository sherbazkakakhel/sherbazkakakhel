- 👋 Hi, I’m @sherbazkakakhel
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<I want to apply Minnesota prior in Stan package. I have a data set data_y which contains variable y1 and a data set data_lags which contains  "y1_lag1" "y1_lag2" "y1_lag3" "y1_lag4" "y1_lag5" "y1_lag6" "y1_lag7" "y1_lag8" "y1_lag9" "y1_lag10". 

I wanted to use BVAR package which contains a default Minnesota prior setting. However, in this case it is not possible to make it with BVAR thus I have to create it manually by rstan or brms package in R. 

But I am struggling to set Minnesota prior using brms or rstan, I can see in the code of BVAR that it used the cross product of the lags. But I don't know how it should coded manually.

All I want is to create is a  function which returns Bayesian linear regression with Minnesota prior using the given data.
--->
