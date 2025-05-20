# Function: <code>fscrypt_match_name</code>

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
In fs/ext4/namei.c (ffffffff8131924c)
Location: include/linux/fscrypt_supp.h:120
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
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
In fs/ext4/namei.c (ffffffff8133d98c)
Location: include/linux/fscrypt_supp.h:122
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
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
In fs/ext4/namei.c (ffffffff8136bec6)
Location: include/linux/fscrypt_supp.h:158
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
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
In fs/ext4/namei.c (ffffffff813843a6)
Location: include/linux/fscrypt_supp.h:158
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
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
In fs/ext4/namei.c (ffffffff813adcd8)
Location: include/linux/fscrypt.h:215
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
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
In fs/ext4/namei.c (ffffffff813c6c18)
Location: include/linux/fscrypt.h:226
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool fscrypt_match_name(const struct fscrypt_name *fname, const u8 *de_name, u32 de_name_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff81390600)
Location: fs/crypto/fname.c:517
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
```
**Symbols:**

```
ffffffff81390600-ffffffff813906ed: fscrypt_match_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool fscrypt_match_name(const struct fscrypt_name *fname, const u8 *de_name, u32 de_name_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff813a1a80)
Location: fs/crypto/fname.c:486
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
```
**Symbols:**

```
ffffffff813a1a80-ffffffff813a1b6e: fscrypt_match_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool fscrypt_match_name(const struct fscrypt_name *fname, const u8 *de_name, u32 de_name_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff813a8c20)
Location: fs/crypto/fname.c:482
Inline: False
```
**Symbols:**

```
ffffffff813a8c20-ffffffff813a8d0d: fscrypt_match_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool fscrypt_match_name(const struct fscrypt_name *fname, const u8 *de_name, u32 de_name_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff813f8390)
Location: fs/crypto/fname.c:506
Inline: False
```
**Symbols:**

```
ffffffff813f8390-ffffffff813f847d: fscrypt_match_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool fscrypt_match_name(const struct fscrypt_name *fname, const u8 *de_name, u32 de_name_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff8146afe0)
Location: fs/crypto/fname.c:512
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_match
```
**Symbols:**

```
ffffffff8146afe0-ffffffff8146b0f9: fscrypt_match_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool fscrypt_match_name(const struct fscrypt_name *fname, const u8 *de_name, u32 de_name_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff814fc180)
Location: fs/crypto/fname.c:536
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_match
```
**Symbols:**

```
ffffffff814fc180-ffffffff814fc29e: fscrypt_match_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool fscrypt_match_name(const struct fscrypt_name *fname, const u8 *de_name, u32 de_name_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff815336f0)
Location: fs/crypto/fname.c:536
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_match
```
**Symbols:**

```
ffffffff815336f0-ffffffff8153380e: fscrypt_match_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool fscrypt_match_name(const struct fscrypt_name *fname, const u8 *de_name, u32 de_name_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff81568680)
Location: fs/crypto/fname.c:536
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_match
```
**Symbols:**

```
ffffffff81568680-ffffffff8156879e: fscrypt_match_name (STB_GLOBAL)
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
In fs/ext4/namei.c (ffff80001049e718)
Location: include/linux/fscrypt.h:226
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
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
In fs/ext4/namei.c (c0660524)
Location: include/linux/fscrypt.h:226
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
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
In fs/ext4/namei.c (c0000000005ca304)
Location: include/linux/fscrypt.h:226
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
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
In fs/ext4/namei.c (ffffffe000321112)
Location: include/linux/fscrypt.h:226
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
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
In fs/ext4/namei.c (ffffffff813bf1f8)
Location: include/linux/fscrypt.h:226
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
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
In fs/ext4/namei.c (ffffffff813afc88)
Location: include/linux/fscrypt.h:226
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
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
In fs/ext4/namei.c (ffffffff813bc67d)
Location: include/linux/fscrypt.h:226
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
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
In fs/ext4/namei.c (ffffffff813d1788)
Location: include/linux/fscrypt.h:226
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
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
