# Function: <code>xhci_suspend</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int xhci_suspend(struct xhci_hcd *xhci, bool do_wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8164c920)
Location: drivers/usb/host/xhci.c:892
Inline: False
Direct callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_suspend
```
**Symbols:**

```
ffffffff8164c920-ffffffff8164cd32: xhci_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int xhci_suspend(struct xhci_hcd *xhci, bool do_wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816ad260)
Location: drivers/usb/host/xhci.c:899
Inline: False
Direct callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_suspend
```
**Symbols:**

```
ffffffff816ad260-ffffffff816ad66a: xhci_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int xhci_suspend(struct xhci_hcd *xhci, bool do_wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816db540)
Location: drivers/usb/host/xhci.c:902
Inline: False
Direct callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_suspend
```
**Symbols:**

```
ffffffff816db540-ffffffff816db94a: xhci_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int xhci_suspend(struct xhci_hcd *xhci, bool do_wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816efba0)
Location: drivers/usb/host/xhci.c:865
Inline: False
Direct callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_suspend
```
**Symbols:**

```
ffffffff816efba0-ffffffff816efffb: xhci_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int xhci_suspend(struct xhci_hcd *xhci, bool do_wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8175bd30)
Location: drivers/usb/host/xhci.c:863
Inline: False
Direct callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_suspend
```
**Symbols:**

```
ffffffff8175bd30-ffffffff8175c1bc: xhci_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int xhci_suspend(struct xhci_hcd *xhci, bool do_wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8179c720)
Location: drivers/usb/host/xhci.c:967
Inline: False
Direct callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_suspend
```
**Symbols:**

```
ffffffff8179c720-ffffffff8179cb82: xhci_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xhci_suspend(struct xhci_hcd *xhci, bool do_wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff817c2ae0)
Location: drivers/usb/host/xhci.c:966
Inline: False
Direct callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_suspend
```
**Symbols:**

```
ffffffff817c2ae0-ffffffff817c2f65: xhci_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int xhci_suspend(struct xhci_hcd *xhci, bool do_wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:973
Inline: False
Direct callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_suspend
```
**Symbols:**

```
ffffffff81807bc4-ffffffff81807bf4: xhci_suspend.cold (STB_LOCAL)
ffffffff818027e0-ffffffff81802ca1: xhci_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int xhci_suspend(struct xhci_hcd *xhci, bool do_wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:970
Inline: False
Direct callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_suspend
```
**Symbols:**

```
ffffffff81838a73-ffffffff81838aa3: xhci_suspend.cold (STB_LOCAL)
ffffffff818336e0-ffffffff81833ba1: xhci_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int xhci_suspend(struct xhci_hcd *xhci, bool do_wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:970
Inline: False
```
**Symbols:**

```
ffffffff8190b359-ffffffff8190b38e: xhci_suspend.cold (STB_LOCAL)
ffffffff81906770-ffffffff81906a64: xhci_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int xhci_suspend(struct xhci_hcd *xhci, bool do_wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:968
Inline: False
```
**Symbols:**

```
ffffffff81c20d86-ffffffff81c20dbb: xhci_suspend.cold (STB_LOCAL)
ffffffff8190ef00-ffffffff8190f20d: xhci_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int xhci_suspend(struct xhci_hcd *xhci, bool do_wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:971
Inline: False
```
**Symbols:**

```
ffffffff81c12db0-ffffffff81c12de5: xhci_suspend.cold (STB_LOCAL)
ffffffff818f2450-ffffffff818f27e6: xhci_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int xhci_suspend(struct xhci_hcd *xhci, bool do_wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:971
Inline: False
```
**Symbols:**

```
ffffffff81d1fb14-ffffffff81d1fb67: xhci_suspend.cold (STB_LOCAL)
ffffffff8198f6a0-ffffffff8198fa5d: xhci_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int xhci_suspend(struct xhci_hcd *xhci, bool do_wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:1008
Inline: False
```
**Symbols:**

```
ffffffff81eeb6b4-ffffffff81eeb714: xhci_suspend.cold (STB_LOCAL)
ffffffff81aebb80-ffffffff81aebf8d: xhci_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int xhci_suspend(struct xhci_hcd *xhci, bool do_wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:1005
Inline: False
```
**Symbols:**

```
ffffffff820a5751-ffffffff820a576f: xhci_suspend.cold (STB_LOCAL)
ffffffff81c78180-ffffffff81c785cf: xhci_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int xhci_suspend(struct xhci_hcd *xhci, bool do_wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:849
Inline: False
```
**Symbols:**

```
ffffffff82126bc9-ffffffff82126be7: xhci_suspend.cold (STB_LOCAL)
ffffffff81cdf260-ffffffff81cdf647: xhci_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int xhci_suspend(struct xhci_hcd *xhci, bool do_wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:888
Inline: False
```
**Symbols:**

```
ffffffff822083cc-ffffffff822083ea: xhci_suspend.cold (STB_LOCAL)
ffffffff81d941e0-ffffffff81d945ea: xhci_suspend (STB_GLOBAL)
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
int xhci_suspend(struct xhci_hcd *xhci, bool do_wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffff800010a706f0)
Location: drivers/usb/host/xhci.c:970
Inline: False
Direct callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_suspend
```
**Symbols:**

```
ffff800010a706f0-ffff800010a70e00: xhci_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int xhci_suspend(struct xhci_hcd *xhci, bool do_wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (c0b4465c)
Location: drivers/usb/host/xhci.c:970
Inline: False
Direct callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_suspend
```
**Symbols:**

```
c0b4465c-c0b44bfc: xhci_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int xhci_suspend(struct xhci_hcd *xhci, bool do_wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (c000000000b44dd0)
Location: drivers/usb/host/xhci.c:970
Inline: False
Direct callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_suspend
```
**Symbols:**

```
c000000000b44dd0-c000000000b459b0: xhci_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int xhci_suspend(struct xhci_hcd *xhci, bool do_wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffe000688e84)
Location: drivers/usb/host/xhci.c:970
Inline: False
Direct callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_suspend
```
**Symbols:**

```
ffffffe000688e84-ffffffe0006894a2: xhci_suspend (STB_GLOBAL)
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
int xhci_suspend(struct xhci_hcd *xhci, bool do_wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:970
Inline: False
Direct callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_suspend
```
**Symbols:**

```
ffffffff817f0e23-ffffffff817f0e53: xhci_suspend.cold (STB_LOCAL)
ffffffff817ebac0-ffffffff817ebf79: xhci_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int xhci_suspend(struct xhci_hcd *xhci, bool do_wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:970
Inline: False
Direct callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_suspend
```
**Symbols:**

```
ffffffff817b5fb9-ffffffff817b5fe9: xhci_suspend.cold (STB_LOCAL)
ffffffff817b0bd0-ffffffff817b108b: xhci_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int xhci_suspend(struct xhci_hcd *xhci, bool do_wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:970
Inline: False
Direct callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_suspend
```
**Symbols:**

```
ffffffff8182d8f3-ffffffff8182d923: xhci_suspend.cold (STB_LOCAL)
ffffffff81828560-ffffffff81828a21: xhci_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int xhci_suspend(struct xhci_hcd *xhci, bool do_wakeup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:970
Inline: False
Direct callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_suspend
```
**Symbols:**

```
ffffffff818479dc-ffffffff81847a0c: xhci_suspend.cold (STB_LOCAL)
ffffffff81842530-ffffffff818429e8: xhci_suspend (STB_GLOBAL)
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
