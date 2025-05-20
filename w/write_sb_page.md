# Function: <code>write_sb_page</code>

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
In drivers/md/bitmap.c (ffffffff8169d5f8)
Location: drivers/md/bitmap.c:207
Inline: True
Inline callers:
  - drivers/md/bitmap.c:write_page
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
In drivers/md/bitmap.c (ffffffff816fe8ca)
Location: drivers/md/bitmap.c:209
Inline: True
Inline callers:
  - drivers/md/bitmap.c:write_page
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
In drivers/md/bitmap.c (ffffffff8173051b)
Location: drivers/md/bitmap.c:210
Inline: True
Inline callers:
  - drivers/md/bitmap.c:write_page
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
In drivers/md/bitmap.c (ffffffff81748399)
Location: drivers/md/bitmap.c:211
Inline: True
Inline callers:
  - drivers/md/bitmap.c:write_page
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
In drivers/md/md-bitmap.c (ffffffff817ba629)
Location: drivers/md/md-bitmap.c:211
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
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
In drivers/md/md-bitmap.c (ffffffff818025b9)
Location: drivers/md/md-bitmap.c:211
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
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
In drivers/md/md-bitmap.c (ffffffff8182e8b2)
Location: drivers/md/md-bitmap.c:211
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
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
In drivers/md/md-bitmap.c (ffffffff81870da7)
Location: drivers/md/md-bitmap.c:212
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
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
In drivers/md/md-bitmap.c (ffffffff818a2b97)
Location: drivers/md/md-bitmap.c:212
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int write_sb_page(struct bitmap *bitmap, struct page *page, int wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81972690)
Location: drivers/md/md-bitmap.c:212
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:write_page
```
**Symbols:**

```
ffffffff81972690-ffffffff819728c9: write_sb_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int write_sb_page(struct bitmap *bitmap, struct page *page, int wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff819775a0)
Location: drivers/md/md-bitmap.c:212
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:write_page
```
**Symbols:**

```
ffffffff819775a0-ffffffff819777e5: write_sb_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int write_sb_page(struct bitmap *bitmap, struct page *page, int wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff8195b500)
Location: drivers/md/md-bitmap.c:212
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:write_page
```
**Symbols:**

```
ffffffff8195b500-ffffffff8195b742: write_sb_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int write_sb_page(struct bitmap *bitmap, struct page *page, int wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81a00cf0)
Location: drivers/md/md-bitmap.c:212
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:write_page
```
**Symbols:**

```
ffffffff81a00cf0-ffffffff81a00f32: write_sb_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int write_sb_page(struct bitmap *bitmap, struct page *page, int wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81b679e0)
Location: drivers/md/md-bitmap.c:212
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:write_page
```
**Symbols:**

```
ffffffff81b679e0-ffffffff81b67c34: write_sb_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int write_sb_page(struct bitmap *bitmap, struct page *page, int wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81d03390)
Location: drivers/md/md-bitmap.c:212
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:write_page
```
**Symbols:**

```
ffffffff81d03390-ffffffff81d035e4: write_sb_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81d6e8ee)
Location: drivers/md/md-bitmap.c:282
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void write_sb_page(struct bitmap *bitmap, long unsigned int pg_index, struct page *page, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81e24610)
Location: drivers/md/md-bitmap.c:279
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:filemap_write_page
```
**Symbols:**

```
ffffffff81e24610-ffffffff81e24734: write_sb_page (STB_LOCAL)
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
In drivers/md/md-bitmap.c (ffff800010af8668)
Location: drivers/md/md-bitmap.c:212
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
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
In drivers/md/md-bitmap.c (c0bd86ec)
Location: drivers/md/md-bitmap.c:212
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
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
In drivers/md/md-bitmap.c (c000000000be4634)
Location: drivers/md/md-bitmap.c:212
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
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
In drivers/md/md-bitmap.c (ffffffe0006e970e)
Location: drivers/md/md-bitmap.c:212
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
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
In drivers/md/md-bitmap.c (ffffffff81848a17)
Location: drivers/md/md-bitmap.c:212
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
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
In drivers/md/md-bitmap.c (ffffffff81810077)
Location: drivers/md/md-bitmap.c:212
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
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
In drivers/md/md-bitmap.c (ffffffff81898047)
Location: drivers/md/md-bitmap.c:212
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
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
In drivers/md/md-bitmap.c (ffffffff818b4241)
Location: drivers/md/md-bitmap.c:212
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:write_page
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
</ul>
