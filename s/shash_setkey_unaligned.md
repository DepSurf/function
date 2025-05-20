# Function: <code>shash_setkey_unaligned</code>

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
In crypto/shash.c (ffffffff813a35a4)
Location: crypto/shash.c:33
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_setkey
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
In crypto/shash.c (ffffffff813df724)
Location: crypto/shash.c:33
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_setkey
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
In crypto/shash.c (ffffffff813f7cb4)
Location: crypto/shash.c:33
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_setkey
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
In crypto/shash.c (ffffffff81404171)
Location: crypto/shash.c:34
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_setkey
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
In crypto/shash.c (ffffffff8142ca3f)
Location: crypto/shash.c:35
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_setkey
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
In crypto/shash.c (ffffffff8145f69f)
Location: crypto/shash.c:35
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_setkey
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
In crypto/shash.c (ffffffff8147d0cf)
Location: crypto/shash.c:35
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_setkey
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
In crypto/shash.c (ffffffff814ab3cf)
Location: crypto/shash.c:30
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_setkey
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
In crypto/shash.c (ffffffff814c608f)
Location: crypto/shash.c:30
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_setkey
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int shash_setkey_unaligned(struct crypto_shash *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff81524f70)
Location: crypto/shash.c:30
Inline: False
Direct callers:
  - crypto/shash.c:shash_async_setkey
```
**Symbols:**

```
ffffffff81524f70-ffffffff8152500f: shash_setkey_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int shash_setkey_unaligned(struct crypto_shash *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff81541e60)
Location: crypto/shash.c:30
Inline: False
Direct callers:
  - crypto/shash.c:shash_async_setkey
```
**Symbols:**

```
ffffffff81541e60-ffffffff81541eff: shash_setkey_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int shash_setkey_unaligned(struct crypto_shash *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff8154a500)
Location: crypto/shash.c:42
Inline: False
Direct callers:
  - crypto/shash.c:shash_async_setkey
```
**Symbols:**

```
ffffffff8154a500-ffffffff8154a5a0: shash_setkey_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int shash_setkey_unaligned(struct crypto_shash *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff815aace0)
Location: crypto/shash.c:42
Inline: False
Direct callers:
  - crypto/shash.c:shash_async_setkey
```
**Symbols:**

```
ffffffff815aace0-ffffffff815aad80: shash_setkey_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int shash_setkey_unaligned(struct crypto_shash *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff81652410)
Location: crypto/shash.c:42
Inline: False
Direct callers:
  - crypto/shash.c:shash_async_setkey
```
**Symbols:**

```
ffffffff81652410-ffffffff816524b1: shash_setkey_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int shash_setkey_unaligned(struct crypto_shash *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff8170c2b0)
Location: crypto/shash.c:32
Inline: False
Direct callers:
  - crypto/shash.c:shash_async_setkey
```
**Symbols:**

```
ffffffff8170c2b0-ffffffff8170c351: shash_setkey_unaligned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int shash_setkey_unaligned(struct crypto_shash *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff81745c00)
Location: crypto/shash.c:41
Inline: False
Direct callers:
  - crypto/shash.c:shash_async_setkey
```
**Symbols:**

```
ffffffff81745c00-ffffffff81745ca1: shash_setkey_unaligned (STB_LOCAL)
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
In crypto/shash.c (ffff8000105c1164)
Location: crypto/shash.c:30
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_setkey
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
In crypto/shash.c (c076ea14)
Location: crypto/shash.c:30
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_setkey
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
In crypto/shash.c (c0000000007494f0)
Location: crypto/shash.c:30
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_setkey
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
In crypto/shash.c (ffffffe000405f48)
Location: crypto/shash.c:30
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_setkey
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
In crypto/shash.c (ffffffff814be66f)
Location: crypto/shash.c:30
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_setkey
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
In crypto/shash.c (ffffffff814af08f)
Location: crypto/shash.c:30
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_setkey
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
In crypto/shash.c (ffffffff814ba6ff)
Location: crypto/shash.c:30
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_setkey
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
In crypto/shash.c (ffffffff814d31af)
Location: crypto/shash.c:30
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_setkey
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
