# Function: <code>setkey</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Selective Inline ⚠️</summary>

```c
int setkey(struct crypto_tfm *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/cipher.c (ffffffff8139ce20)
Location: crypto/cipher.c:46
Inline: False
```
```
In crypto/ablkcipher.c (ffffffff813a02b0)
Location: crypto/ablkcipher.c:329
Inline: False
```
```
In crypto/blkcipher.c (ffffffff813a0bb0)
Location: crypto/blkcipher.c:397
Inline: False
Direct callers:
  - crypto/blkcipher.c:async_setkey
```
```
In lib/btree.c (ffffffff81403e7b)
Location: lib/btree.c:158
Inline: True
Inline callers:
  - lib/btree.c:btree_remove_level
  - lib/btree.c:merge
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
```
**Symbols:**

```
ffffffff8139ce20-ffffffff8139cf1a: setkey (STB_LOCAL)
ffffffff813a02b0-ffffffff813a039a: setkey (STB_LOCAL)
ffffffff813a0bb0-ffffffff813a0c9a: setkey (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline ⚠️</summary>

```c
int setkey(struct crypto_tfm *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/cipher.c (ffffffff813d9cf0)
Location: crypto/cipher.c:46
Inline: False
```
```
In crypto/ablkcipher.c (ffffffff813dc9c0)
Location: crypto/ablkcipher.c:326
Inline: False
```
```
In crypto/blkcipher.c (ffffffff813dd430)
Location: crypto/blkcipher.c:397
Inline: False
Direct callers:
  - crypto/blkcipher.c:async_setkey
```
```
In crypto/xts.c (ffffffff813e80b0)
Location: crypto/xts.c:33
Inline: False
```
```
In lib/btree.c (ffffffff8144bb70)
Location: lib/btree.c:158
Inline: True
Inline callers:
  - lib/btree.c:btree_remove_level
  - lib/btree.c:merge
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
```
**Symbols:**

```
ffffffff813d9cf0-ffffffff813d9ddf: setkey (STB_LOCAL)
ffffffff813dc9c0-ffffffff813dcaa2: setkey (STB_LOCAL)
ffffffff813dd430-ffffffff813dd512: setkey (STB_LOCAL)
ffffffff813e80b0-ffffffff813e815b: setkey (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Selective Inline ⚠️</summary>

```c
int setkey(struct crypto_tfm *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/cipher.c (ffffffff813f1650)
Location: crypto/cipher.c:46
Inline: False
```
```
In crypto/ablkcipher.c (ffffffff813f42a0)
Location: crypto/ablkcipher.c:326
Inline: False
```
```
In crypto/blkcipher.c (ffffffff813f4d00)
Location: crypto/blkcipher.c:397
Inline: False
Direct callers:
  - crypto/blkcipher.c:async_setkey
```
```
In crypto/xts.c (ffffffff814012d0)
Location: crypto/xts.c:58
Inline: True
```
```
In lib/btree.c (ffffffff8146a530)
Location: lib/btree.c:158
Inline: True
Inline callers:
  - lib/btree.c:btree_remove_level
  - lib/btree.c:merge
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
```
**Symbols:**

```
ffffffff813f1650-ffffffff813f173f: setkey (STB_LOCAL)
ffffffff813f42a0-ffffffff813f4382: setkey (STB_LOCAL)
ffffffff813f4d00-ffffffff813f4de2: setkey (STB_LOCAL)
ffffffff814012d0-ffffffff814013b6: setkey (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline ⚠️</summary>

```c
int setkey(struct crypto_tfm *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/cipher.c (ffffffff813fd8d0)
Location: crypto/cipher.c:46
Inline: False
```
```
In crypto/ablkcipher.c (ffffffff81400600)
Location: crypto/ablkcipher.c:327
Inline: False
```
```
In crypto/blkcipher.c (ffffffff81401030)
Location: crypto/blkcipher.c:398
Inline: False
Direct callers:
  - crypto/blkcipher.c:async_setkey
```
```
In crypto/xts.c (ffffffff8140e580)
Location: crypto/xts.c:58
Inline: False
```
```
In lib/btree.c (ffffffff8146fbfe)
Location: lib/btree.c:158
Inline: True
Inline callers:
  - lib/btree.c:btree_remove_level
  - lib/btree.c:merge
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
```
**Symbols:**

```
ffffffff813fd8d0-ffffffff813fd9bf: setkey (STB_LOCAL)
ffffffff81400600-ffffffff814006df: setkey (STB_LOCAL)
ffffffff81401030-ffffffff8140110f: setkey (STB_LOCAL)
ffffffff8140e580-ffffffff8140e66b: setkey (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
int setkey(struct crypto_tfm *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/cipher.c (ffffffff81425e50)
Location: crypto/cipher.c:46
Inline: False
```
```
In crypto/ablkcipher.c (ffffffff81428bf0)
Location: crypto/ablkcipher.c:327
Inline: False
```
```
In crypto/blkcipher.c (ffffffff81429630)
Location: crypto/blkcipher.c:398
Inline: False
Direct callers:
  - crypto/blkcipher.c:async_setkey
```
```
In crypto/xts.c (ffffffff81437040)
Location: crypto/xts.c:58
Inline: False
```
```
In lib/btree.c (ffffffff8149c30e)
Location: lib/btree.c:158
Inline: True
Inline callers:
  - lib/btree.c:btree_remove_level
  - lib/btree.c:merge
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
```
**Symbols:**

```
ffffffff81425e50-ffffffff81425f4c: setkey (STB_LOCAL)
ffffffff81428bf0-ffffffff81428cd9: setkey (STB_LOCAL)
ffffffff81429630-ffffffff81429719: setkey (STB_LOCAL)
ffffffff81437040-ffffffff81437135: setkey (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline ⚠️</summary>

```c
int setkey(struct crypto_tfm *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/cipher.c (ffffffff81458d60)
Location: crypto/cipher.c:47
Inline: False
```
```
In crypto/ablkcipher.c (ffffffff8145ba20)
Location: crypto/ablkcipher.c:322
Inline: False
```
```
In crypto/blkcipher.c (ffffffff8145c3f0)
Location: crypto/blkcipher.c:395
Inline: False
Direct callers:
  - crypto/blkcipher.c:async_setkey
```
```
In crypto/xts.c (ffffffff81469a70)
Location: crypto/xts.c:58
Inline: True
```
```
In lib/btree.c (ffffffff814d15d5)
Location: lib/btree.c:160
Inline: True
Inline callers:
  - lib/btree.c:btree_remove_level
  - lib/btree.c:merge
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
```
**Symbols:**

```
ffffffff81458d60-ffffffff81458e5c: setkey (STB_LOCAL)
ffffffff8145ba20-ffffffff8145bb09: setkey (STB_LOCAL)
ffffffff8145c3f0-ffffffff8145c4d9: setkey (STB_LOCAL)
ffffffff81469a70-ffffffff81469b63: setkey (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline ⚠️</summary>

```c
int setkey(struct crypto_tfm *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/cipher.c (ffffffff81476250)
Location: crypto/cipher.c:47
Inline: False
```
```
In crypto/ablkcipher.c (ffffffff814791a0)
Location: crypto/ablkcipher.c:322
Inline: False
```
```
In crypto/blkcipher.c (ffffffff81479b30)
Location: crypto/blkcipher.c:395
Inline: False
Direct callers:
  - crypto/blkcipher.c:async_setkey
```
```
In crypto/xts.c (ffffffff81487940)
Location: crypto/xts.c:44
Inline: True
```
```
In lib/btree.c (ffffffff814e5f05)
Location: lib/btree.c:160
Inline: True
Inline callers:
  - lib/btree.c:btree_remove_level
  - lib/btree.c:merge
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
```
**Symbols:**

```
ffffffff81476250-ffffffff8147634c: setkey (STB_LOCAL)
ffffffff814791a0-ffffffff81479289: setkey (STB_LOCAL)
ffffffff81479b30-ffffffff81479c19: setkey (STB_LOCAL)
ffffffff81487940-ffffffff81487a33: setkey (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline ⚠️</summary>

```c
int setkey(struct crypto_tfm *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/cipher.c (ffffffff814a3fc0)
Location: crypto/cipher.c:42
Inline: False
```
```
In crypto/ablkcipher.c (ffffffff814a77e0)
Location: crypto/ablkcipher.c:317
Inline: False
```
```
In crypto/blkcipher.c (ffffffff814a82c0)
Location: crypto/blkcipher.c:390
Inline: False
Direct callers:
  - crypto/blkcipher.c:async_setkey
```
```
In crypto/xts.c (ffffffff814b5650)
Location: crypto/xts.c:40
Inline: True
```
```
In lib/btree.c (ffffffff81512842)
Location: lib/btree.c:158
Inline: True
Inline callers:
  - lib/btree.c:btree_remove_level
  - lib/btree.c:merge
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
```
**Symbols:**

```
ffffffff814a3fc0-ffffffff814a40d6: setkey (STB_LOCAL)
ffffffff814a77e0-ffffffff814a78da: setkey (STB_LOCAL)
ffffffff814a82c0-ffffffff814a83ba: setkey (STB_LOCAL)
ffffffff814b5650-ffffffff814b5748: setkey (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline ⚠️</summary>

```c
int setkey(struct crypto_tfm *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/cipher.c (ffffffff814bebf0)
Location: crypto/cipher.c:42
Inline: False
```
```
In crypto/ablkcipher.c (ffffffff814c2460)
Location: crypto/ablkcipher.c:317
Inline: False
```
```
In crypto/blkcipher.c (ffffffff814c2f30)
Location: crypto/blkcipher.c:390
Inline: False
Direct callers:
  - crypto/blkcipher.c:async_setkey
```
```
In crypto/xts.c (ffffffff814ce850)
Location: crypto/xts.c:40
Inline: True
```
```
In lib/btree.c (ffffffff81533282)
Location: lib/btree.c:158
Inline: True
Inline callers:
  - lib/btree.c:btree_remove_level
  - lib/btree.c:merge
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
```
**Symbols:**

```
ffffffff814bebf0-ffffffff814bed06: setkey (STB_LOCAL)
ffffffff814c2460-ffffffff814c255a: setkey (STB_LOCAL)
ffffffff814c2f30-ffffffff814c302a: setkey (STB_LOCAL)
ffffffff814ce850-ffffffff814ce948: setkey (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Selective Inline ⚠️</summary>

```c
int setkey(struct crypto_skcipher *parent, const u8 *key, unsigned int keylen);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff8152db60)
Location: crypto/xts.c:40
Inline: True
```
```
In lib/btree.c (ffffffff8159760d)
Location: lib/btree.c:158
Inline: True
Inline callers:
  - lib/btree.c:btree_remove_level
  - lib/btree.c:merge
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
```
**Symbols:**

```
ffffffff8152db60-ffffffff8152dc12: setkey (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/btree.c (ffffffff815b302d)
Location: lib/btree.c:158
Inline: True
Inline callers:
  - lib/btree.c:btree_remove_level
  - lib/btree.c:merge
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/btree.c (ffffffff815bdead)
Location: lib/btree.c:158
Inline: True
Inline callers:
  - lib/btree.c:btree_remove_level
  - lib/btree.c:merge
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/btree.c (ffffffff81625238)
Location: lib/btree.c:158
Inline: True
Inline callers:
  - lib/btree.c:btree_remove_level
  - lib/btree.c:merge
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/btree.c (ffffffff816f5904)
Location: lib/btree.c:158
Inline: True
Inline callers:
  - lib/btree.c:btree_remove_level
  - lib/btree.c:merge
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/btree.c (ffffffff817e7f74)
Location: lib/btree.c:158
Inline: True
Inline callers:
  - lib/btree.c:btree_remove_level
  - lib/btree.c:merge
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/btree.c (ffffffff81827f72)
Location: lib/btree.c:158
Inline: True
Inline callers:
  - lib/btree.c:btree_remove_level
  - lib/btree.c:merge
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/btree.c (ffffffff81879982)
Location: lib/btree.c:158
Inline: True
Inline callers:
  - lib/btree.c:btree_remove_level
  - lib/btree.c:merge
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Selective Inline ⚠️</summary>

```c
int setkey(struct crypto_tfm *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/cipher.c (ffff8000105b7d08)
Location: crypto/cipher.c:42
Inline: False
```
```
In crypto/ablkcipher.c (ffff8000105bc458)
Location: crypto/ablkcipher.c:317
Inline: False
```
```
In crypto/blkcipher.c (ffff8000105bcf30)
Location: crypto/blkcipher.c:390
Inline: False
Direct callers:
  - crypto/blkcipher.c:async_setkey
```
```
In crypto/xts.c (ffff8000105caa40)
Location: crypto/xts.c:40
Inline: True
```
```
In lib/btree.c (ffff80001063fa98)
Location: lib/btree.c:158
Inline: True
Inline callers:
  - lib/btree.c:btree_remove_level
  - lib/btree.c:merge
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
```
**Symbols:**

```
ffff8000105b7d08-ffff8000105b7e38: setkey (STB_LOCAL)
ffff8000105bc458-ffff8000105bc578: setkey (STB_LOCAL)
ffff8000105bcf30-ffff8000105bd050: setkey (STB_LOCAL)
ffff8000105caa40-ffff8000105cab74: setkey (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Selective Inline ⚠️</summary>

```c
int setkey(struct crypto_tfm *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/cipher.c (c0766a5c)
Location: crypto/cipher.c:42
Inline: False
```
```
In crypto/ablkcipher.c (c076aa50)
Location: crypto/ablkcipher.c:317
Inline: False
```
```
In crypto/blkcipher.c (c076b4d0)
Location: crypto/blkcipher.c:390
Inline: False
Direct callers:
  - crypto/blkcipher.c:async_setkey
```
```
In crypto/xts.c (c0778630)
Location: crypto/xts.c:40
Inline: True
```
```
In lib/btree.c (c07e53d8)
Location: lib/btree.c:158
Inline: True
Inline callers:
  - lib/btree.c:btree_remove_level
  - lib/btree.c:merge
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:find_level
```
**Symbols:**

```
c0766a5c-c0766b48: setkey (STB_LOCAL)
c076aa50-c076ab30: setkey (STB_LOCAL)
c076b4d0-c076b5b0: setkey (STB_LOCAL)
c0778630-c0778758: setkey (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Selective Inline ⚠️</summary>

```c
int setkey(struct crypto_tfm *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/cipher.c (c00000000073ceb0)
Location: crypto/cipher.c:42
Inline: False
```
```
In crypto/ablkcipher.c (c000000000743a70)
Location: crypto/ablkcipher.c:317
Inline: False
```
```
In crypto/blkcipher.c (c000000000744960)
Location: crypto/blkcipher.c:390
Inline: False
Direct callers:
  - crypto/blkcipher.c:async_setkey
```
```
In crypto/xts.c (c0000000007553b0)
Location: crypto/xts.c:40
Inline: True
```
```
In lib/btree.c (c0000000007e994c)
Location: lib/btree.c:158
Inline: True
Inline callers:
  - lib/btree.c:btree_remove_level
  - lib/btree.c:merge
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
```
**Symbols:**

```
c00000000073ceb0-c00000000073cf50: setkey (STB_LOCAL)
c000000000743a70-c000000000743bfc: setkey (STB_LOCAL)
c000000000744960-c000000000744aec: setkey (STB_LOCAL)
c0000000007553b0-c000000000755530: setkey (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Selective Inline ⚠️</summary>

```c
int setkey(struct crypto_tfm *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/cipher.c (ffffffe0003fe490)
Location: crypto/cipher.c:42
Inline: False
```
```
In crypto/ablkcipher.c (ffffffe000401d38)
Location: crypto/ablkcipher.c:317
Inline: False
```
```
In crypto/blkcipher.c (ffffffe00040269c)
Location: crypto/blkcipher.c:390
Inline: False
Direct callers:
  - crypto/blkcipher.c:async_setkey
```
```
In crypto/xts.c (ffffffe00040ec4a)
Location: crypto/xts.c:40
Inline: True
```
```
In lib/btree.c (ffffffe00046c700)
Location: lib/btree.c:158
Inline: True
Inline callers:
  - lib/btree.c:btree_remove_level
  - lib/btree.c:merge
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
```
**Symbols:**

```
ffffffe00040ec4a-ffffffe00040ed4e: setkey (STB_LOCAL)
ffffffe0003fe490-ffffffe0003fe57a: setkey (STB_LOCAL)
ffffffe000401d38-ffffffe000401e18: setkey (STB_LOCAL)
ffffffe00040269c-ffffffe00040277c: setkey (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Selective Inline ⚠️</summary>

```c
int setkey(struct crypto_tfm *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/cipher.c (ffffffff814b71d0)
Location: crypto/cipher.c:42
Inline: False
```
```
In crypto/ablkcipher.c (ffffffff814baa40)
Location: crypto/ablkcipher.c:317
Inline: False
```
```
In crypto/blkcipher.c (ffffffff814bb510)
Location: crypto/blkcipher.c:390
Inline: False
Direct callers:
  - crypto/blkcipher.c:async_setkey
```
```
In crypto/xts.c (ffffffff814c6e30)
Location: crypto/xts.c:40
Inline: True
```
```
In lib/btree.c (ffffffff8152b862)
Location: lib/btree.c:158
Inline: True
Inline callers:
  - lib/btree.c:btree_remove_level
  - lib/btree.c:merge
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
```
**Symbols:**

```
ffffffff814b71d0-ffffffff814b72e6: setkey (STB_LOCAL)
ffffffff814baa40-ffffffff814bab3a: setkey (STB_LOCAL)
ffffffff814bb510-ffffffff814bb60a: setkey (STB_LOCAL)
ffffffff814c6e30-ffffffff814c6f28: setkey (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Selective Inline ⚠️</summary>

```c
int setkey(struct crypto_tfm *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/cipher.c (ffffffff814a7bf0)
Location: crypto/cipher.c:42
Inline: False
```
```
In crypto/ablkcipher.c (ffffffff814ab460)
Location: crypto/ablkcipher.c:317
Inline: False
```
```
In crypto/blkcipher.c (ffffffff814abf30)
Location: crypto/blkcipher.c:390
Inline: False
Direct callers:
  - crypto/blkcipher.c:async_setkey
```
```
In crypto/xts.c (ffffffff814b7850)
Location: crypto/xts.c:40
Inline: True
```
```
In lib/btree.c (ffffffff8151bb42)
Location: lib/btree.c:158
Inline: True
Inline callers:
  - lib/btree.c:btree_remove_level
  - lib/btree.c:merge
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
```
**Symbols:**

```
ffffffff814a7bf0-ffffffff814a7d06: setkey (STB_LOCAL)
ffffffff814ab460-ffffffff814ab55a: setkey (STB_LOCAL)
ffffffff814abf30-ffffffff814ac02a: setkey (STB_LOCAL)
ffffffff814b7850-ffffffff814b7948: setkey (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline ⚠️</summary>

```c
int setkey(struct crypto_tfm *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/cipher.c (ffffffff814b3260)
Location: crypto/cipher.c:42
Inline: False
```
```
In crypto/ablkcipher.c (ffffffff814b6ad0)
Location: crypto/ablkcipher.c:317
Inline: False
```
```
In crypto/blkcipher.c (ffffffff814b75a0)
Location: crypto/blkcipher.c:390
Inline: False
Direct callers:
  - crypto/blkcipher.c:async_setkey
```
```
In crypto/xts.c (ffffffff814c2ec0)
Location: crypto/xts.c:40
Inline: True
```
```
In lib/btree.c (ffffffff815278f2)
Location: lib/btree.c:158
Inline: True
Inline callers:
  - lib/btree.c:btree_remove_level
  - lib/btree.c:merge
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
```
**Symbols:**

```
ffffffff814b3260-ffffffff814b3376: setkey (STB_LOCAL)
ffffffff814b6ad0-ffffffff814b6bca: setkey (STB_LOCAL)
ffffffff814b75a0-ffffffff814b769a: setkey (STB_LOCAL)
ffffffff814c2ec0-ffffffff814c2fb8: setkey (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline ⚠️</summary>

```c
int setkey(struct crypto_tfm *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/cipher.c (ffffffff814cbce0)
Location: crypto/cipher.c:42
Inline: False
```
```
In crypto/ablkcipher.c (ffffffff814cf560)
Location: crypto/ablkcipher.c:317
Inline: False
```
```
In crypto/blkcipher.c (ffffffff814d0080)
Location: crypto/blkcipher.c:390
Inline: False
Direct callers:
  - crypto/blkcipher.c:async_setkey
```
```
In crypto/xts.c (ffffffff814db990)
Location: crypto/xts.c:40
Inline: True
```
```
In lib/btree.c (ffffffff815412d2)
Location: lib/btree.c:158
Inline: True
Inline callers:
  - lib/btree.c:btree_remove_level
  - lib/btree.c:merge
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
  - lib/btree.c:btree_insert_level
```
**Symbols:**

```
ffffffff814cbce0-ffffffff814cbdf6: setkey (STB_LOCAL)
ffffffff814cf560-ffffffff814cf65a: setkey (STB_LOCAL)
ffffffff814d0080-ffffffff814d017a: setkey (STB_LOCAL)
ffffffff814db990-ffffffff814dba88: setkey (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct crypto_skcipher *parent</code>
</li>
<li>
<b>Param removed. </b>
<code>struct crypto_tfm *tfm</code>
</li>
</ul>
</details>
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
