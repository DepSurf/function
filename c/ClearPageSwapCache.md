# Function: <code>ClearPageSwapCache</code>

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
In mm/shmem.c (ffffffff811a8e82)
Location: include/linux/page-flags.h:260
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
```
```
In mm/swap_state.c (ffffffff811d27d7)
Location: include/linux/page-flags.h:260
Inline: True
Inline callers:
  - mm/swap_state.c:__add_to_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
```
```
In mm/migrate.c (ffffffff811f1cd5)
Location: include/linux/page-flags.h:260
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
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
In mm/shmem.c (ffffffff811c0405)
Location: include/linux/page-flags.h:317
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
```
```
In mm/swap_state.c (ffffffff811f0528)
Location: include/linux/page-flags.h:317
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:__add_to_swap_cache
```
```
In mm/migrate.c (ffffffff81210713)
Location: include/linux/page-flags.h:317
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
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
In mm/shmem.c (ffffffff811d09dd)
Location: include/linux/page-flags.h:333
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
```
```
In mm/swap_state.c (ffffffff81200ef5)
Location: include/linux/page-flags.h:333
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:__add_to_swap_cache
```
```
In mm/migrate.c (ffffffff81222883)
Location: include/linux/page-flags.h:333
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
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
In mm/shmem.c (ffffffff811d8fe1)
Location: include/linux/page-flags.h:336
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
```
```
In mm/swap_state.c (ffffffff8120bd63)
Location: include/linux/page-flags.h:336
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:__add_to_swap_cache
```
```
In mm/migrate.c (ffffffff8122e319)
Location: include/linux/page-flags.h:336
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
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
In mm/shmem.c (ffffffff811ee261)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
```
```
In mm/swap_state.c (ffffffff81225356)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:__add_to_swap_cache
```
```
In mm/migrate.c (ffffffff8124945e)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
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
In mm/shmem.c (ffffffff8120eb90)
Location: include/linux/page-flags.h:344
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
```
```
In mm/swap_state.c (ffffffff812478f5)
Location: include/linux/page-flags.h:344
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:__add_to_swap_cache
```
```
In mm/migrate.c (ffffffff8126cea3)
Location: include/linux/page-flags.h:344
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
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
In mm/shmem.c (ffffffff81221f1f)
Location: include/linux/page-flags.h:356
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
```
```
In mm/swap_state.c (ffffffff8125beaa)
Location: include/linux/page-flags.h:356
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff812816cf)
Location: include/linux/page-flags.h:356
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
In mm/shmem.c (ffffffff8123347a)
Location: include/linux/page-flags.h:389
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/swap_state.c (ffffffff8127706d)
Location: include/linux/page-flags.h:389
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff8129d9a4)
Location: include/linux/page-flags.h:389
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
In mm/shmem.c (ffffffff81241670)
Location: include/linux/page-flags.h:389
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/swap_state.c (ffffffff81286b4d)
Location: include/linux/page-flags.h:389
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff812ad2c2)
Location: include/linux/page-flags.h:389
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
In mm/shmem.c (ffffffff8126d516)
Location: include/linux/page-flags.h:397
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
```
```
In mm/memory.c (ffffffff81291b10)
Location: include/linux/page-flags.h:397
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/swap_state.c (ffffffff812b90ce)
Location: include/linux/page-flags.h:397
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff812e2e17)
Location: include/linux/page-flags.h:397
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
In mm/shmem.c (ffffffff81277c6f)
Location: include/linux/page-flags.h:405
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
```
```
In mm/memory.c (ffffffff8129c411)
Location: include/linux/page-flags.h:405
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/swap_state.c (ffffffff812c4880)
Location: include/linux/page-flags.h:405
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff812ee259)
Location: include/linux/page-flags.h:405
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
In mm/shmem.c (ffffffff8127c9cf)
Location: include/linux/page-flags.h:405
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
```
```
In mm/swap_state.c (ffffffff812cb51d)
Location: include/linux/page-flags.h:405
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff812f3d49)
Location: include/linux/page-flags.h:405
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
In mm/shmem.c (ffffffff812bab2f)
Location: include/linux/page-flags.h:419
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
```
```
In mm/swap_state.c (ffffffff813105b6)
Location: include/linux/page-flags.h:419
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff8133e6f5)
Location: include/linux/page-flags.h:419
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
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
In mm/shmem.c (ffffffff8131823f)
Location: include/linux/page-flags.h:572
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
```
```
In mm/swap_state.c (ffffffff8137b159)
Location: include/linux/page-flags.h:572
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
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
In mm/shmem.c (ffff8000102d3a2c)
Location: include/linux/page-flags.h:389
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/swap_state.c (ffff8000103213c0)
Location: include/linux/page-flags.h:389
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffff80001034f5e4)
Location: include/linux/page-flags.h:389
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
In mm/shmem.c (c04fbd2c)
Location: include/linux/page-flags.h:389
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/swap_state.c (c0539c58)
Location: include/linux/page-flags.h:389
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (c0551554)
Location: include/linux/page-flags.h:389
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
In mm/shmem.c (c000000000392c70)
Location: include/linux/page-flags.h:389
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/swap_state.c (c0000000003f6934)
Location: include/linux/page-flags.h:389
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (c000000000431aec)
Location: include/linux/page-flags.h:389
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
In mm/shmem.c (ffffffe0001efada)
Location: include/linux/page-flags.h:389
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/swap_state.c (ffffffe00022274a)
Location: include/linux/page-flags.h:389
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffe00023e5c8)
Location: include/linux/page-flags.h:389
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
In mm/shmem.c (ffffffff81239cc0)
Location: include/linux/page-flags.h:389
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/swap_state.c (ffffffff8127f19d)
Location: include/linux/page-flags.h:389
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff812a58a2)
Location: include/linux/page-flags.h:389
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
In mm/shmem.c (ffffffff8122ccd6)
Location: include/linux/page-flags.h:389
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/swap_state.c (ffffffff81270fbd)
Location: include/linux/page-flags.h:389
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff81297372)
Location: include/linux/page-flags.h:389
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
In mm/shmem.c (ffffffff81237a60)
Location: include/linux/page-flags.h:389
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/swap_state.c (ffffffff8127cf3d)
Location: include/linux/page-flags.h:389
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff812a36b2)
Location: include/linux/page-flags.h:389
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
In mm/shmem.c (ffffffff81246ff3)
Location: include/linux/page-flags.h:389
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/swap_state.c (ffffffff8128cafd)
Location: include/linux/page-flags.h:389
Inline: True
Inline callers:
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffffffff812b3ec2)
Location: include/linux/page-flags.h:389
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
</details>
</li>
</ul>

## Differences
