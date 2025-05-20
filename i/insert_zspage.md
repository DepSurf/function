# Function: <code>insert_zspage</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void insert_zspage(struct page *page, struct size_class *class, enum fullness_group fullness);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81205320)
Location: mm/zsmalloc.c:650
Inline: True
Direct callers:
  - mm/zsmalloc.c:fix_fullness_group
```
**Symbols:**

```
ffffffff81205320-ffffffff81205378: insert_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void insert_zspage(struct size_class *class, struct zspage *zspage, enum fullness_group fullness);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81229e70)
Location: mm/zsmalloc.c:754
Inline: False
Direct callers:
  - mm/zsmalloc.c:putback_zspage
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:fix_fullness_group
```
**Symbols:**

```
ffffffff81229e70-ffffffff81229edc: insert_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void insert_zspage(struct size_class *class, struct zspage *zspage, enum fullness_group fullness);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff8123c400)
Location: mm/zsmalloc.c:754
Inline: False
Direct callers:
  - mm/zsmalloc.c:putback_zspage
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:fix_fullness_group
```
**Symbols:**

```
ffffffff8123c400-ffffffff8123c46b: insert_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void insert_zspage(struct size_class *class, struct zspage *zspage, enum fullness_group fullness);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81248040)
Location: mm/zsmalloc.c:747
Inline: False
Direct callers:
  - mm/zsmalloc.c:putback_zspage
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:fix_fullness_group
```
**Symbols:**

```
ffffffff81248040-ffffffff812480a7: insert_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void insert_zspage(struct size_class *class, struct zspage *zspage, enum fullness_group fullness);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81268200)
Location: mm/zsmalloc.c:751
Inline: False
Direct callers:
  - mm/zsmalloc.c:putback_zspage
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:fix_fullness_group
```
**Symbols:**

```
ffffffff81268200-ffffffff81268267: insert_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void insert_zspage(struct size_class *class, struct zspage *zspage, enum fullness_group fullness);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff8128cb70)
Location: mm/zsmalloc.c:733
Inline: False
Direct callers:
  - mm/zsmalloc.c:putback_zspage
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:fix_fullness_group
```
**Symbols:**

```
ffffffff8128cb70-ffffffff8128cbd7: insert_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void insert_zspage(struct size_class *class, struct zspage *zspage, enum fullness_group fullness);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff812a1af0)
Location: mm/zsmalloc.c:733
Inline: False
Direct callers:
  - mm/zsmalloc.c:putback_zspage
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:fix_fullness_group
```
**Symbols:**

```
ffffffff812a1af0-ffffffff812a1b57: insert_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void insert_zspage(struct size_class *class, struct zspage *zspage, enum fullness_group fullness);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff812bcd80)
Location: mm/zsmalloc.c:723
Inline: False
Direct callers:
  - mm/zsmalloc.c:putback_zspage
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:fix_fullness_group
```
**Symbols:**

```
ffffffff812bcd80-ffffffff812bcdea: insert_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void insert_zspage(struct size_class *class, struct zspage *zspage, enum fullness_group fullness);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff812cec70)
Location: mm/zsmalloc.c:720
Inline: False
Direct callers:
  - mm/zsmalloc.c:putback_zspage
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:fix_fullness_group
```
**Symbols:**

```
ffffffff812cec70-ffffffff812cecda: insert_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void insert_zspage(struct size_class *class, struct zspage *zspage, enum fullness_group fullness);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81304fa0)
Location: mm/zsmalloc.c:720
Inline: True
Direct callers:
  - mm/zsmalloc.c:__zs_compact
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:fix_fullness_group
```
**Symbols:**

```
ffffffff81304fa0-ffffffff81305006: insert_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void insert_zspage(struct size_class *class, struct zspage *zspage, enum fullness_group fullness);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81310d00)
Location: mm/zsmalloc.c:716
Inline: True
Direct callers:
  - mm/zsmalloc.c:__zs_compact
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:fix_fullness_group
```
**Symbols:**

```
ffffffff81310d00-ffffffff81310d66: insert_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void insert_zspage(struct size_class *class, struct zspage *zspage, enum fullness_group fullness);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81316dd0)
Location: mm/zsmalloc.c:716
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:fix_fullness_group
```
**Symbols:**

```
ffffffff81316dd0-ffffffff81316e36: insert_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void insert_zspage(struct size_class *class, struct zspage *zspage, enum fullness_group fullness);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81363060)
Location: mm/zsmalloc.c:716
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:fix_fullness_group
```
**Symbols:**

```
ffffffff81363060-ffffffff81363121: insert_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void insert_zspage(struct size_class *class, struct zspage *zspage, enum fullness_group fullness);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff813dfc30)
Location: mm/zsmalloc.c:717
Inline: True
Direct callers:
  - mm/zsmalloc.c:__zs_compact
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:fix_fullness_group
```
**Symbols:**

```
ffffffff813dfc30-ffffffff813dfd11: insert_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void insert_zspage(struct size_class *class, struct zspage *zspage, enum fullness_group fullness);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81466a60)
Location: mm/zsmalloc.c:765
Inline: True
Direct callers:
  - mm/zsmalloc.c:__zs_compact
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:fix_fullness_group
```
**Symbols:**

```
ffffffff81466a60-ffffffff81466b33: insert_zspage (STB_LOCAL)
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
In mm/zsmalloc.c (ffffffff8149c0c1)
Location: mm/zsmalloc.c:691
Inline: True
Inline callers:
  - mm/zsmalloc.c:putback_zspage
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:fix_fullness_group
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff814cb7e1)
Location: mm/zsmalloc.c:691
Inline: True
Inline callers:
  - mm/zsmalloc.c:putback_zspage
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:fix_fullness_group
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
void insert_zspage(struct size_class *class, struct zspage *zspage, enum fullness_group fullness);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffff800010373830)
Location: mm/zsmalloc.c:720
Inline: False
Direct callers:
  - mm/zsmalloc.c:putback_zspage
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:fix_fullness_group
```
**Symbols:**

```
ffff800010373830-ffff8000103738dc: insert_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void insert_zspage(struct size_class *class, struct zspage *zspage, enum fullness_group fullness);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (c055fec4)
Location: mm/zsmalloc.c:720
Inline: False
Direct callers:
  - mm/zsmalloc.c:putback_zspage
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:fix_fullness_group
```
**Symbols:**

```
c055fec4-c055ff4c: insert_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void insert_zspage(struct size_class *class, struct zspage *zspage, enum fullness_group fullness);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (c0000000004655d0)
Location: mm/zsmalloc.c:720
Inline: False
Direct callers:
  - mm/zsmalloc.c:putback_zspage
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:fix_fullness_group
```
**Symbols:**

```
c0000000004655d0-c000000000465658: insert_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void insert_zspage(struct size_class *class, struct zspage *zspage, enum fullness_group fullness);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffe00024c5e8)
Location: mm/zsmalloc.c:720
Inline: False
Direct callers:
  - mm/zsmalloc.c:putback_zspage
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:fix_fullness_group
```
**Symbols:**

```
ffffffe00024c5e8-ffffffe00024c678: insert_zspage (STB_LOCAL)
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
void insert_zspage(struct size_class *class, struct zspage *zspage, enum fullness_group fullness);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff812c7250)
Location: mm/zsmalloc.c:720
Inline: False
Direct callers:
  - mm/zsmalloc.c:putback_zspage
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:fix_fullness_group
```
**Symbols:**

```
ffffffff812c7250-ffffffff812c72ba: insert_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void insert_zspage(struct size_class *class, struct zspage *zspage, enum fullness_group fullness);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff812b8290)
Location: mm/zsmalloc.c:720
Inline: False
Direct callers:
  - mm/zsmalloc.c:putback_zspage
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:fix_fullness_group
```
**Symbols:**

```
ffffffff812b8290-ffffffff812b82fa: insert_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void insert_zspage(struct size_class *class, struct zspage *zspage, enum fullness_group fullness);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff812c5060)
Location: mm/zsmalloc.c:720
Inline: False
Direct callers:
  - mm/zsmalloc.c:putback_zspage
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:fix_fullness_group
```
**Symbols:**

```
ffffffff812c5060-ffffffff812c50ca: insert_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void insert_zspage(struct size_class *class, struct zspage *zspage, enum fullness_group fullness);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff812d5b40)
Location: mm/zsmalloc.c:720
Inline: False
Direct callers:
  - mm/zsmalloc.c:putback_zspage
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:fix_fullness_group
```
**Symbols:**

```
ffffffff812d5b40-ffffffff812d5baa: insert_zspage (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct zspage *zspage</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page *page</code>
</li>
<li>
<b>Param reordered. </b>
<code>page, class, fullness</code> ➡️ <code>class, zspage, fullness</code>
</li>
</ul>
</details>
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
