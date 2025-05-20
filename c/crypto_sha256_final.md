# Function: <code>crypto_sha256_final</code>

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
<summary>In <code>5.4</code>: ✅</summary>

```c
int crypto_sha256_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/sha256_generic.c (ffffffff814cb870)
Location: crypto/sha256_generic.c:53
Inline: False
Direct callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
```
**Symbols:**

```
ffffffff814cb870-ffffffff814cb89b: crypto_sha256_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int crypto_sha256_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/sha256_generic.c (ffffffff8152ad30)
Location: crypto/sha256_generic.c:56
Inline: True
Inline callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
```
**Symbols:**

```
ffffffff8152ace0-ffffffff8152ad0f: crypto_sha256_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int crypto_sha256_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/sha256_generic.c (ffffffff81547d00)
Location: crypto/sha256_generic.c:56
Inline: True
Inline callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
```
**Symbols:**

```
ffffffff81547cb0-ffffffff81547cdf: crypto_sha256_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int crypto_sha256_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/sha256_generic.c (ffffffff815503c0)
Location: crypto/sha256_generic.c:56
Inline: True
Inline callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
```
**Symbols:**

```
ffffffff81550370-ffffffff8155039f: crypto_sha256_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int crypto_sha256_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/sha256_generic.c (ffffffff815b0d40)
Location: crypto/sha256_generic.c:56
Inline: True
Inline callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
```
**Symbols:**

```
ffffffff815b0cf0-ffffffff815b0d1f: crypto_sha256_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int crypto_sha256_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/sha256_generic.c (ffffffff81659760)
Location: crypto/sha256_generic.c:44
Inline: True
Inline callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
```
**Symbols:**

```
ffffffff816596f0-ffffffff81659733: crypto_sha256_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int crypto_sha256_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/sha256_generic.c (ffffffff81713a80)
Location: crypto/sha256_generic.c:44
Inline: True
Inline callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
```
**Symbols:**

```
ffffffff81713a00-ffffffff81713a43: crypto_sha256_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int crypto_sha256_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/sha256_generic.c (ffffffff8174e880)
Location: crypto/sha256_generic.c:44
Inline: True
Inline callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
```
**Symbols:**

```
ffffffff8174e810-ffffffff8174e84c: crypto_sha256_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int crypto_sha256_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/sha256_generic.c (ffffffff817904d0)
Location: crypto/sha256_generic.c:44
Inline: True
Inline callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
```
**Symbols:**

```
ffffffff81790460-ffffffff8179049c: crypto_sha256_final (STB_LOCAL)
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
int crypto_sha256_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/sha256_generic.c (ffff8000105c7818)
Location: crypto/sha256_generic.c:53
Inline: False
Direct callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
```
**Symbols:**

```
ffff8000105c7818-ffff8000105c7870: crypto_sha256_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int crypto_sha256_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/sha256_generic.c (c07742a4)
Location: crypto/sha256_generic.c:53
Inline: False
Direct callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
```
**Symbols:**

```
c07742a4-c07742dc: crypto_sha256_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int crypto_sha256_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/sha256_generic.c (c000000000751410)
Location: crypto/sha256_generic.c:53
Inline: False
Direct callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
```
**Symbols:**

```
c000000000751410-c000000000751478: crypto_sha256_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int crypto_sha256_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/sha256_generic.c (ffffffe00040b78c)
Location: crypto/sha256_generic.c:53
Inline: False
Direct callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
```
**Symbols:**

```
ffffffe00040b78c-ffffffe00040b7e2: crypto_sha256_final (STB_LOCAL)
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
int crypto_sha256_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/sha256_generic.c (ffffffff814c3e50)
Location: crypto/sha256_generic.c:53
Inline: False
Direct callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
```
**Symbols:**

```
ffffffff814c3e50-ffffffff814c3e7b: crypto_sha256_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int crypto_sha256_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/sha256_generic.c (ffffffff814b4870)
Location: crypto/sha256_generic.c:53
Inline: False
Direct callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
```
**Symbols:**

```
ffffffff814b4870-ffffffff814b489b: crypto_sha256_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int crypto_sha256_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/sha256_generic.c (ffffffff814bfee0)
Location: crypto/sha256_generic.c:53
Inline: False
Direct callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
```
**Symbols:**

```
ffffffff814bfee0-ffffffff814bff0b: crypto_sha256_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int crypto_sha256_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/sha256_generic.c (ffffffff814d89b0)
Location: crypto/sha256_generic.c:53
Inline: False
Direct callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
```
**Symbols:**

```
ffffffff814d89b0-ffffffff814d89db: crypto_sha256_final (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
