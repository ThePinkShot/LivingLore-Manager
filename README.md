# Living Lore AI Companions — Manager

Portable Windows manager for the Living Lore AI Companions Conan Exiles mod.

**Alpha 28. German instructions follow below.** Multiplayer and mod combinations still need dedicated-server testing. Keep a backup of your save before testing.

## Download and start

1. Open [Releases](https://github.com/ThePinkShot/LivingLore-Manager/releases).
2. Download **Living_Lore_AI_Companions_Alpha28_Portable.zip** from the release assets. GitHub’s automatic “Source code” downloads contain this guide, not the manager.
3. Extract the whole ZIP into a writable folder. Open **Start_Living_Lore.bat**. Python is included.
4. The manager opens at **http://127.0.0.1:18741/**. Keep it running while playing.
5. Install and activate the matching Conan game mod separately. This download contains the manager, not the game mod.

## Set up your companion

Choose your conversation provider under **APIs & connections** and enter your own model and key. OpenRouter/OpenAI-compatible Chat, OpenAI Responses, Anthropic Messages and Google Gemini formats are supported. Only use models available from your provider.

Create a companion card using the exact in-game name and fill in your player profile. Personality, background, prompts, language, memories and voice can be configured. Menus are available in English and German; reply language is a free field.

ElevenLabs, OpenAI Speech and local Windows voices are supported. Speech uses a separate connection from conversations. Each companion can inherit the default voice or have a custom one.

The manager also provides memory and conversation summaries, screenshot questions, optional world comments, relationships, animation permissions, furniture/rest settings and equipment preferences. These features depend on the matching game mod and the permissions you enable. External providers may charge for conversations, images, speech, summaries and optional memory search.

ToT and Devious Desires are optional. ToT Chat is needed for ToT local-chat participation. Direct guest text questions do not require ToT. **Voice is not broadcast to other players.**

## Updates and your data

Your data is stored in **private-state/local** next to the starter. Downloads contain no personal cards, conversations or API keys.

Before updating, export your configuration under **Backup & updates**, then stop the manager. Replace program files while keeping the complete **private-state** folder. The configuration export excludes keys and chat history. For a full backup, copy private-state to another drive while the manager is stopped. Keys must be entered again on another PC.

This is an alpha. Public multiplayer voice, partner/carrying animations and a general vanilla-chat adapter are not included. Some ToT cosmetic names, special object animations, seated lip sync and equipment/furniture combinations still have limitations. See **LIES_MICH_README.txt** in the ZIP for details.

---

## Deutsch

Der portable Windows-Manager gehört zur Conan-Exiles-Mod **Living Lore AI Companions**.

**Alpha 28:** Mehrspieler und verschiedene Modkombinationen müssen noch auf dedizierten Servern erprobt werden. Sichere deinen Spielstand vor dem Testen.

### Herunterladen und starten

1. Öffne [Releases](https://github.com/ThePinkShot/LivingLore-Manager/releases).
2. Lade dort **Living_Lore_AI_Companions_Alpha28_Portable.zip** unter den Release-Dateien herunter. Die automatisch angebotenen „Source code“-Downloads enthalten diese Anleitung, nicht den Manager.
3. Entpacke die ganze ZIP in einen beschreibbaren Ordner und öffne **Start_Living_Lore.bat**. Python ist bereits dabei.
4. Der Manager öffnet sich unter **http://127.0.0.1:18741/**. Lass ihn während des Spielens laufen.
5. Installiere und aktiviere zusätzlich die passende Conan-Spielmod. Diese ZIP enthält den Manager, nicht die Spielmod.

### Deinen Begleiter einrichten

Unter **APIs & Verbindungen** trägst du deinen Gesprächsanbieter, das Modell und deinen eigenen Schlüssel ein. Unterstützt werden OpenRouter/OpenAI-kompatibles Chat, OpenAI Responses, Anthropic Messages und Google Gemini. Verwende nur Modelle, die dein Anbieter bereitstellt.

Erstelle eine Begleiterkarte mit genau dem Namen aus dem Spiel und fülle deine Spielerfigur aus. Persönlichkeit, Hintergrund, Prompts, Sprache, Erinnerungen und Stimme lassen sich anpassen. Die Menüs gibt es auf Deutsch und Englisch; die Antwortsprache kannst du frei eintragen.

Für Stimmen stehen ElevenLabs, OpenAI Speech und lokale Windows-Stimmen bereit. Dafür gibt es einen eigenen Zugang, unabhängig vom Gesprächsanbieter. Jeder Begleiter kann die Standardstimme übernehmen oder eine eigene bekommen.

Außerdem findest du Gedächtnis und Gesprächszusammenfassungen, Bildfragen, optionale Weltkommentare, Beziehungen, Animationserlaubnisse, Möbel- und Ruheverhalten sowie Ausrüstungswünsche. Dafür brauchst du die passende Spielmod und die jeweiligen Freigaben. Gespräche, Bilder, Stimmen, Zusammenfassungen und die optionale Erinnerungssuche können beim Anbieter Kosten verursachen.

ToT und Devious Desires sind optional. Die Beteiligung am ToT-Lokalchat benötigt ToT Chat. Direkte Gastfragen mit Textantwort benötigen kein ToT. **Stimmen werden nicht an andere Spieler übertragen.**

### Updates und deine Daten

Deine Daten liegen unter **private-state/local** neben der Startdatei. Die Downloads enthalten keine persönlichen Karten, Gespräche oder API-Schlüssel.

Exportiere vor einem Update deine Konfiguration unter **Sicherung & Update** und beende den Manager. Ersetze die Programmdateien und behalte den vollständigen Ordner **private-state**. Der Konfigurationsexport enthält keine Schlüssel oder Gesprächsverläufe. Kopiere für eine vollständige Sicherung private-state bei beendetem Manager auf ein anderes Laufwerk. Auf einem anderen PC musst du die Schlüssel erneut eintragen.

Diese Ausgabe ist eine Alpha. Öffentliche Mehrspielerstimme, Partner-/Trageanimationen und ein allgemeiner Vanilla-Chatadapter sind nicht enthalten. Einige ToT-Kosmetiknamen, besondere Objektanimationen, Sitz-Lippenbewegungen und Ausrüstungs-/Möbelkombinationen haben noch Einschränkungen. Einzelheiten stehen in **LIES_MICH_README.txt** in der ZIP.
