# Function: <code>vfio_unpin_pages</code>

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
int vfio_unpin_pages(struct device *dev, long unsigned int *user_pfn, int npage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817d1120)
Location: drivers/vfio/vfio.c:1981
Inline: False
```
**Symbols:**

```
ffffffff817d1120-ffffffff817d11da: vfio_unpin_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vfio_unpin_pages(struct device *dev, long unsigned int *user_pfn, int npage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8189c0c0)
Location: drivers/vfio/vfio.c:2005
Inline: False
```
**Symbols:**

```
ffffffff8189c0c0-ffffffff8189c1c0: vfio_unpin_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vfio_unpin_pages(struct device *dev, long unsigned int *user_pfn, int npage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff818aacd0)
Location: drivers/vfio/vfio.c:2008
Inline: False
```
**Symbols:**

```
ffffffff818aacd0-ffffffff818aadd0: vfio_unpin_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vfio_unpin_pages(struct device *dev, long unsigned int *user_pfn, int npage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8188e410)
Location: drivers/vfio/vfio.c:1907
Inline: False
```
**Symbols:**

```
ffffffff8188e410-ffffffff8188e50f: vfio_unpin_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int vfio_unpin_pages(struct device *dev, long unsigned int *user_pfn, int npage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff81921a50)
Location: drivers/vfio/vfio.c:2014
Inline: False
```
**Symbols:**

```
ffffffff81921a50-ffffffff81921b4f: vfio_unpin_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vfio_unpin_pages(struct vfio_device *device, long unsigned int *user_pfn, int npage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff81a75eb0)
Location: drivers/vfio/vfio.c:1967
Inline: False
```
**Symbols:**

```
ffffffff81a75eb0-ffffffff81a75f52: vfio_unpin_pages (STB_GLOBAL)
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
int vfio_unpin_pages(struct device *dev, long unsigned int *user_pfn, int npage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (c000000000aaefc0)
Location: drivers/vfio/vfio.c:1981
Inline: False
```
**Symbols:**

```
c000000000aaefc0-c000000000aaf0ec: vfio_unpin_pages (STB_GLOBAL)
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
int vfio_unpin_pages(struct device *dev, long unsigned int *user_pfn, int npage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8177b1d0)
Location: drivers/vfio/vfio.c:1981
Inline: False
```
**Symbols:**

```
ffffffff8177b1d0-ffffffff8177b28a: vfio_unpin_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vfio_unpin_pages(struct device *dev, long unsigned int *user_pfn, int npage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817c5fa0)
Location: drivers/vfio/vfio.c:1981
Inline: False
```
**Symbols:**

```
ffffffff817c5fa0-ffffffff817c605a: vfio_unpin_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vfio_unpin_pages(struct device *dev, long unsigned int *user_pfn, int npage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817e0240)
Location: drivers/vfio/vfio.c:1981
Inline: False
```
**Symbols:**

```
ffffffff817e0240-ffffffff817e02fa: vfio_unpin_pages (STB_GLOBAL)
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
