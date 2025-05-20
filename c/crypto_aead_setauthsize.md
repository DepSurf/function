# Function: <code>crypto_aead_setauthsize</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int crypto_aead_setauthsize(struct crypto_aead *tfm, unsigned int authsize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff8139eed0)
Location: crypto/aead.c:64
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_setauthsize
```
**Symbols:**

```
ffffffff8139eed0-ffffffff8139ef0a: crypto_aead_setauthsize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int crypto_aead_setauthsize(struct crypto_aead *tfm, unsigned int authsize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff813dbd30)
Location: crypto/aead.c:64
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_setauthsize
```
**Symbols:**

```
ffffffff813dbc80-ffffffff813dbcba: crypto_aead_setauthsize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int crypto_aead_setauthsize(struct crypto_aead *tfm, unsigned int authsize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff813f3610)
Location: crypto/aead.c:64
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_setauthsize
```
**Symbols:**

```
ffffffff813f3560-ffffffff813f359a: crypto_aead_setauthsize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int crypto_aead_setauthsize(struct crypto_aead *tfm, unsigned int authsize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff813ff930)
Location: crypto/aead.c:65
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_setauthsize
```
**Symbols:**

```
ffffffff813ff880-ffffffff813ff8ba: crypto_aead_setauthsize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int crypto_aead_setauthsize(struct crypto_aead *tfm, unsigned int authsize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff81427f00)
Location: crypto/aead.c:65
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_setauthsize
Direct callers:
  - security/keys/big_key.c:big_key_init
  - crypto/gcm.c:crypto_rfc4543_setauthsize
  - crypto/gcm.c:crypto_rfc4106_setauthsize
```
**Symbols:**

```
ffffffff81427e50-ffffffff81427e8d: crypto_aead_setauthsize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int crypto_aead_setauthsize(struct crypto_aead *tfm, unsigned int authsize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff8145ad30)
Location: crypto/aead.c:72
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_setauthsize
Direct callers:
  - security/keys/big_key.c:big_key_init
  - crypto/gcm.c:crypto_rfc4543_setauthsize
  - crypto/gcm.c:crypto_rfc4106_setauthsize
```
**Symbols:**

```
ffffffff8145ac80-ffffffff8145acbd: crypto_aead_setauthsize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int crypto_aead_setauthsize(struct crypto_aead *tfm, unsigned int authsize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff814788a0)
Location: crypto/aead.c:74
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_setauthsize
Direct callers:
  - security/keys/big_key.c:big_key_init
  - crypto/gcm.c:crypto_rfc4543_setauthsize
  - crypto/gcm.c:crypto_rfc4106_setauthsize
```
**Symbols:**

```
ffffffff814787f0-ffffffff8147882d: crypto_aead_setauthsize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int crypto_aead_setauthsize(struct crypto_aead *tfm, unsigned int authsize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff814a66d0)
Location: crypto/aead.c:69
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_setauthsize
Direct callers:
  - security/keys/big_key.c:big_key_init
  - crypto/gcm.c:crypto_rfc4543_setauthsize
  - crypto/gcm.c:crypto_rfc4106_setauthsize
```
**Symbols:**

```
ffffffff814a6620-ffffffff814a665d: crypto_aead_setauthsize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int crypto_aead_setauthsize(struct crypto_aead *tfm, unsigned int authsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff814c12b0)
Location: crypto/aead.c:69
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_init
  - crypto/aead.c:aead_geniv_setauthsize
  - crypto/gcm.c:crypto_rfc4543_setauthsize
  - crypto/gcm.c:crypto_rfc4106_setauthsize
```
**Symbols:**

```
ffffffff814c12b0-ffffffff814c12fd: crypto_aead_setauthsize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int crypto_aead_setauthsize(struct crypto_aead *tfm, unsigned int authsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff81521b60)
Location: crypto/aead.c:64
Inline: False
Direct callers:
  - crypto/geniv.c:aead_geniv_setauthsize
  - crypto/gcm.c:crypto_rfc4543_setauthsize
  - crypto/gcm.c:crypto_rfc4106_setauthsize
```
**Symbols:**

```
ffffffff81521b60-ffffffff81521bad: crypto_aead_setauthsize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int crypto_aead_setauthsize(struct crypto_aead *tfm, unsigned int authsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff8153e9d0)
Location: crypto/aead.c:64
Inline: False
Direct callers:
  - crypto/geniv.c:aead_geniv_setauthsize
  - crypto/gcm.c:crypto_rfc4543_setauthsize
  - crypto/gcm.c:crypto_rfc4106_setauthsize
```
**Symbols:**

```
ffffffff8153e9d0-ffffffff8153ea1e: crypto_aead_setauthsize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int crypto_aead_setauthsize(struct crypto_aead *tfm, unsigned int authsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff81547080)
Location: crypto/aead.c:64
Inline: False
Direct callers:
  - crypto/geniv.c:aead_geniv_setauthsize
  - crypto/gcm.c:crypto_rfc4543_setauthsize
  - crypto/gcm.c:crypto_rfc4106_setauthsize
```
**Symbols:**

```
ffffffff81547080-ffffffff815470cd: crypto_aead_setauthsize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int crypto_aead_setauthsize(struct crypto_aead *tfm, unsigned int authsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff815a7860)
Location: crypto/aead.c:64
Inline: False
Direct callers:
  - crypto/geniv.c:aead_geniv_setauthsize
  - crypto/gcm.c:crypto_rfc4543_setauthsize
  - crypto/gcm.c:crypto_rfc4106_setauthsize
```
**Symbols:**

```
ffffffff815a7860-ffffffff815a78ad: crypto_aead_setauthsize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int crypto_aead_setauthsize(struct crypto_aead *tfm, unsigned int authsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff8164eb60)
Location: crypto/aead.c:64
Inline: False
Direct callers:
  - crypto/geniv.c:aead_geniv_setauthsize
  - crypto/gcm.c:crypto_rfc4543_setauthsize
  - crypto/gcm.c:crypto_rfc4106_setauthsize
```
**Symbols:**

```
ffffffff8164eb60-ffffffff8164ebc4: crypto_aead_setauthsize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int crypto_aead_setauthsize(struct crypto_aead *tfm, unsigned int authsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff81708020)
Location: crypto/aead.c:64
Inline: False
Direct callers:
  - crypto/geniv.c:aead_geniv_setauthsize
  - crypto/gcm.c:crypto_rfc4543_setauthsize
  - crypto/gcm.c:crypto_rfc4106_setauthsize
```
**Symbols:**

```
ffffffff81708020-ffffffff81708084: crypto_aead_setauthsize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int crypto_aead_setauthsize(struct crypto_aead *tfm, unsigned int authsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff81741740)
Location: crypto/aead.c:74
Inline: False
Direct callers:
  - crypto/geniv.c:aead_geniv_setauthsize
  - crypto/gcm.c:crypto_rfc4543_setauthsize
  - crypto/gcm.c:crypto_rfc4106_setauthsize
```
**Symbols:**

```
ffffffff81741740-ffffffff817417a4: crypto_aead_setauthsize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int crypto_aead_setauthsize(struct crypto_aead *tfm, unsigned int authsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff817825e0)
Location: crypto/aead.c:74
Inline: False
Direct callers:
  - crypto/geniv.c:aead_geniv_setauthsize
  - crypto/gcm.c:crypto_rfc4543_setauthsize
  - crypto/gcm.c:crypto_rfc4106_setauthsize
```
**Symbols:**

```
ffffffff817825e0-ffffffff81782644: crypto_aead_setauthsize (STB_GLOBAL)
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
int crypto_aead_setauthsize(struct crypto_aead *tfm, unsigned int authsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffff8000105bb580)
Location: crypto/aead.c:69
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_init
  - crypto/aead.c:aead_geniv_setauthsize
  - crypto/gcm.c:crypto_rfc4543_setauthsize
  - crypto/gcm.c:crypto_rfc4106_setauthsize
```
**Symbols:**

```
ffff8000105bb580-ffff8000105bb5e8: crypto_aead_setauthsize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int crypto_aead_setauthsize(struct crypto_aead *tfm, unsigned int authsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (c07697ec)
Location: crypto/aead.c:69
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_init
  - crypto/aead.c:aead_geniv_setauthsize
  - crypto/gcm.c:crypto_rfc4543_setauthsize
  - crypto/gcm.c:crypto_rfc4106_setauthsize
```
**Symbols:**

```
c07697ec-c0769858: crypto_aead_setauthsize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int crypto_aead_setauthsize(struct crypto_aead *tfm, unsigned int authsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (c000000000741e30)
Location: crypto/aead.c:69
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_init
  - crypto/aead.c:aead_geniv_setauthsize
  - crypto/gcm.c:crypto_rfc4543_setauthsize
  - crypto/gcm.c:crypto_rfc4106_setauthsize
```
**Symbols:**

```
c000000000741e30-c000000000741ed0: crypto_aead_setauthsize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int crypto_aead_setauthsize(struct crypto_aead *tfm, unsigned int authsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffe000401014)
Location: crypto/aead.c:69
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_init
  - crypto/aead.c:aead_geniv_setauthsize
  - crypto/gcm.c:crypto_rfc4543_setauthsize
  - crypto/gcm.c:crypto_rfc4106_setauthsize
```
**Symbols:**

```
ffffffe000401014-ffffffe000401062: crypto_aead_setauthsize (STB_GLOBAL)
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
int crypto_aead_setauthsize(struct crypto_aead *tfm, unsigned int authsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff814b9890)
Location: crypto/aead.c:69
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_init
  - crypto/aead.c:aead_geniv_setauthsize
  - crypto/gcm.c:crypto_rfc4543_setauthsize
  - crypto/gcm.c:crypto_rfc4106_setauthsize
```
**Symbols:**

```
ffffffff814b9890-ffffffff814b98dd: crypto_aead_setauthsize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int crypto_aead_setauthsize(struct crypto_aead *tfm, unsigned int authsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff814aa2b0)
Location: crypto/aead.c:69
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_init
  - crypto/aead.c:aead_geniv_setauthsize
  - crypto/gcm.c:crypto_rfc4543_setauthsize
  - crypto/gcm.c:crypto_rfc4106_setauthsize
```
**Symbols:**

```
ffffffff814aa2b0-ffffffff814aa2fd: crypto_aead_setauthsize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int crypto_aead_setauthsize(struct crypto_aead *tfm, unsigned int authsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff814b5920)
Location: crypto/aead.c:69
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_init
  - crypto/aead.c:aead_geniv_setauthsize
  - crypto/gcm.c:crypto_rfc4543_setauthsize
  - crypto/gcm.c:crypto_rfc4106_setauthsize
```
**Symbols:**

```
ffffffff814b5920-ffffffff814b596d: crypto_aead_setauthsize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int crypto_aead_setauthsize(struct crypto_aead *tfm, unsigned int authsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff814ce3c0)
Location: crypto/aead.c:69
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_init
  - crypto/aead.c:aead_geniv_setauthsize
  - crypto/gcm.c:crypto_rfc4543_setauthsize
  - crypto/gcm.c:crypto_rfc4106_setauthsize
```
**Symbols:**

```
ffffffff814ce3c0-ffffffff814ce40d: crypto_aead_setauthsize (STB_GLOBAL)
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
