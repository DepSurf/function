# Function: <code>SetPageWorkingset</code>

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
In mm/vmscan.c (ffffffff8121d579)
Location: include/linux/page-flags.h:292
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
```
```
In mm/workingset.c (ffffffff81239074)
Location: include/linux/page-flags.h:292
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
```
```
In mm/swap_state.c (ffffffff8125c3e0)
Location: include/linux/page-flags.h:292
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/migrate.c (ffffffff812815aa)
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
In mm/vmscan.c (ffffffff8122cf1e)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
```
```
In mm/workingset.c (ffffffff8124a18c)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
```
```
In mm/swap_state.c (ffffffff812775ce)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/migrate.c (ffffffff8129d83d)
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
In mm/vmscan.c (ffffffff8123b13e)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
```
```
In mm/workingset.c (ffffffff812585dc)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
```
```
In mm/swap_state.c (ffffffff812870b6)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/migrate.c (ffffffff812ad15b)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
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
In mm/vmscan.c (ffffffff812683f0)
Location: include/linux/page-flags.h:331
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
```
```
In mm/workingset.c (ffffffff81286d1b)
Location: include/linux/page-flags.h:331
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
```
```
In mm/swap_state.c (ffffffff812b971d)
Location: include/linux/page-flags.h:331
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/migrate.c (ffffffff812e2c9b)
Location: include/linux/page-flags.h:331
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
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
In mm/vmscan.c (ffffffff81272e88)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
```
```
In mm/workingset.c (ffffffff81290fce)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
```
```
In mm/swap_state.c (ffffffff812c517b)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/migrate.c (ffffffff812ee0cb)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
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
In mm/vmscan.c (ffffffff81278175)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
```
```
In mm/workingset.c (ffffffff812965ee)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
```
```
In mm/migrate.c (ffffffff812f3bbb)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
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
In mm/vmscan.c (ffffffff812b5e0e)
Location: include/linux/page-flags.h:354
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
```
```
In mm/workingset.c (ffffffff812d6d84)
Location: include/linux/page-flags.h:354
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
```
```
In mm/migrate.c (ffffffff8133e55b)
Location: include/linux/page-flags.h:354
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8130f076)
Location: include/linux/page-flags.h:504
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
```
</details>
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
In mm/vmscan.c (ffff8000102cc1cc)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
```
```
In mm/workingset.c (ffff8000102f03bc)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
```
```
In mm/swap_state.c (ffff800010321ba4)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/migrate.c (ffff80001034f44c)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
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
In mm/vmscan.c (c04f5f98)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
```
```
In mm/workingset.c (c0513ad8)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
```
```
In mm/swap_state.c (c053a2d8)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/migrate.c (c05513e4)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
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
In mm/vmscan.c (c000000000389640)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
```
```
In mm/workingset.c (c0000000003b4dd4)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
```
```
In mm/swap_state.c (c0000000003f7380)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/migrate.c (c00000000043187c)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
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
In mm/vmscan.c (ffffffe0001ead20)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
```
```
In mm/workingset.c (ffffffe000203db4)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
```
```
In mm/swap_state.c (ffffffe000222cec)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/migrate.c (ffffffe00023e47a)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
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
In mm/vmscan.c (ffffffff8123378e)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
```
```
In mm/workingset.c (ffffffff81250c2c)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
```
```
In mm/swap_state.c (ffffffff8127f706)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/migrate.c (ffffffff812a573b)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
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
In mm/vmscan.c (ffffffff81226808)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
```
```
In mm/workingset.c (ffffffff81243b80)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
```
```
In mm/swap_state.c (ffffffff81271526)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/migrate.c (ffffffff8129720b)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
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
In mm/vmscan.c (ffffffff8123152e)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
```
```
In mm/workingset.c (ffffffff8124e9cc)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
```
```
In mm/swap_state.c (ffffffff8127d4a6)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/migrate.c (ffffffff812a354b)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
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
In mm/vmscan.c (ffffffff81240965)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
```
```
In mm/workingset.c (ffffffff8125e341)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
```
```
In mm/swap_state.c (ffffffff8128d075)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/migrate.c (ffffffff812b3d5b)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
</details>
</li>
</ul>

## Differences
