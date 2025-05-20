# Function: <code>update_pageblock_skip</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void update_pageblock_skip(struct compact_control *cc, struct page *page, long unsigned int nr_isolated, bool migrate_scanner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff811b5440)
Location: mm/compaction.c:257
Inline: False
Direct callers:
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:isolate_migratepages_block
```
**Symbols:**

```
ffffffff811b5440-ffffffff811b54e9: update_pageblock_skip (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void update_pageblock_skip(struct compact_control *cc, struct page *page, long unsigned int nr_isolated, bool migrate_scanner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff811cef10)
Location: mm/compaction.c:275
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
**Symbols:**

```
ffffffff811cef10-ffffffff811cefbf: update_pageblock_skip (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void update_pageblock_skip(struct compact_control *cc, struct page *page, long unsigned int nr_isolated, bool migrate_scanner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff811df030)
Location: mm/compaction.c:275
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
**Symbols:**

```
ffffffff811df030-ffffffff811df0e9: update_pageblock_skip (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void update_pageblock_skip(struct compact_control *cc, struct page *page, long unsigned int nr_isolated, bool migrate_scanner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff811e8cc0)
Location: mm/compaction.c:270
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
**Symbols:**

```
ffffffff811e8cc0-ffffffff811e8d72: update_pageblock_skip (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void update_pageblock_skip(struct compact_control *cc, struct page *page, long unsigned int nr_isolated, bool migrate_scanner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff811feee0)
Location: mm/compaction.c:291
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
**Symbols:**

```
ffffffff811feee0-ffffffff811fef92: update_pageblock_skip (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void update_pageblock_skip(struct compact_control *cc, struct page *page, long unsigned int nr_isolated, bool migrate_scanner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff812202d0)
Location: mm/compaction.c:291
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
**Symbols:**

```
ffffffff812202d0-ffffffff81220381: update_pageblock_skip (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void update_pageblock_skip(struct compact_control *cc, struct page *page, long unsigned int nr_isolated, bool migrate_scanner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81233470)
Location: mm/compaction.c:292
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
**Symbols:**

```
ffffffff81233470-ffffffff81233521: update_pageblock_skip (STB_LOCAL)
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
In mm/compaction.c (ffffffff81245472)
Location: mm/compaction.c:427
Inline: True
Inline callers:
  - mm/compaction.c:compaction_alloc
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
In mm/compaction.c (ffffffff81253932)
Location: mm/compaction.c:428
Inline: True
Inline callers:
  - mm/compaction.c:compaction_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff812825e4)
Location: mm/compaction.c:428
Inline: True
Inline callers:
  - mm/compaction.c:isolate_freepages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8128c73d)
Location: mm/compaction.c:445
Inline: True
Inline callers:
  - mm/compaction.c:isolate_freepages
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
In mm/compaction.c (ffffffff81291605)
Location: mm/compaction.c:444
Inline: True
Inline callers:
  - mm/compaction.c:isolate_freepages
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
In mm/compaction.c (ffffffff812d2f63)
Location: mm/compaction.c:442
Inline: True
Inline callers:
  - mm/compaction.c:isolate_freepages
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
In mm/compaction.c (ffffffff813300c8)
Location: mm/compaction.c:441
Inline: True
Inline callers:
  - mm/compaction.c:isolate_freepages
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff813a6c98)
Location: mm/compaction.c:436
Inline: True
Inline callers:
  - mm/compaction.c:isolate_freepages
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
In mm/compaction.c (ffffffff813da4b8)
Location: mm/compaction.c:458
Inline: True
Inline callers:
  - mm/compaction.c:isolate_freepages
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
In mm/compaction.c (ffffffff81404379)
Location: mm/compaction.c:483
Inline: True
Inline callers:
  - mm/compaction.c:isolate_freepages
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
In mm/compaction.c (ffff8000102eae00)
Location: mm/compaction.c:428
Inline: True
Inline callers:
  - mm/compaction.c:compaction_alloc
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
In mm/compaction.c (c050f11c)
Location: mm/compaction.c:428
Inline: True
Inline callers:
  - mm/compaction.c:compaction_alloc
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
In mm/compaction.c (c0000000003addb0)
Location: mm/compaction.c:428
Inline: True
Inline callers:
  - mm/compaction.c:compaction_alloc
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
In mm/compaction.c (ffffffe0001ff336)
Location: mm/compaction.c:428
Inline: True
Inline callers:
  - mm/compaction.c:compaction_alloc
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
In mm/compaction.c (ffffffff8124bf82)
Location: mm/compaction.c:428
Inline: True
Inline callers:
  - mm/compaction.c:compaction_alloc
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
In mm/compaction.c (ffffffff8123ef22)
Location: mm/compaction.c:428
Inline: True
Inline callers:
  - mm/compaction.c:compaction_alloc
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
In mm/compaction.c (ffffffff81249d22)
Location: mm/compaction.c:428
Inline: True
Inline callers:
  - mm/compaction.c:compaction_alloc
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
In mm/compaction.c (ffffffff8125958b)
Location: mm/compaction.c:428
Inline: True
Inline callers:
  - mm/compaction.c:compaction_alloc
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
</ul>
