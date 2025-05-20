# Function: <code>__ClearPageActive</code>

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
In mm/swap.c (ffffffff8119ca45)
Location: include/linux/page-flags.h:215
Inline: True
Inline callers:
  - mm/swap.c:__page_cache_release
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
```
```
In mm/vmscan.c (ffffffff811a22be)
Location: include/linux/page-flags.h:215
Inline: True
Inline callers:
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
```
```
In mm/slub.c (ffffffff811e9105)
Location: include/linux/page-flags.h:215
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
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
In mm/swap.c (ffffffff811b2cee)
Location: include/linux/page-flags.h:263
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff811b7d8f)
Location: include/linux/page-flags.h:263
Inline: True
Inline callers:
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
```
```
In mm/slub.c (ffffffff81208bf8)
Location: include/linux/page-flags.h:263
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
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
In mm/swap.c (ffffffff811c3360)
Location: include/linux/page-flags.h:273
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff811c83dd)
Location: include/linux/page-flags.h:273
Inline: True
Inline callers:
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
```
```
In mm/slub.c (ffffffff8121ac74)
Location: include/linux/page-flags.h:273
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
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
In mm/swap.c (ffffffff811cb7dd)
Location: include/linux/page-flags.h:273
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff811d0d87)
Location: include/linux/page-flags.h:273
Inline: True
Inline callers:
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
```
```
In mm/slub.c (ffffffff812266d7)
Location: include/linux/page-flags.h:273
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
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
In kernel/memremap.c (ffffffff811c92ae)
Location: include/linux/page-flags.h:274
Inline: True
```
```
In mm/swap.c (ffffffff811e0bcd)
Location: include/linux/page-flags.h:274
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff811e6277)
Location: include/linux/page-flags.h:274
Inline: True
Inline callers:
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
```
```
In mm/slub.c (ffffffff8124171f)
Location: include/linux/page-flags.h:274
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
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
In kernel/memremap.c (ffffffff811e93ce)
Location: include/linux/page-flags.h:281
Inline: True
```
```
In mm/swap.c (ffffffff8120244b)
Location: include/linux/page-flags.h:281
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff812077e8)
Location: include/linux/page-flags.h:281
Inline: True
Inline callers:
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
```
```
In mm/slub.c (ffffffff81265352)
Location: include/linux/page-flags.h:281
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
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
In kernel/memremap.c (ffffffff811f9fae)
Location: include/linux/page-flags.h:290
Inline: True
```
```
In mm/swap.c (ffffffff81214dd0)
Location: include/linux/page-flags.h:290
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8121a368)
Location: include/linux/page-flags.h:290
Inline: True
Inline callers:
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
```
```
In mm/slub.c (ffffffff8127a084)
Location: include/linux/page-flags.h:290
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
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
In mm/swap.c (ffffffff8122409f)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8122c6fe)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/slub.c (ffffffff812958f4)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
```
```
In mm/memremap.c (ffffffff812c2401)
Location: include/linux/page-flags.h:321
Inline: True
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
In mm/swap.c (ffffffff81231e2f)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8123a91e)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/slub.c (ffffffff812a56d4)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
```
```
In mm/memremap.c (ffffffff812d4331)
Location: include/linux/page-flags.h:321
Inline: True
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
In mm/swap.c (ffffffff8125ea19)
Location: include/linux/page-flags.h:329
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff81265399)
Location: include/linux/page-flags.h:329
Inline: True
```
```
In mm/slub.c (ffffffff812da2ee)
Location: include/linux/page-flags.h:329
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
```
```
In mm/memremap.c (ffffffff8130aa5a)
Location: include/linux/page-flags.h:329
Inline: True
Inline callers:
  - mm/memremap.c:free_devmap_managed_page
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
In mm/swap.c (ffffffff81268ade)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8127005e)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/slub.c (ffffffff812e6cbb)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
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
In mm/swap.c (ffffffff8126e86a)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff812750e9)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/slub.c (ffffffff812ee4ab)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
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
In mm/swap.c (ffffffff812ab87b)
Location: include/linux/page-flags.h:352
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff812b23c1)
Location: include/linux/page-flags.h:352
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/slub.c (ffffffff813366d9)
Location: include/linux/page-flags.h:352
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
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
In mm/swap.c (ffff8000102c1b00)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffff8000102cb874)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/slub.c (ffff800010346524)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
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
In mm/swap.c (c04ecd98)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (c04f5710)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/slub.c (c054b120)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
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
In mm/swap.c (c00000000037b950)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (c0000000003889ec)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/slub.c (c00000000042449c)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
```
```
In mm/memremap.c (c00000000046d950)
Location: include/linux/page-flags.h:321
Inline: True
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
In mm/swap.c (ffffffe0001e2ede)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffe0001ea53c)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/slub.c (ffffffe000239416)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
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
In mm/swap.c (ffffffff8122a47f)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff81232f6e)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/slub.c (ffffffff8129dcb4)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
```
```
In mm/memremap.c (ffffffff812cc911)
Location: include/linux/page-flags.h:321
Inline: True
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
In mm/swap.c (ffffffff8121d59f)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8122600e)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/slub.c (ffffffff8128f844)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
```
```
In mm/memremap.c (ffffffff812bd781)
Location: include/linux/page-flags.h:321
Inline: True
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
In mm/swap.c (ffffffff8122821f)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff81230d0e)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/slub.c (ffffffff8129bac4)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
```
```
In mm/memremap.c (ffffffff812ca721)
Location: include/linux/page-flags.h:321
Inline: True
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
In mm/swap.c (ffffffff8123755f)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:release_pages
  - mm/swap.c:__page_cache_release
```
```
In mm/vmscan.c (ffffffff8124015e)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/slub.c (ffffffff812ab9a4)
Location: include/linux/page-flags.h:321
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
```
```
In mm/memremap.c (ffffffff812db421)
Location: include/linux/page-flags.h:321
Inline: True
```
</details>
</li>
</ul>

## Differences
