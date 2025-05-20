# Function: <code>sha512_final</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int sha512_final(struct shash_desc *desc, u8 *hash);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/sha512_generic.c (ffffffff813a8848)
Location: crypto/sha512_generic.c:150
Inline: True
Inline callers:
  - crypto/sha512_generic.c:crypto_sha512_finup
```
**Symbols:**

```
ffffffff813a8c60-ffffffff813a8e4c: sha512_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int sha512_final(struct shash_desc *desc, u8 *hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/sha512_generic.c (ffffffff813e5cc0)
Location: crypto/sha512_generic.c:150
Inline: False
Direct callers:
  - crypto/sha512_generic.c:crypto_sha512_finup
```
**Symbols:**

```
ffffffff813e5cc0-ffffffff813e5e77: sha512_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int sha512_final(struct shash_desc *desc, u8 *hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/sha512_generic.c (ffffffff813fece0)
Location: crypto/sha512_generic.c:150
Inline: False
Direct callers:
  - crypto/sha512_generic.c:crypto_sha512_finup
```
**Symbols:**

```
ffffffff813fece0-ffffffff813fee97: sha512_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sha512_final(struct shash_desc *desc, u8 *hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/sha512_generic.c (ffffffff8140c000)
Location: crypto/sha512_generic.c:150
Inline: False
Direct callers:
  - crypto/sha512_generic.c:crypto_sha512_finup
```
**Symbols:**

```
ffffffff8140c000-ffffffff8140c1a6: sha512_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sha512_final(struct shash_desc *desc, u8 *hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/sha512_generic.c (ffffffff81434a20)
Location: crypto/sha512_generic.c:150
Inline: False
Direct callers:
  - crypto/sha512_generic.c:crypto_sha512_finup
```
**Symbols:**

```
ffffffff81434a20-ffffffff81434bc6: sha512_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int sha512_final(struct shash_desc *desc, u8 *hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/sha512_generic.c (ffffffff814675a0)
Location: crypto/sha512_generic.c:150
Inline: False
Direct callers:
  - crypto/sha512_generic.c:crypto_sha512_finup
```
**Symbols:**

```
ffffffff814675a0-ffffffff81467766: sha512_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sha512_final(struct shash_desc *desc, u8 *hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/sha512_generic.c (ffffffff81485210)
Location: crypto/sha512_generic.c:172
Inline: False
Direct callers:
  - crypto/sha512_generic.c:crypto_sha512_finup
```
**Symbols:**

```
ffffffff81485210-ffffffff814853d6: sha512_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sha512_final(struct shash_desc *desc, u8 *hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/sha512_generic.c (ffffffff814b3420)
Location: crypto/sha512_generic.c:167
Inline: False
Direct callers:
  - crypto/sha512_generic.c:crypto_sha512_finup
```
**Symbols:**

```
ffffffff814b3420-ffffffff814b35ec: sha512_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sha512_final(struct shash_desc *desc, u8 *hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/sha512_generic.c (ffffffff814cc190)
Location: crypto/sha512_generic.c:167
Inline: False
Direct callers:
  - crypto/sha512_generic.c:crypto_sha512_finup
```
**Symbols:**

```
ffffffff814cc190-ffffffff814cc35c: sha512_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sha512_final(struct shash_desc *desc, u8 *hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/sha512_generic.c (ffffffff8152b5e0)
Location: crypto/sha512_generic.c:167
Inline: False
Direct callers:
  - crypto/sha512_generic.c:crypto_sha512_finup
```
**Symbols:**

```
ffffffff8152b5e0-ffffffff8152b7a2: sha512_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sha512_final(struct shash_desc *desc, u8 *hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/sha512_generic.c (ffffffff815485b0)
Location: crypto/sha512_generic.c:167
Inline: False
Direct callers:
  - crypto/sha512_generic.c:crypto_sha512_finup
```
**Symbols:**

```
ffffffff815485b0-ffffffff81548794: sha512_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sha512_final(struct shash_desc *desc, u8 *hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/sha512_generic.c (ffffffff81550c80)
Location: crypto/sha512_generic.c:167
Inline: False
Direct callers:
  - crypto/sha512_generic.c:crypto_sha512_finup
```
**Symbols:**

```
ffffffff81550c80-ffffffff81550e60: sha512_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sha512_final(struct shash_desc *desc, u8 *hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/sha512_generic.c (ffffffff815b1c30)
Location: crypto/sha512_generic.c:164
Inline: False
Direct callers:
  - crypto/sha512_generic.c:crypto_sha512_finup
```
**Symbols:**

```
ffffffff815b1c30-ffffffff815b1e5b: sha512_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sha512_final(struct shash_desc *desc, u8 *hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/sha512_generic.c (ffffffff8165a760)
Location: crypto/sha512_generic.c:164
Inline: False
Direct callers:
  - crypto/sha512_generic.c:crypto_sha512_finup
```
**Symbols:**

```
ffffffff8165a760-ffffffff8165a99a: sha512_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sha512_final(struct shash_desc *desc, u8 *hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/sha512_generic.c (ffffffff81714ad0)
Location: crypto/sha512_generic.c:164
Inline: False
Direct callers:
  - crypto/sha512_generic.c:crypto_sha512_finup
```
**Symbols:**

```
ffffffff81714ad0-ffffffff81714d14: sha512_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sha512_final(struct shash_desc *desc, u8 *hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/sha512_generic.c (ffffffff8174fa90)
Location: crypto/sha512_generic.c:164
Inline: False
Direct callers:
  - crypto/sha512_generic.c:crypto_sha512_finup
```
**Symbols:**

```
ffffffff8174fa90-ffffffff8174fb49: sha512_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sha512_final(struct shash_desc *desc, u8 *hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/sha512_generic.c (ffffffff817916e0)
Location: crypto/sha512_generic.c:164
Inline: False
Direct callers:
  - crypto/sha512_generic.c:crypto_sha512_finup
```
**Symbols:**

```
ffffffff817916e0-ffffffff81791799: sha512_final (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int sha512_final(struct shash_desc *desc, u8 *hash);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/sha512_generic.c (ffff8000105c810c)
Location: crypto/sha512_generic.c:167
Inline: True
Inline callers:
  - crypto/sha512_generic.c:crypto_sha512_finup
```
**Symbols:**

```
ffff8000105c82d8-ffff8000105c8444: sha512_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int sha512_final(struct shash_desc *desc, u8 *hash);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/sha512_generic.c (c0775714)
Location: crypto/sha512_generic.c:167
Inline: True
Inline callers:
  - crypto/sha512_generic.c:crypto_sha512_finup
```
**Symbols:**

```
c07758a8-c0775a00: sha512_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sha512_final(struct shash_desc *desc, u8 *hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/sha512_generic.c (c000000000751e70)
Location: crypto/sha512_generic.c:167
Inline: False
Direct callers:
  - crypto/sha512_generic.c:crypto_sha512_finup
```
**Symbols:**

```
c000000000751e70-c000000000752010: sha512_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int sha512_final(struct shash_desc *desc, u8 *hash);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/sha512_generic.c (ffffffe00040c106)
Location: crypto/sha512_generic.c:167
Inline: True
Inline callers:
  - crypto/sha512_generic.c:crypto_sha512_finup
```
**Symbols:**

```
ffffffe00040c446-ffffffe00040c63c: sha512_final (STB_LOCAL)
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
int sha512_final(struct shash_desc *desc, u8 *hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/sha512_generic.c (ffffffff814c4770)
Location: crypto/sha512_generic.c:167
Inline: False
Direct callers:
  - crypto/sha512_generic.c:crypto_sha512_finup
```
**Symbols:**

```
ffffffff814c4770-ffffffff814c493c: sha512_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sha512_final(struct shash_desc *desc, u8 *hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/sha512_generic.c (ffffffff814b5190)
Location: crypto/sha512_generic.c:167
Inline: False
Direct callers:
  - crypto/sha512_generic.c:crypto_sha512_finup
```
**Symbols:**

```
ffffffff814b5190-ffffffff814b535c: sha512_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sha512_final(struct shash_desc *desc, u8 *hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/sha512_generic.c (ffffffff814c0800)
Location: crypto/sha512_generic.c:167
Inline: False
Direct callers:
  - crypto/sha512_generic.c:crypto_sha512_finup
```
**Symbols:**

```
ffffffff814c0800-ffffffff814c09cc: sha512_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sha512_final(struct shash_desc *desc, u8 *hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/sha512_generic.c (ffffffff814d92d0)
Location: crypto/sha512_generic.c:167
Inline: False
Direct callers:
  - crypto/sha512_generic.c:crypto_sha512_finup
```
**Symbols:**

```
ffffffff814d92d0-ffffffff814d949c: sha512_final (STB_LOCAL)
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
