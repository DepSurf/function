# Function: <code>mas_pause</code>

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
<summary>In <code>6.2</code>: ✅</summary>

```c
void mas_pause(struct ma_state *mas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/maple_tree.c (ffffffff82025890)
Location: lib/maple_tree.c:5976
Inline: False
Direct callers:
  - mm/mlock.c:apply_mlockall_flags
  - mm/mempolicy.c:mbind_range
  - mm/mempolicy.c:mbind_range
  - mm/mempolicy.c:mbind_range
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/proc/task_mmu.c:show_smaps_rollup
  - ipc/shm.c:ksys_shmdt
  - ipc/shm.c:ksys_shmdt
```
**Symbols:**

```
ffffffff82025890-ffffffff8202589f: mas_pause (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mas_pause(struct ma_state *mas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/maple_tree.c (ffffffff820a59e0)
Location: lib/maple_tree.c:5893
Inline: False
Direct callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_expand
  - mm/mmap.c:vma_complete
  - mm/mmap.c:vma_link
  - fs/proc/task_mmu.c:show_smaps_rollup
  - drivers/base/regmap/regcache-maple.c:regcache_maple_sync_block
```
**Symbols:**

```
ffffffff820a59e0-ffffffff820a59ef: mas_pause (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mas_pause(struct ma_state *mas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/maple_tree.c (ffffffff8217dc50)
Location: lib/maple_tree.c:5906
Inline: False
Direct callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_expand
  - mm/mmap.c:vma_complete
  - mm/mmap.c:vma_link
  - fs/proc/task_mmu.c:show_smaps_rollup
  - drivers/base/regmap/regcache-maple.c:regcache_maple_sync_block
```
**Symbols:**

```
ffffffff8217dc50-ffffffff8217dc66: mas_pause (STB_GLOBAL)
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
