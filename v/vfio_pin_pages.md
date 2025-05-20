# Function: <code>vfio_pin_pages</code>

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
int vfio_pin_pages(struct device *dev, long unsigned int *user_pfn, int npage, int prot, long unsigned int *phys_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817d1030)
Location: drivers/vfio/vfio.c:1934
Inline: False
```
**Symbols:**

```
ffffffff817d1030-ffffffff817d1111: vfio_pin_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vfio_pin_pages(struct device *dev, long unsigned int *user_pfn, int npage, int prot, long unsigned int *phys_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8189c1c0)
Location: drivers/vfio/vfio.c:1954
Inline: False
```
**Symbols:**

```
ffffffff8189c1c0-ffffffff8189c2e9: vfio_pin_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vfio_pin_pages(struct device *dev, long unsigned int *user_pfn, int npage, int prot, long unsigned int *phys_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff818aadd0)
Location: drivers/vfio/vfio.c:1955
Inline: False
```
**Symbols:**

```
ffffffff818aadd0-ffffffff818aaf00: vfio_pin_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vfio_pin_pages(struct device *dev, long unsigned int *user_pfn, int npage, int prot, long unsigned int *phys_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8188e510)
Location: drivers/vfio/vfio.c:1854
Inline: False
```
**Symbols:**

```
ffffffff8188e510-ffffffff8188e640: vfio_pin_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int vfio_pin_pages(struct device *dev, long unsigned int *user_pfn, int npage, int prot, long unsigned int *phys_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff81921b50)
Location: drivers/vfio/vfio.c:1961
Inline: False
```
**Symbols:**

```
ffffffff81921b50-ffffffff81921c80: vfio_pin_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vfio_pin_pages(struct vfio_device *device, long unsigned int *user_pfn, int npage, int prot, long unsigned int *phys_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff81a75d80)
Location: drivers/vfio/vfio.c:1926
Inline: False
```
**Symbols:**

```
ffffffff81a75d80-ffffffff81a75ea2: vfio_pin_pages (STB_GLOBAL)
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
int vfio_pin_pages(struct device *dev, long unsigned int *user_pfn, int npage, int prot, long unsigned int *phys_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (c000000000aaee40)
Location: drivers/vfio/vfio.c:1934
Inline: False
```
**Symbols:**

```
c000000000aaee40-c000000000aaefc0: vfio_pin_pages (STB_GLOBAL)
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
int vfio_pin_pages(struct device *dev, long unsigned int *user_pfn, int npage, int prot, long unsigned int *phys_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8177b0e0)
Location: drivers/vfio/vfio.c:1934
Inline: False
```
**Symbols:**

```
ffffffff8177b0e0-ffffffff8177b1c1: vfio_pin_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vfio_pin_pages(struct device *dev, long unsigned int *user_pfn, int npage, int prot, long unsigned int *phys_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817c5eb0)
Location: drivers/vfio/vfio.c:1934
Inline: False
```
**Symbols:**

```
ffffffff817c5eb0-ffffffff817c5f91: vfio_pin_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vfio_pin_pages(struct device *dev, long unsigned int *user_pfn, int npage, int prot, long unsigned int *phys_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817e0150)
Location: drivers/vfio/vfio.c:1934
Inline: False
```
**Symbols:**

```
ffffffff817e0150-ffffffff817e0231: vfio_pin_pages (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vfio_device *device</code>
</li>
<li>
<b>Param removed. </b>
<code>struct device *dev</code>
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
