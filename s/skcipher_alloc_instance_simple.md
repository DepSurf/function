# Function: <code>skcipher_alloc_instance_simple</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct skcipher_instance *skcipher_alloc_instance_simple(struct crypto_template *tmpl, struct rtattr **tb, struct crypto_alg **cipher_alg_ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814a9260)
Location: crypto/skcipher.c:1166
Inline: False
Direct callers:
  - crypto/ecb.c:crypto_ecb_create
  - crypto/cbc.c:crypto_cbc_create
  - crypto/ctr.c:crypto_ctr_create
```
**Symbols:**

```
ffffffff814a9260-ffffffff814a93e1: skcipher_alloc_instance_simple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct skcipher_instance *skcipher_alloc_instance_simple(struct crypto_template *tmpl, struct rtattr **tb, struct crypto_alg **cipher_alg_ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814c3ed0)
Location: crypto/skcipher.c:1170
Inline: False
Direct callers:
  - crypto/ecb.c:crypto_ecb_create
  - crypto/cbc.c:crypto_cbc_create
  - crypto/ctr.c:crypto_ctr_create
```
**Symbols:**

```
ffffffff814c3ed0-ffffffff814c4051: skcipher_alloc_instance_simple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct skcipher_instance *skcipher_alloc_instance_simple(struct crypto_template *tmpl, struct rtattr **tb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81522fa0)
Location: crypto/skcipher.c:934
Inline: False
Direct callers:
  - crypto/ecb.c:crypto_ecb_create
  - crypto/cbc.c:crypto_cbc_create
  - crypto/ctr.c:crypto_ctr_create
```
**Symbols:**

```
ffffffff81522fa0-ffffffff81523117: skcipher_alloc_instance_simple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct skcipher_instance *skcipher_alloc_instance_simple(struct crypto_template *tmpl, struct rtattr **tb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff8153fef0)
Location: crypto/skcipher.c:934
Inline: False
Direct callers:
  - crypto/ecb.c:crypto_ecb_create
  - crypto/cbc.c:crypto_cbc_create
  - crypto/ctr.c:crypto_ctr_create
```
**Symbols:**

```
ffffffff8153fef0-ffffffff8154006b: skcipher_alloc_instance_simple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct skcipher_instance *skcipher_alloc_instance_simple(struct crypto_template *tmpl, struct rtattr **tb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff815484b0)
Location: crypto/skcipher.c:929
Inline: False
Direct callers:
  - crypto/ecb.c:crypto_ecb_create
  - crypto/cbc.c:crypto_cbc_create
  - crypto/ctr.c:crypto_ctr_create
```
**Symbols:**

```
ffffffff815484b0-ffffffff8154862b: skcipher_alloc_instance_simple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct skcipher_instance *skcipher_alloc_instance_simple(struct crypto_template *tmpl, struct rtattr **tb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff815a8c90)
Location: crypto/skcipher.c:929
Inline: False
Direct callers:
  - crypto/ecb.c:crypto_ecb_create
  - crypto/cbc.c:crypto_cbc_create
  - crypto/ctr.c:crypto_ctr_create
```
**Symbols:**

```
ffffffff815a8c90-ffffffff815a8e0b: skcipher_alloc_instance_simple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct skcipher_instance *skcipher_alloc_instance_simple(struct crypto_template *tmpl, struct rtattr **tb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81650150)
Location: crypto/skcipher.c:929
Inline: False
Direct callers:
  - crypto/ecb.c:crypto_ecb_create
  - crypto/cbc.c:crypto_cbc_create
  - crypto/ctr.c:crypto_ctr_create
```
**Symbols:**

```
ffffffff81650150-ffffffff816502cf: skcipher_alloc_instance_simple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct skcipher_instance *skcipher_alloc_instance_simple(struct crypto_template *tmpl, struct rtattr **tb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff817098c0)
Location: crypto/skcipher.c:929
Inline: False
Direct callers:
  - crypto/ecb.c:crypto_ecb_create
  - crypto/cbc.c:crypto_cbc_create
  - crypto/ctr.c:crypto_ctr_create
```
**Symbols:**

```
ffffffff817098c0-ffffffff81709a3f: skcipher_alloc_instance_simple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct skcipher_instance *skcipher_alloc_instance_simple(struct crypto_template *tmpl, struct rtattr **tb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81743190)
Location: crypto/skcipher.c:980
Inline: False
Direct callers:
  - crypto/ecb.c:crypto_ecb_create
  - crypto/cbc.c:crypto_cbc_create
  - crypto/ctr.c:crypto_ctr_create
```
**Symbols:**

```
ffffffff81743190-ffffffff8174331f: skcipher_alloc_instance_simple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct skcipher_instance *skcipher_alloc_instance_simple(struct crypto_template *tmpl, struct rtattr **tb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81785450)
Location: crypto/skcipher.c:1103
Inline: False
Direct callers:
  - crypto/ctr.c:crypto_ctr_create
```
**Symbols:**

```
ffffffff81785450-ffffffff81785611: skcipher_alloc_instance_simple (STB_GLOBAL)
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
struct skcipher_instance *skcipher_alloc_instance_simple(struct crypto_template *tmpl, struct rtattr **tb, struct crypto_alg **cipher_alg_ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffff8000105be9d8)
Location: crypto/skcipher.c:1170
Inline: False
Direct callers:
  - crypto/ecb.c:crypto_ecb_create
  - crypto/cbc.c:crypto_cbc_create
  - crypto/ctr.c:crypto_ctr_create
```
**Symbols:**

```
ffff8000105be9d8-ffff8000105beb7c: skcipher_alloc_instance_simple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct skcipher_instance *skcipher_alloc_instance_simple(struct crypto_template *tmpl, struct rtattr **tb, struct crypto_alg **cipher_alg_ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (c076c62c)
Location: crypto/skcipher.c:1170
Inline: False
Direct callers:
  - crypto/ecb.c:crypto_ecb_create
  - crypto/cbc.c:crypto_cbc_create
  - crypto/ctr.c:crypto_ctr_create
```
**Symbols:**

```
c076c62c-c076c79c: skcipher_alloc_instance_simple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct skcipher_instance *skcipher_alloc_instance_simple(struct crypto_template *tmpl, struct rtattr **tb, struct crypto_alg **cipher_alg_ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (c000000000746ce0)
Location: crypto/skcipher.c:1170
Inline: False
Direct callers:
  - crypto/ecb.c:crypto_ecb_create
  - crypto/cbc.c:crypto_cbc_create
  - crypto/ctr.c:crypto_ctr_create
```
**Symbols:**

```
c000000000746ce0-c000000000746ef8: skcipher_alloc_instance_simple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct skcipher_instance *skcipher_alloc_instance_simple(struct crypto_template *tmpl, struct rtattr **tb, struct crypto_alg **cipher_alg_ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffe000403e68)
Location: crypto/skcipher.c:1170
Inline: False
Direct callers:
  - crypto/ecb.c:crypto_ecb_create
  - crypto/cbc.c:crypto_cbc_create
  - crypto/ctr.c:crypto_ctr_create
```
**Symbols:**

```
ffffffe000403e68-ffffffe000403fa4: skcipher_alloc_instance_simple (STB_GLOBAL)
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
struct skcipher_instance *skcipher_alloc_instance_simple(struct crypto_template *tmpl, struct rtattr **tb, struct crypto_alg **cipher_alg_ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814bc4b0)
Location: crypto/skcipher.c:1170
Inline: False
Direct callers:
  - crypto/ecb.c:crypto_ecb_create
  - crypto/cbc.c:crypto_cbc_create
  - crypto/ctr.c:crypto_ctr_create
```
**Symbols:**

```
ffffffff814bc4b0-ffffffff814bc631: skcipher_alloc_instance_simple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct skcipher_instance *skcipher_alloc_instance_simple(struct crypto_template *tmpl, struct rtattr **tb, struct crypto_alg **cipher_alg_ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814aced0)
Location: crypto/skcipher.c:1170
Inline: False
Direct callers:
  - crypto/ecb.c:crypto_ecb_create
  - crypto/cbc.c:crypto_cbc_create
  - crypto/ctr.c:crypto_ctr_create
```
**Symbols:**

```
ffffffff814aced0-ffffffff814ad051: skcipher_alloc_instance_simple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct skcipher_instance *skcipher_alloc_instance_simple(struct crypto_template *tmpl, struct rtattr **tb, struct crypto_alg **cipher_alg_ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814b8540)
Location: crypto/skcipher.c:1170
Inline: False
Direct callers:
  - crypto/ecb.c:crypto_ecb_create
  - crypto/cbc.c:crypto_cbc_create
  - crypto/ctr.c:crypto_ctr_create
```
**Symbols:**

```
ffffffff814b8540-ffffffff814b86c1: skcipher_alloc_instance_simple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct skcipher_instance *skcipher_alloc_instance_simple(struct crypto_template *tmpl, struct rtattr **tb, struct crypto_alg **cipher_alg_ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814d1020)
Location: crypto/skcipher.c:1170
Inline: False
Direct callers:
  - crypto/ecb.c:crypto_ecb_create
  - crypto/cbc.c:crypto_cbc_create
  - crypto/ctr.c:crypto_ctr_create
```
**Symbols:**

```
ffffffff814d1020-ffffffff814d11a1: skcipher_alloc_instance_simple (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct crypto_alg **cipher_alg_ret</code>
</li>
</ul>
</details>
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
