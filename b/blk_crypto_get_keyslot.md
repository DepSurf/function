# Function: <code>blk_crypto_get_keyslot</code>

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
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
blk_status_t blk_crypto_get_keyslot(struct blk_crypto_profile *profile, const struct blk_crypto_key *key, struct blk_crypto_keyslot **slot_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-crypto-profile.c (0)
Location: block/blk-crypto-profile.c:241
Inline: False
Direct callers:
  - block/blk-crypto.c:__blk_crypto_init_request
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
```
**Symbols:**

```
ffffffff81e8e231-ffffffff81e8e25d: blk_crypto_get_keyslot.cold (STB_LOCAL)
ffffffff816c25d0-ffffffff816c28f1: blk_crypto_get_keyslot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
blk_status_t blk_crypto_get_keyslot(struct blk_crypto_profile *profile, const struct blk_crypto_key *key, struct blk_crypto_keyslot **slot_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-crypto-profile.c (0)
Location: block/blk-crypto-profile.c:242
Inline: False
Direct callers:
  - block/blk-crypto.c:__blk_crypto_init_request
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
```
**Symbols:**

```
ffffffff82077448-ffffffff82077474: blk_crypto_get_keyslot.cold (STB_LOCAL)
ffffffff81783930-ffffffff81783c51: blk_crypto_get_keyslot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
blk_status_t blk_crypto_get_keyslot(struct blk_crypto_profile *profile, const struct blk_crypto_key *key, struct blk_crypto_keyslot **slot_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-crypto-profile.c (0)
Location: block/blk-crypto-profile.c:248
Inline: False
Direct callers:
  - block/blk-crypto.c:__blk_crypto_rq_get_keyslot
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
```
**Symbols:**

```
ffffffff820f74a9-ffffffff820f74d5: blk_crypto_get_keyslot.cold (STB_LOCAL)
ffffffff817c3c20-ffffffff817c3f41: blk_crypto_get_keyslot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
blk_status_t blk_crypto_get_keyslot(struct blk_crypto_profile *profile, const struct blk_crypto_key *key, struct blk_crypto_keyslot **slot_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-crypto-profile.c (0)
Location: block/blk-crypto-profile.c:248
Inline: False
Direct callers:
  - block/blk-crypto.c:__blk_crypto_rq_get_keyslot
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
```
**Symbols:**

```
ffffffff821d4ed1-ffffffff821d4efd: blk_crypto_get_keyslot.cold (STB_LOCAL)
ffffffff818088b0-ffffffff81808bd1: blk_crypto_get_keyslot (STB_GLOBAL)
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
