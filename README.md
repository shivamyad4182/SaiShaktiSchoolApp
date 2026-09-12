# SAI SHAKTI SCHOOL, AZAMGARH — Android App

Native Android / Jetpack Compose starter implementation based on the supplied reference design.

## What is included
- Premium navy/white/gold visual system
- Animated entry/splash experience
- Student, Parent, Teacher and Admin entry/login flows
- Student dashboard
- Notices, Gallery, Digital Library, Results, Timetable, Homework, Study Materials, Events, Feedback
- Admin panel navigation
- Supabase Kotlin client wiring
- Supabase SQL starter schema with RLS enabled
- Supplied reference design and extracted logo asset

## Supabase setup
1. Create/open your Supabase project.
2. Run `supabase/schema.sql` in SQL Editor.
3. Add your Supabase Project URL and **publishable key** to Gradle properties/build configuration.
4. Never put a service-role key in the Android app.
5. Review and tighten RLS policies before production.

The current UI uses local sample presentation data so the project can be previewed before backend content is connected. The repository layer should be connected to the tables after the Supabase schema is deployed.

## Build
Open the folder in Android Studio with a current Android Gradle Plugin/Kotlin/Compose environment. Minimum Android SDK is 26 for current Supabase Kotlin documentation.

The reference image is `reference_design.png`. The extracted logo asset is `app/src/main/res/drawable/logo_sai_shakti.png`.
