# Function: <code>unreserve_highatomic_pageblock</code>

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
In mm/page_alloc.c (ffffffff81196e58)
Location: mm/page_alloc.c:1684
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
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
In mm/page_alloc.c (ffffffff811aa925)
Location: mm/page_alloc.c:2043
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool unreserve_highatomic_pageblock(const struct alloc_context *ac, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811b8dc0)
Location: mm/page_alloc.c:2065
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
ffffffff811b8dc0-ffffffff811b8f55: unreserve_highatomic_pageblock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool unreserve_highatomic_pageblock(const struct alloc_context *ac, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811c0cc0)
Location: mm/page_alloc.c:2135
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
ffffffff811c0cc0-ffffffff811c0e46: unreserve_highatomic_pageblock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool unreserve_highatomic_pageblock(const struct alloc_context *ac, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811d5280)
Location: mm/page_alloc.c:2173
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
ffffffff811d5280-ffffffff811d5406: unreserve_highatomic_pageblock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool unreserve_highatomic_pageblock(const struct alloc_context *ac, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811f66e0)
Location: mm/page_alloc.c:2282
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
ffffffff811f66e0-ffffffff811f687e: unreserve_highatomic_pageblock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool unreserve_highatomic_pageblock(const struct alloc_context *ac, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81208a50)
Location: mm/page_alloc.c:2361
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
ffffffff81208a50-ffffffff81208bee: unreserve_highatomic_pageblock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool unreserve_highatomic_pageblock(const struct alloc_context *ac, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8126eea0)
Location: mm/page_alloc.c:2540
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
ffffffff8126eea0-ffffffff8126f024: unreserve_highatomic_pageblock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool unreserve_highatomic_pageblock(const struct alloc_context *ac, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8127dce0)
Location: mm/page_alloc.c:2531
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
ffffffff8127dce0-ffffffff8127de64: unreserve_highatomic_pageblock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool unreserve_highatomic_pageblock(const struct alloc_context *ac, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812afeb0)
Location: mm/page_alloc.c:2609
Inline: False
```
**Symbols:**

```
ffffffff812afeb0-ffffffff812b007d: unreserve_highatomic_pageblock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool unreserve_highatomic_pageblock(const struct alloc_context *ac, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812bbb30)
Location: mm/page_alloc.c:2688
Inline: False
```
**Symbols:**

```
ffffffff812bbb30-ffffffff812bbcf2: unreserve_highatomic_pageblock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool unreserve_highatomic_pageblock(const struct alloc_context *ac, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812c0b90)
Location: mm/page_alloc.c:2737
Inline: False
```
**Symbols:**

```
ffffffff812c0b90-ffffffff812c0d48: unreserve_highatomic_pageblock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool unreserve_highatomic_pageblock(const struct alloc_context *ac, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81303b10)
Location: mm/page_alloc.c:2810
Inline: False
```
**Symbols:**

```
ffffffff81303b10-ffffffff81303ce6: unreserve_highatomic_pageblock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool unreserve_highatomic_pageblock(const struct alloc_context *ac, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8136bb70)
Location: mm/page_alloc.c:2835
Inline: False
```
**Symbols:**

```
ffffffff8136bb70-ffffffff8136bdc3: unreserve_highatomic_pageblock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool unreserve_highatomic_pageblock(const struct alloc_context *ac, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff813e7ec0)
Location: mm/page_alloc.c:2914
Inline: False
```
**Symbols:**

```
ffffffff813e7ec0-ffffffff813e8113: unreserve_highatomic_pageblock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool unreserve_highatomic_pageblock(const struct alloc_context *ac, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8141cfa0)
Location: mm/page_alloc.c:1957
Inline: False
```
**Symbols:**

```
ffffffff8141cfa0-ffffffff8141d1f4: unreserve_highatomic_pageblock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool unreserve_highatomic_pageblock(const struct alloc_context *ac, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81449a40)
Location: mm/page_alloc.c:1922
Inline: False
```
**Symbols:**

```
ffffffff81449a40-ffffffff81449c94: unreserve_highatomic_pageblock (STB_LOCAL)
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
bool unreserve_highatomic_pageblock(const struct alloc_context *ac, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff800010315660)
Location: mm/page_alloc.c:2531
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
ffff800010315660-ffff80001031586c: unreserve_highatomic_pageblock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool unreserve_highatomic_pageblock(const struct alloc_context *ac, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c052fed8)
Location: mm/page_alloc.c:2531
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
c052fed8-c05300c8: unreserve_highatomic_pageblock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool unreserve_highatomic_pageblock(const struct alloc_context *ac, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0000000003e7590)
Location: mm/page_alloc.c:2531
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
c0000000003e7590-c0000000003e7834: unreserve_highatomic_pageblock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool unreserve_highatomic_pageblock(const struct alloc_context *ac, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe00021bfc6)
Location: mm/page_alloc.c:2531
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
ffffffe00021bfc6-ffffffe00021c132: unreserve_highatomic_pageblock (STB_LOCAL)
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
bool unreserve_highatomic_pageblock(const struct alloc_context *ac, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81276330)
Location: mm/page_alloc.c:2531
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
ffffffff81276330-ffffffff812764b4: unreserve_highatomic_pageblock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool unreserve_highatomic_pageblock(const struct alloc_context *ac, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81268280)
Location: mm/page_alloc.c:2531
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
ffffffff81268280-ffffffff81268404: unreserve_highatomic_pageblock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool unreserve_highatomic_pageblock(const struct alloc_context *ac, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812740d0)
Location: mm/page_alloc.c:2531
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
ffffffff812740d0-ffffffff81274254: unreserve_highatomic_pageblock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool unreserve_highatomic_pageblock(const struct alloc_context *ac, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81283bd0)
Location: mm/page_alloc.c:2531
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
**Symbols:**

```
ffffffff81283bd0-ffffffff81283d54: unreserve_highatomic_pageblock (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
