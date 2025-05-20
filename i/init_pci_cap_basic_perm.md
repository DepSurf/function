# Function: <code>init_pci_cap_basic_perm</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff8290cb38)
Location: drivers/vfio/pci/vfio_pci_config.c:617
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
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
In drivers/vfio/pci/vfio_pci_config.c (ffffffff82d2173f)
Location: drivers/vfio/pci/vfio_pci_config.c:643
Inline: True
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
```
**Symbols:**

```
ffffffff82d2173f-ffffffff82d218a0: init_pci_cap_basic_perm.constprop.0 (STB_LOCAL)
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
In drivers/vfio/pci/vfio_pci_config.c (ffffffff8300f53f)
Location: drivers/vfio/pci/vfio_pci_config.c:648
Inline: True
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
```
**Symbols:**

```
ffffffff8300f53f-ffffffff8300f6a0: init_pci_cap_basic_perm.constprop.0 (STB_LOCAL)
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
In drivers/vfio/pci/vfio_pci_config.c (ffffffff8321a578)
Location: drivers/vfio/pci/vfio_pci_config.c:648
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
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
In drivers/vfio/pci/vfio_pci_config.c (ffffffff83303ef2)
Location: drivers/vfio/pci/vfio_pci_config.c:648
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
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
In drivers/vfio/pci/vfio_pci_config.c (ffffffff834bceed)
Location: drivers/vfio/pci/vfio_pci_config.c:651
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
```
</details>
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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (c0000000013b0834)
Location: drivers/vfio/pci/vfio_pci_config.c:617
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff828eb9c0)
Location: drivers/vfio/pci/vfio_pci_config.c:617
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
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
In drivers/vfio/pci/vfio_pci_config.c (ffffffff82907f33)
Location: drivers/vfio/pci/vfio_pci_config.c:617
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
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
In drivers/vfio/pci/vfio_pci_config.c (ffffffff8290db9a)
Location: drivers/vfio/pci/vfio_pci_config.c:617
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
```
</details>
</li>
</ul>

## Differences
