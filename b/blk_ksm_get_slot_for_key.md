# Function: <code>blk_ksm_get_slot_for_key</code>

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
blk_status_t blk_ksm_get_slot_for_key(struct blk_keyslot_manager *ksm, const struct blk_crypto_key *key, struct blk_ksm_keyslot **slot_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/keyslot-manager.c (ffffffff81581290)
Location: block/keyslot-manager.c:192
Inline: False
Direct callers:
  - block/blk-crypto.c:__blk_crypto_init_request
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
```
**Symbols:**

```
ffffffff81581290-ffffffff81581554: blk_ksm_get_slot_for_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
blk_status_t blk_ksm_get_slot_for_key(struct blk_keyslot_manager *ksm, const struct blk_crypto_key *key, struct blk_ksm_keyslot **slot_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/keyslot-manager.c (ffffffff8159e2c0)
Location: block/keyslot-manager.c:199
Inline: False
Direct callers:
  - block/blk-crypto.c:__blk_crypto_init_request
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
```
**Symbols:**

```
ffffffff8159e2c0-ffffffff8159e584: blk_ksm_get_slot_for_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
blk_status_t blk_ksm_get_slot_for_key(struct blk_keyslot_manager *ksm, const struct blk_crypto_key *key, struct blk_ksm_keyslot **slot_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/keyslot-manager.c (ffffffff815a5090)
Location: block/keyslot-manager.c:233
Inline: False
Direct callers:
  - block/blk-crypto.c:__blk_crypto_init_request
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
```
**Symbols:**

```
ffffffff815a5090-ffffffff815a536e: blk_ksm_get_slot_for_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
blk_status_t blk_ksm_get_slot_for_key(struct blk_keyslot_manager *ksm, const struct blk_crypto_key *key, struct blk_ksm_keyslot **slot_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/keyslot-manager.c (0)
Location: block/keyslot-manager.c:233
Inline: False
Direct callers:
  - block/blk-crypto.c:__blk_crypto_init_request
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
```
**Symbols:**

```
ffffffff81cda636-ffffffff81cda662: blk_ksm_get_slot_for_key.cold (STB_LOCAL)
ffffffff8160db30-ffffffff8160de17: blk_ksm_get_slot_for_key (STB_GLOBAL)
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
