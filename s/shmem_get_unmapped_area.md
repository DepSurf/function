# Function: <code>shmem_get_unmapped_area</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int shmem_get_unmapped_area(struct file *file, long unsigned int uaddr, long unsigned int len, long unsigned int pgoff, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811be250)
Location: mm/shmem.c:1937
Inline: True
```
**Symbols:**

```
ffffffff811be250-ffffffff811be4e5: shmem_get_unmapped_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
long unsigned int shmem_get_unmapped_area(struct file *file, long unsigned int uaddr, long unsigned int len, long unsigned int pgoff, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811ce820)
Location: mm/shmem.c:1974
Inline: True
```
**Symbols:**

```
ffffffff811ce820-ffffffff811cea7d: shmem_get_unmapped_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int shmem_get_unmapped_area(struct file *file, long unsigned int uaddr, long unsigned int len, long unsigned int pgoff, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811d61f0)
Location: mm/shmem.c:2011
Inline: False
```
**Symbols:**

```
ffffffff811d61f0-ffffffff811d643b: shmem_get_unmapped_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int shmem_get_unmapped_area(struct file *file, long unsigned int uaddr, long unsigned int len, long unsigned int pgoff, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811eb710)
Location: mm/shmem.c:2022
Inline: False
```
**Symbols:**

```
ffffffff811eb710-ffffffff811eb95b: shmem_get_unmapped_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int shmem_get_unmapped_area(struct file *file, long unsigned int uaddr, long unsigned int len, long unsigned int pgoff, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8120ce00)
Location: mm/shmem.c:2041
Inline: False
```
**Symbols:**

```
ffffffff8120ce00-ffffffff8120d059: shmem_get_unmapped_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int shmem_get_unmapped_area(struct file *file, long unsigned int uaddr, long unsigned int len, long unsigned int pgoff, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8121fc70)
Location: mm/shmem.c:2003
Inline: False
```
**Symbols:**

```
ffffffff8121fc70-ffffffff8121fec9: shmem_get_unmapped_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int shmem_get_unmapped_area(struct file *file, long unsigned int uaddr, long unsigned int len, long unsigned int pgoff, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8122f4b0)
Location: mm/shmem.c:2065
Inline: False
```
**Symbols:**

```
ffffffff8122f4b0-ffffffff8122f709: shmem_get_unmapped_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int shmem_get_unmapped_area(struct file *file, long unsigned int uaddr, long unsigned int len, long unsigned int pgoff, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8123d640)
Location: mm/shmem.c:2081
Inline: False
```
**Symbols:**

```
ffffffff8123d640-ffffffff8123d898: shmem_get_unmapped_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int shmem_get_unmapped_area(struct file *file, long unsigned int uaddr, long unsigned int len, long unsigned int pgoff, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8126bbd0)
Location: mm/shmem.c:2059
Inline: False
```
**Symbols:**

```
ffffffff8126bbd0-ffffffff8126bea2: shmem_get_unmapped_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int shmem_get_unmapped_area(struct file *file, long unsigned int uaddr, long unsigned int len, long unsigned int pgoff, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81276620)
Location: mm/shmem.c:2121
Inline: False
```
**Symbols:**

```
ffffffff81276620-ffffffff812768f2: shmem_get_unmapped_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int shmem_get_unmapped_area(struct file *file, long unsigned int uaddr, long unsigned int len, long unsigned int pgoff, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8127b9f0)
Location: mm/shmem.c:2123
Inline: False
```
**Symbols:**

```
ffffffff8127b9f0-ffffffff8127bc67: shmem_get_unmapped_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int shmem_get_unmapped_area(struct file *file, long unsigned int uaddr, long unsigned int len, long unsigned int pgoff, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812b9b60)
Location: mm/shmem.c:2125
Inline: False
```
**Symbols:**

```
ffffffff812b9b60-ffffffff812b9dd7: shmem_get_unmapped_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int shmem_get_unmapped_area(struct file *file, long unsigned int uaddr, long unsigned int len, long unsigned int pgoff, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff813146b0)
Location: mm/shmem.c:2124
Inline: False
```
**Symbols:**

```
ffffffff813146b0-ffffffff8131494d: shmem_get_unmapped_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int shmem_get_unmapped_area(struct file *file, long unsigned int uaddr, long unsigned int len, long unsigned int pgoff, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8138b830)
Location: mm/shmem.c:2144
Inline: False
```
**Symbols:**

```
ffffffff8138b830-ffffffff8138babf: shmem_get_unmapped_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int shmem_get_unmapped_area(struct file *file, long unsigned int uaddr, long unsigned int len, long unsigned int pgoff, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff813bdc60)
Location: mm/shmem.c:2174
Inline: False
```
**Symbols:**

```
ffffffff813bdc60-ffffffff813bdef2: shmem_get_unmapped_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int shmem_get_unmapped_area(struct file *file, long unsigned int uaddr, long unsigned int len, long unsigned int pgoff, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff813e8830)
Location: mm/shmem.c:2239
Inline: False
```
**Symbols:**

```
ffffffff813e8830-ffffffff813e8ac2: shmem_get_unmapped_area (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
long unsigned int shmem_get_unmapped_area(struct file *file, long unsigned int uaddr, long unsigned int len, long unsigned int pgoff, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffff8000102cf050)
Location: mm/shmem.c:2081
Inline: False
```
**Symbols:**

```
ffff8000102cf050-ffff8000102cf258: shmem_get_unmapped_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
long unsigned int shmem_get_unmapped_area(struct file *file, long unsigned int uaddr, long unsigned int len, long unsigned int pgoff, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (c04fa13c)
Location: mm/shmem.c:2081
Inline: True
```
**Symbols:**

```
c04fa13c-c04fa18c: shmem_get_unmapped_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int shmem_get_unmapped_area(struct file *file, long unsigned int uaddr, long unsigned int len, long unsigned int pgoff, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (c00000000038c900)
Location: mm/shmem.c:2081
Inline: False
```
**Symbols:**

```
c00000000038c900-c00000000038cbf8: shmem_get_unmapped_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
long unsigned int shmem_get_unmapped_area(struct file *file, long unsigned int uaddr, long unsigned int len, long unsigned int pgoff, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffe0001ed76a)
Location: mm/shmem.c:2081
Inline: True
```
**Symbols:**

```
ffffffe0001ed76a-ffffffe0001ed7be: shmem_get_unmapped_area (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
long unsigned int shmem_get_unmapped_area(struct file *file, long unsigned int uaddr, long unsigned int len, long unsigned int pgoff, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81235c90)
Location: mm/shmem.c:2081
Inline: False
```
**Symbols:**

```
ffffffff81235c90-ffffffff81235ee8: shmem_get_unmapped_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int shmem_get_unmapped_area(struct file *file, long unsigned int uaddr, long unsigned int len, long unsigned int pgoff, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81228cf0)
Location: mm/shmem.c:2081
Inline: False
```
**Symbols:**

```
ffffffff81228cf0-ffffffff81228f48: shmem_get_unmapped_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int shmem_get_unmapped_area(struct file *file, long unsigned int uaddr, long unsigned int len, long unsigned int pgoff, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81233a30)
Location: mm/shmem.c:2081
Inline: False
```
**Symbols:**

```
ffffffff81233a30-ffffffff81233c88: shmem_get_unmapped_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int shmem_get_unmapped_area(struct file *file, long unsigned int uaddr, long unsigned int len, long unsigned int pgoff, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81243000)
Location: mm/shmem.c:2081
Inline: False
```
**Symbols:**

```
ffffffff81243000-ffffffff81243258: shmem_get_unmapped_area (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
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
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
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
