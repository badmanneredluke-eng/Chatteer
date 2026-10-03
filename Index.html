<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
  <title>chatteer - Worldwide Chat & Photo Hub</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Outfit:wght@500;600;700;800;900&family=Plus+Jakarta+Sans:wght@400;500;600;700&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Plus Jakarta Sans', sans-serif;
      touch-action: manipulation;
    }
    .brand-font {
      font-family: 'Outfit', sans-serif;
    }
    ::-webkit-scrollbar {
      width: 6px;
      height: 6px;
    }
    ::-webkit-scrollbar-track {
      background: rgba(241, 245, 249, 0.8);
    }
    ::-webkit-scrollbar-thumb {
      background: rgba(165, 180, 252, 0.6);
      border-radius: 9999px;
    }
    ::-webkit-scrollbar-thumb:hover {
      background: rgba(129, 140, 248, 0.8);
    }
    .no-scrollbar::-webkit-scrollbar {
      display: none;
    }
    .no-scrollbar {
      -ms-overflow-style: none;
      scrollbar-width: none;
    }
  </style>
</head>
<body class="bg-slate-50 text-slate-800 flex flex-col h-screen overflow-hidden select-none">

  <!-- TOP HEADER -->
  <header class="bg-white/95 border-b border-slate-200/90 backdrop-blur-md px-3 sm:px-5 py-2.5 shrink-0 flex items-center justify-between z-20 shadow-sm">
    <div class="flex items-center space-x-2.5 sm:space-x-3">
      <div class="w-9 h-9 sm:w-10 sm:h-10 rounded-2xl bg-gradient-to-tr from-indigo-600 via-violet-500 to-pink-500 flex items-center justify-center shadow-lg shadow-indigo-500/25 ring-2 ring-indigo-400/20">
        <span class="text-lg sm:text-xl">🌐</span>
      </div>
      <div>
        <div class="flex items-center gap-1.5 sm:gap-2">
          <h1 class="brand-font text-xl sm:text-2xl font-black tracking-tight bg-gradient-to-r from-indigo-600 via-purple-600 to-pink-500 bg-clip-text text-transparent">
            chatteer
          </h1>
          <span class="px-2 py-0.5 text-[9px] sm:text-[10px] font-bold uppercase tracking-wider bg-emerald-50 text-emerald-600 border border-emerald-200 rounded-full flex items-center gap-1">
            <span id="connection-dot" class="w-1.5 h-1.5 rounded-full bg-emerald-500 animate-pulse"></span>
            <span id="connection-status">Connecting...</span>
          </span>
        </div>
        <p class="text-[11px] text-slate-500 hidden sm:flex items-center gap-1 font-medium">
          Worldwide instant cloud network
        </p>
      </div>
    </div>

    <!-- Header Actions -->
    <div class="flex items-center gap-1.5 sm:gap-3">
      <!-- Switch Page Navigation Toggle -->
      <button id="page-nav-btn" type="button" class="flex items-center gap-1.5 px-3 py-1.5 rounded-xl bg-gradient-to-r from-violet-600 to-indigo-600 text-white font-bold text-xs shadow-md shadow-indigo-500/20 hover:from-violet-500 hover:to-indigo-500 transition-all active:scale-95 cursor-pointer">
        <span id="page-nav-icon">📸</span>
        <span id="page-nav-label">To Photos</span>
      </button>

      <!-- Permanent Assigned Device ID Badge -->
      <div id="profile-toggle-btn" title="Permanent Unique Device Username (Locked)" class="flex items-center gap-2 px-2.5 py-1.5 rounded-2xl bg-gradient-to-r from-slate-100 to-indigo-50/60 border border-slate-200/90 shadow-sm text-left select-none cursor-pointer">
        <div class="relative">
          <span id="user-avatar-badge" class="w-7 h-7 rounded-xl bg-white border border-slate-200/80 shadow-xs flex items-center justify-center text-sm">🚀</span>
          <span class="absolute -bottom-0.5 -right-0.5 w-2 h-2 rounded-full bg-emerald-500 ring-1 ring-white"></span>
        </div>
        <div class="flex flex-col pr-1">
          <span class="text-[9px] font-bold uppercase tracking-wider text-indigo-600 leading-none flex items-center gap-1">
            Permanent ID
            <svg class="w-2.5 h-2.5 text-slate-400" fill="currentColor" viewBox="0 0 20 20">
              <path fill-rule="evenodd" d="M5 9V7a5 5 0 0110 0v2a2 2 0 012 2v5a2 2 0 01-2 2H5a2 2 0 01-2-2v-5a2 2 0 012-2zm8-2v2H7V7a3 3 0 016 0z" clip-rule="evenodd"/>
            </svg>
          </span>
          <span id="user-name-badge" class="text-xs font-bold text-slate-800 max-w-[95px] sm:max-w-[140px] truncate leading-tight">@Loading...</span>
        </div>
      </div>

      <!-- Online Indicator -->
      <div id="peers-badge" title="Active worldwide network" class="hidden md:flex items-center gap-1.5 px-2.5 py-1.5 rounded-xl bg-slate-100 text-slate-600 border border-slate-200 text-xs font-semibold">
        <span class="w-2 h-2 rounded-full bg-emerald-500"></span>
        <span id="peers-count">Live</span>
      </div>

      <!-- Sound notification toggle -->
      <button id="sound-btn" type="button" title="Toggle audio cues" class="p-2 rounded-xl bg-slate-100 hover:bg-slate-200 text-slate-600 transition-colors border border-slate-200 cursor-pointer">
        <svg id="sound-icon-on" class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15.536 8.464a5 5 0 010 7.072m2.828-9.9a9 9 0 010 12.728M5.586 15H4a1 1 0 01-1-1v-4a1 1 0 011-1h1.586l4.707-4.707C10.923 3.663 12 4.109 12 5v14c0 .891-1.077 1.337-1.707.707L5.586 15z" />
        </svg>
        <svg id="sound-icon-off" class="w-4 h-4 hidden text-slate-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5.586 15H4a1 1 0 01-1-1v-4a1 1 0 011-1h1.586l4.707-4.707C10.923 3.663 12 4.109 12 5v14c0 .891-1.077 1.337-1.707.707L5.586 15z" />
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 14l2-2m0 0l2-2m-2 2l-2-2m2 2l2 2" />
        </svg>
      </button>
    </div>
  </header>

  <!-- CHAT VIEW CONTAINER -->
  <div id="view-chat" class="flex flex-col flex-1 overflow-hidden">
    <!-- Channel Bar -->
    <div class="bg-white/80 border-b border-slate-200 px-4 py-2 flex items-center justify-between text-xs text-slate-500">
      <div class="flex items-center gap-2 overflow-x-auto no-scrollbar">
        <span class="font-medium text-slate-400 mr-1 hidden sm:inline">Rooms:</span>
        <button type="button" data-room="global" class="room-btn active px-3 py-1 rounded-lg bg-indigo-100/70 text-indigo-700 border border-indigo-300 font-semibold transition cursor-pointer">
          # worldwide-general
        </button>
        <button type="button" data-room="chill" class="room-btn px-3 py-1 rounded-lg bg-slate-100 text-slate-600 hover:text-slate-900 border border-slate-200 transition cursor-pointer">
          # chill-vibes
        </button>
        <button type="button" data-room="tech" class="room-btn px-3 py-1 rounded-lg bg-slate-100 text-slate-600 hover:text-slate-900 border border-slate-200 transition cursor-pointer">
          # gaming-tech
        </button>
      </div>
      <div class="flex items-center gap-2 text-slate-500 text-xs">
        <span id="msg-counter" class="bg-slate-100 px-2.5 py-0.5 rounded-full border border-slate-200 font-medium">0 messages</span>
      </div>
    </div>

    <!-- Messages Container -->
    <main class="flex-1 overflow-y-auto p-4 space-y-4 relative select-text bg-slate-50/60" id="chat-messages-container">
      <div id="messages-loading" class="flex flex-col items-center justify-center py-20 text-slate-400 space-y-3">
        <div class="w-8 h-8 border-3 border-indigo-600 border-t-transparent rounded-full animate-spin"></div>
        <p class="text-sm font-medium">Connecting to worldwide cloud sync...</p>
      </div>
      
      <div id="welcome-banner" class="hidden text-center max-w-md mx-auto py-8 px-4 rounded-2xl bg-white border border-slate-200 shadow-sm">
        <div class="inline-flex p-3 rounded-2xl bg-indigo-50 text-indigo-600 text-2xl mb-2">🌍</div>
        <h3 class="font-bold text-slate-800 brand-font text-lg">Welcome to chatteer live</h3>
        <p class="text-xs text-slate-600 mt-1">Open this link on any phone or computer! Messages sync across all devices.</p>
        <div class="mt-2.5 inline-flex items-center gap-1.5 px-2.5 py-1 rounded-full bg-emerald-50 border border-emerald-200 text-[11px] text-emerald-700 font-medium">
          <span>🛡</span> Strict safe chat active
        </div>
      </div>

      <!-- Active message feed -->
      <div id="messages-list" class="space-y-4 max-w-4xl mx-auto pb-4"></div>
    </main>

    <!-- Scroll Float Action -->
    <div id="scroll-bottom-container" class="relative max-w-4xl mx-auto w-full pointer-events-none">
      <button id="scroll-bottom-btn" type="button" class="pointer-events-auto absolute right-4 bottom-2 px-3 py-1.5 bg-indigo-600 hover:bg-indigo-500 text-white text-xs font-semibold rounded-full shadow-lg shadow-indigo-600/30 flex items-center gap-1.5 transition-all transform translate-y-10 opacity-0 cursor-pointer">
        <span>Latest messages</span>
        <svg class="w-3.5 h-3.5" fill="none" stroke="currentColor" viewBox="0 0 24 24">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 14l-7 7m0 0l-7-7m7 7V3"></path>
        </svg>
      </button>
    </div>

    <!-- Chat Input Footer -->
    <footer class="bg-white/95 border-t border-slate-200 p-3 sm:p-4 shrink-0 backdrop-blur-md z-20 shadow-sm">
      <div class="max-w-4xl mx-auto">
        <div class="flex items-center gap-1.5 pb-2 overflow-x-auto no-scrollbar text-lg">
          <button type="button" class="quick-emoji px-2 py-1 rounded-lg hover:bg-slate-100 transition active:scale-90 cursor-pointer">👋</button>
          <button type="button" class="quick-emoji px-2 py-1 rounded-lg hover:bg-slate-100 transition active:scale-90 cursor-pointer">✨</button>
          <button type="button" class="quick-emoji px-2 py-1 rounded-lg hover:bg-slate-100 transition active:scale-90 cursor-pointer">🔥</button>
          <button type="button" class="quick-emoji px-2 py-1 rounded-lg hover:bg-slate-100 transition active:scale-90 cursor-pointer">🎉</button>
          <button type="button" class="quick-emoji px-2 py-1 rounded-lg hover:bg-slate-100 transition active:scale-90 cursor-pointer">❤️</button>
          <button type="button" class="quick-emoji px-2 py-1 rounded-lg hover:bg-slate-100 transition active:scale-90 cursor-pointer">🚀</button>
          <button type="button" class="quick-emoji px-2 py-1 rounded-lg hover:bg-slate-100 transition active:scale-90 cursor-pointer">😂</button>
          <button type="button" class="quick-emoji px-2 py-1 rounded-lg hover:bg-slate-100 transition active:scale-90 cursor-pointer">💯</button>
        </div>

        <form id="chat-form" class="flex items-center gap-2">
          <div class="relative flex-1">
            <input
              id="message-input"
              type="text"
              maxlength="400"
              placeholder="Type a message to the world in #worldwide-general..."
              autocomplete="off"
              class="w-full bg-slate-50 text-slate-900 placeholder-slate-400 rounded-2xl px-4 py-3 text-sm focus:outline-none focus:ring-2 focus:ring-indigo-500/80 focus:bg-white border border-slate-200 transition shadow-inner"
            />
            <span id="char-limit" class="absolute right-3 top-1/2 -translate-y-1/2 text-[10px] text-slate-400 pointer-events-none hidden sm:inline">400</span>
          </div>

          <button
            type="submit"
            id="send-button"
            disabled
            class="bg-indigo-600 disabled:opacity-40 disabled:hover:bg-indigo-600 hover:bg-indigo-500 text-white font-semibold px-4 sm:px-6 py-3 rounded-2xl transition shadow-lg shadow-indigo-600/25 flex items-center justify-center gap-1.5 text-sm active:scale-95 cursor-pointer"
          >
            <span class="hidden sm:inline font-bold">Send</span>
            <svg class="w-4 h-4 transform rotate-90" fill="currentColor" viewBox="0 0 20 20">
              <path d="M10.894 2.553a1 1 0 00-1.788 0l-7 14a1 1 0 001.169 1.409l5-1.429A1 1 0 009 15.571V11a1 1 0 112 0v4.571a1 1 0 00.725.962l5 1.428a1 1 0 001.17-1.408l-7-14z"></path>
            </svg>
          </button>
        </form>
      </div>
    </footer>
  </div>

  <!-- PHOTOS VIEW CONTAINER -->
  <div id="view-photos" class="hidden flex flex-col flex-1 overflow-hidden bg-slate-50">
    <div class="bg-white border-b border-slate-200 px-3 sm:px-6 py-3 shrink-0 shadow-xs">
      <div class="max-w-6xl mx-auto flex flex-col sm:flex-row items-stretch sm:items-center justify-between gap-3">
        <!-- Search input -->
        <div class="relative flex-1 max-w-lg">
          <input
            id="photo-search-input"
            type="text"
            placeholder="Search photos by title or @creator..."
            class="w-full bg-slate-100 focus:bg-white text-slate-800 placeholder-slate-400 pl-10 pr-4 py-2 rounded-2xl text-xs sm:text-sm border border-slate-200 focus:outline-none focus:ring-2 focus:ring-indigo-500 transition shadow-inner"
          />
          <svg class="w-4 h-4 text-slate-400 absolute left-3.5 top-1/2 -translate-y-1/2" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"></path>
          </svg>
        </div>

        <!-- Post Photo button -->
        <div class="flex items-center gap-2">
          <button id="open-upload-btn" type="button" class="w-full sm:w-auto px-4 py-2 rounded-xl bg-gradient-to-r from-pink-600 via-rose-500 to-indigo-600 text-white font-bold text-xs sm:text-sm shadow-md shadow-rose-500/25 hover:from-pink-500 hover:to-indigo-500 transition-all flex items-center justify-center gap-2 cursor-pointer active:scale-95">
            <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 4v16m8-8H4"></path>
            </svg>
            <span>Post Photo</span>
            <span class="text-[10px] bg-white/20 px-1.5 py-0.5 rounded-md font-semibold">Instant HD</span>
          </button>
        </div>
      </div>
    </div>

    <!-- Photo Feed Gallery -->
    <div class="flex-1 overflow-y-auto p-4 sm:p-6" id="photo-feed-container">
      <div class="max-w-6xl mx-auto">
        <div class="flex items-center justify-between mb-4">
          <div class="flex items-center gap-2">
            <h2 class="text-base sm:text-lg font-bold brand-font text-slate-800">Worldwide Photo Showcase</h2>
            <span id="photo-count-badge" class="px-2 py-0.5 rounded-full bg-slate-200/80 text-slate-600 text-xs font-semibold">0 photos</span>
          </div>
          <span class="text-xs text-slate-400">Universal Device Display</span>
        </div>

        <!-- Cards Grid -->
        <div id="photo-grid" class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-5"></div>

        <!-- Empty state placeholder -->
        <div id="photo-empty-state" class="hidden text-center py-16 px-4 bg-white rounded-2xl border border-slate-200 mt-4 shadow-sm">
          <div class="text-4xl mb-2">📸</div>
          <h3 class="font-bold text-slate-800 text-base">No photos found</h3>
          <p class="text-xs text-slate-500 mt-1 max-w-sm mx-auto">Upload a picture from your camera roll or paste an image link to be the first creator on the feed!</p>
        </div>
      </div>
    </div>
  </div>

  <!-- POST PHOTO MODAL -->
  <div id="upload-modal" class="fixed inset-0 z-50 bg-slate-900/60 backdrop-blur-xs flex items-center justify-center p-4 hidden">
    <div class="bg-white rounded-3xl max-w-md w-full p-5 sm:p-6 border border-slate-200 shadow-2xl relative">
      <div class="flex items-center justify-between pb-3 border-b border-slate-100 mb-3">
        <div class="flex items-center gap-2">
          <span class="text-xl">📷</span>
          <h3 class="font-black brand-font text-lg text-slate-800">Post a Photo</h3>
        </div>
        <button id="close-upload-modal" type="button" class="text-slate-400 hover:text-slate-600 p-1 rounded-lg cursor-pointer">✕</button>
      </div>

      <!-- Mode Selector Tabs: Image File vs Image URL -->
      <div class="flex items-center bg-slate-100 p-1 rounded-xl mb-3 text-xs font-bold">
        <button id="tab-mode-file" type="button" class="flex-1 py-1.5 rounded-lg bg-white shadow-xs text-indigo-700 transition cursor-pointer">
          📁 Device Photo
        </button>
        <button id="tab-mode-url" type="button" class="flex-1 py-1.5 rounded-lg text-slate-600 hover:text-slate-900 transition cursor-pointer">
          🔗 Web Image Link
        </button>
      </div>

      <form id="upload-form" class="space-y-3">
        <!-- File Upload Section -->
        <div id="file-upload-section">
          <label class="block text-xs font-bold text-slate-700 uppercase tracking-wider mb-1">Pick a Photo</label>
          <div class="relative border-2 border-dashed border-indigo-200 hover:border-indigo-400 rounded-2xl p-4 text-center bg-indigo-50/40 transition">
            <input id="photo-file-input" type="file" accept="image/*" class="absolute inset-0 w-full h-full opacity-0 cursor-pointer" />
            <div id="photo-file-preview-info" class="space-y-1">
              <span class="text-2xl">🖼️</span>
              <p class="text-xs font-semibold text-slate-700" id="file-name-label">Tap to take photo or choose from library</p>
              <p class="text-[11px] text-slate-400" id="file-size-label">JPG, PNG, WebP, GIF supported</p>
            </div>
          </div>
          <!-- Preview thumbnail -->
          <div id="photo-file-preview-wrap" class="hidden mt-2 relative rounded-xl overflow-hidden max-h-36 bg-slate-100 border border-slate-200">
            <img id="photo-file-preview-img" src="" alt="Selected image preview" class="w-full h-36 object-contain" />
          </div>
        </div>

        <!-- URL Input Section -->
        <div id="url-upload-section" class="hidden">
          <label class="block text-xs font-bold text-slate-700 uppercase tracking-wider mb-1">Direct Image URL</label>
          <input
            id="photo-url-input"
            type="url"
            placeholder="https://images.unsplash.com/... or https://i.imgur.com/..."
            class="w-full bg-slate-50 border border-slate-200 rounded-xl px-3 py-2 text-xs focus:outline-none focus:ring-2 focus:ring-indigo-500 focus:bg-white"
          />
          <p class="text-[10px] text-slate-400 mt-1">Paste any public web image URL (.jpg, .png, .webp, .gif).</p>
        </div>

        <div>
          <label class="block text-xs font-bold text-slate-700 uppercase tracking-wider mb-1">Title</label>
          <input
            id="photo-title-input"
            type="text"
            maxlength="100"
            required
            placeholder="Give your photo an engaging title..."
            class="w-full bg-slate-50 border border-slate-200 rounded-xl px-3 py-2 text-xs sm:text-sm focus:outline-none focus:ring-2 focus:ring-indigo-500 focus:bg-white"
          />
        </div>

        <!-- Upload Progress Indicator -->
        <div id="upload-progress-box" class="hidden p-3 rounded-xl bg-indigo-50 border border-indigo-200 space-y-1.5">
          <div class="flex items-center justify-between text-xs font-semibold text-indigo-900">
            <span id="upload-status-text">Processing and sharing image...</span>
            <span id="upload-status-pct">0%</span>
          </div>
          <div class="w-full bg-indigo-200/60 rounded-full h-1.5 overflow-hidden">
            <div id="upload-progress-bar" class="bg-indigo-600 h-full rounded-full transition-all duration-300 w-0"></div>
          </div>
        </div>

        <div class="p-2.5 rounded-xl bg-amber-50 border border-amber-200 text-[11px] text-amber-800 flex items-start gap-2">
          <span>⚡</span>
          <span>Photos are published under your permanent handle (<strong id="upload-author-badge">@You</strong>). Safe filters active.</span>
        </div>

        <div class="flex items-center justify-end gap-2 pt-1">
          <button id="cancel-upload-btn" type="button" class="px-4 py-2 rounded-xl text-xs font-bold text-slate-500 hover:bg-slate-100 transition cursor-pointer">Cancel</button>
          <button id="submit-photo-btn" type="submit" class="px-5 py-2 rounded-xl bg-gradient-to-r from-pink-600 via-rose-600 to-indigo-600 hover:from-pink-500 hover:to-indigo-500 text-white font-bold text-xs shadow-md shadow-pink-600/30 transition active:scale-95 flex items-center gap-1.5 cursor-pointer">
            <span id="submit-btn-spinner" class="hidden w-3.5 h-3.5 border-2 border-white border-t-transparent rounded-full animate-spin"></span>
            <span id="submit-btn-text">Publish Worldwide</span>
          </button>
        </div>
      </form>
    </div>
  </div>

  <!-- PHOTO LIGHTBOX MODAL -->
  <div id="viewer-modal" class="fixed inset-0 z-50 bg-slate-950/90 backdrop-blur-md flex items-center justify-center p-2 sm:p-6 hidden">
    <div class="bg-white rounded-3xl max-w-4xl w-full overflow-hidden shadow-2xl flex flex-col border border-slate-200 max-h-[94vh]">
      <div class="relative bg-slate-950 flex items-center justify-center aspect-auto max-h-[65vh] w-full overflow-hidden">
        <img
          id="active-photo-viewer"
          src=""
          alt="Enlarged photo view"
          class="max-h-[65vh] w-full object-contain"
        />

        <button id="close-viewer-btn" type="button" class="absolute top-3 right-3 bg-black/60 hover:bg-black/80 text-white w-9 h-9 rounded-full flex items-center justify-center text-sm font-bold z-30 cursor-pointer transition">✕</button>
      </div>

      <!-- Details & Actions -->
      <div class="p-4 sm:p-5 overflow-y-auto space-y-3">
        <div class="flex flex-col sm:flex-row sm:items-center justify-between gap-3 border-b border-slate-100 pb-3">
          <div>
            <h2 id="modal-photo-title" class="text-base sm:text-xl font-extrabold text-slate-800 brand-font">Title</h2>
            <div class="flex items-center gap-2 mt-1 text-xs text-slate-500">
              <span id="modal-photo-views" class="font-bold text-indigo-600 flex items-center gap-1">👁️ 0 views</span>
              <span>•</span>
              <span id="modal-photo-date">Just now</span>
              <span>•</span>
              <a id="modal-photo-direct-link" href="#" target="_blank" rel="noopener noreferrer" class="text-indigo-600 hover:underline font-semibold">Open Full Size ↗</a>
            </div>
          </div>

          <div class="flex items-center gap-3">
            <button id="modal-like-btn" type="button" class="flex items-center gap-1.5 px-3.5 py-1.5 rounded-xl bg-pink-50 hover:bg-pink-100 text-pink-600 font-bold text-xs border border-pink-200 transition active:scale-95 cursor-pointer">
              <span id="modal-like-icon">❤️</span>
              <span id="modal-like-count">0</span>
            </button>

            <div class="flex items-center gap-2">
              <span id="modal-photo-avatar" class="w-8 h-8 rounded-xl bg-indigo-50 border border-indigo-200 flex items-center justify-center text-sm">🚀</span>
              <div class="flex flex-col">
                <span class="text-[9px] uppercase font-bold text-slate-400">Creator</span>
                <span id="modal-photo-author" class="text-xs font-bold text-slate-800">@Creator</span>
              </div>
            </div>
          </div>
        </div>

        <!-- Interactive 5-Star Rating Section -->
        <div class="p-3 bg-slate-50 rounded-2xl border border-slate-200/80 flex flex-wrap items-center justify-between gap-2">
          <div class="flex items-center gap-2">
            <span class="text-xs font-bold text-slate-700">Rating:</span>
            <div id="modal-star-group" class="flex items-center gap-1 text-lg">
              <button type="button" data-star="1" class="star-btn text-slate-300 hover:text-amber-400 transition cursor-pointer">★</button>
              <button type="button" data-star="2" class="star-btn text-slate-300 hover:text-amber-400 transition cursor-pointer">★</button>
              <button type="button" data-star="3" class="star-btn text-slate-300 hover:text-amber-400 transition cursor-pointer">★</button>
              <button type="button" data-star="4" class="star-btn text-slate-300 hover:text-amber-400 transition cursor-pointer">★</button>
              <button type="button" data-star="5" class="star-btn text-slate-300 hover:text-amber-400 transition cursor-pointer">★</button>
            </div>
            <span id="modal-rating-avg" class="text-xs font-bold text-amber-600">Unrated</span>
            <span id="modal-rating-count" class="text-[11px] text-slate-400 font-medium">(0)</span>
          </div>
          <span id="modal-user-rated-status" class="text-[11px] text-indigo-600 font-semibold">Tap a star to rate!</span>
        </div>

        <p class="text-xs text-slate-500">Published to the Chatteer Worldwide Public Photo Feed.</p>
      </div>
    </div>
  </div>

  <div id="toast-container" class="fixed top-16 right-4 z-50 flex flex-col gap-2 pointer-events-none"></div>

  <!-- APPLICATION JAVASCRIPT -->
  <script type="module">
    import { initializeApp } from "https://www.gstatic.com/firebasejs/11.6.1/firebase-app.js";
    import {
      getAuth,
      signInAnonymously,
      signInWithCustomToken,
      onAuthStateChanged
    } from "https://www.gstatic.com/firebasejs/11.6.1/firebase-auth.js";
    import {
      getFirestore
    } from "https://www.gstatic.com/firebasejs/11.6.1/firebase-firestore.js";

    // --- INDEXEDDB STORAGE FOR HIGH-RESOLUTION LOCAL IMAGES ---
    const IDB_NAME = 'chatteer_photos_db';
    const IDB_VERSION = 1;
    const IDB_STORE = 'photos';

    function openIDB() {
      return new Promise((resolve) => {
        if (!('indexedDB' in window)) {
          resolve(null);
          return;
        }
        const req = indexedDB.open(IDB_NAME, IDB_VERSION);
        req.onupgradeneeded = (e) => {
          const db = e.target.result;
          if (!db.objectStoreNames.contains(IDB_STORE)) {
            db.createObjectStore(IDB_STORE, { keyPath: 'id' });
          }
        };
        req.onsuccess = () => resolve(req.result);
        req.onerror = () => resolve(null);
      });
    }

    async function savePhotoToIDB(id, dataUrl) {
      try {
        const db = await openIDB();
        if (!db) return false;
        return new Promise((resolve) => {
          const tx = db.transaction(IDB_STORE, 'readwrite');
          tx.objectStore(IDB_STORE).put({ id, dataUrl, savedAt: Date.now() });
          tx.oncomplete = () => resolve(true);
          tx.onerror = () => resolve(false);
        });
      } catch (err) {
        return false;
      }
    }

    async function getPhotoFromIDB(id) {
      try {
        const db = await openIDB();
        if (!db) return null;
        return new Promise((resolve) => {
          const tx = db.transaction(IDB_STORE, 'readonly');
          const req = tx.objectStore(IDB_STORE).get(id);
          req.onsuccess = () => resolve(req.result ? req.result.dataUrl : null);
          req.onerror = () => resolve(null);
        });
      } catch (err) {
        return null;
      }
    }

    // --- PERMANENT UNIQUE IDENTITY GENERATOR ---
    const AVATAR_OPTIONS = ['🚀', '🦊', '⚡', '👾', '🌺', '🪐', '🐱', '🍕', '🐼', '💎', '🎸', '🌈', '🐯', '🌟', '🐬', '🍀'];
    const ADJECTIVES = [
      'Swift', 'Cosmic', 'Pixel', 'Nova', 'Hyper', 'Neon', 'Aero', 'Solar', 'Echo', 'Apex',
      'Quantum', 'Frost', 'Vortex', 'Cyber', 'Shadow', 'Blaze', 'Stellar', 'Turbo', 'Mystic', 'Iron',
      'Zenith', 'Prism', 'Orbit', 'Pulse', 'Astro', 'Flare', 'Cobalt', 'Sonic', 'Titan', 'Zephyr'
    ];
    const NOUNS = [
      'Pilot', 'Fox', 'Rider', 'Spark', 'Rover', 'Wave', 'Ninja', 'Falcon', 'Orbit', 'Wolf',
      'Phoenix', 'Tiger', 'Comet', 'Knight', 'Ranger', 'Striker', 'Titan', 'Drifter', 'Ghost', 'Scout',
      'Voyager', 'Falcon', 'Hawk', 'Hunter', 'Echo', 'Legend', 'Matrix', 'Lynx', 'Viper', 'Beacon'
    ];

    let myProfile = {
      name: '',
      avatar: '🚀'
    };

    function generateCandidateName() {
      const adj = ADJECTIVES[Math.floor(Math.random() * ADJECTIVES.length)];
      const noun = NOUNS[Math.floor(Math.random() * NOUNS.length)];
      const num = Math.floor(1000 + Math.random() * 9000);
      return `${adj}${noun}_${num}`;
    }

    function initPermanentIdentity() {
      try {
        const storedName = localStorage.getItem('chatteer_perm_username');
        const storedAvatar = localStorage.getItem('chatteer_perm_avatar');

        if (storedName && storedAvatar) {
          myProfile.name = storedName;
          myProfile.avatar = storedAvatar;
          updateProfileUI();
          return;
        }

        const newName = generateCandidateName();
        const newAvatar = AVATAR_OPTIONS[Math.floor(Math.random() * AVATAR_OPTIONS.length)];

        myProfile.name = newName;
        myProfile.avatar = newAvatar;

        localStorage.setItem('chatteer_perm_username', newName);
        localStorage.setItem('chatteer_perm_avatar', newAvatar);
      } catch (e) {
        if (!myProfile.name) {
          myProfile.name = `Pilot_${Math.floor(1000 + Math.random() * 9000)}`;
        }
      }
      updateProfileUI();
    }

    // --- APPLICATION STATE ---
    let currentRoom = 'global';
    let soundEnabled = true;
    let currentUser = null;
    let allMessages = [];
    let isAutoScrollActive = true;
    let db = null;
    let auth = null;
    let activeEventSource = null;

    let currentTab = 'chat'; // 'chat' or 'photos'
    let allPhotos = [];
    let selectedImageBase64 = null;
    let photoEventSource = null;
    let currentActivePhoto = null;
    let currentUploadMode = 'file';

    // --- SAFETY FILTERS AND WORD SANITIZATION ---
    const BAD_WORD_LIST = [
      'discord',
      'fuck', 'fucking', 'fucked', 'fucker', 'fuckin', 'fck', 'fuk',
      'shit', 'shitty', 'shitting', 'bullshit', 'shite',
      'bitch', 'bitches', 'bitching', 'bitchy',
      'ass', 'asshole', 'assholes', 'dumbass', 'jackass', 'badass', 'arse', 'arsehole',
      'bastard', 'bastards',
      'damn', 'dammit', 'damned',
      'crap', 'crappy',
      'hell',
      'piss', 'pissed', 'pissing',
      'dick', 'dicks', 'dickhead',
      'cock', 'cocks', 'cocksucker',
      'pussy', 'pussies',
      'cunt', 'cunts',
      'whore', 'whores',
      'slut', 'sluts', 'slutty',
      'douche', 'douchebag',
      'retard', 'retarded',
      'fag', 'faggot', 'faggots',
      'nazi', 'hitler',
      'porn', 'porno', 'pornography', 'xxx', 'hentai',
      'nsfw', 'nude', 'nudes', 'naked', 'nudity',
      'sex', 'sexy',
      'boob', 'boobs', 'tit', 'tits', 'titties',
      'penis', 'vagina'
    ];
    const BAD_WORD_SET = new Set(BAD_WORD_LIST);

    const ADVANCED_PATTERNS = [
      /\bd[1i!|][s5$][c(][o0]rd\b/gi,
      /d+[._\s-]*i+[._\s-]*s+[._\s-]*c+[._\s-]*o+[._\s-]*r+[._\s-]*d+/gi,
      /f+[._\s-]*[u*]+[._\s-]*c+[._\s-]*k+[a-z]*/gi,
      /s+[._\s-]*h+[._\s-]*[i!1*]+[._\s-]*t+[a-z]*/gi,
      /b+[._\s-]*[i!1*]+[._\s-]*t+[._\s-]*c+[._\s-]*h+[a-z]*/gi,
      /\b(a+[._\s-]*[s$5*]+[._\s-]*[s$5*]+(h+[o0]+l+e+s?|e+s?|h+e+a+d+)?)\b/gi,
      /b+[._\s-]*a+[._\s-]*s+[._\s-]*t+[._\s-]*a+[._\s-]*r+[._\s-]*d+[a-z]*/gi,
      /d+[._\s-]*[i!1]+[._\s-]*c+[._\s-]*k+[a-z]*/gi,
      /c+[._\s-]*[o0]+[._\s-]*c+[._\s-]*k+[a-z]*/gi,
      /p+[._\s-]*u+[._\s-]*s+[._\s-]*s+[._\s-]*y+/gi,
      /c+[._\s-]*u+[._\s-]*n+[._\s-]*t+[a-z]*/gi,
      /w+[._\s-]*h+[._\s-]*[o0]+[._\s-]*r+[._\s-]*e+[a-z]*/gi,
      /s+[._\s-]*l+[._\s-]*u+[._\s-]*t+[a-z]*/gi,
      /d+[._\s-]*a+[._\s-]*m+[._\s-]*n+[a-z]*/gi,
      /p+[._\s-]*[i!1]+[._\s-]*s+[._\s-]*s+[a-z]*/gi,
      /d+[._\s-]*o+[._\s-]*u+[._\s-]*c+[._\s-]*h+[._\s-]*e+/gi,
      /r+[._\s-]*e+[._\s-]*t+[._\s-]*a+[._\s-]*r+[._\s-]*d+/gi,
      /f+[._\s-]*a+[._\s-]*g+[a-z]*/gi,
      /\b(p+[._\s-]*o+[._\s-]*r+[._\s-]*n+[o0]?|n+[._\s-]*u+[._\s-]*d+[._\s-]*e+s?|s+[._\s-]*e+[._\s-]*x+y?|h+[._\s-]*e+[._\s-]*n+[._\s-]*t+[._\s-]*a+[._\s-]*[i!]|x{3,}|n+s+f+w)\b/gi
    ];

    function normalizeLeetspeak(str) {
      return str
        .toLowerCase()
        .replace(/[@4]/g, 'a')
        .replace(/[$5]/g, 's')
        .replace(/[0]/g, 'o')
        .replace(/[1!|]/g, 'i')
        .replace(/[3]/g, 'e')
        .replace(/[7+]/g, 't')
        .replace(/[8]/g, 'b');
    }

    function sanitizeContent(text) {
      if (!text) return '';
      let filtered = String(text);

      ADVANCED_PATTERNS.forEach((pattern) => {
        filtered = filtered.replace(pattern, (match) => '#'.repeat(match.length));
      });

      filtered = filtered.replace(/[^\s]+/g, (token) => {
        if (/^#+$/.test(token)) return token;
        const prefix = token.match(/^[^\w]+/)?.[0] || '';
        const suffix = token.match(/[^\w]+$/)?.[0] || '';
        const rawCore = token.slice(prefix.length, token.length - suffix.length);
        if (!rawCore) return token;

        const normalizedCore = normalizeLeetspeak(rawCore).replace(/[\W_]+/g, '');
        if (BAD_WORD_SET.has(normalizedCore)) {
          return prefix + '#'.repeat(rawCore.length) + suffix;
        }
        return token;
      });

      return filtered;
    }

    // --- DOM REFERENCES ---
    const chatContainer = document.getElementById('chat-messages-container');
    const messagesList = document.getElementById('messages-list');
    const loadingElem = document.getElementById('messages-loading');
    const welcomeBanner = document.getElementById('welcome-banner');
    const statusText = document.getElementById('connection-status');
    const connectionDot = document.getElementById('connection-dot');
    const peersBadge = document.getElementById('peers-badge');
    const peersCount = document.getElementById('peers-count');
    const chatForm = document.getElementById('chat-form');
    const messageInput = document.getElementById('message-input');
    const sendButton = document.getElementById('send-button');
    const scrollBottomBtn = document.getElementById('scroll-bottom-btn');
    const msgCounter = document.getElementById('msg-counter');
    const profileToggleBtn = document.getElementById('profile-toggle-btn');
    const userNameBadge = document.getElementById('user-name-badge');
    const userAvatarBadge = document.getElementById('user-avatar-badge');
    const soundBtn = document.getElementById('sound-btn');
    const soundIconOn = document.getElementById('sound-icon-on');
    const soundIconOff = document.getElementById('sound-icon-off');

    const pageNavBtn = document.getElementById('page-nav-btn');
    const pageNavIcon = document.getElementById('page-nav-icon');
    const pageNavLabel = document.getElementById('page-nav-label');
    const viewChat = document.getElementById('view-chat');
    const viewPhotos = document.getElementById('view-photos');
    const photoGrid = document.getElementById('photo-grid');
    const photoEmptyState = document.getElementById('photo-empty-state');
    const photoCountBadge = document.getElementById('photo-count-badge');
    const photoSearchInput = document.getElementById('photo-search-input');
    const openUploadBtn = document.getElementById('open-upload-btn');
    const uploadModal = document.getElementById('upload-modal');
    const closeUploadModal = document.getElementById('close-upload-modal');
    const cancelUploadBtn = document.getElementById('cancel-upload-btn');
    const uploadForm = document.getElementById('upload-form');
    const photoFileInput = document.getElementById('photo-file-input');
    const photoTitleInput = document.getElementById('photo-title-input');
    const fileNameLabel = document.getElementById('file-name-label');
    const fileSizeLabel = document.getElementById('file-size-label');
    const uploadAuthorBadge = document.getElementById('upload-author-badge');
    const photoFilePreviewWrap = document.getElementById('photo-file-preview-wrap');
    const photoFilePreviewImg = document.getElementById('photo-file-preview-img');

    const tabModeFile = document.getElementById('tab-mode-file');
    const tabModeUrl = document.getElementById('tab-mode-url');
    const fileUploadSection = document.getElementById('file-upload-section');
    const urlUploadSection = document.getElementById('url-upload-section');
    const photoUrlInput = document.getElementById('photo-url-input');
    const uploadProgressBox = document.getElementById('upload-progress-box');
    const uploadStatusText = document.getElementById('upload-status-text');
    const uploadStatusPct = document.getElementById('upload-status-pct');
    const uploadProgressBar = document.getElementById('upload-progress-bar');
    const submitBtnSpinner = document.getElementById('submit-btn-spinner');
    const submitBtnText = document.getElementById('submit-btn-text');

    const viewerModal = document.getElementById('viewer-modal');
    const activePhotoViewer = document.getElementById('active-photo-viewer');
    const closeViewerBtn = document.getElementById('close-viewer-btn');
    const modalPhotoTitle = document.getElementById('modal-photo-title');
    const modalPhotoViews = document.getElementById('modal-photo-views');
    const modalPhotoDate = document.getElementById('modal-photo-date');
    const modalPhotoAvatar = document.getElementById('modal-photo-avatar');
    const modalPhotoAuthor = document.getElementById('modal-photo-author');
    const modalPhotoDirectLink = document.getElementById('modal-photo-direct-link');
    const modalLikeBtn = document.getElementById('modal-like-btn');
    const modalLikeCount = document.getElementById('modal-like-count');

    // --- IMAGE RESIZING AND COMPRESSION UTILITIES ---
    function compressImageFile(file, maxWidth = 1200, quality = 0.82) {
      return new Promise((resolve, reject) => {
        const reader = new FileReader();
        reader.readAsDataURL(file);
        reader.onload = (event) => {
          const img = new Image();
          img.src = event.target.result;
          img.onload = () => {
            const canvas = document.createElement('canvas');
            let width = img.width;
            let height = img.height;

            if (width > maxWidth) {
              height = Math.round((height * maxWidth) / width);
              width = maxWidth;
            }

            canvas.width = width;
            canvas.height = height;
            const ctx = canvas.getContext('2d');
            ctx.drawImage(img, 0, 0, width, height);

            const compressedDataUrl = canvas.toDataURL('image/jpeg', quality);
            resolve(compressedDataUrl);
          };
          img.onerror = () => reject(new Error('Failed to load image'));
        };
        reader.onerror = () => reject(new Error('Failed to read file'));
      });
    }

    async function uploadImageToCDN(file) {
      if (uploadProgressBox) uploadProgressBox.classList.remove('hidden');
      if (uploadStatusText) uploadStatusText.textContent = 'Uploading image to global CDN...';
      if (uploadStatusPct) uploadStatusPct.textContent = '35%';
      if (uploadProgressBar) uploadProgressBar.style.width = '35%';

      try {
        const formData = new FormData();
        formData.append('reqtype', 'fileupload');
        formData.append('time', '72h');
        formData.append('fileToUpload', file);

        if (uploadStatusPct) uploadStatusPct.textContent = '70%';
        if (uploadProgressBar) uploadProgressBar.style.width = '70%';

        const res = await fetch('https://litterbox.catbox.moe/resources/internals/api.php', {
          method: 'POST',
          body: formData
        });

        if (res.ok) {
          const directUrl = (await res.text()).trim();
          if (directUrl && directUrl.startsWith('http')) {
            if (uploadProgressBar) uploadProgressBar.style.width = '100%';
            if (uploadStatusPct) uploadStatusPct.textContent = '100%';
            return directUrl;
          }
        }
      } catch (err) {}

      try {
        const formData = new FormData();
        formData.append('file', file);

        const res = await fetch('https://tmpfiles.org/api/v1/upload', {
          method: 'POST',
          body: formData
        });

        if (res.ok) {
          const json = await res.json();
          if (json?.data?.url) {
            if (uploadProgressBar) uploadProgressBar.style.width = '100%';
            if (uploadStatusPct) uploadStatusPct.textContent = '100%';
            return json.data.url.replace('tmpfiles.org/', 'tmpfiles.org/dl/');
          }
        }
      } catch (err) {}

      return null;
    }

    // --- PHOTO SHOWCASE STATE AND CALCULATIONS ---
    function getPhotoTopic() {
      return `chatteer_worldwide_photos_hub`;
    }

    function getRatingStats(photo) {
      if (!photo.ratings || typeof photo.ratings !== 'object') {
        return { avg: 0, count: 0 };
      }
      const vals = Object.values(photo.ratings).map(Number).filter(n => !isNaN(n) && n >= 1 && n <= 5);
      if (vals.length === 0) return { avg: 0, count: 0 };
      const sum = vals.reduce((a, b) => a + b, 0);
      return {
        avg: Number((sum / vals.length).toFixed(1)),
        count: vals.length
      };
    }

    function initPhotos() {
      try {
        const stored = localStorage.getItem('chatteer_worldwide_photos');
        if (stored) {
          const parsed = JSON.parse(stored);
          allPhotos = Array.isArray(parsed) ? parsed : [];
        } else {
          allPhotos = [];
        }
      } catch (e) {
        allPhotos = [];
      }
    }

    function savePhotosLocally() {
      try {
        const serializable = allPhotos.map(p => ({
          id: p.id,
          title: p.title,
          author: p.author,
          avatar: p.avatar,
          views: p.views || 0,
          likes: p.likes || 0,
          ratings: p.ratings || {},
          createdAt: p.createdAt,
          url: p.url && !p.url.startsWith('data:') ? p.url : ''
        }));
        localStorage.setItem('chatteer_worldwide_photos', JSON.stringify(serializable));
      } catch (e) {}
    }

    function updateModalRatingDisplay(photo) {
      const stats = getRatingStats(photo);
      const myRating = (photo.ratings && photo.ratings[myProfile.name]) || 0;
      
      const stars = document.querySelectorAll('.star-btn');
      stars.forEach(btn => {
        const starNum = Number(btn.getAttribute('data-star'));
        if (myRating >= starNum) {
          btn.className = 'star-btn text-amber-400 font-bold scale-110 transition cursor-pointer';
        } else {
          btn.className = 'star-btn text-slate-300 hover:text-amber-400 transition cursor-pointer';
        }
      });

      const avgEl = document.getElementById('modal-rating-avg');
      const countEl = document.getElementById('modal-rating-count');
      const statusEl = document.getElementById('modal-user-rated-status');

      if (avgEl) avgEl.textContent = stats.count > 0 ? `★ ${stats.avg}` : 'Unrated';
      if (countEl) countEl.textContent = `(${stats.count} rating${stats.count === 1 ? '' : 's'})`;
      if (statusEl) {
        statusEl.textContent = myRating > 0 ? `You rated this ${myRating} ★` : 'Tap a star to rate!';
      }
    }

    async function openPhotoViewer(photo) {
      currentActivePhoto = photo;
      if (modalPhotoTitle) modalPhotoTitle.textContent = sanitizeContent(photo.title);
      if (modalPhotoAuthor) modalPhotoAuthor.textContent = `@${photo.author}`;
      if (modalPhotoAvatar) modalPhotoAvatar.textContent = photo.avatar || '🚀';
      if (modalPhotoDate) modalPhotoDate.textContent = `${formatDate(photo.createdAt)} at ${formatTime(photo.createdAt)}`;
      if (modalLikeCount) modalLikeCount.textContent = photo.likes || 0;

      updateModalRatingDisplay(photo);

      photo.views = (photo.views || 0) + 1;
      if (modalPhotoViews) modalPhotoViews.textContent = `👁️️ ${photo.views} views`;
      renderPhotos();
      savePhotosLocally();

      let displaySrc = photo.url;
      if (!displaySrc) {
        const idbData = await getPhotoFromIDB(photo.id);
        if (idbData) displaySrc = idbData;
      }

      if (activePhotoViewer) activePhotoViewer.src = displaySrc || 'https://placehold.co/600x400/222/fff?text=Photo';
      if (modalPhotoDirectLink) modalPhotoDirectLink.href = displaySrc || '#';

      if (viewerModal) viewerModal.classList.remove('hidden');

      try {
        fetch(`https://ntfy.sh/${getPhotoTopic()}`, {
          method: 'POST',
          body: JSON.stringify({
            type: 'photo_stat_update',
            photoId: photo.id,
            views: photo.views,
            likes: photo.likes || 0
          })
        });
      } catch (e) {}
    }

    // --- RENDER PHOTOS GRID ---
    function renderPhotos() {
      if (!photoGrid || !photoCountBadge) return;
      const query = (photoSearchInput ? photoSearchInput.value : '').toLowerCase().trim();
      const filtered = allPhotos.filter(p => {
        if (!query) return true;
        const matchTitle = (p.title || '').toLowerCase().includes(query);
        const matchAuthor = (p.author || '').toLowerCase().includes(query.replace('@', ''));
        return matchTitle || matchAuthor;
      });

      photoCountBadge.textContent = `${filtered.length} photo${filtered.length === 1 ? '' : 's'}`;

      if (filtered.length === 0) {
        photoGrid.innerHTML = '';
        if (photoEmptyState) photoEmptyState.classList.remove('hidden');
        return;
      }

      if (photoEmptyState) photoEmptyState.classList.add('hidden');
      photoGrid.innerHTML = '';

      filtered.forEach((photo) => {
        const card = document.createElement('div');
        card.className = 'group bg-white rounded-2xl border border-slate-200 overflow-hidden shadow-xs hover:shadow-lg transition-all duration-300 flex flex-col cursor-pointer';

        const previewWrap = document.createElement('div');
        previewWrap.className = 'relative bg-slate-900 aspect-square flex items-center justify-center overflow-hidden';

        const img = document.createElement('img');
        img.loading = 'lazy';
        img.alt = photo.title || 'Photo';
        img.className = 'w-full h-full object-cover group-hover:scale-105 transition-transform duration-300';

        if (photo.url) {
          img.src = photo.url;
        } else {
          img.src = 'https://placehold.co/400x400/1e293b/cbd5e1?text=Loading...';
          getPhotoFromIDB(photo.id).then((dataUrl) => {
            if (dataUrl) img.src = dataUrl;
          });
        }

        previewWrap.appendChild(img);

        const cardBody = document.createElement('div');
        cardBody.className = 'p-3 flex flex-col flex-1 justify-between gap-2';

        const cardHeader = document.createElement('div');
        cardHeader.className = 'flex items-start gap-2';
        cardHeader.innerHTML = `
          <div class="w-7 h-7 rounded-xl bg-indigo-50 border border-indigo-200 flex items-center justify-center text-xs shrink-0 mt-0.5 select-none">
            ${escapeHtml(photo.avatar || '🚀')}
          </div>
          <div class="flex-1 min-w-0">
            <h3 class="font-bold text-xs sm:text-sm text-slate-800 line-clamp-1 leading-tight">${escapeHtml(photo.title)}</h3>
            <span class="text-[10px] text-slate-500 font-medium">@${escapeHtml(photo.author)}</span>
          </div>
        `;

        const stats = getRatingStats(photo);
        const ratingBadge = stats.count > 0 ? `★ ${stats.avg}` : `☆ New`;

        const cardFooter = document.createElement('div');
        cardFooter.className = 'flex items-center justify-between text-[11px] text-slate-400 border-t border-slate-100 pt-2';
        cardFooter.innerHTML = `
          <div class="flex items-center gap-2">
            <span class="font-semibold text-indigo-600">👁️ ${photo.views || 1}</span>
            <span class="font-semibold text-pink-600 flex items-center gap-1">❤️ ${photo.likes || 0}</span>
            <span class="font-bold text-amber-500 flex items-center gap-0.5" title="${stats.count} ratings">${ratingBadge}</span>
          </div>
          <span>${formatDate(photo.createdAt)}</span>
        `;

        cardBody.appendChild(cardHeader);
        cardBody.appendChild(cardFooter);
        card.appendChild(previewWrap);
        card.appendChild(cardBody);

        card.addEventListener('click', () => openPhotoViewer(photo));
        photoGrid.appendChild(card);
      });
    }

    // --- REAL-TIME PHOTO CLOUD SYNC ---
    async function loadServerPhotos() {
      try {
        const res = await fetch(`https://ntfy.sh/${getPhotoTopic()}/json?poll=1`);
        if (!res.ok) return;
        const text = await res.text();
        const lines = text.trim().split('\n');
        let hasNew = false;

        lines.forEach(line => {
          if (!line) return;
          try {
            const entry = JSON.parse(line);
            if (entry.event === 'message' && entry.message) {
              const pData = JSON.parse(entry.message);
              if (pData.type === 'photo_post' && pData.photo) {
                if (!allPhotos.some(p => p.id === pData.photo.id)) {
                  allPhotos.unshift(pData.photo);
                  hasNew = true;
                }
              } else if (pData.type === 'photo_stat_update') {
                const target = allPhotos.find(p => p.id === pData.photoId);
                if (target) {
                  target.views = Math.max(target.views || 0, pData.views || 0);
                  target.likes = Math.max(target.likes || 0, pData.likes || 0);
                  hasNew = true;
                }
              } else if (pData.type === 'photo_rate') {
                const target = allPhotos.find(p => p.id === pData.photoId);
                if (target) {
                  if (!target.ratings) target.ratings = {};
                  target.ratings[pData.user] = pData.rating;
                  hasNew = true;
                }
              }
            }
          } catch (e) {}
        });

        if (hasNew) {
          renderPhotos();
          savePhotosLocally();
        }
      } catch (e) {}
    }

    function connectToPhotoServer() {
      loadServerPhotos();
      if (photoEventSource) {
        photoEventSource.close();
      }
      try {
        photoEventSource = new EventSource(`https://ntfy.sh/${getPhotoTopic()}/sse`);
        photoEventSource.onmessage = (event) => {
          try {
            const data = JSON.parse(event.data);
            if (data.event === 'message' && data.message) {
              const payload = JSON.parse(data.message);
              if (payload.type === 'photo_post' && payload.photo) {
                if (!allPhotos.some(p => p.id === payload.photo.id)) {
                  allPhotos.unshift(payload.photo);
                  renderPhotos();
                  savePhotosLocally();
                  showToast(`📸 New photo from @${payload.photo.author}!`);
                }
              } else if (payload.type === 'photo_stat_update') {
                const target = allPhotos.find(p => p.id === payload.photoId);
                if (target) {
                  target.views = Math.max(target.views || 0, payload.views || 0);
                  target.likes = Math.max(target.likes || 0, payload.likes || 0);
                  renderPhotos();
                  if (currentActivePhoto && currentActivePhoto.id === target.id) {
                    if (modalPhotoViews) modalPhotoViews.textContent = `👁️ ${target.views} views`;
                    if (modalLikeCount) modalLikeCount.textContent = target.likes;
                  }
                }
              } else if (payload.type === 'photo_rate') {
                const target = allPhotos.find(p => p.id === payload.photoId);
                if (target) {
                  if (!target.ratings) target.ratings = {};
                  target.ratings[payload.user] = payload.rating;
                  renderPhotos();
                  savePhotosLocally();
                  if (currentActivePhoto && currentActivePhoto.id === target.id) {
                    updateModalRatingDisplay(target);
                  }
                }
              }
            }
          } catch (e) {}
        };
      } catch (e) {}
    }

    // --- REAL-TIME CHAT PROTOCOL ---
    function getRoomTopic(room) {
      return `chatteer_worldwide_room_${room}`;
    }

    function renderMessages() {
      if (!messagesList) return;
      messagesList.innerHTML = '';

      if (loadingElem) {
        loadingElem.classList.add('hidden');
      }

      if (allMessages.length === 0) {
        if (welcomeBanner) welcomeBanner.classList.remove('hidden');
        if (msgCounter) msgCounter.textContent = '0 messages';
        return;
      }

      if (welcomeBanner) welcomeBanner.classList.add('hidden');
      if (msgCounter) msgCounter.textContent = `${allMessages.length} message${allMessages.length === 1 ? '' : 's'}`;

      let lastDate = '';

      allMessages.forEach((msg) => {
        const msgDate = formatDate(msg.createdAt);
        if (msgDate && msgDate !== lastDate) {
          lastDate = msgDate;
          const dateDivider = document.createElement('div');
          dateDivider.className = 'flex items-center justify-center my-3';
          dateDivider.innerHTML = `<span class="px-2.5 py-0.5 rounded-full bg-slate-200/70 text-[10px] font-semibold text-slate-500 uppercase tracking-wider">${msgDate}</span>`;
          messagesList.appendChild(dateDivider);
        }

        const isMe = msg.userName === myProfile.name;
        const row = document.createElement('div');
        row.className = `flex items-end gap-2 ${isMe ? 'justify-end' : 'justify-start'}`;

        const avatarMarkup = `
          <div class="w-8 h-8 rounded-xl bg-white border border-slate-200/90 shadow-xs flex items-center justify-center text-sm shrink-0 mb-1 select-none">
            ${escapeHtml(msg.userAvatar || '🚀')}
          </div>
        `;

        const bubble = document.createElement('div');
        bubble.className = `max-w-[85%] sm:max-w-[70%] flex flex-col ${isMe ? 'items-end' : 'items-start'}`;

        const meta = `
          <div class="flex items-center gap-1.5 px-1 mb-1 text-[11px] text-slate-400 font-medium">
            <span class="font-bold ${isMe ? 'text-indigo-600' : 'text-slate-700'}">@${escapeHtml(msg.userName)}</span>
            <span>•</span>
            <span>${formatTime(msg.createdAt)}</span>
          </div>
        `;

        const textContent = sanitizeContent(msg.text);
        const bubbleBody = document.createElement('div');
        bubbleBody.className = isMe
          ? 'px-4 py-2.5 rounded-2xl rounded-br-xs bg-gradient-to-r from-indigo-600 to-violet-600 text-white shadow-md shadow-indigo-600/15 text-xs sm:text-sm font-normal break-words leading-relaxed'
          : 'px-4 py-2.5 rounded-2xl rounded-bl-xs bg-white text-slate-800 border border-slate-200/80 shadow-xs text-xs sm:text-sm font-normal break-words leading-relaxed';
        bubbleBody.textContent = textContent;

        bubble.innerHTML = meta;
        bubble.appendChild(bubbleBody);

        if (isMe) {
          row.appendChild(bubble);
          row.insertAdjacentHTML('beforeend', avatarMarkup);
        } else {
          row.insertAdjacentHTML('afterbegin', avatarMarkup);
          row.appendChild(bubble);
        }

        messagesList.appendChild(row);
      });

      if (isAutoScrollActive) {
        scrollToBottom(false);
      }
    }

    async function connectToServer(room) {
      currentRoom = room;
      if (statusText) statusText.textContent = 'Connecting...';
      if (connectionDot) connectionDot.className = 'w-1.5 h-1.5 rounded-full bg-amber-400 animate-ping';
      if (loadingElem) loadingElem.classList.remove('hidden');

      if (activeEventSource) {
        activeEventSource.close();
      }

      try {
        const response = await fetch(`https://ntfy.sh/${getRoomTopic(room)}/json?poll=1`);
        if (response.ok) {
          const text = await response.text();
          const lines = text.trim().split('\n');
          const loaded = [];

          lines.forEach((line) => {
            if (!line) return;
            try {
              const entry = JSON.parse(line);
              if (entry.event === 'message' && entry.message) {
                const payload = JSON.parse(entry.message);
                if (payload.type === 'chat_msg' && payload.text) {
                  loaded.push(payload);
                }
              }
            } catch (err) {}
          });

          if (loaded.length > 0) {
            allMessages = loaded.sort((a, b) => (a.createdAt || 0) - (b.createdAt || 0));
          } else {
            allMessages = [];
          }
        }
      } catch (err) {
      } finally {
        if (loadingElem) loadingElem.classList.add('hidden');
        if (statusText) statusText.textContent = 'Live Cloud';
        if (connectionDot) connectionDot.className = 'w-1.5 h-1.5 rounded-full bg-emerald-500 animate-pulse';
        if (peersCount) peersCount.textContent = 'Online';
        renderMessages();
      }

      try {
        activeEventSource = new EventSource(`https://ntfy.sh/${getRoomTopic(room)}/sse`);

        activeEventSource.onopen = () => {
          if (statusText) statusText.textContent = 'Live Cloud';
          if (connectionDot) connectionDot.className = 'w-1.5 h-1.5 rounded-full bg-emerald-500 animate-pulse';
          if (peersCount) peersCount.textContent = 'Online';
        };

        activeEventSource.onmessage = (event) => {
          try {
            const data = JSON.parse(event.data);
            if (data.event === 'message' && data.message) {
              const payload = JSON.parse(data.message);
              if (payload.type === 'chat_msg' && payload.text) {
                if (!allMessages.some((m) => m.id === payload.id)) {
                  allMessages.push(payload);
                  renderMessages();
                  if (payload.userName !== myProfile.name) {
                    playAudioTone(520);
                  }
                }
              }
            }
          } catch (e) {}
        };

        activeEventSource.onerror = () => {
          if (statusText) statusText.textContent = 'Reconnecting...';
          if (connectionDot) connectionDot.className = 'w-1.5 h-1.5 rounded-full bg-amber-500 animate-ping';
        };
      } catch (err) {
        if (statusText) statusText.textContent = 'Live Cloud';
        if (connectionDot) connectionDot.className = 'w-1.5 h-1.5 rounded-full bg-emerald-500';
      }
    }

    async function sendChatMessage(rawText) {
      const text = rawText.trim();
      if (!text) return;

      const cleanText = sanitizeContent(text);
      const newMsg = {
        id: 'msg_' + Date.now() + '_' + Math.random().toString(36).substring(2, 7),
        roomId: currentRoom,
        userName: myProfile.name,
        userAvatar: myProfile.avatar,
        text: cleanText,
        createdAt: Date.now(),
        type: 'chat_msg'
      };

      allMessages.push(newMsg);
      renderMessages();
      playAudioTone(640);
      scrollToBottom();

      try {
        await fetch(`https://ntfy.sh/${getRoomTopic(currentRoom)}`, {
          method: 'POST',
          body: JSON.stringify(newMsg)
        });
      } catch (err) {}
    }

    function setupFirebase() {
      if (typeof __firebase_config === 'undefined') return;
      try {
        const firebaseConfig = JSON.parse(__firebase_config);
        const app = initializeApp(firebaseConfig);
        auth = getAuth(app);
        db = getFirestore(app);

        const initAuth = typeof __initial_auth_token !== 'undefined'
          ? signInWithCustomToken(auth, __initial_auth_token)
          : signInAnonymously(auth);

        initAuth.then((cred) => {
          currentUser = cred.user;
          onAuthStateChanged(auth, (usr) => {
            if (usr) currentUser = usr;
          });
        }).catch(() => {});
      } catch (e) {}
    }

    function updateProfileUI() {
      if (userNameBadge) userNameBadge.textContent = `@${myProfile.name}`;
      if (userAvatarBadge) userAvatarBadge.textContent = myProfile.avatar;
      if (uploadAuthorBadge) uploadAuthorBadge.textContent = `@${myProfile.name}`;
    }

    function escapeHtml(text) {
      if (!text) return '';
      return String(text)
        .replace(/&/g, '&amp;')
        .replace(/</g, '&lt;')
        .replace(/>/g, '&gt;')
        .replace(/"/g, '&quot;')
        .replace(/'/g, '&#039;');
    }

    function formatTime(timestamp) {
      if (!timestamp) return '';
      const date = new Date(timestamp);
      return date.toLocaleTimeString([], { hour: '2-digit', minute: '2-digit' });
    }

    function formatDate(timestamp) {
      if (!timestamp) return '';
      const date = new Date(timestamp);
      const today = new Date();
      if (date.toDateString() === today.toDateString()) {
        return 'Today';
      }
      return date.toLocaleDateString([], { month: 'short', day: 'numeric' });
    }

    function showToast(message, type = 'info') {
      const container = document.getElementById('toast-container');
      if (!container) return;
      const toast = document.createElement('div');
      toast.className = `px-4 py-2 rounded-xl text-xs font-bold shadow-lg transition-all transform translate-y-2 opacity-0 pointer-events-auto flex items-center gap-2 ${
        type === 'error' ? 'bg-rose-600 text-white' : 'bg-slate-900 text-white'
      }`;
      toast.textContent = message;
      container.appendChild(toast);

      requestAnimationFrame(() => {
        toast.classList.remove('translate-y-2', 'opacity-0');
      });

      setTimeout(() => {
        toast.classList.add('opacity-0', 'translate-y-2');
        setTimeout(() => toast.remove(), 300);
      }, 3500);
    }

    function playAudioTone(freq = 440) {
      if (!soundEnabled) return;
      try {
        const audioCtx = new (window.AudioContext || window.webkitAudioContext)();
        const osc = audioCtx.createOscillator();
        const gain = audioCtx.createGain();
        osc.type = 'sine';
        osc.frequency.setValueAtTime(freq, audioCtx.currentTime);
        gain.gain.setValueAtTime(0.04, audioCtx.currentTime);
        gain.gain.exponentialRampToValueAtTime(0.0001, audioCtx.currentTime + 0.15);
        osc.connect(gain);
        gain.connect(audioCtx.destination);
        osc.start();
        osc.stop(audioCtx.currentTime + 0.15);
      } catch (e) {}
    }

    function scrollToBottom(smooth = true) {
      if (!chatContainer) return;
      chatContainer.scrollTo({
        top: chatContainer.scrollHeight,
        behavior: smooth ? 'smooth' : 'auto'
      });
      if (scrollBottomBtn) {
        scrollBottomBtn.classList.add('translate-y-10', 'opacity-0');
      }
    }

    // --- EVENT LISTENERS ---
    if (tabModeFile && tabModeUrl && fileUploadSection && urlUploadSection) {
      tabModeFile.addEventListener('click', () => {
        currentUploadMode = 'file';
        tabModeFile.className = 'flex-1 py-1.5 rounded-lg bg-white shadow-xs text-indigo-700 transition cursor-pointer';
        tabModeUrl.className = 'flex-1 py-1.5 rounded-lg text-slate-600 hover:text-slate-900 transition cursor-pointer';
        fileUploadSection.classList.remove('hidden');
        urlUploadSection.classList.add('hidden');
      });

      tabModeUrl.addEventListener('click', () => {
        currentUploadMode = 'url';
        tabModeUrl.className = 'flex-1 py-1.5 rounded-lg bg-white shadow-xs text-indigo-700 transition cursor-pointer';
        tabModeFile.className = 'flex-1 py-1.5 rounded-lg text-slate-600 hover:text-slate-900 transition cursor-pointer';
        urlUploadSection.classList.remove('hidden');
        fileUploadSection.classList.add('hidden');
      });
    }

    if (profileToggleBtn) {
      profileToggleBtn.addEventListener('click', () => {
        showToast(`🔒 @${myProfile.name} is permanently locked to this device.`);
      });
    }

    if (pageNavBtn && viewChat && viewPhotos && pageNavIcon && pageNavLabel) {
      pageNavBtn.addEventListener('click', () => {
        if (currentTab === 'chat') {
          currentTab = 'photos';
          viewChat.classList.add('hidden');
          viewPhotos.classList.remove('hidden');
          pageNavIcon.textContent = '💬';
          pageNavLabel.textContent = 'To Chat';
          connectToPhotoServer();
          renderPhotos();
        } else {
          currentTab = 'chat';
          viewPhotos.classList.add('hidden');
          viewChat.classList.remove('hidden');
          pageNavIcon.textContent = '📸';
          pageNavLabel.textContent = 'To Photos';
          scrollToBottom(false);
        }
      });
    }

    document.querySelectorAll('.room-btn').forEach((btn) => {
      btn.addEventListener('click', () => {
        document.querySelectorAll('.room-btn').forEach((b) => {
          b.className = 'room-btn px-3 py-1 rounded-lg bg-slate-100 text-slate-600 hover:text-slate-900 border border-slate-200 transition cursor-pointer';
        });
        btn.className = 'room-btn active px-3 py-1 rounded-lg bg-indigo-100/70 text-indigo-700 border border-indigo-300 font-semibold transition cursor-pointer';
        const room = btn.getAttribute('data-room') || 'global';
        connectToServer(room);
      });
    });

    if (chatForm && messageInput && sendButton) {
      messageInput.addEventListener('input', () => {
        const val = messageInput.value.trim();
        sendButton.disabled = val.length === 0;
        const charLimit = document.getElementById('char-limit');
        if (charLimit) charLimit.textContent = 400 - messageInput.value.length;
      });

      chatForm.addEventListener('submit', (e) => {
        e.preventDefault();
        const text = messageInput.value.trim();
        if (!text) return;
        sendChatMessage(text);
        messageInput.value = '';
        sendButton.disabled = true;
        const charLimit = document.getElementById('char-limit');
        if (charLimit) charLimit.textContent = '400';
      });
    }

    document.querySelectorAll('.quick-emoji').forEach((btn) => {
      btn.addEventListener('click', () => {
        if (messageInput) {
          messageInput.value += btn.textContent;
          messageInput.focus();
          if (sendButton) sendButton.disabled = false;
        }
      });
    });

    if (chatContainer) {
      chatContainer.addEventListener('scroll', () => {
        const distFromBottom = chatContainer.scrollHeight - chatContainer.scrollTop - chatContainer.clientHeight;
        isAutoScrollActive = distFromBottom < 100;
        if (scrollBottomBtn) {
          if (distFromBottom > 150) {
            scrollBottomBtn.classList.remove('translate-y-10', 'opacity-0');
          } else {
            scrollBottomBtn.classList.add('translate-y-10', 'opacity-0');
          }
        }
      });
    }

    if (scrollBottomBtn) {
      scrollBottomBtn.addEventListener('click', () => {
        isAutoScrollActive = true;
        scrollToBottom(true);
      });
    }

    if (soundBtn && soundIconOn && soundIconOff) {
      soundBtn.addEventListener('click', () => {
        soundEnabled = !soundEnabled;
        if (soundEnabled) {
          soundIconOn.classList.remove('hidden');
          soundIconOff.classList.add('hidden');
          showToast('🔔 Sound cues enabled');
        } else {
          soundIconOn.classList.add('hidden');
          soundIconOff.classList.remove('hidden');
          showToast('🔕 Sound cues muted');
        }
      });
    }

    if (photoSearchInput) {
      photoSearchInput.addEventListener('input', renderPhotos);
    }

    if (openUploadBtn && uploadModal) {
      openUploadBtn.addEventListener('click', () => {
        uploadModal.classList.remove('hidden');
        if (photoTitleInput) photoTitleInput.value = '';
        if (photoFileInput) photoFileInput.value = '';
        if (photoUrlInput) photoUrlInput.value = '';
        selectedImageBase64 = null;
        if (photoFilePreviewWrap) photoFilePreviewWrap.classList.add('hidden');
        if (uploadProgressBox) uploadProgressBox.classList.add('hidden');
        if (submitBtnSpinner) submitBtnSpinner.classList.add('hidden');
        if (submitBtnText) submitBtnText.textContent = 'Publish Worldwide';
        if (fileNameLabel) fileNameLabel.textContent = 'Tap to take photo or choose from library';
        if (fileSizeLabel) fileSizeLabel.textContent = 'JPG, PNG, WebP, GIF supported';
      });
    }

    if (closeUploadModal && uploadModal) {
      closeUploadModal.addEventListener('click', () => uploadModal.classList.add('hidden'));
    }
    if (cancelUploadBtn && uploadModal) {
      cancelUploadBtn.addEventListener('click', () => uploadModal.classList.add('hidden'));
    }

    if (photoFileInput) {
      photoFileInput.addEventListener('change', async (e) => {
        const file = e.target.files[0];
        if (!file) return;

        if (fileNameLabel) fileNameLabel.textContent = file.name;
        if (fileSizeLabel) fileSizeLabel.textContent = `Compressing ${(file.size / (1024 * 1024)).toFixed(2)} MB...`;

        try {
          const compressed = await compressImageFile(file, 1200, 0.82);
          selectedImageBase64 = compressed;
          if (photoFilePreviewImg && photoFilePreviewWrap) {
            photoFilePreviewImg.src = compressed;
            photoFilePreviewWrap.classList.remove('hidden');
          }
          if (fileSizeLabel) fileSizeLabel.textContent = '✅ Image ready for high-speed sharing';
        } catch (err) {
          showToast('Failed to process image file.', 'error');
        }
      });
    }

    if (uploadForm) {
      uploadForm.addEventListener('submit', async (e) => {
        e.preventDefault();
        const title = photoTitleInput ? photoTitleInput.value.trim() : '';
        if (!title) {
          showToast('Please enter a title for your photo.', 'error');
          return;
        }

        let finalImageUrl = '';

        if (currentUploadMode === 'file') {
          if (!selectedImageBase64) {
            showToast('Please select a photo to share.', 'error');
            return;
          }

          if (submitBtnSpinner) submitBtnSpinner.classList.remove('hidden');
          if (submitBtnText) submitBtnText.textContent = 'Uploading...';
          const submitBtn = document.getElementById('submit-photo-btn');
          if (submitBtn) submitBtn.disabled = true;

          const file = photoFileInput.files[0];
          if (file) {
            const uploadedUrl = await uploadImageToCDN(file);
            if (uploadedUrl) {
              finalImageUrl = uploadedUrl;
            }
          }
        } else {
          const link = photoUrlInput ? photoUrlInput.value.trim() : '';
          if (!link || !link.startsWith('http')) {
            showToast('Please enter a valid web image link.', 'error');
            return;
          }
          finalImageUrl = link;
        }

        const cleanTitle = sanitizeContent(title);

        const newPhoto = {
          id: 'photo_' + Date.now() + '_' + Math.random().toString(36).substring(2, 7),
          title: cleanTitle,
          author: myProfile.name,
          avatar: myProfile.avatar,
          views: 1,
          likes: 0,
          ratings: {},
          createdAt: Date.now(),
          url: finalImageUrl
        };

        if (selectedImageBase64) {
          await savePhotoToIDB(newPhoto.id, selectedImageBase64);
          if (!newPhoto.url) {
            newPhoto.url = selectedImageBase64;
          }
        }

        allPhotos.unshift(newPhoto);
        savePhotosLocally();
        renderPhotos();

        if (submitBtnSpinner) submitBtnSpinner.classList.add('hidden');
        if (submitBtnText) submitBtnText.textContent = 'Publish Worldwide';
        const submitBtn = document.getElementById('submit-photo-btn');
        if (submitBtn) submitBtn.disabled = false;
        if (uploadModal) uploadModal.classList.add('hidden');
        showToast('🎉 Your photo was posted and is now live!');

        try {
          await fetch(`https://ntfy.sh/${getPhotoTopic()}`, {
            method: 'POST',
            body: JSON.stringify({
              type: 'photo_post',
              photo: newPhoto
            })
          });
        } catch (err) {}
      });
    }

    if (closeViewerBtn && viewerModal) {
      closeViewerBtn.addEventListener('click', () => viewerModal.classList.add('hidden'));
    }

    if (viewerModal) {
      viewerModal.addEventListener('click', (e) => {
        if (e.target === viewerModal) viewerModal.classList.add('hidden');
      });
    }

    document.querySelectorAll('.star-btn').forEach((btn) => {
      btn.addEventListener('click', () => {
        if (!currentActivePhoto) return;
        const score = Number(btn.getAttribute('data-star'));
        if (!score || score < 1 || score > 5) return;

        if (!currentActivePhoto.ratings) currentActivePhoto.ratings = {};
        currentActivePhoto.ratings[myProfile.name] = score;

        updateModalRatingDisplay(currentActivePhoto);
        renderPhotos();
        savePhotosLocally();
        playAudioTone(880);
        showToast(`⭐ Rated ${score} / 5 stars!`);

        try {
          fetch(`https://ntfy.sh/${getPhotoTopic()}`, {
            method: 'POST',
            body: JSON.stringify({
              type: 'photo_rate',
              photoId: currentActivePhoto.id,
              user: myProfile.name,
              rating: score
            })
          });
        } catch (e) {}
      });
    });

    if (modalLikeBtn) {
      modalLikeBtn.addEventListener('click', () => {
        if (!currentActivePhoto) return;
        currentActivePhoto.likes = (currentActivePhoto.likes || 0) + 1;
        if (modalLikeCount) modalLikeCount.textContent = currentActivePhoto.likes;
        renderPhotos();
        savePhotosLocally();
        playAudioTone(780);

        try {
          fetch(`https://ntfy.sh/${getPhotoTopic()}`, {
            method: 'POST',
            body: JSON.stringify({
              type: 'photo_stat_update',
              photoId: currentActivePhoto.id,
              views: currentActivePhoto.views || 1,
              likes: currentActivePhoto.likes
            })
          });
        } catch (e) {}
      });
    }

    document.addEventListener('visibilitychange', () => {
      if (!document.hidden && currentTab === 'chat') {
        connectToServer(currentRoom);
      }
    });

    // --- INITIALIZE APPLICATION ---
    initPermanentIdentity();
    initPhotos();
    connectToServer(currentRoom);
    setupFirebase();
  </script>
</body>
</html>
