# **Gradient Favicon — Canonical Design Spec**

### **Canvas**
- Size: **256×256 px** (source)
- Export: **favicon.ico** containing:
  - 16×16  
  - 32×32  
  - 48×48  
  - 64×64  
  - 128×128  
  - 256×256  

### **Background**
- Solid black: `#000000`

### **Core Glyph**
Use the same center glyph from your `logo.svg`:

- White circle  
- Diameter: **24 px**  
- Centered at (128, 128)

### **Triadic Arcs**
Use simplified arcs from the full logo:

- **S‑mode arc (cyan)**: `#00e5ff`  
- **R‑mode arc (magenta)**: `#ff00e5`  
- **E‑mode arc (yellow)**: `#ffe500`  

Each arc:

- Stroke width: **18 px**  
- Radius: **100 px**  
- Arc length: **90°**  
- Positioned to form a triadic loop around the center

### **Inner Ring**
- White ring  
- Radius: **60 px**  
- Stroke width: **6 px**  
- Opacity: **0.85**

### **No Text**
Favicons must remain symbol‑only.

---

# **Favicon Export Instructions**

1. Open your `logo.svg` in Figma or Illustrator.  
2. Duplicate the artboard and simplify it using the spec above.  
3. Export as **PNG 256×256**.  
4. Use any favicon generator (RealFaviconGenerator, Favicon.io, etc.) to produce a multi‑resolution `.ico`.  
5. Upload the generated `favicon.ico` into this GitHub tab and commit.
