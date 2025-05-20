# Function: <code>calc_buffer_shash_tfm</code>

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
In security/integrity/ima/ima_crypto.c (ffffffff813d481f)
Location: security/integrity/ima/ima_crypto.c:579
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
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
In security/integrity/ima/ima_crypto.c (ffffffff813ec26f)
Location: security/integrity/ima/ima_crypto.c:581
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
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
In security/integrity/ima/ima_crypto.c (ffffffff813f863b)
Location: security/integrity/ima/ima_crypto.c:581
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff814209ab)
Location: security/integrity/ima/ima_crypto.c:569
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff81452e48)
Location: security/integrity/ima/ima_crypto.c:571
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int calc_buffer_shash_tfm(const void *buf, loff_t size, struct ima_digest_data *hash, struct crypto_shash *tfm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff8146f0d0)
Location: security/integrity/ima/ima_crypto.c:585
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
```
**Symbols:**

```
ffffffff8146f0d0-ffffffff8146f1b6: calc_buffer_shash_tfm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int calc_buffer_shash_tfm(const void *buf, loff_t size, struct ima_digest_data *hash, struct crypto_shash *tfm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff8149cb90)
Location: security/integrity/ima/ima_crypto.c:580
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
```
**Symbols:**

```
ffffffff8149cb90-ffffffff8149cc6d: calc_buffer_shash_tfm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int calc_buffer_shash_tfm(const void *buf, loff_t size, struct ima_digest_data *hash, struct crypto_shash *tfm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff814b6ef0)
Location: security/integrity/ima/ima_crypto.c:588
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
```
**Symbols:**

```
ffffffff814b6ef0-ffffffff814b6fcd: calc_buffer_shash_tfm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int calc_buffer_shash_tfm(const void *buf, loff_t size, struct ima_digest_data *hash, struct crypto_shash *tfm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff81516af0)
Location: security/integrity/ima/ima_crypto.c:729
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
```
**Symbols:**

```
ffffffff81516af0-ffffffff81516bcd: calc_buffer_shash_tfm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int calc_buffer_shash_tfm(const void *buf, loff_t size, struct ima_digest_data *hash, struct crypto_shash *tfm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff81533cb0)
Location: security/integrity/ima/ima_crypto.c:719
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
```
**Symbols:**

```
ffffffff81533cb0-ffffffff81533d8d: calc_buffer_shash_tfm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int calc_buffer_shash_tfm(const void *buf, loff_t size, struct ima_digest_data *hash, struct crypto_shash *tfm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff8153c2f0)
Location: security/integrity/ima/ima_crypto.c:719
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
```
**Symbols:**

```
ffffffff8153c2f0-ffffffff8153c3bf: calc_buffer_shash_tfm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int calc_buffer_shash_tfm(const void *buf, loff_t size, struct ima_digest_data *hash, struct crypto_shash *tfm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff8159afd0)
Location: security/integrity/ima/ima_crypto.c:719
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
```
**Symbols:**

```
ffffffff8159afd0-ffffffff8159b09f: calc_buffer_shash_tfm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int calc_buffer_shash_tfm(const void *buf, loff_t size, struct ima_digest_data *hash, struct crypto_shash *tfm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff8163fe30)
Location: security/integrity/ima/ima_crypto.c:720
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
```
**Symbols:**

```
ffffffff8163fe30-ffffffff8163ff15: calc_buffer_shash_tfm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int calc_buffer_shash_tfm(const void *buf, loff_t size, struct ima_digest_data *hash, struct crypto_shash *tfm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff816f7c70)
Location: security/integrity/ima/ima_crypto.c:720
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
```
**Symbols:**

```
ffffffff816f7c70-ffffffff816f7d55: calc_buffer_shash_tfm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int calc_buffer_shash_tfm(const void *buf, loff_t size, struct ima_digest_data *hash, struct crypto_shash *tfm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff81731ee0)
Location: security/integrity/ima/ima_crypto.c:720
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
```
**Symbols:**

```
ffffffff81731ee0-ffffffff81731fc5: calc_buffer_shash_tfm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int calc_buffer_shash_tfm(const void *buf, loff_t size, struct ima_digest_data *hash, struct crypto_shash *tfm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff81772900)
Location: security/integrity/ima/ima_crypto.c:720
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
```
**Symbols:**

```
ffffffff81772900-ffffffff817729e5: calc_buffer_shash_tfm (STB_LOCAL)
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
int calc_buffer_shash_tfm(const void *buf, loff_t size, struct ima_digest_data *hash, struct crypto_shash *tfm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffff8000105af2c8)
Location: security/integrity/ima/ima_crypto.c:588
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
```
**Symbols:**

```
ffff8000105af2c8-ffff8000105af3c0: calc_buffer_shash_tfm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int calc_buffer_shash_tfm(const void *buf, loff_t size, struct ima_digest_data *hash, struct crypto_shash *tfm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (c075e90c)
Location: security/integrity/ima/ima_crypto.c:588
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
```
**Symbols:**

```
c075e90c-c075ea20: calc_buffer_shash_tfm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int calc_buffer_shash_tfm(const void *buf, loff_t size, struct ima_digest_data *hash, struct crypto_shash *tfm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (c00000000072e4b0)
Location: security/integrity/ima/ima_crypto.c:588
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
```
**Symbols:**

```
c00000000072e4b0-c00000000072e62c: calc_buffer_shash_tfm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int calc_buffer_shash_tfm(const void *buf, loff_t size, struct ima_digest_data *hash, struct crypto_shash *tfm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffe0003f716a)
Location: security/integrity/ima/ima_crypto.c:588
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
```
**Symbols:**

```
ffffffe0003f716a-ffffffe0003f720a: calc_buffer_shash_tfm (STB_LOCAL)
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
int calc_buffer_shash_tfm(const void *buf, loff_t size, struct ima_digest_data *hash, struct crypto_shash *tfm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff814af4d0)
Location: security/integrity/ima/ima_crypto.c:588
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
```
**Symbols:**

```
ffffffff814af4d0-ffffffff814af5ad: calc_buffer_shash_tfm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int calc_buffer_shash_tfm(const void *buf, loff_t size, struct ima_digest_data *hash, struct crypto_shash *tfm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff8149fef0)
Location: security/integrity/ima/ima_crypto.c:588
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
```
**Symbols:**

```
ffffffff8149fef0-ffffffff8149ffcd: calc_buffer_shash_tfm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int calc_buffer_shash_tfm(const void *buf, loff_t size, struct ima_digest_data *hash, struct crypto_shash *tfm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff814ab560)
Location: security/integrity/ima/ima_crypto.c:588
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
```
**Symbols:**

```
ffffffff814ab560-ffffffff814ab63d: calc_buffer_shash_tfm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int calc_buffer_shash_tfm(const void *buf, loff_t size, struct ima_digest_data *hash, struct crypto_shash *tfm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff814c3fb0)
Location: security/integrity/ima/ima_crypto.c:588
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
```
**Symbols:**

```
ffffffff814c3fb0-ffffffff814c408d: calc_buffer_shash_tfm (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
