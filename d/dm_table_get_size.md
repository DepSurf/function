# Function: <code>dm_table_get_size</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
sector_t dm_table_get_size(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff816a4cb0)
Location: drivers/md/dm-table.c:1158
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_get_live_table_for_ioctl
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:dm_resume
```
**Symbols:**

```
ffffffff816a4cb0-ffffffff816a4cd9: dm_table_get_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
sector_t dm_table_get_size(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81704e10)
Location: drivers/md/dm-table.c:1260
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:dm_grab_bdev_for_ioctl
```
**Symbols:**

```
ffffffff81704e10-ffffffff81704e39: dm_table_get_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
sector_t dm_table_get_size(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81736cc0)
Location: drivers/md/dm-table.c:1261
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:dm_grab_bdev_for_ioctl
```
**Symbols:**

```
ffffffff81736cc0-ffffffff81736ce9: dm_table_get_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
sector_t dm_table_get_size(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81750040)
Location: drivers/md/dm-table.c:1312
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:dm_grab_bdev_for_ioctl
```
**Symbols:**

```
ffffffff81750040-ffffffff81750069: dm_table_get_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
sector_t dm_table_get_size(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff817c2220)
Location: drivers/md/dm-table.c:1314
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:dm_grab_bdev_for_ioctl
```
**Symbols:**

```
ffffffff817c2220-ffffffff817c2249: dm_table_get_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
sector_t dm_table_get_size(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff8180ab40)
Location: drivers/md/dm-table.c:1352
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:dm_prepare_ioctl
```
**Symbols:**

```
ffffffff8180ab40-ffffffff8180ab69: dm_table_get_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
sector_t dm_table_get_size(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81836b30)
Location: drivers/md/dm-table.c:1332
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:dm_prepare_ioctl
```
**Symbols:**

```
ffffffff81836b30-ffffffff81836b59: dm_table_get_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
sector_t dm_table_get_size(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff8187b6f5)
Location: drivers/md/dm-table.c:1345
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_find_target
Direct callers:
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:dm_prepare_ioctl
```
**Symbols:**

```
ffffffff81879740-ffffffff8187975f: dm_table_get_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
sector_t dm_table_get_size(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff818ad4e5)
Location: drivers/md/dm-table.c:1343
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_find_target
Direct callers:
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:dm_prepare_ioctl
```
**Symbols:**

```
ffffffff818ab540-ffffffff818ab55f: dm_table_get_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
sector_t dm_table_get_size(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff8197d7b5)
Location: drivers/md/dm-table.c:1319
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_find_target
Direct callers:
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:__bind
  - drivers/md/dm.c:dm_prepare_ioctl
```
**Symbols:**

```
ffffffff8197b700-ffffffff8197b71f: dm_table_get_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
sector_t dm_table_get_size(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81981d35)
Location: drivers/md/dm-table.c:1258
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_find_target
Direct callers:
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:__bind
  - drivers/md/dm.c:dm_prepare_ioctl
```
**Symbols:**

```
ffffffff8197fdd0-ffffffff8197fdef: dm_table_get_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
sector_t dm_table_get_size(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff819660f5)
Location: drivers/md/dm-table.c:1454
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_find_target
Direct callers:
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:__bind
  - drivers/md/dm.c:dm_prepare_ioctl
```
**Symbols:**

```
ffffffff81963f50-ffffffff81963f6f: dm_table_get_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
sector_t dm_table_get_size(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81a0e2e5)
Location: drivers/md/dm-table.c:1449
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_find_target
Direct callers:
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:__bind
  - drivers/md/dm.c:dm_prepare_ioctl
```
**Symbols:**

```
ffffffff81a0bf00-ffffffff81a0bf1f: dm_table_get_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
sector_t dm_table_get_size(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81b76a35)
Location: drivers/md/dm-table.c:1441
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_find_target
Direct callers:
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:__bind
  - drivers/md/dm.c:dm_prepare_ioctl
```
**Symbols:**

```
ffffffff81b74500-ffffffff81b74527: dm_table_get_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
sector_t dm_table_get_size(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81d13dd5)
Location: drivers/md/dm-table.c:1458
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_find_target
Direct callers:
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:__bind
  - drivers/md/dm.c:dm_prepare_ioctl
```
**Symbols:**

```
ffffffff81d113c0-ffffffff81d113e7: dm_table_get_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
sector_t dm_table_get_size(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81d7cf05)
Location: drivers/md/dm-table.c:1442
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_find_target
Direct callers:
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:__bind
  - drivers/md/dm.c:dm_prepare_ioctl
```
**Symbols:**

```
ffffffff81d7a840-ffffffff81d7a867: dm_table_get_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
sector_t dm_table_get_size(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81e343e5)
Location: drivers/md/dm-table.c:1464
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_find_target
Direct callers:
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:__bind
  - drivers/md/dm.c:dm_prepare_ioctl
```
**Symbols:**

```
ffffffff81e319e0-ffffffff81e31a07: dm_table_get_size (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
sector_t dm_table_get_size(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffff800010b0409c)
Location: drivers/md/dm-table.c:1343
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_find_target
Direct callers:
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:dm_prepare_ioctl
```
**Symbols:**

```
ffff800010b01ca8-ffff800010b01ccc: dm_table_get_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
sector_t dm_table_get_size(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (c0be30c4)
Location: drivers/md/dm-table.c:1343
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_find_target
Direct callers:
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:dm_prepare_ioctl
```
**Symbols:**

```
c0be0e78-c0be0eb4: dm_table_get_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
sector_t dm_table_get_size(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (c000000000bf3938)
Location: drivers/md/dm-table.c:1343
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_find_target
Direct callers:
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:dm_prepare_ioctl
```
**Symbols:**

```
c000000000bf0b50-c000000000bf0b88: dm_table_get_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
sector_t dm_table_get_size(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffe0006f3414)
Location: drivers/md/dm-table.c:1343
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_find_target
Direct callers:
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:dm_prepare_ioctl
```
**Symbols:**

```
ffffffe0006f16c6-ffffffe0006f16ee: dm_table_get_size (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
sector_t dm_table_get_size(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81853365)
Location: drivers/md/dm-table.c:1343
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_find_target
Direct callers:
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:dm_prepare_ioctl
```
**Symbols:**

```
ffffffff818513c0-ffffffff818513df: dm_table_get_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
sector_t dm_table_get_size(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff8181a975)
Location: drivers/md/dm-table.c:1343
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_find_target
Direct callers:
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:dm_prepare_ioctl
```
**Symbols:**

```
ffffffff818189d0-ffffffff818189ef: dm_table_get_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
sector_t dm_table_get_size(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff818a2995)
Location: drivers/md/dm-table.c:1343
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_find_target
Direct callers:
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:dm_prepare_ioctl
```
**Symbols:**

```
ffffffff818a09f0-ffffffff818a0a0f: dm_table_get_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
sector_t dm_table_get_size(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff818bebd5)
Location: drivers/md/dm-table.c:1343
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_find_target
Direct callers:
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:dm_prepare_ioctl
```
**Symbols:**

```
ffffffff818bcc30-ffffffff818bcc4f: dm_table_get_size (STB_GLOBAL)
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
