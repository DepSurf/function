# Function: <code>vfio_pci_ioeventfd_thread</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void vfio_pci_ioeventfd_thread(void *opaque, void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_rdwr.c (ffffffff818b6170)
Location: drivers/vfio/pci/vfio_pci_rdwr.c:406
Inline: False
```
**Symbols:**

```
ffffffff818b6170-ffffffff818b6184: vfio_pci_ioeventfd_thread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void vfio_pci_ioeventfd_thread(void *opaque, void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_rdwr.c (ffffffff81899630)
Location: drivers/vfio/pci/vfio_pci_rdwr.c:406
Inline: False
```
**Symbols:**

```
ffffffff81899630-ffffffff81899644: vfio_pci_ioeventfd_thread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void vfio_pci_ioeventfd_thread(void *opaque, void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_rdwr.c (0)
Location: drivers/vfio/pci/vfio_pci_rdwr.c:406
Inline: False
```
**Symbols:**

```
ffffffff8192d1b0-ffffffff8192d1de: vfio_pci_ioeventfd_thread (STB_LOCAL)
ffffffff81d124c5-ffffffff81d124d9: vfio_pci_ioeventfd_thread.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void vfio_pci_ioeventfd_thread(void *opaque, void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_rdwr.c (0)
Location: drivers/vfio/pci/vfio_pci_rdwr.c:408
Inline: False
```
**Symbols:**

```
ffffffff81a83940-ffffffff81a83976: vfio_pci_ioeventfd_thread (STB_LOCAL)
ffffffff81edd1ed-ffffffff81edd201: vfio_pci_ioeventfd_thread.cold (STB_LOCAL)
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
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
