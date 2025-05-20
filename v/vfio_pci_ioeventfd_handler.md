# Function: <code>vfio_pci_ioeventfd_handler</code>

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
int vfio_pci_ioeventfd_handler(void *opaque, void *unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_rdwr.c (ffffffff817d96c0)
Location: drivers/vfio/pci/vfio_pci_rdwr.c:277
Inline: True
```
**Symbols:**

```
ffffffff817d96c0-ffffffff817d9712: vfio_pci_ioeventfd_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vfio_pci_ioeventfd_handler(void *opaque, void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_rdwr.c (ffffffff818a7160)
Location: drivers/vfio/pci/vfio_pci_rdwr.c:359
Inline: False
```
**Symbols:**

```
ffffffff818a7160-ffffffff818a72b1: vfio_pci_ioeventfd_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vfio_pci_ioeventfd_handler(void *opaque, void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_rdwr.c (ffffffff818b6190)
Location: drivers/vfio/pci/vfio_pci_rdwr.c:384
Inline: False
```
**Symbols:**

```
ffffffff818b6190-ffffffff818b621f: vfio_pci_ioeventfd_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vfio_pci_ioeventfd_handler(void *opaque, void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_rdwr.c (ffffffff81899650)
Location: drivers/vfio/pci/vfio_pci_rdwr.c:384
Inline: False
```
**Symbols:**

```
ffffffff81899650-ffffffff818996df: vfio_pci_ioeventfd_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int vfio_pci_ioeventfd_handler(void *opaque, void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_rdwr.c (0)
Location: drivers/vfio/pci/vfio_pci_rdwr.c:384
Inline: False
```
**Symbols:**

```
ffffffff8192d1e0-ffffffff8192d288: vfio_pci_ioeventfd_handler (STB_LOCAL)
ffffffff81d124d9-ffffffff81d12502: vfio_pci_ioeventfd_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int vfio_pci_ioeventfd_handler(void *opaque, void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_rdwr.c (0)
Location: drivers/vfio/pci/vfio_pci_rdwr.c:386
Inline: False
```
**Symbols:**

```
ffffffff81a83980-ffffffff81a83a2c: vfio_pci_ioeventfd_handler (STB_LOCAL)
ffffffff81edd201-ffffffff81edd22a: vfio_pci_ioeventfd_handler.cold (STB_LOCAL)
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
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int vfio_pci_ioeventfd_handler(void *opaque, void *unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_rdwr.c (c000000000ab9a70)
Location: drivers/vfio/pci/vfio_pci_rdwr.c:277
Inline: True
```
**Symbols:**

```
c000000000ab9a70-c000000000ab9b3c: vfio_pci_ioeventfd_handler (STB_LOCAL)
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
int vfio_pci_ioeventfd_handler(void *opaque, void *unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_rdwr.c (ffffffff81783770)
Location: drivers/vfio/pci/vfio_pci_rdwr.c:277
Inline: True
```
**Symbols:**

```
ffffffff81783770-ffffffff817837c2: vfio_pci_ioeventfd_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int vfio_pci_ioeventfd_handler(void *opaque, void *unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_rdwr.c (ffffffff817ce540)
Location: drivers/vfio/pci/vfio_pci_rdwr.c:277
Inline: True
```
**Symbols:**

```
ffffffff817ce540-ffffffff817ce592: vfio_pci_ioeventfd_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int vfio_pci_ioeventfd_handler(void *opaque, void *unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_rdwr.c (ffffffff817e87e0)
Location: drivers/vfio/pci/vfio_pci_rdwr.c:277
Inline: True
```
**Symbols:**

```
ffffffff817e87e0-ffffffff817e8832: vfio_pci_ioeventfd_handler (STB_LOCAL)
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
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
