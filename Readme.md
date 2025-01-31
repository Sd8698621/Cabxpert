# CabXpert - Cab Booking Application

## Overview
CabXpert is a feature-rich Cab Booking Application built using PHP, MySQL, Laravel, and Flutter. It serves both customers and drivers (captains), providing seamless ride booking, real-time tracking, secure payments, and an intuitive user experience. The app is designed to launch in West Bengal, India, with localized features to meet regional demands.

---

## Features
### Customer Interface Features
#### **User Onboarding**
- Interactive splash screen with an engaging introductory tour.
- Easy role selection (Customer or Captain).
- Language preference selection (Bengali, Hindi, English, etc.).

#### **Login & Authentication**
- Phone number & password login.
- OTP-based login for fast and secure access.
- Two-Factor Authentication (2FA) for enhanced security.

#### **Booking a Ride**
- Set pickup and drop-off locations easily.
- One-tap access to saved locations and favorite routes.
- Ride scheduling for future trips.
- Instant & scheduled booking options.
- **Emergency Booking (Medical Priority):** High-priority booking option for medical emergencies with faster driver allocation.
- **Round Trips:** Users can book rides for time-based journeys with scheduled return trips.
- **Fare Negotiation:** Riders and drivers can negotiate fare prices within a recommended range calculated by the system.

#### **Ride Preferences & Customization**
- Choose from Economy, Premium, SUV, or Auto-rickshaw.
- Set preferences for AC, music, pet-friendly rides, and child seats.
- Option for female-only drivers for enhanced safety.

#### **Real-Time Ride Tracking**
- Track driver’s location with live ETA.
- View driver details, including ratings and vehicle information.

#### **Fare Estimation & Ride Confirmation**
- Dynamic pricing based on distance, traffic, and time.
- Transparent fare breakdown (base fare, distance fare, tax, etc.).
- Ride confirmation with estimated fare display.

#### **Payments & Wallet**
- Multiple payment options: **UPI, E-Wallet, Credit/Debit Cards, Net Banking, Binance Payment Gateway, and Cash**.
- Auto-payment for seamless transactions.
- **Gift Card & Coupon Code Integration:** Apply promo codes and gift cards for discounts.
- Option to tip the driver post-ride.
- **In-App Wallet & Loyalty Program:** Earn points for each ride and redeem them for discounts and free rides.

#### **Ride History & Rebooking**
- View past rides with details and invoice downloads.
- Rebook favorite trips with a single tap.

#### **Ride Ratings & Feedback**
- Rate drivers and rides to improve service quality.
- Provide written feedback & select reasons for low ratings.

#### **Ride-Sharing & Carpooling**
- Opt for shared rides to reduce costs and environmental impact.
- Smart ride-matching to find nearby passengers going in the same direction.
- **Dual Booking at a Time:** If multiple users book for the same or nearby location (e.g., total seats = 4, 1st user books for 2 people, 2nd user books for 1 person, 3rd user books for 1 person), all are allocated to the same driver.

#### **Safety & Emergency Features**
- In-app SOS button to alert emergency contacts or authorities.
- Live ride-sharing with family/friends for safety.
- AI-powered behavior monitoring (detects abrupt stops, deviations, etc.).

#### **Notifications & Promotions**
- Real-time ride updates and promotional alerts.
- Personalized discounts and offers based on ride history.

#### **Referral & Loyalty Program**
- Refer friends and earn rewards or discounts.
- Earn loyalty points for every ride and redeem them for perks.

#### **Accessibility Features**
- Text-to-speech navigation.
- Voice command booking and ride details.
- High-contrast UI for visually impaired users.

---

### Captain (Driver) Interface Features
#### **Onboarding & Verification**
- Easy registration with document upload (license, vehicle details, etc.).
- Background verification for driver authentication.

#### **Login & Dashboard**
- OTP-based secure login.
- Dashboard showing daily earnings, ride requests, and trip statistics.

#### **Ride Management**
- Accept/reject ride requests based on availability.
- Ride navigation with optimized routing.
- Auto trip-assignment based on location and demand.
- **Dual Booking Support:** Drivers can accept multiple passengers going in the same direction to optimize earnings.
- **Fare Negotiation:** Drivers and riders can negotiate fares while ensuring fair pricing through automated recommendations.

#### **Earnings & Payouts**
- Daily/weekly/monthly earnings tracking.
- Instant withdrawal to a linked bank account.
- Bonus rewards for peak-hour rides.
- **Driver Rewards:** If a driver completes up to 20 bookings in a month, they receive a special reward.
- **Per Ride Charges:** The platform deducts a 10% service charge per ride.
- **Incentives:** Drivers receive 10% of the platform charges as incentives.

#### **Driver Safety & Support**
- Emergency SOS button for driver assistance.
- AI-powered fatigue detection alerts.
- Insurance and medical assistance options.

#### **Customer Communication**
- In-app chat and call with customers.
- Ride feedback to improve service quality.

#### **Fuel & Expense Tracking**
- Log fuel expenses and maintenance costs.
- Insights to optimize ride efficiency and earnings.

#### **Smart Ride Suggestions**
- AI-powered suggestions based on demand and traffic data.

#### **Offline Mode**
- Toggle offline/online mode when needed.

#### **Driver Training & Support**
- Video tutorials and guidelines for better service delivery.

---

### Shared Features (Customer & Driver)
#### **In-App Chat & Voice Calls**
- Secure, private communication between customers and drivers.

#### **Insurance Integration**
- Ride insurance for both customers and drivers.

#### **Location-Based Promotions**
- Discounts and offers based on ride location and frequency.

#### **Cross-Promotion with Local Businesses**
- Exclusive deals with restaurants, shopping malls, and partner businesses.

#### **Admin Panel & Fleet Management**
- Monitor live trips, handle disputes, and manage payments.
- Fraud detection and automated ban for rule violators.
- Surge pricing management based on demand.

---

## Future Enhancements
- **Carbon Footprint Tracker**: Show users the environmental impact of their rides and suggest eco-friendly options.
- **Voice-Activated Booking**: Hands-free ride booking using voice commands.
- **Subscription Model**: Monthly subscription for unlimited rides.
- **AI-Powered Customer Support**: 24/7 chatbot assistance for ride-related issues.
- **Driver Wellness Support**: Stress-relief programs and incentive-based performance rewards.
- **Electric Vehicle Integration**: Exclusive booking options for EV cabs to promote sustainability.

---

## Installation
1. **Clone the Repository:**
   ```sh
   git clone https://github.com/SRB/CabXpert.git
   cd CabXpert
   ```
2. **Install Dependencies:**
   ```sh
   composer install
   npm install
   ```
3. **Run the Application:**
   ```sh
   php artisan serve
   flutter run
   ```

---

## License
This project is licensed under the Apache-2.0 License.

---

## Contributors
Sayan Dutta - Developer & Maintainer  
Rhytham Hore - 
Biswarup Moldal - 

For contributions, feel free to fork the repo and submit pull requests.

---

## Contact & Support
For any issues or suggestions, reach out via:
- **Email:** support@cabxpert.com sayandutta@engineer.com
- **GitHub Issues:** [https://github.com/SRB/CabXpert/issues](https://github.com/SRB/CabXpert/issues)
- **Community Forum:** [CabXpert Community](#)

**Join us in revolutionizing cab booking with CabXpert! 🚖**

