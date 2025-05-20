# Function: <code>ehci_mem_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81637a30)
Location: drivers/usb/host/ehci-mem.c:160
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff8169873d)
Location: drivers/usb/host/ehci-mem.c:152
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff816c6c6d)
Location: drivers/usb/host/ehci-mem.c:152
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff816db43a)
Location: drivers/usb/host/ehci-mem.c:152
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81747b6a)
Location: drivers/usb/host/ehci-mem.c:139
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
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
In drivers/usb/host/ehci-hcd.c (ffffffff81788385)
Location: drivers/usb/host/ehci-mem.c:139
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
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
In drivers/usb/host/ehci-hcd.c (ffffffff817b1565)
Location: drivers/usb/host/ehci-mem.c:139
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff817f1d70)
Location: drivers/usb/host/ehci-mem.c:139
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
```
**Symbols:**

```
ffffffff817f1d70-ffffffff817f1fb2: ehci_mem_init.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81822c60)
Location: drivers/usb/host/ehci-mem.c:139
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
```
**Symbols:**

```
ffffffff81822c60-ffffffff81822ea2: ehci_mem_init.constprop.0 (STB_LOCAL)
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
In drivers/usb/host/ehci-hcd.c (ffffffff818edf70)
Location: drivers/usb/host/ehci-mem.c:139
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_init
```
**Symbols:**

```
ffffffff818edf70-ffffffff818ee1bb: ehci_mem_init.constprop.0 (STB_LOCAL)
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
In drivers/usb/host/ehci-hcd.c (ffffffff818f6e90)
Location: drivers/usb/host/ehci-mem.c:139
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_init
```
**Symbols:**

```
ffffffff818f6e90-ffffffff818f70db: ehci_mem_init.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818da480)
Location: drivers/usb/host/ehci-mem.c:139
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_init
```
**Symbols:**

```
ffffffff818da480-ffffffff818da6c8: ehci_mem_init.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81975830)
Location: drivers/usb/host/ehci-mem.c:139
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_init
```
**Symbols:**

```
ffffffff81975830-ffffffff81975a75: ehci_mem_init.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81ad12c0)
Location: drivers/usb/host/ehci-mem.c:138
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_init
```
**Symbols:**

```
ffffffff81ad12c0-ffffffff81ad1512: ehci_mem_init.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81c5bb00)
Location: drivers/usb/host/ehci-mem.c:138
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_init
```
**Symbols:**

```
ffffffff81c5bb00-ffffffff81c5bd52: ehci_mem_init.constprop.0 (STB_LOCAL)
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
In drivers/usb/host/ehci-hcd.c (ffffffff81cc33b0)
Location: drivers/usb/host/ehci-mem.c:138
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_init
```
**Symbols:**

```
ffffffff81cc33b0-ffffffff81cc3602: ehci_mem_init.constprop.0 (STB_LOCAL)
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
In drivers/usb/host/ehci-hcd.c (ffffffff81d782b0)
Location: drivers/usb/host/ehci-mem.c:138
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_init
```
**Symbols:**

```
ffffffff81d782b0-ffffffff81d78502: ehci_mem_init.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffff800010a54e10)
Location: drivers/usb/host/ehci-mem.c:139
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
```
**Symbols:**

```
ffff800010a54e10-ffff800010a54ff0: ehci_mem_init.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (c0b2eaf8)
Location: drivers/usb/host/ehci-mem.c:139
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
```
**Symbols:**

```
c0b2eaf8-c0b2ed1c: ehci_mem_init.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (c000000000b28d90)
Location: drivers/usb/host/ehci-mem.c:139
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
```
**Symbols:**

```
c000000000b28d90-c000000000b28fe0: ehci_mem_init.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffe00067464a)
Location: drivers/usb/host/ehci-mem.c:139
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
```
**Symbols:**

```
ffffffe00067464a-ffffffe000674808: ehci_mem_init.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff817db040)
Location: drivers/usb/host/ehci-mem.c:139
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
```
**Symbols:**

```
ffffffff817db040-ffffffff817db282: ehci_mem_init.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81817ae0)
Location: drivers/usb/host/ehci-mem.c:139
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
```
**Symbols:**

```
ffffffff81817ae0-ffffffff81817d22: ehci_mem_init.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81831ad0)
Location: drivers/usb/host/ehci-mem.c:139
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_setup
```
**Symbols:**

```
ffffffff81831ad0-ffffffff81831d12: ehci_mem_init.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
