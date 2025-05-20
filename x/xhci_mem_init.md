# Function: <code>xhci_mem_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int xhci_mem_init(struct xhci_hcd *xhci, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81655ea0)
Location: drivers/usb/host/xhci-mem.c:2331
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_init
```
**Symbols:**

```
ffffffff81655ea0-ffffffff81656a87: xhci_mem_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int xhci_mem_init(struct xhci_hcd *xhci, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff816b68e0)
Location: drivers/usb/host/xhci-mem.c:2334
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_init
```
**Symbols:**

```
ffffffff816b68e0-ffffffff816b74ca: xhci_mem_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int xhci_mem_init(struct xhci_hcd *xhci, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff816e4b50)
Location: drivers/usb/host/xhci-mem.c:2367
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_init
```
**Symbols:**

```
ffffffff816e4b50-ffffffff816e5771: xhci_mem_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int xhci_mem_init(struct xhci_hcd *xhci, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff816f8a90)
Location: drivers/usb/host/xhci-mem.c:2310
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_init
```
**Symbols:**

```
ffffffff816f8a90-ffffffff816f95e3: xhci_mem_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int xhci_mem_init(struct xhci_hcd *xhci, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81765670)
Location: drivers/usb/host/xhci-mem.c:2352
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_init
```
**Symbols:**

```
ffffffff81765670-ffffffff817660d0: xhci_mem_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int xhci_mem_init(struct xhci_hcd *xhci, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817a59d0)
Location: drivers/usb/host/xhci-mem.c:2359
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_init
```
**Symbols:**

```
ffffffff817a59d0-ffffffff817a6bfc: xhci_mem_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xhci_mem_init(struct xhci_hcd *xhci, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817cbac0)
Location: drivers/usb/host/xhci-mem.c:2347
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_init
```
**Symbols:**

```
ffffffff817cbac0-ffffffff817ccaa2: xhci_mem_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int xhci_mem_init(struct xhci_hcd *xhci, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (0)
Location: drivers/usb/host/xhci-mem.c:2347
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_init
```
**Symbols:**

```
ffffffff8180c8e2-ffffffff8180c8fa: xhci_mem_init.cold (STB_LOCAL)
ffffffff8180be70-ffffffff8180c6de: xhci_mem_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int xhci_mem_init(struct xhci_hcd *xhci, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (0)
Location: drivers/usb/host/xhci-mem.c:2372
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_init
```
**Symbols:**

```
ffffffff8183d8dd-ffffffff8183d8f5: xhci_mem_init.cold (STB_LOCAL)
ffffffff8183ce70-ffffffff8183d6d0: xhci_mem_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int xhci_mem_init(struct xhci_hcd *xhci, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (0)
Location: drivers/usb/host/xhci-mem.c:2372
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_init
```
**Symbols:**

```
ffffffff8191019a-ffffffff819101b2: xhci_mem_init.cold (STB_LOCAL)
ffffffff8190f920-ffffffff8190ffa6: xhci_mem_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int xhci_mem_init(struct xhci_hcd *xhci, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (0)
Location: drivers/usb/host/xhci-mem.c:2380
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_init
```
**Symbols:**

```
ffffffff81c21842-ffffffff81c2185a: xhci_mem_init.cold (STB_LOCAL)
ffffffff81917480-ffffffff81917aef: xhci_mem_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int xhci_mem_init(struct xhci_hcd *xhci, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (0)
Location: drivers/usb/host/xhci-mem.c:2380
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_init
```
**Symbols:**

```
ffffffff81c138ed-ffffffff81c13905: xhci_mem_init.cold (STB_LOCAL)
ffffffff818fa910-ffffffff818faf77: xhci_mem_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int xhci_mem_init(struct xhci_hcd *xhci, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (0)
Location: drivers/usb/host/xhci-mem.c:2380
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_init
```
**Symbols:**

```
ffffffff81d20767-ffffffff81d2077f: xhci_mem_init.cold (STB_LOCAL)
ffffffff819996c0-ffffffff81999de3: xhci_mem_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int xhci_mem_init(struct xhci_hcd *xhci, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (0)
Location: drivers/usb/host/xhci-mem.c:2369
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_init
```
**Symbols:**

```
ffffffff81eec2e3-ffffffff81eec332: xhci_mem_init.cold (STB_LOCAL)
ffffffff81af66b0-ffffffff81af6dd1: xhci_mem_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int xhci_mem_init(struct xhci_hcd *xhci, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (0)
Location: drivers/usb/host/xhci-mem.c:2378
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_init
```
**Symbols:**

```
ffffffff820a5815-ffffffff820a5834: xhci_mem_init.cold (STB_LOCAL)
ffffffff81c84050-ffffffff81c847a1: xhci_mem_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int xhci_mem_init(struct xhci_hcd *xhci, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (0)
Location: drivers/usb/host/xhci-mem.c:2301
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_init
```
**Symbols:**

```
ffffffff82126c8d-ffffffff82126cac: xhci_mem_init.cold (STB_LOCAL)
ffffffff81cead50-ffffffff81ceb46f: xhci_mem_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int xhci_mem_init(struct xhci_hcd *xhci, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (0)
Location: drivers/usb/host/xhci-mem.c:2398
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_init
```
**Symbols:**

```
ffffffff82208490-ffffffff822084af: xhci_mem_init.cold (STB_LOCAL)
ffffffff81da0520-ffffffff81da0a83: xhci_mem_init (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int xhci_mem_init(struct xhci_hcd *xhci, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffff800010a7ac30)
Location: drivers/usb/host/xhci-mem.c:2372
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_init
```
**Symbols:**

```
ffff800010a7ac30-ffff800010a7b938: xhci_mem_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int xhci_mem_init(struct xhci_hcd *xhci, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (c0b4e558)
Location: drivers/usb/host/xhci-mem.c:2372
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_init
```
**Symbols:**

```
c0b4e558-c0b4ee74: xhci_mem_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int xhci_mem_init(struct xhci_hcd *xhci, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (c000000000b52840)
Location: drivers/usb/host/xhci-mem.c:2372
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_init
```
**Symbols:**

```
c000000000b52840-c000000000b53570: xhci_mem_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int xhci_mem_init(struct xhci_hcd *xhci, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffe00069227a)
Location: drivers/usb/host/xhci-mem.c:2372
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_init
```
**Symbols:**

```
ffffffe00069227a-ffffffe000692b82: xhci_mem_init (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int xhci_mem_init(struct xhci_hcd *xhci, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (0)
Location: drivers/usb/host/xhci-mem.c:2372
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_init
```
**Symbols:**

```
ffffffff817f5c8d-ffffffff817f5ca5: xhci_mem_init.cold (STB_LOCAL)
ffffffff817f5220-ffffffff817f5a80: xhci_mem_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int xhci_mem_init(struct xhci_hcd *xhci, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (0)
Location: drivers/usb/host/xhci-mem.c:2372
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_init
```
**Symbols:**

```
ffffffff817bae2d-ffffffff817bae45: xhci_mem_init.cold (STB_LOCAL)
ffffffff817ba3c0-ffffffff817bac20: xhci_mem_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int xhci_mem_init(struct xhci_hcd *xhci, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (0)
Location: drivers/usb/host/xhci-mem.c:2372
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_init
```
**Symbols:**

```
ffffffff8183275d-ffffffff81832775: xhci_mem_init.cold (STB_LOCAL)
ffffffff81831cf0-ffffffff81832550: xhci_mem_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int xhci_mem_init(struct xhci_hcd *xhci, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (0)
Location: drivers/usb/host/xhci-mem.c:2372
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_init
```
**Symbols:**

```
ffffffff8184c93d-ffffffff8184c955: xhci_mem_init.cold (STB_LOCAL)
ffffffff8184bed0-ffffffff8184c730: xhci_mem_init (STB_GLOBAL)
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
