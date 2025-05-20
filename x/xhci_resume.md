# Function: <code>xhci_resume</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int xhci_resume(struct xhci_hcd *xhci, bool hibernated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8164db10)
Location: drivers/usb/host/xhci.c:980
Inline: False
Direct callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_resume
```
**Symbols:**

```
ffffffff8164db10-ffffffff8164e035: xhci_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int xhci_resume(struct xhci_hcd *xhci, bool hibernated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816ae460)
Location: drivers/usb/host/xhci.c:987
Inline: False
Direct callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_resume
```
**Symbols:**

```
ffffffff816ae460-ffffffff816ae95b: xhci_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int xhci_resume(struct xhci_hcd *xhci, bool hibernated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816dc600)
Location: drivers/usb/host/xhci.c:990
Inline: False
Direct callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_resume
```
**Symbols:**

```
ffffffff816dc600-ffffffff816dcafb: xhci_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int xhci_resume(struct xhci_hcd *xhci, bool hibernated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816f09c0)
Location: drivers/usb/host/xhci.c:953
Inline: False
Direct callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_resume
```
**Symbols:**

```
ffffffff816f09c0-ffffffff816f0eeb: xhci_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int xhci_resume(struct xhci_hcd *xhci, bool hibernated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8175cb90)
Location: drivers/usb/host/xhci.c:956
Inline: False
Direct callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_resume
```
**Symbols:**

```
ffffffff8175cb90-ffffffff8175d0cb: xhci_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int xhci_resume(struct xhci_hcd *xhci, bool hibernated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8179d540)
Location: drivers/usb/host/xhci.c:1060
Inline: False
Direct callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_resume
```
**Symbols:**

```
ffffffff8179d540-ffffffff8179daf6: xhci_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xhci_resume(struct xhci_hcd *xhci, bool hibernated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff817c3920)
Location: drivers/usb/host/xhci.c:1077
Inline: False
Direct callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_resume
```
**Symbols:**

```
ffffffff817c3920-ffffffff817c3ee8: xhci_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int xhci_resume(struct xhci_hcd *xhci, bool hibernated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:1084
Inline: False
Direct callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_resume
```
**Symbols:**

```
ffffffff81807d54-ffffffff81807d79: xhci_resume.cold (STB_LOCAL)
ffffffff81803170-ffffffff818036f1: xhci_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int xhci_resume(struct xhci_hcd *xhci, bool hibernated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:1081
Inline: False
Direct callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_resume
```
**Symbols:**

```
ffffffff81838c03-ffffffff81838c4a: xhci_resume.cold (STB_LOCAL)
ffffffff81834130-ffffffff818346b5: xhci_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int xhci_resume(struct xhci_hcd *xhci, bool hibernated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:1081
Inline: False
```
**Symbols:**

```
ffffffff8190b4ee-ffffffff8190b53f: xhci_resume.cold (STB_LOCAL)
ffffffff81907000-ffffffff81907575: xhci_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int xhci_resume(struct xhci_hcd *xhci, bool hibernated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:1082
Inline: False
```
**Symbols:**

```
ffffffff81c20f1b-ffffffff81c20f6c: xhci_resume.cold (STB_LOCAL)
ffffffff8190f7a0-ffffffff8190fd1c: xhci_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int xhci_resume(struct xhci_hcd *xhci, bool hibernated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:1085
Inline: False
```
**Symbols:**

```
ffffffff81c12f60-ffffffff81c12fb1: xhci_resume.cold (STB_LOCAL)
ffffffff818f2d70-ffffffff818f3301: xhci_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int xhci_resume(struct xhci_hcd *xhci, bool hibernated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:1086
Inline: False
```
**Symbols:**

```
ffffffff81d1fce2-ffffffff81d1fd68: xhci_resume.cold (STB_LOCAL)
ffffffff8198ffe0-ffffffff819905bd: xhci_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int xhci_resume(struct xhci_hcd *xhci, bool hibernated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:1126
Inline: False
```
**Symbols:**

```
ffffffff81eeb8a3-ffffffff81eeb91f: xhci_resume.cold (STB_LOCAL)
ffffffff81aec710-ffffffff81aecd1c: xhci_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int xhci_resume(struct xhci_hcd *xhci, bool hibernated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:1123
Inline: False
```
**Symbols:**

```
ffffffff820a576f-ffffffff820a578d: xhci_resume.cold (STB_LOCAL)
ffffffff81c78f20-ffffffff81c795a7: xhci_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int xhci_resume(struct xhci_hcd *xhci, pm_message_t msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:963
Inline: False
```
**Symbols:**

```
ffffffff82126c05-ffffffff82126c23: xhci_resume.cold (STB_LOCAL)
ffffffff81ce0160-ffffffff81ce0830: xhci_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int xhci_resume(struct xhci_hcd *xhci, pm_message_t msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:1002
Inline: False
```
**Symbols:**

```
ffffffff82208408-ffffffff82208426: xhci_resume.cold (STB_LOCAL)
ffffffff81d95250-ffffffff81d95974: xhci_resume (STB_GLOBAL)
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
int xhci_resume(struct xhci_hcd *xhci, bool hibernated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffff800010a716c0)
Location: drivers/usb/host/xhci.c:1081
Inline: False
Direct callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_resume
  - drivers/usb/host/xhci-pci.c:xhci_pci_resume
```
**Symbols:**

```
ffff800010a716c0-ffff800010a71e58: xhci_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int xhci_resume(struct xhci_hcd *xhci, bool hibernated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (c0b45458)
Location: drivers/usb/host/xhci.c:1081
Inline: False
Direct callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_resume
```
**Symbols:**

```
c0b45458-c0b45ba8: xhci_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int xhci_resume(struct xhci_hcd *xhci, bool hibernated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (c000000000b467e0)
Location: drivers/usb/host/xhci.c:1081
Inline: False
Direct callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_resume
  - drivers/usb/host/xhci-pci.c:xhci_pci_resume
```
**Symbols:**

```
c000000000b467e0-c000000000b472e0: xhci_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int xhci_resume(struct xhci_hcd *xhci, bool hibernated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffe000689d32)
Location: drivers/usb/host/xhci.c:1081
Inline: False
Direct callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_resume
```
**Symbols:**

```
ffffffe000689d32-ffffffe00068a582: xhci_resume (STB_GLOBAL)
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
int xhci_resume(struct xhci_hcd *xhci, bool hibernated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:1081
Inline: False
Direct callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_resume
```
**Symbols:**

```
ffffffff817f0fb3-ffffffff817f0ffa: xhci_resume.cold (STB_LOCAL)
ffffffff817ec4f0-ffffffff817eca6d: xhci_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int xhci_resume(struct xhci_hcd *xhci, bool hibernated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:1081
Inline: False
Direct callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_resume
```
**Symbols:**

```
ffffffff817b6149-ffffffff817b6190: xhci_resume.cold (STB_LOCAL)
ffffffff817b1600-ffffffff817b1b79: xhci_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int xhci_resume(struct xhci_hcd *xhci, bool hibernated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:1081
Inline: False
Direct callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_resume
```
**Symbols:**

```
ffffffff8182da83-ffffffff8182daca: xhci_resume.cold (STB_LOCAL)
ffffffff81828fb0-ffffffff81829535: xhci_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int xhci_resume(struct xhci_hcd *xhci, bool hibernated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:1081
Inline: False
Direct callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_resume
```
**Symbols:**

```
ffffffff81847b6c-ffffffff81847bb3: xhci_resume.cold (STB_LOCAL)
ffffffff81842f60-ffffffff818434d3: xhci_resume (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>pm_message_t msg</code>
</li>
<li>
<b>Param removed. </b>
<code>bool hibernated</code>
</li>
</ul>
</details>
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
