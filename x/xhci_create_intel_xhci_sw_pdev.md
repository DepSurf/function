# Function: <code>xhci_create_intel_xhci_sw_pdev</code>

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
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ext-caps.c (ffffffff817a6cfb)
Location: drivers/usb/host/xhci-ext-caps.c:19
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
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
In drivers/usb/host/xhci-ext-caps.c (ffffffff817ccbaa)
Location: drivers/usb/host/xhci-ext-caps.c:19
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ext-caps.c (ffffffff8180ca00)
Location: drivers/usb/host/xhci-ext-caps.c:19
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ext-caps.c (ffffffff8183da00)
Location: drivers/usb/host/xhci-ext-caps.c:28
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int xhci_create_intel_xhci_sw_pdev(struct xhci_hcd *xhci, u32 cap_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ext-caps.c (0)
Location: drivers/usb/host/xhci-ext-caps.c:28
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
**Symbols:**

```
ffffffff819101d0-ffffffff819102e1: xhci_create_intel_xhci_sw_pdev (STB_LOCAL)
ffffffff8191039b-ffffffff81910446: xhci_create_intel_xhci_sw_pdev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int xhci_create_intel_xhci_sw_pdev(struct xhci_hcd *xhci, u32 cap_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ext-caps.c (0)
Location: drivers/usb/host/xhci-ext-caps.c:28
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
**Symbols:**

```
ffffffff81917b00-ffffffff81917c14: xhci_create_intel_xhci_sw_pdev (STB_LOCAL)
ffffffff81c2185a-ffffffff81c21905: xhci_create_intel_xhci_sw_pdev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int xhci_create_intel_xhci_sw_pdev(struct xhci_hcd *xhci, u32 cap_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ext-caps.c (0)
Location: drivers/usb/host/xhci-ext-caps.c:28
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
**Symbols:**

```
ffffffff818faf90-ffffffff818fb0a6: xhci_create_intel_xhci_sw_pdev (STB_LOCAL)
ffffffff81c13905-ffffffff81c139b0: xhci_create_intel_xhci_sw_pdev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int xhci_create_intel_xhci_sw_pdev(struct xhci_hcd *xhci, u32 cap_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ext-caps.c (0)
Location: drivers/usb/host/xhci-ext-caps.c:28
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
**Symbols:**

```
ffffffff81999e00-ffffffff81999f16: xhci_create_intel_xhci_sw_pdev (STB_LOCAL)
ffffffff81d2077f-ffffffff81d2082a: xhci_create_intel_xhci_sw_pdev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int xhci_create_intel_xhci_sw_pdev(struct xhci_hcd *xhci, u32 cap_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ext-caps.c (0)
Location: drivers/usb/host/xhci-ext-caps.c:28
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
**Symbols:**

```
ffffffff81af6e00-ffffffff81af6f23: xhci_create_intel_xhci_sw_pdev (STB_LOCAL)
ffffffff81eec332-ffffffff81eec3dd: xhci_create_intel_xhci_sw_pdev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xhci_create_intel_xhci_sw_pdev(struct xhci_hcd *xhci, u32 cap_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ext-caps.c (ffffffff81c847f0)
Location: drivers/usb/host/xhci-ext-caps.c:28
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
**Symbols:**

```
ffffffff81c847f0-ffffffff81c849a4: xhci_create_intel_xhci_sw_pdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xhci_create_intel_xhci_sw_pdev(struct xhci_hcd *xhci, u32 cap_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ext-caps.c (ffffffff81ceb4b0)
Location: drivers/usb/host/xhci-ext-caps.c:28
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
**Symbols:**

```
ffffffff81ceb4b0-ffffffff81ceb66b: xhci_create_intel_xhci_sw_pdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xhci_create_intel_xhci_sw_pdev(struct xhci_hcd *xhci, u32 cap_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ext-caps.c (ffffffff81da0ad0)
Location: drivers/usb/host/xhci-ext-caps.c:28
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
**Symbols:**

```
ffffffff81da0ad0-ffffffff81da0c8b: xhci_create_intel_xhci_sw_pdev (STB_LOCAL)
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
In drivers/usb/host/xhci-ext-caps.c (ffff800010a7baf4)
Location: drivers/usb/host/xhci-ext-caps.c:28
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ext-caps.c (c0b4efe0)
Location: drivers/usb/host/xhci-ext-caps.c:28
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ext-caps.c (c000000000b53820)
Location: drivers/usb/host/xhci-ext-caps.c:28
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ext-caps.c (ffffffe000692c12)
Location: drivers/usb/host/xhci-ext-caps.c:28
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ext-caps.c (ffffffff817f5db0)
Location: drivers/usb/host/xhci-ext-caps.c:28
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ext-caps.c (ffffffff817baf50)
Location: drivers/usb/host/xhci-ext-caps.c:28
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ext-caps.c (ffffffff81832880)
Location: drivers/usb/host/xhci-ext-caps.c:28
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ext-caps.c (ffffffff8184ca60)
Location: drivers/usb/host/xhci-ext-caps.c:28
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
