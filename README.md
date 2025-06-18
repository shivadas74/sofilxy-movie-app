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
/sofilxy-app
 ├── pages/
 │    └── index.js
 ├── public/
 ├── styles/
 ├── .gitignore
 ├── package.json
 └── next.config.js
 export default function Home() {
  return (
    <div style={{
      color: '#fff',
      backgroundColor: '#000',
      minHeight: '100vh',
      display: 'flex',
      justifyContent: 'center',
      alignItems: 'center'
    }}>
      <h1>🎬 Welcome to SOFILXY - A Netflix-style Movie App</h1>
    </div>
  );
}
{
  "name": "sofilxy",
  "scripts": {
    "dev": "next dev",
    "build": "next build",
    "start": "next start"
  },
  "dependencies": {
    "next": "^14.1.0",
    "react": "^18.2.0",
    "react-dom": "^18.2.0"
  }
}
cd sofilxy
git init
git remote add origin https://github.com/your-username/sofilxy.git
git add .
git commit -m "Initial commit"
git push -u origin main
