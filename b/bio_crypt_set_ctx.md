# Function: <code>bio_crypt_set_ctx</code>

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
void bio_crypt_set_ctx(struct bio *bio, const struct blk_crypto_key *key, const u64 *dun, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff815818f0)
Location: block/blk-crypto.c:81
Inline: False
```
**Symbols:**

```
ffffffff815818f0-ffffffff81581943: bio_crypt_set_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bio_crypt_set_ctx(struct bio *bio, const struct blk_crypto_key *key, const u64 *dun, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff8159e8e0)
Location: block/blk-crypto.c:81
Inline: False
```
**Symbols:**

```
ffffffff8159e8e0-ffffffff8159e93f: bio_crypt_set_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bio_crypt_set_ctx(struct bio *bio, const struct blk_crypto_key *key, const u64 *dun, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff815a56b0)
Location: block/blk-crypto.c:81
Inline: False
```
**Symbols:**

```
ffffffff815a56b0-ffffffff815a570f: bio_crypt_set_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void bio_crypt_set_ctx(struct bio *bio, const struct blk_crypto_key *key, const u64 *dun, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff8160e180)
Location: block/blk-crypto.c:81
Inline: False
```
**Symbols:**

```
ffffffff8160e180-ffffffff8160e1df: bio_crypt_set_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void bio_crypt_set_ctx(struct bio *bio, const struct blk_crypto_key *key, const u64 *dun, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff816c1720)
Location: block/blk-crypto.c:84
Inline: False
Direct callers:
  - fs/crypto/inline_crypt.c:fscrypt_set_bio_crypt_ctx
```
**Symbols:**

```
ffffffff816c1720-ffffffff816c178d: bio_crypt_set_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bio_crypt_set_ctx(struct bio *bio, const struct blk_crypto_key *key, const u64 *dun, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff81782870)
Location: block/blk-crypto.c:90
Inline: False
Direct callers:
  - fs/crypto/inline_crypt.c:fscrypt_set_bio_crypt_ctx
```
**Symbols:**

```
ffffffff81782870-ffffffff817828dd: bio_crypt_set_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bio_crypt_set_ctx(struct bio *bio, const struct blk_crypto_key *key, const u64 *dun, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff817c29f0)
Location: block/blk-crypto.c:91
Inline: False
Direct callers:
  - fs/crypto/inline_crypt.c:fscrypt_set_bio_crypt_ctx
```
**Symbols:**

```
ffffffff817c29f0-ffffffff817c2a5d: bio_crypt_set_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bio_crypt_set_ctx(struct bio *bio, const struct blk_crypto_key *key, const u64 *dun, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff81807680)
Location: block/blk-crypto.c:91
Inline: False
Direct callers:
  - fs/crypto/inline_crypt.c:fscrypt_set_bio_crypt_ctx
```
**Symbols:**

```
ffffffff81807680-ffffffff818076ed: bio_crypt_set_ctx (STB_GLOBAL)
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
