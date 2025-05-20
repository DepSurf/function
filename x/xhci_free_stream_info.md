# Function: <code>xhci_free_stream_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void xhci_free_stream_info(struct xhci_hcd *xhci, struct xhci_stream_info *stream_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff816552b0)
Location: drivers/usb/host/xhci-mem.c:800
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
```
**Symbols:**

```
ffffffff816552b0-ffffffff816553f6: xhci_free_stream_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void xhci_free_stream_info(struct xhci_hcd *xhci, struct xhci_stream_info *stream_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff816b5cc0)
Location: drivers/usb/host/xhci-mem.c:815
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
```
**Symbols:**

```
ffffffff816b5cc0-ffffffff816b5e06: xhci_free_stream_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void xhci_free_stream_info(struct xhci_hcd *xhci, struct xhci_stream_info *stream_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff816e3e70)
Location: drivers/usb/host/xhci-mem.c:815
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
```
**Symbols:**

```
ffffffff816e3e70-ffffffff816e3fb6: xhci_free_stream_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xhci_free_stream_info(struct xhci_hcd *xhci, struct xhci_stream_info *stream_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff816f7e40)
Location: drivers/usb/host/xhci-mem.c:769
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
```
**Symbols:**

```
ffffffff816f7e40-ffffffff816f7f51: xhci_free_stream_info.part.39 (STB_LOCAL)
ffffffff816f7f60-ffffffff816f7f77: xhci_free_stream_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xhci_free_stream_info(struct xhci_hcd *xhci, struct xhci_stream_info *stream_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81764b60)
Location: drivers/usb/host/xhci-mem.c:756
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
```
**Symbols:**

```
ffffffff81764b60-ffffffff81764c74: xhci_free_stream_info.part.37 (STB_LOCAL)
ffffffff81764c80-ffffffff81764c97: xhci_free_stream_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xhci_free_stream_info(struct xhci_hcd *xhci, struct xhci_stream_info *stream_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817a507b)
Location: drivers/usb/host/xhci-mem.c:762
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
```
**Symbols:**

```
ffffffff817a4e90-ffffffff817a4fa4: xhci_free_stream_info.part.39 (STB_LOCAL)
ffffffff817a4fb0-ffffffff817a4fc6: xhci_free_stream_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xhci_free_stream_info(struct xhci_hcd *xhci, struct xhci_stream_info *stream_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817cb35b)
Location: drivers/usb/host/xhci-mem.c:762
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
```
**Symbols:**

```
ffffffff817cb1b0-ffffffff817cb28a: xhci_free_stream_info.part.37 (STB_LOCAL)
ffffffff817cb290-ffffffff817cb2a6: xhci_free_stream_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xhci_free_stream_info(struct xhci_hcd *xhci, struct xhci_stream_info *stream_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff8180b72b)
Location: drivers/usb/host/xhci-mem.c:762
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
```
**Symbols:**

```
ffffffff8180b590-ffffffff8180b66c: xhci_free_stream_info.part.0 (STB_LOCAL)
ffffffff8180b670-ffffffff8180b686: xhci_free_stream_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xhci_free_stream_info(struct xhci_hcd *xhci, struct xhci_stream_info *stream_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff8183c6eb)
Location: drivers/usb/host/xhci-mem.c:762
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
```
**Symbols:**

```
ffffffff8183c550-ffffffff8183c62c: xhci_free_stream_info.part.0 (STB_LOCAL)
ffffffff8183c630-ffffffff8183c646: xhci_free_stream_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xhci_free_stream_info(struct xhci_hcd *xhci, struct xhci_stream_info *stream_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff8190dc0b)
Location: drivers/usb/host/xhci-mem.c:762
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
```
**Symbols:**

```
ffffffff8190c820-ffffffff8190c92d: xhci_free_stream_info.part.0 (STB_LOCAL)
ffffffff8190d9e0-ffffffff8190d9f6: xhci_free_stream_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xhci_free_stream_info(struct xhci_hcd *xhci, struct xhci_stream_info *stream_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff819157ab)
Location: drivers/usb/host/xhci-mem.c:771
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
```
**Symbols:**

```
ffffffff819141f0-ffffffff819142fd: xhci_free_stream_info.part.0 (STB_LOCAL)
ffffffff81915580-ffffffff81915596: xhci_free_stream_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xhci_free_stream_info(struct xhci_hcd *xhci, struct xhci_stream_info *stream_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff818f8c3b)
Location: drivers/usb/host/xhci-mem.c:754
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
```
**Symbols:**

```
ffffffff818f7a00-ffffffff818f7b0d: xhci_free_stream_info.part.0 (STB_LOCAL)
ffffffff818f8a20-ffffffff818f8a36: xhci_free_stream_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xhci_free_stream_info(struct xhci_hcd *xhci, struct xhci_stream_info *stream_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff8199746d)
Location: drivers/usb/host/xhci-mem.c:754
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
```
**Symbols:**

```
ffffffff81995fd0-ffffffff819960dd: xhci_free_stream_info.part.0 (STB_LOCAL)
ffffffff81997190-ffffffff819971a6: xhci_free_stream_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xhci_free_stream_info(struct xhci_hcd *xhci, struct xhci_stream_info *stream_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81af4377)
Location: drivers/usb/host/xhci-mem.c:753
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
```
**Symbols:**

```
ffffffff81af2cc0-ffffffff81af2de1: xhci_free_stream_info.part.0 (STB_LOCAL)
ffffffff81af4090-ffffffff81af40b6: xhci_free_stream_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xhci_free_stream_info(struct xhci_hcd *xhci, struct xhci_stream_info *stream_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81c81a26)
Location: drivers/usb/host/xhci-mem.c:758
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
```
**Symbols:**

```
ffffffff81c801f0-ffffffff81c802c6: xhci_free_stream_info.part.0 (STB_LOCAL)
ffffffff81c816f0-ffffffff81c81716: xhci_free_stream_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xhci_free_stream_info(struct xhci_hcd *xhci, struct xhci_stream_info *stream_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81ce8736)
Location: drivers/usb/host/xhci-mem.c:740
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
```
**Symbols:**

```
ffffffff81ce6ed0-ffffffff81ce6fa6: xhci_free_stream_info.part.0 (STB_LOCAL)
ffffffff81ce8400-ffffffff81ce8426: xhci_free_stream_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xhci_free_stream_info(struct xhci_hcd *xhci, struct xhci_stream_info *stream_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81d9df56)
Location: drivers/usb/host/xhci-mem.c:751
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
```
**Symbols:**

```
ffffffff81d9c100-ffffffff81d9c1d6: xhci_free_stream_info.part.0 (STB_LOCAL)
ffffffff81d9dc10-ffffffff81d9dc36: xhci_free_stream_info (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xhci_free_stream_info(struct xhci_hcd *xhci, struct xhci_stream_info *stream_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffff800010a7a500)
Location: drivers/usb/host/xhci-mem.c:762
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
```
**Symbols:**

```
ffff800010a7a328-ffff800010a7a450: xhci_free_stream_info.part.0 (STB_LOCAL)
ffff800010a7a450-ffff800010a7a488: xhci_free_stream_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xhci_free_stream_info(struct xhci_hcd *xhci, struct xhci_stream_info *stream_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (c0b4de2c)
Location: drivers/usb/host/xhci-mem.c:762
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
```
**Symbols:**

```
c0b4dc8c-c0b4dd74: xhci_free_stream_info.part.0 (STB_LOCAL)
c0b4dd74-c0b4dd98: xhci_free_stream_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xhci_free_stream_info(struct xhci_hcd *xhci, struct xhci_stream_info *stream_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (c000000000b51e74)
Location: drivers/usb/host/xhci-mem.c:762
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
```
**Symbols:**

```
c000000000b51c00-c000000000b51da0: xhci_free_stream_info.part.0 (STB_LOCAL)
c000000000b51da0-c000000000b51dbc: xhci_free_stream_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xhci_free_stream_info(struct xhci_hcd *xhci, struct xhci_stream_info *stream_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffe000691bc0)
Location: drivers/usb/host/xhci-mem.c:762
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
```
**Symbols:**

```
ffffffe000691a14-ffffffe000691b0a: xhci_free_stream_info.part.0 (STB_LOCAL)
ffffffe000691b0a-ffffffe000691b3e: xhci_free_stream_info (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xhci_free_stream_info(struct xhci_hcd *xhci, struct xhci_stream_info *stream_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817f4a9b)
Location: drivers/usb/host/xhci-mem.c:762
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
```
**Symbols:**

```
ffffffff817f4900-ffffffff817f49dc: xhci_free_stream_info.part.0 (STB_LOCAL)
ffffffff817f49e0-ffffffff817f49f6: xhci_free_stream_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xhci_free_stream_info(struct xhci_hcd *xhci, struct xhci_stream_info *stream_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817b9c3b)
Location: drivers/usb/host/xhci-mem.c:762
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
```
**Symbols:**

```
ffffffff817b9aa0-ffffffff817b9b7c: xhci_free_stream_info.part.0 (STB_LOCAL)
ffffffff817b9b80-ffffffff817b9b96: xhci_free_stream_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xhci_free_stream_info(struct xhci_hcd *xhci, struct xhci_stream_info *stream_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff8183156b)
Location: drivers/usb/host/xhci-mem.c:762
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
```
**Symbols:**

```
ffffffff818313d0-ffffffff818314ac: xhci_free_stream_info.part.0 (STB_LOCAL)
ffffffff818314b0-ffffffff818314c6: xhci_free_stream_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xhci_free_stream_info(struct xhci_hcd *xhci, struct xhci_stream_info *stream_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff8184b73b)
Location: drivers/usb/host/xhci-mem.c:762
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
```
**Symbols:**

```
ffffffff8184b5a0-ffffffff8184b67c: xhci_free_stream_info.part.0 (STB_LOCAL)
ffffffff8184b680-ffffffff8184b696: xhci_free_stream_info (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
