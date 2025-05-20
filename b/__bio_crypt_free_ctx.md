# Function: <code>__bio_crypt_free_ctx</code>

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
void __bio_crypt_free_ctx(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff81581950)
Location: block/blk-crypto.c:92
Inline: False
Direct callers:
  - block/bio.c:bio_uninit
  - block/blk-core.c:bio_attempt_back_merge
  - block/blk-map.c:blk_rq_append_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_bio_prep
```
**Symbols:**

```
ffffffff81581950-ffffffff8158197b: __bio_crypt_free_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __bio_crypt_free_ctx(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff8159e940)
Location: block/blk-crypto.c:100
Inline: False
Direct callers:
  - block/bio.c:bio_uninit
  - block/blk-map.c:blk_rq_append_bio
  - block/blk-merge.c:bio_attempt_back_merge
  - block/blk-crypto-fallback.c:blk_crypto_fallback_bio_prep
```
**Symbols:**

```
ffffffff8159e940-ffffffff8159e96b: __bio_crypt_free_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __bio_crypt_free_ctx(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff815a5710)
Location: block/blk-crypto.c:100
Inline: False
Direct callers:
  - block/bio.c:bio_uninit
  - block/blk-map.c:blk_rq_append_bio
  - block/blk-merge.c:bio_attempt_back_merge
  - block/blk-crypto-fallback.c:blk_crypto_fallback_bio_prep
```
**Symbols:**

```
ffffffff815a5710-ffffffff815a573b: __bio_crypt_free_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __bio_crypt_free_ctx(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff8160e1e0)
Location: block/blk-crypto.c:100
Inline: False
Direct callers:
  - block/bio.c:bio_uninit
  - block/blk-map.c:blk_rq_append_bio
  - block/blk-merge.c:bio_attempt_back_merge
  - block/blk-crypto-fallback.c:blk_crypto_fallback_bio_prep
```
**Symbols:**

```
ffffffff8160e1e0-ffffffff8160e20b: __bio_crypt_free_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __bio_crypt_free_ctx(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff816c1790)
Location: block/blk-crypto.c:103
Inline: False
Direct callers:
  - block/bio.c:bio_uninit
  - block/blk-map.c:blk_rq_append_bio
  - block/blk-merge.c:bio_attempt_back_merge
  - block/blk-crypto-fallback.c:blk_crypto_fallback_bio_prep
```
**Symbols:**

```
ffffffff816c1790-ffffffff816c17c3: __bio_crypt_free_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __bio_crypt_free_ctx(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff817828f0)
Location: block/blk-crypto.c:109
Inline: False
Direct callers:
  - block/bio.c:bio_uninit
  - block/blk-map.c:blk_rq_append_bio
  - block/blk-merge.c:bio_attempt_back_merge
  - block/blk-crypto-fallback.c:blk_crypto_fallback_bio_prep
```
**Symbols:**

```
ffffffff817828f0-ffffffff81782923: __bio_crypt_free_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __bio_crypt_free_ctx(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff817c2a70)
Location: block/blk-crypto.c:110
Inline: False
Direct callers:
  - block/bio.c:bio_uninit
  - block/blk-map.c:blk_rq_append_bio
  - block/blk-merge.c:bio_attempt_back_merge
  - block/blk-crypto-fallback.c:blk_crypto_fallback_bio_prep
```
**Symbols:**

```
ffffffff817c2a70-ffffffff817c2aa3: __bio_crypt_free_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __bio_crypt_free_ctx(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff81807700)
Location: block/blk-crypto.c:110
Inline: False
Direct callers:
  - block/bio.c:bio_uninit
  - block/blk-map.c:blk_rq_append_bio
  - block/blk-merge.c:bio_attempt_back_merge
  - block/blk-crypto-fallback.c:blk_crypto_fallback_bio_prep
```
**Symbols:**

```
ffffffff81807700-ffffffff81807733: __bio_crypt_free_ctx (STB_GLOBAL)
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
