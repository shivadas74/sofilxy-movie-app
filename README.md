# SOFILXY 🎬

Netflix-style movie app. Deploy on Vercel.

## Steps:
1. Rename `.env.example` to `.env.local`
2. Run `npm install`
3. `npm run dev` to start local server.
# Create a new .env.local file using a demo TMDb API key for testing

demo_env_path = "/mnt/data/.env.local"

demo_tmdb_key = "d3m0a9ikey123456789"  # Example demo key (not real)



with open(demo_env_path, "w") as f:

    f.write(f"NEXT_PUBLIC_TMDB_API_KEY={demo_tmdb_key}\n")



demo_env_path
