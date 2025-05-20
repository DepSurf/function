# Function: <code>dm_table_determine_type</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81706441)
Location: drivers/md/dm-table.c:876
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
In drivers/md/dm-table.c (ffffffff817382b1)
Location: drivers/md/dm-table.c:870
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
In drivers/md/dm-table.c (ffffffff81751831)
Location: drivers/md/dm-table.c:910
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
In drivers/md/dm-table.c (ffffffff817c3a21)
Location: drivers/md/dm-table.c:912
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
In drivers/md/dm-table.c (ffffffff8180c4e2)
Location: drivers/md/dm-table.c:932
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
In drivers/md/dm-table.c (ffffffff81838482)
Location: drivers/md/dm-table.c:930
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
In drivers/md/dm-table.c (ffffffff8187b052)
Location: drivers/md/dm-table.c:942
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
In drivers/md/dm-table.c (ffffffff818ace42)
Location: drivers/md/dm-table.c:940
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int dm_table_determine_type(struct dm_table *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-table.c (0)
Location: drivers/md/dm-table.c:921
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
```
**Symbols:**

```
ffffffff8197d120-ffffffff8197d3d5: dm_table_determine_type (STB_LOCAL)
ffffffff8197e57d-ffffffff8197e5fb: dm_table_determine_type.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int dm_table_determine_type(struct dm_table *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-table.c (0)
Location: drivers/md/dm-table.c:877
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
```
**Symbols:**

```
ffffffff81981750-ffffffff8198195b: dm_table_determine_type (STB_LOCAL)
ffffffff81c2814c-ffffffff81c281ba: dm_table_determine_type.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int dm_table_determine_type(struct dm_table *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-table.c (0)
Location: drivers/md/dm-table.c:863
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
```
**Symbols:**

```
ffffffff81965990-ffffffff81965b9b: dm_table_determine_type (STB_LOCAL)
ffffffff81c1a322-ffffffff81c1a390: dm_table_determine_type.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dm_table_determine_type(struct dm_table *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-table.c (0)
Location: drivers/md/dm-table.c:858
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
```
**Symbols:**

```
ffffffff81a0d920-ffffffff81a0db2b: dm_table_determine_type (STB_LOCAL)
ffffffff81d2a07e-ffffffff81d2a0ec: dm_table_determine_type.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dm_table_determine_type(struct dm_table *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-table.c (0)
Location: drivers/md/dm-table.c:861
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
```
**Symbols:**

```
ffffffff81b74cd0-ffffffff81b74ee4: dm_table_determine_type (STB_LOCAL)
ffffffff81ef62bd-ffffffff81ef630b: dm_table_determine_type.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dm_table_determine_type(struct dm_table *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81d11d30)
Location: drivers/md/dm-table.c:857
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
```
**Symbols:**

```
ffffffff81d11d30-ffffffff81d11fab: dm_table_determine_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dm_table_determine_type(struct dm_table *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81d7b100)
Location: drivers/md/dm-table.c:852
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
```
**Symbols:**

```
ffffffff81d7b100-ffffffff81d7b37c: dm_table_determine_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dm_table_determine_type(struct dm_table *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81e32080)
Location: drivers/md/dm-table.c:874
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
```
**Symbols:**

```
ffffffff81e32080-ffffffff81e322fc: dm_table_determine_type (STB_LOCAL)
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
In drivers/md/dm-table.c (ffff800010b03910)
Location: drivers/md/dm-table.c:940
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
In drivers/md/dm-table.c (c0be2990)
Location: drivers/md/dm-table.c:940
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
In drivers/md/dm-table.c (c000000000bf2f44)
Location: drivers/md/dm-table.c:940
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
In drivers/md/dm-table.c (ffffffe0006f2df2)
Location: drivers/md/dm-table.c:940
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
In drivers/md/dm-table.c (ffffffff81852cc2)
Location: drivers/md/dm-table.c:940
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
In drivers/md/dm-table.c (ffffffff8181a2d2)
Location: drivers/md/dm-table.c:940
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
In drivers/md/dm-table.c (ffffffff818a22f2)
Location: drivers/md/dm-table.c:940
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
In drivers/md/dm-table.c (ffffffff818be532)
Location: drivers/md/dm-table.c:940
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
