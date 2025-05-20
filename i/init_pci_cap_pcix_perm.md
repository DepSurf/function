# Function: <code>init_pci_cap_pcix_perm</code>

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
In drivers/vfio/pci/vfio_pci_config.c (ffffffff8290cd6a)
Location: drivers/vfio/pci/vfio_pci_config.c:788
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff82d2198d)
Location: drivers/vfio/pci/vfio_pci_config.c:814
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff8300f78d)
Location: drivers/vfio/pci/vfio_pci_config.c:819
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
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
In drivers/vfio/pci/vfio_pci_config.c (ffffffff8321a7aa)
Location: drivers/vfio/pci/vfio_pci_config.c:819
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
In drivers/vfio/pci/vfio_pci_config.c (ffffffff83304124)
Location: drivers/vfio/pci/vfio_pci_config.c:819
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
In drivers/vfio/pci/vfio_pci_config.c (ffffffff834bd139)
Location: drivers/vfio/pci/vfio_pci_config.c:855
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
In drivers/vfio/pci/vfio_pci_config.c (c0000000013b0a2c)
Location: drivers/vfio/pci/vfio_pci_config.c:788
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
In drivers/vfio/pci/vfio_pci_config.c (ffffffff828ebbf2)
Location: drivers/vfio/pci/vfio_pci_config.c:788
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
In drivers/vfio/pci/vfio_pci_config.c (ffffffff82908165)
Location: drivers/vfio/pci/vfio_pci_config.c:788
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
In drivers/vfio/pci/vfio_pci_config.c (ffffffff8290ddcc)
Location: drivers/vfio/pci/vfio_pci_config.c:788
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
```
</details>
</li>
</ul>

## Differences
