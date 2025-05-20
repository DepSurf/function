# Function: <code>can_vma_merge_after</code>

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
In mm/mmap.c (ffffffff811c5782)
Location: mm/mmap.c:996
Inline: True
Inline callers:
  - mm/mmap.c:vma_merge
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
In mm/mmap.c (ffffffff811e15f4)
Location: mm/mmap.c:898
Inline: True
Inline callers:
  - mm/mmap.c:vma_merge
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
In mm/mmap.c (ffffffff811f15bd)
Location: mm/mmap.c:1027
Inline: True
Inline callers:
  - mm/mmap.c:vma_merge
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
In mm/mmap.c (ffffffff811fc187)
Location: mm/mmap.c:1043
Inline: True
Inline callers:
  - mm/mmap.c:vma_merge
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
In mm/mmap.c (ffffffff812146c7)
Location: mm/mmap.c:1044
Inline: True
Inline callers:
  - mm/mmap.c:vma_merge
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
In mm/mmap.c (ffffffff812355e0)
Location: mm/mmap.c:1053
Inline: True
Inline callers:
  - mm/mmap.c:vma_merge
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
In mm/mmap.c (ffffffff81248d40)
Location: mm/mmap.c:1077
Inline: True
Inline callers:
  - mm/mmap.c:vma_merge
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
In mm/mmap.c (ffffffff8125aff3)
Location: mm/mmap.c:1079
Inline: True
Inline callers:
  - mm/mmap.c:vma_merge
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
In mm/mmap.c (ffffffff812696f3)
Location: mm/mmap.c:1080
Inline: True
Inline callers:
  - mm/mmap.c:vma_merge
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
In mm/mmap.c (ffffffff81299fc5)
Location: mm/mmap.c:1058
Inline: True
Inline callers:
  - mm/mmap.c:vma_merge
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
In mm/mmap.c (ffffffff812a51f2)
Location: mm/mmap.c:1099
Inline: True
Inline callers:
  - mm/mmap.c:vma_merge
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
In mm/mmap.c (ffffffff812aa95a)
Location: mm/mmap.c:1103
Inline: True
Inline callers:
  - mm/mmap.c:vma_merge
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
In mm/mmap.c (ffffffff812ebf7a)
Location: mm/mmap.c:1100
Inline: True
Inline callers:
  - mm/mmap.c:vma_merge
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
In mm/mmap.c (ffffffff8134ee1e)
Location: mm/mmap.c:1110
Inline: True
Inline callers:
  - mm/mmap.c:vma_merge
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int can_vma_merge_after(struct vm_area_struct *vma, long unsigned int vm_flags, struct anon_vma *anon_vma, struct file *file, long unsigned int vm_pgoff, struct vm_userfaultfd_ctx vm_userfaultfd_ctx, struct anon_vma_name *anon_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff813c6750)
Location: mm/mmap.c:940
Inline: False
Direct callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
```
**Symbols:**

```
ffffffff813c6750-ffffffff813c686b: can_vma_merge_after (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool can_vma_merge_after(struct vm_area_struct *vma, long unsigned int vm_flags, struct anon_vma *anon_vma, struct file *file, long unsigned int vm_pgoff, struct vm_userfaultfd_ctx vm_userfaultfd_ctx, struct anon_vma_name *anon_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff813fa9c0)
Location: mm/mmap.c:804
Inline: False
Direct callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:vma_merge
```
**Symbols:**

```
ffffffff813fa9c0-ffffffff813faac7: can_vma_merge_after (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool can_vma_merge_after(struct vm_area_struct *vma, long unsigned int vm_flags, struct anon_vma *anon_vma, struct file *file, long unsigned int vm_pgoff, struct vm_userfaultfd_ctx vm_userfaultfd_ctx, struct anon_vma_name *anon_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81426780)
Location: mm/mmap.c:796
Inline: False
Direct callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:mmap_region
  - mm/mmap.c:vma_merge
```
**Symbols:**

```
ffffffff81426780-ffffffff81426887: can_vma_merge_after (STB_LOCAL)
```
</details>
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
In mm/mmap.c (ffff800010300ba0)
Location: mm/mmap.c:1080
Inline: True
Inline callers:
  - mm/mmap.c:vma_merge
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
In mm/mmap.c (c051f6e8)
Location: mm/mmap.c:1080
Inline: True
Inline callers:
  - mm/mmap.c:vma_merge
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
In mm/mmap.c (c0000000003cce34)
Location: mm/mmap.c:1080
Inline: True
Inline callers:
  - mm/mmap.c:vma_merge
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
In mm/mmap.c (ffffffe00020e20e)
Location: mm/mmap.c:1080
Inline: True
Inline callers:
  - mm/mmap.c:vma_merge
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
In mm/mmap.c (ffffffff81261d43)
Location: mm/mmap.c:1080
Inline: True
Inline callers:
  - mm/mmap.c:vma_merge
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
In mm/mmap.c (ffffffff81254163)
Location: mm/mmap.c:1080
Inline: True
Inline callers:
  - mm/mmap.c:vma_merge
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
In mm/mmap.c (ffffffff8125fae3)
Location: mm/mmap.c:1080
Inline: True
Inline callers:
  - mm/mmap.c:vma_merge
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
In mm/mmap.c (ffffffff8126f4b3)
Location: mm/mmap.c:1080
Inline: True
Inline callers:
  - mm/mmap.c:vma_merge
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
