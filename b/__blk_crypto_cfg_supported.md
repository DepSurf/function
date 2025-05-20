# Function: <code>__blk_crypto_cfg_supported</code>

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
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool __blk_crypto_cfg_supported(struct blk_crypto_profile *profile, const struct blk_crypto_config *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto-profile.c (ffffffff816c29d0)
Location: block/blk-crypto-profile.c:344
Inline: False
Direct callers:
  - fs/crypto/inline_crypt.c:fscrypt_select_encryption_impl
  - block/blk-crypto.c:blk_crypto_start_using_key
  - block/blk-crypto.c:__blk_crypto_bio_prep
  - block/blk-crypto-fallback.c:blk_crypto_fallback_bio_prep
```
**Symbols:**

```
ffffffff816c29d0-ffffffff816c2a45: __blk_crypto_cfg_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool __blk_crypto_cfg_supported(struct blk_crypto_profile *profile, const struct blk_crypto_config *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto-profile.c (ffffffff81783d50)
Location: block/blk-crypto-profile.c:345
Inline: False
Direct callers:
  - block/blk-crypto.c:blk_crypto_evict_key
  - block/blk-crypto.c:blk_crypto_start_using_key
  - block/blk-crypto.c:__blk_crypto_bio_prep
  - block/blk-crypto-fallback.c:blk_crypto_fallback_bio_prep
```
**Symbols:**

```
ffffffff81783d50-ffffffff81783dc5: __blk_crypto_cfg_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool __blk_crypto_cfg_supported(struct blk_crypto_profile *profile, const struct blk_crypto_config *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto-profile.c (ffffffff817c4030)
Location: block/blk-crypto-profile.c:346
Inline: False
Direct callers:
  - block/blk-crypto.c:blk_crypto_evict_key
  - block/blk-crypto.c:blk_crypto_start_using_key
  - block/blk-crypto.c:__blk_crypto_bio_prep
  - block/blk-crypto-fallback.c:blk_crypto_fallback_bio_prep
```
**Symbols:**

```
ffffffff817c4030-ffffffff817c40a5: __blk_crypto_cfg_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool __blk_crypto_cfg_supported(struct blk_crypto_profile *profile, const struct blk_crypto_config *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto-profile.c (ffffffff81808cc0)
Location: block/blk-crypto-profile.c:346
Inline: False
Direct callers:
  - block/blk-crypto.c:blk_crypto_evict_key
  - block/blk-crypto.c:blk_crypto_start_using_key
  - block/blk-crypto.c:__blk_crypto_bio_prep
  - block/blk-crypto-fallback.c:blk_crypto_fallback_bio_prep
```
**Symbols:**

```
ffffffff81808cc0-ffffffff81808d35: __blk_crypto_cfg_supported (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
