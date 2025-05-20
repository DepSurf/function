# Function: <code>blk_crypto_alloc_cipher_req</code>

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
bool blk_crypto_alloc_cipher_req(struct blk_ksm_keyslot *slot, struct skcipher_request **ciph_req_ret, struct crypto_wait *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto-fallback.c (ffffffff81581ff0)
Location: block/blk-crypto-fallback.c:186
Inline: False
Direct callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
```
**Symbols:**

```
ffffffff81581ff0-ffffffff8158206b: blk_crypto_alloc_cipher_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool blk_crypto_alloc_cipher_req(struct blk_ksm_keyslot *slot, struct skcipher_request **ciph_req_ret, struct crypto_wait *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto-fallback.c (ffffffff8159efc0)
Location: block/blk-crypto-fallback.c:186
Inline: False
Direct callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
```
**Symbols:**

```
ffffffff8159efc0-ffffffff8159f03b: blk_crypto_alloc_cipher_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-crypto-fallback.c (ffffffff815a5dd0)
Location: block/blk-crypto-fallback.c:189
Inline: True
Direct callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
```
**Symbols:**

```
ffffffff815a5dd0-ffffffff815a5e4b: blk_crypto_alloc_cipher_req.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-crypto-fallback.c (ffffffff8160e8e0)
Location: block/blk-crypto-fallback.c:189
Inline: True
Direct callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
```
**Symbols:**

```
ffffffff8160e8e0-ffffffff8160e95b: blk_crypto_alloc_cipher_req.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
</ul>
