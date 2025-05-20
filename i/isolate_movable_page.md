# Function: <code>isolate_movable_page</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool isolate_movable_page(struct page *page, isolate_mode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81211210)
Location: mm/migrate.c:77
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
```
**Symbols:**

```
ffffffff81211210-ffffffff8121134b: isolate_movable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool isolate_movable_page(struct page *page, isolate_mode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812233d0)
Location: mm/migrate.c:77
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
```
**Symbols:**

```
ffffffff812233d0-ffffffff8122350b: isolate_movable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int isolate_movable_page(struct page *page, isolate_mode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8122ede0)
Location: mm/migrate.c:79
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff8122ede0-ffffffff8122eed8: isolate_movable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int isolate_movable_page(struct page *page, isolate_mode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8124ba90)
Location: mm/migrate.c:83
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff8124ba90-ffffffff8124bbba: isolate_movable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int isolate_movable_page(struct page *page, isolate_mode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8126f530)
Location: mm/migrate.c:84
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff8126f530-ffffffff8126f683: isolate_movable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int isolate_movable_page(struct page *page, isolate_mode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81283bc0)
Location: mm/migrate.c:84
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff81283bc0-ffffffff81283d13: isolate_movable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int isolate_movable_page(struct page *page, isolate_mode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8129edc0)
Location: mm/migrate.c:84
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/memory_hotplug.c:do_migrate_range
```
**Symbols:**

```
ffffffff8129edc0-ffffffff8129eed7: isolate_movable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int isolate_movable_page(struct page *page, isolate_mode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812af7b0)
Location: mm/migrate.c:85
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/memory_hotplug.c:do_migrate_range
```
**Symbols:**

```
ffffffff812af7b0-ffffffff812af8c7: isolate_movable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int isolate_movable_page(struct page *page, isolate_mode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812e5840)
Location: mm/migrate.c:86
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
```
**Symbols:**

```
ffffffff812e5840-ffffffff812e5957: isolate_movable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int isolate_movable_page(struct page *page, isolate_mode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812f0c00)
Location: mm/migrate.c:82
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/memory-failure.c:isolate_page
```
**Symbols:**

```
ffffffff812f0c00-ffffffff812f0d11: isolate_movable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int isolate_movable_page(struct page *page, isolate_mode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812f6f30)
Location: mm/migrate.c:60
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/memory-failure.c:__soft_offline_page
```
**Symbols:**

```
ffffffff812f6f30-ffffffff812f7041: isolate_movable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int isolate_movable_page(struct page *page, isolate_mode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81341590)
Location: mm/migrate.c:61
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/memory-failure.c:__soft_offline_page
```
**Symbols:**

```
ffffffff81341590-ffffffff813416a1: isolate_movable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int isolate_movable_page(struct page *page, isolate_mode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff813b2ff0)
Location: mm/migrate.c:60
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/memory-failure.c:__soft_offline_page
```
**Symbols:**

```
ffffffff813b2ff0-ffffffff813b316d: isolate_movable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int isolate_movable_page(struct page *page, isolate_mode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81433430)
Location: mm/migrate.c:61
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/memory-failure.c:soft_offline_in_use_page
```
**Symbols:**

```
ffffffff81433430-ffffffff8143367c: isolate_movable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool isolate_movable_page(struct page *page, isolate_mode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81469120)
Location: mm/migrate.c:60
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory-failure.c:soft_offline_in_use_page
```
**Symbols:**

```
ffffffff81469120-ffffffff8146920d: isolate_movable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool isolate_movable_page(struct page *page, isolate_mode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81498040)
Location: mm/migrate.c:60
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory-failure.c:soft_offline_in_use_page
```
**Symbols:**

```
ffffffff81498040-ffffffff8149812d: isolate_movable_page (STB_GLOBAL)
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
int isolate_movable_page(struct page *page, isolate_mode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffff8000103505a8)
Location: mm/migrate.c:85
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffff8000103505a8-ffff800010350768: isolate_movable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int isolate_movable_page(struct page *page, isolate_mode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (c0551cb0)
Location: mm/migrate.c:85
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
```
**Symbols:**

```
c0551cb0-c0551e8c: isolate_movable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int isolate_movable_page(struct page *page, isolate_mode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (c0000000004352f0)
Location: mm/migrate.c:85
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/memory_hotplug.c:do_migrate_range
```
**Symbols:**

```
c0000000004352f0-c00000000043556c: isolate_movable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int isolate_movable_page(struct page *page, isolate_mode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffe00023f1ac)
Location: mm/migrate.c:85
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
```
**Symbols:**

```
ffffffe00023f1ac-ffffffe00023f2ac: isolate_movable_page (STB_GLOBAL)
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
int isolate_movable_page(struct page *page, isolate_mode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812a7d90)
Location: mm/migrate.c:85
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/memory_hotplug.c:do_migrate_range
```
**Symbols:**

```
ffffffff812a7d90-ffffffff812a7ea7: isolate_movable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int isolate_movable_page(struct page *page, isolate_mode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81299750)
Location: mm/migrate.c:85
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/memory_hotplug.c:do_migrate_range
```
**Symbols:**

```
ffffffff81299750-ffffffff81299867: isolate_movable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int isolate_movable_page(struct page *page, isolate_mode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812a5ba0)
Location: mm/migrate.c:85
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/memory_hotplug.c:do_migrate_range
```
**Symbols:**

```
ffffffff812a5ba0-ffffffff812a5cb7: isolate_movable_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int isolate_movable_page(struct page *page, isolate_mode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812b5ef0)
Location: mm/migrate.c:85
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/memory_hotplug.c:do_migrate_range
```
**Symbols:**

```
ffffffff812b5ef0-ffffffff812b6007: isolate_movable_page (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
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
