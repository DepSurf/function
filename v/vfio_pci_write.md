# Function: <code>vfio_pci_write</code>

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
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
ssize_t vfio_pci_write(void *device_data, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff817d6680)
Location: drivers/vfio/pci/vfio_pci.c:1186
Inline: True
```
**Symbols:**

```
ffffffff817d6680-ffffffff817d669e: vfio_pci_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t vfio_pci_write(void *device_data, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff818a34c0)
Location: drivers/vfio/pci/vfio_pci.c:1371
Inline: True
```
**Symbols:**

```
ffffffff818a34c0-ffffffff818a34de: vfio_pci_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
ssize_t vfio_pci_write(void *device_data, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff818b2170)
Location: drivers/vfio/pci/vfio_pci.c:1448
Inline: True
```
**Symbols:**

```
ffffffff818b2170-ffffffff818b218e: vfio_pci_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
ssize_t vfio_pci_write(struct vfio_device *core_vdev, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff81895630)
Location: drivers/vfio/pci/vfio_pci.c:1425
Inline: True
```
**Symbols:**

```
ffffffff81895630-ffffffff8189564e: vfio_pci_write (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
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
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
ssize_t vfio_pci_write(void *device_data, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (c000000000ab56f0)
Location: drivers/vfio/pci/vfio_pci.c:1186
Inline: True
```
**Symbols:**

```
c000000000ab56f0-c000000000ab5718: vfio_pci_write (STB_LOCAL)
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
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
ssize_t vfio_pci_write(void *device_data, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff81780730)
Location: drivers/vfio/pci/vfio_pci.c:1186
Inline: True
```
**Symbols:**

```
ffffffff81780730-ffffffff8178074e: vfio_pci_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
ssize_t vfio_pci_write(void *device_data, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff817cb500)
Location: drivers/vfio/pci/vfio_pci.c:1186
Inline: True
```
**Symbols:**

```
ffffffff817cb500-ffffffff817cb51e: vfio_pci_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
ssize_t vfio_pci_write(void *device_data, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff817e57a0)
Location: drivers/vfio/pci/vfio_pci.c:1186
Inline: True
```
**Symbols:**

```
ffffffff817e57a0-ffffffff817e57be: vfio_pci_write (STB_LOCAL)
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
<code>struct vfio_device *core_vdev</code>
</li>
<li>
<b>Param removed. </b>
<code>void *device_data</code>
</li>
</ul>
</details>
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
