# Function: <code>PageMappedToDisk</code>

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
In mm/filemap.c (ffffffff8118e3e4)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/swap.c (ffffffff8119c5dd)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/migrate.c (ffffffff811f1c6c)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
```
```
In fs/buffer.c (ffffffff812460b6)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
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
In mm/filemap.c (ffffffff811a1dfc)
Location: include/linux/page-flags.h:298
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/swap.c (ffffffff811b1e7c)
Location: include/linux/page-flags.h:298
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/migrate.c (ffffffff81210671)
Location: include/linux/page-flags.h:298
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
```
```
In fs/buffer.c (ffffffff8126ef87)
Location: include/linux/page-flags.h:298
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
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
In mm/filemap.c (ffffffff811b1c6d)
Location: include/linux/page-flags.h:308
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/swap.c (ffffffff811c24c8)
Location: include/linux/page-flags.h:308
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/migrate.c (ffffffff812227b8)
Location: include/linux/page-flags.h:308
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
```
```
In fs/buffer.c (ffffffff81282197)
Location: include/linux/page-flags.h:308
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
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
In mm/filemap.c (ffffffff811b897b)
Location: include/linux/page-flags.h:308
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/swap.c (ffffffff811ca969)
Location: include/linux/page-flags.h:308
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/migrate.c (ffffffff8122e24c)
Location: include/linux/page-flags.h:308
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
```
```
In fs/buffer.c (ffffffff8128f8a4)
Location: include/linux/page-flags.h:308
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
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
In mm/filemap.c (ffffffff811ca0de)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (ffffffff811dfb30)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/migrate.c (ffffffff81249320)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/buffer.c (ffffffff812b25a4)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
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
In mm/filemap.c (ffffffff811eb25e)
Location: include/linux/page-flags.h:316
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (ffffffff81201091)
Location: include/linux/page-flags.h:316
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/migrate.c (ffffffff8126cda1)
Location: include/linux/page-flags.h:316
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/buffer.c (ffffffff812da487)
Location: include/linux/page-flags.h:316
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
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
In mm/filemap.c (ffffffff811fbdce)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (ffffffff81213a01)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/migrate.c (ffffffff812815cd)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/buffer.c (ffffffff812ef967)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
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
In mm/filemap.c (ffffffff81213eab)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (ffffffff81223417)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/migrate.c (ffffffff8129d85f)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/buffer.c (ffffffff813111e7)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
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
In mm/filemap.c (ffffffff812216bb)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (ffffffff81230ec7)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/migrate.c (ffffffff812ad17d)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/buffer.c (ffffffff813241c7)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
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
In mm/filemap.c (ffffffff8124f54b)
Location: include/linux/page-flags.h:369
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (ffffffff8125dd01)
Location: include/linux/page-flags.h:369
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/migrate.c (ffffffff812e2cbb)
Location: include/linux/page-flags.h:369
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/buffer.c (ffffffff8135e1f7)
Location: include/linux/page-flags.h:369
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
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
In mm/filemap.c (ffffffff812598ab)
Location: include/linux/page-flags.h:377
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (ffffffff812681b1)
Location: include/linux/page-flags.h:377
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/migrate.c (ffffffff812ee0eb)
Location: include/linux/page-flags.h:377
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/buffer.c (ffffffff8136bd16)
Location: include/linux/page-flags.h:377
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
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
In mm/filemap.c (ffffffff8125da3b)
Location: include/linux/page-flags.h:377
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (ffffffff8126d3b3)
Location: include/linux/page-flags.h:377
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/migrate.c (ffffffff812f3bdb)
Location: include/linux/page-flags.h:377
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/buffer.c (ffffffff81372646)
Location: include/linux/page-flags.h:377
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
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
In mm/filemap.c (ffffffff81299ccb)
Location: include/linux/page-flags.h:391
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (ffffffff812a9db3)
Location: include/linux/page-flags.h:391
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/migrate.c (ffffffff8133e57b)
Location: include/linux/page-flags.h:391
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/buffer.c (ffffffff813c16a1)
Location: include/linux/page-flags.h:391
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
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
In mm/memory.c (ffffffff8134437b)
Location: include/linux/page-flags.h:541
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/swapfile.c (ffffffff8137ec61)
Location: include/linux/page-flags.h:541
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In fs/buffer.c (ffffffff8144858a)
Location: include/linux/page-flags.h:541
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff813fd66f)
Location: include/linux/page-flags.h:520
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
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
In mm/swapfile.c (ffffffff8143093c)
Location: include/linux/page-flags.h:513
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
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
In mm/filemap.c (ffff8000102aece4)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (ffff8000102c05d4)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/migrate.c (ffff80001034f478)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/buffer.c (ffff8000103dd500)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
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
In mm/filemap.c (c04da92c)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (c04ec234)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/migrate.c (c0551408)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/buffer.c (c05b69f0)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
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
In mm/filemap.c (c000000000362160)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (c000000000379dc4)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/migrate.c (c0000000004318c0)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/buffer.c (c0000000004e2e20)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
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
In mm/filemap.c (ffffffe0001d42be)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (ffffffe0001e254e)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/migrate.c (ffffffe00023e4a0)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/buffer.c (ffffffe000295582)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
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
In mm/filemap.c (ffffffff81219d0b)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (ffffffff81229517)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/migrate.c (ffffffff812a575d)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/buffer.c (ffffffff8131c7a7)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
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
In mm/filemap.c (ffffffff8120cf1b)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (ffffffff8121c637)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/migrate.c (ffffffff8129722d)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/buffer.c (ffffffff8130d347)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
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
In mm/filemap.c (ffffffff81217aab)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (ffffffff812272b7)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/migrate.c (ffffffff812a356d)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/buffer.c (ffffffff8131a277)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
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
In mm/filemap.c (ffffffff81226b6b)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (ffffffff812365e7)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/migrate.c (ffffffff812b3d7d)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/buffer.c (ffffffff8132bf77)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
```
</details>
</li>
</ul>

## Differences
