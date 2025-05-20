# Function: <code>utf8_casefold</code>

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
int utf8_casefold(const struct unicode_map *um, const struct qstr *str, unsigned char *dest, size_t dlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-core.c (ffffffff81404f00)
Location: fs/unicode/utf8-core.c:104
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_d_hash
  - fs/ext4/hash.c:ext4fs_dirhash
```
**Symbols:**

```
ffffffff81404f00-ffffffff81404f9a: utf8_casefold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int utf8_casefold(const struct unicode_map *um, const struct qstr *str, unsigned char *dest, size_t dlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-core.c (ffffffff8141eeb0)
Location: fs/unicode/utf8-core.c:104
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_d_hash
  - fs/ext4/hash.c:ext4fs_dirhash
```
**Symbols:**

```
ffffffff8141eeb0-ffffffff8141ef4a: utf8_casefold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int utf8_casefold(const struct unicode_map *um, const struct qstr *str, unsigned char *dest, size_t dlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-core.c (ffffffff8146dac0)
Location: fs/unicode/utf8-core.c:104
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_d_hash
  - fs/ext4/hash.c:ext4fs_dirhash
```
**Symbols:**

```
ffffffff8146dac0-ffffffff8146db5a: utf8_casefold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int utf8_casefold(const struct unicode_map *um, const struct qstr *str, unsigned char *dest, size_t dlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-core.c (ffffffff814881c0)
Location: fs/unicode/utf8-core.c:105
Inline: False
Direct callers:
  - fs/ext4/hash.c:ext4fs_dirhash
```
**Symbols:**

```
ffffffff814881c0-ffffffff8148825a: utf8_casefold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int utf8_casefold(const struct unicode_map *um, const struct qstr *str, unsigned char *dest, size_t dlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-core.c (ffffffff8148dba0)
Location: fs/unicode/utf8-core.c:105
Inline: False
Direct callers:
  - fs/ext4/hash.c:ext4fs_dirhash
  - fs/ext4/namei.c:ext4_fname_setup_ci_filename
```
**Symbols:**

```
ffffffff8148dba0-ffffffff8148dc3a: utf8_casefold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int utf8_casefold(const struct unicode_map *um, const struct qstr *str, unsigned char *dest, size_t dlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-core.c (ffffffff814e5610)
Location: fs/unicode/utf8-core.c:105
Inline: False
Direct callers:
  - fs/ext4/hash.c:ext4fs_dirhash
  - fs/ext4/namei.c:ext4_fname_setup_ci_filename
```
**Symbols:**

```
ffffffff814e5610-ffffffff814e56aa: utf8_casefold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int utf8_casefold(const struct unicode_map *um, const struct qstr *str, unsigned char *dest, size_t dlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-core.c (ffffffff815735c0)
Location: fs/unicode/utf8-core.c:99
Inline: False
Direct callers:
  - fs/ext4/hash.c:ext4fs_dirhash
  - fs/ext4/namei.c:ext4_fname_setup_ci_filename
```
**Symbols:**

```
ffffffff815735c0-ffffffff8157367d: utf8_casefold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int utf8_casefold(const struct unicode_map *um, const struct qstr *str, unsigned char *dest, size_t dlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-core.c (ffffffff81618ba0)
Location: fs/unicode/utf8-core.c:99
Inline: False
Direct callers:
  - fs/ext4/hash.c:ext4fs_dirhash
  - fs/ext4/namei.c:ext4_fname_setup_ci_filename
```
**Symbols:**

```
ffffffff81618ba0-ffffffff81618c5d: utf8_casefold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int utf8_casefold(const struct unicode_map *um, const struct qstr *str, unsigned char *dest, size_t dlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-core.c (ffffffff81650c60)
Location: fs/unicode/utf8-core.c:99
Inline: False
Direct callers:
  - fs/ext4/hash.c:ext4fs_dirhash
  - fs/ext4/namei.c:ext4_fname_setup_ci_filename
```
**Symbols:**

```
ffffffff81650c60-ffffffff81650d1d: utf8_casefold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int utf8_casefold(const struct unicode_map *um, const struct qstr *str, unsigned char *dest, size_t dlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-core.c (ffffffff8168a240)
Location: fs/unicode/utf8-core.c:99
Inline: False
Direct callers:
  - fs/ext4/hash.c:ext4fs_dirhash
  - fs/ext4/namei.c:ext4_fname_setup_ci_filename
```
**Symbols:**

```
ffffffff8168a240-ffffffff8168a2fd: utf8_casefold (STB_GLOBAL)
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
int utf8_casefold(const struct unicode_map *um, const struct qstr *str, unsigned char *dest, size_t dlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-core.c (ffff8000105010e8)
Location: fs/unicode/utf8-core.c:104
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_d_hash
  - fs/ext4/hash.c:ext4fs_dirhash
```
**Symbols:**

```
ffff8000105010e8-ffff8000105011ac: utf8_casefold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int utf8_casefold(const struct unicode_map *um, const struct qstr *str, unsigned char *dest, size_t dlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-core.c (c06bdd8c)
Location: fs/unicode/utf8-core.c:104
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_d_hash
  - fs/ext4/hash.c:ext4fs_dirhash
```
**Symbols:**

```
c06bdd8c-c06bde5c: utf8_casefold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int utf8_casefold(const struct unicode_map *um, const struct qstr *str, unsigned char *dest, size_t dlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-core.c (c0000000006453a0)
Location: fs/unicode/utf8-core.c:104
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_d_hash
  - fs/ext4/hash.c:ext4fs_dirhash
```
**Symbols:**

```
c0000000006453a0-c00000000064549c: utf8_casefold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int utf8_casefold(const struct unicode_map *um, const struct qstr *str, unsigned char *dest, size_t dlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-core.c (ffffffe00036e7a2)
Location: fs/unicode/utf8-core.c:104
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_d_hash
  - fs/ext4/hash.c:ext4fs_dirhash
```
**Symbols:**

```
ffffffe00036e7a2-ffffffe00036e838: utf8_casefold (STB_GLOBAL)
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
int utf8_casefold(const struct unicode_map *um, const struct qstr *str, unsigned char *dest, size_t dlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-core.c (ffffffff81417490)
Location: fs/unicode/utf8-core.c:104
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_d_hash
  - fs/ext4/hash.c:ext4fs_dirhash
```
**Symbols:**

```
ffffffff81417490-ffffffff8141752a: utf8_casefold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int utf8_casefold(const struct unicode_map *um, const struct qstr *str, unsigned char *dest, size_t dlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-core.c (ffffffff81407f10)
Location: fs/unicode/utf8-core.c:104
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_d_hash
  - fs/ext4/hash.c:ext4fs_dirhash
```
**Symbols:**

```
ffffffff81407f10-ffffffff81407faa: utf8_casefold (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int utf8_casefold(const struct unicode_map *um, const struct qstr *str, unsigned char *dest, size_t dlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-core.c (ffffffff8142a470)
Location: fs/unicode/utf8-core.c:104
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_d_hash
  - fs/ext4/hash.c:ext4fs_dirhash
```
**Symbols:**

```
ffffffff8142a470-ffffffff8142a50a: utf8_casefold (STB_GLOBAL)
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
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
