# Function: <code>crypto_alloc_ahash</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct crypto_ahash *crypto_alloc_ahash(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff813a2fa0)
Location: crypto/ahash.c:538
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
**Symbols:**

```
ffffffff813a2fa0-ffffffff813a2fbb: crypto_alloc_ahash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct crypto_ahash *crypto_alloc_ahash(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff813df180)
Location: crypto/ahash.c:521
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_alloc_atfm
  - net/ipv4/tcp.c:tcp_alloc_md5sig_pool
```
**Symbols:**

```
ffffffff813df180-ffffffff813df19b: crypto_alloc_ahash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct crypto_ahash *crypto_alloc_ahash(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff813f7710)
Location: crypto/ahash.c:521
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_alloc_atfm
  - arch/x86/power/hibernate_64.c:get_e820_md5
  - net/ipv4/tcp.c:tcp_alloc_md5sig_pool
```
**Symbols:**

```
ffffffff813f7710-ffffffff813f772b: crypto_alloc_ahash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct crypto_ahash *crypto_alloc_ahash(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff81403d60)
Location: crypto/ahash.c:543
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_alloc_atfm
  - arch/x86/power/hibernate_64.c:get_e820_md5
  - net/ipv4/tcp.c:tcp_alloc_md5sig_pool
```
**Symbols:**

```
ffffffff81403d60-ffffffff81403d7b: crypto_alloc_ahash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct crypto_ahash *crypto_alloc_ahash(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff8142c4e0)
Location: crypto/ahash.c:550
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_alloc_atfm
  - arch/x86/power/hibernate_64.c:get_e820_md5
  - net/ipv4/tcp.c:tcp_alloc_md5sig_pool
```
**Symbols:**

```
ffffffff8142c4e0-ffffffff8142c4fb: crypto_alloc_ahash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct crypto_ahash *crypto_alloc_ahash(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff8145f190)
Location: crypto/ahash.c:536
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_alloc_atfm
  - arch/x86/power/hibernate_64.c:get_e820_md5
  - net/ipv4/tcp.c:tcp_alloc_md5sig_pool
```
**Symbols:**

```
ffffffff8145f190-ffffffff8145f1ab: crypto_alloc_ahash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct crypto_ahash *crypto_alloc_ahash(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff8147cb80)
Location: crypto/ahash.c:564
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_alloc_atfm
  - net/ipv4/tcp.c:tcp_alloc_md5sig_pool
```
**Symbols:**

```
ffffffff8147cb80-ffffffff8147cb9b: crypto_alloc_ahash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct crypto_ahash *crypto_alloc_ahash(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff814aab30)
Location: crypto/ahash.c:559
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_alloc_atfm
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
```
**Symbols:**

```
ffffffff814aab30-ffffffff814aab4b: crypto_alloc_ahash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct crypto_ahash *crypto_alloc_ahash(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff814c57f0)
Location: crypto/ahash.c:559
Inline: False
Direct callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - security/integrity/ima/ima_crypto.c:ima_alloc_atfm
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
```
**Symbols:**

```
ffffffff814c57f0-ffffffff814c580b: crypto_alloc_ahash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct crypto_ahash *crypto_alloc_ahash(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff81524900)
Location: crypto/ahash.c:577
Inline: False
Direct callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - security/integrity/ima/ima_crypto.c:ima_alloc_atfm
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
```
**Symbols:**

```
ffffffff81524900-ffffffff8152491b: crypto_alloc_ahash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct crypto_ahash *crypto_alloc_ahash(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff81541800)
Location: crypto/ahash.c:555
Inline: False
Direct callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - security/integrity/ima/ima_crypto.c:ima_alloc_atfm
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
```
**Symbols:**

```
ffffffff81541800-ffffffff81541821: crypto_alloc_ahash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct crypto_ahash *crypto_alloc_ahash(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff81549e30)
Location: crypto/ahash.c:555
Inline: False
Direct callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - security/integrity/ima/ima_crypto.c:ima_alloc_atfm
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
```
**Symbols:**

```
ffffffff81549e30-ffffffff81549e51: crypto_alloc_ahash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct crypto_ahash *crypto_alloc_ahash(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff815aa610)
Location: crypto/ahash.c:555
Inline: False
Direct callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - security/integrity/ima/ima_crypto.c:ima_alloc_atfm
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
```
**Symbols:**

```
ffffffff815aa610-ffffffff815aa631: crypto_alloc_ahash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct crypto_ahash *crypto_alloc_ahash(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff81651aa0)
Location: crypto/ahash.c:555
Inline: False
Direct callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - security/integrity/ima/ima_crypto.c:ima_alloc_atfm
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
```
**Symbols:**

```
ffffffff81651aa0-ffffffff81651ad0: crypto_alloc_ahash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct crypto_ahash *crypto_alloc_ahash(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff8170b060)
Location: crypto/ahash.c:555
Inline: False
Direct callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - security/integrity/ima/ima_crypto.c:ima_alloc_atfm
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
```
**Symbols:**

```
ffffffff8170b060-ffffffff8170b090: crypto_alloc_ahash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct crypto_ahash *crypto_alloc_ahash(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff81744770)
Location: crypto/ahash.c:529
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_alloc_atfm
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
```
**Symbols:**

```
ffffffff81744770-ffffffff817447a0: crypto_alloc_ahash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct crypto_ahash *crypto_alloc_ahash(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff81786cd0)
Location: crypto/ahash.c:608
Inline: False
Direct callers:
  - security/integrity/ima/ima_crypto.c:ima_alloc_atfm
  - net/ipv4/tcp_sigpool.c:tcp_sigpool_alloc_ahash
```
**Symbols:**

```
ffffffff81786cd0-ffffffff81786d00: crypto_alloc_ahash (STB_GLOBAL)
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
struct crypto_ahash *crypto_alloc_ahash(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffff8000105c0520)
Location: crypto/ahash.c:559
Inline: False
Direct callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - security/integrity/ima/ima_crypto.c:ima_alloc_atfm
  - net/ipv4/tcp.c:tcp_alloc_md5sig_pool
```
**Symbols:**

```
ffff8000105c0520-ffff8000105c056c: crypto_alloc_ahash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct crypto_ahash *crypto_alloc_ahash(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (c076e068)
Location: crypto/ahash.c:559
Inline: False
Direct callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - security/integrity/ima/ima_crypto.c:ima_alloc_atfm
  - net/ipv4/tcp.c:tcp_alloc_md5sig_pool
```
**Symbols:**

```
c076e068-c076e094: crypto_alloc_ahash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct crypto_ahash *crypto_alloc_ahash(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (c000000000748640)
Location: crypto/ahash.c:559
Inline: False
Direct callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - security/integrity/ima/ima_crypto.c:ima_alloc_atfm
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
```
**Symbols:**

```
c000000000748640-c000000000748688: crypto_alloc_ahash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct crypto_ahash *crypto_alloc_ahash(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffe000405466)
Location: crypto/ahash.c:559
Inline: False
Direct callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - security/integrity/ima/ima_crypto.c:ima_alloc_atfm
  - net/ipv4/tcp.c:tcp_alloc_md5sig_pool
```
**Symbols:**

```
ffffffe000405466-ffffffe0004054a8: crypto_alloc_ahash (STB_GLOBAL)
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
struct crypto_ahash *crypto_alloc_ahash(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff814bddd0)
Location: crypto/ahash.c:559
Inline: False
Direct callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - security/integrity/ima/ima_crypto.c:ima_alloc_atfm
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
```
**Symbols:**

```
ffffffff814bddd0-ffffffff814bddeb: crypto_alloc_ahash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct crypto_ahash *crypto_alloc_ahash(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff814ae7f0)
Location: crypto/ahash.c:559
Inline: False
Direct callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - security/integrity/ima/ima_crypto.c:ima_alloc_atfm
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
```
**Symbols:**

```
ffffffff814ae7f0-ffffffff814ae80b: crypto_alloc_ahash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct crypto_ahash *crypto_alloc_ahash(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff814b9e60)
Location: crypto/ahash.c:559
Inline: False
Direct callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - security/integrity/ima/ima_crypto.c:ima_alloc_atfm
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
```
**Symbols:**

```
ffffffff814b9e60-ffffffff814b9e7b: crypto_alloc_ahash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct crypto_ahash *crypto_alloc_ahash(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff814d2910)
Location: crypto/ahash.c:559
Inline: False
Direct callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - security/integrity/ima/ima_crypto.c:ima_alloc_atfm
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
```
**Symbols:**

```
ffffffff814d2910-ffffffff814d292b: crypto_alloc_ahash (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
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
