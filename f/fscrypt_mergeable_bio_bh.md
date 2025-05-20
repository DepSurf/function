# Function: <code>fscrypt_mergeable_bio_bh</code>

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
<summary>In <code>5.11</code>: ✅</summary>

```c
bool fscrypt_mergeable_bio_bh(struct bio *bio, const struct buffer_head *next_bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/inline_crypt.c (ffffffff813a7310)
Location: fs/crypto/inline_crypt.c:354
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff813a7310-ffffffff813a737d: fscrypt_mergeable_bio_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool fscrypt_mergeable_bio_bh(struct bio *bio, const struct buffer_head *next_bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/inline_crypt.c (ffffffff813ae360)
Location: fs/crypto/inline_crypt.c:354
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff813ae360-ffffffff813ae3cd: fscrypt_mergeable_bio_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool fscrypt_mergeable_bio_bh(struct bio *bio, const struct buffer_head *next_bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/inline_crypt.c (0)
Location: fs/crypto/inline_crypt.c:354
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff81cc6b32-ffffffff81cc6b77: fscrypt_mergeable_bio_bh.cold (STB_LOCAL)
ffffffff813fe000-ffffffff813fe092: fscrypt_mergeable_bio_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool fscrypt_mergeable_bio_bh(struct bio *bio, const struct buffer_head *next_bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/inline_crypt.c (ffffffff81471a10)
Location: fs/crypto/inline_crypt.c:390
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff81471a10-ffffffff81471a92: fscrypt_mergeable_bio_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool fscrypt_mergeable_bio_bh(struct bio *bio, const struct buffer_head *next_bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/inline_crypt.c (ffffffff815035f0)
Location: fs/crypto/inline_crypt.c:381
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff815035f0-ffffffff81503672: fscrypt_mergeable_bio_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool fscrypt_mergeable_bio_bh(struct bio *bio, const struct buffer_head *next_bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/inline_crypt.c (ffffffff8153aea0)
Location: fs/crypto/inline_crypt.c:381
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_bio_write_folio
```
**Symbols:**

```
ffffffff8153aea0-ffffffff8153af22: fscrypt_mergeable_bio_bh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool fscrypt_mergeable_bio_bh(struct bio *bio, const struct buffer_head *next_bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/inline_crypt.c (ffffffff815701c0)
Location: fs/crypto/inline_crypt.c:383
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_bio_write_folio
```
**Symbols:**

```
ffffffff815701c0-ffffffff81570242: fscrypt_mergeable_bio_bh (STB_GLOBAL)
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
