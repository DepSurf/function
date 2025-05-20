# Function: <code>vfio_vc_cap_len</code>

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
In drivers/vfio/pci/vfio_pci_config.c (ffffffff817dae4b)
Location: drivers/vfio/pci/vfio_pci_config.c:1188
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
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
In drivers/vfio/pci/vfio_pci_config.c (ffffffff818a8b70)
Location: drivers/vfio/pci/vfio_pci_config.c:1220
Inline: True
```
**Symbols:**

```
ffffffff818a8b70-ffffffff818a8c39: vfio_vc_cap_len.isra.0 (STB_LOCAL)
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
In drivers/vfio/pci/vfio_pci_config.c (ffffffff818b7ab0)
Location: drivers/vfio/pci/vfio_pci_config.c:1225
Inline: True
```
**Symbols:**

```
ffffffff818b7ab0-ffffffff818b7b79: vfio_vc_cap_len.isra.0 (STB_LOCAL)
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
In drivers/vfio/pci/vfio_pci_config.c (ffffffff8189aff0)
Location: drivers/vfio/pci/vfio_pci_config.c:1225
Inline: True
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
In drivers/vfio/pci/vfio_pci_config.c (ffffffff8192f0c0)
Location: drivers/vfio/pci/vfio_pci_config.c:1225
Inline: True
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
In drivers/vfio/pci/vfio_pci_config.c (ffffffff81a859fe)
Location: drivers/vfio/pci/vfio_pci_config.c:1261
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ext_cap_len
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
In drivers/vfio/pci/vfio_pci_config.c (c000000000abb9a0)
Location: drivers/vfio/pci/vfio_pci_config.c:1188
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
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
In drivers/vfio/pci/vfio_pci_config.c (ffffffff81784efb)
Location: drivers/vfio/pci/vfio_pci_config.c:1188
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
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
In drivers/vfio/pci/vfio_pci_config.c (ffffffff817cfccb)
Location: drivers/vfio/pci/vfio_pci_config.c:1188
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
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
In drivers/vfio/pci/vfio_pci_config.c (ffffffff817e9f6b)
Location: drivers/vfio/pci/vfio_pci_config.c:1188
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
```
</details>
</li>
</ul>

## Differences
