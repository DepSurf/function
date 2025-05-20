# Function: <code>blk_free_queue_stats</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_free_queue_stats(struct blk_queue_stats *stats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff81434740)
Location: block/blk-stat.c:244
Inline: False
Direct callers:
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
ffffffff81434740-ffffffff81434763: blk_free_queue_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_free_queue_stats(struct blk_queue_stats *stats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff81460350)
Location: block/blk-stat.c:213
Inline: False
Direct callers:
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
ffffffff81460350-ffffffff81460373: blk_free_queue_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_free_queue_stats(struct blk_queue_stats *stats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff81493c40)
Location: block/blk-stat.c:209
Inline: False
Direct callers:
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
ffffffff81493c40-ffffffff81493c62: blk_free_queue_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void blk_free_queue_stats(struct blk_queue_stats *stats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff814add50)
Location: block/blk-stat.c:206
Inline: False
Direct callers:
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
ffffffff814add50-ffffffff814add72: blk_free_queue_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void blk_free_queue_stats(struct blk_queue_stats *stats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-stat.c (0)
Location: block/blk-stat.c:207
Inline: False
Direct callers:
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
ffffffff814dbffc-ffffffff814dc00f: blk_free_queue_stats.cold (STB_LOCAL)
ffffffff814dbfd0-ffffffff814dbffc: blk_free_queue_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blk_free_queue_stats(struct blk_queue_stats *stats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff814f5400)
Location: block/blk-stat.c:207
Inline: False
Direct callers:
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
ffffffff814f5400-ffffffff814f5422: blk_free_queue_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blk_free_queue_stats(struct blk_queue_stats *stats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff81555e20)
Location: block/blk-stat.c:213
Inline: False
Direct callers:
  - block/blk-core.c:__blk_alloc_queue
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
ffffffff81555e20-ffffffff81555e42: blk_free_queue_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_free_queue_stats(struct blk_queue_stats *stats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff81572670)
Location: block/blk-stat.c:213
Inline: False
Direct callers:
  - block/blk-core.c:blk_alloc_queue
  - block/blk-sysfs.c:blk_release_queue
```
**Symbols:**

```
ffffffff81572670-ffffffff81572692: blk_free_queue_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_free_queue_stats(struct blk_queue_stats *stats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff8157a690)
Location: block/blk-stat.c:213
Inline: False
Direct callers:
  - block/blk-core.c:blk_alloc_queue
  - block/blk-sysfs.c:blk_release_queue
```
**Symbols:**

```
ffffffff8157a690-ffffffff8157a6b2: blk_free_queue_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blk_free_queue_stats(struct blk_queue_stats *stats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff815dfa50)
Location: block/blk-stat.c:213
Inline: False
Direct callers:
  - block/blk-core.c:blk_alloc_queue
  - block/blk-sysfs.c:blk_release_queue
```
**Symbols:**

```
ffffffff815dfa50-ffffffff815dfa72: blk_free_queue_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void blk_free_queue_stats(struct blk_queue_stats *stats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff8168e1c0)
Location: block/blk-stat.c:224
Inline: False
Direct callers:
  - block/blk-core.c:blk_alloc_queue
  - block/blk-sysfs.c:blk_release_queue
```
**Symbols:**

```
ffffffff8168e1c0-ffffffff8168e1f2: blk_free_queue_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blk_free_queue_stats(struct blk_queue_stats *stats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff8174cb20)
Location: block/blk-stat.c:224
Inline: False
Direct callers:
  - block/blk-core.c:blk_alloc_queue
  - block/blk-core.c:blk_put_queue
```
**Symbols:**

```
ffffffff8174cb20-ffffffff8174cb52: blk_free_queue_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_free_queue_stats(struct blk_queue_stats *stats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff81789260)
Location: block/blk-stat.c:224
Inline: False
Direct callers:
  - block/blk-core.c:blk_alloc_queue
  - block/blk-core.c:blk_put_queue
```
**Symbols:**

```
ffffffff81789260-ffffffff81789292: blk_free_queue_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blk_free_queue_stats(struct blk_queue_stats *stats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff817cba00)
Location: block/blk-stat.c:224
Inline: False
Direct callers:
  - block/blk-core.c:blk_alloc_queue
  - block/blk-core.c:blk_put_queue
```
**Symbols:**

```
ffffffff817cba00-ffffffff817cba32: blk_free_queue_stats (STB_GLOBAL)
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
void blk_free_queue_stats(struct blk_queue_stats *stats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffff8000105f5550)
Location: block/blk-stat.c:207
Inline: False
Direct callers:
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
ffff8000105f5550-ffff8000105f5594: blk_free_queue_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_free_queue_stats(struct blk_queue_stats *stats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (c07a1030)
Location: block/blk-stat.c:207
Inline: False
Direct callers:
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
c07a1030-c07a1080: blk_free_queue_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_free_queue_stats(struct blk_queue_stats *stats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (c00000000078d1a0)
Location: block/blk-stat.c:207
Inline: False
Direct callers:
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
c00000000078d1a0-c00000000078d1f0: blk_free_queue_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_free_queue_stats(struct blk_queue_stats *stats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffe00043327a)
Location: block/blk-stat.c:207
Inline: False
Direct callers:
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
ffffffe00043327a-ffffffe0004332b0: blk_free_queue_stats (STB_GLOBAL)
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
void blk_free_queue_stats(struct blk_queue_stats *stats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff814ed9e0)
Location: block/blk-stat.c:207
Inline: False
Direct callers:
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
ffffffff814ed9e0-ffffffff814eda02: blk_free_queue_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blk_free_queue_stats(struct blk_queue_stats *stats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff814ddf30)
Location: block/blk-stat.c:207
Inline: False
Direct callers:
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
ffffffff814ddf30-ffffffff814ddf52: blk_free_queue_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blk_free_queue_stats(struct blk_queue_stats *stats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff814e9a70)
Location: block/blk-stat.c:207
Inline: False
Direct callers:
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
ffffffff814e9a70-ffffffff814e9a92: blk_free_queue_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blk_free_queue_stats(struct blk_queue_stats *stats);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff81502a40)
Location: block/blk-stat.c:207
Inline: False
Direct callers:
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
ffffffff81502a40-ffffffff81502a62: blk_free_queue_stats (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
