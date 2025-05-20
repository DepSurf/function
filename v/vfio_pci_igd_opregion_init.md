# Function: <code>vfio_pci_igd_opregion_init</code>

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
In drivers/vfio/pci/vfio_pci_igd.c (ffffffff817dc516)
Location: drivers/vfio/pci/vfio_pci_igd.c:55
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
int vfio_pci_igd_opregion_init(struct vfio_pci_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_igd.c (ffffffff818aa530)
Location: drivers/vfio/pci/vfio_pci_igd.c:55
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
```
**Symbols:**

```
ffffffff818aa530-ffffffff818aa68e: vfio_pci_igd_opregion_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vfio_pci_igd_opregion_init(struct vfio_pci_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_igd.c (ffffffff818b9250)
Location: drivers/vfio/pci/vfio_pci_igd.c:55
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
```
**Symbols:**

```
ffffffff818b9250-ffffffff818b93ae: vfio_pci_igd_opregion_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vfio_pci_igd_opregion_init(struct vfio_pci_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_igd.c (ffffffff8189c740)
Location: drivers/vfio/pci/vfio_pci_igd.c:59
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
```
**Symbols:**

```
ffffffff8189c740-ffffffff8189c93b: vfio_pci_igd_opregion_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int vfio_pci_igd_opregion_init(struct vfio_pci_core_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_igd.c (ffffffff81930b60)
Location: drivers/vfio/pci/vfio_pci_igd.c:60
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
```
**Symbols:**

```
ffffffff81930b60-ffffffff81930d5b: vfio_pci_igd_opregion_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vfio_pci_igd_opregion_init(struct vfio_pci_core_device *vdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_igd.c (ffffffff81a87940)
Location: drivers/vfio/pci/vfio_pci_igd.c:168
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_init
```
**Symbols:**

```
ffffffff81a87940-ffffffff81a87b39: vfio_pci_igd_opregion_init (STB_LOCAL)
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
In drivers/vfio/pci/vfio_pci_igd.c (ffffffff817865c6)
Location: drivers/vfio/pci/vfio_pci_igd.c:55
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
In drivers/vfio/pci/vfio_pci_igd.c (ffffffff817d1396)
Location: drivers/vfio/pci/vfio_pci_igd.c:55
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
In drivers/vfio/pci/vfio_pci_igd.c (ffffffff817eb636)
Location: drivers/vfio/pci/vfio_pci_igd.c:55
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct vfio_pci_device *vdev</code> ➡️ <code>struct vfio_pci_core_device *vdev</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
