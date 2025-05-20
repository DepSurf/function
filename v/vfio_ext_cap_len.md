# Function: <code>vfio_ext_cap_len</code>

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
In drivers/vfio/pci/vfio_pci_config.c (ffffffff817dada1)
Location: drivers/vfio/pci/vfio_pci_config.c:1304
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
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: drivers/vfio/pci/vfio_pci_config.c:1336
Inline: True
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
```
**Symbols:**

```
ffffffff818a8c40-ffffffff818a8e03: vfio_ext_cap_len.isra.0 (STB_LOCAL)
ffffffff818aa2e3-ffffffff818aa30a: vfio_ext_cap_len.isra.0.cold (STB_LOCAL)
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
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: drivers/vfio/pci/vfio_pci_config.c:1341
Inline: True
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
```
**Symbols:**

```
ffffffff818b7b80-ffffffff818b7d43: vfio_ext_cap_len.isra.0 (STB_LOCAL)
ffffffff81c1a362-ffffffff81c1a389: vfio_ext_cap_len.isra.0.cold (STB_LOCAL)
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
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: drivers/vfio/pci/vfio_pci_config.c:1341
Inline: True
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
```
**Symbols:**

```
ffffffff8189af50-ffffffff8189b19f: vfio_ext_cap_len.isra.0 (STB_LOCAL)
ffffffff81c0c251-ffffffff81c0c278: vfio_ext_cap_len.isra.0.cold (STB_LOCAL)
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
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: drivers/vfio/pci/vfio_pci_config.c:1341
Inline: True
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
```
**Symbols:**

```
ffffffff8192f020-ffffffff8192f26f: vfio_ext_cap_len.isra.0 (STB_LOCAL)
ffffffff81d126df-ffffffff81d12706: vfio_ext_cap_len.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int vfio_ext_cap_len(struct vfio_pci_core_device *vdev, u16 ecap, u16 epos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: drivers/vfio/pci/vfio_pci_config.c:1377
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
```
**Symbols:**

```
ffffffff81a85930-ffffffff81a85bc6: vfio_ext_cap_len (STB_LOCAL)
ffffffff81edd3e4-ffffffff81edd40d: vfio_ext_cap_len.cold (STB_LOCAL)
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
In drivers/vfio/pci/vfio_pci_config.c (c000000000abb810)
Location: drivers/vfio/pci/vfio_pci_config.c:1304
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
In drivers/vfio/pci/vfio_pci_config.c (ffffffff81784e51)
Location: drivers/vfio/pci/vfio_pci_config.c:1304
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
In drivers/vfio/pci/vfio_pci_config.c (ffffffff817cfc21)
Location: drivers/vfio/pci/vfio_pci_config.c:1304
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
In drivers/vfio/pci/vfio_pci_config.c (ffffffff817e9ec1)
Location: drivers/vfio/pci/vfio_pci_config.c:1304
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_ecap_init
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
