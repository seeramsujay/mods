# Minecraft Fabric 1.21 Modpack & Optimization Collection

A curated collection of client-side performance, visual enhancement, audio realism, and quality-of-life mods designed for **Minecraft 1.21.x** running on the **Fabric Loader**.

---

## ⚡ Overview & Features

This repository aggregates high-performance Fabric mods pre-configured and tested for compatibility, delivering ultra-smooth framerates, low memory footprints, modern shader support, and rich quality-of-life UI features.

### Included Mod Categories

1. **Performance & Engine Optimization**
   - **Sodium** & **Sodium Extra**: State-of-the-art modern rendering engine replacement.
   - **Lithium**: Comprehensive game physics and chunk tick optimizations without modifying vanilla behavior.
   - **FerriteCore**: Drastically reduces memory usage and garbage collection stalls.
   - **ModernFix**: All-in-one performance patch fixing memory leaks and slow startup times.
   - **ImmediatelyFast**: Optimizes immediate-mode rendering (HUD, GUI, entities).
   - **BadOptimizations**: Micro-optimizations for rendering tick logic.
   - **C2ME (Concurrent Chunk Management Engine)**: Multi-threaded chunk generation and IO.
   - **Krypton**: Optimized networking stack for lower packet latency.
   - **FastQuit**: Lets single-player worlds save in the background on exit.
   - **Noisium**: Optimizes world generation biome blending and noise functions.

2. **Graphics, Shaders & Visuals**
   - **Iris**: High-performance modern shader support compatible with Sodium.
   - **Indium**: Sodium compatibility layer for Fabric Rendering API (FREX).
   - **Continuity**: Connected textures mod (CTM) support.
   - **Dynamic Lights & LambDynamicLights**: Real-time handheld and dropped light sources.
   - **Entity Model Features (EMF)** & **Entity Texture Features (ETF)**: Custom entity models and random textures.
   - **BetterGrassify**: Realistic grass side rendering.
   - **FallingLeaves** & **CullLeaves**: Aesthetic foliage effects and leaf occlusion culling.
   - **Visuality**: Subtle particle enhancements (sparkles, splash particles).

3. **Quality of Life & HUD**
   - **Xaero's Minimap & World Map**: Real-time minimap with waypoints and persistent world cartography.
   - **Jade**: Modern WAILA replacement showing targeted blocks, entities, and contents.
   - **ModMenu**: In-game mod configuration screen.
   - **Controlling**: Searchable keybind manager.
   - **Inventory Profiles Next (IPN)** & **ClientSort**: Intelligent inventory sorting, restock, and weapon swap.
   - **Better Ping Display**: Shows exact numerical latency in player list.
   - **Centered Crosshair**: Perfectly centered crosshair alignment.
   - **Detail Armor Bar**: Visual display of armor toughness, absorption, and durability.
   - **Gamma Utils**: Fullbright toggles and gamma adjustments.
   - **Mouse Tweaks**: Drag sorting and scroll wheel crafting.
   - **Presence Footsteps**: Dynamic acoustics and immersive movement sound effects.

4. **Multiplayer & Connectivity**
   - **e4mc & e4mc Offline**: Seamless LAN world sharing over secure peer-to-peer tunnels without port forwarding.
   - **Fast IP Ping**: Faster multiplayer server ping checks.
   - **Packet Fixer**: Handles oversized packet payloads preventing network kicks.

---

## 📦 Installation Instructions

1. **Prerequisites**:
   - Install **Minecraft 1.21.x** (Official Launcher, Prism Launcher, or Modrinth).
   - Install the latest **Fabric Loader** for Minecraft 1.21.x from [fabricmc.net](https://fabricmc.net/).
2. **Setup**:
   - Locate your `.minecraft` directory:
     - **Linux**: `~/.minecraft/mods`
     - **macOS**: `~/Library/Application Support/minecraft/mods`
     - **Windows**: `%appdata%\.minecraft\mods`
   - Copy all `.jar` files from this repository directly into the `mods/` directory.
3. **Launch**:
   - Launch your Fabric 1.21 profile.
   - Verify active mods through the in-game **Mods** button provided by ModMenu.

---

## 🛡️ Integrity Verification

All bundled `.jar` binaries can be verified against their SHA-256 hashes provided in `CHECKSUMS.txt`:

```bash
sha256sum -c CHECKSUMS.txt
```

---

## 📝 License & Credits

All included mods are the property of their respective creators and authors. Refer to each project's upstream Modrinth / CurseForge page for individual licenses and attribution.
