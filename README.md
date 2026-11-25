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

1) Direct Farmer-to-Customer Marketplace: Farmers can register and upload their agricultural products with quantity, quality, images and expected prices. Consumers and bulk buyers can purchase products directly without unnecessary intermediaries.
2) AI-Based Price Recommendation: The system analyses available market prices, demand and historical data to suggest suitable selling prices to farmers.
3) Smart Demand Forecasting: AI predicts the future demand for agricultural products using historical sales, seasonal trends and market information.
4) Integrated Logistics Management: The platform connects farmers with transport providers and helps arrange product delivery.
5) Route Optimization: AI identifies efficient delivery routes to reduce transportation time and costs.
6) Real-Time Order Tracking: Farmers and customers can monitor order status, delivery progress and payment details.
   
How it addresses the problem

1)Removes unnecessary intermediaries between farmers and buyers.
2)Helps farmers receive better prices for their products.
3)Allows consumers to purchase agricultural products at competitive prices.
4)Reduces transportation expenses through optimized routes.
5)Minimizes food wastage by matching supply with demand.
6)Provides farmers with better access to larger markets.

Innovation and uniqueness

1)AI-powered price suggestions and demand prediction.
2)Direct farmer-to-consumer and farmer-to-business transactions.
3)Smart logistics and route optimization in one platform.
4)Digital marketplace designed specifically for agricultural products.
5)Regional language support to make the platform accessible to rural farmers.
6)Transparent pricing and order management.


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

1. Onboarding: Farmer / FPO KYC via Aadhaar + Phone OTP
2. Listing: Photo + Voice + Quantity
3. Matching: AI matches nearest buyer with best price
4. Logistics: Auto-assign driver, live tracking
5. Payment & Rating: Transparent rating for both sides


## Feasibility and Viability

Feasibility:

1)90% farmers now have smartphones, UPI is already used in villages.
2)FPOs already exist in Tamil Nadu, we just digitize them.
3)Prototype can be built in 36 hours with above stack.
4)Pilot in 1 district (Chengalpattu) with 50 farmers + 20 buyers.

Potential Challenges & Risks:

1) Low digital literacy of farmers
2) Trust issue - Will buyer pay? Will farmer deliver quality?
3) Logistics in remote villages
4) Internet issues

Strategies to Overcome:

1) Voice + Video + Tamil UI + FPO Sahayak to help onboarding
2) Escrow Payment + Quality check by FPO + Rating system
3) Use existing local vehicles, not own fleet - low cost model
4) Offline-first app, works on 2G, auto-syncs when net comes
   
### Impact and Benefits

Impact on Target Audience:

1) Farmers:Income from Rs. 15/kg (via middleman) to Rs. 28/kg (direct). 2x profit.
2)Consumers: Tomato that costs Rs. 60 in market, gets for Rs. 40.
3)FPOs: Become mini-entrepreneurs, earn commission 5% for logistics / grading.

Benefits:

1)Social: Empowers small & marginal farmers, women SHGs.
2)Economic: Reduces supply chain cost by 30%, creates rural delivery jobs.
3)Environmental: Route optimization reduces fuel, less food waste reduces CO2, less plastic packaging.

### Research and References

1) eNAM - National Agriculture Market: https://enam.gov.in
2) Ministry of Agriculture - FPO Scheme, Govt. of India
3) FAO Report: Post-harvest losses in India 30-40%
4) Agmarknet - Live Mandi Prices: https://agmarknet.gov.in
5) ONDC - Open Network for Digital Commerce for Agriculture
