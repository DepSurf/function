# Function: <code>mapping_cap_account_dirty</code>

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
In mm/filemap.c (ffffffff8118e0c2)
Location: include/linux/backing-dev.h:231
Inline: True
Inline callers:
  - mm/filemap.c:pagecache_get_page
```
```
In mm/page-writeback.c (ffffffff81198cb1)
Location: include/linux/backing-dev.h:231
Inline: True
Inline callers:
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:cancel_dirty_page
```
```
In mm/mmap.c (ffffffff811c5cfd)
Location: include/linux/backing-dev.h:231
Inline: True
```
```
In mm/migrate.c (ffffffff811f18eb)
Location: include/linux/backing-dev.h:231
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memcontrol.c (ffffffff811fd349)
Location: include/linux/backing-dev.h:231
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
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
In mm/filemap.c (ffffffff811a11c1)
Location: include/linux/backing-dev.h:232
Inline: True
Inline callers:
  - mm/filemap.c:pagecache_get_page
```
```
In mm/page-writeback.c (ffffffff811af57e)
Location: include/linux/backing-dev.h:232
Inline: True
Inline callers:
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/mmap.c (ffffffff811e1b1e)
Location: include/linux/backing-dev.h:232
Inline: True
```
```
In mm/migrate.c (ffffffff81210f41)
Location: include/linux/backing-dev.h:232
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memcontrol.c (ffffffff81220f09)
Location: include/linux/backing-dev.h:232
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
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
In mm/filemap.c (ffffffff811b0dc1)
Location: include/linux/backing-dev.h:232
Inline: True
Inline callers:
  - mm/filemap.c:pagecache_get_page
```
```
In mm/page-writeback.c (ffffffff811bfc3e)
Location: include/linux/backing-dev.h:232
Inline: True
Inline callers:
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/mmap.c (ffffffff811f1b0d)
Location: include/linux/backing-dev.h:232
Inline: True
```
```
In mm/migrate.c (ffffffff81223116)
Location: include/linux/backing-dev.h:232
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memcontrol.c (ffffffff81233659)
Location: include/linux/backing-dev.h:232
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
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
In mm/filemap.c (ffffffff811b82b9)
Location: include/linux/backing-dev.h:207
Inline: True
Inline callers:
  - mm/filemap.c:pagecache_get_page
```
```
In mm/page-writeback.c (ffffffff811c7e0e)
Location: include/linux/backing-dev.h:207
Inline: True
Inline callers:
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/mmap.c (ffffffff811fc814)
Location: include/linux/backing-dev.h:207
Inline: True
```
```
In mm/migrate.c (ffffffff8122eb39)
Location: include/linux/backing-dev.h:207
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memcontrol.c (ffffffff8123ef1f)
Location: include/linux/backing-dev.h:207
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
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
In mm/filemap.c (ffffffff811cc9a9)
Location: include/linux/backing-dev.h:212
Inline: True
Inline callers:
  - mm/filemap.c:pagecache_get_page
```
```
In mm/page-writeback.c (ffffffff811dcc4e)
Location: include/linux/backing-dev.h:212
Inline: True
Inline callers:
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/mmap.c (ffffffff81214d70)
Location: include/linux/backing-dev.h:212
Inline: True
```
```
In mm/migrate.c (ffffffff8124ac85)
Location: include/linux/backing-dev.h:212
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memcontrol.c (ffffffff8125eaae)
Location: include/linux/backing-dev.h:212
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
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
In mm/filemap.c (ffffffff811edaaf)
Location: include/linux/backing-dev.h:213
Inline: True
Inline callers:
  - mm/filemap.c:pagecache_get_page
```
```
In mm/page-writeback.c (ffffffff811fdce4)
Location: include/linux/backing-dev.h:213
Inline: True
Inline callers:
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/mmap.c (ffffffff81235bed)
Location: include/linux/backing-dev.h:213
Inline: True
Inline callers:
  - mm/mmap.c:vma_wants_writenotify
```
```
In mm/migrate.c (ffffffff8126eabc)
Location: include/linux/backing-dev.h:213
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memcontrol.c (ffffffff81282d68)
Location: include/linux/backing-dev.h:213
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
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
In mm/filemap.c (ffffffff811ff05f)
Location: include/linux/backing-dev.h:213
Inline: True
Inline callers:
  - mm/filemap.c:pagecache_get_page
```
```
In mm/page-writeback.c (ffffffff81210974)
Location: include/linux/backing-dev.h:213
Inline: True
Inline callers:
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/mmap.c (ffffffff812493fa)
Location: include/linux/backing-dev.h:213
Inline: True
Inline callers:
  - mm/mmap.c:vma_wants_writenotify
```
```
In mm/migrate.c (ffffffff81282782)
Location: include/linux/backing-dev.h:213
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memcontrol.c (ffffffff81296f08)
Location: include/linux/backing-dev.h:213
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
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
In mm/filemap.c (ffffffff81216060)
Location: include/linux/backing-dev.h:214
Inline: True
Inline callers:
  - mm/filemap.c:pagecache_get_page
```
```
In mm/page-writeback.c (ffffffff812200b4)
Location: include/linux/backing-dev.h:214
Inline: True
Inline callers:
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/mmap.c (ffffffff8125b70f)
Location: include/linux/backing-dev.h:214
Inline: True
Inline callers:
  - mm/mmap.c:vma_wants_writenotify
```
```
In mm/migrate.c (ffffffff8129e77a)
Location: include/linux/backing-dev.h:214
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memcontrol.c (ffffffff812b2b8e)
Location: include/linux/backing-dev.h:214
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
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
In mm/filemap.c (ffffffff8122396f)
Location: include/linux/backing-dev.h:218
Inline: True
Inline callers:
  - mm/filemap.c:pagecache_get_page
```
```
In mm/page-writeback.c (ffffffff8122db64)
Location: include/linux/backing-dev.h:218
Inline: True
Inline callers:
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/mmap.c (ffffffff81269def)
Location: include/linux/backing-dev.h:218
Inline: True
Inline callers:
  - mm/mmap.c:vma_wants_writenotify
```
```
In mm/migrate.c (ffffffff812ae019)
Location: include/linux/backing-dev.h:218
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memcontrol.c (ffffffff812c4646)
Location: include/linux/backing-dev.h:218
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
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
In mm/filemap.c (ffffffff81251ebd)
Location: include/linux/backing-dev.h:214
Inline: True
Inline callers:
  - mm/filemap.c:pagecache_get_page
```
```
In mm/page-writeback.c (ffffffff81259609)
Location: include/linux/backing-dev.h:214
Inline: True
Inline callers:
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/mmap.c (ffffffff8129a61f)
Location: include/linux/backing-dev.h:214
Inline: True
Inline callers:
  - mm/mmap.c:vma_wants_writenotify
```
```
In mm/migrate.c (ffffffff812e4b62)
Location: include/linux/backing-dev.h:214
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memcontrol.c (ffffffff812fa537)
Location: include/linux/backing-dev.h:214
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
</details>
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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffff8000102b1428)
Location: include/linux/backing-dev.h:218
Inline: True
Inline callers:
  - mm/filemap.c:pagecache_get_page
```
```
In mm/page-writeback.c (ffff8000102bca00)
Location: include/linux/backing-dev.h:218
Inline: True
Inline callers:
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/mmap.c (ffff800010301184)
Location: include/linux/backing-dev.h:218
Inline: True
```
```
In mm/migrate.c (ffff80001034ff90)
Location: include/linux/backing-dev.h:218
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memcontrol.c (ffff8000103672b4)
Location: include/linux/backing-dev.h:218
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
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
In mm/filemap.c (c04ddd08)
Location: include/linux/backing-dev.h:218
Inline: True
Inline callers:
  - mm/filemap.c:pagecache_get_page
```
```
In mm/page-writeback.c (c04e8f64)
Location: include/linux/backing-dev.h:218
Inline: True
Inline callers:
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/mmap.c (c051fcbc)
Location: include/linux/backing-dev.h:218
Inline: True
```
```
In mm/migrate.c (c05511a0)
Location: include/linux/backing-dev.h:218
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memcontrol.c (c05589c4)
Location: include/linux/backing-dev.h:218
Inline: True
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
In mm/filemap.c (c000000000366a50)
Location: include/linux/backing-dev.h:218
Inline: True
Inline callers:
  - mm/filemap.c:pagecache_get_page
```
```
In mm/page-writeback.c (c000000000375438)
Location: include/linux/backing-dev.h:218
Inline: True
Inline callers:
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/mmap.c (c0000000003cd55c)
Location: include/linux/backing-dev.h:218
Inline: True
```
```
In mm/migrate.c (c000000000433520)
Location: include/linux/backing-dev.h:218
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memcontrol.c (c00000000045470c)
Location: include/linux/backing-dev.h:218
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
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
In mm/filemap.c (ffffffe0001d6a8c)
Location: include/linux/backing-dev.h:218
Inline: True
Inline callers:
  - mm/filemap.c:pagecache_get_page
```
```
In mm/page-writeback.c (ffffffe0001df99c)
Location: include/linux/backing-dev.h:218
Inline: True
Inline callers:
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/mmap.c (ffffffe00020e676)
Location: include/linux/backing-dev.h:218
Inline: True
```
```
In mm/migrate.c (ffffffe00023ec7e)
Location: include/linux/backing-dev.h:218
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memcontrol.c (ffffffe000245444)
Location: include/linux/backing-dev.h:218
Inline: True
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
In mm/filemap.c (ffffffff8121bfbf)
Location: include/linux/backing-dev.h:218
Inline: True
Inline callers:
  - mm/filemap.c:pagecache_get_page
```
```
In mm/page-writeback.c (ffffffff812261b4)
Location: include/linux/backing-dev.h:218
Inline: True
Inline callers:
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/mmap.c (ffffffff8126243f)
Location: include/linux/backing-dev.h:218
Inline: True
Inline callers:
  - mm/mmap.c:vma_wants_writenotify
```
```
In mm/migrate.c (ffffffff812a65f9)
Location: include/linux/backing-dev.h:218
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memcontrol.c (ffffffff812bcc26)
Location: include/linux/backing-dev.h:218
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
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
In mm/filemap.c (ffffffff8120f1af)
Location: include/linux/backing-dev.h:218
Inline: True
Inline callers:
  - mm/filemap.c:pagecache_get_page
```
```
In mm/page-writeback.c (ffffffff81219344)
Location: include/linux/backing-dev.h:218
Inline: True
Inline callers:
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/mmap.c (ffffffff8125485f)
Location: include/linux/backing-dev.h:218
Inline: True
Inline callers:
  - mm/mmap.c:vma_wants_writenotify
```
```
In mm/migrate.c (ffffffff812980a3)
Location: include/linux/backing-dev.h:218
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memcontrol.c (ffffffff812add7a)
Location: include/linux/backing-dev.h:218
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
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
In mm/filemap.c (ffffffff81219d5f)
Location: include/linux/backing-dev.h:218
Inline: True
Inline callers:
  - mm/filemap.c:pagecache_get_page
```
```
In mm/page-writeback.c (ffffffff81223f54)
Location: include/linux/backing-dev.h:218
Inline: True
Inline callers:
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/mmap.c (ffffffff812601df)
Location: include/linux/backing-dev.h:218
Inline: True
Inline callers:
  - mm/mmap.c:vma_wants_writenotify
```
```
In mm/migrate.c (ffffffff812a4409)
Location: include/linux/backing-dev.h:218
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memcontrol.c (ffffffff812baa36)
Location: include/linux/backing-dev.h:218
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
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
In mm/filemap.c (ffffffff81228e5f)
Location: include/linux/backing-dev.h:218
Inline: True
Inline callers:
  - mm/filemap.c:pagecache_get_page
```
```
In mm/page-writeback.c (ffffffff81233214)
Location: include/linux/backing-dev.h:218
Inline: True
Inline callers:
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/mmap.c (ffffffff8126fbaf)
Location: include/linux/backing-dev.h:218
Inline: True
Inline callers:
  - mm/mmap.c:vma_wants_writenotify
```
```
In mm/migrate.c (ffffffff812b3b77)
Location: include/linux/backing-dev.h:218
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memcontrol.c (ffffffff812cb176)
Location: include/linux/backing-dev.h:218
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
</details>
</li>
</ul>

## Differences
