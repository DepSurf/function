# Function: <code>__putback_isolated_page</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __putback_isolated_page(struct page *page, unsigned int order, int mt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812b2020)
Location: mm/page_alloc.c:3263
Inline: False
Direct callers:
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffff812b2020-ffffffff812b2066: __putback_isolated_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __putback_isolated_page(struct page *page, unsigned int order, int mt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812bd9e0)
Location: mm/page_alloc.c:3364
Inline: False
Direct callers:
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffff812bd9e0-ffffffff812bda29: __putback_isolated_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __putback_isolated_page(struct page *page, unsigned int order, int mt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812c2990)
Location: mm/page_alloc.c:3413
Inline: False
Direct callers:
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffff812c2990-ffffffff812c29d9: __putback_isolated_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __putback_isolated_page(struct page *page, unsigned int order, int mt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81306510)
Location: mm/page_alloc.c:3560
Inline: False
Direct callers:
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffff81306510-ffffffff8130659d: __putback_isolated_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __putback_isolated_page(struct page *page, unsigned int order, int mt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8136e6e0)
Location: mm/page_alloc.c:3596
Inline: False
Direct callers:
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffff8136e6e0-ffffffff8136e782: __putback_isolated_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __putback_isolated_page(struct page *page, unsigned int order, int mt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff813eabd0)
Location: mm/page_alloc.c:3654
Inline: False
Direct callers:
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffff813eabd0-ffffffff813eac72: __putback_isolated_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __putback_isolated_page(struct page *page, unsigned int order, int mt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8141fb30)
Location: mm/page_alloc.c:2633
Inline: False
Direct callers:
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffff8141fb30-ffffffff8141fbd2: __putback_isolated_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __putback_isolated_page(struct page *page, unsigned int order, int mt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8144c750)
Location: mm/page_alloc.c:2676
Inline: False
Direct callers:
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffff8144c750-ffffffff8144c7f2: __putback_isolated_page (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
