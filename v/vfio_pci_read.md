# Function: <code>vfio_pci_read</code>

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
ssize_t vfio_pci_read(void *device_data, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff817d66a0)
Location: drivers/vfio/pci/vfio_pci.c:1177
Inline: True
```
**Symbols:**

```
ffffffff817d66a0-ffffffff817d66bb: vfio_pci_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t vfio_pci_read(void *device_data, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff818a34e0)
Location: drivers/vfio/pci/vfio_pci.c:1362
Inline: True
```
**Symbols:**

```
ffffffff818a34e0-ffffffff818a34fb: vfio_pci_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
ssize_t vfio_pci_read(void *device_data, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff818b2190)
Location: drivers/vfio/pci/vfio_pci.c:1439
Inline: True
```
**Symbols:**

```
ffffffff818b2190-ffffffff818b21ab: vfio_pci_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
ssize_t vfio_pci_read(struct vfio_device *core_vdev, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff81895650)
Location: drivers/vfio/pci/vfio_pci.c:1413
Inline: True
```
**Symbols:**

```
ffffffff81895650-ffffffff8189566b: vfio_pci_read (STB_LOCAL)
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
ssize_t vfio_pci_read(void *device_data, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (c000000000ab5720)
Location: drivers/vfio/pci/vfio_pci.c:1177
Inline: True
```
**Symbols:**

```
c000000000ab5720-c000000000ab5748: vfio_pci_read (STB_LOCAL)
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
ssize_t vfio_pci_read(void *device_data, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff81780750)
Location: drivers/vfio/pci/vfio_pci.c:1177
Inline: True
```
**Symbols:**

```
ffffffff81780750-ffffffff8178076b: vfio_pci_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
ssize_t vfio_pci_read(void *device_data, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff817cb520)
Location: drivers/vfio/pci/vfio_pci.c:1177
Inline: True
```
**Symbols:**

```
ffffffff817cb520-ffffffff817cb53b: vfio_pci_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
ssize_t vfio_pci_read(void *device_data, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff817e57c0)
Location: drivers/vfio/pci/vfio_pci.c:1177
Inline: True
```
**Symbols:**

```
ffffffff817e57c0-ffffffff817e57db: vfio_pci_read (STB_LOCAL)
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
