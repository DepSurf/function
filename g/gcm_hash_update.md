# Function: <code>gcm_hash_update</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff814389d9)
Location: crypto/gcm.c:224
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash_init_continue
  - crypto/gcm.c:gcm_hash_assoc_continue
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
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
In crypto/gcm.c (ffffffff8146b931)
Location: crypto/gcm.c:224
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash_init_continue
  - crypto/gcm.c:gcm_hash_assoc_continue
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int gcm_hash_update(struct aead_request *req, crypto_completion_t compl, struct scatterlist *src, unsigned int len, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff814887c0)
Location: crypto/gcm.c:224
Inline: False
Direct callers:
  - crypto/gcm.c:gcm_hash_init_continue
  - crypto/gcm.c:gcm_hash_assoc_continue
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
```
**Symbols:**

```
ffffffff814887c0-ffffffff81488856: gcm_hash_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int gcm_hash_update(struct aead_request *req, crypto_completion_t compl, struct scatterlist *src, unsigned int len, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff814b67e0)
Location: crypto/gcm.c:221
Inline: False
Direct callers:
  - crypto/gcm.c:gcm_hash_init_continue
  - crypto/gcm.c:gcm_hash_assoc_continue
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
```
**Symbols:**

```
ffffffff814b67e0-ffffffff814b687c: gcm_hash_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int gcm_hash_update(struct aead_request *req, crypto_completion_t compl, struct scatterlist *src, unsigned int len, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff814cfa00)
Location: crypto/gcm.c:208
Inline: False
Direct callers:
  - crypto/gcm.c:gcm_hash_init_continue
  - crypto/gcm.c:gcm_hash_assoc_continue
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
```
**Symbols:**

```
ffffffff814cfa00-ffffffff814cfa9c: gcm_hash_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int gcm_hash_update(struct aead_request *req, crypto_completion_t compl, struct scatterlist *src, unsigned int len, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff8152ebd0)
Location: crypto/gcm.c:202
Inline: False
Direct callers:
  - crypto/gcm.c:gcm_hash_init_continue
  - crypto/gcm.c:gcm_hash_assoc_continue
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
```
**Symbols:**

```
ffffffff8152ebd0-ffffffff8152ec6c: gcm_hash_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int gcm_hash_update(struct aead_request *req, crypto_completion_t compl, struct scatterlist *src, unsigned int len, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff8154bb50)
Location: crypto/gcm.c:202
Inline: False
Direct callers:
  - crypto/gcm.c:gcm_hash_init_continue
  - crypto/gcm.c:gcm_hash_assoc_continue
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
```
**Symbols:**

```
ffffffff8154bb50-ffffffff8154bbec: gcm_hash_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int gcm_hash_update(struct aead_request *req, crypto_completion_t compl, struct scatterlist *src, unsigned int len, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff81554150)
Location: crypto/gcm.c:202
Inline: False
Direct callers:
  - crypto/gcm.c:gcm_hash_init_continue
  - crypto/gcm.c:gcm_hash_assoc_continue
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
```
**Symbols:**

```
ffffffff81554150-ffffffff815541ef: gcm_hash_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int gcm_hash_update(struct aead_request *req, crypto_completion_t compl, struct scatterlist *src, unsigned int len, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff815b5180)
Location: crypto/gcm.c:202
Inline: False
Direct callers:
  - crypto/gcm.c:gcm_hash_init_continue
  - crypto/gcm.c:gcm_hash_assoc_continue
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
```
**Symbols:**

```
ffffffff815b5180-ffffffff815b521f: gcm_hash_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int gcm_hash_update(struct aead_request *req, crypto_completion_t compl, struct scatterlist *src, unsigned int len, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff8165e230)
Location: crypto/gcm.c:202
Inline: False
Direct callers:
  - crypto/gcm.c:gcm_hash_init_continue
  - crypto/gcm.c:gcm_hash_assoc_continue
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
```
**Symbols:**

```
ffffffff8165e230-ffffffff8165e2de: gcm_hash_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int gcm_hash_update(struct aead_request *req, crypto_completion_t compl, struct scatterlist *src, unsigned int len, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff81717bd0)
Location: crypto/gcm.c:202
Inline: False
Direct callers:
  - crypto/gcm.c:gcm_hash_init_continue
  - crypto/gcm.c:gcm_hash_assoc_continue
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
```
**Symbols:**

```
ffffffff81717bd0-ffffffff81717c7e: gcm_hash_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int gcm_hash_update(struct aead_request *req, crypto_completion_t compl, struct scatterlist *src, unsigned int len, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff81753040)
Location: crypto/gcm.c:202
Inline: False
Direct callers:
  - crypto/gcm.c:gcm_hash_init_continue
  - crypto/gcm.c:gcm_hash_assoc_continue
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
```
**Symbols:**

```
ffffffff81753040-ffffffff817530fa: gcm_hash_update (STB_LOCAL)
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
In crypto/gcm.c (ffffffff81796a37)
Location: crypto/gcm.c:202
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash_init_continue
  - crypto/gcm.c:gcm_hash_assoc_continue
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
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
int gcm_hash_update(struct aead_request *req, crypto_completion_t compl, struct scatterlist *src, unsigned int len, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffff8000105cc3d0)
Location: crypto/gcm.c:208
Inline: False
Direct callers:
  - crypto/gcm.c:gcm_hash_init_continue
  - crypto/gcm.c:gcm_hash_assoc_continue
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
```
**Symbols:**

```
ffff8000105cc3d0-ffff8000105cc478: gcm_hash_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int gcm_hash_update(struct aead_request *req, crypto_completion_t compl, struct scatterlist *src, unsigned int len, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (c0779d0c)
Location: crypto/gcm.c:208
Inline: False
Direct callers:
  - crypto/gcm.c:gcm_hash_init_continue
  - crypto/gcm.c:gcm_hash_assoc_continue
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
```
**Symbols:**

```
c0779d0c-c0779d98: gcm_hash_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int gcm_hash_update(struct aead_request *req, crypto_completion_t compl, struct scatterlist *src, unsigned int len, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (c000000000756df0)
Location: crypto/gcm.c:208
Inline: False
Direct callers:
  - crypto/gcm.c:gcm_hash_init_continue
  - crypto/gcm.c:gcm_hash_assoc_continue
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
```
**Symbols:**

```
c000000000756df0-c000000000756eb4: gcm_hash_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int gcm_hash_update(struct aead_request *req, crypto_completion_t compl, struct scatterlist *src, unsigned int len, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffe0004104f2)
Location: crypto/gcm.c:208
Inline: False
Direct callers:
  - crypto/gcm.c:gcm_hash_init_continue
  - crypto/gcm.c:gcm_hash_assoc_continue
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
```
**Symbols:**

```
ffffffe0004104f2-ffffffe00041058e: gcm_hash_update (STB_LOCAL)
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
int gcm_hash_update(struct aead_request *req, crypto_completion_t compl, struct scatterlist *src, unsigned int len, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff814c7fe0)
Location: crypto/gcm.c:208
Inline: False
Direct callers:
  - crypto/gcm.c:gcm_hash_init_continue
  - crypto/gcm.c:gcm_hash_assoc_continue
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
```
**Symbols:**

```
ffffffff814c7fe0-ffffffff814c807c: gcm_hash_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int gcm_hash_update(struct aead_request *req, crypto_completion_t compl, struct scatterlist *src, unsigned int len, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff814b8a00)
Location: crypto/gcm.c:208
Inline: False
Direct callers:
  - crypto/gcm.c:gcm_hash_init_continue
  - crypto/gcm.c:gcm_hash_assoc_continue
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
```
**Symbols:**

```
ffffffff814b8a00-ffffffff814b8a9c: gcm_hash_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int gcm_hash_update(struct aead_request *req, crypto_completion_t compl, struct scatterlist *src, unsigned int len, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff814c4070)
Location: crypto/gcm.c:208
Inline: False
Direct callers:
  - crypto/gcm.c:gcm_hash_init_continue
  - crypto/gcm.c:gcm_hash_assoc_continue
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
```
**Symbols:**

```
ffffffff814c4070-ffffffff814c410c: gcm_hash_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int gcm_hash_update(struct aead_request *req, crypto_completion_t compl, struct scatterlist *src, unsigned int len, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff814dcb40)
Location: crypto/gcm.c:208
Inline: False
Direct callers:
  - crypto/gcm.c:gcm_hash_init_continue
  - crypto/gcm.c:gcm_hash_assoc_continue
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
```
**Symbols:**

```
ffffffff814dcb40-ffffffff814dcbdc: gcm_hash_update (STB_LOCAL)
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
