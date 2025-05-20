# Function: <code>TestClearPageMlocked</code>

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
In mm/mlock.c (ffffffff811c2e3a)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:clear_page_mlock
  - mm/mlock.c:munlock_vma_page
```
```
In mm/migrate.c (ffffffff811f36ac)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
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
In mm/mlock.c (ffffffff811deaf9)
Location: include/linux/page-flags.h:329
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/migrate.c (ffffffff81213553)
Location: include/linux/page-flags.h:329
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
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
In mm/mlock.c (ffffffff811ee919)
Location: include/linux/page-flags.h:345
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/migrate.c (ffffffff812258b8)
Location: include/linux/page-flags.h:345
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
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
In mm/mlock.c (ffffffff811f9921)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/migrate.c (ffffffff81230c88)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
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
In mm/mlock.c (ffffffff81211d4d)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/migrate.c (ffffffff8124e9e2)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
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
In mm/mlock.c (ffffffff81232a78)
Location: include/linux/page-flags.h:356
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/migrate.c (ffffffff81272811)
Location: include/linux/page-flags.h:356
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
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
In mm/mlock.c (ffffffff81246248)
Location: include/linux/page-flags.h:368
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/migrate.c (ffffffff81286dc9)
Location: include/linux/page-flags.h:368
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
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
In mm/mlock.c (ffffffff81258483)
Location: include/linux/page-flags.h:401
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/migrate.c (ffffffff812a1358)
Location: include/linux/page-flags.h:401
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
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
In mm/mlock.c (ffffffff81266953)
Location: include/linux/page-flags.h:401
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/migrate.c (ffffffff812b2778)
Location: include/linux/page-flags.h:401
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
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
In mm/mlock.c (ffffffff81296be2)
Location: include/linux/page-flags.h:409
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/migrate.c (ffffffff812e7d17)
Location: include/linux/page-flags.h:409
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
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
In mm/mlock.c (ffffffff812a1a71)
Location: include/linux/page-flags.h:417
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/migrate.c (ffffffff812f3103)
Location: include/linux/page-flags.h:417
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
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
In mm/mlock.c (ffffffff812a722d)
Location: include/linux/page-flags.h:417
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/migrate.c (ffffffff812f949c)
Location: include/linux/page-flags.h:417
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff812e874a)
Location: include/linux/page-flags.h:431
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:clear_page_mlock
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
In mm/mlock.c (ffffffff8134a9a4)
Location: include/linux/page-flags.h:584
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_page
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
In mm/mlock.c (ffffffff813c3594)
Location: include/linux/page-flags.h:563
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_page
```
</details>
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
In mm/mlock.c (ffff8000102fd974)
Location: include/linux/page-flags.h:401
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/migrate.c (ffff800010352fd8)
Location: include/linux/page-flags.h:401
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mlock.c (c051cd0c)
Location: include/linux/page-flags.h:401
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:clear_page_mlock
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
In mm/mlock.c (c0000000003c8e88)
Location: include/linux/page-flags.h:401
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/migrate.c (c000000000439b7c)
Location: include/linux/page-flags.h:401
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffe00020c184)
Location: include/linux/page-flags.h:401
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:clear_page_mlock
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
In mm/mlock.c (ffffffff8125efa3)
Location: include/linux/page-flags.h:401
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/migrate.c (ffffffff812aad58)
Location: include/linux/page-flags.h:401
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
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
In mm/mlock.c (ffffffff812513d3)
Location: include/linux/page-flags.h:401
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/migrate.c (ffffffff8129c690)
Location: include/linux/page-flags.h:401
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
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
In mm/mlock.c (ffffffff8125cd43)
Location: include/linux/page-flags.h:401
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/migrate.c (ffffffff812a8b68)
Location: include/linux/page-flags.h:401
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
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
In mm/mlock.c (ffffffff8126c727)
Location: include/linux/page-flags.h:401
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
  - mm/mlock.c:clear_page_mlock
```
```
In mm/migrate.c (ffffffff812b8e88)
Location: include/linux/page-flags.h:401
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
</details>
</li>
</ul>

## Differences
