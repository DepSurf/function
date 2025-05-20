# Function: <code>fscrypt_decrypt_bio</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void fscrypt_decrypt_bio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/bio.c (ffffffff812fc680)
Location: fs/crypto/bio.c:50
Inline: False
```
**Symbols:**

```
ffffffff812fc680-ffffffff812fc692: fscrypt_decrypt_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void fscrypt_decrypt_bio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/bio.c (ffffffff81311ee0)
Location: fs/crypto/bio.c:50
Inline: False
```
**Symbols:**

```
ffffffff81311ee0-ffffffff81311ef2: fscrypt_decrypt_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void fscrypt_decrypt_bio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/bio.c (ffffffff81339480)
Location: fs/crypto/bio.c:47
Inline: False
```
**Symbols:**

```
ffffffff81339480-ffffffff81339492: fscrypt_decrypt_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void fscrypt_decrypt_bio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/bio.c (ffffffff8134f300)
Location: fs/crypto/bio.c:47
Inline: False
Direct callers:
  - fs/ext4/readpage.c:decrypt_work
```
**Symbols:**

```
ffffffff8134f300-ffffffff8134f312: fscrypt_decrypt_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void fscrypt_decrypt_bio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/bio.c (ffffffff81395790)
Location: fs/crypto/bio.c:29
Inline: False
Direct callers:
  - fs/ext4/readpage.c:decrypt_work
```
**Symbols:**

```
ffffffff81395790-ffffffff8139583c: fscrypt_decrypt_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fscrypt_decrypt_bio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/bio.c (ffffffff813a6ab0)
Location: fs/crypto/bio.c:29
Inline: False
Direct callers:
  - fs/ext4/readpage.c:decrypt_work
```
**Symbols:**

```
ffffffff813a6ab0-ffffffff813a6b5c: fscrypt_decrypt_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fscrypt_decrypt_bio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/bio.c (ffffffff813adb40)
Location: fs/crypto/bio.c:29
Inline: False
Direct callers:
  - fs/ext4/readpage.c:decrypt_work
```
**Symbols:**

```
ffffffff813adb40-ffffffff813adbec: fscrypt_decrypt_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void fscrypt_decrypt_bio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/bio.c (ffffffff813fd4c0)
Location: fs/crypto/bio.c:29
Inline: False
Direct callers:
  - fs/ext4/readpage.c:decrypt_work
```
**Symbols:**

```
ffffffff813fd4c0-ffffffff813fd56c: fscrypt_decrypt_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void fscrypt_decrypt_bio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/bio.c (ffffffff81470cc0)
Location: fs/crypto/bio.c:31
Inline: False
Direct callers:
  - fs/ext4/readpage.c:decrypt_work
```
**Symbols:**

```
ffffffff81470cc0-ffffffff81470da6: fscrypt_decrypt_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool fscrypt_decrypt_bio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/bio.c (ffffffff815027b0)
Location: fs/crypto/bio.c:31
Inline: False
Direct callers:
  - fs/ext4/readpage.c:decrypt_work
```
**Symbols:**

```
ffffffff815027b0-ffffffff8150287e: fscrypt_decrypt_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool fscrypt_decrypt_bio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/bio.c (0)
Location: fs/crypto/bio.c:31
Inline: False
Direct callers:
  - fs/ext4/readpage.c:decrypt_work
```
**Symbols:**

```
ffffffff820ea65d-ffffffff820ea6c3: fscrypt_decrypt_bio.cold (STB_LOCAL)
ffffffff8153a5a0-ffffffff8153a86b: fscrypt_decrypt_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool fscrypt_decrypt_bio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/bio.c (0)
Location: fs/crypto/bio.c:31
Inline: False
Direct callers:
  - fs/ext4/readpage.c:decrypt_work
```
**Symbols:**

```
ffffffff821c7314-ffffffff821c732d: fscrypt_decrypt_bio.cold (STB_LOCAL)
ffffffff8156f950-ffffffff8156fa96: fscrypt_decrypt_bio (STB_GLOBAL)
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
void fscrypt_decrypt_bio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/bio.c (ffff800010410ee0)
Location: fs/crypto/bio.c:47
Inline: False
Direct callers:
  - fs/ext4/readpage.c:decrypt_work
```
**Symbols:**

```
ffff800010410ee0-ffff800010410f10: fscrypt_decrypt_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fscrypt_decrypt_bio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/bio.c (c05dd2c0)
Location: fs/crypto/bio.c:47
Inline: False
Direct callers:
  - fs/ext4/readpage.c:decrypt_work
```
**Symbols:**

```
c05dd2c0-c05dd2e0: fscrypt_decrypt_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fscrypt_decrypt_bio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/bio.c (c00000000051e6b0)
Location: fs/crypto/bio.c:47
Inline: False
Direct callers:
  - fs/ext4/readpage.c:decrypt_work
```
**Symbols:**

```
c00000000051e6b0-c00000000051e6c8: fscrypt_decrypt_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fscrypt_decrypt_bio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/bio.c (ffffffe0002b9122)
Location: fs/crypto/bio.c:47
Inline: False
Direct callers:
  - fs/ext4/readpage.c:decrypt_work
```
**Symbols:**

```
ffffffe0002b9122-ffffffe0002b914e: fscrypt_decrypt_bio (STB_GLOBAL)
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
void fscrypt_decrypt_bio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/bio.c (ffffffff813478e0)
Location: fs/crypto/bio.c:47
Inline: False
Direct callers:
  - fs/ext4/readpage.c:decrypt_work
```
**Symbols:**

```
ffffffff813478e0-ffffffff813478f2: fscrypt_decrypt_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void fscrypt_decrypt_bio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/bio.c (ffffffff813385c0)
Location: fs/crypto/bio.c:47
Inline: False
Direct callers:
  - fs/ext4/readpage.c:decrypt_work
```
**Symbols:**

```
ffffffff813385c0-ffffffff813385d2: fscrypt_decrypt_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void fscrypt_decrypt_bio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/bio.c (ffffffff813453b0)
Location: fs/crypto/bio.c:47
Inline: False
Direct callers:
  - fs/ext4/readpage.c:decrypt_work
```
**Symbols:**

```
ffffffff813453b0-ffffffff813453c2: fscrypt_decrypt_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void fscrypt_decrypt_bio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/bio.c (ffffffff81358690)
Location: fs/crypto/bio.c:47
Inline: False
Direct callers:
  - fs/ext4/readpage.c:decrypt_work
```
**Symbols:**

```
ffffffff81358690-ffffffff813586a2: fscrypt_decrypt_bio (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
