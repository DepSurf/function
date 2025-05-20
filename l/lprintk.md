# Function: <code>lprintk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void lprintk(char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81644d10)
Location: drivers/usb/host/uhci-debug.c:26
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_irq
```
**Symbols:**

```
ffffffff81644d10-ffffffff81644d6b: lprintk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void lprintk(char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff816a5860)
Location: drivers/usb/host/uhci-debug.c:26
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_irq
```
**Symbols:**

```
ffffffff816a5860-ffffffff816a58c2: lprintk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void lprintk(char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff816d3960)
Location: drivers/usb/host/uhci-debug.c:26
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_irq
```
**Symbols:**

```
ffffffff816d3960-ffffffff816d39c2: lprintk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void lprintk(char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff816e7fc0)
Location: drivers/usb/host/uhci-debug.c:26
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_irq
```
**Symbols:**

```
ffffffff816e7fc0-ffffffff816e8023: lprintk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void lprintk(char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff817547a0)
Location: drivers/usb/host/uhci-debug.c:27
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_irq
```
**Symbols:**

```
ffffffff817547a0-ffffffff81754803: lprintk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81799199)
Location: drivers/usb/host/uhci-debug.c:27
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_irq
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_irq
```
**Symbols:**

```
ffffffff81796f30-ffffffff81796f4e: lprintk.part.29 (STB_LOCAL)
ffffffff8179a3c0-ffffffff8179a410: lprintk.part.29.cold.46 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff817bf909)
Location: drivers/usb/host/uhci-debug.c:27
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_irq
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_irq
```
**Symbols:**

```
ffffffff817bd840-ffffffff817bd85e: lprintk.part.33 (STB_LOCAL)
ffffffff817c074f-ffffffff817c079f: lprintk.part.33.cold.41 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void lprintk(char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (0)
Location: drivers/usb/host/uhci-debug.c:27
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_irq
```
**Symbols:**

```
ffffffff817fac00-ffffffff817fac1e: lprintk (STB_LOCAL)
ffffffff817fff31-ffffffff817fff7e: lprintk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void lprintk(char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (0)
Location: drivers/usb/host/uhci-debug.c:27
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_irq
```
**Symbols:**

```
ffffffff8182ba40-ffffffff8182ba5e: lprintk (STB_LOCAL)
ffffffff81830d7e-ffffffff81830dcb: lprintk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void lprintk(char *buf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff818ffa38)
Location: drivers/usb/host/uhci-debug.c:27
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_result_common
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_irq
```
**Symbols:**

```
ffffffff818fde10-ffffffff818fde2d: lprintk (STB_LOCAL)
ffffffff81903125-ffffffff81903172: lprintk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void lprintk(char *buf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81908308)
Location: drivers/usb/host/uhci-debug.c:27
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_result_common
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_irq
```
**Symbols:**

```
ffffffff819066f0-ffffffff8190670d: lprintk (STB_LOCAL)
ffffffff81c20740-ffffffff81c2078d: lprintk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void lprintk(char *buf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff818ebae8)
Location: drivers/usb/host/uhci-debug.c:27
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_result_common
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_irq
```
**Symbols:**

```
ffffffff818e9d00-ffffffff818e9d0f: lprintk (STB_LOCAL)
ffffffff81c127a5-ffffffff81c127f7: lprintk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void lprintk(char *buf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff819881f8)
Location: drivers/usb/host/uhci-debug.c:27
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_result_common
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_irq
```
**Symbols:**

```
ffffffff819863a0-ffffffff819863af: lprintk (STB_LOCAL)
ffffffff81d1f298-ffffffff81d1f2ea: lprintk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void lprintk(char *buf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81ae4d24)
Location: drivers/usb/host/uhci-debug.c:27
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_result_common
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_irq
```
**Symbols:**

```
ffffffff81ae22a0-ffffffff81ae22b9: lprintk (STB_LOCAL)
ffffffff81eeadbb-ffffffff81eeae17: lprintk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81c717f7)
Location: drivers/usb/host/uhci-debug.c:27
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:uhci_result_common
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81cd8dc7)
Location: drivers/usb/host/uhci-debug.c:27
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:uhci_result_common
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81d8ddd7)
Location: drivers/usb/host/uhci-debug.c:27
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:uhci_result_common
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
void lprintk(char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffff800010a67298)
Location: drivers/usb/host/uhci-debug.c:27
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_irq
```
**Symbols:**

```
ffff800010a67298-ffff800010a6730c: lprintk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void lprintk(char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (c0b39180)
Location: drivers/usb/host/uhci-debug.c:27
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_irq
```
**Symbols:**

```
c0b39180-c0b391e8: lprintk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void lprintk(char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (c000000000b384b0)
Location: drivers/usb/host/uhci-debug.c:27
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_irq
```
**Symbols:**

```
c000000000b384b0-c000000000b38554: lprintk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void lprintk(char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffe00068134c)
Location: drivers/usb/host/uhci-debug.c:27
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_irq
```
**Symbols:**

```
ffffffe00068134c-ffffffe0006813b4: lprintk (STB_LOCAL)
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
void lprintk(char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (0)
Location: drivers/usb/host/uhci-debug.c:27
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_irq
```
**Symbols:**

```
ffffffff817e3e20-ffffffff817e3e3e: lprintk (STB_LOCAL)
ffffffff817e915e-ffffffff817e91ab: lprintk.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void lprintk(char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (0)
Location: drivers/usb/host/uhci-debug.c:27
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_irq
```
**Symbols:**

```
ffffffff818208c0-ffffffff818208de: lprintk (STB_LOCAL)
ffffffff81825bfe-ffffffff81825c4b: lprintk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void lprintk(char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (0)
Location: drivers/usb/host/uhci-debug.c:27
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_irq
```
**Symbols:**

```
ffffffff8183a9d0-ffffffff8183a9ee: lprintk (STB_LOCAL)
ffffffff8183fb1c-ffffffff8183fb69: lprintk.cold (STB_LOCAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
