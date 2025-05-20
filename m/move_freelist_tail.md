# Function: <code>move_freelist_tail</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void move_freelist_tail(struct list_head *freelist, struct page *freepage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81242900)
Location: mm/compaction.c:1209
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff81242900-ffffffff812429c3: move_freelist_tail (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void move_freelist_tail(struct list_head *freelist, struct page *freepage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81250dc0)
Location: mm/compaction.c:1210
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff81250dc0-ffffffff81250e83: move_freelist_tail (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void move_freelist_tail(struct list_head *freelist, struct page *freepage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8127f4a0)
Location: mm/compaction.c:1215
Inline: False
Direct callers:
  - mm/compaction.c:fast_find_migrateblock
  - mm/compaction.c:fast_find_migrateblock
```
**Symbols:**

```
ffffffff8127f4a0-ffffffff8127f560: move_freelist_tail (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void move_freelist_tail(struct list_head *freelist, struct page *freepage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81289540)
Location: mm/compaction.c:1276
Inline: False
Direct callers:
  - mm/compaction.c:fast_find_migrateblock
  - mm/compaction.c:fast_find_migrateblock
```
**Symbols:**

```
ffffffff81289540-ffffffff81289600: move_freelist_tail (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void move_freelist_tail(struct list_head *freelist, struct page *freepage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8128eba0)
Location: mm/compaction.c:1312
Inline: False
Direct callers:
  - mm/compaction.c:fast_find_migrateblock
  - mm/compaction.c:fast_find_migrateblock
```
**Symbols:**

```
ffffffff8128eba0-ffffffff8128ec63: move_freelist_tail (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void move_freelist_tail(struct list_head *freelist, struct page *freepage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff812cea60)
Location: mm/compaction.c:1305
Inline: False
Direct callers:
  - mm/compaction.c:fast_find_migrateblock
  - mm/compaction.c:fast_find_migrateblock
```
**Symbols:**

```
ffffffff812cea60-ffffffff812ceb1a: move_freelist_tail (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void move_freelist_tail(struct list_head *freelist, struct page *freepage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8132cba0)
Location: mm/compaction.c:1338
Inline: False
Direct callers:
  - mm/compaction.c:fast_find_migrateblock
  - mm/compaction.c:fast_find_migrateblock
```
**Symbols:**

```
ffffffff8132cba0-ffffffff8132cc6f: move_freelist_tail (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void move_freelist_tail(struct list_head *freelist, struct page *freepage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff813a3180)
Location: mm/compaction.c:1336
Inline: False
Direct callers:
  - mm/compaction.c:fast_find_migrateblock
  - mm/compaction.c:fast_find_migrateblock
```
**Symbols:**

```
ffffffff813a3180-ffffffff813a324f: move_freelist_tail (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void move_freelist_tail(struct list_head *freelist, struct page *freepage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff813d6730)
Location: mm/compaction.c:1389
Inline: False
Direct callers:
  - mm/compaction.c:fast_find_migrateblock
  - mm/compaction.c:fast_find_migrateblock
```
**Symbols:**

```
ffffffff813d6730-ffffffff813d67ff: move_freelist_tail (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void move_freelist_tail(struct list_head *freelist, struct page *freepage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81400400)
Location: mm/compaction.c:1429
Inline: False
Direct callers:
  - mm/compaction.c:fast_find_migrateblock
  - mm/compaction.c:fast_find_migrateblock
```
**Symbols:**

```
ffffffff81400400-ffffffff814004d4: move_freelist_tail (STB_LOCAL)
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
void move_freelist_tail(struct list_head *freelist, struct page *freepage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffff8000102e7fd0)
Location: mm/compaction.c:1210
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffff8000102e7fd0-ffff8000102e80c8: move_freelist_tail (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void move_freelist_tail(struct list_head *freelist, struct page *freepage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (c050c014)
Location: mm/compaction.c:1210
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
c050c014-c050c114: move_freelist_tail (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void move_freelist_tail(struct list_head *freelist, struct page *freepage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (c0000000003a9f70)
Location: mm/compaction.c:1210
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
c0000000003a9f70-c0000000003aa07c: move_freelist_tail (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void move_freelist_tail(struct list_head *freelist, struct page *freepage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffe0001fd9c4)
Location: mm/compaction.c:1210
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffe0001fd9c4-ffffffe0001fda62: move_freelist_tail (STB_LOCAL)
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
void move_freelist_tail(struct list_head *freelist, struct page *freepage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81249410)
Location: mm/compaction.c:1210
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff81249410-ffffffff812494d3: move_freelist_tail (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void move_freelist_tail(struct list_head *freelist, struct page *freepage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8123c3c0)
Location: mm/compaction.c:1210
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff8123c3c0-ffffffff8123c483: move_freelist_tail (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void move_freelist_tail(struct list_head *freelist, struct page *freepage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff812471b0)
Location: mm/compaction.c:1210
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff812471b0-ffffffff81247273: move_freelist_tail (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void move_freelist_tail(struct list_head *freelist, struct page *freepage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff812569e0)
Location: mm/compaction.c:1210
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff812569e0-ffffffff81256aa3: move_freelist_tail (STB_LOCAL)
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
