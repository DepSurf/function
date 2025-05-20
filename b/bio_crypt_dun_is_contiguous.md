# Function: <code>bio_crypt_dun_is_contiguous</code>

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
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool bio_crypt_dun_is_contiguous(const struct bio_crypt_ctx *bc, unsigned int bytes, const u64 *next_dun);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff81581ab5)
Location: block/blk-crypto.c:136
Inline: True
Inline callers:
  - block/blk-crypto.c:bio_crypt_ctx_mergeable
```
**Symbols:**

```
ffffffff81581a10-ffffffff81581a4e: bio_crypt_dun_is_contiguous (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool bio_crypt_dun_is_contiguous(const struct bio_crypt_ctx *bc, unsigned int bytes, const u64 *next_dun);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff8159eaa5)
Location: block/blk-crypto.c:147
Inline: True
Inline callers:
  - block/blk-crypto.c:bio_crypt_ctx_mergeable
Direct callers:
  - fs/crypto/inline_crypt.c:fscrypt_mergeable_bio
```
**Symbols:**

```
ffffffff8159ea00-ffffffff8159ea3e: bio_crypt_dun_is_contiguous (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool bio_crypt_dun_is_contiguous(const struct bio_crypt_ctx *bc, unsigned int bytes, const u64 *next_dun);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff815a5875)
Location: block/blk-crypto.c:147
Inline: True
Inline callers:
  - block/blk-crypto.c:bio_crypt_ctx_mergeable
Direct callers:
  - fs/crypto/inline_crypt.c:fscrypt_mergeable_bio
```
**Symbols:**

```
ffffffff815a57d0-ffffffff815a580b: bio_crypt_dun_is_contiguous (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool bio_crypt_dun_is_contiguous(const struct bio_crypt_ctx *bc, unsigned int bytes, const u64 *next_dun);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-crypto.c (0)
Location: block/blk-crypto.c:147
Inline: False
Direct callers:
  - fs/crypto/inline_crypt.c:fscrypt_mergeable_bio
  - block/blk-crypto.c:bio_crypt_ctx_mergeable
```
**Symbols:**

```
ffffffff81cda688-ffffffff81cda6a7: bio_crypt_dun_is_contiguous.cold (STB_LOCAL)
ffffffff8160e2b0-ffffffff8160e30e: bio_crypt_dun_is_contiguous (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool bio_crypt_dun_is_contiguous(const struct bio_crypt_ctx *bc, unsigned int bytes, const u64 *next_dun);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-crypto.c (0)
Location: block/blk-crypto.c:149
Inline: False
Direct callers:
  - fs/crypto/inline_crypt.c:fscrypt_mergeable_bio
  - block/blk-crypto.c:bio_crypt_ctx_mergeable
```
**Symbols:**

```
ffffffff81e8e1bc-ffffffff81e8e1db: bio_crypt_dun_is_contiguous.cold (STB_LOCAL)
ffffffff816c18f0-ffffffff816c1966: bio_crypt_dun_is_contiguous (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool bio_crypt_dun_is_contiguous(const struct bio_crypt_ctx *bc, unsigned int bytes, const u64 *next_dun);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-crypto.c (0)
Location: block/blk-crypto.c:155
Inline: False
Direct callers:
  - fs/crypto/inline_crypt.c:fscrypt_mergeable_bio
  - block/blk-crypto.c:bio_crypt_ctx_mergeable
```
**Symbols:**

```
ffffffff820773ef-ffffffff8207740e: bio_crypt_dun_is_contiguous.cold (STB_LOCAL)
ffffffff81782a90-ffffffff81782b06: bio_crypt_dun_is_contiguous (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool bio_crypt_dun_is_contiguous(const struct bio_crypt_ctx *bc, unsigned int bytes, const u64 *next_dun);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-crypto.c (0)
Location: block/blk-crypto.c:156
Inline: False
Direct callers:
  - fs/crypto/inline_crypt.c:fscrypt_mergeable_bio
  - block/blk-crypto.c:bio_crypt_ctx_mergeable
```
**Symbols:**

```
ffffffff820f7434-ffffffff820f745a: bio_crypt_dun_is_contiguous.cold (STB_LOCAL)
ffffffff817c2c10-ffffffff817c2ce5: bio_crypt_dun_is_contiguous (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool bio_crypt_dun_is_contiguous(const struct bio_crypt_ctx *bc, unsigned int bytes, const u64 *next_dun);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-crypto.c (0)
Location: block/blk-crypto.c:156
Inline: False
Direct callers:
  - fs/crypto/inline_crypt.c:fscrypt_mergeable_bio
  - block/blk-crypto.c:bio_crypt_ctx_mergeable
```
**Symbols:**

```
ffffffff821d4e5c-ffffffff821d4e82: bio_crypt_dun_is_contiguous.cold (STB_LOCAL)
ffffffff818078a0-ffffffff81807975: bio_crypt_dun_is_contiguous (STB_GLOBAL)
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
