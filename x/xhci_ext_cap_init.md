# Function: <code>xhci_ext_cap_init</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int xhci_ext_cap_init(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ext-caps.c (ffffffff817a6c10)
Location: drivers/usb/host/xhci-ext-caps.c:64
Inline: False
Direct callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
**Symbols:**

```
ffffffff817a6c10-ffffffff817a6e15: xhci_ext_cap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xhci_ext_cap_init(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ext-caps.c (ffffffff817ccac0)
Location: drivers/usb/host/xhci-ext-caps.c:64
Inline: False
Direct callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
**Symbols:**

```
ffffffff817ccac0-ffffffff817cccc4: xhci_ext_cap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int xhci_ext_cap_init(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ext-caps.c (0)
Location: drivers/usb/host/xhci-ext-caps.c:64
Inline: False
Direct callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
**Symbols:**

```
ffffffff8180caa7-ffffffff8180cb30: xhci_ext_cap_init.cold (STB_LOCAL)
ffffffff8180c910-ffffffff8180caa7: xhci_ext_cap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int xhci_ext_cap_init(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ext-caps.c (0)
Location: drivers/usb/host/xhci-ext-caps.c:83
Inline: False
Direct callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
**Symbols:**

```
ffffffff8183dac8-ffffffff8183db73: xhci_ext_cap_init.cold (STB_LOCAL)
ffffffff8183d910-ffffffff8183dac8: xhci_ext_cap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xhci_ext_cap_init(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ext-caps.c (ffffffff819102f0)
Location: drivers/usb/host/xhci-ext-caps.c:83
Inline: False
```
**Symbols:**

```
ffffffff819102f0-ffffffff8191039b: xhci_ext_cap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xhci_ext_cap_init(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ext-caps.c (ffffffff81917c20)
Location: drivers/usb/host/xhci-ext-caps.c:83
Inline: False
```
**Symbols:**

```
ffffffff81917c20-ffffffff81917ccb: xhci_ext_cap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xhci_ext_cap_init(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ext-caps.c (ffffffff818fb0b0)
Location: drivers/usb/host/xhci-ext-caps.c:84
Inline: False
```
**Symbols:**

```
ffffffff818fb0b0-ffffffff818fb15b: xhci_ext_cap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int xhci_ext_cap_init(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ext-caps.c (ffffffff81999f20)
Location: drivers/usb/host/xhci-ext-caps.c:84
Inline: False
```
**Symbols:**

```
ffffffff81999f20-ffffffff81999fcb: xhci_ext_cap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int xhci_ext_cap_init(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ext-caps.c (ffffffff81af6f30)
Location: drivers/usb/host/xhci-ext-caps.c:84
Inline: False
```
**Symbols:**

```
ffffffff81af6f30-ffffffff81af6ff3: xhci_ext_cap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xhci_ext_cap_init(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ext-caps.c (ffffffff81c849c0)
Location: drivers/usb/host/xhci-ext-caps.c:84
Inline: False
```
**Symbols:**

```
ffffffff81c849c0-ffffffff81c84a83: xhci_ext_cap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xhci_ext_cap_init(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ext-caps.c (ffffffff81ceb680)
Location: drivers/usb/host/xhci-ext-caps.c:84
Inline: False
```
**Symbols:**

```
ffffffff81ceb680-ffffffff81ceb743: xhci_ext_cap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xhci_ext_cap_init(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ext-caps.c (ffffffff81da0ca0)
Location: drivers/usb/host/xhci-ext-caps.c:84
Inline: False
```
**Symbols:**

```
ffffffff81da0ca0-ffffffff81da0d63: xhci_ext_cap_init (STB_GLOBAL)
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
int xhci_ext_cap_init(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ext-caps.c (ffff800010a7b968)
Location: drivers/usb/host/xhci-ext-caps.c:83
Inline: False
Direct callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
**Symbols:**

```
ffff800010a7b968-ffff800010a7bc28: xhci_ext_cap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int xhci_ext_cap_init(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ext-caps.c (c0b4ee90)
Location: drivers/usb/host/xhci-ext-caps.c:83
Inline: False
Direct callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
**Symbols:**

```
c0b4ee90-c0b4f170: xhci_ext_cap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int xhci_ext_cap_init(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ext-caps.c (c000000000b535b0)
Location: drivers/usb/host/xhci-ext-caps.c:83
Inline: False
Direct callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
**Symbols:**

```
c000000000b535b0-c000000000b53a84: xhci_ext_cap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int xhci_ext_cap_init(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ext-caps.c (ffffffe000692bac)
Location: drivers/usb/host/xhci-ext-caps.c:83
Inline: False
Direct callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
**Symbols:**

```
ffffffe000692bac-ffffffe000692e24: xhci_ext_cap_init (STB_GLOBAL)
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
int xhci_ext_cap_init(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ext-caps.c (0)
Location: drivers/usb/host/xhci-ext-caps.c:83
Inline: False
Direct callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
**Symbols:**

```
ffffffff817f5e78-ffffffff817f5f23: xhci_ext_cap_init.cold (STB_LOCAL)
ffffffff817f5cc0-ffffffff817f5e78: xhci_ext_cap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int xhci_ext_cap_init(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ext-caps.c (0)
Location: drivers/usb/host/xhci-ext-caps.c:83
Inline: False
Direct callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
**Symbols:**

```
ffffffff817bb018-ffffffff817bb0c3: xhci_ext_cap_init.cold (STB_LOCAL)
ffffffff817bae60-ffffffff817bb018: xhci_ext_cap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int xhci_ext_cap_init(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ext-caps.c (0)
Location: drivers/usb/host/xhci-ext-caps.c:83
Inline: False
Direct callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
**Symbols:**

```
ffffffff81832948-ffffffff818329f3: xhci_ext_cap_init.cold (STB_LOCAL)
ffffffff81832790-ffffffff81832948: xhci_ext_cap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int xhci_ext_cap_init(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ext-caps.c (0)
Location: drivers/usb/host/xhci-ext-caps.c:83
Inline: False
Direct callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
**Symbols:**

```
ffffffff8184cb28-ffffffff8184cbd3: xhci_ext_cap_init.cold (STB_LOCAL)
ffffffff8184c970-ffffffff8184cb28: xhci_ext_cap_init (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
