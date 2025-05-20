# Function: <code>crypto_aead_encrypt</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/seqiv.c (ffffffff813dea34)
Location: include/crypto/aead.h:328
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/seqiv.c (ffffffff813f6fd4)
Location: include/crypto/aead.h:328
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/seqiv.c (ffffffff814033d0)
Location: include/crypto/aead.h:328
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/big_key.c (ffffffff813bc083)
Location: include/crypto/aead.h:328
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_crypt
```
```
In crypto/seqiv.c (ffffffff8142bac6)
Location: include/crypto/aead.h:328
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff81439093)
Location: include/crypto/aead.h:328
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_encrypt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/big_key.c (ffffffff813ece48)
Location: include/crypto/aead.h:328
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_crypt
```
```
In crypto/seqiv.c (ffffffff8145e7d7)
Location: include/crypto/aead.h:328
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff8146b451)
Location: include/crypto/aead.h:328
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_encrypt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/big_key.c (ffffffff8140800c)
Location: include/crypto/aead.h:325
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_crypt
```
```
In crypto/seqiv.c (ffffffff8147c100)
Location: include/crypto/aead.h:325
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff814897a4)
Location: include/crypto/aead.h:325
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_encrypt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int crypto_aead_encrypt(struct aead_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff814a6710)
Location: crypto/aead.c:87
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_crypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_encrypt
```
**Symbols:**

```
ffffffff814a6710-ffffffff814a6771: crypto_aead_encrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int crypto_aead_encrypt(struct aead_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff814c1380)
Location: crypto/aead.c:88
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_crypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_encrypt
```
**Symbols:**

```
ffffffff814c1380-ffffffff814c13e1: crypto_aead_encrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int crypto_aead_encrypt(struct aead_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff81521d50)
Location: crypto/aead.c:83
Inline: False
Direct callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_encrypt
```
**Symbols:**

```
ffffffff81521d50-ffffffff81521db1: crypto_aead_encrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int crypto_aead_encrypt(struct aead_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff8153eba0)
Location: crypto/aead.c:83
Inline: False
Direct callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_encrypt
```
**Symbols:**

```
ffffffff8153eba0-ffffffff8153ec01: crypto_aead_encrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int crypto_aead_encrypt(struct aead_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff81547240)
Location: crypto/aead.c:83
Inline: False
Direct callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_encrypt
```
**Symbols:**

```
ffffffff81547240-ffffffff815472a1: crypto_aead_encrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int crypto_aead_encrypt(struct aead_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff815a7a20)
Location: crypto/aead.c:83
Inline: False
Direct callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_encrypt
```
**Symbols:**

```
ffffffff815a7a20-ffffffff815a7a81: crypto_aead_encrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int crypto_aead_encrypt(struct aead_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff8164ed80)
Location: crypto/aead.c:83
Inline: False
Direct callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_encrypt
```
**Symbols:**

```
ffffffff8164ed80-ffffffff8164ede8: crypto_aead_encrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int crypto_aead_encrypt(struct aead_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff81708180)
Location: crypto/aead.c:83
Inline: False
Direct callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_encrypt
```
**Symbols:**

```
ffffffff81708180-ffffffff817081e8: crypto_aead_encrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int crypto_aead_encrypt(struct aead_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff81741f10)
Location: crypto/aead.c:104
Inline: False
Direct callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_encrypt
```
**Symbols:**

```
ffffffff81741f10-ffffffff81741f71: crypto_aead_encrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int crypto_aead_encrypt(struct aead_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff81782df0)
Location: crypto/aead.c:104
Inline: False
Direct callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_encrypt
```
**Symbols:**

```
ffffffff81782df0-ffffffff81782e51: crypto_aead_encrypt (STB_GLOBAL)
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
int crypto_aead_encrypt(struct aead_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffff8000105bb6c0)
Location: crypto/aead.c:88
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_crypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_encrypt
```
**Symbols:**

```
ffff8000105bb6c0-ffff8000105bb738: crypto_aead_encrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int crypto_aead_encrypt(struct aead_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (c0769904)
Location: crypto/aead.c:88
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_crypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_encrypt
```
**Symbols:**

```
c0769904-c0769970: crypto_aead_encrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int crypto_aead_encrypt(struct aead_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (c000000000741fd0)
Location: crypto/aead.c:88
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_crypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_encrypt
```
**Symbols:**

```
c000000000741fd0-c000000000742088: crypto_aead_encrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int crypto_aead_encrypt(struct aead_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffe000401110)
Location: crypto/aead.c:88
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_crypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_encrypt
```
**Symbols:**

```
ffffffe000401110-ffffffe00040117e: crypto_aead_encrypt (STB_GLOBAL)
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
int crypto_aead_encrypt(struct aead_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff814b9960)
Location: crypto/aead.c:88
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_crypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_encrypt
```
**Symbols:**

```
ffffffff814b9960-ffffffff814b99c1: crypto_aead_encrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int crypto_aead_encrypt(struct aead_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff814aa380)
Location: crypto/aead.c:88
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_crypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_encrypt
```
**Symbols:**

```
ffffffff814aa380-ffffffff814aa3e1: crypto_aead_encrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int crypto_aead_encrypt(struct aead_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff814b59f0)
Location: crypto/aead.c:88
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_crypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_encrypt
```
**Symbols:**

```
ffffffff814b59f0-ffffffff814b5a51: crypto_aead_encrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int crypto_aead_encrypt(struct aead_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff814ce490)
Location: crypto/aead.c:88
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_crypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_encrypt
```
**Symbols:**

```
ffffffff814ce490-ffffffff814ce4f1: crypto_aead_encrypt (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
