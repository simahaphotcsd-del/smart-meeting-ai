# Smart Meeting AI — GitHub Pages

1. Upload the contents of this ZIP (not the ZIP itself) to the repository root.
2. Edit `js/config.js`: replace `PASTE_YOUR_PUBLISHABLE_KEY_HERE` with your Supabase publishable/anon key. NEVER use a secret/service_role key.
3. GitHub repository > Settings > Pages > Deploy from branch > main / (root).
4. Supabase Auth > URL Configuration: add your GitHub Pages URL to Site URL and Redirect URLs.
5. Sign in and test using non-sensitive sample audio.

Supabase project: rfghyrdjexqidgfsnfjp. The database and Edge Function are deployed separately, not hosted on GitHub Pages.

Warning: Publishing the repository makes its files public. Do not upload secrets or meeting recordings.
