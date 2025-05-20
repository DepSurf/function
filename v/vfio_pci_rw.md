# Function: <code>vfio_pci_rw</code>

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
ssize_t vfio_pci_rw(void *device_data, char *buf, size_t count, loff_t *ppos, bool iswrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff817d6300)
Location: drivers/vfio/pci/vfio_pci.c:1145
Inline: False
```
**Symbols:**

```
ffffffff817d6300-ffffffff817d639b: vfio_pci_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t vfio_pci_rw(void *device_data, char *buf, size_t count, loff_t *ppos, bool iswrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff818a3270)
Location: drivers/vfio/pci/vfio_pci.c:1330
Inline: False
```
**Symbols:**

```
ffffffff818a3270-ffffffff818a3315: vfio_pci_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t vfio_pci_rw(void *device_data, char *buf, size_t count, loff_t *ppos, bool iswrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff818b1f20)
Location: drivers/vfio/pci/vfio_pci.c:1407
Inline: False
```
**Symbols:**

```
ffffffff818b1f20-ffffffff818b1fc5: vfio_pci_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t vfio_pci_rw(struct vfio_pci_device *vdev, char *buf, size_t count, loff_t *ppos, bool iswrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff81895350)
Location: drivers/vfio/pci/vfio_pci.c:1382
Inline: False
```
**Symbols:**

```
ffffffff81895350-ffffffff818953f5: vfio_pci_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t vfio_pci_rw(struct vfio_pci_core_device *vdev, char *buf, size_t count, loff_t *ppos, bool iswrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_core.c (ffffffff81928a00)
Location: drivers/vfio/pci/vfio_pci_core.c:1182
Inline: False
```
**Symbols:**

```
ffffffff81928a00-ffffffff81928aa5: vfio_pci_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t vfio_pci_rw(struct vfio_pci_core_device *vdev, char *buf, size_t count, loff_t *ppos, bool iswrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_core.c (ffffffff81a7e8e0)
Location: drivers/vfio/pci/vfio_pci_core.c:1212
Inline: False
```
**Symbols:**

```
ffffffff81a7e8e0-ffffffff81a7ea1d: vfio_pci_rw (STB_LOCAL)
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
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t vfio_pci_rw(void *device_data, char *buf, size_t count, loff_t *ppos, bool iswrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (c000000000ab50b0)
Location: drivers/vfio/pci/vfio_pci.c:1145
Inline: False
```
**Symbols:**

```
c000000000ab50b0-c000000000ab5208: vfio_pci_rw (STB_LOCAL)
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
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t vfio_pci_rw(void *device_data, char *buf, size_t count, loff_t *ppos, bool iswrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff817803b0)
Location: drivers/vfio/pci/vfio_pci.c:1145
Inline: False
```
**Symbols:**

```
ffffffff817803b0-ffffffff8178044b: vfio_pci_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t vfio_pci_rw(void *device_data, char *buf, size_t count, loff_t *ppos, bool iswrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff817cb180)
Location: drivers/vfio/pci/vfio_pci.c:1145
Inline: False
```
**Symbols:**

```
ffffffff817cb180-ffffffff817cb21b: vfio_pci_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t vfio_pci_rw(void *device_data, char *buf, size_t count, loff_t *ppos, bool iswrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff817e5420)
Location: drivers/vfio/pci/vfio_pci.c:1145
Inline: False
```
**Symbols:**

```
ffffffff817e5420-ffffffff817e54bb: vfio_pci_rw (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vfio_pci_device *vdev</code>
</li>
<li>
<b>Param removed. </b>
<code>void *device_data</code>
</li>
</ul>
</details>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
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
