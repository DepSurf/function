# Function: <code>dm_table_complete</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int dm_table_complete(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff816a6290)
Location: drivers/md/dm-table.c:1104
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
```
**Symbols:**

```
ffffffff816a6290-ffffffff816a6830: dm_table_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int dm_table_complete(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81706430)
Location: drivers/md/dm-table.c:1206
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
```
**Symbols:**

```
ffffffff81706430-ffffffff81706aab: dm_table_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int dm_table_complete(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff817382a0)
Location: drivers/md/dm-table.c:1207
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
```
**Symbols:**

```
ffffffff817382a0-ffffffff8173897e: dm_table_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int dm_table_complete(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81751820)
Location: drivers/md/dm-table.c:1258
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
```
**Symbols:**

```
ffffffff81751820-ffffffff81751edb: dm_table_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dm_table_complete(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff817c3a10)
Location: drivers/md/dm-table.c:1260
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
```
**Symbols:**

```
ffffffff817c3a10-ffffffff817c40b1: dm_table_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int dm_table_complete(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-table.c (0)
Location: drivers/md/dm-table.c:1298
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
```
**Symbols:**

```
ffffffff8180dab0-ffffffff8180db4c: dm_table_complete.cold.30 (STB_LOCAL)
ffffffff8180c4b0-ffffffff8180cbae: dm_table_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int dm_table_complete(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-table.c (0)
Location: drivers/md/dm-table.c:1278
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
```
**Symbols:**

```
ffffffff818399fd-ffffffff81839a8b: dm_table_complete.cold.30 (STB_LOCAL)
ffffffff81838450-ffffffff81838ad8: dm_table_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int dm_table_complete(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-table.c (0)
Location: drivers/md/dm-table.c:1291
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff8187c53d-ffffffff8187c619: dm_table_complete.cold (STB_LOCAL)
ffffffff8187b020-ffffffff8187b668: dm_table_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int dm_table_complete(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-table.c (0)
Location: drivers/md/dm-table.c:1289
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff818ae31d-ffffffff818ae3f9: dm_table_complete.cold (STB_LOCAL)
ffffffff818ace10-ffffffff818ad458: dm_table_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int dm_table_complete(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-table.c (0)
Location: drivers/md/dm-table.c:1265
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff8197e5fb-ffffffff8197e669: dm_table_complete.cold (STB_LOCAL)
ffffffff8197d520-ffffffff8197d72b: dm_table_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int dm_table_complete(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-table.c (0)
Location: drivers/md/dm-table.c:1210
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff81c281ba-ffffffff81c28228: dm_table_complete.cold (STB_LOCAL)
ffffffff81981aa0-ffffffff81981ca4: dm_table_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int dm_table_complete(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-table.c (0)
Location: drivers/md/dm-table.c:1400
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff81c1a390-ffffffff81c1a413: dm_table_complete.cold (STB_LOCAL)
ffffffff81965d10-ffffffff81966070: dm_table_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dm_table_complete(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-table.c (0)
Location: drivers/md/dm-table.c:1395
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff81d2a0ec-ffffffff81d2a16e: dm_table_complete.cold (STB_LOCAL)
ffffffff81a0dca0-ffffffff81a0e25b: dm_table_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dm_table_complete(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-table.c (0)
Location: drivers/md/dm-table.c:1387
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff81ef6329-ffffffff81ef63a8: dm_table_complete.cold (STB_LOCAL)
ffffffff81b763a0-ffffffff81b769a0: dm_table_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dm_table_complete(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81d137c0)
Location: drivers/md/dm-table.c:1404
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff81d137c0-ffffffff81d13d54: dm_table_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dm_table_complete(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81d7c920)
Location: drivers/md/dm-table.c:1388
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:populate_table
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff81d7c920-ffffffff81d7ce88: dm_table_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dm_table_complete(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81e33e00)
Location: drivers/md/dm-table.c:1410
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:populate_table
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff81e33e00-ffffffff81e34368: dm_table_complete (STB_GLOBAL)
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
int dm_table_complete(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffff800010b038e0)
Location: drivers/md/dm-table.c:1289
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffff800010b038e0-ffff800010b03fdc: dm_table_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dm_table_complete(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (c0be2958)
Location: drivers/md/dm-table.c:1289
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
c0be2958-c0be3040: dm_table_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dm_table_complete(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (c000000000bf2f00)
Location: drivers/md/dm-table.c:1289
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
c000000000bf2f00-c000000000bf3870: dm_table_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dm_table_complete(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffe0006f2dd2)
Location: drivers/md/dm-table.c:1289
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffe0006f2dd2-ffffffe0006f3358: dm_table_complete (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int dm_table_complete(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-table.c (0)
Location: drivers/md/dm-table.c:1289
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff8185419d-ffffffff81854279: dm_table_complete.cold (STB_LOCAL)
ffffffff81852c90-ffffffff818532d8: dm_table_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int dm_table_complete(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-table.c (0)
Location: drivers/md/dm-table.c:1289
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff8181b7ad-ffffffff8181b889: dm_table_complete.cold (STB_LOCAL)
ffffffff8181a2a0-ffffffff8181a8e8: dm_table_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int dm_table_complete(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-table.c (0)
Location: drivers/md/dm-table.c:1289
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff818a37cd-ffffffff818a38a9: dm_table_complete.cold (STB_LOCAL)
ffffffff818a22c0-ffffffff818a2908: dm_table_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int dm_table_complete(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-table.c (0)
Location: drivers/md/dm-table.c:1289
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff818bfa0d-ffffffff818bfae9: dm_table_complete.cold (STB_LOCAL)
ffffffff818be500-ffffffff818beb48: dm_table_complete (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
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
