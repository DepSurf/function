# Function: <code>ahash_setkey_unaligned</code>

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
In crypto/ahash.c (ffffffff813a31e0)
Location: crypto/ahash.c:187
Inline: True
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
In crypto/ahash.c (ffffffff813df3e1)
Location: crypto/ahash.c:170
Inline: True
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
In crypto/ahash.c (ffffffff813f7971)
Location: crypto/ahash.c:170
Inline: True
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
In crypto/ahash.c (ffffffff814037b1)
Location: crypto/ahash.c:172
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_setkey
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
In crypto/ahash.c (ffffffff8142bf0f)
Location: crypto/ahash.c:173
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_setkey
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
In crypto/ahash.c (ffffffff8145ebff)
Location: crypto/ahash.c:173
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_setkey
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
In crypto/ahash.c (ffffffff8147c54f)
Location: crypto/ahash.c:173
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_setkey
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
In crypto/ahash.c (ffffffff814aae8f)
Location: crypto/ahash.c:168
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_setkey
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff814c5b4f)
Location: crypto/ahash.c:168
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_setkey
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ahash_setkey_unaligned(struct crypto_ahash *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff81524400)
Location: crypto/ahash.c:170
Inline: False
Direct callers:
  - crypto/ahash.c:crypto_ahash_setkey
```
**Symbols:**

```
ffffffff81524400-ffffffff81524494: ahash_setkey_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ahash_setkey_unaligned(struct crypto_ahash *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff815412d0)
Location: crypto/ahash.c:137
Inline: False
Direct callers:
  - crypto/ahash.c:crypto_ahash_setkey
```
**Symbols:**

```
ffffffff815412d0-ffffffff81541364: ahash_setkey_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ahash_setkey_unaligned(struct crypto_ahash *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff81549900)
Location: crypto/ahash.c:137
Inline: False
Direct callers:
  - crypto/ahash.c:crypto_ahash_setkey
```
**Symbols:**

```
ffffffff81549900-ffffffff81549995: ahash_setkey_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ahash_setkey_unaligned(struct crypto_ahash *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff815aa0e0)
Location: crypto/ahash.c:137
Inline: False
Direct callers:
  - crypto/ahash.c:crypto_ahash_setkey
```
**Symbols:**

```
ffffffff815aa0e0-ffffffff815aa175: ahash_setkey_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ahash_setkey_unaligned(struct crypto_ahash *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff81651560)
Location: crypto/ahash.c:137
Inline: False
Direct callers:
  - crypto/ahash.c:crypto_ahash_setkey
```
**Symbols:**

```
ffffffff81651560-ffffffff81651603: ahash_setkey_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ahash_setkey_unaligned(struct crypto_ahash *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff8170b220)
Location: crypto/ahash.c:137
Inline: False
Direct callers:
  - crypto/ahash.c:crypto_ahash_setkey
```
**Symbols:**

```
ffffffff8170b220-ffffffff8170b2c3: ahash_setkey_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ahash_setkey_unaligned(struct crypto_ahash *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff817448b0)
Location: crypto/ahash.c:130
Inline: False
Direct callers:
  - crypto/ahash.c:crypto_ahash_setkey
```
**Symbols:**

```
ffffffff817448b0-ffffffff81744953: ahash_setkey_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffff8000105c0d4c)
Location: crypto/ahash.c:168
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_setkey
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (c076e430)
Location: crypto/ahash.c:168
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_setkey
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (c000000000748c00)
Location: crypto/ahash.c:168
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_setkey
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffe000405ba8)
Location: crypto/ahash.c:168
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_setkey
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff814be12f)
Location: crypto/ahash.c:168
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_setkey
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff814aeb4f)
Location: crypto/ahash.c:168
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_setkey
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff814ba1bf)
Location: crypto/ahash.c:168
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_setkey
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff814d2c6f)
Location: crypto/ahash.c:168
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_setkey
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
