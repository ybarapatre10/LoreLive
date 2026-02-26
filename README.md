# LoreLive: Real-Time Multimodal Cartoon Creator & Interactive Companion
Built for the Gemini Live Agent Challenge, LoreLive is a generative multi-agent ecosystem that transforms simple verbal prompts into living cartoon universes. It moves beyond the traditional "text box" paradigm by enabling parents to co-create consistent narratives and allowing children to interact with their favorite characters in an emotionally aware, real-time environment.

# 🌟 The Vision: From Copilot to Teammate
LoreLive isn't just a content generator; it's a creative director. It leverages the Gemini Multimodal Live API and Gemini 2.5 Flash Image to bridge the gap between imagination and digital reality, satisfying the hackathon's focus on "See, Hear, Speak, and Create."

# 🚀 Key Features
Multimodal Storytelling (Interleaved Output): Real-time generation of digital storybooks where text narration and generated illustrations are woven into a single, fluid response stream. 

Character Consistency (Nano Banana): Utilizing the unique capabilities of Gemini 2.5 Flash Image, LoreLive ensures that characters (like "Toby the Turtle") maintain their visual identity across multiple scenes, episodes, and interactive sessions. 

Live Persona Interaction: Characters "come to life" via the Multimodal Live API. Kids can speak directly to characters, who respond with Affective Dialogue—automatically adjusting their tone and empathy based on the child's voice input.

LoreVault (Persistent Memory): A dedicated metadata layer that stores character traits, backstories, and world rules. This allows for long-horizon narrative continuity, enabling characters to "remember" previous adventures with the child. 

# 🏗️ Technical Architecture
LoreLive employs a sophisticated multi-agent orchestration using the Agent Development Kit (ADK):

The Director Agent (Root): Orchestrates the high-level workflow and manages the transition between creation mode and interaction mode.

The Chronicler Agent: A stateful agent that listens to parent input to build a "World Bible," ensuring story logic remains coherent across multiple episodes.

The Illustrator Agent: Specializes in visual style coherence, processing character metadata to generate high-fidelity 1024x1024 assets via the Nano Banana architecture.

The Persona Agent: A low-latency agent that powers the real-time interaction loop, utilizing Voice Activity Detection (VAD) to handle natural interruptions and turn-taking.
