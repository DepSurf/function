# Function: <code>vfio_pci_set_req_trigger</code>

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
int vfio_pci_set_req_trigger(struct vfio_pci_device *vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff817d8da0)
Location: drivers/vfio/pci/vfio_pci_intrs.c:611
Inline: False
```
**Symbols:**

```
ffffffff817d8da0-ffffffff817d8de2: vfio_pci_set_req_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vfio_pci_set_req_trigger(struct vfio_pci_device *vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff818a6690)
Location: drivers/vfio/pci/vfio_pci_intrs.c:625
Inline: False
```
**Symbols:**

```
ffffffff818a6690-ffffffff818a66d2: vfio_pci_set_req_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vfio_pci_set_req_trigger(struct vfio_pci_device *vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff818b5580)
Location: drivers/vfio/pci/vfio_pci_intrs.c:627
Inline: False
```
**Symbols:**

```
ffffffff818b5580-ffffffff818b55c2: vfio_pci_set_req_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vfio_pci_set_req_trigger(struct vfio_pci_device *vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff81898a20)
Location: drivers/vfio/pci/vfio_pci_intrs.c:627
Inline: False
```
**Symbols:**

```
ffffffff81898a20-ffffffff81898a62: vfio_pci_set_req_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int vfio_pci_set_req_trigger(struct vfio_pci_core_device *vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff8192c430)
Location: drivers/vfio/pci/vfio_pci_intrs.c:627
Inline: False
```
**Symbols:**

```
ffffffff8192c430-ffffffff8192c472: vfio_pci_set_req_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vfio_pci_set_req_trigger(struct vfio_pci_core_device *vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff81a82200)
Location: drivers/vfio/pci/vfio_pci_intrs.c:627
Inline: False
```
**Symbols:**

```
ffffffff81a82200-ffffffff81a8226c: vfio_pci_set_req_trigger (STB_LOCAL)
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
int vfio_pci_set_req_trigger(struct vfio_pci_device *vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (c000000000ab8b30)
Location: drivers/vfio/pci/vfio_pci_intrs.c:611
Inline: False
```
**Symbols:**

```
c000000000ab8b30-c000000000ab8b78: vfio_pci_set_req_trigger (STB_LOCAL)
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
int vfio_pci_set_req_trigger(struct vfio_pci_device *vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff81782e50)
Location: drivers/vfio/pci/vfio_pci_intrs.c:611
Inline: False
```
**Symbols:**

```
ffffffff81782e50-ffffffff81782e92: vfio_pci_set_req_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vfio_pci_set_req_trigger(struct vfio_pci_device *vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff817cdc20)
Location: drivers/vfio/pci/vfio_pci_intrs.c:611
Inline: False
```
**Symbols:**

```
ffffffff817cdc20-ffffffff817cdc62: vfio_pci_set_req_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vfio_pci_set_req_trigger(struct vfio_pci_device *vdev, unsigned int index, unsigned int start, unsigned int count, uint32_t flags, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff817e7ec0)
Location: drivers/vfio/pci/vfio_pci_intrs.c:611
Inline: False
```
**Symbols:**

```
ffffffff817e7ec0-ffffffff817e7f02: vfio_pci_set_req_trigger (STB_LOCAL)
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
