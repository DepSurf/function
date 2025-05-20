# Function: <code>ima_calc_file_hash_tfm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff813981ed)
Location: security/integrity/ima/ima_crypto.c:353
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff813d409a)
Location: security/integrity/ima/ima_crypto.c:353
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
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
In security/integrity/ima/ima_crypto.c (ffffffff813ebaea)
Location: security/integrity/ima/ima_crypto.c:353
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
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
In security/integrity/ima/ima_crypto.c (ffffffff813f7e13)
Location: security/integrity/ima/ima_crypto.c:353
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
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
In security/integrity/ima/ima_crypto.c (ffffffff8141fed7)
Location: security/integrity/ima/ima_crypto.c:331
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
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
In security/integrity/ima/ima_crypto.c (ffffffff814524d8)
Location: security/integrity/ima/ima_crypto.c:333
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ima_calc_file_hash_tfm(struct file *file, struct ima_digest_data *hash, struct crypto_shash *tfm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff8146f540)
Location: security/integrity/ima/ima_crypto.c:326
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
**Symbols:**

```
ffffffff8146f540-ffffffff8146f6a0: ima_calc_file_hash_tfm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ima_calc_file_hash_tfm(struct file *file, struct ima_digest_data *hash, struct crypto_shash *tfm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff8149cec0)
Location: security/integrity/ima/ima_crypto.c:323
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
**Symbols:**

```
ffffffff8149cec0-ffffffff8149d006: ima_calc_file_hash_tfm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ima_calc_file_hash_tfm(struct file *file, struct ima_digest_data *hash, struct crypto_shash *tfm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff814b7220)
Location: security/integrity/ima/ima_crypto.c:331
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
**Symbols:**

```
ffffffff814b7220-ffffffff814b7366: ima_calc_file_hash_tfm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ima_calc_file_hash_tfm(struct file *file, struct ima_digest_data *hash, struct crypto_shash *tfm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff81516bd0)
Location: security/integrity/ima/ima_crypto.c:455
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
**Symbols:**

```
ffffffff81516bd0-ffffffff81516d1b: ima_calc_file_hash_tfm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ima_calc_file_hash_tfm(struct file *file, struct ima_digest_data *hash, struct crypto_shash *tfm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff81533d90)
Location: security/integrity/ima/ima_crypto.c:455
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
**Symbols:**

```
ffffffff81533d90-ffffffff81533edb: ima_calc_file_hash_tfm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ima_calc_file_hash_tfm(struct file *file, struct ima_digest_data *hash, struct crypto_shash *tfm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff8153c3c0)
Location: security/integrity/ima/ima_crypto.c:455
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
**Symbols:**

```
ffffffff8153c3c0-ffffffff8153c50b: ima_calc_file_hash_tfm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ima_calc_file_hash_tfm(struct file *file, struct ima_digest_data *hash, struct crypto_shash *tfm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff8159b0a0)
Location: security/integrity/ima/ima_crypto.c:455
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
**Symbols:**

```
ffffffff8159b0a0-ffffffff8159b1eb: ima_calc_file_hash_tfm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ima_calc_file_hash_tfm(struct file *file, struct ima_digest_data *hash, struct crypto_shash *tfm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff8163ff20)
Location: security/integrity/ima/ima_crypto.c:456
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
**Symbols:**

```
ffffffff8163ff20-ffffffff81640086: ima_calc_file_hash_tfm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ima_calc_file_hash_tfm(struct file *file, struct ima_digest_data *hash, struct crypto_shash *tfm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff816f7d70)
Location: security/integrity/ima/ima_crypto.c:456
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
**Symbols:**

```
ffffffff816f7d70-ffffffff816f7ed6: ima_calc_file_hash_tfm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ima_calc_file_hash_tfm(struct file *file, struct ima_digest_data *hash, struct crypto_shash *tfm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff81731fe0)
Location: security/integrity/ima/ima_crypto.c:456
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
**Symbols:**

```
ffffffff81731fe0-ffffffff81732149: ima_calc_file_hash_tfm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ima_calc_file_hash_tfm(struct file *file, struct ima_digest_data *hash, struct crypto_shash *tfm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff81772c00)
Location: security/integrity/ima/ima_crypto.c:456
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
**Symbols:**

```
ffffffff81772c00-ffffffff81772d98: ima_calc_file_hash_tfm (STB_LOCAL)
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
int ima_calc_file_hash_tfm(struct file *file, struct ima_digest_data *hash, struct crypto_shash *tfm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffff8000105af498)
Location: security/integrity/ima/ima_crypto.c:331
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
**Symbols:**

```
ffff8000105af498-ffff8000105af60c: ima_calc_file_hash_tfm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ima_calc_file_hash_tfm(struct file *file, struct ima_digest_data *hash, struct crypto_shash *tfm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (c075ec84)
Location: security/integrity/ima/ima_crypto.c:331
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
**Symbols:**

```
c075ec84-c075ee50: ima_calc_file_hash_tfm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ima_calc_file_hash_tfm(struct file *file, struct ima_digest_data *hash, struct crypto_shash *tfm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (c00000000072ebb0)
Location: security/integrity/ima/ima_crypto.c:331
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
**Symbols:**

```
c00000000072ebb0-c00000000072edd8: ima_calc_file_hash_tfm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ima_calc_file_hash_tfm(struct file *file, struct ima_digest_data *hash, struct crypto_shash *tfm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffe0003f7566)
Location: security/integrity/ima/ima_crypto.c:331
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
**Symbols:**

```
ffffffe0003f7566-ffffffe0003f766a: ima_calc_file_hash_tfm (STB_LOCAL)
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
int ima_calc_file_hash_tfm(struct file *file, struct ima_digest_data *hash, struct crypto_shash *tfm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff814af800)
Location: security/integrity/ima/ima_crypto.c:331
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
**Symbols:**

```
ffffffff814af800-ffffffff814af946: ima_calc_file_hash_tfm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ima_calc_file_hash_tfm(struct file *file, struct ima_digest_data *hash, struct crypto_shash *tfm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff814a0220)
Location: security/integrity/ima/ima_crypto.c:331
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
**Symbols:**

```
ffffffff814a0220-ffffffff814a0366: ima_calc_file_hash_tfm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ima_calc_file_hash_tfm(struct file *file, struct ima_digest_data *hash, struct crypto_shash *tfm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff814ab890)
Location: security/integrity/ima/ima_crypto.c:331
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
**Symbols:**

```
ffffffff814ab890-ffffffff814ab9d6: ima_calc_file_hash_tfm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ima_calc_file_hash_tfm(struct file *file, struct ima_digest_data *hash, struct crypto_shash *tfm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_crypto.c (ffffffff814c42e0)
Location: security/integrity/ima/ima_crypto.c:331
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
**Symbols:**

```
ffffffff814c42e0-ffffffff814c4426: ima_calc_file_hash_tfm (STB_LOCAL)
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
