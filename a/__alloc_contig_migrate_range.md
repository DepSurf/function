# Function: <code>__alloc_contig_migrate_range</code>

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
In mm/page_alloc.c (ffffffff8119785e)
Location: mm/page_alloc.c:6617
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
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
In mm/page_alloc.c (ffffffff811ac767)
Location: mm/page_alloc.c:7148
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
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
In mm/page_alloc.c (ffffffff811bcd3d)
Location: mm/page_alloc.c:7200
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
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
In mm/page_alloc.c (ffffffff811c4f3e)
Location: mm/page_alloc.c:7530
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
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
In mm/page_alloc.c (ffffffff811d9d10)
Location: mm/page_alloc.c:7554
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
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
In mm/page_alloc.c (ffffffff811fa5eb)
Location: mm/page_alloc.c:7721
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
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
In mm/page_alloc.c (ffffffff8120cd31)
Location: mm/page_alloc.c:8054
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
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
In mm/page_alloc.c (ffffffff81273109)
Location: mm/page_alloc.c:8266
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
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
In mm/page_alloc.c (ffffffff81281f79)
Location: mm/page_alloc.c:8296
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __alloc_contig_migrate_range(struct compact_control *cc, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812aded0)
Location: mm/page_alloc.c:8328
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
```
**Symbols:**

```
ffffffff812aded0-ffffffff812adfd7: __alloc_contig_migrate_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __alloc_contig_migrate_range(struct compact_control *cc, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812b98d0)
Location: mm/page_alloc.c:8456
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
```
**Symbols:**

```
ffffffff812b98d0-ffffffff812b9a18: __alloc_contig_migrate_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812c20e4)
Location: mm/page_alloc.c:8686
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81305a59)
Location: mm/page_alloc.c:8948
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __alloc_contig_migrate_range(struct compact_control *cc, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:9005
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_isolation.c:isolate_single_pageblock
  - mm/page_isolation.c:isolate_single_pageblock
```
**Symbols:**

```
ffffffff81e70498-ffffffff81e704cb: __alloc_contig_migrate_range.cold (STB_LOCAL)
ffffffff81371c70-ffffffff81371e09: __alloc_contig_migrate_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __alloc_contig_migrate_range(struct compact_control *cc, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff813ef450)
Location: mm/page_alloc.c:9179
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_isolation.c:isolate_single_pageblock
  - mm/page_isolation.c:isolate_single_pageblock
```
**Symbols:**

```
ffffffff813ef450-ffffffff813ef616: __alloc_contig_migrate_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __alloc_contig_migrate_range(struct compact_control *cc, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81422fd0)
Location: mm/page_alloc.c:6083
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_isolation.c:isolate_single_pageblock
  - mm/page_isolation.c:isolate_single_pageblock
```
**Symbols:**

```
ffffffff81422fd0-ffffffff81423199: __alloc_contig_migrate_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __alloc_contig_migrate_range(struct compact_control *cc, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8144ff00)
Location: mm/page_alloc.c:6225
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_isolation.c:isolate_single_pageblock
  - mm/page_isolation.c:isolate_single_pageblock
```
**Symbols:**

```
ffffffff8144ff00-ffffffff814500c9: __alloc_contig_migrate_range (STB_GLOBAL)
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
In mm/page_alloc.c (ffff80001031a6cc)
Location: mm/page_alloc.c:8296
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
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
In mm/page_alloc.c (c0534c90)
Location: mm/page_alloc.c:8296
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
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
In mm/page_alloc.c (c0000000003ed9c4)
Location: mm/page_alloc.c:8296
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
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
In mm/page_alloc.c (ffffffe00021fe7c)
Location: mm/page_alloc.c:8296
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
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
In mm/page_alloc.c (ffffffff8127a5c9)
Location: mm/page_alloc.c:8296
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
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
In mm/page_alloc.c (ffffffff8126c4b9)
Location: mm/page_alloc.c:8296
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
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
In mm/page_alloc.c (ffffffff81278369)
Location: mm/page_alloc.c:8296
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
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
In mm/page_alloc.c (ffffffff81287f59)
Location: mm/page_alloc.c:8296
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
