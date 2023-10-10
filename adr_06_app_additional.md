# Additional frameworks or technology stacks 
### Status
- *Decision Made*
### Context
- *The app requires real-time order tracking, payment gateway integration, user-generated content moderation, and push notifications.*
### Decision
- *We will use the following additional frameworks and technology stacks:*
	- *For real-time order tracking: WebSocket protocol for real-time communication between the app and the server.*
	- *For payment gateway integration: Stripe and PayPal for secure and reliable payment processing.*
	- *For user-generated content moderation: Implement a content moderation service or API (e.g., Google Cloud's Content Moderation API).*
	- *For push notifications: Firebase Cloud Messaging (FCM) for sending and managing push notifications.*
### Consequences
- *WebSocket ensures real-time updates for order tracking but may require additional server infrastructure.*
- *Stripe and PayPal provide widely accepted payment solutions, but transaction fees should be considered.*
- *Content moderation services help maintain a safe and user-friendly environment.*
- *FCM simplifies push notification management for both iOS and Android.* 