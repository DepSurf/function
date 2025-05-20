# Function: <code>vma_do_fput</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void vma_do_fput(struct vm_area_struct *vma, const char *func, int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/prfile.c (ffffffff811ba010)
Location: mm/prfile.c:57
Inline: False
Direct callers:
  - mm/mmap.c:remove_vma
  - mm/mmap.c:vma_adjust
  - mm/mmap.c:mmap_region
  - mm/mmap.c:SyS_remap_file_pages
```
**Symbols:**

```
ffffffff811ba010-ffffffff811ba049: vma_do_fput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void vma_do_fput(struct vm_area_struct *vma, const char *func, int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/prfile.c (ffffffff811d4430)
Location: mm/prfile.c:57
Inline: False
Direct callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:vma_adjust
  - mm/mmap.c:remove_vma
```
**Symbols:**

```
ffffffff811d4430-ffffffff811d4469: vma_do_fput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void vma_do_fput(struct vm_area_struct *vma, const char *func, int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/prfile.c (ffffffff811e4480)
Location: mm/prfile.c:57
Inline: False
Direct callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
```
**Symbols:**

```
ffffffff811e4480-ffffffff811e44b9: vma_do_fput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void vma_do_fput(struct vm_area_struct *vma, const char *func, int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/prfile.c (ffffffff811ee8e0)
Location: mm/prfile.c:56
Inline: False
Direct callers:
  - mm/mmap.c:__split_vma
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
```
**Symbols:**

```
ffffffff811ee8e0-ffffffff811ee919: vma_do_fput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void vma_do_fput(struct vm_area_struct *vma, const char *func, int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/prfile.c (ffffffff81204d50)
Location: mm/prfile.c:57
Inline: False
Direct callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
```
**Symbols:**

```
ffffffff81204d50-ffffffff81204d89: vma_do_fput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void vma_do_fput(struct vm_area_struct *vma, const char *func, int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/prfile.c (ffffffff81225bf0)
Location: mm/prfile.c:57
Inline: False
Direct callers:
  - mm/mmap.c:__split_vma
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
```
**Symbols:**

```
ffffffff81225bf0-ffffffff81225c2e: vma_do_fput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void vma_do_fput(struct vm_area_struct *vma, const char *func, int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/prfile.c (ffffffff812392b0)
Location: mm/prfile.c:57
Inline: False
Direct callers:
  - mm/mmap.c:__split_vma
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
```
**Symbols:**

```
ffffffff812392b0-ffffffff812392ee: vma_do_fput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void vma_do_fput(struct vm_area_struct *vma, const char *func, int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/prfile.c (ffffffff8124a310)
Location: mm/prfile.c:57
Inline: False
Direct callers:
  - mm/mmap.c:__split_vma
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
```
**Symbols:**

```
ffffffff8124a310-ffffffff8124a34e: vma_do_fput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void vma_do_fput(struct vm_area_struct *vma, const char *func, int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/prfile.c (ffffffff81258750)
Location: mm/prfile.c:57
Inline: False
Direct callers:
  - mm/mmap.c:__split_vma
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
```
**Symbols:**

```
ffffffff81258750-ffffffff8125878e: vma_do_fput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void vma_do_fput(struct vm_area_struct *vma, const char *func, int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/prfile.c (ffffffff81286f60)
Location: mm/prfile.c:57
Inline: False
Direct callers:
  - mm/mmap.c:__split_vma
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
```
**Symbols:**

```
ffffffff81286f60-ffffffff81286f9e: vma_do_fput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void vma_do_fput(struct vm_area_struct *vma, const char *func, int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/prfile.c (ffffffff81291280)
Location: mm/prfile.c:57
Inline: False
Direct callers:
  - mm/mmap.c:__split_vma
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
```
**Symbols:**

```
ffffffff81291280-ffffffff812912be: vma_do_fput (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void vma_do_fput(struct vm_area_struct *vma, const char *func, int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/prfile.c (ffffffff812d7000)
Location: mm/prfile.c:57
Inline: False
Direct callers:
  - mm/mmap.c:__split_vma
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
```
**Symbols:**

```
ffffffff812d7000-ffffffff812d703e: vma_do_fput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void vma_do_fput(struct vm_area_struct *vma, const char *func, int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/prfile.c (ffffffff81336870)
Location: mm/prfile.c:57
Inline: False
Direct callers:
  - mm/mmap.c:__split_vma
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
```
**Symbols:**

```
ffffffff81336870-ffffffff813368ba: vma_do_fput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void vma_do_fput(struct vm_area_struct *vma, const char *func, int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/prfile.c (ffffffff813adaf0)
Location: mm/prfile.c:57
Inline: False
Direct callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
```
**Symbols:**

```
ffffffff813adaf0-ffffffff813adb34: vma_do_fput (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void vma_do_fput(struct vm_area_struct *vma, const char *func, int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/prfile.c (ffff8000102f06d0)
Location: mm/prfile.c:57
Inline: False
Direct callers:
  - mm/mmap.c:__split_vma
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
```
**Symbols:**

```
ffff8000102f06d0-ffff8000102f0720: vma_do_fput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void vma_do_fput(struct vm_area_struct *vma, const char *func, int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/prfile.c (c0513c74)
Location: mm/prfile.c:57
Inline: False
Direct callers:
  - mm/mmap.c:__split_vma
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
```
**Symbols:**

```
c0513c74-c0513cac: vma_do_fput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void vma_do_fput(struct vm_area_struct *vma, const char *func, int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/prfile.c (c0000000003b5040)
Location: mm/prfile.c:57
Inline: False
Direct callers:
  - mm/mmap.c:__split_vma
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
```
**Symbols:**

```
c0000000003b5040-c0000000003b50ac: vma_do_fput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void vma_do_fput(struct vm_area_struct *vma, const char *func, int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/prfile.c (ffffffe000203f2c)
Location: mm/prfile.c:57
Inline: False
Direct callers:
  - mm/mmap.c:__split_vma
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
```
**Symbols:**

```
ffffffe000203f2c-ffffffe000203f70: vma_do_fput (STB_GLOBAL)
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
void vma_do_fput(struct vm_area_struct *vma, const char *func, int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/prfile.c (ffffffff81250da0)
Location: mm/prfile.c:57
Inline: False
Direct callers:
  - mm/mmap.c:__split_vma
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
```
**Symbols:**

```
ffffffff81250da0-ffffffff81250dde: vma_do_fput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void vma_do_fput(struct vm_area_struct *vma, const char *func, int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/prfile.c (ffffffff81243ce0)
Location: mm/prfile.c:57
Inline: False
Direct callers:
  - mm/mmap.c:__split_vma
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
```
**Symbols:**

```
ffffffff81243ce0-ffffffff81243d1e: vma_do_fput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void vma_do_fput(struct vm_area_struct *vma, const char *func, int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/prfile.c (ffffffff8124eb40)
Location: mm/prfile.c:57
Inline: False
Direct callers:
  - mm/mmap.c:__split_vma
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
```
**Symbols:**

```
ffffffff8124eb40-ffffffff8124eb7e: vma_do_fput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void vma_do_fput(struct vm_area_struct *vma, const char *func, int line);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/prfile.c (ffffffff8125e4c0)
Location: mm/prfile.c:57
Inline: False
Direct callers:
  - mm/mmap.c:__split_vma
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:remove_vma
```
**Symbols:**

```
ffffffff8125e4c0-ffffffff8125e4fe: vma_do_fput (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
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
