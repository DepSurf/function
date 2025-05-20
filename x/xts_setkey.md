# Function: <code>xts_setkey</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int xts_setkey(struct crypto_skcipher *parent, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff8154ab30)
Location: crypto/xts.c:40
Inline: True
```
**Symbols:**

```
ffffffff8154ab30-ffffffff8154abe2: xts_setkey (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int xts_setkey(struct crypto_skcipher *parent, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff81553150)
Location: crypto/xts.c:41
Inline: True
```
**Symbols:**

```
ffffffff81553150-ffffffff81553202: xts_setkey (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int xts_setkey(struct crypto_skcipher *parent, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff815b4180)
Location: crypto/xts.c:41
Inline: True
```
**Symbols:**

```
ffffffff815b4180-ffffffff815b4232: xts_setkey (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int xts_setkey(struct crypto_skcipher *parent, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff8165cfe0)
Location: crypto/xts.c:41
Inline: True
```
**Symbols:**

```
ffffffff8165cfe0-ffffffff8165d0b1: xts_setkey (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int xts_setkey(struct crypto_skcipher *parent, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff81716ac0)
Location: crypto/xts.c:41
Inline: True
```
**Symbols:**

```
ffffffff81716ac0-ffffffff81716b91: xts_setkey (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int xts_setkey(struct crypto_skcipher *parent, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff81752370)
Location: crypto/xts.c:41
Inline: True
```
**Symbols:**

```
ffffffff81752370-ffffffff81752444: xts_setkey (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int xts_setkey(struct crypto_skcipher *parent, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff81794200)
Location: crypto/xts.c:41
Inline: True
```
**Symbols:**

```
ffffffff81794200-ffffffff817942d4: xts_setkey (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
