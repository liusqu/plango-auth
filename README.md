# plango-auth

Magic-link landing page for the PlanGo iOS app. Receives the Supabase auth
redirect on a real https page (in-app browsers refuse server redirects into
custom URL schemes) and hands the auth params to plango://auth/callback.
No secrets live here.
