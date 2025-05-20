# Function: <code>vma_set_file</code>

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
void vma_set_file(struct vm_area_struct *vma, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8127d360)
Location: mm/util.c:317
Inline: False
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
**Symbols:**

```
ffffffff8127d360-ffffffff8127d386: vma_set_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void vma_set_file(struct vm_area_struct *vma, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff812824f0)
Location: mm/util.c:317
Inline: False
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
**Symbols:**

```
ffffffff812824f0-ffffffff81282516: vma_set_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void vma_set_file(struct vm_area_struct *vma, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff812c0600)
Location: mm/util.c:317
Inline: False
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
**Symbols:**

```
ffffffff812c0600-ffffffff812c0626: vma_set_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void vma_set_file(struct vm_area_struct *vma, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8131d0c0)
Location: mm/util.c:318
Inline: False
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
**Symbols:**

```
ffffffff8131d0c0-ffffffff8131d0f0: vma_set_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void vma_set_file(struct vm_area_struct *vma, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff813909f0)
Location: mm/util.c:286
Inline: False
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
**Symbols:**

```
ffffffff813909f0-ffffffff81390a1a: vma_set_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void vma_set_file(struct vm_area_struct *vma, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff813c32f0)
Location: mm/util.c:309
Inline: False
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
**Symbols:**

```
ffffffff813c32f0-ffffffff813c3320: vma_set_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void vma_set_file(struct vm_area_struct *vma, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff813ede10)
Location: mm/util.c:309
Inline: False
Direct callers:
  - fs/backing-file.c:backing_file_mmap
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
**Symbols:**

```
ffffffff813ede10-ffffffff813ede40: vma_set_file (STB_GLOBAL)
```
</details>
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
