# Function: <code>__bio_crypt_clone</code>

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
void __bio_crypt_clone(struct bio *dst, struct bio *src, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff81581790)
Location: block/blk-crypto.c:98
Inline: False
Direct callers:
  - block/bio.c:bio_clone_fast
  - drivers/md/dm.c:clone_bio
```
**Symbols:**

```
ffffffff81581790-ffffffff815817e4: __bio_crypt_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __bio_crypt_clone(struct bio *dst, struct bio *src, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff8159e870)
Location: block/blk-crypto.c:106
Inline: False
Direct callers:
  - block/bio.c:bio_clone_fast
  - drivers/md/dm.c:clone_bio
```
**Symbols:**

```
ffffffff8159e870-ffffffff8159e8d2: __bio_crypt_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __bio_crypt_clone(struct bio *dst, struct bio *src, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff815a55f0)
Location: block/blk-crypto.c:106
Inline: False
Direct callers:
  - block/bio.c:bio_clone_fast
  - drivers/md/dm.c:__split_and_process_non_flush
```
**Symbols:**

```
ffffffff815a55f0-ffffffff815a5652: __bio_crypt_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __bio_crypt_clone(struct bio *dst, struct bio *src, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff8160e0c0)
Location: block/blk-crypto.c:106
Inline: False
Direct callers:
  - block/bio.c:bio_clone_fast
  - drivers/md/dm.c:__split_and_process_non_flush
```
**Symbols:**

```
ffffffff8160e0c0-ffffffff8160e122: __bio_crypt_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __bio_crypt_clone(struct bio *dst, struct bio *src, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff816c17d0)
Location: block/blk-crypto.c:109
Inline: False
Direct callers:
  - block/bio.c:__bio_clone
```
**Symbols:**

```
ffffffff816c17d0-ffffffff816c183e: __bio_crypt_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __bio_crypt_clone(struct bio *dst, struct bio *src, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff81782940)
Location: block/blk-crypto.c:115
Inline: False
Direct callers:
  - block/bio.c:__bio_clone
```
**Symbols:**

```
ffffffff81782940-ffffffff817829ae: __bio_crypt_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __bio_crypt_clone(struct bio *dst, struct bio *src, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff817c2ac0)
Location: block/blk-crypto.c:116
Inline: False
Direct callers:
  - block/bio.c:__bio_clone
```
**Symbols:**

```
ffffffff817c2ac0-ffffffff817c2b2e: __bio_crypt_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __bio_crypt_clone(struct bio *dst, struct bio *src, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff81807750)
Location: block/blk-crypto.c:116
Inline: False
Direct callers:
  - block/bio.c:__bio_clone
```
**Symbols:**

```
ffffffff81807750-ffffffff818077be: __bio_crypt_clone (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
