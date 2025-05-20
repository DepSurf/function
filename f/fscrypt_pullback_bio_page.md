# Function: <code>fscrypt_pullback_bio_page</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void fscrypt_pullback_bio_page(struct page **page, bool restore);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff81288820)
Location: fs/crypto/crypto.c:439
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
**Symbols:**

```
ffffffff81288820-ffffffff8128884f: fscrypt_pullback_bio_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void fscrypt_pullback_bio_page(struct page **page, bool restore);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff8129d520)
Location: fs/crypto/crypto.c:474
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
**Symbols:**

```
ffffffff8129d520-ffffffff8129d54f: fscrypt_pullback_bio_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void fscrypt_pullback_bio_page(struct page **page, bool restore);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/bio.c (ffffffff812ae1f0)
Location: fs/crypto/bio.c:65
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
**Symbols:**

```
ffffffff812ae1f0-ffffffff812ae21f: fscrypt_pullback_bio_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void fscrypt_pullback_bio_page(struct page **page, bool restore);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/bio.c (ffffffff812d1bf0)
Location: fs/crypto/bio.c:66
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
**Symbols:**

```
ffffffff812d1bf0-ffffffff812d1c1f: fscrypt_pullback_bio_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void fscrypt_pullback_bio_page(struct page **page, bool restore);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/bio.c (ffffffff812fc720)
Location: fs/crypto/bio.c:75
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
**Symbols:**

```
ffffffff812fc720-ffffffff812fc74e: fscrypt_pullback_bio_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void fscrypt_pullback_bio_page(struct page **page, bool restore);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/bio.c (ffffffff81311f80)
Location: fs/crypto/bio.c:75
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
**Symbols:**

```
ffffffff81311f80-ffffffff81311fae: fscrypt_pullback_bio_page (STB_GLOBAL)
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
</ul>
