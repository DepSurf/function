# Function: <code>dm_table_alloc_md_mempools</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff816a6548)
Location: drivers/md/dm-table.c:933
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff817067f1)
Location: drivers/md/dm-table.c:1035
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81738679)
Location: drivers/md/dm-table.c:1036
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81751ba2)
Location: drivers/md/dm-table.c:1076
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff817c3db0)
Location: drivers/md/dm-table.c:1078
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff8180c6f9)
Location: drivers/md/dm-table.c:1113
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81838672)
Location: drivers/md/dm-table.c:1093
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff8187b249)
Location: drivers/md/dm-table.c:1106
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff818ad039)
Location: drivers/md/dm-table.c:1104
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff8197d5ac)
Location: drivers/md/dm-table.c:1080
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
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
In drivers/md/dm-table.c (ffffffff81981b2c)
Location: drivers/md/dm-table.c:1025
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
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
In drivers/md/dm-table.c (ffffffff81965dbe)
Location: drivers/md/dm-table.c:1011
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
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
In drivers/md/dm-table.c (ffffffff81a0dd6a)
Location: drivers/md/dm-table.c:1006
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
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
In drivers/md/dm-table.c (ffffffff81b76469)
Location: drivers/md/dm-table.c:1010
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dm_table_alloc_md_mempools(struct dm_table *t, struct mapped_device *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81d12560)
Location: drivers/md/dm-table.c:1003
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
```
**Symbols:**

```
ffffffff81d12560-ffffffff81d126e8: dm_table_alloc_md_mempools (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dm_table_alloc_md_mempools(struct dm_table *t, struct mapped_device *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81d7b920)
Location: drivers/md/dm-table.c:997
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
```
**Symbols:**

```
ffffffff81d7b920-ffffffff81d7baa8: dm_table_alloc_md_mempools (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dm_table_alloc_md_mempools(struct dm_table *t, struct mapped_device *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81e328a0)
Location: drivers/md/dm-table.c:1019
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
```
**Symbols:**

```
ffffffff81e328a0-ffffffff81e32a59: dm_table_alloc_md_mempools (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffff800010b03ad8)
Location: drivers/md/dm-table.c:1104
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
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
In drivers/md/dm-table.c (c0be2b88)
Location: drivers/md/dm-table.c:1104
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (c000000000bf32d8)
Location: drivers/md/dm-table.c:1104
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
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
In drivers/md/dm-table.c (ffffffe0006f301e)
Location: drivers/md/dm-table.c:1104
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81852eb9)
Location: drivers/md/dm-table.c:1104
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff8181a4c9)
Location: drivers/md/dm-table.c:1104
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff818a24e9)
Location: drivers/md/dm-table.c:1104
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff818be729)
Location: drivers/md/dm-table.c:1104
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
