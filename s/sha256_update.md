# Function: <code>sha256_update</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sha256_update(struct sha256_state *sctx, const u8 *data, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/sha256.c (ffffffff81531240)
Location: lib/crypto/sha256.c:209
Inline: False
Direct callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
  - crypto/sha256_generic.c:crypto_sha256_update
  - lib/crypto/sha256.c:__sha256_final
  - lib/crypto/sha256.c:__sha256_final
  - lib/crypto/sha256.c:sha224_update
```
**Symbols:**

```
ffffffff81531240-ffffffff8153134d: sha256_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sha256_update(struct sha256_state *sctx, const u8 *data, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/sha256.c (ffffffff81595440)
Location: lib/crypto/sha256.c:209
Inline: False
Direct callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
  - crypto/sha256_generic.c:crypto_sha256_update
  - lib/crypto/sha256.c:__sha256_final
  - lib/crypto/sha256.c:__sha256_final
  - lib/crypto/sha256.c:sha224_update
  - drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware
  - net/mptcp/crypto.c:mptcp_crypto_hmac_sha
  - net/mptcp/crypto.c:mptcp_crypto_hmac_sha
  - net/mptcp/crypto.c:mptcp_crypto_key_sha
```
**Symbols:**

```
ffffffff81595440-ffffffff8159554b: sha256_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sha256_update(struct sha256_state *sctx, const u8 *data, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/sha256.c (ffffffff815b0d40)
Location: lib/crypto/sha256.c:122
Inline: False
Direct callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
  - crypto/sha256_generic.c:crypto_sha256_update
  - lib/crypto/sha256.c:sha256
  - lib/crypto/sha256.c:sha256
  - lib/crypto/sha256.c:sha256
  - lib/crypto/sha256.c:sha224_update
```
**Symbols:**

```
ffffffff815b0d40-ffffffff815b0ea5: sha256_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sha256_update(struct sha256_state *sctx, const u8 *data, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/sha256.c (ffffffff815bbb50)
Location: lib/crypto/sha256.c:122
Inline: False
Direct callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
  - crypto/sha256_generic.c:crypto_sha256_update
  - lib/crypto/sha256.c:sha256
  - lib/crypto/sha256.c:sha256
  - lib/crypto/sha256.c:sha256
  - lib/crypto/sha256.c:sha224_update
```
**Symbols:**

```
ffffffff815bbb50-ffffffff815bbcb5: sha256_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sha256_update(struct sha256_state *sctx, const u8 *data, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/sha256.c (ffffffff81622950)
Location: lib/crypto/sha256.c:122
Inline: False
Direct callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
  - crypto/sha256_generic.c:crypto_sha256_update
  - lib/crypto/sha256.c:sha256
  - lib/crypto/sha256.c:sha256
  - lib/crypto/sha256.c:sha256
  - lib/crypto/sha256.c:sha224_update
```
**Symbols:**

```
ffffffff81622950-ffffffff81622ab5: sha256_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sha256_update(struct sha256_state *sctx, const u8 *data, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/sha256.c (ffffffff816f25f0)
Location: lib/crypto/sha256.c:122
Inline: False
Direct callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
  - crypto/sha256_generic.c:crypto_sha256_update
  - lib/crypto/sha256.c:sha256
  - lib/crypto/sha256.c:sha256
  - lib/crypto/sha256.c:sha256
  - lib/crypto/sha256.c:sha224_final
  - lib/crypto/sha256.c:sha224_final
  - lib/crypto/sha256.c:sha224_update
```
**Symbols:**

```
ffffffff816f25f0-ffffffff816f279c: sha256_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sha256_update(struct sha256_state *sctx, const u8 *data, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/sha256.c (ffffffff817e43e0)
Location: lib/crypto/sha256.c:122
Inline: False
Direct callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
  - crypto/sha256_generic.c:crypto_sha256_update
  - lib/crypto/sha256.c:sha256
  - lib/crypto/sha256.c:sha256
  - lib/crypto/sha256.c:sha256
  - lib/crypto/sha256.c:sha224_final
  - lib/crypto/sha256.c:sha224_final
  - lib/crypto/sha256.c:sha224_update
```
**Symbols:**

```
ffffffff817e43e0-ffffffff817e458c: sha256_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void sha256_update(struct sha256_state *sctx, const u8 *data, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/crypto/sha256.c (ffffffff818247be)
Location: lib/crypto/sha256.c:134
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256
Direct callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
  - crypto/sha256_generic.c:crypto_sha256_update
```
**Symbols:**

```
ffffffff818245d0-ffffffff818245ea: sha256_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void sha256_update(struct sha256_state *sctx, const u8 *data, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/crypto/sha256.c (ffffffff8186a7fe)
Location: lib/crypto/sha256.c:134
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256
Direct callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
  - crypto/sha256_generic.c:crypto_sha256_update
```
**Symbols:**

```
ffffffff8186a610-ffffffff8186a62a: sha256_update (STB_GLOBAL)
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
int sha256_update(struct sha256_state *sctx, const u8 *data, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/sha256.c (ffff80001063d2e8)
Location: lib/crypto/sha256.c:209
Inline: False
Direct callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
  - crypto/sha256_generic.c:crypto_sha256_update
  - lib/crypto/sha256.c:__sha256_final
  - lib/crypto/sha256.c:__sha256_final
  - lib/crypto/sha256.c:sha224_update
```
**Symbols:**

```
ffff80001063d2e8-ffff80001063d3b0: sha256_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sha256_update(struct sha256_state *sctx, const u8 *data, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/sha256.c (c07e378c)
Location: lib/crypto/sha256.c:209
Inline: False
Direct callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
  - crypto/sha256_generic.c:crypto_sha256_update
  - lib/crypto/sha256.c:__sha256_final
  - lib/crypto/sha256.c:__sha256_final
  - lib/crypto/sha256.c:sha224_update
```
**Symbols:**

```
c07e378c-c07e3824: sha256_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sha256_update(struct sha256_state *sctx, const u8 *data, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/sha256.c (c0000000007e4c60)
Location: lib/crypto/sha256.c:209
Inline: False
Direct callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
  - crypto/sha256_generic.c:crypto_sha256_update
  - lib/crypto/sha256.c:__sha256_final
  - lib/crypto/sha256.c:__sha256_final
  - lib/crypto/sha256.c:sha224_update
```
**Symbols:**

```
c0000000007e4c60-c0000000007e4d98: sha256_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sha256_update(struct sha256_state *sctx, const u8 *data, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/sha256.c (ffffffe00046b02c)
Location: lib/crypto/sha256.c:209
Inline: False
Direct callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
  - crypto/sha256_generic.c:crypto_sha256_update
  - lib/crypto/sha256.c:__sha256_final
  - lib/crypto/sha256.c:__sha256_final
  - lib/crypto/sha256.c:sha224_update
```
**Symbols:**

```
ffffffe00046b02c-ffffffe00046b0dc: sha256_update (STB_GLOBAL)
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
int sha256_update(struct sha256_state *sctx, const u8 *data, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/sha256.c (ffffffff81529820)
Location: lib/crypto/sha256.c:209
Inline: False
Direct callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
  - crypto/sha256_generic.c:crypto_sha256_update
  - lib/crypto/sha256.c:__sha256_final
  - lib/crypto/sha256.c:__sha256_final
  - lib/crypto/sha256.c:sha224_update
```
**Symbols:**

```
ffffffff81529820-ffffffff8152992d: sha256_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sha256_update(struct sha256_state *sctx, const u8 *data, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/sha256.c (ffffffff81519b00)
Location: lib/crypto/sha256.c:209
Inline: False
Direct callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
  - crypto/sha256_generic.c:crypto_sha256_update
  - lib/crypto/sha256.c:__sha256_final
  - lib/crypto/sha256.c:__sha256_final
  - lib/crypto/sha256.c:sha224_update
```
**Symbols:**

```
ffffffff81519b00-ffffffff81519c0d: sha256_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sha256_update(struct sha256_state *sctx, const u8 *data, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/sha256.c (ffffffff815258b0)
Location: lib/crypto/sha256.c:209
Inline: False
Direct callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
  - crypto/sha256_generic.c:crypto_sha256_update
  - lib/crypto/sha256.c:__sha256_final
  - lib/crypto/sha256.c:__sha256_final
  - lib/crypto/sha256.c:sha224_update
```
**Symbols:**

```
ffffffff815258b0-ffffffff815259bd: sha256_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sha256_update(struct sha256_state *sctx, const u8 *data, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/sha256.c (ffffffff8153f230)
Location: lib/crypto/sha256.c:209
Inline: False
Direct callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
  - crypto/sha256_generic.c:crypto_sha256_update
  - lib/crypto/sha256.c:__sha256_final
  - lib/crypto/sha256.c:__sha256_final
  - lib/crypto/sha256.c:sha224_update
```
**Symbols:**

```
ffffffff8153f230-ffffffff8153f33d: sha256_update (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
