# Function: <code>xhci_alloc_dev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int xhci_alloc_dev(struct usb_hcd *hcd, struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8164aec0)
Location: drivers/usb/host/xhci.c:3699
Inline: False
```
**Symbols:**

```
ffffffff8164aec0-ffffffff8164b172: xhci_alloc_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int xhci_alloc_dev(struct usb_hcd *hcd, struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816ab790)
Location: drivers/usb/host/xhci.c:3681
Inline: False
```
**Symbols:**

```
ffffffff816ab790-ffffffff816aba4d: xhci_alloc_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int xhci_alloc_dev(struct usb_hcd *hcd, struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816d98b0)
Location: drivers/usb/host/xhci.c:3670
Inline: False
```
**Symbols:**

```
ffffffff816d98b0-ffffffff816d9b79: xhci_alloc_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int xhci_alloc_dev(struct usb_hcd *hcd, struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816f47e0)
Location: drivers/usb/host/xhci.c:3630
Inline: False
```
**Symbols:**

```
ffffffff816f47e0-ffffffff816f4ae0: xhci_alloc_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int xhci_alloc_dev(struct usb_hcd *hcd, struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81760a50)
Location: drivers/usb/host/xhci.c:3632
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
```
**Symbols:**

```
ffffffff81760a50-ffffffff81760d47: xhci_alloc_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int xhci_alloc_dev(struct usb_hcd *hcd, struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff817a1490)
Location: drivers/usb/host/xhci.c:3825
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
```
**Symbols:**

```
ffffffff817a1490-ffffffff817a1783: xhci_alloc_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xhci_alloc_dev(struct usb_hcd *hcd, struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff817c7750)
Location: drivers/usb/host/xhci.c:3842
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
```
**Symbols:**

```
ffffffff817c7750-ffffffff817c7a43: xhci_alloc_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int xhci_alloc_dev(struct usb_hcd *hcd, struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:3884
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
```
**Symbols:**

```
ffffffff818083f6-ffffffff8180845a: xhci_alloc_dev.cold (STB_LOCAL)
ffffffff81806a90-ffffffff81806d10: xhci_alloc_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int xhci_alloc_dev(struct usb_hcd *hcd, struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:3955
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
```
**Symbols:**

```
ffffffff818392dd-ffffffff81839341: xhci_alloc_dev.cold (STB_LOCAL)
ffffffff81837950-ffffffff81837bd0: xhci_alloc_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int xhci_alloc_dev(struct usb_hcd *hcd, struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:3959
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
```
**Symbols:**

```
ffffffff8190ba1a-ffffffff8190ba7e: xhci_alloc_dev.cold (STB_LOCAL)
ffffffff8190a040-ffffffff8190a2c0: xhci_alloc_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int xhci_alloc_dev(struct usb_hcd *hcd, struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:4097
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
```
**Symbols:**

```
ffffffff81c21425-ffffffff81c21489: xhci_alloc_dev.cold (STB_LOCAL)
ffffffff819128a0-ffffffff81912b0b: xhci_alloc_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int xhci_alloc_dev(struct usb_hcd *hcd, struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:4024
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
```
**Symbols:**

```
ffffffff81c134dc-ffffffff81c13540: xhci_alloc_dev.cold (STB_LOCAL)
ffffffff818f5d80-ffffffff818f5fe5: xhci_alloc_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int xhci_alloc_dev(struct usb_hcd *hcd, struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:4047
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
```
**Symbols:**

```
ffffffff81d202e1-ffffffff81d20355: xhci_alloc_dev.cold (STB_LOCAL)
ffffffff81993ee0-ffffffff819941a0: xhci_alloc_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int xhci_alloc_dev(struct usb_hcd *hcd, struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:4079
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
```
**Symbols:**

```
ffffffff81eebe28-ffffffff81eebe8c: xhci_alloc_dev.cold (STB_LOCAL)
ffffffff81af09e0-ffffffff81af0cb5: xhci_alloc_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xhci_alloc_dev(struct usb_hcd *hcd, struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81c7d870)
Location: drivers/usb/host/xhci.c:4082
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
```
**Symbols:**

```
ffffffff81c7d870-ffffffff81c7dbe7: xhci_alloc_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xhci_alloc_dev(struct usb_hcd *hcd, struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81ce4ae0)
Location: drivers/usb/host/xhci.c:3922
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
```
**Symbols:**

```
ffffffff81ce4ae0-ffffffff81ce4e57: xhci_alloc_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xhci_alloc_dev(struct usb_hcd *hcd, struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81d99b50)
Location: drivers/usb/host/xhci.c:3973
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
```
**Symbols:**

```
ffffffff81d99b50-ffffffff81d99ec7: xhci_alloc_dev (STB_GLOBAL)
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
int xhci_alloc_dev(struct usb_hcd *hcd, struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffff800010a75ad0)
Location: drivers/usb/host/xhci.c:3955
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
```
**Symbols:**

```
ffff800010a75ad0-ffff800010a75e80: xhci_alloc_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int xhci_alloc_dev(struct usb_hcd *hcd, struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (c0b494ec)
Location: drivers/usb/host/xhci.c:3955
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
```
**Symbols:**

```
c0b494ec-c0b497f4: xhci_alloc_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int xhci_alloc_dev(struct usb_hcd *hcd, struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (c000000000b4be80)
Location: drivers/usb/host/xhci.c:3955
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
```
**Symbols:**

```
c000000000b4be80-c000000000b4c290: xhci_alloc_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int xhci_alloc_dev(struct usb_hcd *hcd, struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffe00068da84)
Location: drivers/usb/host/xhci.c:3955
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
```
**Symbols:**

```
ffffffe00068da84-ffffffe00068dd50: xhci_alloc_dev (STB_GLOBAL)
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
int xhci_alloc_dev(struct usb_hcd *hcd, struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:3955
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
```
**Symbols:**

```
ffffffff817f168d-ffffffff817f16f1: xhci_alloc_dev.cold (STB_LOCAL)
ffffffff817efd00-ffffffff817eff80: xhci_alloc_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int xhci_alloc_dev(struct usb_hcd *hcd, struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:3955
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
```
**Symbols:**

```
ffffffff817b6823-ffffffff817b6897: xhci_alloc_dev.cold (STB_LOCAL)
ffffffff817b4e10-ffffffff817b50de: xhci_alloc_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int xhci_alloc_dev(struct usb_hcd *hcd, struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:3955
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
```
**Symbols:**

```
ffffffff8182e15d-ffffffff8182e1c1: xhci_alloc_dev.cold (STB_LOCAL)
ffffffff8182c7d0-ffffffff8182ca50: xhci_alloc_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int xhci_alloc_dev(struct usb_hcd *hcd, struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:3955
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
```
**Symbols:**

```
ffffffff81848243-ffffffff818482a7: xhci_alloc_dev.cold (STB_LOCAL)
ffffffff818467c0-ffffffff81846a5c: xhci_alloc_dev (STB_GLOBAL)
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
