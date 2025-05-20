# Function: <code>cts_cbc_encrypt</code>

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
int cts_cbc_encrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cts.c (ffffffff813e7b00)
Location: crypto/cts.c:100
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt_done
```
**Symbols:**

```
ffffffff813e7b00-ffffffff813e7c4f: cts_cbc_encrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int cts_cbc_encrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cts.c (ffffffff81400930)
Location: crypto/cts.c:100
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt_done
```
**Symbols:**

```
ffffffff81400930-ffffffff81400a7f: cts_cbc_encrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int cts_cbc_encrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cts.c (ffffffff8140d8d0)
Location: crypto/cts.c:101
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt_done
```
**Symbols:**

```
ffffffff8140d8d0-ffffffff8140da22: cts_cbc_encrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int cts_cbc_encrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cts.c (ffffffff81436370)
Location: crypto/cts.c:101
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt_done
```
**Symbols:**

```
ffffffff81436370-ffffffff814364c8: cts_cbc_encrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int cts_cbc_encrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/cts.c (0)
Location: crypto/cts.c:102
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt_done
```
**Symbols:**

```
ffffffff81468ec0-ffffffff8146901d: cts_cbc_encrypt (STB_LOCAL)
ffffffff81469878-ffffffff81469884: cts_cbc_encrypt.cold.3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int cts_cbc_encrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/cts.c (0)
Location: crypto/cts.c:102
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt_done
```
**Symbols:**

```
ffffffff81486e50-ffffffff81486fcf: cts_cbc_encrypt (STB_LOCAL)
ffffffff814875cc-ffffffff814875d8: cts_cbc_encrypt.cold.3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int cts_cbc_encrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/cts.c (0)
Location: crypto/cts.c:102
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt_done
```
**Symbols:**

```
ffffffff814b49c0-ffffffff814b4b05: cts_cbc_encrypt (STB_LOCAL)
ffffffff814b52c8-ffffffff814b52d4: cts_cbc_encrypt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int cts_cbc_encrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/cts.c (0)
Location: crypto/cts.c:102
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt_done
```
**Symbols:**

```
ffffffff814cda10-ffffffff814cdb68: cts_cbc_encrypt (STB_LOCAL)
ffffffff814ce058-ffffffff814ce064: cts_cbc_encrypt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int cts_cbc_encrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/cts.c (0)
Location: crypto/cts.c:98
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt_done
```
**Symbols:**

```
ffffffff8152cdc0-ffffffff8152cf18: cts_cbc_encrypt (STB_LOCAL)
ffffffff8152d40b-ffffffff8152d417: cts_cbc_encrypt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int cts_cbc_encrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/cts.c (0)
Location: crypto/cts.c:98
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt_done
```
**Symbols:**

```
ffffffff81549e30-ffffffff81549f88: cts_cbc_encrypt (STB_LOCAL)
ffffffff81bf20df-ffffffff81bf20eb: cts_cbc_encrypt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int cts_cbc_encrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/cts.c (0)
Location: crypto/cts.c:98
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt_done
```
**Symbols:**

```
ffffffff81552470-ffffffff815525c8: cts_cbc_encrypt (STB_LOCAL)
ffffffff81be40a3-ffffffff81be40af: cts_cbc_encrypt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int cts_cbc_encrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/cts.c (0)
Location: crypto/cts.c:98
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt_done
```
**Symbols:**

```
ffffffff815b3470-ffffffff815b35c8: cts_cbc_encrypt (STB_LOCAL)
ffffffff81cd77c2-ffffffff81cd77ce: cts_cbc_encrypt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int cts_cbc_encrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/cts.c (0)
Location: crypto/cts.c:98
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt_done
```
**Symbols:**

```
ffffffff8165be60-ffffffff8165bff9: cts_cbc_encrypt (STB_LOCAL)
ffffffff81e8aa7c-ffffffff81e8aa88: cts_cbc_encrypt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cts_cbc_encrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cts.c (ffffffff817157c0)
Location: crypto/cts.c:98
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt_done
```
**Symbols:**

```
ffffffff817157c0-ffffffff81715965: cts_cbc_encrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cts_cbc_encrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cts.c (ffffffff81751070)
Location: crypto/cts.c:98
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt_done
```
**Symbols:**

```
ffffffff81751070-ffffffff81751215: cts_cbc_encrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cts_cbc_encrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cts.c (ffffffff81792ec0)
Location: crypto/cts.c:98
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt_done
```
**Symbols:**

```
ffffffff81792ec0-ffffffff81793065: cts_cbc_encrypt (STB_LOCAL)
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
int cts_cbc_encrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cts.c (ffff8000105c9960)
Location: crypto/cts.c:102
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt_done
```
**Symbols:**

```
ffff8000105c9960-ffff8000105c9aa8: cts_cbc_encrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cts_cbc_encrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cts.c (c07774c8)
Location: crypto/cts.c:102
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt_done
```
**Symbols:**

```
c07774c8-c0777610: cts_cbc_encrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cts_cbc_encrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cts.c (c0000000007540e0)
Location: crypto/cts.c:102
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt_done
```
**Symbols:**

```
c0000000007540e0-c000000000754298: cts_cbc_encrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cts_cbc_encrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cts.c (ffffffe00040e0d6)
Location: crypto/cts.c:102
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt_done
```
**Symbols:**

```
ffffffe00040e0d6-ffffffe00040e1ca: cts_cbc_encrypt (STB_LOCAL)
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
int cts_cbc_encrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/cts.c (0)
Location: crypto/cts.c:102
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt_done
```
**Symbols:**

```
ffffffff814c5ff0-ffffffff814c6148: cts_cbc_encrypt (STB_LOCAL)
ffffffff814c6638-ffffffff814c6644: cts_cbc_encrypt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int cts_cbc_encrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/cts.c (0)
Location: crypto/cts.c:102
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt_done
```
**Symbols:**

```
ffffffff814b6a10-ffffffff814b6b68: cts_cbc_encrypt (STB_LOCAL)
ffffffff814b7058-ffffffff814b7064: cts_cbc_encrypt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int cts_cbc_encrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/cts.c (0)
Location: crypto/cts.c:102
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt_done
```
**Symbols:**

```
ffffffff814c2080-ffffffff814c21d8: cts_cbc_encrypt (STB_LOCAL)
ffffffff814c26c8-ffffffff814c26d4: cts_cbc_encrypt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int cts_cbc_encrypt(struct skcipher_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/cts.c (0)
Location: crypto/cts.c:102
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt_done
```
**Symbols:**

```
ffffffff814dab50-ffffffff814daca8: cts_cbc_encrypt (STB_LOCAL)
ffffffff814db198-ffffffff814db1a4: cts_cbc_encrypt.cold (STB_LOCAL)
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
