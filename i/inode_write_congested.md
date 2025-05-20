# Function: <code>inode_write_congested</code>

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
In mm/vmscan.c (ffffffff811a09de)
Location: include/linux/backing-dev.h:485
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/fadvise.c (ffffffff811d12ed)
Location: include/linux/backing-dev.h:485
Inline: True
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
In mm/vmscan.c (ffffffff811b96ec)
Location: include/linux/backing-dev.h:486
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/fadvise.c (ffffffff811ee48d)
Location: include/linux/backing-dev.h:486
Inline: True
Inline callers:
  - mm/fadvise.c:SyS_fadvise64
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
In mm/vmscan.c (ffffffff811c9d43)
Location: include/linux/backing-dev.h:486
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/fadvise.c (ffffffff811feddd)
Location: include/linux/backing-dev.h:486
Inline: True
Inline callers:
  - mm/fadvise.c:SyS_fadvise64
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
In mm/vmscan.c (ffffffff811d2783)
Location: include/linux/backing-dev.h:461
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/fadvise.c (ffffffff812099c5)
Location: include/linux/backing-dev.h:461
Inline: True
Inline callers:
  - mm/fadvise.c:SyS_fadvise64
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
In mm/vmscan.c (ffffffff811e7c87)
Location: include/linux/backing-dev.h:466
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/fadvise.c (ffffffff81222ad7)
Location: include/linux/backing-dev.h:466
Inline: True
Inline callers:
  - mm/fadvise.c:SyS_fadvise64
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
In mm/vmscan.c (ffffffff8120910f)
Location: include/linux/backing-dev.h:469
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/fadvise.c (ffffffff812447e8)
Location: include/linux/backing-dev.h:469
Inline: True
Inline callers:
  - mm/fadvise.c:ksys_fadvise64_64
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
In mm/fadvise.c (ffffffff8120619f)
Location: include/linux/backing-dev.h:469
Inline: True
Inline callers:
  - mm/fadvise.c:vfs_fadvise
```
```
In mm/vmscan.c (ffffffff8121bdef)
Location: include/linux/backing-dev.h:469
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
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
In mm/fadvise.c (ffffffff8121d4d0)
Location: include/linux/backing-dev.h:470
Inline: True
Inline callers:
  - mm/fadvise.c:vfs_fadvise
```
```
In mm/vmscan.c (ffffffff8122ba5b)
Location: include/linux/backing-dev.h:470
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
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
In mm/fadvise.c (ffffffff8122aec5)
Location: include/linux/backing-dev.h:476
Inline: True
Inline callers:
  - mm/fadvise.c:generic_fadvise
```
```
In mm/vmscan.c (ffffffff81239924)
Location: include/linux/backing-dev.h:476
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
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
In mm/fadvise.c (ffffffff81257c85)
Location: include/linux/backing-dev.h:472
Inline: True
Inline callers:
  - mm/fadvise.c:generic_fadvise
```
```
In mm/vmscan.c (ffffffff81266088)
Location: include/linux/backing-dev.h:472
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:pageout
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
In mm/fadvise.c (ffffffff8126253d)
Location: include/linux/backing-dev.h:400
Inline: True
Inline callers:
  - mm/fadvise.c:generic_fadvise
```
```
In mm/vmscan.c (ffffffff81270a36)
Location: include/linux/backing-dev.h:400
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:pageout
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
In mm/fadvise.c (ffffffff81266fd1)
Location: include/linux/backing-dev.h:400
Inline: True
Inline callers:
  - mm/fadvise.c:generic_fadvise
```
```
In mm/vmscan.c (ffffffff81275534)
Location: include/linux/backing-dev.h:400
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:pageout
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
In mm/fadvise.c (ffffffff812a3a18)
Location: include/linux/backing-dev.h:419
Inline: True
Inline callers:
  - mm/fadvise.c:generic_fadvise
```
```
In mm/vmscan.c (ffffffff812b3136)
Location: include/linux/backing-dev.h:419
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:pageout
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
In mm/fadvise.c (ffff8000102b9190)
Location: include/linux/backing-dev.h:476
Inline: True
Inline callers:
  - mm/fadvise.c:generic_fadvise
```
```
In mm/vmscan.c (ffff8000102ca810)
Location: include/linux/backing-dev.h:476
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
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
In mm/fadvise.c (c04e58e0)
Location: include/linux/backing-dev.h:476
Inline: True
Inline callers:
  - mm/fadvise.c:generic_fadvise
```
```
In mm/vmscan.c (c04f4d18)
Location: include/linux/backing-dev.h:476
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
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
In mm/fadvise.c (c000000000371300)
Location: include/linux/backing-dev.h:476
Inline: True
Inline callers:
  - mm/fadvise.c:generic_fadvise
```
```
In mm/vmscan.c (c0000000003873e4)
Location: include/linux/backing-dev.h:476
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
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
In mm/fadvise.c (ffffffe0001dcc8e)
Location: include/linux/backing-dev.h:476
Inline: True
Inline callers:
  - mm/fadvise.c:generic_fadvise
```
```
In mm/vmscan.c (ffffffe0001e9894)
Location: include/linux/backing-dev.h:476
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
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
In mm/fadvise.c (ffffffff81223515)
Location: include/linux/backing-dev.h:476
Inline: True
Inline callers:
  - mm/fadvise.c:generic_fadvise
```
```
In mm/vmscan.c (ffffffff81231f74)
Location: include/linux/backing-dev.h:476
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
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
In mm/fadvise.c (ffffffff812166c5)
Location: include/linux/backing-dev.h:476
Inline: True
Inline callers:
  - mm/fadvise.c:generic_fadvise
```
```
In mm/vmscan.c (ffffffff81225034)
Location: include/linux/backing-dev.h:476
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
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
In mm/fadvise.c (ffffffff812212b5)
Location: include/linux/backing-dev.h:476
Inline: True
Inline callers:
  - mm/fadvise.c:generic_fadvise
```
```
In mm/vmscan.c (ffffffff8122fd14)
Location: include/linux/backing-dev.h:476
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
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
In mm/fadvise.c (ffffffff81230473)
Location: include/linux/backing-dev.h:476
Inline: True
Inline callers:
  - mm/fadvise.c:generic_fadvise
```
```
In mm/vmscan.c (ffffffff8123f15a)
Location: include/linux/backing-dev.h:476
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
</details>
</li>
</ul>

## Differences
