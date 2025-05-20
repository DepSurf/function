# Function: <code>anon_vma_name_reuse</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810c8ebf)
Location: include/linux/mm_inline.h:172
Inline: True
Inline callers:
  - kernel/fork.c:vm_area_dup
```
```
In mm/madvise.c (ffffffff813780ba)
Location: include/linux/mm_inline.h:172
Inline: True
Inline callers:
  - mm/madvise.c:madvise_update_vma
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810e636c)
Location: include/linux/mm_inline.h:390
Inline: True
Inline callers:
  - kernel/fork.c:vm_area_dup
```
```
In mm/madvise.c (ffffffff813f59c8)
Location: include/linux/mm_inline.h:390
Inline: True
Inline callers:
  - mm/madvise.c:madvise_update_vma
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810f1c3d)
Location: include/linux/mm_inline.h:378
Inline: True
Inline callers:
  - kernel/fork.c:vm_area_dup
```
```
In mm/madvise.c (ffffffff81428758)
Location: include/linux/mm_inline.h:378
Inline: True
Inline callers:
  - mm/madvise.c:madvise_update_vma
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810fafcd)
Location: include/linux/mm_inline.h:375
Inline: True
Inline callers:
  - kernel/fork.c:vm_area_dup
```
```
In mm/madvise.c (ffffffff81462002)
Location: include/linux/mm_inline.h:375
Inline: True
Inline callers:
  - mm/madvise.c:madvise_update_vma
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
