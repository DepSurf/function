# Function: <code>anon_vma_name_put</code>

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
In kernel/fork.c (ffffffff810c8f51)
Location: include/linux/mm_inline.h:165
Inline: True
Inline callers:
  - kernel/fork.c:vm_area_free
```
```
In kernel/sys.c (ffffffff810e9f30)
Location: include/linux/mm_inline.h:165
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_vma
```
```
In mm/madvise.c (ffffffff81378339)
Location: include/linux/mm_inline.h:165
Inline: True
Inline callers:
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_update_vma
  - mm/madvise.c:madvise_update_vma
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
In kernel/fork.c (ffffffff810e6414)
Location: include/linux/mm_inline.h:383
Inline: True
Inline callers:
  - kernel/fork.c:vm_area_free
```
```
In kernel/sys.c (ffffffff8110a740)
Location: include/linux/mm_inline.h:383
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_vma
```
```
In mm/madvise.c (ffffffff813f5dd0)
Location: include/linux/mm_inline.h:383
Inline: True
Inline callers:
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_update_vma
  - mm/madvise.c:madvise_update_vma
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
In kernel/fork.c (ffffffff810f1d10)
Location: include/linux/mm_inline.h:371
Inline: True
Inline callers:
  - kernel/fork.c:__vm_area_free
```
```
In kernel/sys.c (ffffffff811177cb)
Location: include/linux/mm_inline.h:371
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_vma
```
```
In mm/madvise.c (ffffffff81428a0e)
Location: include/linux/mm_inline.h:371
Inline: True
Inline callers:
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_update_vma
  - mm/madvise.c:madvise_update_vma
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
In kernel/fork.c (ffffffff810fb990)
Location: include/linux/mm_inline.h:368
Inline: True
Inline callers:
  - kernel/fork.c:__vm_area_free
```
```
In kernel/sys.c (ffffffff811211bb)
Location: include/linux/mm_inline.h:368
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_vma
```
```
In mm/madvise.c (ffffffff8146223e)
Location: include/linux/mm_inline.h:368
Inline: True
Inline callers:
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_update_vma
  - mm/madvise.c:madvise_update_vma
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
