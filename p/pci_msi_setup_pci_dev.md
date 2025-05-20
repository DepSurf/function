# Function: <code>pci_msi_setup_pci_dev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void pci_msi_setup_pci_dev(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81431010)
Location: drivers/pci/probe.c:1165
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
```
**Symbols:**

```
ffffffff81431010-ffffffff814310e5: pci_msi_setup_pci_dev (STB_GLOBAL)
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
In drivers/pci/probe.c (ffffffff8147cd67)
Location: drivers/pci/probe.c:1177
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
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
In drivers/pci/probe.c (ffffffff8149e2c7)
Location: drivers/pci/probe.c:1298
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
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
In drivers/pci/probe.c (ffffffff814a81ad)
Location: drivers/pci/probe.c:1342
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
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
In drivers/pci/probe.c (ffffffff814e71ed)
Location: drivers/pci/probe.c:1384
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
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
In drivers/pci/probe.c (ffffffff815167fd)
Location: drivers/pci/probe.c:1508
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
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
In drivers/pci/probe.c (ffffffff8152c210)
Location: drivers/pci/probe.c:1538
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
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
In drivers/pci/probe.c (ffffffff8155abf0)
Location: drivers/pci/probe.c:1639
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
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
In drivers/pci/probe.c (ffffffff8157bc80)
Location: drivers/pci/probe.c:1653
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pci_msi_setup_pci_dev(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8161fff0)
Location: drivers/pci/probe.c:1701
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_init_capabilities
```
**Symbols:**

```
ffffffff8161fff0-ffffffff816200bc: pci_msi_setup_pci_dev (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In drivers/pci/probe.c (ffff8000106df260)
Location: drivers/pci/probe.c:1653
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
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
In drivers/pci/probe.c (c087aee0)
Location: drivers/pci/probe.c:1653
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
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
In drivers/pci/probe.c (c0000000008578e0)
Location: drivers/pci/probe.c:1653
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
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
In drivers/pci/probe.c (ffffffe0004b72b8)
Location: drivers/pci/probe.c:1653
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
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
In drivers/pci/probe.c (ffffffff815701a0)
Location: drivers/pci/probe.c:1653
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
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
In drivers/pci/probe.c (ffffffff8155e900)
Location: drivers/pci/probe.c:1653
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
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
In drivers/pci/probe.c (ffffffff8156f9d0)
Location: drivers/pci/probe.c:1653
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
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
In drivers/pci/probe.c (ffffffff81589eb0)
Location: drivers/pci/probe.c:1653
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
