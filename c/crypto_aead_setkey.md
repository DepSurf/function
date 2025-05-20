# Function: <code>crypto_aead_setkey</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int crypto_aead_setkey(struct crypto_aead *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff8139efb0)
Location: crypto/aead.c:52
Inline: False
Direct callers:
  - crypto/aead.c:aead_geniv_setkey
```
**Symbols:**

```
ffffffff8139efb0-ffffffff8139f06b: crypto_aead_setkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int crypto_aead_setkey(struct crypto_aead *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff813dbd60)
Location: crypto/aead.c:52
Inline: False
Direct callers:
  - crypto/aead.c:aead_geniv_setkey
```
**Symbols:**

```
ffffffff813dbd60-ffffffff813dbe0f: crypto_aead_setkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int crypto_aead_setkey(struct crypto_aead *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff813f3640)
Location: crypto/aead.c:52
Inline: False
Direct callers:
  - crypto/aead.c:aead_geniv_setkey
```
**Symbols:**

```
ffffffff813f3640-ffffffff813f36ef: crypto_aead_setkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int crypto_aead_setkey(struct crypto_aead *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff813ff960)
Location: crypto/aead.c:53
Inline: False
Direct callers:
  - crypto/aead.c:aead_geniv_setkey
```
**Symbols:**

```
ffffffff813ff960-ffffffff813ffa0c: crypto_aead_setkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int crypto_aead_setkey(struct crypto_aead *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff81427f40)
Location: crypto/aead.c:53
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_crypt
  - crypto/aead.c:aead_geniv_setkey
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
```
**Symbols:**

```
ffffffff81427f40-ffffffff81427ffb: crypto_aead_setkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int crypto_aead_setkey(struct crypto_aead *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff8145ad70)
Location: crypto/aead.c:53
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_crypt
  - crypto/aead.c:aead_geniv_setkey
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
```
**Symbols:**

```
ffffffff8145ad70-ffffffff8145ae3a: crypto_aead_setkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int crypto_aead_setkey(struct crypto_aead *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff814788e0)
Location: crypto/aead.c:53
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_crypt
  - crypto/aead.c:aead_geniv_setkey
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
```
**Symbols:**

```
ffffffff814788e0-ffffffff814789bd: crypto_aead_setkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int crypto_aead_setkey(struct crypto_aead *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff814a6c00)
Location: crypto/aead.c:48
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_crypt
  - crypto/aead.c:aead_geniv_setkey
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
```
**Symbols:**

```
ffffffff814a6c00-ffffffff814a6ce5: crypto_aead_setkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int crypto_aead_setkey(struct crypto_aead *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff814c1870)
Location: crypto/aead.c:48
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_crypt
  - crypto/aead.c:aead_geniv_setkey
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
```
**Symbols:**

```
ffffffff814c1870-ffffffff814c1955: crypto_aead_setkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int crypto_aead_setkey(struct crypto_aead *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff81521d00)
Location: crypto/aead.c:43
Inline: False
Direct callers:
  - crypto/geniv.c:aead_geniv_setkey
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
```
**Symbols:**

```
ffffffff81521d00-ffffffff81521d49: crypto_aead_setkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int crypto_aead_setkey(struct crypto_aead *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff8153eb50)
Location: crypto/aead.c:43
Inline: False
Direct callers:
  - crypto/geniv.c:aead_geniv_setkey
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
```
**Symbols:**

```
ffffffff8153eb50-ffffffff8153eb99: crypto_aead_setkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int crypto_aead_setkey(struct crypto_aead *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff81547200)
Location: crypto/aead.c:43
Inline: False
Direct callers:
  - crypto/geniv.c:aead_geniv_setkey
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
```
**Symbols:**

```
ffffffff81547200-ffffffff8154723f: crypto_aead_setkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int crypto_aead_setkey(struct crypto_aead *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff815a79e0)
Location: crypto/aead.c:43
Inline: False
Direct callers:
  - crypto/geniv.c:aead_geniv_setkey
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
```
**Symbols:**

```
ffffffff815a79e0-ffffffff815a7a1f: crypto_aead_setkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int crypto_aead_setkey(struct crypto_aead *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff8164ed30)
Location: crypto/aead.c:43
Inline: False
Direct callers:
  - crypto/geniv.c:aead_geniv_setkey
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
```
**Symbols:**

```
ffffffff8164ed30-ffffffff8164ed7b: crypto_aead_setkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int crypto_aead_setkey(struct crypto_aead *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff817086c0)
Location: crypto/aead.c:43
Inline: False
Direct callers:
  - crypto/geniv.c:aead_geniv_setkey
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
```
**Symbols:**

```
ffffffff817086c0-ffffffff8170870b: crypto_aead_setkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int crypto_aead_setkey(struct crypto_aead *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff81741e30)
Location: crypto/aead.c:53
Inline: False
Direct callers:
  - crypto/geniv.c:aead_geniv_setkey
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
```
**Symbols:**

```
ffffffff81741e30-ffffffff81741e7b: crypto_aead_setkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int crypto_aead_setkey(struct crypto_aead *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff81782d10)
Location: crypto/aead.c:53
Inline: False
Direct callers:
  - crypto/geniv.c:aead_geniv_setkey
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
```
**Symbols:**

```
ffffffff81782d10-ffffffff81782d5b: crypto_aead_setkey (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int crypto_aead_setkey(struct crypto_aead *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffff8000105bbf10)
Location: crypto/aead.c:48
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_crypt
  - crypto/aead.c:aead_geniv_setkey
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
```
**Symbols:**

```
ffff8000105bbf10-ffff8000105bc028: crypto_aead_setkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int crypto_aead_setkey(struct crypto_aead *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (c0769fec)
Location: crypto/aead.c:48
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_crypt
  - crypto/aead.c:aead_geniv_setkey
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
```
**Symbols:**

```
c0769fec-c076a0b8: crypto_aead_setkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int crypto_aead_setkey(struct crypto_aead *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (c000000000742810)
Location: crypto/aead.c:48
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_crypt
  - crypto/aead.c:aead_geniv_setkey
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
```
**Symbols:**

```
c000000000742810-c000000000742974: crypto_aead_setkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int crypto_aead_setkey(struct crypto_aead *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffe0004016f8)
Location: crypto/aead.c:48
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_crypt
  - crypto/aead.c:aead_geniv_setkey
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
```
**Symbols:**

```
ffffffe0004016f8-ffffffe0004017c4: crypto_aead_setkey (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int crypto_aead_setkey(struct crypto_aead *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff814b9e50)
Location: crypto/aead.c:48
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_crypt
  - crypto/aead.c:aead_geniv_setkey
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
```
**Symbols:**

```
ffffffff814b9e50-ffffffff814b9f35: crypto_aead_setkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int crypto_aead_setkey(struct crypto_aead *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff814aa870)
Location: crypto/aead.c:48
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_crypt
  - crypto/aead.c:aead_geniv_setkey
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
```
**Symbols:**

```
ffffffff814aa870-ffffffff814aa955: crypto_aead_setkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int crypto_aead_setkey(struct crypto_aead *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff814b5ee0)
Location: crypto/aead.c:48
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_crypt
  - crypto/aead.c:aead_geniv_setkey
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
```
**Symbols:**

```
ffffffff814b5ee0-ffffffff814b5fc5: crypto_aead_setkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int crypto_aead_setkey(struct crypto_aead *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff814ce980)
Location: crypto/aead.c:48
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_crypt
  - crypto/aead.c:aead_geniv_setkey
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
```
**Symbols:**

```
ffffffff814ce980-ffffffff814cea65: crypto_aead_setkey (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
