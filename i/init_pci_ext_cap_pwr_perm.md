# Function: <code>init_pci_ext_cap_pwr_perm</code>

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
In drivers/vfio/pci/vfio_pci_config.c (ffffffff8290cf8b)
Location: drivers/vfio/pci/vfio_pci_config.c:983
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
In drivers/vfio/pci/vfio_pci_config.c (ffffffff82d21bae)
Location: drivers/vfio/pci/vfio_pci_config.c:1015
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
In drivers/vfio/pci/vfio_pci_config.c (ffffffff8300f9ae)
Location: drivers/vfio/pci/vfio_pci_config.c:1020
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
In drivers/vfio/pci/vfio_pci_config.c (ffffffff8321a9cb)
Location: drivers/vfio/pci/vfio_pci_config.c:1020
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
In drivers/vfio/pci/vfio_pci_config.c (ffffffff83304345)
Location: drivers/vfio/pci/vfio_pci_config.c:1020
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
In drivers/vfio/pci/vfio_pci_config.c (ffffffff834bd352)
Location: drivers/vfio/pci/vfio_pci_config.c:1056
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
In drivers/vfio/pci/vfio_pci_config.c (c0000000013b0c28)
Location: drivers/vfio/pci/vfio_pci_config.c:983
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
In drivers/vfio/pci/vfio_pci_config.c (ffffffff828ebe13)
Location: drivers/vfio/pci/vfio_pci_config.c:983
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
In drivers/vfio/pci/vfio_pci_config.c (ffffffff82908386)
Location: drivers/vfio/pci/vfio_pci_config.c:983
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
In drivers/vfio/pci/vfio_pci_config.c (ffffffff8290dfed)
Location: drivers/vfio/pci/vfio_pci_config.c:983
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_init_perm_bits
```
</details>
</li>
</ul>

## Differences
