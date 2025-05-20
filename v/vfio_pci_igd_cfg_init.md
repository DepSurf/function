# Function: <code>vfio_pci_igd_cfg_init</code>

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
In drivers/vfio/pci/vfio_pci_igd.c (ffffffff817dc61a)
Location: drivers/vfio/pci/vfio_pci_igd.c:216
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vfio_pci_igd_cfg_init(struct vfio_pci_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_igd.c (ffffffff818aa690)
Location: drivers/vfio/pci/vfio_pci_igd.c:216
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
```
**Symbols:**

```
ffffffff818aa690-ffffffff818aa78b: vfio_pci_igd_cfg_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vfio_pci_igd_cfg_init(struct vfio_pci_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_igd.c (ffffffff818b93b0)
Location: drivers/vfio/pci/vfio_pci_igd.c:216
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
```
**Symbols:**

```
ffffffff818b93b0-ffffffff818b94ab: vfio_pci_igd_cfg_init (STB_LOCAL)
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
In drivers/vfio/pci/vfio_pci_igd.c (ffffffff8189cbd7)
Location: drivers/vfio/pci/vfio_pci_igd.c:269
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
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
In drivers/vfio/pci/vfio_pci_igd.c (ffffffff81931017)
Location: drivers/vfio/pci/vfio_pci_igd.c:270
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
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
In drivers/vfio/pci/vfio_pci_igd.c (ffffffff81a87f67)
Location: drivers/vfio/pci/vfio_pci_igd.c:390
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
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
In <code>ppc64el</code>: Absent ⚠️
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
In drivers/vfio/pci/vfio_pci_igd.c (ffffffff817866ca)
Location: drivers/vfio/pci/vfio_pci_igd.c:216
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
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
In drivers/vfio/pci/vfio_pci_igd.c (ffffffff817d149a)
Location: drivers/vfio/pci/vfio_pci_igd.c:216
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
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
In drivers/vfio/pci/vfio_pci_igd.c (ffffffff817eb73a)
Location: drivers/vfio/pci/vfio_pci_igd.c:216
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
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
