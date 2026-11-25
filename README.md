# Smart India Hackathon Workshop
# Date:20/11/2026
## Reference Number:26018367
## Name:SARAN N K

## Problem Title
SIH 26033: Multiple intermediaries reduce farmers earnings and increase consumer prices.

## Problem Creater's Organization
Ministry of Consumer Affairs, Food & Public Distribution

## Theme
Agriculture, FoodTech & Rural Development

## Problem Description
Expected Solution: Create a digital marketplace that:

• Connects farmers/FPOs directly with consumers and bulk buyers.
• Provides logistics support.
• Uses AI for demand forecasting and route optimization.

Benefits:

• Better prices for farmers.
• Lower prices for consumers.
• Reduced supply chain inefficiencies.

## Proposed Solution
  PROJECT NAME:GREENYFARM

  GreenyFarm is a web-based and mobile-friendly digital platform designed to create a direct connection between farmers, Farmer Producer Organizations (FPOs), consumers and bulk buyers.
The platform provides the following features:

Direct Farmer-to-Customer Marketplace: Farmers can register and upload their agricultural products with quantity, quality, images and expected prices. Consumers and bulk buyers can purchase products directly without unnecessary intermediaries.
AI-Based Price Recommendation: The system analyses available market prices, demand and historical data to suggest suitable selling prices to farmers.
Smart Demand Forecasting: AI predicts the future demand for agricultural products using historical sales, seasonal trends and market information.
Integrated Logistics Management: The platform connects farmers with transport providers and helps arrange product delivery.
Route Optimization: AI identifies efficient delivery routes to reduce transportation time and costs.
Real-Time Order Tracking: Farmers and customers can monitor order status, delivery progress and payment details.
   
How it addresses the problem

Removes unnecessary intermediaries between farmers and buyers.
Helps farmers receive better prices for their products.
Allows consumers to purchase agricultural products at competitive prices.
Reduces transportation expenses through optimized routes.
Minimizes food wastage by matching supply with demand.
Provides farmers with better access to larger markets.

Innovation and uniqueness

AI-powered price suggestions and demand prediction.
Direct farmer-to-consumer and farmer-to-business transactions.
Smart logistics and route optimization in one platform.
Digital marketplace designed specifically for agricultural products.
Regional language support to make the platform accessible to rural farmers.
Transparent pricing and order management.


## Technical Approach
Technologies to be Used:

-> Frontend:React Native (Mobile App), http://React.js (Web Dashboard)
->Backend: http://Node.js + Express / Python FastAPI
-> Database: PostgreSQL + Firebase (Real-time orders)
-> AI/ML: Python, TensorFlow, LSTM Model for Demand Forecasting, Google OR-Tools for Route Optimization
->Maps & Logistics: Google Maps API, OpenStreetMap
-> Payment:Razorpay / UPI, Escrow System
-> Cloud:AWS / Google Cloud, Cloudinary for Images
-> Language:Google Speech-to-Text for Tamil Voice Input

Methodology & Process:

Farmer Lists Crop -> AI Checks Price + Demand -> Buyer Orders -> FPO Verifies Quality -> AI Creates Best Delivery Route -> Driver Picks & Delivers -> Buyer Confirms -> UPI Payment to Farmer

Flow:

Onboarding: Farmer / FPO KYC via Aadhaar + Phone OTP
Listing: Photo + Voice + Quantity
Matching: AI matches nearest buyer with best price
Logistics: Auto-assign driver, live tracking
Payment & Rating: Transparent rating for both sides


## Feasibility and Viability

Feasibility:

90% farmers now have smartphones, UPI is already used in villages.
FPOs already exist in Tamil Nadu, we just digitize them.
Prototype can be built in 36 hours with above stack.
Pilot in 1 district (Chengalpattu) with 50 farmers + 20 buyers.

Potential Challenges & Risks:

Low digital literacy of farmers
Trust issue - Will buyer pay? Will farmer deliver quality?
Logistics in remote villages
Internet issues

Strategies to Overcome:

Voice + Video + Tamil UI + FPO Sahayak to help onboarding
Escrow Payment + Quality check by FPO + Rating system
Use existing local vehicles, not own fleet - low cost model
Offline-first app, works on 2G, auto-syncs when net comes
   
### Impact and Benefits

Impact on Target Audience:

Farmers:Income from Rs. 15/kg (via middleman) to Rs. 28/kg (direct). 2x profit.
Consumers: Tomato that costs Rs. 60 in market, gets for Rs. 40.
FPOs: Become mini-entrepreneurs, earn commission 5% for logistics / grading.

Benefits:

Social: Empowers small & marginal farmers, women SHGs.
Economic: Reduces supply chain cost by 30%, creates rural delivery jobs.
Environmental: Route optimization reduces fuel, less food waste reduces CO2, less plastic packaging.

### Research and References

eNAM - National Agriculture Market: https://enam.gov.in
Ministry of Agriculture - FPO Scheme, Govt. of India
FAO Report: Post-harvest losses in India 30-40%
Agmarknet - Live Mandi Prices: https://agmarknet.gov.in
ONDC - Open Network for Digital Commerce for Agriculture
