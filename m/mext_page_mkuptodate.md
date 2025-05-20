# Function: <code>mext_page_mkuptodate</code>

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
In fs/ext4/move_extent.c (ffffffff812d682e)
Location: fs/ext4/move_extent.c:177
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
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
In fs/ext4/move_extent.c (ffffffff813064cc)
Location: fs/ext4/move_extent.c:177
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
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
In fs/ext4/move_extent.c (ffffffff8131c48c)
Location: fs/ext4/move_extent.c:177
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
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
In fs/ext4/move_extent.c (ffffffff81315037)
Location: fs/ext4/move_extent.c:177
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
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
In fs/ext4/move_extent.c (ffffffff81339b15)
Location: fs/ext4/move_extent.c:177
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
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
In fs/ext4/move_extent.c (ffffffff813680e2)
Location: fs/ext4/move_extent.c:169
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
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
In fs/ext4/move_extent.c (ffffffff81380564)
Location: fs/ext4/move_extent.c:167
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int mext_page_mkuptodate(struct page *page, unsigned int from, unsigned int to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/move_extent.c (ffffffff813a93c0)
Location: fs/ext4/move_extent.c:167
Inline: False
Direct callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffff813a93c0-ffffffff813a96c9: mext_page_mkuptodate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int mext_page_mkuptodate(struct page *page, unsigned int from, unsigned int to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/move_extent.c (ffffffff813c22e0)
Location: fs/ext4/move_extent.c:167
Inline: False
Direct callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffff813c22e0-ffffffff813c25f8: mext_page_mkuptodate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int mext_page_mkuptodate(struct page *page, unsigned int from, unsigned int to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/move_extent.c (ffffffff8140e9a0)
Location: fs/ext4/move_extent.c:167
Inline: False
```
**Symbols:**

```
ffffffff8140e9a0-ffffffff8140ecf4: mext_page_mkuptodate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mext_page_mkuptodate(struct page *page, unsigned int from, unsigned int to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/move_extent.c (ffffffff81421ef0)
Location: fs/ext4/move_extent.c:167
Inline: False
```
**Symbols:**

```
ffffffff81421ef0-ffffffff814221bf: mext_page_mkuptodate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mext_page_mkuptodate(struct page *page, unsigned int from, unsigned int to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/move_extent.c (ffffffff814285b0)
Location: fs/ext4/move_extent.c:167
Inline: False
```
**Symbols:**

```
ffffffff814285b0-ffffffff81428883: mext_page_mkuptodate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int mext_page_mkuptodate(struct page *page, unsigned int from, unsigned int to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/move_extent.c (0)
Location: fs/ext4/move_extent.c:167
Inline: False
```
**Symbols:**

```
ffffffff8147c2f0-ffffffff8147c646: mext_page_mkuptodate (STB_LOCAL)
ffffffff81ccc9c3-ffffffff81ccca39: mext_page_mkuptodate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int mext_page_mkuptodate(struct page *page, unsigned int from, unsigned int to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/move_extent.c (0)
Location: fs/ext4/move_extent.c:172
Inline: False
```
**Symbols:**

```
ffffffff814fea40-ffffffff814fee8d: mext_page_mkuptodate (STB_LOCAL)
ffffffff81e7f8ac-ffffffff81e7f922: mext_page_mkuptodate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int mext_page_mkuptodate(struct page *page, unsigned int from, unsigned int to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/move_extent.c (0)
Location: fs/ext4/move_extent.c:169
Inline: False
```
**Symbols:**

```
ffffffff81599290-ffffffff815996e7: mext_page_mkuptodate (STB_LOCAL)
ffffffff8206fd9e-ffffffff8206fe14: mext_page_mkuptodate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int mext_page_mkuptodate(struct folio *folio, unsigned int from, unsigned int to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/move_extent.c (0)
Location: fs/ext4/move_extent.c:171
Inline: False
```
**Symbols:**

```
ffffffff815cfcb0-ffffffff815cffdf: mext_page_mkuptodate (STB_LOCAL)
ffffffff820ef942-ffffffff820ef9b8: mext_page_mkuptodate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int mext_page_mkuptodate(struct folio *folio, unsigned int from, unsigned int to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/move_extent.c (0)
Location: fs/ext4/move_extent.c:171
Inline: False
```
**Symbols:**

```
ffffffff81608530-ffffffff8160885b: mext_page_mkuptodate (STB_LOCAL)
ffffffff821cca21-ffffffff821cca97: mext_page_mkuptodate.cold (STB_LOCAL)
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
int mext_page_mkuptodate(struct page *page, unsigned int from, unsigned int to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/move_extent.c (ffff800010499ce8)
Location: fs/ext4/move_extent.c:167
Inline: False
Direct callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffff800010499ce8-ffff80001049a068: mext_page_mkuptodate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mext_page_mkuptodate(struct page *page, unsigned int from, unsigned int to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/move_extent.c (c065b4fc)
Location: fs/ext4/move_extent.c:167
Inline: False
Direct callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
c065b4fc-c065b810: mext_page_mkuptodate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int mext_page_mkuptodate(struct page *page, unsigned int from, unsigned int to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/move_extent.c (c0000000005c3f70)
Location: fs/ext4/move_extent.c:167
Inline: False
Direct callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
c0000000005c3f70-c0000000005c43a0: mext_page_mkuptodate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int mext_page_mkuptodate(struct page *page, unsigned int from, unsigned int to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/move_extent.c (ffffffe00031d4c6)
Location: fs/ext4/move_extent.c:167
Inline: False
Direct callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffe00031d4c6-ffffffe00031d796: mext_page_mkuptodate (STB_LOCAL)
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
int mext_page_mkuptodate(struct page *page, unsigned int from, unsigned int to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/move_extent.c (ffffffff813ba8c0)
Location: fs/ext4/move_extent.c:167
Inline: False
Direct callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffff813ba8c0-ffffffff813babd8: mext_page_mkuptodate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int mext_page_mkuptodate(struct page *page, unsigned int from, unsigned int to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/move_extent.c (ffffffff813ab350)
Location: fs/ext4/move_extent.c:167
Inline: False
Direct callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffff813ab350-ffffffff813ab668: mext_page_mkuptodate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int mext_page_mkuptodate(struct page *page, unsigned int from, unsigned int to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/move_extent.c (ffffffff813b8120)
Location: fs/ext4/move_extent.c:167
Inline: False
Direct callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffff813b8120-ffffffff813b8438: mext_page_mkuptodate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int mext_page_mkuptodate(struct page *page, unsigned int from, unsigned int to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/move_extent.c (ffffffff813cce20)
Location: fs/ext4/move_extent.c:167
Inline: False
Direct callers:
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffff813cce20-ffffffff813cd152: mext_page_mkuptodate (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct folio *folio</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page *page</code>
</li>
</ul>
</details>
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
