# Apna Insaan V2
Mobile-first customer + assistant marketplace starter.

Vercel environment variables:
- VITE_SUPABASE_URL
- VITE_SUPABASE_PUBLISHABLE_KEY

The browser may use the publishable key. Never put a Supabase secret/service-role key in this project.

Expected public tables:
profiles, assistants, services, assistant_services, bookings.

Before production: configure RLS policies, enable/verify phone OTP, add admin authorization, identity verification, payment processing, and server-side booking/payment validation.
