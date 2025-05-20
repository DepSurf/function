# Function: <code>mb_cache_shrink</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void mb_cache_shrink(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff8126d670)
Location: fs/mbcache.c:396
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_put_super
```
**Symbols:**

```
ffffffff8126d670-ffffffff8126d859: mb_cache_shrink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int mb_cache_shrink(struct mb_cache *cache, unsigned int nr_to_scan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff812989c0)
Location: fs/mbcache.c:276
Inline: False
Direct callers:
  - fs/mbcache.c:mb_cache_shrink_worker
  - fs/mbcache.c:mb_cache_scan
  - fs/mbcache.c:mb_cache_entry_create
```
**Symbols:**

```
ffffffff812989c0-ffffffff81298b15: mb_cache_shrink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int mb_cache_shrink(struct mb_cache *cache, long unsigned int nr_to_scan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff812ad440)
Location: fs/mbcache.c:276
Inline: False
Direct callers:
  - fs/mbcache.c:mb_cache_shrink_worker
  - fs/mbcache.c:mb_cache_scan
  - fs/mbcache.c:mb_cache_entry_create
```
**Symbols:**

```
ffffffff812ad440-ffffffff812ad593: mb_cache_shrink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int mb_cache_shrink(struct mb_cache *cache, long unsigned int nr_to_scan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff812ba8f0)
Location: fs/mbcache.c:276
Inline: False
Direct callers:
  - fs/mbcache.c:mb_cache_shrink_worker
  - fs/mbcache.c:mb_cache_scan
  - fs/mbcache.c:mb_cache_entry_create
```
**Symbols:**

```
ffffffff812ba8f0-ffffffff812baa2e: mb_cache_shrink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int mb_cache_shrink(struct mb_cache *cache, long unsigned int nr_to_scan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff812de1d0)
Location: fs/mbcache.c:280
Inline: False
Direct callers:
  - fs/mbcache.c:mb_cache_shrink_worker
  - fs/mbcache.c:mb_cache_scan
  - fs/mbcache.c:mb_cache_entry_create
```
**Symbols:**

```
ffffffff812de1d0-ffffffff812de30e: mb_cache_shrink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int mb_cache_shrink(struct mb_cache *cache, long unsigned int nr_to_scan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff8130a410)
Location: fs/mbcache.c:279
Inline: False
Direct callers:
  - fs/mbcache.c:mb_cache_shrink_worker
  - fs/mbcache.c:mb_cache_scan
  - fs/mbcache.c:mb_cache_entry_create
```
**Symbols:**

```
ffffffff8130a410-ffffffff8130a54f: mb_cache_shrink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int mb_cache_shrink(struct mb_cache *cache, long unsigned int nr_to_scan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff8131fbf0)
Location: fs/mbcache.c:279
Inline: False
Direct callers:
  - fs/mbcache.c:mb_cache_shrink_worker
  - fs/mbcache.c:mb_cache_scan
  - fs/mbcache.c:mb_cache_entry_create
```
**Symbols:**

```
ffffffff8131fbf0-ffffffff8131fd2f: mb_cache_shrink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int mb_cache_shrink(struct mb_cache *cache, long unsigned int nr_to_scan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff81347450)
Location: fs/mbcache.c:280
Inline: False
Direct callers:
  - fs/mbcache.c:mb_cache_shrink_worker
  - fs/mbcache.c:mb_cache_scan
  - fs/mbcache.c:mb_cache_entry_create
```
**Symbols:**

```
ffffffff81347450-ffffffff813475b1: mb_cache_shrink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int mb_cache_shrink(struct mb_cache *cache, long unsigned int nr_to_scan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff8135f5c0)
Location: fs/mbcache.c:280
Inline: False
Direct callers:
  - fs/mbcache.c:mb_cache_shrink_worker
  - fs/mbcache.c:mb_cache_scan
  - fs/mbcache.c:mb_cache_entry_create
```
**Symbols:**

```
ffffffff8135f5c0-ffffffff8135f721: mb_cache_shrink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int mb_cache_shrink(struct mb_cache *cache, long unsigned int nr_to_scan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff813a51a0)
Location: fs/mbcache.c:280
Inline: False
Direct callers:
  - fs/mbcache.c:mb_cache_shrink_worker
  - fs/mbcache.c:mb_cache_scan
  - fs/mbcache.c:mb_cache_entry_create
```
**Symbols:**

```
ffffffff813a51a0-ffffffff813a52f9: mb_cache_shrink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int mb_cache_shrink(struct mb_cache *cache, long unsigned int nr_to_scan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff813b5f00)
Location: fs/mbcache.c:280
Inline: False
Direct callers:
  - fs/mbcache.c:mb_cache_shrink_worker
  - fs/mbcache.c:mb_cache_scan
  - fs/mbcache.c:mb_cache_entry_create
```
**Symbols:**

```
ffffffff813b5f00-ffffffff813b6059: mb_cache_shrink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int mb_cache_shrink(struct mb_cache *cache, long unsigned int nr_to_scan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff813bd050)
Location: fs/mbcache.c:280
Inline: False
Direct callers:
  - fs/mbcache.c:mb_cache_shrink_worker
  - fs/mbcache.c:mb_cache_scan
  - fs/mbcache.c:mb_cache_entry_create
```
**Symbols:**

```
ffffffff813bd050-ffffffff813bd1a9: mb_cache_shrink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long unsigned int mb_cache_shrink(struct mb_cache *cache, long unsigned int nr_to_scan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/mbcache.c (0)
Location: fs/mbcache.c:280
Inline: False
Direct callers:
  - fs/mbcache.c:mb_cache_shrink_worker
  - fs/mbcache.c:mb_cache_scan
  - fs/mbcache.c:mb_cache_entry_create
```
**Symbols:**

```
ffffffff8140cdd0-ffffffff8140cf5d: mb_cache_shrink (STB_LOCAL)
ffffffff81cc7574-ffffffff81cc759d: mb_cache_shrink.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long unsigned int mb_cache_shrink(struct mb_cache *cache, long unsigned int nr_to_scan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/mbcache.c (0)
Location: fs/mbcache.c:342
Inline: False
Direct callers:
  - fs/mbcache.c:mb_cache_shrink_worker
  - fs/mbcache.c:mb_cache_scan
  - fs/mbcache.c:mb_cache_entry_create
```
**Symbols:**

```
ffffffff81481c40-ffffffff81481e69: mb_cache_shrink (STB_LOCAL)
ffffffff81e79b1a-ffffffff81e79b43: mb_cache_shrink.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int mb_cache_shrink(struct mb_cache *cache, long unsigned int nr_to_scan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff81514a30)
Location: fs/mbcache.c:303
Inline: False
Direct callers:
  - fs/mbcache.c:mb_cache_shrink_worker
  - fs/mbcache.c:mb_cache_scan
  - fs/mbcache.c:mb_cache_entry_create
```
**Symbols:**

```
ffffffff81514a30-ffffffff81514b44: mb_cache_shrink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int mb_cache_shrink(struct mb_cache *cache, long unsigned int nr_to_scan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff8154c440)
Location: fs/mbcache.c:303
Inline: False
Direct callers:
  - fs/mbcache.c:mb_cache_shrink_worker
  - fs/mbcache.c:mb_cache_scan
  - fs/mbcache.c:mb_cache_entry_create
```
**Symbols:**

```
ffffffff8154c440-ffffffff8154c54e: mb_cache_shrink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int mb_cache_shrink(struct mb_cache *cache, long unsigned int nr_to_scan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff81582270)
Location: fs/mbcache.c:302
Inline: False
Direct callers:
  - fs/mbcache.c:mb_cache_shrink_worker
  - fs/mbcache.c:mb_cache_scan
  - fs/mbcache.c:mb_cache_entry_create
```
**Symbols:**

```
ffffffff81582270-ffffffff8158237e: mb_cache_shrink (STB_LOCAL)
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
long unsigned int mb_cache_shrink(struct mb_cache *cache, long unsigned int nr_to_scan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffff8000104251c8)
Location: fs/mbcache.c:280
Inline: False
Direct callers:
  - fs/mbcache.c:mb_cache_shrink_worker
  - fs/mbcache.c:mb_cache_scan
  - fs/mbcache.c:mb_cache_entry_create
```
**Symbols:**

```
ffff8000104251c8-ffff800010425474: mb_cache_shrink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int mb_cache_shrink(struct mb_cache *cache, long unsigned int nr_to_scan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (c05edd54)
Location: fs/mbcache.c:280
Inline: False
Direct callers:
  - fs/mbcache.c:mb_cache_shrink_worker
  - fs/mbcache.c:mb_cache_scan
  - fs/mbcache.c:mb_cache_entry_create
```
**Symbols:**

```
c05edd54-c05edfb8: mb_cache_shrink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int mb_cache_shrink(struct mb_cache *cache, long unsigned int nr_to_scan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (c000000000534410)
Location: fs/mbcache.c:280
Inline: False
Direct callers:
  - fs/mbcache.c:mb_cache_shrink_worker
  - fs/mbcache.c:mb_cache_scan
  - fs/mbcache.c:mb_cache_entry_create
```
**Symbols:**

```
c000000000534410-c0000000005346c8: mb_cache_shrink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int mb_cache_shrink(struct mb_cache *cache, long unsigned int nr_to_scan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffe0002c4382)
Location: fs/mbcache.c:280
Inline: False
Direct callers:
  - fs/mbcache.c:mb_cache_shrink_worker
  - fs/mbcache.c:mb_cache_scan
  - fs/mbcache.c:mb_cache_entry_create
```
**Symbols:**

```
ffffffe0002c4382-ffffffe0002c456e: mb_cache_shrink (STB_LOCAL)
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
long unsigned int mb_cache_shrink(struct mb_cache *cache, long unsigned int nr_to_scan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff81357ba0)
Location: fs/mbcache.c:280
Inline: False
Direct callers:
  - fs/mbcache.c:mb_cache_shrink_worker
  - fs/mbcache.c:mb_cache_scan
  - fs/mbcache.c:mb_cache_entry_create
```
**Symbols:**

```
ffffffff81357ba0-ffffffff81357d01: mb_cache_shrink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int mb_cache_shrink(struct mb_cache *cache, long unsigned int nr_to_scan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff81348850)
Location: fs/mbcache.c:280
Inline: False
Direct callers:
  - fs/mbcache.c:mb_cache_shrink_worker
  - fs/mbcache.c:mb_cache_scan
  - fs/mbcache.c:mb_cache_entry_create
```
**Symbols:**

```
ffffffff81348850-ffffffff813489b1: mb_cache_shrink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int mb_cache_shrink(struct mb_cache *cache, long unsigned int nr_to_scan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff81355670)
Location: fs/mbcache.c:280
Inline: False
Direct callers:
  - fs/mbcache.c:mb_cache_shrink_worker
  - fs/mbcache.c:mb_cache_scan
  - fs/mbcache.c:mb_cache_entry_create
```
**Symbols:**

```
ffffffff81355670-ffffffff813557d1: mb_cache_shrink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int mb_cache_shrink(struct mb_cache *cache, long unsigned int nr_to_scan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mbcache.c (ffffffff81368c50)
Location: fs/mbcache.c:280
Inline: False
Direct callers:
  - fs/mbcache.c:mb_cache_shrink_worker
  - fs/mbcache.c:mb_cache_scan
  - fs/mbcache.c:mb_cache_entry_create
```
**Symbols:**

```
ffffffff81368c50-ffffffff81368dfb: mb_cache_shrink (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mb_cache *cache</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int nr_to_scan</code>
</li>
<li>
<b>Param removed. </b>
<code>struct block_device *bdev</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>long unsigned int</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>unsigned int nr_to_scan</code> ➡️ <code>long unsigned int nr_to_scan</code>
</li>
</ul>
</details>
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
