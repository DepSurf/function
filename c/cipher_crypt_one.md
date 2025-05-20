# Function: <code>cipher_crypt_one</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/cipher.c (0)
Location: crypto/cipher.c:58
Inline: True
Inline callers:
  - crypto/cipher.c:crypto_cipher_decrypt_one
  - crypto/cipher.c:crypto_cipher_encrypt_one
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
In crypto/cipher.c (0)
Location: crypto/cipher.c:58
Inline: True
Inline callers:
  - crypto/cipher.c:crypto_cipher_decrypt_one
  - crypto/cipher.c:crypto_cipher_encrypt_one
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
In crypto/cipher.c (0)
Location: crypto/cipher.c:59
Inline: True
Inline callers:
  - crypto/cipher.c:crypto_cipher_decrypt_one
  - crypto/cipher.c:crypto_cipher_encrypt_one
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
In crypto/cipher.c (0)
Location: crypto/cipher.c:59
Inline: True
Inline callers:
  - crypto/cipher.c:crypto_cipher_decrypt_one
  - crypto/cipher.c:crypto_cipher_encrypt_one
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
In crypto/cipher.c (0)
Location: crypto/cipher.c:59
Inline: True
Inline callers:
  - crypto/cipher.c:crypto_cipher_decrypt_one
  - crypto/cipher.c:crypto_cipher_encrypt_one
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void cipher_crypt_one(struct crypto_cipher *tfm, u8 *dst, const u8 *src, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cipher.c (ffffffff81704dd0)
Location: crypto/cipher.c:59
Inline: False
Direct callers:
  - crypto/cipher.c:crypto_cipher_decrypt_one
  - crypto/cipher.c:crypto_cipher_encrypt_one
```
**Symbols:**

```
ffffffff81704dd0-ffffffff81704eb3: cipher_crypt_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void cipher_crypt_one(struct crypto_cipher *tfm, u8 *dst, const u8 *src, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cipher.c (ffffffff8173f0a0)
Location: crypto/cipher.c:59
Inline: False
Direct callers:
  - crypto/cipher.c:crypto_cipher_decrypt_one
  - crypto/cipher.c:crypto_cipher_encrypt_one
```
**Symbols:**

```
ffffffff8173f0a0-ffffffff8173f183: cipher_crypt_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void cipher_crypt_one(struct crypto_cipher *tfm, u8 *dst, const u8 *src, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cipher.c (ffffffff8177ff20)
Location: crypto/cipher.c:59
Inline: False
Direct callers:
  - crypto/cipher.c:crypto_cipher_decrypt_one
  - crypto/cipher.c:crypto_cipher_encrypt_one
```
**Symbols:**

```
ffffffff8177ff20-ffffffff81780003: cipher_crypt_one (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
