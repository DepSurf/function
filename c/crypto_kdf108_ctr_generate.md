# Function: <code>crypto_kdf108_ctr_generate</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int crypto_kdf108_ctr_generate(struct crypto_shash *kmd, const struct kvec *info, unsigned int info_nvec, u8 *dst, unsigned int dlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/kdf_sp800108.c (0)
Location: crypto/kdf_sp800108.c:17
Inline: False
Direct callers:
  - security/keys/dh.c:keyctl_dh_compute_kdf
```
**Symbols:**

```
ffffffff81e8b108-ffffffff81e8b114: crypto_kdf108_ctr_generate.cold (STB_LOCAL)
ffffffff8166e050-ffffffff8166e2b1: crypto_kdf108_ctr_generate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int crypto_kdf108_ctr_generate(struct crypto_shash *kmd, const struct kvec *info, unsigned int info_nvec, u8 *dst, unsigned int dlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/kdf_sp800108.c (ffffffff81729240)
Location: crypto/kdf_sp800108.c:17
Inline: False
Direct callers:
  - security/keys/dh.c:keyctl_dh_compute_kdf
```
**Symbols:**

```
ffffffff81729240-ffffffff817294a9: crypto_kdf108_ctr_generate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int crypto_kdf108_ctr_generate(struct crypto_shash *kmd, const struct kvec *info, unsigned int info_nvec, u8 *dst, unsigned int dlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/kdf_sp800108.c (ffffffff817655a0)
Location: crypto/kdf_sp800108.c:17
Inline: False
Direct callers:
  - security/keys/dh.c:keyctl_dh_compute_kdf
```
**Symbols:**

```
ffffffff817655a0-ffffffff81765809: crypto_kdf108_ctr_generate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int crypto_kdf108_ctr_generate(struct crypto_shash *kmd, const struct kvec *info, unsigned int info_nvec, u8 *dst, unsigned int dlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/kdf_sp800108.c (ffffffff817a71a0)
Location: crypto/kdf_sp800108.c:17
Inline: False
Direct callers:
  - security/keys/dh.c:keyctl_dh_compute_kdf
```
**Symbols:**

```
ffffffff817a71a0-ffffffff817a7409: crypto_kdf108_ctr_generate (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
