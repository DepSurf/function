# Function: <code>ClearPageUnevictable</code>

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
In mm/vmscan.c (ffffffff811a2cdf)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/vmscan.c:putback_lru_page
  - mm/vmscan.c:check_move_unevictable_pages
```
```
In mm/memory-failure.c (ffffffff81201915)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/memory-failure.c:delete_from_lru_cache
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
In mm/vmscan.c (ffffffff811bcaa5)
Location: include/linux/page-flags.h:322
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:putback_lru_page
```
```
In mm/migrate.c (ffffffff812120e2)
Location: include/linux/page-flags.h:322
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/khugepaged.c (ffffffff8121b142)
Location: include/linux/page-flags.h:322
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memory-failure.c (ffffffff8122664d)
Location: include/linux/page-flags.h:322
Inline: True
Inline callers:
  - mm/memory-failure.c:delete_from_lru_cache
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
In mm/vmscan.c (ffffffff811cd178)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:putback_lru_page
```
```
In mm/migrate.c (ffffffff8122425b)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/khugepaged.c (ffffffff8122c856)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memory-failure.c (ffffffff81238c1d)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - mm/memory-failure.c:delete_from_lru_cache
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
In mm/vmscan.c (ffffffff811d5e95)
Location: include/linux/page-flags.h:341
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:putback_lru_page
```
```
In mm/migrate.c (ffffffff8122f972)
Location: include/linux/page-flags.h:341
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/khugepaged.c (ffffffff81239061)
Location: include/linux/page-flags.h:341
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memory-failure.c (ffffffff8124507d)
Location: include/linux/page-flags.h:341
Inline: True
Inline callers:
  - mm/memory-failure.c:delete_from_lru_cache
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
In mm/vmscan.c (ffffffff811eb3b5)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:putback_lru_page
```
```
In mm/migrate.c (ffffffff8124d614)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/khugepaged.c (ffffffff81257766)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memory-failure.c (ffffffff81264f71)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/memory-failure.c:delete_from_lru_cache
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
In mm/vmscan.c (ffffffff8120cb8c)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
```
```
In mm/migrate.c (ffffffff8127112c)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/khugepaged.c (ffffffff8127b8c6)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memory-failure.c (ffffffff81289291)
Location: include/linux/page-flags.h:349
Inline: True
Inline callers:
  - mm/memory-failure.c:delete_from_lru_cache
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
In mm/vmscan.c (ffffffff8121fa4c)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
```
```
In mm/migrate.c (ffffffff81285738)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/khugepaged.c (ffffffff8128fcc5)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memory-failure.c (ffffffff8129e1e1)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - mm/memory-failure.c:delete_from_lru_cache
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
In mm/vmscan.c (ffffffff8122f1c1)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
```
```
In mm/migrate.c (ffffffff8129fdea)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/khugepaged.c (ffffffff812aad63)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memory-failure.c (ffffffff812b93a4)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/memory-failure.c:delete_from_lru_cache
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
In mm/vmscan.c (ffffffff8123d351)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
```
```
In mm/migrate.c (ffffffff812b118a)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/khugepaged.c (ffffffff812bc334)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memory-failure.c (ffffffff812cb294)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/memory-failure.c:delete_from_lru_cache
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
In mm/vmscan.c (ffffffff81265917)
Location: include/linux/page-flags.h:402
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
```
```
In mm/migrate.c (ffffffff812e65e1)
Location: include/linux/page-flags.h:402
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move
```
```
In mm/khugepaged.c (ffffffff812f1870)
Location: include/linux/page-flags.h:402
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memory-failure.c (ffffffff813015a4)
Location: include/linux/page-flags.h:402
Inline: True
Inline callers:
  - mm/memory-failure.c:delete_from_lru_cache
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
In mm/vmscan.c (ffffffff812702f3)
Location: include/linux/page-flags.h:410
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
```
```
In mm/migrate.c (ffffffff812f19f5)
Location: include/linux/page-flags.h:410
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move
```
```
In mm/khugepaged.c (ffffffff812fddc5)
Location: include/linux/page-flags.h:410
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memory-failure.c (ffffffff8130d674)
Location: include/linux/page-flags.h:410
Inline: True
Inline callers:
  - mm/memory-failure.c:delete_from_lru_cache
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
In mm/vmscan.c (ffffffff812761d3)
Location: include/linux/page-flags.h:410
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
```
```
In mm/migrate.c (ffffffff812f7d82)
Location: include/linux/page-flags.h:410
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move
```
```
In mm/khugepaged.c (ffffffff81304f34)
Location: include/linux/page-flags.h:410
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memory-failure.c (ffffffff813139b4)
Location: include/linux/page-flags.h:410
Inline: True
Inline callers:
  - mm/memory-failure.c:delete_from_lru_cache
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
In mm/vmscan.c (ffffffff812b284a)
Location: include/linux/page-flags.h:424
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
```
```
In mm/migrate.c (ffffffff813423f2)
Location: include/linux/page-flags.h:424
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move
```
```
In mm/khugepaged.c (ffffffff8134ecc7)
Location: include/linux/page-flags.h:424
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memory-failure.c (ffffffff8135eca4)
Location: include/linux/page-flags.h:424
Inline: True
Inline callers:
  - mm/memory-failure.c:delete_from_lru_cache
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
In mm/vmscan.c (ffffffff8130f596)
Location: include/linux/page-flags.h:577
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
```
```
In mm/mlock.c (ffffffff8134ad97)
Location: include/linux/page-flags.h:577
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__mlock_page
```
```
In mm/migrate.c (ffffffff813b4646)
Location: include/linux/page-flags.h:577
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move
```
```
In mm/khugepaged.c (ffffffff813c58fc)
Location: include/linux/page-flags.h:577
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memory-failure.c (ffffffff813d92a4)
Location: include/linux/page-flags.h:577
Inline: True
Inline callers:
  - mm/memory-failure.c:delete_from_lru_cache
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
In mm/mlock.c (ffffffff813c39ad)
Location: include/linux/page-flags.h:556
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__mlock_page
```
```
In mm/khugepaged.c (ffffffff8144a25e)
Location: include/linux/page-flags.h:556
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memory-failure.c (ffffffff8145f564)
Location: include/linux/page-flags.h:556
Inline: True
Inline callers:
  - mm/memory-failure.c:delete_from_lru_cache
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
In mm/khugepaged.c (ffffffff8148049f)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memory-failure.c (ffffffff8149577f)
Location: include/linux/page-flags.h:550
Inline: True
Inline callers:
  - mm/memory-failure.c:delete_from_lru_cache
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff814ae5af)
Location: include/linux/page-flags.h:552
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
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
In mm/vmscan.c (ffff8000102ce790)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
```
```
In mm/migrate.c (ffff80001035174c)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/khugepaged.c (ffff80001035d4b8)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memory-failure.c (ffff80001036e6cc)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/memory-failure.c:delete_from_lru_cache
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
In mm/vmscan.c (c04f8548)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
```
```
In mm/migrate.c (c0552c28)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
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
In mm/vmscan.c (c00000000038c580)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
```
```
In mm/migrate.c (c000000000437cf4)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/khugepaged.c (c000000000448fb8)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memory-failure.c (c00000000045fadc)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/memory-failure.c:delete_from_lru_cache
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
In mm/vmscan.c (ffffffe0001ec7fc)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
```
```
In mm/migrate.c (ffffffe00023fb00)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
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
In mm/vmscan.c (ffffffff812359a1)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
```
```
In mm/migrate.c (ffffffff812a976a)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/khugepaged.c (ffffffff812b4914)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memory-failure.c (ffffffff812c3874)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/memory-failure.c:delete_from_lru_cache
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
In mm/vmscan.c (ffffffff81228a0b)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
```
```
In mm/migrate.c (ffffffff8129b0ca)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/khugepaged.c (ffffffff812a5975)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memory-failure.c (ffffffff812b48b4)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/memory-failure.c:delete_from_lru_cache
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
In mm/vmscan.c (ffffffff81233741)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
```
```
In mm/migrate.c (ffffffff812a757a)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/khugepaged.c (ffffffff812b2724)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memory-failure.c (ffffffff812c1684)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/memory-failure.c:delete_from_lru_cache
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
In mm/vmscan.c (ffffffff81242c78)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
```
```
In mm/migrate.c (ffffffff812b7880)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/khugepaged.c (ffffffff812c2df7)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memory-failure.c (ffffffff812d2144)
Location: include/linux/page-flags.h:394
Inline: True
Inline callers:
  - mm/memory-failure.c:delete_from_lru_cache
```
</details>
</li>
</ul>

## Differences
