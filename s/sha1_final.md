# Function: <code>sha1_final</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int sha1_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/sha1_generic.c (ffffffff813a589d)
Location: crypto/sha1_generic.c:48
Inline: True
Inline callers:
  - crypto/sha1_generic.c:crypto_sha1_finup
```
**Symbols:**

```
ffffffff813a5c30-ffffffff813a5d88: sha1_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int sha1_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/sha1_generic.c (ffffffff813e3010)
Location: crypto/sha1_generic.c:55
Inline: False
Direct callers:
  - crypto/sha1_generic.c:crypto_sha1_finup
```
**Symbols:**

```
ffffffff813e3010-ffffffff813e3156: sha1_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int sha1_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/sha1_generic.c (ffffffff813fc030)
Location: crypto/sha1_generic.c:55
Inline: False
Direct callers:
  - crypto/sha1_generic.c:crypto_sha1_finup
```
**Symbols:**

```
ffffffff813fc030-ffffffff813fc176: sha1_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sha1_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/sha1_generic.c (ffffffff81409310)
Location: crypto/sha1_generic.c:55
Inline: False
Direct callers:
  - crypto/sha1_generic.c:crypto_sha1_finup
```
**Symbols:**

```
ffffffff81409310-ffffffff8140944f: sha1_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sha1_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/sha1_generic.c (ffffffff81431d30)
Location: crypto/sha1_generic.c:55
Inline: False
Direct callers:
  - crypto/sha1_generic.c:crypto_sha1_finup
```
**Symbols:**

```
ffffffff81431d30-ffffffff81431e6f: sha1_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int sha1_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/sha1_generic.c (ffffffff81464890)
Location: crypto/sha1_generic.c:55
Inline: False
Direct callers:
  - crypto/sha1_generic.c:crypto_sha1_finup
```
**Symbols:**

```
ffffffff81464890-ffffffff814649de: sha1_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sha1_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/sha1_generic.c (ffffffff81482500)
Location: crypto/sha1_generic.c:55
Inline: False
Direct callers:
  - crypto/sha1_generic.c:crypto_sha1_finup
```
**Symbols:**

```
ffffffff81482500-ffffffff8148264e: sha1_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sha1_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/sha1_generic.c (ffffffff814b0740)
Location: crypto/sha1_generic.c:50
Inline: False
Direct callers:
  - crypto/sha1_generic.c:crypto_sha1_finup
```
**Symbols:**

```
ffffffff814b0740-ffffffff814b088d: sha1_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sha1_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/sha1_generic.c (ffffffff814cb3b0)
Location: crypto/sha1_generic.c:50
Inline: False
Direct callers:
  - crypto/sha1_generic.c:crypto_sha1_finup
```
**Symbols:**

```
ffffffff814cb3b0-ffffffff814cb4fd: sha1_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sha1_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/sha1_generic.c (ffffffff8152a6c0)
Location: crypto/sha1_generic.c:49
Inline: False
Direct callers:
  - crypto/sha1_generic.c:crypto_sha1_finup
```
**Symbols:**

```
ffffffff8152a6c0-ffffffff8152a860: sha1_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sha1_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/sha1_generic.c (ffffffff81547670)
Location: crypto/sha1_generic.c:49
Inline: False
Direct callers:
  - crypto/sha1_generic.c:crypto_sha1_finup
```
**Symbols:**

```
ffffffff81547670-ffffffff8154782f: sha1_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sha1_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/sha1_generic.c (ffffffff8154fd30)
Location: crypto/sha1_generic.c:49
Inline: False
Direct callers:
  - crypto/sha1_generic.c:crypto_sha1_finup
```
**Symbols:**

```
ffffffff8154fd30-ffffffff8154feed: sha1_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sha1_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/sha1_generic.c (ffffffff815b0680)
Location: crypto/sha1_generic.c:49
Inline: False
Direct callers:
  - crypto/sha1_generic.c:crypto_sha1_finup
```
**Symbols:**

```
ffffffff815b0680-ffffffff815b0862: sha1_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sha1_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/sha1_generic.c (ffffffff81658fe0)
Location: crypto/sha1_generic.c:49
Inline: False
Direct callers:
  - crypto/sha1_generic.c:crypto_sha1_finup
```
**Symbols:**

```
ffffffff81658fe0-ffffffff816591e4: sha1_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sha1_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/sha1_generic.c (ffffffff81713460)
Location: crypto/sha1_generic.c:49
Inline: False
Direct callers:
  - crypto/sha1_generic.c:crypto_sha1_finup
```
**Symbols:**

```
ffffffff81713460-ffffffff81713664: sha1_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int sha1_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/sha1_generic.c (ffffffff8174e662)
Location: crypto/sha1_generic.c:49
Inline: True
Inline callers:
  - crypto/sha1_generic.c:crypto_sha1_finup
```
**Symbols:**

```
ffffffff8174e330-ffffffff8174e3bb: sha1_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int sha1_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/sha1_generic.c (ffffffff817902b2)
Location: crypto/sha1_generic.c:49
Inline: True
Inline callers:
  - crypto/sha1_generic.c:crypto_sha1_finup
```
**Symbols:**

```
ffffffff8178ff80-ffffffff8179000b: sha1_final (STB_LOCAL)
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
int sha1_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/sha1_generic.c (ffff8000105c732c)
Location: crypto/sha1_generic.c:50
Inline: True
Inline callers:
  - crypto/sha1_generic.c:crypto_sha1_finup
```
**Symbols:**

```
ffff8000105c75a0-ffff8000105c76e0: sha1_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sha1_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/sha1_generic.c (c0773edc)
Location: crypto/sha1_generic.c:50
Inline: False
Direct callers:
  - crypto/sha1_generic.c:crypto_sha1_finup
```
**Symbols:**

```
c0773edc-c0773fd0: sha1_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sha1_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/sha1_generic.c (c000000000750eb0)
Location: crypto/sha1_generic.c:50
Inline: False
Direct callers:
  - crypto/sha1_generic.c:crypto_sha1_finup
```
**Symbols:**

```
c000000000750eb0-c000000000751000: sha1_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sha1_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/sha1_generic.c (ffffffe00040b370)
Location: crypto/sha1_generic.c:50
Inline: False
Direct callers:
  - crypto/sha1_generic.c:crypto_sha1_finup
```
**Symbols:**

```
ffffffe00040b370-ffffffe00040b4dc: sha1_final (STB_LOCAL)
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
int sha1_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/sha1_generic.c (ffffffff814c3990)
Location: crypto/sha1_generic.c:50
Inline: False
Direct callers:
  - crypto/sha1_generic.c:crypto_sha1_finup
```
**Symbols:**

```
ffffffff814c3990-ffffffff814c3add: sha1_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sha1_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/sha1_generic.c (ffffffff814b43b0)
Location: crypto/sha1_generic.c:50
Inline: False
Direct callers:
  - crypto/sha1_generic.c:crypto_sha1_finup
```
**Symbols:**

```
ffffffff814b43b0-ffffffff814b44fd: sha1_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sha1_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/sha1_generic.c (ffffffff814bfa20)
Location: crypto/sha1_generic.c:50
Inline: False
Direct callers:
  - crypto/sha1_generic.c:crypto_sha1_finup
```
**Symbols:**

```
ffffffff814bfa20-ffffffff814bfb6d: sha1_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sha1_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/sha1_generic.c (ffffffff814d84f0)
Location: crypto/sha1_generic.c:50
Inline: False
Direct callers:
  - crypto/sha1_generic.c:crypto_sha1_finup
```
**Symbols:**

```
ffffffff814d84f0-ffffffff814d863d: sha1_final (STB_LOCAL)
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
