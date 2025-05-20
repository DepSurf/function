# Function: <code>fsverity_hash_buffer</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fsverity_hash_buffer(const struct fsverity_hash_alg *alg, const void *data, size_t size, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (ffffffff81350480)
Location: fs/verity/hash_algs.c:232
Inline: False
Direct callers:
  - fs/verity/open.c:fsverity_create_info
```
**Symbols:**

```
ffffffff81350480-ffffffff8135059b: fsverity_hash_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fsverity_hash_buffer(struct fsverity_hash_alg *alg, const void *data, size_t size, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (ffffffff81396e40)
Location: fs/verity/hash_algs.c:281
Inline: False
Direct callers:
  - fs/verity/open.c:fsverity_create_info
```
**Symbols:**

```
ffffffff81396e40-ffffffff81396fd3: fsverity_hash_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fsverity_hash_buffer(struct fsverity_hash_alg *alg, const void *data, size_t size, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (ffffffff813a8a70)
Location: fs/verity/hash_algs.c:281
Inline: False
Direct callers:
  - fs/verity/open.c:fsverity_create_info
```
**Symbols:**

```
ffffffff813a8a70-ffffffff813a8c03: fsverity_hash_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fsverity_hash_buffer(struct fsverity_hash_alg *alg, const void *data, size_t size, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (ffffffff813afae0)
Location: fs/verity/hash_algs.c:281
Inline: False
Direct callers:
  - fs/verity/open.c:fsverity_create_info
```
**Symbols:**

```
ffffffff813afae0-ffffffff813afc72: fsverity_hash_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fsverity_hash_buffer(struct fsverity_hash_alg *alg, const void *data, size_t size, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (ffffffff813ff6d0)
Location: fs/verity/hash_algs.c:281
Inline: False
Direct callers:
  - fs/verity/open.c:fsverity_create_info
```
**Symbols:**

```
ffffffff813ff6d0-ffffffff813ff862: fsverity_hash_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fsverity_hash_buffer(struct fsverity_hash_alg *alg, const void *data, size_t size, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (ffffffff814732f0)
Location: fs/verity/hash_algs.c:281
Inline: False
Direct callers:
  - fs/verity/open.c:fsverity_create_info
```
**Symbols:**

```
ffffffff814732f0-ffffffff814734dd: fsverity_hash_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fsverity_hash_buffer(struct fsverity_hash_alg *alg, const void *data, size_t size, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (ffffffff81505180)
Location: fs/verity/hash_algs.c:283
Inline: False
Direct callers:
  - fs/verity/open.c:fsverity_create_info
```
**Symbols:**

```
ffffffff81505180-ffffffff8150536d: fsverity_hash_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fsverity_hash_buffer(const struct fsverity_hash_alg *alg, const void *data, size_t size, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (ffffffff8153c570)
Location: fs/verity/hash_algs.c:209
Inline: False
Direct callers:
  - fs/verity/open.c:fsverity_create_info
```
**Symbols:**

```
ffffffff8153c570-ffffffff8153c58f: fsverity_hash_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fsverity_hash_buffer(const struct fsverity_hash_alg *alg, const void *data, size_t size, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (ffffffff81571830)
Location: fs/verity/hash_algs.c:209
Inline: False
Direct callers:
  - fs/verity/open.c:fsverity_create_info
```
**Symbols:**

```
ffffffff81571830-ffffffff8157184f: fsverity_hash_buffer (STB_GLOBAL)
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
int fsverity_hash_buffer(const struct fsverity_hash_alg *alg, const void *data, size_t size, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (ffff800010412140)
Location: fs/verity/hash_algs.c:232
Inline: False
Direct callers:
  - fs/verity/open.c:fsverity_create_info
```
**Symbols:**

```
ffff800010412140-ffff800010412268: fsverity_hash_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fsverity_hash_buffer(const struct fsverity_hash_alg *alg, const void *data, size_t size, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (c05de7b4)
Location: fs/verity/hash_algs.c:232
Inline: False
Direct callers:
  - fs/verity/open.c:fsverity_create_info
```
**Symbols:**

```
c05de7b4-c05de8dc: fsverity_hash_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fsverity_hash_buffer(const struct fsverity_hash_alg *alg, const void *data, size_t size, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (c00000000051fe80)
Location: fs/verity/hash_algs.c:232
Inline: False
Direct callers:
  - fs/verity/open.c:fsverity_create_info
```
**Symbols:**

```
c00000000051fe80-c000000000520000: fsverity_hash_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fsverity_hash_buffer(const struct fsverity_hash_alg *alg, const void *data, size_t size, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (ffffffe0002ba1bc)
Location: fs/verity/hash_algs.c:232
Inline: False
Direct callers:
  - fs/verity/open.c:fsverity_create_info
```
**Symbols:**

```
ffffffe0002ba1bc-ffffffe0002ba2b6: fsverity_hash_buffer (STB_GLOBAL)
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
int fsverity_hash_buffer(const struct fsverity_hash_alg *alg, const void *data, size_t size, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (ffffffff81348a60)
Location: fs/verity/hash_algs.c:232
Inline: False
Direct callers:
  - fs/verity/open.c:fsverity_create_info
```
**Symbols:**

```
ffffffff81348a60-ffffffff81348b7b: fsverity_hash_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fsverity_hash_buffer(const struct fsverity_hash_alg *alg, const void *data, size_t size, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (ffffffff81339740)
Location: fs/verity/hash_algs.c:232
Inline: False
Direct callers:
  - fs/verity/open.c:fsverity_create_info
```
**Symbols:**

```
ffffffff81339740-ffffffff8133985b: fsverity_hash_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fsverity_hash_buffer(const struct fsverity_hash_alg *alg, const void *data, size_t size, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (ffffffff81346530)
Location: fs/verity/hash_algs.c:232
Inline: False
Direct callers:
  - fs/verity/open.c:fsverity_create_info
```
**Symbols:**

```
ffffffff81346530-ffffffff8134664b: fsverity_hash_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fsverity_hash_buffer(const struct fsverity_hash_alg *alg, const void *data, size_t size, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/hash_algs.c (ffffffff81359810)
Location: fs/verity/hash_algs.c:232
Inline: False
Direct callers:
  - fs/verity/open.c:fsverity_create_info
```
**Symbols:**

```
ffffffff81359810-ffffffff8135992b: fsverity_hash_buffer (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const struct fsverity_hash_alg *alg</code> ➡️ <code>struct fsverity_hash_alg *alg</code>
</li>
</ul>
</details>
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
<b>Param type changed. </b>
<code>struct fsverity_hash_alg *alg</code> ➡️ <code>const struct fsverity_hash_alg *alg</code>
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
