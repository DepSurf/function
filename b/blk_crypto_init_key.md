# Function: <code>blk_crypto_init_key</code>

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
int blk_crypto_init_key(struct blk_crypto_key *blk_key, const u8 *raw_key, enum blk_crypto_mode_num crypto_mode, unsigned int dun_bytes, unsigned int data_unit_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff81581c80)
Location: block/blk-crypto.c:312
Inline: False
```
**Symbols:**

```
ffffffff81581c80-ffffffff81581d25: blk_crypto_init_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int blk_crypto_init_key(struct blk_crypto_key *blk_key, const u8 *raw_key, enum blk_crypto_mode_num crypto_mode, unsigned int dun_bytes, unsigned int data_unit_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff8159ec70)
Location: block/blk-crypto.c:319
Inline: False
Direct callers:
  - fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key
```
**Symbols:**

```
ffffffff8159ec70-ffffffff8159ed15: blk_crypto_init_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int blk_crypto_init_key(struct blk_crypto_key *blk_key, const u8 *raw_key, enum blk_crypto_mode_num crypto_mode, unsigned int dun_bytes, unsigned int data_unit_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff815a5ad0)
Location: block/blk-crypto.c:319
Inline: False
Direct callers:
  - fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key
```
**Symbols:**

```
ffffffff815a5ad0-ffffffff815a5b74: blk_crypto_init_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int blk_crypto_init_key(struct blk_crypto_key *blk_key, const u8 *raw_key, enum blk_crypto_mode_num crypto_mode, unsigned int dun_bytes, unsigned int data_unit_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff8160e5a0)
Location: block/blk-crypto.c:319
Inline: False
Direct callers:
  - fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key
```
**Symbols:**

```
ffffffff8160e5a0-ffffffff8160e690: blk_crypto_init_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int blk_crypto_init_key(struct blk_crypto_key *blk_key, const u8 *raw_key, enum blk_crypto_mode_num crypto_mode, unsigned int dun_bytes, unsigned int data_unit_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff816c1c50)
Location: block/blk-crypto.c:323
Inline: False
Direct callers:
  - fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key
```
**Symbols:**

```
ffffffff816c1c50-ffffffff816c1d64: blk_crypto_init_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int blk_crypto_init_key(struct blk_crypto_key *blk_key, const u8 *raw_key, enum blk_crypto_mode_num crypto_mode, unsigned int dun_bytes, unsigned int data_unit_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff81782e60)
Location: block/blk-crypto.c:327
Inline: False
Direct callers:
  - fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key
```
**Symbols:**

```
ffffffff81782e60-ffffffff81782f74: blk_crypto_init_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int blk_crypto_init_key(struct blk_crypto_key *blk_key, const u8 *raw_key, enum blk_crypto_mode_num crypto_mode, unsigned int dun_bytes, unsigned int data_unit_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-crypto.c (0)
Location: block/blk-crypto.c:328
Inline: False
Direct callers:
  - fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key
```
**Symbols:**

```
ffffffff820f745a-ffffffff820f746f: blk_crypto_init_key.cold (STB_LOCAL)
ffffffff817c30d0-ffffffff817c3233: blk_crypto_init_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int blk_crypto_init_key(struct blk_crypto_key *blk_key, const u8 *raw_key, enum blk_crypto_mode_num crypto_mode, unsigned int dun_bytes, unsigned int data_unit_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-crypto.c (0)
Location: block/blk-crypto.c:328
Inline: False
Direct callers:
  - fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key
```
**Symbols:**

```
ffffffff821d4e82-ffffffff821d4e97: blk_crypto_init_key.cold (STB_LOCAL)
ffffffff81807d60-ffffffff81807ec3: blk_crypto_init_key (STB_GLOBAL)
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
