# Function: <code>crypto_cbc_setkey</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int crypto_cbc_setkey(struct crypto_tfm *parent, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (ffffffff813a91a0)
Location: crypto/cbc.c:26
Inline: False
```
**Symbols:**

```
ffffffff813a91a0-ffffffff813a91df: crypto_cbc_setkey (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int crypto_cbc_setkey(struct crypto_tfm *parent, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (ffffffff813e7160)
Location: crypto/cbc.c:26
Inline: False
```
**Symbols:**

```
ffffffff813e7160-ffffffff813e719f: crypto_cbc_setkey (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int crypto_cbc_setkey(struct crypto_skcipher *parent, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (ffffffff813fff10)
Location: crypto/cbc.c:26
Inline: False
```
**Symbols:**

```
ffffffff813fff10-ffffffff813fff51: crypto_cbc_setkey (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int crypto_cbc_setkey(struct crypto_skcipher *parent, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (ffffffff8140d220)
Location: crypto/cbc.c:27
Inline: False
```
**Symbols:**

```
ffffffff8140d220-ffffffff8140d261: crypto_cbc_setkey (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int crypto_cbc_setkey(struct crypto_skcipher *parent, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (ffffffff81435c90)
Location: crypto/cbc.c:27
Inline: False
```
**Symbols:**

```
ffffffff81435c90-ffffffff81435cd7: crypto_cbc_setkey (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int crypto_cbc_setkey(struct crypto_skcipher *parent, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (ffffffff81468820)
Location: crypto/cbc.c:27
Inline: False
```
**Symbols:**

```
ffffffff81468820-ffffffff81468867: crypto_cbc_setkey (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int crypto_cbc_setkey(struct crypto_skcipher *parent, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (ffffffff81486490)
Location: crypto/cbc.c:27
Inline: False
```
**Symbols:**

```
ffffffff81486490-ffffffff814864d7: crypto_cbc_setkey (STB_LOCAL)
```
</details>
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct crypto_tfm *parent</code> ➡️ <code>struct crypto_skcipher *parent</code>
</li>
</ul>
</details>
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
</ul>
