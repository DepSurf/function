# Function: <code>blk_ksm_put_slot</code>

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
void blk_ksm_put_slot(struct blk_ksm_keyslot *slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/keyslot-manager.c (ffffffff81581560)
Location: block/keyslot-manager.c:260
Inline: False
Direct callers:
  - block/blk-crypto.c:__blk_crypto_free_request
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
```
**Symbols:**

```
ffffffff81581560-ffffffff8158160c: blk_ksm_put_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_ksm_put_slot(struct blk_ksm_keyslot *slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/keyslot-manager.c (ffffffff8159e590)
Location: block/keyslot-manager.c:267
Inline: False
Direct callers:
  - block/blk-crypto.c:__blk_crypto_free_request
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
```
**Symbols:**

```
ffffffff8159e590-ffffffff8159e63c: blk_ksm_put_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_ksm_put_slot(struct blk_ksm_keyslot *slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/keyslot-manager.c (ffffffff815a5370)
Location: block/keyslot-manager.c:305
Inline: False
Direct callers:
  - block/blk-crypto.c:__blk_crypto_free_request
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
```
**Symbols:**

```
ffffffff815a5370-ffffffff815a541c: blk_ksm_put_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blk_ksm_put_slot(struct blk_ksm_keyslot *slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/keyslot-manager.c (ffffffff8160de20)
Location: block/keyslot-manager.c:305
Inline: False
Direct callers:
  - block/blk-crypto.c:__blk_crypto_free_request
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
```
**Symbols:**

```
ffffffff8160de20-ffffffff8160decc: blk_ksm_put_slot (STB_GLOBAL)
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
