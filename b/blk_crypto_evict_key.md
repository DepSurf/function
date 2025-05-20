# Function: <code>blk_crypto_evict_key</code>

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
int blk_crypto_evict_key(struct request_queue *q, const struct blk_crypto_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff81581d80)
Location: block/blk-crypto.c:392
Inline: False
```
**Symbols:**

```
ffffffff81581d80-ffffffff81581dc3: blk_crypto_evict_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int blk_crypto_evict_key(struct request_queue *q, const struct blk_crypto_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff8159ed70)
Location: block/blk-crypto.c:399
Inline: False
Direct callers:
  - fs/crypto/inline_crypt.c:fscrypt_destroy_inline_crypt_key
```
**Symbols:**

```
ffffffff8159ed70-ffffffff8159edb3: blk_crypto_evict_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int blk_crypto_evict_key(struct request_queue *q, const struct blk_crypto_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff815a5660)
Location: block/blk-crypto.c:399
Inline: True
Direct callers:
  - fs/crypto/inline_crypt.c:fscrypt_destroy_inline_crypt_key
  - drivers/md/dm-table.c:dm_keyslot_evict_callback
```
**Symbols:**

```
ffffffff815a5660-ffffffff815a56a3: blk_crypto_evict_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int blk_crypto_evict_key(struct request_queue *q, const struct blk_crypto_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff8160e130)
Location: block/blk-crypto.c:399
Inline: True
Direct callers:
  - fs/crypto/inline_crypt.c:fscrypt_destroy_inline_crypt_key
  - drivers/md/dm-table.c:dm_keyslot_evict_callback
```
**Symbols:**

```
ffffffff8160e130-ffffffff8160e173: blk_crypto_evict_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int blk_crypto_evict_key(struct request_queue *q, const struct blk_crypto_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff816c16c0)
Location: block/blk-crypto.c:403
Inline: True
Direct callers:
  - fs/crypto/inline_crypt.c:fscrypt_destroy_inline_crypt_key
  - drivers/md/dm-table.c:dm_keyslot_evict_callback
```
**Symbols:**

```
ffffffff816c16c0-ffffffff816c1714: blk_crypto_evict_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int blk_crypto_evict_key(struct block_device *bdev, const struct blk_crypto_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff81782800)
Location: block/blk-crypto.c:414
Inline: False
Direct callers:
  - fs/crypto/inline_crypt.c:fscrypt_destroy_inline_crypt_key
  - drivers/md/dm-table.c:dm_keyslot_evict_callback
```
**Symbols:**

```
ffffffff81782800-ffffffff81782859: blk_crypto_evict_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_crypto_evict_key(struct block_device *bdev, const struct blk_crypto_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff817c2940)
Location: block/blk-crypto.c:417
Inline: False
Direct callers:
  - fs/crypto/inline_crypt.c:fscrypt_destroy_inline_crypt_key
  - drivers/md/dm-table.c:dm_keyslot_evict_callback
```
**Symbols:**

```
ffffffff817c2940-ffffffff817c29d9: blk_crypto_evict_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blk_crypto_evict_key(struct block_device *bdev, const struct blk_crypto_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff818075d0)
Location: block/blk-crypto.c:417
Inline: False
Direct callers:
  - fs/crypto/inline_crypt.c:fscrypt_destroy_inline_crypt_key
  - drivers/md/dm-table.c:dm_keyslot_evict_callback
```
**Symbols:**

```
ffffffff818075d0-ffffffff81807669: blk_crypto_evict_key (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
