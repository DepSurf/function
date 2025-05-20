# Function: <code>skcipher_setkey_unaligned</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff8140204a)
Location: crypto/skcipher.c:767
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey
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
In crypto/skcipher.c (ffffffff8142a6b7)
Location: crypto/skcipher.c:773
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey
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
In crypto/skcipher.c (ffffffff8145d400)
Location: crypto/skcipher.c:786
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey
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
In crypto/skcipher.c (ffffffff8147ac80)
Location: crypto/skcipher.c:793
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey
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
In crypto/skcipher.c (ffffffff814a9c10)
Location: crypto/skcipher.c:793
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey
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
In crypto/skcipher.c (ffffffff814c4900)
Location: crypto/skcipher.c:797
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int skcipher_setkey_unaligned(struct crypto_skcipher *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81522860)
Location: crypto/skcipher.c:578
Inline: False
Direct callers:
  - crypto/skcipher.c:crypto_skcipher_setkey
```
**Symbols:**

```
ffffffff81522860-ffffffff815228fa: skcipher_setkey_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int skcipher_setkey_unaligned(struct crypto_skcipher *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff8153f720)
Location: crypto/skcipher.c:578
Inline: False
Direct callers:
  - crypto/skcipher.c:crypto_skcipher_setkey
```
**Symbols:**

```
ffffffff8153f720-ffffffff8153f7ba: skcipher_setkey_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int skcipher_setkey_unaligned(struct crypto_skcipher *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81547cb0)
Location: crypto/skcipher.c:573
Inline: False
Direct callers:
  - crypto/skcipher.c:crypto_skcipher_setkey
```
**Symbols:**

```
ffffffff81547cb0-ffffffff81547d4b: skcipher_setkey_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int skcipher_setkey_unaligned(struct crypto_skcipher *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff815a8490)
Location: crypto/skcipher.c:573
Inline: False
Direct callers:
  - crypto/skcipher.c:crypto_skcipher_setkey
```
**Symbols:**

```
ffffffff815a8490-ffffffff815a852b: skcipher_setkey_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int skcipher_setkey_unaligned(struct crypto_skcipher *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff8164f860)
Location: crypto/skcipher.c:573
Inline: False
Direct callers:
  - crypto/skcipher.c:crypto_skcipher_setkey
```
**Symbols:**

```
ffffffff8164f860-ffffffff8164f905: skcipher_setkey_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int skcipher_setkey_unaligned(struct crypto_skcipher *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81709510)
Location: crypto/skcipher.c:573
Inline: False
Direct callers:
  - crypto/skcipher.c:crypto_skcipher_setkey
```
**Symbols:**

```
ffffffff81709510-ffffffff817095b5: skcipher_setkey_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int skcipher_setkey_unaligned(struct crypto_skcipher *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81742d50)
Location: crypto/skcipher.c:591
Inline: False
Direct callers:
  - crypto/skcipher.c:crypto_skcipher_setkey
```
**Symbols:**

```
ffffffff81742d50-ffffffff81742df5: skcipher_setkey_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int skcipher_setkey_unaligned(struct crypto_skcipher *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81785020)
Location: crypto/skcipher.c:595
Inline: False
Direct callers:
  - crypto/skcipher.c:crypto_skcipher_setkey
```
**Symbols:**

```
ffffffff81785020-ffffffff817850c5: skcipher_setkey_unaligned (STB_LOCAL)
```
</details>
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
In crypto/skcipher.c (ffff8000105bec30)
Location: crypto/skcipher.c:797
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey
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
In crypto/skcipher.c (c076d094)
Location: crypto/skcipher.c:797
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey
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
In crypto/skcipher.c (c000000000746fc0)
Location: crypto/skcipher.c:797
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey
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
In crypto/skcipher.c (ffffffe000403df8)
Location: crypto/skcipher.c:797
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey
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
In crypto/skcipher.c (ffffffff814bcee0)
Location: crypto/skcipher.c:797
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey
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
In crypto/skcipher.c (ffffffff814ad900)
Location: crypto/skcipher.c:797
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey
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
In crypto/skcipher.c (ffffffff814b8f70)
Location: crypto/skcipher.c:797
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey
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
In crypto/skcipher.c (ffffffff814d1a30)
Location: crypto/skcipher.c:797
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey
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
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
