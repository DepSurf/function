# Function: <code>validate_hardware_logical_block_alignment</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/dm-table.c (ffffffff816a5780)
Location: drivers/md/dm-table.c:591
Inline: True
Direct callers:
  - drivers/md/dm-table.c:dm_calculate_queue_limits
```
**Symbols:**

```
ffffffff816a5780-ffffffff816a58e2: validate_hardware_logical_block_alignment.isra.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81705900)
Location: drivers/md/dm-table.c:606
Inline: True
Direct callers:
  - drivers/md/dm-table.c:dm_calculate_queue_limits
```
**Symbols:**

```
ffffffff81705900-ffffffff81705a62: validate_hardware_logical_block_alignment.isra.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/dm-table.c (ffffffff817377b0)
Location: drivers/md/dm-table.c:606
Inline: True
Direct callers:
  - drivers/md/dm-table.c:dm_calculate_queue_limits
```
**Symbols:**

```
ffffffff817377b0-ffffffff81737918: validate_hardware_logical_block_alignment.isra.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81750cd0)
Location: drivers/md/dm-table.c:643
Inline: True
Direct callers:
  - drivers/md/dm-table.c:dm_calculate_queue_limits
```
**Symbols:**

```
ffffffff81750cd0-ffffffff81750e43: validate_hardware_logical_block_alignment.isra.16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/dm-table.c (ffffffff817c2ea0)
Location: drivers/md/dm-table.c:644
Inline: True
Direct callers:
  - drivers/md/dm-table.c:dm_calculate_queue_limits
```
**Symbols:**

```
ffffffff817c2ea0-ffffffff817c3016: validate_hardware_logical_block_alignment.isra.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/dm-table.c (ffffffff8180b8b0)
Location: drivers/md/dm-table.c:644
Inline: True
Direct callers:
  - drivers/md/dm-table.c:dm_calculate_queue_limits
```
**Symbols:**

```
ffffffff8180b8b0-ffffffff8180ba2b: validate_hardware_logical_block_alignment.isra.21 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81837870)
Location: drivers/md/dm-table.c:643
Inline: True
Direct callers:
  - drivers/md/dm-table.c:dm_calculate_queue_limits
```
**Symbols:**

```
ffffffff81837870-ffffffff818379eb: validate_hardware_logical_block_alignment.isra.21 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/dm-table.c (ffffffff8187a3e0)
Location: drivers/md/dm-table.c:643
Inline: True
Direct callers:
  - drivers/md/dm-table.c:dm_calculate_queue_limits
```
**Symbols:**

```
ffffffff8187a3e0-ffffffff8187a554: validate_hardware_logical_block_alignment.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/dm-table.c (ffffffff818ac1c0)
Location: drivers/md/dm-table.c:641
Inline: True
Direct callers:
  - drivers/md/dm-table.c:dm_calculate_queue_limits
```
**Symbols:**

```
ffffffff818ac1c0-ffffffff818ac337: validate_hardware_logical_block_alignment.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int validate_hardware_logical_block_alignment(struct dm_table *table, struct queue_limits *limits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff8197c040)
Location: drivers/md/dm-table.c:624
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_calculate_queue_limits
```
**Symbols:**

```
ffffffff8197c040-ffffffff8197c1b4: validate_hardware_logical_block_alignment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int validate_hardware_logical_block_alignment(struct dm_table *table, struct queue_limits *limits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81980450)
Location: drivers/md/dm-table.c:583
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_calculate_queue_limits
```
**Symbols:**

```
ffffffff81980450-ffffffff819805c4: validate_hardware_logical_block_alignment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int validate_hardware_logical_block_alignment(struct dm_table *table, struct queue_limits *limits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81964680)
Location: drivers/md/dm-table.c:569
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_calculate_queue_limits
```
**Symbols:**

```
ffffffff81964680-ffffffff819647ec: validate_hardware_logical_block_alignment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int validate_hardware_logical_block_alignment(struct dm_table *table, struct queue_limits *limits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81a0c630)
Location: drivers/md/dm-table.c:569
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_calculate_queue_limits
```
**Symbols:**

```
ffffffff81a0c630-ffffffff81a0c79c: validate_hardware_logical_block_alignment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int validate_hardware_logical_block_alignment(struct dm_table *table, struct queue_limits *limits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81b750b0)
Location: drivers/md/dm-table.c:567
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_calculate_queue_limits
```
**Symbols:**

```
ffffffff81b750b0-ffffffff81b75248: validate_hardware_logical_block_alignment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int validate_hardware_logical_block_alignment(struct dm_table *t, struct queue_limits *limits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81d121c0)
Location: drivers/md/dm-table.c:566
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_calculate_queue_limits
```
**Symbols:**

```
ffffffff81d121c0-ffffffff81d12358: validate_hardware_logical_block_alignment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int validate_hardware_logical_block_alignment(struct dm_table *t, struct queue_limits *limits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81d7b570)
Location: drivers/md/dm-table.c:561
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_calculate_queue_limits
```
**Symbols:**

```
ffffffff81d7b570-ffffffff81d7b718: validate_hardware_logical_block_alignment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int validate_hardware_logical_block_alignment(struct dm_table *t, struct queue_limits *limits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81e324f0)
Location: drivers/md/dm-table.c:582
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_calculate_queue_limits
```
**Symbols:**

```
ffffffff81e324f0-ffffffff81e32698: validate_hardware_logical_block_alignment (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/dm-table.c (ffff800010b02bd8)
Location: drivers/md/dm-table.c:641
Inline: True
Direct callers:
  - drivers/md/dm-table.c:dm_calculate_queue_limits
```
**Symbols:**

```
ffff800010b02bd8-ffff800010b02d38: validate_hardware_logical_block_alignment.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int validate_hardware_logical_block_alignment(struct dm_table *table, struct queue_limits *limits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (c0be1b1c)
Location: drivers/md/dm-table.c:641
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_calculate_queue_limits
```
**Symbols:**

```
c0be1b1c-c0be1c80: validate_hardware_logical_block_alignment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/dm-table.c (c000000000bf1e00)
Location: drivers/md/dm-table.c:641
Inline: True
Direct callers:
  - drivers/md/dm-table.c:dm_calculate_queue_limits
```
**Symbols:**

```
c000000000bf1e00-c000000000bf1ff0: validate_hardware_logical_block_alignment.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/dm-table.c (ffffffe0006f232a)
Location: drivers/md/dm-table.c:641
Inline: True
Direct callers:
  - drivers/md/dm-table.c:dm_calculate_queue_limits
```
**Symbols:**

```
ffffffe0006f232a-ffffffe0006f243e: validate_hardware_logical_block_alignment.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81852040)
Location: drivers/md/dm-table.c:641
Inline: True
Direct callers:
  - drivers/md/dm-table.c:dm_calculate_queue_limits
```
**Symbols:**

```
ffffffff81852040-ffffffff818521b7: validate_hardware_logical_block_alignment.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81819650)
Location: drivers/md/dm-table.c:641
Inline: True
Direct callers:
  - drivers/md/dm-table.c:dm_calculate_queue_limits
```
**Symbols:**

```
ffffffff81819650-ffffffff818197c7: validate_hardware_logical_block_alignment.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/dm-table.c (ffffffff818a1670)
Location: drivers/md/dm-table.c:641
Inline: True
Direct callers:
  - drivers/md/dm-table.c:dm_calculate_queue_limits
```
**Symbols:**

```
ffffffff818a1670-ffffffff818a17e7: validate_hardware_logical_block_alignment.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/dm-table.c (ffffffff818bd8b0)
Location: drivers/md/dm-table.c:641
Inline: True
Direct callers:
  - drivers/md/dm-table.c:dm_calculate_queue_limits
```
**Symbols:**

```
ffffffff818bd8b0-ffffffff818bda27: validate_hardware_logical_block_alignment.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<code>struct dm_table *t</code>
</li>
<li>
<b>Param removed. </b>
<code>struct dm_table *table</code>
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
</ul>
