# Function: <code>blk_crypto_start_using_key</code>

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
int blk_crypto_start_using_key(const struct blk_crypto_key *key, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff81581d40)
Location: block/blk-crypto.c:371
Inline: False
```
**Symbols:**

```
ffffffff81581d40-ffffffff81581d73: blk_crypto_start_using_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int blk_crypto_start_using_key(const struct blk_crypto_key *key, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff8159ed30)
Location: block/blk-crypto.c:378
Inline: False
Direct callers:
  - fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key
```
**Symbols:**

```
ffffffff8159ed30-ffffffff8159ed63: blk_crypto_start_using_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int blk_crypto_start_using_key(const struct blk_crypto_key *key, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff815a5b90)
Location: block/blk-crypto.c:378
Inline: False
Direct callers:
  - fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key
```
**Symbols:**

```
ffffffff815a5b90-ffffffff815a5bc3: blk_crypto_start_using_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int blk_crypto_start_using_key(const struct blk_crypto_key *key, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff8160e6a0)
Location: block/blk-crypto.c:378
Inline: False
Direct callers:
  - fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key
```
**Symbols:**

```
ffffffff8160e6a0-ffffffff8160e6d3: blk_crypto_start_using_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int blk_crypto_start_using_key(const struct blk_crypto_key *key, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff816c1d90)
Location: block/blk-crypto.c:382
Inline: False
Direct callers:
  - fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key
```
**Symbols:**

```
ffffffff816c1d90-ffffffff816c1dcb: blk_crypto_start_using_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int blk_crypto_start_using_key(struct block_device *bdev, const struct blk_crypto_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff81783000)
Location: block/blk-crypto.c:393
Inline: False
Direct callers:
  - fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key
```
**Symbols:**

```
ffffffff81783000-ffffffff8178303f: blk_crypto_start_using_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int blk_crypto_start_using_key(struct block_device *bdev, const struct blk_crypto_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff817c32c0)
Location: block/blk-crypto.c:394
Inline: False
Direct callers:
  - fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key
```
**Symbols:**

```
ffffffff817c32c0-ffffffff817c32fc: blk_crypto_start_using_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int blk_crypto_start_using_key(struct block_device *bdev, const struct blk_crypto_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff81807f50)
Location: block/blk-crypto.c:394
Inline: False
Direct callers:
  - fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key
```
**Symbols:**

```
ffffffff81807f50-ffffffff81807f8c: blk_crypto_start_using_key (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct block_device *bdev</code>
</li>
<li>
<b>Param removed. </b>
<code>struct request_queue *q</code>
</li>
<li>
<b>Param reordered. </b>
<code>key, q</code> ➡️ <code>bdev, key</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
