# Function: <code>blkcg_schedule_throttle</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
void blkcg_schedule_throttle(struct request_queue *q, bool use_memdelay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814c3410)
Location: block/blk-cgroup.c:1754
Inline: False
Direct callers:
  - mm/swapfile.c:mem_cgroup_throttle_swaprate
```
**Symbols:**

```
ffffffff814c3410-ffffffff814c3496: blkcg_schedule_throttle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blkcg_schedule_throttle(struct request_queue *q, bool use_memdelay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814f1b10)
Location: block/blk-cgroup.c:1740
Inline: False
Direct callers:
  - mm/swapfile.c:mem_cgroup_throttle_swaprate
```
**Symbols:**

```
ffffffff814f1b10-ffffffff814f1b96: blkcg_schedule_throttle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blkcg_schedule_throttle(struct request_queue *q, bool use_memdelay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff8150b0f0)
Location: block/blk-cgroup.c:1803
Inline: False
Direct callers:
  - mm/swapfile.c:mem_cgroup_throttle_swaprate
  - block/blk-iocost.c:ioc_rqos_throttle
```
**Symbols:**

```
ffffffff8150b0f0-ffffffff8150b176: blkcg_schedule_throttle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blkcg_schedule_throttle(struct request_queue *q, bool use_memdelay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff8156c050)
Location: block/blk-cgroup.c:1699
Inline: False
Direct callers:
  - mm/swapfile.c:cgroup_throttle_swaprate
  - block/blk-iocost.c:ioc_rqos_throttle
```
**Symbols:**

```
ffffffff8156c050-ffffffff8156c0d6: blkcg_schedule_throttle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blkcg_schedule_throttle(struct request_queue *q, bool use_memdelay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81586d80)
Location: block/blk-cgroup.c:1763
Inline: False
Direct callers:
  - mm/swapfile.c:cgroup_throttle_swaprate
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
```
**Symbols:**

```
ffffffff81586d80-ffffffff81586e06: blkcg_schedule_throttle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blkcg_schedule_throttle(struct request_queue *q, bool use_memdelay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff8158dbb0)
Location: block/blk-cgroup.c:1768
Inline: False
Direct callers:
  - mm/swapfile.c:cgroup_throttle_swaprate
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
```
**Symbols:**

```
ffffffff8158dbb0-ffffffff8158dc45: blkcg_schedule_throttle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blkcg_schedule_throttle(struct request_queue *q, bool use_memdelay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff815f3620)
Location: block/blk-cgroup.c:1762
Inline: False
Direct callers:
  - mm/swapfile.c:__cgroup_throttle_swaprate
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
```
**Symbols:**

```
ffffffff815f3620-ffffffff815f36b5: blkcg_schedule_throttle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void blkcg_schedule_throttle(struct request_queue *q, bool use_memdelay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff816a4c30)
Location: block/blk-cgroup.c:1850
Inline: False
Direct callers:
  - mm/swapfile.c:__cgroup_throttle_swaprate
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
```
**Symbols:**

```
ffffffff816a4c30-ffffffff816a4cd9: blkcg_schedule_throttle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blkcg_schedule_throttle(struct gendisk *disk, bool use_memdelay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff817639d0)
Location: block/blk-cgroup.c:1855
Inline: False
Direct callers:
  - mm/swapfile.c:__cgroup_throttle_swaprate
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
```
**Symbols:**

```
ffffffff817639d0-ffffffff81763a7f: blkcg_schedule_throttle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blkcg_schedule_throttle(struct gendisk *disk, bool use_memdelay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff817a2a60)
Location: block/blk-cgroup.c:1947
Inline: False
Direct callers:
  - mm/swapfile.c:__folio_throttle_swaprate
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
```
**Symbols:**

```
ffffffff817a2a60-ffffffff817a2b1b: blkcg_schedule_throttle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blkcg_schedule_throttle(struct gendisk *disk, bool use_memdelay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff817e65a0)
Location: block/blk-cgroup.c:1960
Inline: False
Direct callers:
  - mm/swapfile.c:__folio_throttle_swaprate
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
```
**Symbols:**

```
ffffffff817e65a0-ffffffff817e665b: blkcg_schedule_throttle (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void blkcg_schedule_throttle(struct request_queue *q, bool use_memdelay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffff80001060ea80)
Location: block/blk-cgroup.c:1803
Inline: False
Direct callers:
  - mm/swapfile.c:mem_cgroup_throttle_swaprate
  - block/blk-iocost.c:ioc_rqos_throttle
```
**Symbols:**

```
ffff80001060ea80-ffff80001060eb48: blkcg_schedule_throttle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blkcg_schedule_throttle(struct request_queue *q, bool use_memdelay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (c07b92f4)
Location: block/blk-cgroup.c:1803
Inline: False
Direct callers:
  - mm/swapfile.c:mem_cgroup_throttle_swaprate
  - block/blk-iocost.c:ioc_rqos_throttle
```
**Symbols:**

```
c07b92f4-c07b93a0: blkcg_schedule_throttle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blkcg_schedule_throttle(struct request_queue *q, bool use_memdelay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (c0000000007ac0a0)
Location: block/blk-cgroup.c:1803
Inline: False
Direct callers:
  - mm/swapfile.c:mem_cgroup_throttle_swaprate
  - block/blk-iocost.c:ioc_rqos_throttle
```
**Symbols:**

```
c0000000007ac0a0-c0000000007ac194: blkcg_schedule_throttle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blkcg_schedule_throttle(struct request_queue *q, bool use_memdelay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffe000446e76)
Location: block/blk-cgroup.c:1803
Inline: False
Direct callers:
  - mm/swapfile.c:mem_cgroup_throttle_swaprate
  - block/blk-iocost.c:ioc_rqos_throttle
```
**Symbols:**

```
ffffffe000446e76-ffffffe000446efe: blkcg_schedule_throttle (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void blkcg_schedule_throttle(struct request_queue *q, bool use_memdelay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff815036d0)
Location: block/blk-cgroup.c:1803
Inline: False
Direct callers:
  - mm/swapfile.c:mem_cgroup_throttle_swaprate
  - block/blk-iocost.c:ioc_rqos_throttle
```
**Symbols:**

```
ffffffff815036d0-ffffffff81503756: blkcg_schedule_throttle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blkcg_schedule_throttle(struct request_queue *q, bool use_memdelay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814f3b90)
Location: block/blk-cgroup.c:1803
Inline: False
Direct callers:
  - mm/swapfile.c:mem_cgroup_throttle_swaprate
  - block/blk-iocost.c:ioc_rqos_throttle
```
**Symbols:**

```
ffffffff814f3b90-ffffffff814f3c16: blkcg_schedule_throttle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blkcg_schedule_throttle(struct request_queue *q, bool use_memdelay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814ff760)
Location: block/blk-cgroup.c:1803
Inline: False
Direct callers:
  - mm/swapfile.c:mem_cgroup_throttle_swaprate
  - block/blk-iocost.c:ioc_rqos_throttle
```
**Symbols:**

```
ffffffff814ff760-ffffffff814ff7e6: blkcg_schedule_throttle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blkcg_schedule_throttle(struct request_queue *q, bool use_memdelay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81518930)
Location: block/blk-cgroup.c:1803
Inline: False
Direct callers:
  - mm/swapfile.c:mem_cgroup_throttle_swaprate
  - block/blk-iocost.c:ioc_rqos_throttle
```
**Symbols:**

```
ffffffff81518930-ffffffff815189b6: blkcg_schedule_throttle (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct gendisk *disk</code>
</li>
<li>
<b>Param removed. </b>
<code>struct request_queue *q</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
