# Function: <code>vfio_pci_igd_cfg_rw</code>

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
<summary>In <code>5.4</code>: ✅</summary>

```c
size_t vfio_pci_igd_cfg_rw(struct vfio_pci_device *vdev, char *buf, size_t count, loff_t *ppos, bool iswrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_igd.c (ffffffff817dc280)
Location: drivers/vfio/pci/vfio_pci_igd.c:110
Inline: False
```
**Symbols:**

```
ffffffff817dc280-ffffffff817dc4d3: vfio_pci_igd_cfg_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
size_t vfio_pci_igd_cfg_rw(struct vfio_pci_device *vdev, char *buf, size_t count, loff_t *ppos, bool iswrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_igd.c (ffffffff818aa7b0)
Location: drivers/vfio/pci/vfio_pci_igd.c:110
Inline: False
```
**Symbols:**

```
ffffffff818aa7b0-ffffffff818aaa14: vfio_pci_igd_cfg_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
size_t vfio_pci_igd_cfg_rw(struct vfio_pci_device *vdev, char *buf, size_t count, loff_t *ppos, bool iswrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_igd.c (ffffffff818b94d0)
Location: drivers/vfio/pci/vfio_pci_igd.c:110
Inline: False
```
**Symbols:**

```
ffffffff818b94d0-ffffffff818b9734: vfio_pci_igd_cfg_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
size_t vfio_pci_igd_cfg_rw(struct vfio_pci_device *vdev, char *buf, size_t count, loff_t *ppos, bool iswrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_igd.c (ffffffff8189c960)
Location: drivers/vfio/pci/vfio_pci_igd.c:163
Inline: False
```
**Symbols:**

```
ffffffff8189c960-ffffffff8189cba1: vfio_pci_igd_cfg_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t vfio_pci_igd_cfg_rw(struct vfio_pci_core_device *vdev, char *buf, size_t count, loff_t *ppos, bool iswrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_igd.c (ffffffff81930d80)
Location: drivers/vfio/pci/vfio_pci_igd.c:164
Inline: False
```
**Symbols:**

```
ffffffff81930d80-ffffffff81930ff0: vfio_pci_igd_cfg_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t vfio_pci_igd_cfg_rw(struct vfio_pci_core_device *vdev, char *buf, size_t count, loff_t *ppos, bool iswrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_igd.c (ffffffff81a87650)
Location: drivers/vfio/pci/vfio_pci_igd.c:281
Inline: False
```
**Symbols:**

```
ffffffff81a87650-ffffffff81a8793e: vfio_pci_igd_cfg_rw (STB_LOCAL)
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
<summary>In <code>azure</code>: ✅</summary>

```c
size_t vfio_pci_igd_cfg_rw(struct vfio_pci_device *vdev, char *buf, size_t count, loff_t *ppos, bool iswrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_igd.c (ffffffff81786330)
Location: drivers/vfio/pci/vfio_pci_igd.c:110
Inline: False
```
**Symbols:**

```
ffffffff81786330-ffffffff81786583: vfio_pci_igd_cfg_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
size_t vfio_pci_igd_cfg_rw(struct vfio_pci_device *vdev, char *buf, size_t count, loff_t *ppos, bool iswrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_igd.c (ffffffff817d1100)
Location: drivers/vfio/pci/vfio_pci_igd.c:110
Inline: False
```
**Symbols:**

```
ffffffff817d1100-ffffffff817d1353: vfio_pci_igd_cfg_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
size_t vfio_pci_igd_cfg_rw(struct vfio_pci_device *vdev, char *buf, size_t count, loff_t *ppos, bool iswrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_igd.c (ffffffff817eb3a0)
Location: drivers/vfio/pci/vfio_pci_igd.c:110
Inline: False
```
**Symbols:**

```
ffffffff817eb3a0-ffffffff817eb5f3: vfio_pci_igd_cfg_rw (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<li>
<b>Return type changed. </b>
<code>size_t</code> ➡️ <code>ssize_t</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
