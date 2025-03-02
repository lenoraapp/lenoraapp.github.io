# Lenora - AI Dating Coach

An iOS app that helps users improve their dating app experience with AI-powered suggestions and analysis.

## Technical Details
- iOS 17.0+
- SwiftUI
- Supabase for backend
- Observable pattern for state management

## Completed Features

### Onboarding
- ✅ Onboarding flow

### Home Dashboard
- ✅ Welcome header with personalized greeting
- ✅ Quick action buttons for common tasks
- ✅ Grid layout of coaching categories
- ✅ Navigation structure
- ✅ Theme implementation (colors, fonts)

### Profile & Match Analysis
- ✅ Multiple image upload (up to 5 images)
- ✅ Basic UI for profile screenshot analysis
- ✅ Message suggestions UI with copy functionality
- ✅ Profile strength analysis
- ✅ Improvement suggestions
- ✅ Bio writing assistance
- ✅ Impact metrics for suggestions

### Message Help
- ✅ Conversation stage selection
- ✅ Tone customization
- ✅ Match bio and interests input
- ✅ AI-powered message suggestions
- ✅ Do's and Don'ts for each suggestion
- ✅ Conversation strategies with examples

### Chat Analysis
- ✅ Chat screenshot analysis
- ✅ Conversation improvement tips
- ✅ Response suggestions

### Message & Conversation Help
- ✅ Context-aware message suggestions
- ✅ Conversation strategy tips
- ✅  Ice breaker suggestions

### Date Planning
- ✅ Personalized date ideas
- ✅ Planning assistance
- ✅ Location-based suggestions

### App Review System
- ✅ Smart review request timing based on user engagement
- ✅ Tracking of successful AI analyses
- ✅ Limited review requests (max 3 per year)
- ✅ Minimum 90-day spacing between requests
- ✅ Delayed review prompts (45 seconds after analysis)
- ✅ Persistent review tracking across app sessions
- ✅ App lifecycle-aware review system
- ✅ Centralized review management

### Credits System
- ✅ Base credit tiers implementation
- ✅ Free: 5 credits/month
- ✅ Premium: 50 credits/month
- ✅ Credit management with iCloud sync
- ✅ Automatic monthly credit refresh
- ✅ Purchased credits tracking
- ✅ Robust sync mechanism with conflict resolution

### Credits System
# Base Tiers:
- ✅Free: 5 uses/month (increased to give better taste)
- ✅Premium ($12.99): 75 uses/month ($0.17/use)

# Extra Credits:
- ✅ 15 credits for $4.99 ($0.33/credit) 89,99 TL
- ✅ 50 credits for $11.99 ($0.24/credit) 199,99 TL
- ✅ 100 credits for $19.99 ($0.20/credit) 359,99 TL

# Details:

- ✅ Free user can have 5 credits in a month to be used in the app.
- ✅ The premium user which will be based on a subscription can have 50 credits in a month to be used in the app.
- ✅ The user can add credits with a non consumable in app purchase product.
- ✅ 
- ✅ If the user is free, expending a credit will decrease the free credits first, then the pruchased ones. But the free amount will be refresh every month.
- ✅ If the user is premium, the user will decrease the 50 credits first, then the purchased ones. There won't be any free credits to use. But the premium amount will be refreshed - ✅ every month.
- ✅ 
- ✅ iCloud to track the credits.
- ✅ 
- ✅ The credit count should be always in sync.
- ✅ 
- ✅ There should be a retry and a backup mechanism to keep the credits in sync. Because any request to or from iCloud can be failed.
- ✅ I don't want to add extra credit to the user's credits or decrease extra credit from the user's credits.
- ✅ 
- ✅ There shoul be a syncin mechanism that can be start from anywhere. On app lunch will be required.
- ✅ Only app launch won't be enough because the user may not close the app. We should cover every edge case as much as possible.

## In Progress / Planned Features

## Not planned features:
### Authentication
- ⏳ Onboarding flow

### Backend Integration
- ⏳ Supabase data models and relationships
- ⏳ API integration for image analysis
- ⏳ User data persistence
- ⏳ History tracking

### Profile & Match Analysis
- ⏳ Save favorite suggestions