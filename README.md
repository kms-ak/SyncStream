# 📡 SyncStream Real-time Media Engine

SyncStream is a collaborative video synchronization platform designed for frame-perfect viewing. 

## 🛠 Tech Architecture
- **WebSockets:** Powered by Ably Realtime for state synchronization.
- **Metadata:** TMDB API for dynamic movie search and poster retrieval.
- **Stream:** YouTube IFrame Player API for synchronized embedding.
- **DevOps:** GitHub Actions CI/CD with secure secret injection.

## 🚀 Deployment
1. Add `ABLY_KEY`, `TMDB_KEY`, and `YOUTUBE_KEY` to GitHub Actions Secrets.
2. Push to `main` branch.
3. Access the live environment via GitHub Pages.