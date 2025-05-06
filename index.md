# VIBE AI Playlist Generator  
**Privacy Policy**  

_Last updated: May 2025_

## 1. Introduction  
VIBE AI (“we”, “us”, or “our”) is committed to protecting your privacy. This Privacy Policy explains how we collect, use, and store data when you use our iOS app, **VIBE AI Playlist Generator**.

## 2. Data We Collect  

### 2.1 Speech Transcription  
- We use Apple’s **Speech** and **AVFoundation** frameworks to convert your spoken “vibe” description into text.  
- **What we collect:** audio buffers are processed on-device; no raw audio is uploaded to our servers.  
- **Why:** to let you dictate your playlist description hands-free.  

### 2.2 OpenAI API  
- We send only your **text** description and desired song count to our secure proxy on Vercel (HTTPS).  
- **What we collect:** the text you enter; OpenAI’s recommendations (artist & title) are returned.  
- **Why:** to generate a curated list of song suggestions.

### 2.3 Spotify API  
- We use OAuth 2.0 to authenticate you with Spotify.  
- **What we store:**  
  - Access token and refresh token in your device’s **Keychain** only.  
  - No tokens are stored on our servers.  
- **Why:** to create and open playlists in your personal Spotify account.

## 3. How We Use Your Data  
- **On-device speech processing:** for transcription only.  
- **OpenAI calls:** to generate recommendations; we do not store your text or results beyond the current session.  
- **Spotify calls:** to manage playlists; tokens remain securely in your Keychain.

## 4. Data Sharing & Disclosure  
- We never sell or share your data with third parties.  
- All server-side communication (Vercel, OpenAI, Spotify) is over HTTPS.

## 5. Security  
- Tokens are stored in Apple’s **Keychain**.  
- All network calls use TLS/HTTPS.  
- No personal data is persisted on our servers.

## 6. Your Choices  
- You can revoke Spotify access at any time in the Spotify app.  
- You can reset speech permissions in **Settings → Privacy & Security → Speech Recognition**.  

## 7. Contact Us  
If you have any questions or concerns about this policy, please reach out:  
- GitHub Issues: [github.com/your-username/vibe-ai-privacy](https://github.com/your-username/vibe-ai-privacy)
