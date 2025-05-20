# Function: <code>__entry_find</code>

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
struct mb_cache_entry *__entry_find(struct mb_cache *cache, struct mb_cache_entry *entry, u32 key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff81298d90)
Location: fs/mbcache.c:125
Inline: False
Direct callers:
  - fs/mbcache.c:mb_cache_entry_find_next
  - fs/mbcache.c:mb_cache_entry_find_first
```
**Symbols:**

```
ffffffff81298d90-ffffffff81298e27: __entry_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct mb_cache_entry *__entry_find(struct mb_cache *cache, struct mb_cache_entry *entry, u32 key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff812ad800)
Location: fs/mbcache.c:125
Inline: False
Direct callers:
  - fs/mbcache.c:mb_cache_entry_find_next
  - fs/mbcache.c:mb_cache_entry_find_first
```
**Symbols:**

```
ffffffff812ad800-ffffffff812ad897: __entry_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct mb_cache_entry *__entry_find(struct mb_cache *cache, struct mb_cache_entry *entry, u32 key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff812bac90)
Location: fs/mbcache.c:126
Inline: False
Direct callers:
  - fs/mbcache.c:mb_cache_entry_find_next
  - fs/mbcache.c:mb_cache_entry_find_first
```
**Symbols:**

```
ffffffff812bac90-ffffffff812bad2a: __entry_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct mb_cache_entry *__entry_find(struct mb_cache *cache, struct mb_cache_entry *entry, u32 key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff812de570)
Location: fs/mbcache.c:127
Inline: False
Direct callers:
  - fs/mbcache.c:mb_cache_entry_find_next
  - fs/mbcache.c:mb_cache_entry_find_first
```
**Symbols:**

```
ffffffff812de570-ffffffff812de60a: __entry_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct mb_cache_entry *__entry_find(struct mb_cache *cache, struct mb_cache_entry *entry, u32 key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff8130a330)
Location: fs/mbcache.c:127
Inline: False
Direct callers:
  - fs/mbcache.c:mb_cache_entry_find_next
  - fs/mbcache.c:mb_cache_entry_find_first
```
**Symbols:**

```
ffffffff8130a330-ffffffff8130a3c9: __entry_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct mb_cache_entry *__entry_find(struct mb_cache *cache, struct mb_cache_entry *entry, u32 key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff8131fde0)
Location: fs/mbcache.c:127
Inline: False
Direct callers:
  - fs/mbcache.c:mb_cache_entry_find_next
  - fs/mbcache.c:mb_cache_entry_find_first
```
**Symbols:**

```
ffffffff8131fde0-ffffffff8131fe7b: __entry_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct mb_cache_entry *__entry_find(struct mb_cache *cache, struct mb_cache_entry *entry, u32 key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff81347670)
Location: fs/mbcache.c:128
Inline: False
Direct callers:
  - fs/mbcache.c:mb_cache_entry_find_next
  - fs/mbcache.c:mb_cache_entry_find_first
```
**Symbols:**

```
ffffffff81347670-ffffffff81347719: __entry_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct mb_cache_entry *__entry_find(struct mb_cache *cache, struct mb_cache_entry *entry, u32 key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff8135f9a0)
Location: fs/mbcache.c:128
Inline: False
Direct callers:
  - fs/mbcache.c:mb_cache_entry_find_next
  - fs/mbcache.c:mb_cache_entry_find_first
```
**Symbols:**

```
ffffffff8135f9a0-ffffffff8135fa49: __entry_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/mbcache.c (ffffffff813a53b0)
Location: fs/mbcache.c:128
Inline: True
Direct callers:
  - fs/mbcache.c:mb_cache_entry_find_next
  - fs/mbcache.c:mb_cache_entry_find_first
```
**Symbols:**

```
ffffffff813a53b0-ffffffff813a5462: __entry_find.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/mbcache.c (ffffffff813b6110)
Location: fs/mbcache.c:128
Inline: True
Direct callers:
  - fs/mbcache.c:mb_cache_entry_find_next
  - fs/mbcache.c:mb_cache_entry_find_first
```
**Symbols:**

```
ffffffff813b6110-ffffffff813b61c2: __entry_find.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/mbcache.c (ffffffff813bcf50)
Location: fs/mbcache.c:128
Inline: True
Direct callers:
  - fs/mbcache.c:mb_cache_entry_find_next
  - fs/mbcache.c:mb_cache_entry_find_first
```
**Symbols:**

```
ffffffff813bcf50-ffffffff813bd002: __entry_find.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/mbcache.c (0)
Location: fs/mbcache.c:128
Inline: True
Direct callers:
  - fs/mbcache.c:mb_cache_entry_find_next
  - fs/mbcache.c:mb_cache_entry_find_first
```
**Symbols:**

```
ffffffff8140ccb0-ffffffff8140cd8b: __entry_find.isra.0 (STB_LOCAL)
ffffffff81cc7555-ffffffff81cc7574: __entry_find.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/mbcache.c (0)
Location: fs/mbcache.c:141
Inline: True
Direct callers:
  - fs/mbcache.c:mb_cache_entry_find_next
  - fs/mbcache.c:mb_cache_entry_find_first
```
**Symbols:**

```
ffffffff81481fa0-ffffffff814820d3: __entry_find.isra.0 (STB_LOCAL)
ffffffff81e79b62-ffffffff81e79b80: __entry_find.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct mb_cache_entry *__entry_find(struct mb_cache *cache, struct mb_cache_entry *entry, u32 key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/mbcache.c (0)
Location: fs/mbcache.c:152
Inline: False
Direct callers:
  - fs/mbcache.c:mb_cache_entry_find_next
  - fs/mbcache.c:mb_cache_entry_find_first
```
**Symbols:**

```
ffffffff815150d0-ffffffff815151f6: __entry_find (STB_LOCAL)
ffffffff8206abe3-ffffffff8206ac02: __entry_find.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct mb_cache_entry *__entry_find(struct mb_cache *cache, struct mb_cache_entry *entry, u32 key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/mbcache.c (0)
Location: fs/mbcache.c:152
Inline: False
Direct callers:
  - fs/mbcache.c:mb_cache_entry_find_next
  - fs/mbcache.c:mb_cache_entry_find_first
```
**Symbols:**

```
ffffffff8154cad0-ffffffff8154cbf6: __entry_find (STB_LOCAL)
ffffffff820eab52-ffffffff820eab71: __entry_find.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct mb_cache_entry *__entry_find(struct mb_cache *cache, struct mb_cache_entry *entry, u32 key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/mbcache.c (0)
Location: fs/mbcache.c:152
Inline: False
Direct callers:
  - fs/mbcache.c:mb_cache_entry_find_next
  - fs/mbcache.c:mb_cache_entry_find_first
```
**Symbols:**

```
ffffffff81582900-ffffffff81582a26: __entry_find (STB_LOCAL)
ffffffff821c78cd-ffffffff821c78ec: __entry_find.cold (STB_LOCAL)
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
struct mb_cache_entry *__entry_find(struct mb_cache *cache, struct mb_cache_entry *entry, u32 key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffff800010425898)
Location: fs/mbcache.c:128
Inline: False
Direct callers:
  - fs/mbcache.c:mb_cache_entry_find_next
  - fs/mbcache.c:mb_cache_entry_find_first
```
**Symbols:**

```
ffff800010425898-ffff800010425a10: __entry_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct mb_cache_entry *__entry_find(struct mb_cache *cache, struct mb_cache_entry *entry, u32 key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (c05ee3e8)
Location: fs/mbcache.c:128
Inline: False
Direct callers:
  - fs/mbcache.c:mb_cache_entry_find_next
  - fs/mbcache.c:mb_cache_entry_find_first
```
**Symbols:**

```
c05ee3e8-c05ee594: __entry_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct mb_cache_entry *__entry_find(struct mb_cache *cache, struct mb_cache_entry *entry, u32 key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (c000000000534800)
Location: fs/mbcache.c:128
Inline: False
Direct callers:
  - fs/mbcache.c:mb_cache_entry_find_next
  - fs/mbcache.c:mb_cache_entry_find_first
```
**Symbols:**

```
c000000000534800-c000000000534998: __entry_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct mb_cache_entry *__entry_find(struct mb_cache *cache, struct mb_cache_entry *entry, u32 key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffe0002c4234)
Location: fs/mbcache.c:128
Inline: False
Direct callers:
  - fs/mbcache.c:mb_cache_entry_find_next
  - fs/mbcache.c:mb_cache_entry_find_first
```
**Symbols:**

```
ffffffe0002c4234-ffffffe0002c431a: __entry_find (STB_LOCAL)
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
struct mb_cache_entry *__entry_find(struct mb_cache *cache, struct mb_cache_entry *entry, u32 key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff81357f80)
Location: fs/mbcache.c:128
Inline: False
Direct callers:
  - fs/mbcache.c:mb_cache_entry_find_next
  - fs/mbcache.c:mb_cache_entry_find_first
```
**Symbols:**

```
ffffffff81357f80-ffffffff81358029: __entry_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct mb_cache_entry *__entry_find(struct mb_cache *cache, struct mb_cache_entry *entry, u32 key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff81348c30)
Location: fs/mbcache.c:128
Inline: False
Direct callers:
  - fs/mbcache.c:mb_cache_entry_find_next
  - fs/mbcache.c:mb_cache_entry_find_first
```
**Symbols:**

```
ffffffff81348c30-ffffffff81348cd9: __entry_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct mb_cache_entry *__entry_find(struct mb_cache *cache, struct mb_cache_entry *entry, u32 key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff81355a50)
Location: fs/mbcache.c:128
Inline: False
Direct callers:
  - fs/mbcache.c:mb_cache_entry_find_next
  - fs/mbcache.c:mb_cache_entry_find_first
```
**Symbols:**

```
ffffffff81355a50-ffffffff81355af9: __entry_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct mb_cache_entry *__entry_find(struct mb_cache *cache, struct mb_cache_entry *entry, u32 key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff813690d0)
Location: fs/mbcache.c:128
Inline: False
Direct callers:
  - fs/mbcache.c:mb_cache_entry_find_next
  - fs/mbcache.c:mb_cache_entry_find_first
```
**Symbols:**

```
ffffffff813690d0-ffffffff813691a0: __entry_find (STB_LOCAL)
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
