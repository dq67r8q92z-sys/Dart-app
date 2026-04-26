# Dart Score Pro V3.2 REST Fix

Diese Version nutzt direkte Supabase REST Requests statt CDN Client.
Dadurch stabiler auf iPhone/Brave/Safari.

Voraussetzung Supabase Tabelle:
- id bigint identity primary key
- created_at timestamptz default now()
- room_code text not null
- state jsonb not null
- RLS disabled
