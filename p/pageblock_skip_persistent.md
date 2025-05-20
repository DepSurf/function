# Function: <code>pageblock_skip_persistent</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff811ff08f)
Location: mm/compaction.c:226
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_suitable
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
In mm/compaction.c (ffffffff8122044f)
Location: mm/compaction.c:226
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_suitable
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
In mm/compaction.c (ffffffff812333cf)
Location: mm/compaction.c:227
Inline: True
Inline callers:
  - mm/compaction.c:__reset_isolation_suitable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool pageblock_skip_persistent(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81243d50)
Location: mm/compaction.c:227
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:__reset_isolation_pfn
```
**Symbols:**

```
ffffffff81243d50-ffffffff81243d91: pageblock_skip_persistent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool pageblock_skip_persistent(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81252210)
Location: mm/compaction.c:227
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:__reset_isolation_pfn
```
**Symbols:**

```
ffffffff81252210-ffffffff81252251: pageblock_skip_persistent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool pageblock_skip_persistent(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81280b50)
Location: mm/compaction.c:227
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages
  - mm/compaction.c:__reset_isolation_pfn
```
**Symbols:**

```
ffffffff81280b50-ffffffff81280b91: pageblock_skip_persistent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool pageblock_skip_persistent(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8128ac20)
Location: mm/compaction.c:244
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages
  - mm/compaction.c:__reset_isolation_pfn
```
**Symbols:**

```
ffffffff8128ac20-ffffffff8128ac61: pageblock_skip_persistent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool pageblock_skip_persistent(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff812902a0)
Location: mm/compaction.c:243
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages
  - mm/compaction.c:__reset_isolation_pfn
```
**Symbols:**

```
ffffffff812902a0-ffffffff812902e1: pageblock_skip_persistent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool pageblock_skip_persistent(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff812d02f0)
Location: mm/compaction.c:243
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages
  - mm/compaction.c:__reset_isolation_pfn
```
**Symbols:**

```
ffffffff812d02f0-ffffffff812d0331: pageblock_skip_persistent (STB_LOCAL)
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
In mm/compaction.c (ffffffff81331bb1)
Location: mm/compaction.c:243
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages
  - mm/compaction.c:__reset_isolation_pfn
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool pageblock_skip_persistent(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff813a6da0)
Location: mm/compaction.c:238
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages
  - mm/compaction.c:__reset_isolation_pfn
```
**Symbols:**

```
ffffffff813a6da0-ffffffff813a6e3c: pageblock_skip_persistent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool pageblock_skip_persistent(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff813da5c0)
Location: mm/compaction.c:264
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages
  - mm/compaction.c:__reset_isolation_pfn
```
**Symbols:**

```
ffffffff813da5c0-ffffffff813da62d: pageblock_skip_persistent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool pageblock_skip_persistent(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff814044b0)
Location: mm/compaction.c:289
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages
  - mm/compaction.c:__reset_isolation_pfn
```
**Symbols:**

```
ffffffff814044b0-ffffffff8140451a: pageblock_skip_persistent (STB_LOCAL)
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
bool pageblock_skip_persistent(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffff8000102e87c8)
Location: mm/compaction.c:227
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:__reset_isolation_pfn
```
**Symbols:**

```
ffff8000102e87c8-ffff8000102e8830: pageblock_skip_persistent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool pageblock_skip_persistent(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (c050d1fc)
Location: mm/compaction.c:227
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:__reset_isolation_pfn
```
**Symbols:**

```
c050d1fc-c050d260: pageblock_skip_persistent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool pageblock_skip_persistent(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (c0000000003ab9a0)
Location: mm/compaction.c:227
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:__reset_isolation_pfn
```
**Symbols:**

```
c0000000003ab9a0-c0000000003aba18: pageblock_skip_persistent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool pageblock_skip_persistent(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffe0001fe5c0)
Location: mm/compaction.c:227
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:__reset_isolation_pfn
```
**Symbols:**

```
ffffffe0001fe5c0-ffffffe0001fe616: pageblock_skip_persistent (STB_LOCAL)
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
bool pageblock_skip_persistent(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8124a860)
Location: mm/compaction.c:227
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:__reset_isolation_pfn
```
**Symbols:**

```
ffffffff8124a860-ffffffff8124a8a1: pageblock_skip_persistent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool pageblock_skip_persistent(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8123d800)
Location: mm/compaction.c:227
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:__reset_isolation_pfn
```
**Symbols:**

```
ffffffff8123d800-ffffffff8123d841: pageblock_skip_persistent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool pageblock_skip_persistent(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81248600)
Location: mm/compaction.c:227
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:__reset_isolation_pfn
```
**Symbols:**

```
ffffffff81248600-ffffffff81248641: pageblock_skip_persistent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool pageblock_skip_persistent(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81257e30)
Location: mm/compaction.c:227
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:__reset_isolation_pfn
```
**Symbols:**

```
ffffffff81257e30-ffffffff81257e71: pageblock_skip_persistent (STB_LOCAL)
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
