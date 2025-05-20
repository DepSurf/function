# Function: <code>init_crypt</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int init_crypt(struct skcipher_request *req, crypto_completion_t done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff81401110)
Location: crypto/xts.c:216
Inline: False
Direct callers:
  - crypto/xts.c:decrypt
  - crypto/xts.c:encrypt
```
**Symbols:**

```
ffffffff81401110-ffffffff814011db: init_crypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int init_crypt(struct skcipher_request *req, crypto_completion_t done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff8140e4a0)
Location: crypto/xts.c:216
Inline: False
Direct callers:
  - crypto/xts.c:decrypt
  - crypto/xts.c:encrypt
```
**Symbols:**

```
ffffffff8140e4a0-ffffffff8140e575: init_crypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int init_crypt(struct skcipher_request *req, crypto_completion_t done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff81436f60)
Location: crypto/xts.c:216
Inline: False
Direct callers:
  - crypto/xts.c:decrypt
  - crypto/xts.c:encrypt
```
**Symbols:**

```
ffffffff81436f60-ffffffff81437038: init_crypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int init_crypt(struct skcipher_request *req, crypto_completion_t done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff81469890)
Location: crypto/xts.c:216
Inline: False
Direct callers:
  - crypto/xts.c:decrypt
  - crypto/xts.c:encrypt
```
**Symbols:**

```
ffffffff81469890-ffffffff81469968: init_crypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff81487835)
Location: crypto/xts.c:146
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff814b5515)
Location: crypto/xts.c:146
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int init_crypt(struct skcipher_request *req, crypto_completion_t compl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff814ce070)
Location: crypto/xts.c:241
Inline: False
```
**Symbols:**

```
ffffffff814ce070-ffffffff814ce0f2: init_crypt (STB_LOCAL)
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
In crypto/xts.c (ffffffff8152d8b5)
Location: crypto/xts.c:235
Inline: True
Inline callers:
  - crypto/xts.c:decrypt
  - crypto/xts.c:encrypt
```
</details>
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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int init_crypt(struct skcipher_request *req, crypto_completion_t compl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffff8000105c9f90)
Location: crypto/xts.c:241
Inline: False
```
**Symbols:**

```
ffff8000105c9f90-ffff8000105ca014: init_crypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int init_crypt(struct skcipher_request *req, crypto_completion_t compl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/xts.c (c0777a98)
Location: crypto/xts.c:241
Inline: False
```
**Symbols:**

```
c0777a98-c0777b1c: init_crypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int init_crypt(struct skcipher_request *req, crypto_completion_t compl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/xts.c (c000000000754930)
Location: crypto/xts.c:241
Inline: False
```
**Symbols:**

```
c000000000754930-c0000000007549d8: init_crypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int init_crypt(struct skcipher_request *req, crypto_completion_t compl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffe00040e5d0)
Location: crypto/xts.c:241
Inline: False
```
**Symbols:**

```
ffffffe00040e5d0-ffffffe00040e636: init_crypt (STB_LOCAL)
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
int init_crypt(struct skcipher_request *req, crypto_completion_t compl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff814c6650)
Location: crypto/xts.c:241
Inline: False
```
**Symbols:**

```
ffffffff814c6650-ffffffff814c66d2: init_crypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int init_crypt(struct skcipher_request *req, crypto_completion_t compl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff814b7070)
Location: crypto/xts.c:241
Inline: False
```
**Symbols:**

```
ffffffff814b7070-ffffffff814b70f2: init_crypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int init_crypt(struct skcipher_request *req, crypto_completion_t compl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff814c26e0)
Location: crypto/xts.c:241
Inline: False
```
**Symbols:**

```
ffffffff814c26e0-ffffffff814c2762: init_crypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int init_crypt(struct skcipher_request *req, crypto_completion_t compl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff814db1b0)
Location: crypto/xts.c:241
Inline: False
```
**Symbols:**

```
ffffffff814db1b0-ffffffff814db232: init_crypt (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
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
