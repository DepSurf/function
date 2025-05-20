# Function: <code>__bind_mempools</code>

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
In drivers/md/dm.c (ffffffff816a43fe)
Location: drivers/md/dm.c:2407
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
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
In drivers/md/dm.c (ffffffff817045ae)
Location: drivers/md/dm.c:1572
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
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
In drivers/md/dm.c (ffffffff8173648c)
Location: drivers/md/dm.c:1627
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
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
In drivers/md/dm.c (ffffffff8174f866)
Location: drivers/md/dm.c:1832
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
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
In drivers/md/dm.c (ffffffff817c1a6f)
Location: drivers/md/dm.c:1812
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
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
In drivers/md/dm.c (ffffffff8180a187)
Location: drivers/md/dm.c:1978
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
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
In drivers/md/dm.c (ffffffff81836187)
Location: drivers/md/dm.c:2018
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
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
In drivers/md/dm.c (ffffffff81878db5)
Location: drivers/md/dm.c:2049
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
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
In drivers/md/dm.c (ffffffff818aabf5)
Location: drivers/md/dm.c:2047
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __bind_mempools(struct mapped_device *md, struct dm_table *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81977150)
Location: drivers/md/dm.c:2050
Inline: False
Direct callers:
  - drivers/md/dm.c:__bind
```
**Symbols:**

```
ffffffff81977150-ffffffff81977217: __bind_mempools (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __bind_mempools(struct mapped_device *md, struct dm_table *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8197be30)
Location: drivers/md/dm.c:1935
Inline: False
Direct callers:
  - drivers/md/dm.c:__bind
```
**Symbols:**

```
ffffffff8197be30-ffffffff8197bef7: __bind_mempools (STB_LOCAL)
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
In drivers/md/dm.c (ffffffff8195fe47)
Location: drivers/md/dm.c:1954
Inline: True
Inline callers:
  - drivers/md/dm.c:__bind
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
In drivers/md/dm.c (ffffffff81a07df3)
Location: drivers/md/dm.c:1835
Inline: True
Inline callers:
  - drivers/md/dm.c:__bind
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffff800010b00d14)
Location: drivers/md/dm.c:2047
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
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
In drivers/md/dm.c (c0be0630)
Location: drivers/md/dm.c:2047
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
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
In drivers/md/dm.c (c000000000beff14)
Location: drivers/md/dm.c:2047
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
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
In drivers/md/dm.c (ffffffe0006f0e88)
Location: drivers/md/dm.c:2047
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
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
In drivers/md/dm.c (ffffffff81850a75)
Location: drivers/md/dm.c:2047
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
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
In drivers/md/dm.c (ffffffff81818085)
Location: drivers/md/dm.c:2047
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
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
In drivers/md/dm.c (ffffffff818a00a5)
Location: drivers/md/dm.c:2047
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
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
In drivers/md/dm.c (ffffffff818bc317)
Location: drivers/md/dm.c:2047
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
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
</ul>
