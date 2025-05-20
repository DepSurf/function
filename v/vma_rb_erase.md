# Function: <code>vma_rb_erase</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void vma_rb_erase(struct vm_area_struct *vma, struct rb_root *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811c46e0)
Location: mm/mmap.c:506
Inline: False
Direct callers:
  - mm/mmap.c:vma_adjust
  - mm/mmap.c:do_munmap
```
**Symbols:**

```
ffffffff811c46e0-ffffffff811c4911: vma_rb_erase (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void vma_rb_erase(struct vm_area_struct *vma, struct rb_root *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811e0630)
Location: mm/mmap.c:398
Inline: False
Direct callers:
  - mm/mmap.c:do_munmap
  - mm/mmap.c:vma_adjust
```
**Symbols:**

```
ffffffff811e0630-ffffffff811e0863: vma_rb_erase (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811f20d8)
Location: mm/mmap.c:429
Inline: True
Inline callers:
  - mm/mmap.c:do_munmap
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811fd0d5)
Location: mm/mmap.c:445
Inline: True
Inline callers:
  - mm/mmap.c:do_munmap
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8121560c)
Location: mm/mmap.c:446
Inline: True
Inline callers:
  - mm/mmap.c:do_munmap
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81236445)
Location: mm/mmap.c:455
Inline: True
Inline callers:
  - mm/mmap.c:do_munmap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81249c69)
Location: mm/mmap.c:479
Inline: True
Inline callers:
  - mm/mmap.c:__do_munmap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8125bf85)
Location: mm/mmap.c:481
Inline: True
Inline callers:
  - mm/mmap.c:__do_munmap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8126a67f)
Location: mm/mmap.c:482
Inline: True
Inline callers:
  - mm/mmap.c:__do_munmap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8129b0b0)
Location: mm/mmap.c:485
Inline: True
Inline callers:
  - mm/mmap.c:__do_munmap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812a6270)
Location: mm/mmap.c:489
Inline: True
Inline callers:
  - mm/mmap.c:__do_munmap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812ab5ce)
Location: mm/mmap.c:493
Inline: True
Inline callers:
  - mm/mmap.c:__do_munmap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812ecc36)
Location: mm/mmap.c:491
Inline: True
Inline callers:
  - mm/mmap.c:__do_munmap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8134ff37)
Location: mm/mmap.c:497
Inline: True
Inline callers:
  - mm/mmap.c:__do_munmap
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
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffff800010301d9c)
Location: mm/mmap.c:482
Inline: True
Inline callers:
  - mm/mmap.c:__do_munmap
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (c05204e8)
Location: mm/mmap.c:482
Inline: True
Inline callers:
  - mm/mmap.c:__do_munmap
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (c0000000003cdfcc)
Location: mm/mmap.c:482
Inline: True
Inline callers:
  - mm/mmap.c:__do_munmap
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffe00020ee92)
Location: mm/mmap.c:482
Inline: True
Inline callers:
  - mm/mmap.c:__do_munmap
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81262ccf)
Location: mm/mmap.c:482
Inline: True
Inline callers:
  - mm/mmap.c:__do_munmap
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812550ef)
Location: mm/mmap.c:482
Inline: True
Inline callers:
  - mm/mmap.c:__do_munmap
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81260a6f)
Location: mm/mmap.c:482
Inline: True
Inline callers:
  - mm/mmap.c:__do_munmap
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8127043f)
Location: mm/mmap.c:482
Inline: True
Inline callers:
  - mm/mmap.c:__do_munmap
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
</ul>
