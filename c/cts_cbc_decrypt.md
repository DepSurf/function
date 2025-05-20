# Function: <code>cts_cbc_decrypt</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int cts_cbc_decrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cts.c (ffffffff813e77a0)
Location: crypto/cts.c:180
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt_done
```
**Symbols:**

```
ffffffff813e77a0-ffffffff813e7959: cts_cbc_decrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int cts_cbc_decrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cts.c (ffffffff814005d0)
Location: crypto/cts.c:180
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt_done
```
**Symbols:**

```
ffffffff814005d0-ffffffff81400789: cts_cbc_decrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int cts_cbc_decrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cts.c (ffffffff8140dea0)
Location: crypto/cts.c:181
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt_done
```
**Symbols:**

```
ffffffff8140dea0-ffffffff8140e05e: cts_cbc_decrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int cts_cbc_decrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cts.c (ffffffff81436940)
Location: crypto/cts.c:180
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt_done
```
**Symbols:**

```
ffffffff81436940-ffffffff81436b0c: cts_cbc_decrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int cts_cbc_decrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/cts.c (0)
Location: crypto/cts.c:181
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt_done
```
**Symbols:**

```
ffffffff814694d0-ffffffff814696a2: cts_cbc_decrypt (STB_LOCAL)
ffffffff81469884-ffffffff81469890: cts_cbc_decrypt.cold.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int cts_cbc_decrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/cts.c (0)
Location: crypto/cts.c:181
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt_done
```
**Symbols:**

```
ffffffff814871b0-ffffffff8148739f: cts_cbc_decrypt (STB_LOCAL)
ffffffff814875d8-ffffffff814875e4: cts_cbc_decrypt.cold.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int cts_cbc_decrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/cts.c (0)
Location: crypto/cts.c:183
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt_done
```
**Symbols:**

```
ffffffff814b4f40-ffffffff814b5112: cts_cbc_decrypt (STB_LOCAL)
ffffffff814b52d4-ffffffff814b52e0: cts_cbc_decrypt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int cts_cbc_decrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/cts.c (0)
Location: crypto/cts.c:183
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt_done
```
**Symbols:**

```
ffffffff814cdcc0-ffffffff814cdea3: cts_cbc_decrypt (STB_LOCAL)
ffffffff814ce064-ffffffff814ce070: cts_cbc_decrypt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int cts_cbc_decrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/cts.c (0)
Location: crypto/cts.c:179
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt_done
```
**Symbols:**

```
ffffffff8152d070-ffffffff8152d252: cts_cbc_decrypt (STB_LOCAL)
ffffffff8152d417-ffffffff8152d423: cts_cbc_decrypt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int cts_cbc_decrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/cts.c (0)
Location: crypto/cts.c:179
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt_done
```
**Symbols:**

```
ffffffff8154a0e0-ffffffff8154a2c2: cts_cbc_decrypt (STB_LOCAL)
ffffffff81bf20eb-ffffffff81bf20f7: cts_cbc_decrypt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int cts_cbc_decrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/cts.c (0)
Location: crypto/cts.c:179
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt_done
```
**Symbols:**

```
ffffffff81552720-ffffffff815528ff: cts_cbc_decrypt (STB_LOCAL)
ffffffff81be40af-ffffffff81be40bb: cts_cbc_decrypt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int cts_cbc_decrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/cts.c (0)
Location: crypto/cts.c:179
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt_done
```
**Symbols:**

```
ffffffff815b3720-ffffffff815b3902: cts_cbc_decrypt (STB_LOCAL)
ffffffff81cd77ce-ffffffff81cd77da: cts_cbc_decrypt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int cts_cbc_decrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/cts.c (0)
Location: crypto/cts.c:179
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt_done
```
**Symbols:**

```
ffffffff8165c480-ffffffff8165c67f: cts_cbc_decrypt (STB_LOCAL)
ffffffff81e8aa88-ffffffff81e8aa94: cts_cbc_decrypt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cts_cbc_decrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cts.c (ffffffff81715e70)
Location: crypto/cts.c:179
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt_done
```
**Symbols:**

```
ffffffff81715e70-ffffffff8171607b: cts_cbc_decrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cts_cbc_decrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cts.c (ffffffff81751730)
Location: crypto/cts.c:179
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt_done
```
**Symbols:**

```
ffffffff81751730-ffffffff8175197b: cts_cbc_decrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cts_cbc_decrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cts.c (ffffffff817935b0)
Location: crypto/cts.c:179
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt_done
```
**Symbols:**

```
ffffffff817935b0-ffffffff817937fb: cts_cbc_decrypt (STB_LOCAL)
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
int cts_cbc_decrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cts.c (ffff8000105c9bf0)
Location: crypto/cts.c:183
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt_done
```
**Symbols:**

```
ffff8000105c9bf0-ffff8000105c9db4: cts_cbc_decrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cts_cbc_decrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cts.c (c077773c)
Location: crypto/cts.c:183
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt_done
```
**Symbols:**

```
c077773c-c07778f0: cts_cbc_decrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cts_cbc_decrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cts.c (c000000000754450)
Location: crypto/cts.c:183
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt_done
```
**Symbols:**

```
c000000000754450-c0000000007546a4: cts_cbc_decrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cts_cbc_decrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cts.c (ffffffe00040de00)
Location: crypto/cts.c:183
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt_done
```
**Symbols:**

```
ffffffe00040de00-ffffffe00040df5c: cts_cbc_decrypt (STB_LOCAL)
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
int cts_cbc_decrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/cts.c (0)
Location: crypto/cts.c:183
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt_done
```
**Symbols:**

```
ffffffff814c62a0-ffffffff814c6483: cts_cbc_decrypt (STB_LOCAL)
ffffffff814c6644-ffffffff814c6650: cts_cbc_decrypt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int cts_cbc_decrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/cts.c (0)
Location: crypto/cts.c:183
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt_done
```
**Symbols:**

```
ffffffff814b6cc0-ffffffff814b6ea3: cts_cbc_decrypt (STB_LOCAL)
ffffffff814b7064-ffffffff814b7070: cts_cbc_decrypt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int cts_cbc_decrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/cts.c (0)
Location: crypto/cts.c:183
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt_done
```
**Symbols:**

```
ffffffff814c2330-ffffffff814c2513: cts_cbc_decrypt (STB_LOCAL)
ffffffff814c26d4-ffffffff814c26e0: cts_cbc_decrypt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int cts_cbc_decrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/cts.c (0)
Location: crypto/cts.c:183
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt_done
```
**Symbols:**

```
ffffffff814dae00-ffffffff814dafe3: cts_cbc_decrypt (STB_LOCAL)
ffffffff814db1a4-ffffffff814db1b0: cts_cbc_decrypt.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
