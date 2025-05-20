# Function: <code>vfio_pci_igd_rw</code>

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
size_t vfio_pci_igd_rw(struct vfio_pci_device *vdev, char *buf, size_t count, loff_t *ppos, bool iswrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_igd.c (ffffffff817dc1a0)
Location: drivers/vfio/pci/vfio_pci_igd.c:24
Inline: False
```
**Symbols:**

```
ffffffff817dc1a0-ffffffff817dc260: vfio_pci_igd_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
size_t vfio_pci_igd_rw(struct vfio_pci_device *vdev, char *buf, size_t count, loff_t *ppos, bool iswrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_igd.c (ffffffff818aa470)
Location: drivers/vfio/pci/vfio_pci_igd.c:24
Inline: False
```
**Symbols:**

```
ffffffff818aa470-ffffffff818aa530: vfio_pci_igd_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
size_t vfio_pci_igd_rw(struct vfio_pci_device *vdev, char *buf, size_t count, loff_t *ppos, bool iswrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_igd.c (ffffffff818b9190)
Location: drivers/vfio/pci/vfio_pci_igd.c:24
Inline: False
```
**Symbols:**

```
ffffffff818b9190-ffffffff818b9250: vfio_pci_igd_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
size_t vfio_pci_igd_rw(struct vfio_pci_device *vdev, char *buf, size_t count, loff_t *ppos, bool iswrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_igd.c (ffffffff8189c680)
Location: drivers/vfio/pci/vfio_pci_igd.c:28
Inline: False
```
**Symbols:**

```
ffffffff8189c680-ffffffff8189c740: vfio_pci_igd_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t vfio_pci_igd_rw(struct vfio_pci_core_device *vdev, char *buf, size_t count, loff_t *ppos, bool iswrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_igd.c (ffffffff81930aa0)
Location: drivers/vfio/pci/vfio_pci_igd.c:28
Inline: False
```
**Symbols:**

```
ffffffff81930aa0-ffffffff81930b57: vfio_pci_igd_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t vfio_pci_igd_rw(struct vfio_pci_core_device *vdev, char *buf, size_t count, loff_t *ppos, bool iswrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_igd.c (ffffffff81a87b40)
Location: drivers/vfio/pci/vfio_pci_igd.c:64
Inline: False
```
**Symbols:**

```
ffffffff81a87b40-ffffffff81a87f2e: vfio_pci_igd_rw (STB_LOCAL)
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
size_t vfio_pci_igd_rw(struct vfio_pci_device *vdev, char *buf, size_t count, loff_t *ppos, bool iswrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_igd.c (ffffffff81786250)
Location: drivers/vfio/pci/vfio_pci_igd.c:24
Inline: False
```
**Symbols:**

```
ffffffff81786250-ffffffff81786310: vfio_pci_igd_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
size_t vfio_pci_igd_rw(struct vfio_pci_device *vdev, char *buf, size_t count, loff_t *ppos, bool iswrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_igd.c (ffffffff817d1020)
Location: drivers/vfio/pci/vfio_pci_igd.c:24
Inline: False
```
**Symbols:**

```
ffffffff817d1020-ffffffff817d10e0: vfio_pci_igd_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
size_t vfio_pci_igd_rw(struct vfio_pci_device *vdev, char *buf, size_t count, loff_t *ppos, bool iswrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_igd.c (ffffffff817eb2c0)
Location: drivers/vfio/pci/vfio_pci_igd.c:24
Inline: False
```
**Symbols:**

```
ffffffff817eb2c0-ffffffff817eb380: vfio_pci_igd_rw (STB_LOCAL)
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
