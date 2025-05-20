# Function: <code>md_bitmap_read_sb</code>

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
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff818314a5)
Location: drivers/md/md-bitmap.c:580
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int md_bitmap_read_sb(struct bitmap *bitmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:581
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
**Symbols:**

```
ffffffff81873420-ffffffff8187387a: md_bitmap_read_sb (STB_LOCAL)
ffffffff81874a65-ffffffff81874b36: md_bitmap_read_sb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int md_bitmap_read_sb(struct bitmap *bitmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:581
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
**Symbols:**

```
ffffffff818a5220-ffffffff818a567a: md_bitmap_read_sb (STB_LOCAL)
ffffffff818a6875-ffffffff818a6946: md_bitmap_read_sb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int md_bitmap_read_sb(struct bitmap *bitmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:577
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
**Symbols:**

```
ffffffff81975140-ffffffff8197559f: md_bitmap_read_sb (STB_LOCAL)
ffffffff819766cb-ffffffff819767a4: md_bitmap_read_sb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int md_bitmap_read_sb(struct bitmap *bitmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:578
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
**Symbols:**

```
ffffffff8197a040-ffffffff8197a583: md_bitmap_read_sb (STB_LOCAL)
ffffffff81c27dc0-ffffffff81c27eb4: md_bitmap_read_sb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int md_bitmap_read_sb(struct bitmap *bitmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:578
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
**Symbols:**

```
ffffffff8195e290-ffffffff8195e7aa: md_bitmap_read_sb (STB_LOCAL)
ffffffff81c19f88-ffffffff81c1a079: md_bitmap_read_sb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int md_bitmap_read_sb(struct bitmap *bitmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:578
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
**Symbols:**

```
ffffffff81a03ba0-ffffffff81a040ba: md_bitmap_read_sb (STB_LOCAL)
ffffffff81d29a30-ffffffff81d29b21: md_bitmap_read_sb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int md_bitmap_read_sb(struct bitmap *bitmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:578
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
**Symbols:**

```
ffffffff81b6b870-ffffffff81b6bd0c: md_bitmap_read_sb (STB_LOCAL)
ffffffff81ef5d0e-ffffffff81ef5e88: md_bitmap_read_sb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int md_bitmap_read_sb(struct bitmap *bitmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81d07750)
Location: drivers/md/md-bitmap.c:578
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
**Symbols:**

```
ffffffff81d07750-ffffffff81d07d20: md_bitmap_read_sb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int md_bitmap_read_sb(struct bitmap *bitmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81d708e0)
Location: drivers/md/md-bitmap.c:594
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
**Symbols:**

```
ffffffff81d708e0-ffffffff81d70eb0: md_bitmap_read_sb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int md_bitmap_read_sb(struct bitmap *bitmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81e27970)
Location: drivers/md/md-bitmap.c:613
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
**Symbols:**

```
ffffffff81e27970-ffffffff81e27f56: md_bitmap_read_sb (STB_LOCAL)
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
int md_bitmap_read_sb(struct bitmap *bitmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffff800010af9e80)
Location: drivers/md/md-bitmap.c:581
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
**Symbols:**

```
ffff800010af9e80-ffff800010afa3f8: md_bitmap_read_sb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int md_bitmap_read_sb(struct bitmap *bitmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (c0bda928)
Location: drivers/md/md-bitmap.c:581
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
**Symbols:**

```
c0bda928-c0bdaf78: md_bitmap_read_sb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int md_bitmap_read_sb(struct bitmap *bitmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (c000000000be7b90)
Location: drivers/md/md-bitmap.c:581
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
**Symbols:**

```
c000000000be7b90-c000000000be8250: md_bitmap_read_sb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int md_bitmap_read_sb(struct bitmap *bitmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffe0006eb9e6)
Location: drivers/md/md-bitmap.c:581
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
**Symbols:**

```
ffffffe0006eb9e6-ffffffe0006ebe64: md_bitmap_read_sb (STB_LOCAL)
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
int md_bitmap_read_sb(struct bitmap *bitmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:581
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
**Symbols:**

```
ffffffff8184b0a0-ffffffff8184b4fa: md_bitmap_read_sb (STB_LOCAL)
ffffffff8184c6f5-ffffffff8184c7c6: md_bitmap_read_sb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int md_bitmap_read_sb(struct bitmap *bitmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:581
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
**Symbols:**

```
ffffffff818126d0-ffffffff81812b2a: md_bitmap_read_sb (STB_LOCAL)
ffffffff81813d15-ffffffff81813de6: md_bitmap_read_sb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int md_bitmap_read_sb(struct bitmap *bitmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:581
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
**Symbols:**

```
ffffffff8189a6d0-ffffffff8189ab2a: md_bitmap_read_sb (STB_LOCAL)
ffffffff8189bd25-ffffffff8189bdf6: md_bitmap_read_sb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int md_bitmap_read_sb(struct bitmap *bitmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:581
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
**Symbols:**

```
ffffffff818b6840-ffffffff818b6cb1: md_bitmap_read_sb (STB_LOCAL)
ffffffff818b7ecd-ffffffff818b7f9e: md_bitmap_read_sb.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
