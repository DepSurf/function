# Function: <code>mas_walk</code>

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
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void *mas_walk(struct ma_state *mas);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/maple_tree.c (ffffffff8202a9f0)
Location: lib/maple_tree.c:5041
Inline: True
Direct callers:
  - mm/mlock.c:apply_vma_lock_flags
  - mm/mmap.c:do_mas_align_munmap
  - mm/mmap.c:find_vma_prev
  - mm/mmap.c:find_mergeable_anon_vma
  - lib/maple_tree.c:mas_find_rev
  - lib/maple_tree.c:mas_find
  - lib/maple_tree.c:mt_prev
  - lib/maple_tree.c:mt_next
```
**Symbols:**

```
ffffffff8202a9f0-ffffffff8202ad1d: mas_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *mas_walk(struct ma_state *mas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/maple_tree.c (ffffffff820a9550)
Location: lib/maple_tree.c:4981
Inline: False
Direct callers:
  - mm/memory.c:lock_vma_under_rcu
  - mm/mlock.c:apply_vma_lock_flags
  - mm/mmap.c:do_vmi_align_munmap
  - mm/mmap.c:do_vmi_align_munmap
  - mm/mmap.c:find_vma_prev
  - mm/mmap.c:find_mergeable_anon_vma
  - drivers/base/regmap/regcache-maple.c:regcache_maple_write
  - drivers/base/regmap/regcache-maple.c:regcache_maple_read
```
**Symbols:**

```
ffffffff820a9550-ffffffff820a96b1: mas_walk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *mas_walk(struct ma_state *mas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/maple_tree.c (ffffffff821833d0)
Location: lib/maple_tree.c:4854
Inline: False
Direct callers:
  - mm/memory.c:lock_vma_under_rcu
  - mm/mlock.c:apply_vma_lock_flags
  - mm/mmap.c:find_vma_prev
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:vma_merge
  - drivers/base/regmap/regcache-maple.c:regcache_maple_write
  - drivers/base/regmap/regcache-maple.c:regcache_maple_read
  - lib/maple_tree.c:mas_find_range
  - lib/maple_tree.c:mas_find_range
  - lib/maple_tree.c:mas_find_range
  - lib/maple_tree.c:mas_find
  - lib/maple_tree.c:mas_find
  - lib/maple_tree.c:mas_find
  - lib/maple_tree.c:mt_prev
  - lib/maple_tree.c:mt_next
```
**Symbols:**

```
ffffffff821833d0-ffffffff821837bb: mas_walk (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
