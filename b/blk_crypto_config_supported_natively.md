# Function: <code>blk_crypto_config_supported_natively</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool blk_crypto_config_supported_natively(struct block_device *bdev, const struct blk_crypto_config *cfg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff81782816)
Location: block/blk-crypto.c:359
Inline: True
Inline callers:
  - block/blk-crypto.c:blk_crypto_evict_key
  - block/blk-crypto.c:blk_crypto_start_using_key
  - block/blk-crypto.c:__blk_crypto_bio_prep
Direct callers:
  - fs/crypto/inline_crypt.c:fscrypt_select_encryption_impl
```
**Symbols:**

```
ffffffff81782f90-ffffffff81782fb6: blk_crypto_config_supported_natively (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool blk_crypto_config_supported_natively(struct block_device *bdev, const struct blk_crypto_config *cfg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff817c2958)
Location: block/blk-crypto.c:360
Inline: True
Inline callers:
  - block/blk-crypto.c:blk_crypto_evict_key
  - block/blk-crypto.c:blk_crypto_start_using_key
  - block/blk-crypto.c:__blk_crypto_bio_prep
Direct callers:
  - fs/crypto/inline_crypt.c:fscrypt_select_encryption_impl
```
**Symbols:**

```
ffffffff817c3250-ffffffff817c3273: blk_crypto_config_supported_natively (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool blk_crypto_config_supported_natively(struct block_device *bdev, const struct blk_crypto_config *cfg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff818075e8)
Location: block/blk-crypto.c:360
Inline: True
Inline callers:
  - block/blk-crypto.c:blk_crypto_evict_key
  - block/blk-crypto.c:blk_crypto_start_using_key
  - block/blk-crypto.c:__blk_crypto_bio_prep
Direct callers:
  - fs/crypto/inline_crypt.c:fscrypt_select_encryption_impl
```
**Symbols:**

```
ffffffff81807ee0-ffffffff81807f03: blk_crypto_config_supported_natively (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
