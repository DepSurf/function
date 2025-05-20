# Function: <code>free_mm_slot</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff811e51e9)
Location: mm/ksm.c:316
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:__ksm_exit
```
```
In mm/huge_memory.c (ffffffff811f435a)
Location: mm/huge_memory.c:2066
Inline: True
Inline callers:
  - mm/huge_memory.c:collect_mm_slot
  - mm/huge_memory.c:__khugepaged_enter
  - mm/huge_memory.c:__khugepaged_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81203d78)
Location: mm/ksm.c:317
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff8121973a)
Location: mm/khugepaged.c:367
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
  - mm/khugepaged.c:__khugepaged_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81215d98)
Location: mm/ksm.c:328
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff8122bcba)
Location: mm/khugepaged.c:369
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
  - mm/khugepaged.c:__khugepaged_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff8122148e)
Location: mm/ksm.c:400
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff812377e6)
Location: mm/khugepaged.c:371
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
  - mm/khugepaged.c:__khugepaged_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff8123c79e)
Location: mm/ksm.c:400
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff81256b76)
Location: mm/khugepaged.c:372
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
  - mm/khugepaged.c:__khugepaged_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff8125fd2f)
Location: mm/ksm.c:419
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff8127ab46)
Location: mm/khugepaged.c:372
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
  - mm/khugepaged.c:__khugepaged_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff8127446f)
Location: mm/ksm.c:420
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff8128f156)
Location: mm/khugepaged.c:372
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
  - mm/khugepaged.c:__khugepaged_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812905dd)
Location: mm/ksm.c:419
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff812a9a1e)
Location: mm/khugepaged.c:372
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
  - mm/khugepaged.c:__khugepaged_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812a035d)
Location: mm/ksm.c:419
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff812baf8e)
Location: mm/khugepaged.c:379
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
  - mm/khugepaged.c:__khugepaged_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812d6bf2)
Location: mm/ksm.c:419
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
```
```
In mm/khugepaged.c (ffffffff812efe4f)
Location: mm/khugepaged.c:409
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
  - mm/khugepaged.c:__khugepaged_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812e2745)
Location: mm/ksm.c:419
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
```
```
In mm/khugepaged.c (ffffffff812fb60e)
Location: mm/khugepaged.c:414
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
  - mm/khugepaged.c:__khugepaged_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812e9ed2)
Location: mm/ksm.c:417
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
```
```
In mm/khugepaged.c (ffffffff813023de)
Location: mm/khugepaged.c:414
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
  - mm/khugepaged.c:__khugepaged_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81331df9)
Location: mm/ksm.c:417
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
```
```
In mm/khugepaged.c (ffffffff8134c14e)
Location: mm/khugepaged.c:414
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
  - mm/khugepaged.c:__khugepaged_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff813a3019)
Location: mm/ksm.c:418
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
```
```
In mm/khugepaged.c (ffffffff813c37f4)
Location: mm/khugepaged.c:412
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
  - mm/khugepaged.c:__khugepaged_enter
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
<summary>In <code>arm64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffff80001033fb88)
Location: mm/ksm.c:419
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffff80001035c6e8)
Location: mm/khugepaged.c:379
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
  - mm/khugepaged.c:__khugepaged_enter
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
In mm/ksm.c (c0545ea8)
Location: mm/ksm.c:419
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_do_scan
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/ksm.c (c00000000041c448)
Location: mm/ksm.c:419
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
```
```
In mm/khugepaged.c (c000000000445e58)
Location: mm/khugepaged.c:379
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
  - mm/khugepaged.c:__khugepaged_enter
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
In mm/ksm.c (ffffffe000234434)
Location: mm/ksm.c:419
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_do_scan
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff8129893d)
Location: mm/ksm.c:419
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff812b356e)
Location: mm/khugepaged.c:379
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
  - mm/khugepaged.c:__khugepaged_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff8128a4fd)
Location: mm/ksm.c:419
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff812a48ee)
Location: mm/khugepaged.c:379
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
  - mm/khugepaged.c:__khugepaged_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff8129674d)
Location: mm/ksm.c:419
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff812b137e)
Location: mm/khugepaged.c:379
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
  - mm/khugepaged.c:__khugepaged_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812a6537)
Location: mm/ksm.c:419
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff812c16be)
Location: mm/khugepaged.c:379
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
  - mm/khugepaged.c:__khugepaged_enter
```
</details>
</li>
</ul>

## Differences
