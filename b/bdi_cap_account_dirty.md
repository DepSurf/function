# Function: <code>bdi_cap_account_dirty</code>

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
In mm/filemap.c (0)
Location: include/linux/backing-dev.h:214
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/backing-dev.h:214
Inline: True
```
```
In mm/mmap.c (0)
Location: include/linux/backing-dev.h:214
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/backing-dev.h:214
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/backing-dev.h:214
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/backing-dev.h:214
Inline: True
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
In mm/filemap.c (0)
Location: include/linux/backing-dev.h:215
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/backing-dev.h:215
Inline: True
```
```
In mm/mmap.c (0)
Location: include/linux/backing-dev.h:215
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/backing-dev.h:215
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/backing-dev.h:215
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/backing-dev.h:215
Inline: True
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
In mm/filemap.c (0)
Location: include/linux/backing-dev.h:215
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/backing-dev.h:215
Inline: True
```
```
In mm/mmap.c (0)
Location: include/linux/backing-dev.h:215
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/backing-dev.h:215
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/backing-dev.h:215
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/backing-dev.h:215
Inline: True
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
In mm/filemap.c (0)
Location: include/linux/backing-dev.h:190
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/backing-dev.h:190
Inline: True
```
```
In mm/mmap.c (0)
Location: include/linux/backing-dev.h:190
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/backing-dev.h:190
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/backing-dev.h:190
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/backing-dev.h:190
Inline: True
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
In mm/filemap.c (0)
Location: include/linux/backing-dev.h:195
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/backing-dev.h:195
Inline: True
```
```
In mm/mmap.c (0)
Location: include/linux/backing-dev.h:195
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/backing-dev.h:195
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/backing-dev.h:195
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/backing-dev.h:195
Inline: True
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
In mm/filemap.c (ffffffff811edad3)
Location: include/linux/backing-dev.h:196
Inline: True
Inline callers:
  - mm/filemap.c:pagecache_get_page
```
```
In mm/page-writeback.c (ffffffff811fdd08)
Location: include/linux/backing-dev.h:196
Inline: True
Inline callers:
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/mmap.c (0)
Location: include/linux/backing-dev.h:196
Inline: True
```
```
In mm/migrate.c (ffffffff8126eae0)
Location: include/linux/backing-dev.h:196
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memcontrol.c (ffffffff81282d8c)
Location: include/linux/backing-dev.h:196
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In fs/fs-writeback.c (ffffffff812cd283)
Location: include/linux/backing-dev.h:196
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:__inode_attach_wb
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
In mm/filemap.c (ffffffff811ff083)
Location: include/linux/backing-dev.h:196
Inline: True
Inline callers:
  - mm/filemap.c:pagecache_get_page
```
```
In mm/page-writeback.c (ffffffff81210998)
Location: include/linux/backing-dev.h:196
Inline: True
Inline callers:
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/mmap.c (0)
Location: include/linux/backing-dev.h:196
Inline: True
```
```
In mm/migrate.c (ffffffff812827a6)
Location: include/linux/backing-dev.h:196
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memcontrol.c (ffffffff81296f2c)
Location: include/linux/backing-dev.h:196
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In fs/fs-writeback.c (ffffffff812e25a3)
Location: include/linux/backing-dev.h:196
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:__inode_attach_wb
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
In mm/filemap.c (ffffffff81216081)
Location: include/linux/backing-dev.h:197
Inline: True
Inline callers:
  - mm/filemap.c:pagecache_get_page
```
```
In mm/page-writeback.c (ffffffff812200d5)
Location: include/linux/backing-dev.h:197
Inline: True
Inline callers:
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/mmap.c (0)
Location: include/linux/backing-dev.h:197
Inline: True
```
```
In mm/migrate.c (ffffffff8129e79b)
Location: include/linux/backing-dev.h:197
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memcontrol.c (ffffffff812b2bab)
Location: include/linux/backing-dev.h:197
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In fs/fs-writeback.c (ffffffff813005f0)
Location: include/linux/backing-dev.h:197
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:__inode_attach_wb
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
In mm/filemap.c (ffffffff81223990)
Location: include/linux/backing-dev.h:201
Inline: True
Inline callers:
  - mm/filemap.c:pagecache_get_page
```
```
In mm/page-writeback.c (ffffffff8122db85)
Location: include/linux/backing-dev.h:201
Inline: True
Inline callers:
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/mmap.c (0)
Location: include/linux/backing-dev.h:201
Inline: True
```
```
In mm/migrate.c (ffffffff812ae03a)
Location: include/linux/backing-dev.h:201
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memcontrol.c (ffffffff812c4663)
Location: include/linux/backing-dev.h:201
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In fs/fs-writeback.c (ffffffff81312c30)
Location: include/linux/backing-dev.h:201
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:__inode_attach_wb
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
In mm/filemap.c (ffffffff81251ee1)
Location: include/linux/backing-dev.h:197
Inline: True
Inline callers:
  - mm/filemap.c:pagecache_get_page
```
```
In mm/page-writeback.c (ffffffff8125962a)
Location: include/linux/backing-dev.h:197
Inline: True
Inline callers:
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/mmap.c (ffffffff8129a63b)
Location: include/linux/backing-dev.h:197
Inline: True
Inline callers:
  - mm/mmap.c:vma_wants_writenotify
```
```
In mm/migrate.c (ffffffff812e4b86)
Location: include/linux/backing-dev.h:197
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memcontrol.c (ffffffff812fa55b)
Location: include/linux/backing-dev.h:197
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In fs/fs-writeback.c (ffffffff81349d80)
Location: include/linux/backing-dev.h:197
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
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
In mm/filemap.c (ffff8000102b1440)
Location: include/linux/backing-dev.h:201
Inline: True
Inline callers:
  - mm/filemap.c:pagecache_get_page
```
```
In mm/page-writeback.c (ffff8000102bca1c)
Location: include/linux/backing-dev.h:201
Inline: True
Inline callers:
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/mmap.c (0)
Location: include/linux/backing-dev.h:201
Inline: True
```
```
In mm/migrate.c (ffff80001034ffac)
Location: include/linux/backing-dev.h:201
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memcontrol.c (ffff8000103672d0)
Location: include/linux/backing-dev.h:201
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In fs/fs-writeback.c (ffff8000103c84ec)
Location: include/linux/backing-dev.h:201
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
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
In mm/filemap.c (c04ddd28)
Location: include/linux/backing-dev.h:201
Inline: True
Inline callers:
  - mm/filemap.c:pagecache_get_page
```
```
In mm/page-writeback.c (c04e8f8c)
Location: include/linux/backing-dev.h:201
Inline: True
Inline callers:
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/mmap.c (c051fce4)
Location: include/linux/backing-dev.h:201
Inline: True
```
```
In mm/migrate.c (c05511c8)
Location: include/linux/backing-dev.h:201
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memcontrol.c (c05589ec)
Location: include/linux/backing-dev.h:201
Inline: True
```
```
In fs/fs-writeback.c (c05a4da4)
Location: include/linux/backing-dev.h:201
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
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
In mm/filemap.c (c000000000366a78)
Location: include/linux/backing-dev.h:201
Inline: True
Inline callers:
  - mm/filemap.c:pagecache_get_page
```
```
In mm/page-writeback.c (c000000000375460)
Location: include/linux/backing-dev.h:201
Inline: True
Inline callers:
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/mmap.c (c0000000003cd584)
Location: include/linux/backing-dev.h:201
Inline: True
```
```
In mm/migrate.c (c000000000433548)
Location: include/linux/backing-dev.h:201
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memcontrol.c (c000000000454734)
Location: include/linux/backing-dev.h:201
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In fs/fs-writeback.c (c0000000004c98b4)
Location: include/linux/backing-dev.h:201
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
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
In mm/filemap.c (ffffffe0001d6b94)
Location: include/linux/backing-dev.h:201
Inline: True
Inline callers:
  - mm/filemap.c:pagecache_get_page
```
```
In mm/page-writeback.c (ffffffe0001df9b2)
Location: include/linux/backing-dev.h:201
Inline: True
Inline callers:
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/mmap.c (ffffffe00020e68a)
Location: include/linux/backing-dev.h:201
Inline: True
```
```
In mm/migrate.c (ffffffe00023ec96)
Location: include/linux/backing-dev.h:201
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memcontrol.c (ffffffe000245458)
Location: include/linux/backing-dev.h:201
Inline: True
```
```
In fs/fs-writeback.c (ffffffe000286b58)
Location: include/linux/backing-dev.h:201
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:__inode_attach_wb
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
In mm/filemap.c (ffffffff8121bfe0)
Location: include/linux/backing-dev.h:201
Inline: True
Inline callers:
  - mm/filemap.c:pagecache_get_page
```
```
In mm/page-writeback.c (ffffffff812261d5)
Location: include/linux/backing-dev.h:201
Inline: True
Inline callers:
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/mmap.c (0)
Location: include/linux/backing-dev.h:201
Inline: True
```
```
In mm/migrate.c (ffffffff812a661a)
Location: include/linux/backing-dev.h:201
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memcontrol.c (ffffffff812bcc43)
Location: include/linux/backing-dev.h:201
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In fs/fs-writeback.c (ffffffff8130b210)
Location: include/linux/backing-dev.h:201
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:__inode_attach_wb
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
In mm/filemap.c (ffffffff8120f1d0)
Location: include/linux/backing-dev.h:201
Inline: True
Inline callers:
  - mm/filemap.c:pagecache_get_page
```
```
In mm/page-writeback.c (ffffffff81219365)
Location: include/linux/backing-dev.h:201
Inline: True
Inline callers:
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/mmap.c (0)
Location: include/linux/backing-dev.h:201
Inline: True
```
```
In mm/migrate.c (ffffffff812980c4)
Location: include/linux/backing-dev.h:201
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memcontrol.c (ffffffff812add97)
Location: include/linux/backing-dev.h:201
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In fs/fs-writeback.c (ffffffff812fbe30)
Location: include/linux/backing-dev.h:201
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:__inode_attach_wb
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
In mm/filemap.c (ffffffff81219d80)
Location: include/linux/backing-dev.h:201
Inline: True
Inline callers:
  - mm/filemap.c:pagecache_get_page
```
```
In mm/page-writeback.c (ffffffff81223f75)
Location: include/linux/backing-dev.h:201
Inline: True
Inline callers:
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/mmap.c (0)
Location: include/linux/backing-dev.h:201
Inline: True
```
```
In mm/migrate.c (ffffffff812a442a)
Location: include/linux/backing-dev.h:201
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memcontrol.c (ffffffff812baa53)
Location: include/linux/backing-dev.h:201
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In fs/fs-writeback.c (ffffffff81309000)
Location: include/linux/backing-dev.h:201
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:__inode_attach_wb
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
In mm/filemap.c (ffffffff81228e80)
Location: include/linux/backing-dev.h:201
Inline: True
Inline callers:
  - mm/filemap.c:pagecache_get_page
```
```
In mm/page-writeback.c (ffffffff81233235)
Location: include/linux/backing-dev.h:201
Inline: True
Inline callers:
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/page-writeback.c:account_page_redirty
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/mmap.c (0)
Location: include/linux/backing-dev.h:201
Inline: True
```
```
In mm/migrate.c (ffffffff812b3b98)
Location: include/linux/backing-dev.h:201
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memcontrol.c (ffffffff812cb193)
Location: include/linux/backing-dev.h:201
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In fs/fs-writeback.c (ffffffff8131ad00)
Location: include/linux/backing-dev.h:201
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:__inode_attach_wb
```
</details>
</li>
</ul>

## Differences
