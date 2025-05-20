# Function: <code>radix_to_swp_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811a9106)
Location: include/linux/swapops.h:87
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/mincore.c (ffffffff811c25bb)
Location: include/linux/swapops.h:87
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/madvise.c (0)
Location: include/linux/swapops.h:87
Inline: True
```
```
In mm/memcontrol.c (ffffffff811fa918)
Location: include/linux/swapops.h:87
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811c080f)
Location: include/linux/swapops.h:87
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/mincore.c (ffffffff811de12b)
Location: include/linux/swapops.h:87
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/madvise.c (ffffffff811ef5bd)
Location: include/linux/swapops.h:87
Inline: True
Inline callers:
  - mm/madvise.c:SyS_madvise
```
```
In mm/memcontrol.c (ffffffff8121e832)
Location: include/linux/swapops.h:87
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811d0df8)
Location: include/linux/swapops.h:87
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/mincore.c (0)
Location: include/linux/swapops.h:87
Inline: True
```
```
In mm/madvise.c (ffffffff811fff3d)
Location: include/linux/swapops.h:87
Inline: True
Inline callers:
  - mm/madvise.c:SyS_madvise
```
```
In mm/memcontrol.c (ffffffff81230e62)
Location: include/linux/swapops.h:87
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811d988f)
Location: include/linux/swapops.h:87
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_free_swap
```
```
In mm/mincore.c (0)
Location: include/linux/swapops.h:87
Inline: True
```
```
In mm/madvise.c (ffffffff81209fe3)
Location: include/linux/swapops.h:87
Inline: True
Inline callers:
  - mm/madvise.c:madvise_willneed
```
```
In mm/memcontrol.c (ffffffff8123c6c2)
Location: include/linux/swapops.h:87
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811ef54f)
Location: include/linux/swapops.h:88
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_free_swap
```
```
In mm/mincore.c (0)
Location: include/linux/swapops.h:88
Inline: True
```
```
In mm/madvise.c (ffffffff812231c6)
Location: include/linux/swapops.h:88
Inline: True
Inline callers:
  - mm/madvise.c:madvise_willneed
```
```
In mm/memcontrol.c (ffffffff8125c349)
Location: include/linux/swapops.h:88
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81210bb2)
Location: include/linux/swapops.h:88
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_free_swap
```
```
In mm/mincore.c (ffffffff81231db8)
Location: include/linux/swapops.h:88
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/madvise.c (ffffffff81244d7b)
Location: include/linux/swapops.h:88
Inline: True
Inline callers:
  - mm/madvise.c:madvise_willneed
```
```
In mm/memcontrol.c (ffffffff8127fce9)
Location: include/linux/swapops.h:88
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81222be7)
Location: include/linux/swapops.h:87
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_free_swap
```
```
In mm/mincore.c (ffffffff81245588)
Location: include/linux/swapops.h:87
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/madvise.c (ffffffff812593cb)
Location: include/linux/swapops.h:87
Inline: True
Inline callers:
  - mm/madvise.c:madvise_willneed
```
```
In mm/memcontrol.c (ffffffff81294655)
Location: include/linux/swapops.h:87
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812330bb)
Location: include/linux/swapops.h:87
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_free_swap
```
```
In mm/mincore.c (ffffffff81257625)
Location: include/linux/swapops.h:87
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/madvise.c (ffffffff81274c00)
Location: include/linux/swapops.h:87
Inline: True
Inline callers:
  - mm/madvise.c:madvise_willneed
```
```
In mm/memcontrol.c (ffffffff812b088b)
Location: include/linux/swapops.h:87
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812412db)
Location: include/linux/swapops.h:87
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_free_swap
```
```
In mm/mincore.c (ffffffff81265b75)
Location: include/linux/swapops.h:87
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/madvise.c (ffffffff8128428e)
Location: include/linux/swapops.h:87
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
```
```
In mm/memcontrol.c (ffffffff812c22eb)
Location: include/linux/swapops.h:87
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8126db29)
Location: include/linux/swapops.h:89
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/mincore.c (ffffffff81295eb6)
Location: include/linux/swapops.h:89
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/madvise.c (ffffffff812b61c5)
Location: include/linux/swapops.h:89
Inline: True
Inline callers:
  - mm/madvise.c:madvise_willneed
```
```
In mm/memcontrol.c (ffffffff812f9241)
Location: include/linux/swapops.h:89
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81279869)
Location: include/linux/swapops.h:89
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/madvise.c (ffffffff812c1013)
Location: include/linux/swapops.h:89
Inline: True
Inline callers:
  - mm/madvise.c:force_shm_swapin_readahead
```
```
In mm/swap_state.c (ffffffff812c4eef)
Location: include/linux/swapops.h:89
Inline: True
Inline callers:
  - mm/swap_state.c:find_get_incore_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8127e9c9)
Location: include/linux/swapops.h:96
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/madvise.c (ffffffff812c7e26)
Location: include/linux/swapops.h:96
Inline: True
Inline callers:
  - mm/madvise.c:force_shm_swapin_readahead
```
```
In mm/swap_state.c (ffffffff812cbb96)
Location: include/linux/swapops.h:96
Inline: True
Inline callers:
  - mm/swap_state.c:find_get_incore_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812bc548)
Location: include/linux/swapops.h:96
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/madvise.c (ffffffff8130cbec)
Location: include/linux/swapops.h:96
Inline: True
Inline callers:
  - mm/madvise.c:force_shm_swapin_readahead
```
```
In mm/swap_state.c (ffffffff81310cc1)
Location: include/linux/swapops.h:96
Inline: True
Inline callers:
  - mm/swap_state.c:find_get_incore_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81318594)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/madvise.c (ffffffff81376125)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/madvise.c:force_shm_swapin_readahead
```
```
In mm/swap_state.c (ffffffff8137baf8)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/swap_state.c:find_get_incore_page
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
In mm/shmem.c (ffffffff8138c493)
Location: include/linux/swapops.h:154
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/madvise.c (ffffffff813f3a72)
Location: include/linux/swapops.h:154
Inline: True
Inline callers:
  - mm/madvise.c:force_shm_swapin_readahead
```
```
In mm/swap_state.c (ffffffff813f947c)
Location: include/linux/swapops.h:154
Inline: True
Inline callers:
  - mm/swap_state.c:filemap_get_incore_folio
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
In mm/filemap.c (ffffffff8138ccbe)
Location: include/linux/swapops.h:154
Inline: True
Inline callers:
  - mm/filemap.c:filemap_cachestat
```
```
In mm/shmem.c (ffffffff813bea8c)
Location: include/linux/swapops.h:154
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/madvise.c (ffffffff81427535)
Location: include/linux/swapops.h:154
Inline: True
Inline callers:
  - mm/madvise.c:shmem_swapin_range
```
```
In mm/swap_state.c (ffffffff8142c1eb)
Location: include/linux/swapops.h:154
Inline: True
Inline callers:
  - mm/swap_state.c:filemap_get_incore_folio
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
In mm/filemap.c (ffffffff813b67ba)
Location: include/linux/swapops.h:154
Inline: True
Inline callers:
  - mm/filemap.c:filemap_cachestat
```
```
In mm/shmem.c (ffffffff813e9ab0)
Location: include/linux/swapops.h:154
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/madvise.c (ffffffff81460c19)
Location: include/linux/swapops.h:154
Inline: True
Inline callers:
  - mm/madvise.c:shmem_swapin_range
```
```
In mm/swap_state.c (ffffffff8146594b)
Location: include/linux/swapops.h:154
Inline: True
Inline callers:
  - mm/swap_state.c:filemap_get_incore_folio
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffff8000102d36c8)
Location: include/linux/swapops.h:87
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_free_swap
```
```
In mm/mincore.c (ffff8000102fcd70)
Location: include/linux/swapops.h:87
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/madvise.c (ffff80001031e6bc)
Location: include/linux/swapops.h:87
Inline: True
Inline callers:
  - mm/madvise.c:__arm64_sys_madvise
```
```
In mm/memcontrol.c (ffff800010363dcc)
Location: include/linux/swapops.h:87
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (c04fb950)
Location: include/linux/swapops.h:87
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_free_swap
```
```
In mm/mincore.c (c051c470)
Location: include/linux/swapops.h:87
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/madvise.c (c0538630)
Location: include/linux/swapops.h:87
Inline: True
Inline callers:
  - mm/madvise.c:__se_sys_madvise
```
```
In mm/memcontrol.c (c05560f0)
Location: include/linux/swapops.h:87
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (c00000000039274c)
Location: include/linux/swapops.h:87
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_free_swap
```
```
In mm/mincore.c (c0000000003c7d30)
Location: include/linux/swapops.h:87
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/madvise.c (c0000000003f2920)
Location: include/linux/swapops.h:87
Inline: True
Inline callers:
  - mm/madvise.c:__se_sys_madvise
```
```
In mm/memcontrol.c (c000000000451010)
Location: include/linux/swapops.h:87
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffe0001ef78a)
Location: include/linux/swapops.h:87
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_free_swap
```
```
In mm/mincore.c (ffffffe00020b988)
Location: include/linux/swapops.h:87
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/madvise.c (ffffffe000221598)
Location: include/linux/swapops.h:87
Inline: True
Inline callers:
  - mm/madvise.c:__se_sys_madvise
```
```
In mm/memcontrol.c (ffffffe000241c9c)
Location: include/linux/swapops.h:87
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8123992b)
Location: include/linux/swapops.h:87
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_free_swap
```
```
In mm/mincore.c (ffffffff8125e1c5)
Location: include/linux/swapops.h:87
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/madvise.c (ffffffff8127c8de)
Location: include/linux/swapops.h:87
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
```
```
In mm/memcontrol.c (ffffffff812ba8cb)
Location: include/linux/swapops.h:87
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8122c95b)
Location: include/linux/swapops.h:87
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_free_swap
```
```
In mm/mincore.c (ffffffff81250655)
Location: include/linux/swapops.h:87
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/madvise.c (ffffffff8126e78e)
Location: include/linux/swapops.h:87
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
```
```
In mm/memcontrol.c (ffffffff812aba89)
Location: include/linux/swapops.h:87
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812376cb)
Location: include/linux/swapops.h:87
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_free_swap
```
```
In mm/mincore.c (ffffffff8125bf65)
Location: include/linux/swapops.h:87
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/madvise.c (ffffffff8127a67e)
Location: include/linux/swapops.h:87
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
```
```
In mm/memcontrol.c (ffffffff812b86db)
Location: include/linux/swapops.h:87
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81246c0a)
Location: include/linux/swapops.h:87
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_free_swap
```
```
In mm/mincore.c (ffffffff8126b955)
Location: include/linux/swapops.h:87
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/madvise.c (ffffffff8128a25e)
Location: include/linux/swapops.h:87
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
```
```
In mm/memcontrol.c (ffffffff812c8d1b)
Location: include/linux/swapops.h:87
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
</details>
</li>
</ul>

## Differences
