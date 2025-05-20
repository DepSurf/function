# Function: <code>hkdf_extract</code>

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
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int hkdf_extract(struct crypto_shash *hmac_tfm, const u8 *ikm, unsigned int ikmlen, u8 *prk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/hkdf.c (0)
Location: fs/crypto/hkdf.c:43
Inline: False
Direct callers:
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
```
**Symbols:**

```
ffffffff8134b690-ffffffff8134b74d: hkdf_extract (STB_LOCAL)
ffffffff8134bb47-ffffffff8134bb53: hkdf_extract.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/hkdf.c (ffffffff813910cc)
Location: fs/crypto/hkdf.c:43
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/hkdf.c (ffffffff813a252c)
Location: fs/crypto/hkdf.c:43
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/hkdf.c (ffffffff813a96ac)
Location: fs/crypto/hkdf.c:43
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/hkdf.c (ffffffff813f8eec)
Location: fs/crypto/hkdf.c:48
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/hkdf.c (ffffffff8146bcab)
Location: fs/crypto/hkdf.c:48
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/hkdf.c (ffffffff814fcfab)
Location: fs/crypto/hkdf.c:48
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/hkdf.c (ffffffff8153450b)
Location: fs/crypto/hkdf.c:48
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/hkdf.c (ffffffff815694cb)
Location: fs/crypto/hkdf.c:48
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
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
int hkdf_extract(struct crypto_shash *hmac_tfm, const u8 *ikm, unsigned int ikmlen, u8 *prk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hkdf.c (ffff80001040c0a8)
Location: fs/crypto/hkdf.c:43
Inline: False
Direct callers:
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
```
**Symbols:**

```
ffff80001040c0a8-ffff80001040c194: hkdf_extract (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int hkdf_extract(struct crypto_shash *hmac_tfm, const u8 *ikm, unsigned int ikmlen, u8 *prk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hkdf.c (c05d91cc)
Location: fs/crypto/hkdf.c:43
Inline: False
Direct callers:
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
```
**Symbols:**

```
c05d91cc-c05d92a0: hkdf_extract (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int hkdf_extract(struct crypto_shash *hmac_tfm, const u8 *ikm, unsigned int ikmlen, u8 *prk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hkdf.c (c000000000518fa0)
Location: fs/crypto/hkdf.c:43
Inline: False
Direct callers:
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
```
**Symbols:**

```
c000000000518fa0-c0000000005190bc: hkdf_extract (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int hkdf_extract(struct crypto_shash *hmac_tfm, const u8 *ikm, unsigned int ikmlen, u8 *prk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hkdf.c (ffffffe0002b5a7c)
Location: fs/crypto/hkdf.c:43
Inline: False
Direct callers:
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
```
**Symbols:**

```
ffffffe0002b5a7c-ffffffe0002b5b02: hkdf_extract (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int hkdf_extract(struct crypto_shash *hmac_tfm, const u8 *ikm, unsigned int ikmlen, u8 *prk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/hkdf.c (0)
Location: fs/crypto/hkdf.c:43
Inline: False
Direct callers:
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
```
**Symbols:**

```
ffffffff81343c70-ffffffff81343d2d: hkdf_extract (STB_LOCAL)
ffffffff81344127-ffffffff81344133: hkdf_extract.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int hkdf_extract(struct crypto_shash *hmac_tfm, const u8 *ikm, unsigned int ikmlen, u8 *prk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/hkdf.c (0)
Location: fs/crypto/hkdf.c:43
Inline: False
Direct callers:
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
```
**Symbols:**

```
ffffffff81334950-ffffffff81334a0d: hkdf_extract (STB_LOCAL)
ffffffff81334e07-ffffffff81334e13: hkdf_extract.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int hkdf_extract(struct crypto_shash *hmac_tfm, const u8 *ikm, unsigned int ikmlen, u8 *prk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/hkdf.c (0)
Location: fs/crypto/hkdf.c:43
Inline: False
Direct callers:
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
```
**Symbols:**

```
ffffffff81341740-ffffffff813417fd: hkdf_extract (STB_LOCAL)
ffffffff81341bf7-ffffffff81341c03: hkdf_extract.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int hkdf_extract(struct crypto_shash *hmac_tfm, const u8 *ikm, unsigned int ikmlen, u8 *prk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/hkdf.c (0)
Location: fs/crypto/hkdf.c:43
Inline: False
Direct callers:
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
```
**Symbols:**

```
ffffffff81354a40-ffffffff81354afd: hkdf_extract (STB_LOCAL)
ffffffff81354ef7-ffffffff81354f03: hkdf_extract.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
