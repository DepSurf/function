# Function: <code>find_cap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/aperture_64.c (ffffffff81f7576a)
Location: arch/x86/kernel/aperture_64.c:95
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff81fb0bbf)
Location: drivers/usb/early/ehci-dbgp.c:369
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/aperture_64.c (ffffffff81f9de8f)
Location: arch/x86/kernel/aperture_64.c:95
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff81fdd6ed)
Location: drivers/usb/early/ehci-dbgp.c:369
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/aperture_64.c (ffffffff81fd9412)
Location: arch/x86/kernel/aperture_64.c:95
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff8201b304)
Location: drivers/usb/early/ehci-dbgp.c:368
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/aperture_64.c (ffffffff820ba2b9)
Location: arch/x86/kernel/aperture_64.c:95
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff820fdbc8)
Location: drivers/usb/early/ehci-dbgp.c:368
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/aperture_64.c (ffffffff826c0c68)
Location: arch/x86/kernel/aperture_64.c:124
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff827074b4)
Location: drivers/usb/early/ehci-dbgp.c:369
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/aperture_64.c (ffffffff826eae83)
Location: arch/x86/kernel/aperture_64.c:124
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff827313a5)
Location: drivers/usb/early/ehci-dbgp.c:369
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
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
In drivers/usb/early/ehci-dbgp.c (ffffffff828ea062)
Location: drivers/usb/early/ehci-dbgp.c:369
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
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
In drivers/usb/early/ehci-dbgp.c (ffffffff82904a7e)
Location: drivers/usb/early/ehci-dbgp.c:369
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
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
In drivers/usb/early/ehci-dbgp.c (ffffffff8290e4a8)
Location: drivers/usb/early/ehci-dbgp.c:369
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/early/ehci-dbgp.c (ffffffff82d22481)
Location: drivers/usb/early/ehci-dbgp.c:369
Inline: True
Direct callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
```
**Symbols:**

```
ffffffff82d22481-ffffffff82d22526: find_cap.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/early/ehci-dbgp.c (ffffffff8301027a)
Location: drivers/usb/early/ehci-dbgp.c:364
Inline: True
Direct callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
```
**Symbols:**

```
ffffffff8301027a-ffffffff8301031f: find_cap.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/early/ehci-dbgp.c (ffffffff8321b304)
Location: drivers/usb/early/ehci-dbgp.c:364
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/early/ehci-dbgp.c (ffffffff83305054)
Location: drivers/usb/early/ehci-dbgp.c:364
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/early/ehci-dbgp.c (ffffffff834be153)
Location: drivers/usb/early/ehci-dbgp.c:364
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
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
In drivers/usb/early/ehci-dbgp.c (ffffffff83efc038)
Location: drivers/usb/early/ehci-dbgp.c:364
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
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
In drivers/usb/early/ehci-dbgp.c (ffffffff83721e48)
Location: drivers/usb/early/ehci-dbgp.c:364
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
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
In drivers/usb/early/ehci-dbgp.c (ffffffff83955c78)
Location: drivers/usb/early/ehci-dbgp.c:364
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In drivers/usb/early/ehci-dbgp.c (ffffffff828f5602)
Location: drivers/usb/early/ehci-dbgp.c:369
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
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
In drivers/usb/early/ehci-dbgp.c (ffffffff828ecf16)
Location: drivers/usb/early/ehci-dbgp.c:369
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
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
In drivers/usb/early/ehci-dbgp.c (ffffffff829098a3)
Location: drivers/usb/early/ehci-dbgp.c:369
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
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
In drivers/usb/early/ehci-dbgp.c (ffffffff8290f50a)
Location: drivers/usb/early/ehci-dbgp.c:369
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
```
</details>
</li>
</ul>

## Differences
