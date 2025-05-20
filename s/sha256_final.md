# Function: <code>sha256_final</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int sha256_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/sha256_generic.c (ffffffff813a79fc)
Location: crypto/sha256_generic.c:234
Inline: True
Inline callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
```
**Symbols:**

```
ffffffff813a7db0-ffffffff813a7f15: sha256_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int sha256_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/sha256_generic.c (ffffffff813e5010)
Location: crypto/sha256_generic.c:250
Inline: False
Direct callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
```
**Symbols:**

```
ffffffff813e5010-ffffffff813e5163: sha256_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int sha256_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/sha256_generic.c (ffffffff813fe030)
Location: crypto/sha256_generic.c:250
Inline: False
Direct callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
```
**Symbols:**

```
ffffffff813fe030-ffffffff813fe183: sha256_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sha256_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/sha256_generic.c (ffffffff8140b320)
Location: crypto/sha256_generic.c:250
Inline: False
Direct callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
```
**Symbols:**

```
ffffffff8140b320-ffffffff8140b46c: sha256_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sha256_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/sha256_generic.c (ffffffff81433d40)
Location: crypto/sha256_generic.c:250
Inline: False
Direct callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
```
**Symbols:**

```
ffffffff81433d40-ffffffff81433e8c: sha256_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int sha256_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/sha256_generic.c (ffffffff814668b0)
Location: crypto/sha256_generic.c:250
Inline: False
Direct callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
```
**Symbols:**

```
ffffffff814668b0-ffffffff81466a0d: sha256_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sha256_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/sha256_generic.c (ffffffff81484520)
Location: crypto/sha256_generic.c:250
Inline: False
Direct callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
```
**Symbols:**

```
ffffffff81484520-ffffffff8148467d: sha256_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sha256_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/sha256_generic.c (ffffffff814b2750)
Location: crypto/sha256_generic.c:245
Inline: False
Direct callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
```
**Symbols:**

```
ffffffff814b2750-ffffffff814b28ad: sha256_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sha256_final(struct sha256_state *sctx, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/sha256.c (ffffffff81531440)
Location: lib/crypto/sha256.c:275
Inline: False
Direct callers:
  - crypto/sha256_generic.c:crypto_sha256_final
```
**Symbols:**

```
ffffffff81531440-ffffffff81531450: sha256_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sha256_final(struct sha256_state *sctx, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/sha256.c (ffffffff81595630)
Location: lib/crypto/sha256.c:271
Inline: False
Direct callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
  - drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware
  - net/mptcp/crypto.c:mptcp_crypto_hmac_sha
  - net/mptcp/crypto.c:mptcp_crypto_hmac_sha
  - net/mptcp/crypto.c:mptcp_crypto_key_sha
```
**Symbols:**

```
ffffffff81595630-ffffffff81595640: sha256_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void sha256_final(struct sha256_state *sctx, u8 *out);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/crypto/sha256.c (ffffffff815b1041)
Location: lib/crypto/sha256.c:187
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256
Direct callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
```
**Symbols:**

```
ffffffff815b0f90-ffffffff815b0fa5: sha256_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void sha256_final(struct sha256_state *sctx, u8 *out);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/crypto/sha256.c (ffffffff815bbe51)
Location: lib/crypto/sha256.c:187
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256
Direct callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
```
**Symbols:**

```
ffffffff815bbda0-ffffffff815bbdb5: sha256_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void sha256_final(struct sha256_state *sctx, u8 *out);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/crypto/sha256.c (ffffffff81622c89)
Location: lib/crypto/sha256.c:187
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256
Direct callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
```
**Symbols:**

```
ffffffff81622bd0-ffffffff81622be5: sha256_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void sha256_final(struct sha256_state *sctx, u8 *out);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/crypto/sha256.c (ffffffff816f2841)
Location: lib/crypto/sha256.c:187
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256
Direct callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
```
**Symbols:**

```
ffffffff816f2a10-ffffffff816f2b10: sha256_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void sha256_final(struct sha256_state *sctx, u8 *out);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/crypto/sha256.c (ffffffff817e4651)
Location: lib/crypto/sha256.c:187
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256
Direct callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
```
**Symbols:**

```
ffffffff817e4840-ffffffff817e4940: sha256_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void sha256_final(struct sha256_state *sctx, u8 *out);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/crypto/sha256.c (ffffffff818247c3)
Location: lib/crypto/sha256.c:146
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256
Direct callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
```
**Symbols:**

```
ffffffff81824850-ffffffff818248d5: sha256_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void sha256_final(struct sha256_state *sctx, u8 *out);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/crypto/sha256.c (ffffffff8186a803)
Location: lib/crypto/sha256.c:146
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256
Direct callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
```
**Symbols:**

```
ffffffff8186a890-ffffffff8186a915: sha256_final (STB_GLOBAL)
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
int sha256_final(struct sha256_state *sctx, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/sha256.c (ffff80001063d4e8)
Location: lib/crypto/sha256.c:275
Inline: False
Direct callers:
  - crypto/sha256_generic.c:crypto_sha256_final
```
**Symbols:**

```
ffff80001063d4e8-ffff80001063d500: sha256_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sha256_final(struct sha256_state *sctx, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/sha256.c (c07e392c)
Location: lib/crypto/sha256.c:275
Inline: False
Direct callers:
  - crypto/sha256_generic.c:crypto_sha256_final
```
**Symbols:**

```
c07e392c-c07e3944: sha256_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sha256_final(struct sha256_state *sctx, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/sha256.c (c0000000007e4ef0)
Location: lib/crypto/sha256.c:275
Inline: False
Direct callers:
  - crypto/sha256_generic.c:crypto_sha256_final
```
**Symbols:**

```
c0000000007e4ef0-c0000000007e4f00: sha256_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sha256_final(struct sha256_state *sctx, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/sha256.c (ffffffe00046b214)
Location: lib/crypto/sha256.c:275
Inline: False
Direct callers:
  - crypto/sha256_generic.c:crypto_sha256_final
```
**Symbols:**

```
ffffffe00046b214-ffffffe00046b22e: sha256_final (STB_GLOBAL)
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
int sha256_final(struct sha256_state *sctx, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/sha256.c (ffffffff81529a20)
Location: lib/crypto/sha256.c:275
Inline: False
Direct callers:
  - crypto/sha256_generic.c:crypto_sha256_final
```
**Symbols:**

```
ffffffff81529a20-ffffffff81529a30: sha256_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sha256_final(struct sha256_state *sctx, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/sha256.c (ffffffff81519d00)
Location: lib/crypto/sha256.c:275
Inline: False
Direct callers:
  - crypto/sha256_generic.c:crypto_sha256_final
```
**Symbols:**

```
ffffffff81519d00-ffffffff81519d10: sha256_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sha256_final(struct sha256_state *sctx, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/sha256.c (ffffffff81525ab0)
Location: lib/crypto/sha256.c:275
Inline: False
Direct callers:
  - crypto/sha256_generic.c:crypto_sha256_final
```
**Symbols:**

```
ffffffff81525ab0-ffffffff81525ac0: sha256_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sha256_final(struct sha256_state *sctx, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/sha256.c (ffffffff8153f430)
Location: lib/crypto/sha256.c:275
Inline: False
Direct callers:
  - crypto/sha256_generic.c:crypto_sha256_final
```
**Symbols:**

```
ffffffff8153f430-ffffffff8153f440: sha256_final (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct sha256_state *sctx</code>
</li>
<li>
<b>Param removed. </b>
<code>struct shash_desc *desc</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
