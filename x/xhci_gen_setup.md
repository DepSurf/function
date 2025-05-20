# Function: <code>xhci_gen_setup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int xhci_gen_setup(struct usb_hcd *hcd, xhci_get_quirks_t get_quirks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8164e040)
Location: drivers/usb/host/xhci.c:4852
Inline: False
Direct callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
```
**Symbols:**

```
ffffffff8164e040-ffffffff8164e500: xhci_gen_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int xhci_gen_setup(struct usb_hcd *hcd, xhci_get_quirks_t get_quirks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816ae960)
Location: drivers/usb/host/xhci.c:4834
Inline: False
Direct callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
```
**Symbols:**

```
ffffffff816ae960-ffffffff816aee14: xhci_gen_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int xhci_gen_setup(struct usb_hcd *hcd, xhci_get_quirks_t get_quirks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816dcb00)
Location: drivers/usb/host/xhci.c:4827
Inline: False
Direct callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
```
**Symbols:**

```
ffffffff816dcb00-ffffffff816dcfba: xhci_gen_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int xhci_gen_setup(struct usb_hcd *hcd, xhci_get_quirks_t get_quirks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816f0ef0)
Location: drivers/usb/host/xhci.c:4772
Inline: False
Direct callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
```
**Symbols:**

```
ffffffff816f0ef0-ffffffff816f1416: xhci_gen_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int xhci_gen_setup(struct usb_hcd *hcd, xhci_get_quirks_t get_quirks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8175d0d0)
Location: drivers/usb/host/xhci.c:4779
Inline: False
Direct callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
```
**Symbols:**

```
ffffffff8175d0d0-ffffffff8175d688: xhci_gen_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int xhci_gen_setup(struct usb_hcd *hcd, xhci_get_quirks_t get_quirks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8179db00)
Location: drivers/usb/host/xhci.c:4964
Inline: False
Direct callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
```
**Symbols:**

```
ffffffff8179db00-ffffffff8179e079: xhci_gen_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xhci_gen_setup(struct usb_hcd *hcd, xhci_get_quirks_t get_quirks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff817c3ef0)
Location: drivers/usb/host/xhci.c:4996
Inline: False
Direct callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
```
**Symbols:**

```
ffffffff817c3ef0-ffffffff817c4289: xhci_gen_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int xhci_gen_setup(struct usb_hcd *hcd, xhci_get_quirks_t get_quirks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:5041
Inline: False
Direct callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
```
**Symbols:**

```
ffffffff81807d79-ffffffff81807e29: xhci_gen_setup.cold (STB_LOCAL)
ffffffff81803700-ffffffff81803a46: xhci_gen_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int xhci_gen_setup(struct usb_hcd *hcd, xhci_get_quirks_t get_quirks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:5114
Inline: False
Direct callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
```
**Symbols:**

```
ffffffff81838c4a-ffffffff81838d10: xhci_gen_setup.cold (STB_LOCAL)
ffffffff818346c0-ffffffff81834a06: xhci_gen_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int xhci_gen_setup(struct usb_hcd *hcd, xhci_get_quirks_t get_quirks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:5124
Inline: False
```
**Symbols:**

```
ffffffff8190b53f-ffffffff8190b605: xhci_gen_setup.cold (STB_LOCAL)
ffffffff81907580-ffffffff819078c6: xhci_gen_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int xhci_gen_setup(struct usb_hcd *hcd, xhci_get_quirks_t get_quirks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:5262
Inline: False
```
**Symbols:**

```
ffffffff81c20f6c-ffffffff81c21032: xhci_gen_setup.cold (STB_LOCAL)
ffffffff8190fd20-ffffffff81910066: xhci_gen_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int xhci_gen_setup(struct usb_hcd *hcd, xhci_get_quirks_t get_quirks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:5189
Inline: False
```
**Symbols:**

```
ffffffff81c12fb1-ffffffff81c1308f: xhci_gen_setup.cold (STB_LOCAL)
ffffffff818f3310-ffffffff818f3665: xhci_gen_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int xhci_gen_setup(struct usb_hcd *hcd, xhci_get_quirks_t get_quirks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:5209
Inline: False
```
**Symbols:**

```
ffffffff81d1fd68-ffffffff81d1fe46: xhci_gen_setup.cold (STB_LOCAL)
ffffffff819905c0-ffffffff81990909: xhci_gen_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int xhci_gen_setup(struct usb_hcd *hcd, xhci_get_quirks_t get_quirks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:5282
Inline: False
```
**Symbols:**

```
ffffffff81eeb91f-ffffffff81eeb9c2: xhci_gen_setup.cold (STB_LOCAL)
ffffffff81aecd20-ffffffff81aed01c: xhci_gen_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xhci_gen_setup(struct usb_hcd *hcd, xhci_get_quirks_t get_quirks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81c795c0)
Location: drivers/usb/host/xhci.c:5295
Inline: False
```
**Symbols:**

```
ffffffff81c795c0-ffffffff81c799a2: xhci_gen_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xhci_gen_setup(struct usb_hcd *hcd, xhci_get_quirks_t get_quirks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81ce0840)
Location: drivers/usb/host/xhci.c:5129
Inline: False
```
**Symbols:**

```
ffffffff81ce0840-ffffffff81ce0c7a: xhci_gen_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xhci_gen_setup(struct usb_hcd *hcd, xhci_get_quirks_t get_quirks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81d95990)
Location: drivers/usb/host/xhci.c:5189
Inline: False
```
**Symbols:**

```
ffffffff81d95990-ffffffff81d95dca: xhci_gen_setup (STB_GLOBAL)
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
int xhci_gen_setup(struct usb_hcd *hcd, xhci_get_quirks_t get_quirks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffff800010a71e58)
Location: drivers/usb/host/xhci.c:5114
Inline: False
Direct callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
```
**Symbols:**

```
ffff800010a71e58-ffff800010a722c8: xhci_gen_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int xhci_gen_setup(struct usb_hcd *hcd, xhci_get_quirks_t get_quirks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (c0b45ba8)
Location: drivers/usb/host/xhci.c:5114
Inline: False
Direct callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
```
**Symbols:**

```
c0b45ba8-c0b45fec: xhci_gen_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int xhci_gen_setup(struct usb_hcd *hcd, xhci_get_quirks_t get_quirks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (c000000000b472e0)
Location: drivers/usb/host/xhci.c:5114
Inline: False
Direct callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
```
**Symbols:**

```
c000000000b472e0-c000000000b47a3c: xhci_gen_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int xhci_gen_setup(struct usb_hcd *hcd, xhci_get_quirks_t get_quirks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffe00068a582)
Location: drivers/usb/host/xhci.c:5114
Inline: False
Direct callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
```
**Symbols:**

```
ffffffe00068a582-ffffffe00068a96e: xhci_gen_setup (STB_GLOBAL)
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
int xhci_gen_setup(struct usb_hcd *hcd, xhci_get_quirks_t get_quirks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:5114
Inline: False
Direct callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
```
**Symbols:**

```
ffffffff817f0ffa-ffffffff817f10c0: xhci_gen_setup.cold (STB_LOCAL)
ffffffff817eca70-ffffffff817ecdb6: xhci_gen_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int xhci_gen_setup(struct usb_hcd *hcd, xhci_get_quirks_t get_quirks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:5114
Inline: False
Direct callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
```
**Symbols:**

```
ffffffff817b6190-ffffffff817b6256: xhci_gen_setup.cold (STB_LOCAL)
ffffffff817b1b80-ffffffff817b1ec6: xhci_gen_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int xhci_gen_setup(struct usb_hcd *hcd, xhci_get_quirks_t get_quirks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:5114
Inline: False
Direct callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
```
**Symbols:**

```
ffffffff8182daca-ffffffff8182db90: xhci_gen_setup.cold (STB_LOCAL)
ffffffff81829540-ffffffff81829886: xhci_gen_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int xhci_gen_setup(struct usb_hcd *hcd, xhci_get_quirks_t get_quirks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:5114
Inline: False
Direct callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_setup
```
**Symbols:**

```
ffffffff81847bb3-ffffffff81847c79: xhci_gen_setup.cold (STB_LOCAL)
ffffffff818434e0-ffffffff81843826: xhci_gen_setup (STB_GLOBAL)
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
