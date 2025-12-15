<h1>🚀 Astra</h1>

<p>
  <strong>Astra</strong> is a modern <strong>video streaming application</strong> built with React Native,
  where users can <strong>upload, share, and stream AI-generated videos</strong>.
  It delivers a <strong>YouTube-like experience</strong> with multi-user support,
  global authentication, saved videos, and a clean, stylish UI ✨
</p>

<hr />

<h2>🌌 What is Astra?</h2>
<p>
  Astra is a mobile platform dedicated to <strong>AI-generated video content</strong>.
  Users can upload videos created using AI tools, explore content from other creators,
  save videos for later, and enjoy a smooth and intuitive streaming experience.
</p>
<p>
  ⚠️ Astra does <strong>not generate AI internally</strong> — it acts as a platform
  for hosting and consuming AI-created videos.
</p>

<hr />

<h2>✨ Features</h2>
<ul>
  <li>🎥 Smooth video streaming</li>
  <li>🤖 Platform focused on AI-generated videos</li>
  <li>👥 Multi-user support with individual profiles</li>
  <li>🔐 Global authentication with persistent sessions</li>
  <li>💾 Save videos to watch later</li>
  <li>📤 Upload and manage video content</li>
  <li>🎨 Modern, clean, and stylish UI</li>
  <li>📱 Mobile-first experience</li>
</ul>

<hr />

<h2>🛠️ Tech Stack</h2>

<h3>📱 Frontend</h3>
<ul>
  <li>⚛️ React Native</li>
  <li>🚀 Expo</li>
  <li>🎨 NativeWind (utility-first styling)</li>
</ul>

<h3>🧩 Backend</h3>
<ul>
  <li>🛠️ Appwrite</li>
  <li>🔐 Authentication</li>
  <li>🗄️ Database</li>
  <li>📦 Storage (video uploads)</li>
</ul>

<hr />

<h2>🧑‍💻 Project Structure</h2>
<pre>
Astra/
├── app/              📄 Screens and routes
├── components/       🧱 Reusable UI components
├── constants/        ⚙️ App constants and configs
├── hooks/            🪝 Custom React hooks
├── context/          🌍 Global state and auth context
├── lib/              🔌 Appwrite & helper utilities
├── assets/           🖼️ Images, icons, fonts
└── app.json
</pre>

<hr />

<h2>🔐 Authentication Flow</h2>
<ul>
  <li>👤 Users sign up or log in using Appwrite Auth</li>
  <li>🌍 Auth state is managed globally using context</li>
  <li>🔁 Sessions persist across app reloads</li>
  <li>🚫 Protected routes require authentication</li>
</ul>

<hr />

<h2>🎥 Video Handling</h2>
<ul>
  <li>📤 Videos are uploaded to Appwrite Storage</li>
  <li>🗄️ Metadata is stored in Appwrite Database</li>
  <li>📡 Video feeds are fetched dynamically</li>
  <li>💾 Users can save videos for later viewing</li>
</ul>

<hr />

<h2>🚀 Getting Started (Development)</h2>

<h3>✅ Prerequisites</h3>
<ul>
  <li>🟢 Node.js (v16 or higher)</li>
  <li>📦 Expo CLI</li>
  <li>🛠️ Appwrite backend (local or cloud)</li>
</ul>

<h3>📥 Installation</h3>
<pre>
git clone https://github.com/Anant-Dev925/Astra-React_Native.git
cd Astra-React_Native
npm install
</pre>

<h3>▶️ Run the App</h3>
<pre>
npx expo start
</pre>

<hr />

<h2>⚙️ Environment Configuration</h2>
<p>Create a <code>.env</code> file and add your Appwrite credentials:</p>
<pre>
APPWRITE_ENDPOINT=your_appwrite_endpoint
APPWRITE_PROJECT_ID=your_project_id
APPWRITE_DATABASE_ID=your_database_id
APPWRITE_STORAGE_ID=your_storage_id
</pre>

<hr />

<h2>🚧 Current Status</h2>
<p>
  Astra is under <strong>active development</strong>.
  New features, UI refinements, and performance improvements
  are being added continuously.
</p>

<hr />

<h2>🌠 Vision</h2>
<p>
  Astra aims to become a <strong>dedicated hub for AI-generated video content</strong>,
  offering creators and viewers a reliable, elegant, and enjoyable streaming platform.
</p>

<hr />

<h2>📄 License</h2>
<p>
  License information will be added in the future.
</p>
