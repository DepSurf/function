# Function: <code>mlock_future_ok</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool mlock_future_ok(struct mm_struct *mm, long unsigned int flags, long unsigned int bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff813ff9c4)
Location: mm/mmap.c:1136
Inline: True
Inline callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:do_mmap
  - mm/mmap.c:do_mmap
  - mm/mmap.c:check_brk_limits
  - mm/mmap.c:check_brk_limits
Direct callers:
  - mm/mremap.c:vma_to_resize
  - mm/secretmem.c:secretmem_mmap
```
**Symbols:**

```
ffffffff813fc8f0-ffffffff813fc97b: mlock_future_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool mlock_future_ok(struct mm_struct *mm, long unsigned int flags, long unsigned int bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8142bf4e)
Location: mm/mmap.c:1164
Inline: True
Inline callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:do_mmap
  - mm/mmap.c:do_mmap
  - mm/mmap.c:check_brk_limits
  - mm/mmap.c:check_brk_limits
Direct callers:
  - mm/mremap.c:vma_to_resize
  - mm/secretmem.c:secretmem_mmap
```
**Symbols:**

```
ffffffff814292c0-ffffffff8142934b: mlock_future_ok (STB_GLOBAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
