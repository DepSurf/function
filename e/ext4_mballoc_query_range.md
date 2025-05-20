# Function: <code>ext4_mballoc_query_range</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_mballoc_query_range(struct super_block *sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t end, ext4_mballoc_query_range_fn formatter, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81313030)
Location: fs/ext4/mballoc.c:5337
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
**Symbols:**

```
ffffffff81313030-ffffffff81313352: ext4_mballoc_query_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_mballoc_query_range(struct super_block *sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t end, ext4_mballoc_query_range_fn formatter, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813377f0)
Location: fs/ext4/mballoc.c:5341
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
**Symbols:**

```
ffffffff813377f0-ffffffff81337b15: ext4_mballoc_query_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ext4_mballoc_query_range(struct super_block *sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t end, ext4_mballoc_query_range_fn formatter, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81365d50)
Location: fs/ext4/mballoc.c:5311
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
**Symbols:**

```
ffffffff81365d50-ffffffff81366069: ext4_mballoc_query_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ext4_mballoc_query_range(struct super_block *sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t end, ext4_mballoc_query_range_fn formatter, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8137e1b0)
Location: fs/ext4/mballoc.c:5318
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
**Symbols:**

```
ffffffff8137e1b0-ffffffff8137e4c9: ext4_mballoc_query_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_mballoc_query_range(struct super_block *sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t end, ext4_mballoc_query_range_fn formatter, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813a7640)
Location: fs/ext4/mballoc.c:5320
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
**Symbols:**

```
ffffffff813a7640-ffffffff813a78cf: ext4_mballoc_query_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_mballoc_query_range(struct super_block *sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t end, ext4_mballoc_query_range_fn formatter, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813c04e0)
Location: fs/ext4/mballoc.c:5341
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
**Symbols:**

```
ffffffff813c04e0-ffffffff813c076f: ext4_mballoc_query_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_mballoc_query_range(struct super_block *sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t end, ext4_mballoc_query_range_fn formatter, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8140c610)
Location: fs/ext4/mballoc.c:5586
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
**Symbols:**

```
ffffffff8140c610-ffffffff8140c949: ext4_mballoc_query_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_mballoc_query_range(struct super_block *sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t end, ext4_mballoc_query_range_fn formatter, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8141fa80)
Location: fs/ext4/mballoc.c:5873
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
**Symbols:**

```
ffffffff8141fa80-ffffffff8141fdb3: ext4_mballoc_query_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_mballoc_query_range(struct super_block *sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t end, ext4_mballoc_query_range_fn formatter, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81426350)
Location: fs/ext4/mballoc.c:6406
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
**Symbols:**

```
ffffffff81426350-ffffffff814265f6: ext4_mballoc_query_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_mballoc_query_range(struct super_block *sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t end, ext4_mballoc_query_range_fn formatter, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8147a000)
Location: fs/ext4/mballoc.c:6499
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
**Symbols:**

```
ffffffff8147a000-ffffffff8147a28c: ext4_mballoc_query_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_mballoc_query_range(struct super_block *sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t end, ext4_mballoc_query_range_fn formatter, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff814fc280)
Location: fs/ext4/mballoc.c:6591
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
**Symbols:**

```
ffffffff814fc280-ffffffff814fc549: ext4_mballoc_query_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_mballoc_query_range(struct super_block *sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t end, ext4_mballoc_query_range_fn formatter, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81596a10)
Location: fs/ext4/mballoc.c:6560
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
**Symbols:**

```
ffffffff81596a10-ffffffff81596c75: ext4_mballoc_query_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_mballoc_query_range(struct super_block *sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t end, ext4_mballoc_query_range_fn formatter, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff815cd400)
Location: fs/ext4/mballoc.c:7138
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
**Symbols:**

```
ffffffff815cd400-ffffffff815cd6b2: ext4_mballoc_query_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_mballoc_query_range(struct super_block *sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t end, ext4_mballoc_query_range_fn formatter, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81605c80)
Location: fs/ext4/mballoc.c:6978
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
**Symbols:**

```
ffffffff81605c80-ffffffff81605f32: ext4_mballoc_query_range (STB_GLOBAL)
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
int ext4_mballoc_query_range(struct super_block *sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t end, ext4_mballoc_query_range_fn formatter, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffff8000104970f0)
Location: fs/ext4/mballoc.c:5341
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
**Symbols:**

```
ffff8000104970f0-ffff8000104972c0: ext4_mballoc_query_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_mballoc_query_range(struct super_block *sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t end, ext4_mballoc_query_range_fn formatter, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (c06593bc)
Location: fs/ext4/mballoc.c:5341
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
**Symbols:**

```
c06593bc-c06596e8: ext4_mballoc_query_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_mballoc_query_range(struct super_block *sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t end, ext4_mballoc_query_range_fn formatter, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (c0000000005c15e0)
Location: fs/ext4/mballoc.c:5341
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
**Symbols:**

```
c0000000005c15e0-c0000000005c1a3c: ext4_mballoc_query_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_mballoc_query_range(struct super_block *sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t end, ext4_mballoc_query_range_fn formatter, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffe00031bb0c)
Location: fs/ext4/mballoc.c:5341
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
**Symbols:**

```
ffffffe00031bb0c-ffffffe00031bdcc: ext4_mballoc_query_range (STB_GLOBAL)
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
int ext4_mballoc_query_range(struct super_block *sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t end, ext4_mballoc_query_range_fn formatter, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813b8ac0)
Location: fs/ext4/mballoc.c:5341
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
**Symbols:**

```
ffffffff813b8ac0-ffffffff813b8d4f: ext4_mballoc_query_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_mballoc_query_range(struct super_block *sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t end, ext4_mballoc_query_range_fn formatter, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813a9550)
Location: fs/ext4/mballoc.c:5341
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
**Symbols:**

```
ffffffff813a9550-ffffffff813a97df: ext4_mballoc_query_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_mballoc_query_range(struct super_block *sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t end, ext4_mballoc_query_range_fn formatter, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813b6320)
Location: fs/ext4/mballoc.c:5341
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
**Symbols:**

```
ffffffff813b6320-ffffffff813b65af: ext4_mballoc_query_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_mballoc_query_range(struct super_block *sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t end, ext4_mballoc_query_range_fn formatter, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813cb040)
Location: fs/ext4/mballoc.c:5341
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
**Symbols:**

```
ffffffff813cb040-ffffffff813cb2ca: ext4_mballoc_query_range (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
