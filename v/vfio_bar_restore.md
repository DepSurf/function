# Function: <code>vfio_bar_restore</code>

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
In drivers/vfio/pci/vfio_pci_config.c (ffffffff817da6e9)
Location: drivers/vfio/pci/vfio_pci_config.c:402
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void vfio_bar_restore(struct vfio_pci_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: drivers/vfio/pci/vfio_pci_config.c:416
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
```
**Symbols:**

```
ffffffff818a83d0-ffffffff818a8422: vfio_bar_restore (STB_LOCAL)
ffffffff818aa253-ffffffff818aa2e3: vfio_bar_restore.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void vfio_bar_restore(struct vfio_pci_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: drivers/vfio/pci/vfio_pci_config.c:416
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
```
**Symbols:**

```
ffffffff818b7200-ffffffff818b7252: vfio_bar_restore (STB_LOCAL)
ffffffff81c1a2d2-ffffffff81c1a362: vfio_bar_restore.cold (STB_LOCAL)
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
In drivers/vfio/pci/vfio_pci_config.c (ffffffff8189a81a)
Location: drivers/vfio/pci/vfio_pci_config.c:416
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
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
In drivers/vfio/pci/vfio_pci_config.c (ffffffff8192ed3b)
Location: drivers/vfio/pci/vfio_pci_config.c:416
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
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
In drivers/vfio/pci/vfio_pci_config.c (ffffffff81a855ff)
Location: drivers/vfio/pci/vfio_pci_config.c:419
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
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
In drivers/vfio/pci/vfio_pci_config.c (c000000000abadc0)
Location: drivers/vfio/pci/vfio_pci_config.c:402
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
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
In drivers/vfio/pci/vfio_pci_config.c (ffffffff81784799)
Location: drivers/vfio/pci/vfio_pci_config.c:402
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
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
In drivers/vfio/pci/vfio_pci_config.c (ffffffff817cf569)
Location: drivers/vfio/pci/vfio_pci_config.c:402
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
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
In drivers/vfio/pci/vfio_pci_config.c (ffffffff817e9809)
Location: drivers/vfio/pci/vfio_pci_config.c:402
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_basic_config_write
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
</ul>
