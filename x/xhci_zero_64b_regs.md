# Function: <code>xhci_zero_64b_regs</code>

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
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void xhci_zero_64b_regs(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8179b890)
Location: drivers/usb/host/xhci.c:227
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_resume
```
**Symbols:**

```
ffffffff8179b890-ffffffff8179b9c7: xhci_zero_64b_regs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void xhci_zero_64b_regs(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff817c1c50)
Location: drivers/usb/host/xhci.c:228
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_resume
```
**Symbols:**

```
ffffffff817c1c50-ffffffff817c1d87: xhci_zero_64b_regs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xhci_zero_64b_regs(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81807c3d)
Location: drivers/usb/host/xhci.c:226
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_resume
```
**Symbols:**

```
ffffffff81802cb0-ffffffff81802cdf: xhci_zero_64b_regs (STB_LOCAL)
ffffffff81807bf4-ffffffff81807cde: xhci_zero_64b_regs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xhci_zero_64b_regs(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81838aec)
Location: drivers/usb/host/xhci.c:226
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_resume
```
**Symbols:**

```
ffffffff81833bb0-ffffffff81833bdf: xhci_zero_64b_regs (STB_LOCAL)
ffffffff81838aa3-ffffffff81838b8d: xhci_zero_64b_regs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void xhci_zero_64b_regs(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:226
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_resume
```
**Symbols:**

```
ffffffff81906a70-ffffffff81906aa2: xhci_zero_64b_regs (STB_LOCAL)
ffffffff8190b38e-ffffffff8190b478: xhci_zero_64b_regs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void xhci_zero_64b_regs(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:226
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_resume
```
**Symbols:**

```
ffffffff8190f210-ffffffff8190f242: xhci_zero_64b_regs (STB_LOCAL)
ffffffff81c20dbb-ffffffff81c20ea5: xhci_zero_64b_regs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void xhci_zero_64b_regs(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:225
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_resume
```
**Symbols:**

```
ffffffff818f27f0-ffffffff818f2815: xhci_zero_64b_regs (STB_LOCAL)
ffffffff81c12de5-ffffffff81c12eea: xhci_zero_64b_regs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void xhci_zero_64b_regs(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:225
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_resume
```
**Symbols:**

```
ffffffff8198fa60-ffffffff8198fa85: xhci_zero_64b_regs (STB_LOCAL)
ffffffff81d1fb67-ffffffff81d1fc6c: xhci_zero_64b_regs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void xhci_zero_64b_regs(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:226
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_resume
```
**Symbols:**

```
ffffffff81aebf90-ffffffff81aebfdd: xhci_zero_64b_regs (STB_LOCAL)
ffffffff81eeb714-ffffffff81eeb82d: xhci_zero_64b_regs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xhci_zero_64b_regs(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81c785e0)
Location: drivers/usb/host/xhci.c:228
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_resume
```
**Symbols:**

```
ffffffff81c785e0-ffffffff81c7875e: xhci_zero_64b_regs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81ce09d3)
Location: drivers/usb/host/xhci.c:229
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_resume
Direct callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_resume
```
**Symbols:**

```
ffffffff81cdf660-ffffffff81cdf7df: xhci_zero_64b_regs.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81d95b23)
Location: drivers/usb/host/xhci.c:253
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_resume
Direct callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_resume
```
**Symbols:**

```
ffffffff81d94600-ffffffff81d9477f: xhci_zero_64b_regs.part.0 (STB_LOCAL)
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
void xhci_zero_64b_regs(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffff800010a70e00)
Location: drivers/usb/host/xhci.c:226
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_resume
```
**Symbols:**

```
ffff800010a70e00-ffff800010a70fc8: xhci_zero_64b_regs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void xhci_zero_64b_regs(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (c0b44bfc)
Location: drivers/usb/host/xhci.c:226
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_resume
```
**Symbols:**

```
c0b44bfc-c0b44dfc: xhci_zero_64b_regs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void xhci_zero_64b_regs(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (c000000000b459b0)
Location: drivers/usb/host/xhci.c:226
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_resume
```
**Symbols:**

```
c000000000b459b0-c000000000b45bf0: xhci_zero_64b_regs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void xhci_zero_64b_regs(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffe0006894a2)
Location: drivers/usb/host/xhci.c:226
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_resume
```
**Symbols:**

```
ffffffe0006894a2-ffffffe000689648: xhci_zero_64b_regs (STB_LOCAL)
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
void xhci_zero_64b_regs(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff817f0e9c)
Location: drivers/usb/host/xhci.c:226
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_resume
```
**Symbols:**

```
ffffffff817ebf80-ffffffff817ebfaf: xhci_zero_64b_regs (STB_LOCAL)
ffffffff817f0e53-ffffffff817f0f3d: xhci_zero_64b_regs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xhci_zero_64b_regs(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff817b6032)
Location: drivers/usb/host/xhci.c:226
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_resume
```
**Symbols:**

```
ffffffff817b1090-ffffffff817b10bf: xhci_zero_64b_regs (STB_LOCAL)
ffffffff817b5fe9-ffffffff817b60d3: xhci_zero_64b_regs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xhci_zero_64b_regs(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8182d96c)
Location: drivers/usb/host/xhci.c:226
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_resume
```
**Symbols:**

```
ffffffff81828a30-ffffffff81828a5f: xhci_zero_64b_regs (STB_LOCAL)
ffffffff8182d923-ffffffff8182da0d: xhci_zero_64b_regs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xhci_zero_64b_regs(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81847a55)
Location: drivers/usb/host/xhci.c:226
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_resume
```
**Symbols:**

```
ffffffff818429f0-ffffffff81842a1f: xhci_zero_64b_regs (STB_LOCAL)
ffffffff81847a0c-ffffffff81847af6: xhci_zero_64b_regs.cold (STB_LOCAL)
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
