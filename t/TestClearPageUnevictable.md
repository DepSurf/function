# Function: <code>TestClearPageUnevictable</code>

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
In mm/mlock.c (ffffffff811c2f3d)
Location: include/linux/page-flags.h:266
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/migrate.c (ffffffff811f1c50)
Location: include/linux/page-flags.h:266
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_misplaced_transhuge_page
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
In mm/mlock.c (ffffffff811dec7f)
Location: include/linux/page-flags.h:324
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/migrate.c (ffffffff812132f6)
Location: include/linux/page-flags.h:324
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
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
In mm/mlock.c (ffffffff811eea9f)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/migrate.c (ffffffff8122565e)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
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
In mm/mlock.c (ffffffff811f9a7f)
Location: include/linux/page-flags.h:343
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/migrate.c (ffffffff81230fb1)
Location: include/linux/page-flags.h:343
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
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
In mm/mlock.c (ffffffff81211eb4)
Location: include/linux/page-flags.h:344
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/migrate.c (ffffffff8124edde)
Location: include/linux/page-flags.h:344
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
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
In mm/swap.c (ffffffff81201dd5)
Location: include/linux/page-flags.h:351
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/mlock.c (ffffffff81232bd4)
Location: include/linux/page-flags.h:351
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/migrate.c (ffffffff81272c96)
Location: include/linux/page-flags.h:351
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
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
In mm/swap.c (ffffffff81214755)
Location: include/linux/page-flags.h:363
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/mlock.c (ffffffff812463a6)
Location: include/linux/page-flags.h:363
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/migrate.c (ffffffff81287144)
Location: include/linux/page-flags.h:363
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
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
In mm/swap.c (ffffffff81224415)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/mlock.c (ffffffff812585e4)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/migrate.c (ffffffff812a1650)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
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
In mm/swap.c (ffffffff812321a5)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/mlock.c (ffffffff81266ab4)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/migrate.c (ffffffff812b2a57)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
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
In mm/swap.c (ffffffff8125f3f5)
Location: include/linux/page-flags.h:404
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/mlock.c (ffffffff8129670c)
Location: include/linux/page-flags.h:404
Inline: True
Inline callers:
  - mm/mlock.c:__putback_lru_fast_prepare
```
```
In mm/migrate.c (ffffffff812e7fce)
Location: include/linux/page-flags.h:404
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
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
In mm/swap.c (ffffffff812699f5)
Location: include/linux/page-flags.h:412
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/mlock.c (ffffffff812a168c)
Location: include/linux/page-flags.h:412
Inline: True
Inline callers:
  - mm/mlock.c:__putback_lru_fast_prepare
```
```
In mm/migrate.c (ffffffff812f3581)
Location: include/linux/page-flags.h:412
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
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
In mm/swap.c (ffffffff8126d7e5)
Location: include/linux/page-flags.h:412
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/mlock.c (ffffffff812a741c)
Location: include/linux/page-flags.h:412
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/migrate.c (ffffffff812f972c)
Location: include/linux/page-flags.h:412
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
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
In mm/swap.c (ffffffff812a9e55)
Location: include/linux/page-flags.h:426
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/mlock.c (ffffffff812e8a5c)
Location: include/linux/page-flags.h:426
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/migrate.c (ffffffff8133e691)
Location: include/linux/page-flags.h:426
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
</details>
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
In mm/swap.c (ffff8000102c1044)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/mlock.c (ffff8000102fdbd4)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/migrate.c (ffff80001035344c)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
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
In mm/swap.c (c04ed2f8)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/mlock.c (c051cee0)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/migrate.c (c0551390)
Location: include/linux/page-flags.h:396
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
In mm/swap.c (c00000000037c0a8)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/mlock.c (c0000000003c9154)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/migrate.c (c00000000043a270)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
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
In mm/swap.c (ffffffe0001e351c)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/mlock.c (ffffffe00020c252)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/migrate.c (ffffffe00023e572)
Location: include/linux/page-flags.h:396
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
In mm/swap.c (ffffffff8122a7f5)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/mlock.c (ffffffff8125f104)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/migrate.c (ffffffff812ab037)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
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
In mm/swap.c (ffffffff8121d915)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/mlock.c (ffffffff8125152e)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/migrate.c (ffffffff8129c94f)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
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
In mm/swap.c (ffffffff81228595)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/mlock.c (ffffffff8125cea4)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/migrate.c (ffffffff812a8e47)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
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
In mm/swap.c (ffffffff81237905)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/mlock.c (ffffffff8126c871)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/migrate.c (ffffffff812b9161)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page_states
```
</details>
</li>
</ul>

## Differences
