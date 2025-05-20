# Function: <code>bdi_congested</code>

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
In mm/vmscan.c (ffffffff811a051e)
Location: include/linux/backing-dev.h:496
Inline: True
```
```
In drivers/md/dm-table.c (ffffffff816a7116)
Location: include/linux/backing-dev.h:496
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_any_congested
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
In mm/vmscan.c (ffffffff811b68ee)
Location: include/linux/backing-dev.h:497
Inline: True
```
```
In drivers/md/dm-table.c (ffffffff81707456)
Location: include/linux/backing-dev.h:497
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_any_congested
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
In mm/vmscan.c (ffffffff811c6e9e)
Location: include/linux/backing-dev.h:497
Inline: True
```
```
In drivers/md/dm-table.c (ffffffff81739326)
Location: include/linux/backing-dev.h:497
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_any_congested
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
In mm/vmscan.c (ffffffff811cf63e)
Location: include/linux/backing-dev.h:472
Inline: True
```
```
In drivers/md/dm-table.c (ffffffff81752bd6)
Location: include/linux/backing-dev.h:472
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_any_congested
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
In mm/vmscan.c (ffffffff811e49ee)
Location: include/linux/backing-dev.h:477
Inline: True
```
```
In drivers/md/dm-table.c (ffffffff817c4e16)
Location: include/linux/backing-dev.h:477
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_any_congested
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
In mm/vmscan.c (ffffffff8120b662)
Location: include/linux/backing-dev.h:480
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
```
```
In drivers/md/dm-table.c (ffffffff8180d9eb)
Location: include/linux/backing-dev.h:480
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_any_congested
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
In mm/vmscan.c (ffffffff8121e33d)
Location: include/linux/backing-dev.h:480
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
```
```
In drivers/md/dm-table.c (ffffffff81839938)
Location: include/linux/backing-dev.h:480
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_any_congested
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
In mm/vmscan.c (ffffffff8122d9cb)
Location: include/linux/backing-dev.h:481
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
```
```
In drivers/md/dm-table.c (ffffffff8187c478)
Location: include/linux/backing-dev.h:481
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_any_congested
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
In mm/vmscan.c (ffffffff8123bb81)
Location: include/linux/backing-dev.h:487
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
```
```
In drivers/md/dm-table.c (ffffffff818ae258)
Location: include/linux/backing-dev.h:487
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_any_congested
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
In mm/vmscan.c (ffffffff81268dce)
Location: include/linux/backing-dev.h:483
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
```
```
In drivers/md/dm-table.c (ffffffff8197e4b8)
Location: include/linux/backing-dev.h:483
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_any_congested
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8127374e)
Location: include/linux/backing-dev.h:411
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81278a6e)
Location: include/linux/backing-dev.h:411
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
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
In mm/vmscan.c (ffffffff812b67d2)
Location: include/linux/backing-dev.h:430
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
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
In mm/vmscan.c (ffff8000102ccc60)
Location: include/linux/backing-dev.h:487
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
```
```
In drivers/md/dm-table.c (ffff800010b04d40)
Location: include/linux/backing-dev.h:487
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_any_congested
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
In mm/vmscan.c (c04f6a84)
Location: include/linux/backing-dev.h:487
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
```
```
In drivers/md/dm-table.c (c0be3cec)
Location: include/linux/backing-dev.h:487
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_any_congested
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
In mm/vmscan.c (c00000000038a4c4)
Location: include/linux/backing-dev.h:487
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
```
```
In drivers/md/dm-table.c (c000000000bf4a14)
Location: include/linux/backing-dev.h:487
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_any_congested
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
In mm/vmscan.c (ffffffe0001eb622)
Location: include/linux/backing-dev.h:487
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
```
```
In drivers/md/dm-table.c (ffffffe0006f3e1e)
Location: include/linux/backing-dev.h:487
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_any_congested
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
In mm/vmscan.c (ffffffff812341d1)
Location: include/linux/backing-dev.h:487
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
```
```
In drivers/md/dm-table.c (ffffffff818540d8)
Location: include/linux/backing-dev.h:487
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_any_congested
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
In mm/vmscan.c (ffffffff81227241)
Location: include/linux/backing-dev.h:487
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
```
```
In drivers/md/dm-table.c (ffffffff8181b6e8)
Location: include/linux/backing-dev.h:487
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_any_congested
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
In mm/vmscan.c (ffffffff81231f71)
Location: include/linux/backing-dev.h:487
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
```
```
In drivers/md/dm-table.c (ffffffff818a3708)
Location: include/linux/backing-dev.h:487
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_any_congested
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
In mm/vmscan.c (ffffffff812413d1)
Location: include/linux/backing-dev.h:487
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
```
```
In drivers/md/dm-table.c (ffffffff818bf948)
Location: include/linux/backing-dev.h:487
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_any_congested
```
</details>
</li>
</ul>

## Differences
