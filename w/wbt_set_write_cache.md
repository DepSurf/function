# Function: <code>wbt_set_write_cache</code>

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
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void wbt_set_write_cache(struct rq_wb *rwb, bool write_cache_on);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff8144ae45)
Location: block/blk-wbt.c:663
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
Direct callers:
  - block/blk-settings.c:blk_queue_write_cache
```
**Symbols:**

```
ffffffff8144acb0-ffffffff8144acca: wbt_set_write_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void wbt_set_write_cache(struct rq_wb *rwb, bool write_cache_on);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff814590d7)
Location: block/blk-wbt.c:650
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
Direct callers:
  - block/blk-settings.c:blk_queue_write_cache
```
**Symbols:**

```
ffffffff81458f30-ffffffff81458f47: wbt_set_write_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void wbt_set_write_cache(struct rq_wb *rwb, bool write_cache_on);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81484e29)
Location: block/blk-wbt.c:649
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
Direct callers:
  - block/blk-settings.c:blk_queue_write_cache
```
**Symbols:**

```
ffffffff81484c90-ffffffff81484ca7: wbt_set_write_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void wbt_set_write_cache(struct rq_wb *rwb, bool write_cache_on);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff814b9d11)
Location: block/blk-wbt.c:682
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
Direct callers:
  - block/blk-settings.c:blk_queue_write_cache
```
**Symbols:**

```
ffffffff814b9b50-ffffffff814b9b67: wbt_set_write_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void wbt_set_write_cache(struct request_queue *q, bool write_cache_on);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff814cde44)
Location: block/blk-wbt.c:640
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
Direct callers:
  - block/blk-settings.c:blk_queue_write_cache
```
**Symbols:**

```
ffffffff814cdc60-ffffffff814cdc8d: wbt_set_write_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void wbt_set_write_cache(struct request_queue *q, bool write_cache_on);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff814fc6f5)
Location: block/blk-wbt.c:641
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
Direct callers:
  - block/blk-settings.c:blk_queue_write_cache
```
**Symbols:**

```
ffffffff814fc500-ffffffff814fc52d: wbt_set_write_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void wbt_set_write_cache(struct request_queue *q, bool write_cache_on);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff8151a652)
Location: block/blk-wbt.c:634
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
Direct callers:
  - block/blk-settings.c:blk_queue_write_cache
```
**Symbols:**

```
ffffffff8151a450-ffffffff8151a47d: wbt_set_write_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void wbt_set_write_cache(struct request_queue *q, bool write_cache_on);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff8157ada2)
Location: block/blk-wbt.c:626
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
Direct callers:
  - block/blk-settings.c:blk_queue_write_cache
```
**Symbols:**

```
ffffffff8157aba0-ffffffff8157abcd: wbt_set_write_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void wbt_set_write_cache(struct request_queue *q, bool write_cache_on);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81597e53)
Location: block/blk-wbt.c:626
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
Direct callers:
  - block/blk-settings.c:blk_queue_write_cache
```
**Symbols:**

```
ffffffff81597c70-ffffffff81597c9d: wbt_set_write_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void wbt_set_write_cache(struct request_queue *q, bool write_cache_on);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff8159ec64)
Location: block/blk-wbt.c:627
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
Direct callers:
  - block/blk-settings.c:blk_queue_write_cache
```
**Symbols:**

```
ffffffff8159ea50-ffffffff8159ea7d: wbt_set_write_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void wbt_set_write_cache(struct request_queue *q, bool write_cache_on);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff816073d4)
Location: block/blk-wbt.c:629
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
Direct callers:
  - block/blk-settings.c:blk_queue_write_cache
```
**Symbols:**

```
ffffffff816071c0-ffffffff816071ed: wbt_set_write_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void wbt_set_write_cache(struct request_queue *q, bool write_cache_on);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff816bafc3)
Location: block/blk-wbt.c:629
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
Direct callers:
  - block/blk-settings.c:blk_queue_write_cache
```
**Symbols:**

```
ffffffff816bad50-ffffffff816bad89: wbt_set_write_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void wbt_set_write_cache(struct request_queue *q, bool write_cache_on);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff8177b3e0)
Location: block/blk-wbt.c:643
Inline: False
Direct callers:
  - block/blk-settings.c:blk_queue_write_cache
```
**Symbols:**

```
ffffffff8177b3e0-ffffffff8177b419: wbt_set_write_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void wbt_set_write_cache(struct request_queue *q, bool write_cache_on);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff817baee0)
Location: block/blk-wbt.c:702
Inline: False
Direct callers:
  - block/blk-settings.c:blk_queue_write_cache
```
**Symbols:**

```
ffffffff817baee0-ffffffff817baf19: wbt_set_write_cache (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void wbt_set_write_cache(struct request_queue *q, bool write_cache_on);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffff800010622504)
Location: block/blk-wbt.c:634
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
Direct callers:
  - block/blk-settings.c:blk_queue_write_cache
  - block/blk-settings.c:blk_queue_write_cache
```
**Symbols:**

```
ffff800010622318-ffff800010622360: wbt_set_write_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void wbt_set_write_cache(struct request_queue *q, bool write_cache_on);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (c07ca0c4)
Location: block/blk-wbt.c:634
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
Direct callers:
  - block/blk-settings.c:blk_queue_write_cache
```
**Symbols:**

```
c07c9ec0-c07c9f04: wbt_set_write_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void wbt_set_write_cache(struct request_queue *q, bool write_cache_on);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (c0000000007c25e4)
Location: block/blk-wbt.c:634
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
Direct callers:
  - block/blk-settings.c:blk_queue_write_cache
  - block/blk-settings.c:blk_queue_write_cache
```
**Symbols:**

```
c0000000007c23d0-c0000000007c2410: wbt_set_write_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void wbt_set_write_cache(struct request_queue *q, bool write_cache_on);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffe0004544f0)
Location: block/blk-wbt.c:634
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
Direct callers:
  - block/blk-settings.c:blk_queue_write_cache
```
**Symbols:**

```
ffffffe000454326-ffffffe00045435e: wbt_set_write_cache (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void wbt_set_write_cache(struct request_queue *q, bool write_cache_on);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81512c32)
Location: block/blk-wbt.c:634
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
Direct callers:
  - block/blk-settings.c:blk_queue_write_cache
```
**Symbols:**

```
ffffffff81512a30-ffffffff81512a5d: wbt_set_write_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void wbt_set_write_cache(struct request_queue *q, bool write_cache_on);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81502f52)
Location: block/blk-wbt.c:634
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
Direct callers:
  - block/blk-settings.c:blk_queue_write_cache
```
**Symbols:**

```
ffffffff81502d50-ffffffff81502d7d: wbt_set_write_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void wbt_set_write_cache(struct request_queue *q, bool write_cache_on);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff8150ecc2)
Location: block/blk-wbt.c:634
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
Direct callers:
  - block/blk-settings.c:blk_queue_write_cache
```
**Symbols:**

```
ffffffff8150eac0-ffffffff8150eaed: wbt_set_write_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void wbt_set_write_cache(struct request_queue *q, bool write_cache_on);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81528492)
Location: block/blk-wbt.c:634
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
Direct callers:
  - block/blk-settings.c:blk_queue_write_cache
```
**Symbols:**

```
ffffffff81528290-ffffffff815282bd: wbt_set_write_cache (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct request_queue *q</code>
</li>
<li>
<b>Param removed. </b>
<code>struct rq_wb *rwb</code>
</li>
</ul>
</details>
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
