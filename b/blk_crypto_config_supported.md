# Function: <code>blk_crypto_config_supported</code>

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
bool blk_crypto_config_supported(struct request_queue *q, const struct blk_crypto_config *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff81581d30)
Location: block/blk-crypto.c:349
Inline: False
```
**Symbols:**

```
ffffffff81581d30-ffffffff81581d40: blk_crypto_config_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool blk_crypto_config_supported(struct request_queue *q, const struct blk_crypto_config *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff8159ed20)
Location: block/blk-crypto.c:356
Inline: False
Direct callers:
  - fs/crypto/inline_crypt.c:fscrypt_select_encryption_impl
```
**Symbols:**

```
ffffffff8159ed20-ffffffff8159ed30: blk_crypto_config_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool blk_crypto_config_supported(struct request_queue *q, const struct blk_crypto_config *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff815a5b80)
Location: block/blk-crypto.c:356
Inline: False
Direct callers:
  - fs/crypto/inline_crypt.c:fscrypt_select_encryption_impl
```
**Symbols:**

```
ffffffff815a5b80-ffffffff815a5b90: blk_crypto_config_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool blk_crypto_config_supported(struct request_queue *q, const struct blk_crypto_config *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff8160e690)
Location: block/blk-crypto.c:356
Inline: False
Direct callers:
  - fs/crypto/inline_crypt.c:fscrypt_select_encryption_impl
```
**Symbols:**

```
ffffffff8160e690-ffffffff8160e6a0: blk_crypto_config_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool blk_crypto_config_supported(struct request_queue *q, const struct blk_crypto_config *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff816c1d70)
Location: block/blk-crypto.c:360
Inline: False
Direct callers:
  - fs/crypto/inline_crypt.c:fscrypt_select_encryption_impl
```
**Symbols:**

```
ffffffff816c1d70-ffffffff816c1d84: blk_crypto_config_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool blk_crypto_config_supported(struct block_device *bdev, const struct blk_crypto_config *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff81782fd0)
Location: block/blk-crypto.c:371
Inline: False
Direct callers:
  - fs/crypto/inline_crypt.c:fscrypt_select_encryption_impl
```
**Symbols:**

```
ffffffff81782fd0-ffffffff81782fe4: blk_crypto_config_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool blk_crypto_config_supported(struct block_device *bdev, const struct blk_crypto_config *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff817c3290)
Location: block/blk-crypto.c:372
Inline: False
Direct callers:
  - fs/crypto/inline_crypt.c:fscrypt_select_encryption_impl
```
**Symbols:**

```
ffffffff817c3290-ffffffff817c32a4: blk_crypto_config_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool blk_crypto_config_supported(struct block_device *bdev, const struct blk_crypto_config *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff81807f20)
Location: block/blk-crypto.c:372
Inline: False
Direct callers:
  - fs/crypto/inline_crypt.c:fscrypt_select_encryption_impl
```
**Symbols:**

```
ffffffff81807f20-ffffffff81807f34: blk_crypto_config_supported (STB_GLOBAL)
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
