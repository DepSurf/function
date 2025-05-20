# Function: <code>ClearPageLRU</code>

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
In mm/vmscan.c (ffffffff811a269e)
Location: include/linux/page-flags.h:214
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
  - mm/vmscan.c:isolate_lru_page
```
```
In mm/mlock.c (ffffffff811c2cde)
Location: include/linux/page-flags.h:214
Inline: True
```
```
In mm/memcontrol.c (ffffffff811fece9)
Location: include/linux/page-flags.h:214
Inline: True
Inline callers:
  - mm/memcontrol.c:lock_page_lru
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
In mm/vmscan.c (ffffffff811b8f47)
Location: include/linux/page-flags.h:262
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/mlock.c (ffffffff811de886)
Location: include/linux/page-flags.h:262
Inline: True
```
```
In mm/memcontrol.c (ffffffff8122481f)
Location: include/linux/page-flags.h:262
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
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
In mm/vmscan.c (ffffffff811c9587)
Location: include/linux/page-flags.h:272
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/mlock.c (ffffffff811ee6a6)
Location: include/linux/page-flags.h:272
Inline: True
```
```
In mm/memcontrol.c (ffffffff81236e08)
Location: include/linux/page-flags.h:272
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
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
In mm/vmscan.c (ffffffff811d204f)
Location: include/linux/page-flags.h:272
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/mlock.c (ffffffff811f9646)
Location: include/linux/page-flags.h:272
Inline: True
```
```
In mm/memcontrol.c (ffffffff812428b9)
Location: include/linux/page-flags.h:272
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
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
In mm/vmscan.c (ffffffff811e74ef)
Location: include/linux/page-flags.h:273
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/mlock.c (ffffffff81211a76)
Location: include/linux/page-flags.h:273
Inline: True
```
```
In mm/memcontrol.c (ffffffff812626f9)
Location: include/linux/page-flags.h:273
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
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
In mm/vmscan.c (ffffffff81208a8e)
Location: include/linux/page-flags.h:280
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/mlock.c (ffffffff812327d5)
Location: include/linux/page-flags.h:280
Inline: True
```
```
In mm/memcontrol.c (ffffffff812868b9)
Location: include/linux/page-flags.h:280
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
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
In mm/vmscan.c (ffffffff8121b72e)
Location: include/linux/page-flags.h:289
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/mlock.c (ffffffff81246015)
Location: include/linux/page-flags.h:289
Inline: True
```
```
In mm/memcontrol.c (ffffffff8129b844)
Location: include/linux/page-flags.h:289
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
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
In mm/vmscan.c (ffffffff8122b3cb)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/mlock.c (ffffffff8125821c)
Location: include/linux/page-flags.h:320
Inline: True
```
```
In mm/memcontrol.c (ffffffff812b6995)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
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
In mm/vmscan.c (ffffffff8123929b)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/mlock.c (ffffffff812666ec)
Location: include/linux/page-flags.h:320
Inline: True
```
```
In mm/memcontrol.c (ffffffff812c8865)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
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
In mm/vmscan.c (ffffffff81269f7c)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/mlock.c (ffffffff812967bc)
Location: include/linux/page-flags.h:328
Inline: True
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
In mm/vmscan.c (ffff8000102ca128)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/mlock.c (ffff8000102fd764)
Location: include/linux/page-flags.h:320
Inline: True
```
```
In mm/memcontrol.c (ffff80001036b7a0)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
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
In mm/vmscan.c (c04f4000)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/mlock.c (c051cb00)
Location: include/linux/page-flags.h:320
Inline: True
```
```
In mm/memcontrol.c (c055ce7c)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
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
In mm/vmscan.c (c0000000003869a0)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/mlock.c (c0000000003c8a2c)
Location: include/linux/page-flags.h:320
Inline: True
```
```
In mm/memcontrol.c (c00000000045b2f0)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
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
In mm/vmscan.c (ffffffe0001e928e)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/mlock.c (ffffffe00020bfde)
Location: include/linux/page-flags.h:320
Inline: True
```
```
In mm/memcontrol.c (ffffffe000248e46)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
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
In mm/vmscan.c (ffffffff812318eb)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/mlock.c (ffffffff8125ed3c)
Location: include/linux/page-flags.h:320
Inline: True
```
```
In mm/memcontrol.c (ffffffff812c0e45)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
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
In mm/vmscan.c (ffffffff812249ab)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/mlock.c (ffffffff8125116c)
Location: include/linux/page-flags.h:320
Inline: True
```
```
In mm/memcontrol.c (ffffffff812b1e99)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
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
In mm/vmscan.c (ffffffff8122f68b)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/mlock.c (ffffffff8125cadc)
Location: include/linux/page-flags.h:320
Inline: True
```
```
In mm/memcontrol.c (ffffffff812bec55)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
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
In mm/vmscan.c (ffffffff8123eabc)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/mlock.c (ffffffff8126c4bc)
Location: include/linux/page-flags.h:320
Inline: True
```
```
In mm/memcontrol.c (ffffffff812cf6d5)
Location: include/linux/page-flags.h:320
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
</details>
</li>
</ul>

## Differences
