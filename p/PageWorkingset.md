# Function: <code>PageWorkingset</code>

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
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811ff4b7)
Location: include/linux/page-flags.h:292
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
```
```
In mm/workingset.c (ffffffff81238dd9)
Location: include/linux/page-flags.h:292
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/migrate.c (ffffffff81281594)
Location: include/linux/page-flags.h:292
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
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
In mm/filemap.c (ffffffff81216745)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
```
```
In mm/workingset.c (ffffffff81249fdd)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/migrate.c (ffffffff8129d826)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
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
In mm/filemap.c (ffffffff81224055)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
```
```
In mm/workingset.c (ffffffff8125842c)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/migrate.c (ffffffff812ad144)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In block/bio.c (ffffffff814de65c)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - block/bio.c:__bio_add_page
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
In mm/filemap.c (ffffffff8124f9f7)
Location: include/linux/page-flags.h:331
Inline: True
Inline callers:
  - mm/filemap.c:wait_on_page_bit_common
```
```
In mm/workingset.c (ffffffff81286add)
Location: include/linux/page-flags.h:331
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/migrate.c (ffffffff812e2c84)
Location: include/linux/page-flags.h:331
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In block/bio.c (ffffffff8153dbfc)
Location: include/linux/page-flags.h:331
Inline: True
Inline callers:
  - block/bio.c:__bio_add_page
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
In mm/filemap.c (ffffffff8125a91d)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/filemap.c:wait_on_page_bit_common
```
```
In mm/workingset.c (ffffffff81290d3e)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/migrate.c (ffffffff812ee0b4)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In block/bio.c (ffffffff8155a77c)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - block/bio.c:__bio_add_page
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
In mm/filemap.c (ffffffff8125f16f)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/filemap.c:wait_on_page_bit_common
```
```
In mm/workingset.c (ffffffff8129639d)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/migrate.c (ffffffff812f3ba4)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In block/bio.c (ffffffff81562f50)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - block/bio.c:__bio_add_page
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
In mm/filemap.c (ffffffff8129b8d1)
Location: include/linux/page-flags.h:354
Inline: True
Inline callers:
  - mm/filemap.c:wait_on_page_bit_common
```
```
In mm/workingset.c (ffffffff812d6b31)
Location: include/linux/page-flags.h:354
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/migrate.c (ffffffff8133e544)
Location: include/linux/page-flags.h:354
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In block/bio.c (ffffffff815c631e)
Location: include/linux/page-flags.h:354
Inline: True
Inline callers:
  - block/bio.c:__bio_add_page
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
In mm/page_io.c (ffffffff8137a456)
Location: include/linux/page-flags.h:504
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In block/bio.c (ffffffff81670fdc)
Location: include/linux/page-flags.h:504
Inline: True
Inline callers:
  - block/bio.c:__bio_add_page
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
In mm/readahead.c (ffffffff8136c114)
Location: include/linux/page-flags.h:483
Inline: True
Inline callers:
  - mm/readahead.c:readahead_expand
```
```
In mm/page_io.c (ffffffff813f7ef6)
Location: include/linux/page-flags.h:483
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff8142afe6)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
</details>
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
In mm/filemap.c (ffff8000102af57c)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/filemap.c:wait_on_page_bit_common
```
```
In mm/workingset.c (ffff8000102f0214)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/migrate.c (ffff80001034f430)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In block/bio.c (ffff8000105d9edc)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - block/bio.c:__bio_add_page
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
In mm/filemap.c (c04de1c4)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
```
```
In mm/workingset.c (c0513938)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/migrate.c (c05513c8)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In block/bio.c (c07874bc)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - block/bio.c:__bio_add_page
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
In mm/filemap.c (c0000000003673d0)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
```
```
In mm/workingset.c (c0000000003b4bc0)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/migrate.c (c000000000431860)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In block/bio.c (c00000000076a2e0)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - block/bio.c:__bio_add_page
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
In mm/filemap.c (ffffffe0001d70f0)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
```
```
In mm/workingset.c (ffffffe000203c16)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/migrate.c (ffffffe00023e466)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In block/bio.c (ffffffe00041d89a)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - block/bio.c:__bio_add_page
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
In mm/filemap.c (ffffffff8121c6a5)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
```
```
In mm/workingset.c (ffffffff81250a7c)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/migrate.c (ffffffff812a5724)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In block/bio.c (ffffffff814d6c3c)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - block/bio.c:__bio_add_page
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
In mm/filemap.c (ffffffff8120f889)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
```
```
In mm/workingset.c (ffffffff812439fc)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/migrate.c (ffffffff812971f4)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In block/bio.c (ffffffff814c75fc)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - block/bio.c:__bio_add_page
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
In mm/filemap.c (ffffffff8121a445)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
```
```
In mm/workingset.c (ffffffff8124e81c)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/migrate.c (ffffffff812a3534)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In block/bio.c (ffffffff814d2ccc)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - block/bio.c:__bio_add_page
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
In mm/filemap.c (ffffffff81229510)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
```
```
In mm/workingset.c (ffffffff8125e18c)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/migrate.c (ffffffff812b3d44)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In block/bio.c (ffffffff814eb84c)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - block/bio.c:__bio_add_page
```
</details>
</li>
</ul>

## Differences
