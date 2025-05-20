# Function: <code>xhci_setup_port_arrays</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int xhci_setup_port_arrays(struct xhci_hcd *xhci, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81653240)
Location: drivers/usb/host/xhci-mem.c:2179
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
ffffffff81653240-ffffffff816539ea: xhci_setup_port_arrays (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int xhci_setup_port_arrays(struct xhci_hcd *xhci, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff816b3890)
Location: drivers/usb/host/xhci-mem.c:2203
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
ffffffff816b3890-ffffffff816b40fc: xhci_setup_port_arrays (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int xhci_setup_port_arrays(struct xhci_hcd *xhci, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff816e1a40)
Location: drivers/usb/host/xhci-mem.c:2236
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
ffffffff816e1a40-ffffffff816e22ac: xhci_setup_port_arrays (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int xhci_setup_port_arrays(struct xhci_hcd *xhci, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff816f5c40)
Location: drivers/usb/host/xhci-mem.c:2178
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
ffffffff816f5c40-ffffffff816f6491: xhci_setup_port_arrays (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int xhci_setup_port_arrays(struct xhci_hcd *xhci, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817625c0)
Location: drivers/usb/host/xhci-mem.c:2220
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
ffffffff817625c0-ffffffff81762e11: xhci_setup_port_arrays (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817a6055)
Location: drivers/usb/host/xhci-mem.c:2259
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817cc0f6)
Location: drivers/usb/host/xhci-mem.c:2247
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int xhci_setup_port_arrays(struct xhci_hcd *xhci, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (0)
Location: drivers/usb/host/xhci-mem.c:2247
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
ffffffff818092e0-ffffffff8180997a: xhci_setup_port_arrays (STB_LOCAL)
ffffffff8180c7ba-ffffffff8180c873: xhci_setup_port_arrays.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int xhci_setup_port_arrays(struct xhci_hcd *xhci, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (0)
Location: drivers/usb/host/xhci-mem.c:2267
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
ffffffff8183a190-ffffffff8183a8fb: xhci_setup_port_arrays (STB_LOCAL)
ffffffff8183d7ac-ffffffff8183d86e: xhci_setup_port_arrays.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int xhci_setup_port_arrays(struct xhci_hcd *xhci, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (0)
Location: drivers/usb/host/xhci-mem.c:2267
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
ffffffff8190cec0-ffffffff8190d301: xhci_setup_port_arrays (STB_LOCAL)
ffffffff81910112-ffffffff8191012e: xhci_setup_port_arrays.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int xhci_setup_port_arrays(struct xhci_hcd *xhci, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (0)
Location: drivers/usb/host/xhci-mem.c:2275
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
ffffffff81914910-ffffffff81914d51: xhci_setup_port_arrays (STB_LOCAL)
ffffffff81c217ba-ffffffff81c217d6: xhci_setup_port_arrays.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int xhci_setup_port_arrays(struct xhci_hcd *xhci, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (0)
Location: drivers/usb/host/xhci-mem.c:2275
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
ffffffff818f7e40-ffffffff818f827e: xhci_setup_port_arrays (STB_LOCAL)
ffffffff81c13865-ffffffff81c13881: xhci_setup_port_arrays.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int xhci_setup_port_arrays(struct xhci_hcd *xhci, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (0)
Location: drivers/usb/host/xhci-mem.c:2275
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
ffffffff81996450-ffffffff819968d1: xhci_setup_port_arrays (STB_LOCAL)
ffffffff81d2068b-ffffffff81d206a7: xhci_setup_port_arrays.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int xhci_setup_port_arrays(struct xhci_hcd *xhci, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (0)
Location: drivers/usb/host/xhci-mem.c:2263
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
ffffffff81af3340-ffffffff81af37b0: xhci_setup_port_arrays (STB_LOCAL)
ffffffff81eec1da-ffffffff81eec227: xhci_setup_port_arrays.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xhci_setup_port_arrays(struct xhci_hcd *xhci, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81c80860)
Location: drivers/usb/host/xhci-mem.c:2272
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
ffffffff81c80860-ffffffff81c80d29: xhci_setup_port_arrays (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xhci_setup_port_arrays(struct xhci_hcd *xhci, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81ce7540)
Location: drivers/usb/host/xhci-mem.c:2130
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
ffffffff81ce7540-ffffffff81ce7a64: xhci_setup_port_arrays (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xhci_setup_port_arrays(struct xhci_hcd *xhci, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81d9c9a0)
Location: drivers/usb/host/xhci-mem.c:2173
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
ffffffff81d9c9a0-ffffffff81d9cec4: xhci_setup_port_arrays (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffff800010a7b2f0)
Location: drivers/usb/host/xhci-mem.c:2267
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int xhci_setup_port_arrays(struct xhci_hcd *xhci, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (c0b4b82c)
Location: drivers/usb/host/xhci-mem.c:2267
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
c0b4b82c-c0b4bfd4: xhci_setup_port_arrays (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int xhci_setup_port_arrays(struct xhci_hcd *xhci, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (c000000000b4e6d0)
Location: drivers/usb/host/xhci-mem.c:2267
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
c000000000b4e6d0-c000000000b4f320: xhci_setup_port_arrays (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int xhci_setup_port_arrays(struct xhci_hcd *xhci, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffe00068f7ae)
Location: drivers/usb/host/xhci-mem.c:2267
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
ffffffe00068f7ae-ffffffe00068ff10: xhci_setup_port_arrays (STB_LOCAL)
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
int xhci_setup_port_arrays(struct xhci_hcd *xhci, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (0)
Location: drivers/usb/host/xhci-mem.c:2267
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
ffffffff817f2540-ffffffff817f2cab: xhci_setup_port_arrays (STB_LOCAL)
ffffffff817f5b5c-ffffffff817f5c1e: xhci_setup_port_arrays.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int xhci_setup_port_arrays(struct xhci_hcd *xhci, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (0)
Location: drivers/usb/host/xhci-mem.c:2267
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
ffffffff817b76e0-ffffffff817b7e4b: xhci_setup_port_arrays (STB_LOCAL)
ffffffff817bacfc-ffffffff817badbe: xhci_setup_port_arrays.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int xhci_setup_port_arrays(struct xhci_hcd *xhci, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (0)
Location: drivers/usb/host/xhci-mem.c:2267
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
ffffffff8182f010-ffffffff8182f77b: xhci_setup_port_arrays (STB_LOCAL)
ffffffff8183262c-ffffffff818326ee: xhci_setup_port_arrays.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int xhci_setup_port_arrays(struct xhci_hcd *xhci, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (0)
Location: drivers/usb/host/xhci-mem.c:2267
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
ffffffff81849180-ffffffff818498eb: xhci_setup_port_arrays (STB_LOCAL)
ffffffff8184c80c-ffffffff8184c8ce: xhci_setup_port_arrays.cold (STB_LOCAL)
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
