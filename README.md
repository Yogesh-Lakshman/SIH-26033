# Smart India Hackathon Workshop
# Date:25.11.26
## Reference Number:26009783
## Name:P.Yogesh Lakshman

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
1. **Brief Explanation**:
   we can build a digital marketplace eliminating the mediators by directly buying goods from farmers which will be benefit for both consumers and farmers by involving Farmer-Producer-Organizations(FPO).<br>
2.**The constraints:**
   Not every farmers have smart mobiles some can have basic telephone but we can still involve them in our digital workplace. We can provide customer care based service by issuing a toll-free number and they can simply dial it and register in the workplace with necessary information.<br>
3.**Procedure:**
   i) If the farmer has smartmobile they can simply register in it, if they don't have one           they can still register in the workplace by dialing the toll-free number.
   ii) The Farmer can sell their harvest which will be updated in the workplace/app.
   iii) When a customer places an order, The farmer receives an SMS notification/call                  regarding the order.
   iv) Quality check takes place at the village collection centre and the farmers can claim their amount directly from there by simply showing the receipt of the order.<br>
## Technical Approach
1. **Technologies to be used:**
   i)Front-end(app/website):Flutter or React Native for low-end phones.
   ii)Basic phone access:Interactive Voice Response `(IVR)` which is used to inform the farmer         `Eg.Press 1 to sell harvest which will then connect to a real-person to gather further         information.` 
   iii)Backend & APIs:Node.js, Python (Django/FastAPI), or Java (Spring Boot) to handle user         profiles and  offline caching (using SQLite or PouchDB).
   iv)Payments & Verification: UPI,Aadhaar-enabled Payment System (AePS),IMPS for instant           direct-to-bank transfers.
2. **Methodology and process for implementation:**
   <img width="1130" height="1600" alt="mindmap sih" src="https://github.com/user-attachments/assets/32995e5c-b52b-4340-a09b-82f4f4d94ba0" />

    

## Feasibility and Viability

1. **Analysis of the feasibility of the idea:**
    Our project will be feasible because in India most of the people are aware of and using       digital payments it is also feasible for farmers with basic phones and we  also have an       advantage & benefits through pre-existing FPO's which connects millions of farmers            altogether.  
2. **Potential challenges and risks:**
   Many farmers worked with mediators & middle-men throughout their life who give them the       cash immediately so they might hesitate to trust a new app or wait for bank transfers. As      we are shipping and storing vegetables and fruits they might be get spoiled quickly if it     doesn't get properly stored or delayed in shipping.
3. **Strategies for overcoming these challenges:**
   Our solution strategies for the risk we might face are;
      i)Appoint a local FPO coordinator for each village collection center and check the               harvest the farmers produce and transfer the correct amount immediately.
      ii)Smart route planning & storage planning can be implemented through Google OR-tools,GPS,etc.

## Impact and Benefits
1. **Potential impact on the target audience:**
   i) This digital marketplace empowers small-scale farmers and FPO's with direct access to         the market, Transparency in Pricing and providing a constant income.
2. **Benefits of the solution:**
   i)***Social benefit:*** Strengthens Local FPO organizations network,Promotes digital awareness in     rural areas and reduces the bargain and disputes among farmers.
   ii)***Economic:*** It completely eliminates the system of middle-men therefore increasing the           revenue of the farmers and also reduces the commodity price of harvest for the                consumers.
   iii)***Environmental:*** It majorly cuts down wastage of post-harvest with optimized supply chain and shared transport routes reduces fuel wastage.

## Research and References

1. [Ministry of Agriculture & Farmers Welfare](https://agricoop.nic.in/) – Guidelines on Farmer Producer Organizations (FPOs) and agricultural supply chain reforms.
2. [Interactive Voice Response (IVR) Systems for Smallholder Farmers] – Research on bridging digital devices and enabling voice-based market access for rural users with basic keypad phones (ACM / ResearchGate).("also used in customer-care services in telecommunications").
3. [AI-driven Demand Forecasting and Route Optimization in Agri-Food Supply Chains] – Studies on reducing post-harvest wastage and optimizing multi-stop vehicle routing (Published via IEEE / Springer).
