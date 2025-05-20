# Function: <code>vma_compute_subtree_gap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811c3ee1)
Location: mm/mmap.c:356
Inline: True
Inline callers:
  - mm/mmap.c:vma_gap_callbacks_rotate
  - mm/mmap.c:vma_rb_erase
  - mm/mmap.c:vma_rb_erase
  - mm/mmap.c:__vma_link_rb
  - mm/mmap.c:__vma_link_rb
  - mm/mmap.c:vma_adjust
  - mm/mmap.c:vma_adjust
  - mm/mmap.c:vma_adjust
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:do_munmap
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811e2271)
Location: mm/mmap.c:245
Inline: True
Inline callers:
  - mm/mmap.c:do_munmap
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:vma_adjust
  - mm/mmap.c:vma_adjust
  - mm/mmap.c:vma_adjust
  - mm/mmap.c:__vma_link_rb
  - mm/mmap.c:__vma_link_rb
  - mm/mmap.c:vma_rb_erase
  - mm/mmap.c:vma_rb_erase
  - mm/mmap.c:vma_gap_callbacks_rotate
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
In mm/mmap.c (ffffffff811f2241)
Location: mm/mmap.c:252
Inline: True
Inline callers:
  - mm/mmap.c:do_munmap
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_link_rb
  - mm/mmap.c:__vma_link_rb
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:vma_gap_callbacks_rotate
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int vma_compute_subtree_gap(struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811fab60)
Location: mm/mmap.c:256
Inline: False
Direct callers:
  - mm/mmap.c:do_munmap
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_link_rb
  - mm/mmap.c:__vma_link_rb
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:vma_gap_callbacks_rotate
```
**Symbols:**

```
ffffffff811fab60-ffffffff811fabd7: vma_compute_subtree_gap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int vma_compute_subtree_gap(struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81213070)
Location: mm/mmap.c:257
Inline: False
Direct callers:
  - mm/mmap.c:do_munmap
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_link_rb
  - mm/mmap.c:__vma_link_rb
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:vma_gap_callbacks_rotate
```
**Symbols:**

```
ffffffff81213070-ffffffff812130e7: vma_compute_subtree_gap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int vma_compute_subtree_gap(struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81234010)
Location: mm/mmap.c:266
Inline: False
Direct callers:
  - mm/mmap.c:do_munmap
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_link_rb
  - mm/mmap.c:__vma_link_rb
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:vma_gap_callbacks_rotate
```
**Symbols:**

```
ffffffff81234010-ffffffff81234087: vma_compute_subtree_gap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int vma_compute_subtree_gap(struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812477c0)
Location: mm/mmap.c:290
Inline: False
Direct callers:
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_link_rb
  - mm/mmap.c:__vma_link_rb
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:vma_gap_callbacks_rotate
```
**Symbols:**

```
ffffffff812477c0-ffffffff81247837: vma_compute_subtree_gap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int vma_compute_subtree_gap(struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812599d0)
Location: mm/mmap.c:292
Inline: False
Direct callers:
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_link_rb
  - mm/mmap.c:__vma_link_rb
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:vma_gap_callbacks_rotate
```
**Symbols:**

```
ffffffff812599d0-ffffffff81259a47: vma_compute_subtree_gap (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
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
</ul>
