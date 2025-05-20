# Function: <code>aa_perm_mask_to_str</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void aa_perm_mask_to_str(char *str, const char *chrs, u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff81378670)
Location: security/apparmor/lib.c:231
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_audit_perm_mask
Direct callers:
  - security/apparmor/file.c:audit_file_mask
```
**Symbols:**

```
ffffffff81378670-ffffffff813786a2: aa_perm_mask_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void aa_perm_mask_to_str(char *str, const char *chrs, u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff813b1504)
Location: security/apparmor/lib.c:231
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_audit_perm_mask
Direct callers:
  - security/apparmor/file.c:audit_file_mask
```
**Symbols:**

```
ffffffff813b13d0-ffffffff813b1402: aa_perm_mask_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void aa_perm_mask_to_str(char *str, const char *chrs, u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff813c86c4)
Location: security/apparmor/lib.c:231
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_audit_perm_mask
Direct callers:
  - security/apparmor/file.c:audit_file_mask
```
**Symbols:**

```
ffffffff813c8590-ffffffff813c85c2: aa_perm_mask_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void aa_perm_mask_to_str(char *str, const char *chrs, u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff813dde6f)
Location: security/apparmor/lib.c:203
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_audit_perm_mask
Direct callers:
  - security/apparmor/file.c:audit_file_mask
```
**Symbols:**

```
ffffffff813ddd40-ffffffff813ddd72: aa_perm_mask_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void aa_perm_mask_to_str(char *str, const char *chrs, u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff8140480f)
Location: security/apparmor/lib.c:203
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_audit_perm_mask
Direct callers:
  - security/apparmor/file.c:audit_file_mask
```
**Symbols:**

```
ffffffff814046e0-ffffffff81404712: aa_perm_mask_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void aa_perm_mask_to_str(char *str, const char *chrs, u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff814358bf)
Location: security/apparmor/lib.c:203
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_audit_perm_mask
Direct callers:
  - security/apparmor/file.c:audit_file_mask
```
**Symbols:**

```
ffffffff81435790-ffffffff814357c2: aa_perm_mask_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void aa_perm_mask_to_str(char *str, size_t str_size, const char *chrs, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff81452380)
Location: security/apparmor/lib.c:207
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_audit_perm_mask
  - security/apparmor/file.c:audit_file_mask
```
**Symbols:**

```
ffffffff81452380-ffffffff814523f7: aa_perm_mask_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void aa_perm_mask_to_str(char *str, size_t str_size, const char *chrs, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff8147fd40)
Location: security/apparmor/lib.c:203
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_audit_perm_mask
  - security/apparmor/file.c:audit_file_mask
```
**Symbols:**

```
ffffffff8147fd40-ffffffff8147fdb7: aa_perm_mask_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void aa_perm_mask_to_str(char *str, size_t str_size, const char *chrs, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff81499a40)
Location: security/apparmor/lib.c:203
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_audit_perm_mask
  - security/apparmor/file.c:audit_file_mask
```
**Symbols:**

```
ffffffff81499a40-ffffffff81499ab7: aa_perm_mask_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void aa_perm_mask_to_str(char *str, size_t str_size, const char *chrs, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff814f2130)
Location: security/apparmor/lib.c:203
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_audit_perm_mask
  - security/apparmor/file.c:audit_file_mask
```
**Symbols:**

```
ffffffff814f2130-ffffffff814f21a7: aa_perm_mask_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void aa_perm_mask_to_str(char *str, size_t str_size, const char *chrs, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff8150f330)
Location: security/apparmor/lib.c:203
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_audit_perm_mask
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/file.c:file_audit_cb
```
**Symbols:**

```
ffffffff8150f330-ffffffff8150f3a7: aa_perm_mask_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void aa_perm_mask_to_str(char *str, size_t str_size, const char *chrs, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff81515d20)
Location: security/apparmor/lib.c:203
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_audit_perm_mask
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/file.c:file_audit_cb
```
**Symbols:**

```
ffffffff81515d20-ffffffff81515d96: aa_perm_mask_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void aa_perm_mask_to_str(char *str, size_t str_size, const char *chrs, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff81573d20)
Location: security/apparmor/lib.c:203
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_audit_perm_mask
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/file.c:file_audit_cb
```
**Symbols:**

```
ffffffff81573d20-ffffffff81573d96: aa_perm_mask_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void aa_perm_mask_to_str(char *str, size_t str_size, const char *chrs, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff81611630)
Location: security/apparmor/lib.c:222
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_audit_perm_mask
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/file.c:file_audit_cb
```
**Symbols:**

```
ffffffff81611630-ffffffff816116c8: aa_perm_mask_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void aa_perm_mask_to_str(char *str, size_t str_size, const char *chrs, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff816c42f0)
Location: security/apparmor/lib.c:314
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_audit_perm_mask
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/file.c:file_audit_cb
```
**Symbols:**

```
ffffffff816c42f0-ffffffff816c4388: aa_perm_mask_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void aa_perm_mask_to_str(char *str, size_t str_size, const char *chrs, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff816fcec0)
Location: security/apparmor/lib.c:314
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_audit_perm_mask
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/file.c:file_audit_cb
```
**Symbols:**

```
ffffffff816fcec0-ffffffff816fcf58: aa_perm_mask_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void aa_perm_mask_to_str(char *str, size_t str_size, const char *chrs, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff8173a420)
Location: security/apparmor/lib.c:316
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_audit_perm_mask
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/file.c:file_audit_cb
```
**Symbols:**

```
ffffffff8173a420-ffffffff8173a4b8: aa_perm_mask_to_str (STB_GLOBAL)
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
void aa_perm_mask_to_str(char *str, size_t str_size, const char *chrs, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffff80001058f868)
Location: security/apparmor/lib.c:203
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_audit_perm_mask
  - security/apparmor/file.c:audit_file_mask
```
**Symbols:**

```
ffff80001058f868-ffff80001058f90c: aa_perm_mask_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void aa_perm_mask_to_str(char *str, size_t str_size, const char *chrs, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (c0740638)
Location: security/apparmor/lib.c:203
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_audit_perm_mask
  - security/apparmor/file.c:audit_file_mask
```
**Symbols:**

```
c0740638-c07406ec: aa_perm_mask_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void aa_perm_mask_to_str(char *str, size_t str_size, const char *chrs, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (c000000000702bc0)
Location: security/apparmor/lib.c:203
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_audit_perm_mask
  - security/apparmor/file.c:audit_file_mask
```
**Symbols:**

```
c000000000702bc0-c000000000702cbc: aa_perm_mask_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void aa_perm_mask_to_str(char *str, size_t str_size, const char *chrs, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffe0003dd4f0)
Location: security/apparmor/lib.c:203
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_audit_perm_mask
  - security/apparmor/file.c:audit_file_mask
```
**Symbols:**

```
ffffffe0003dd4f0-ffffffe0003dd56c: aa_perm_mask_to_str (STB_GLOBAL)
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
void aa_perm_mask_to_str(char *str, size_t str_size, const char *chrs, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff81492020)
Location: security/apparmor/lib.c:203
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_audit_perm_mask
  - security/apparmor/file.c:audit_file_mask
```
**Symbols:**

```
ffffffff81492020-ffffffff81492097: aa_perm_mask_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void aa_perm_mask_to_str(char *str, size_t str_size, const char *chrs, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff81482a40)
Location: security/apparmor/lib.c:203
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_audit_perm_mask
  - security/apparmor/file.c:audit_file_mask
```
**Symbols:**

```
ffffffff81482a40-ffffffff81482ab7: aa_perm_mask_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void aa_perm_mask_to_str(char *str, size_t str_size, const char *chrs, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff8148e0c0)
Location: security/apparmor/lib.c:203
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_audit_perm_mask
  - security/apparmor/file.c:audit_file_mask
```
**Symbols:**

```
ffffffff8148e0c0-ffffffff8148e137: aa_perm_mask_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void aa_perm_mask_to_str(char *str, size_t str_size, const char *chrs, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff814a5fd0)
Location: security/apparmor/lib.c:203
Inline: False
Direct callers:
  - security/apparmor/lib.c:aa_audit_perm_mask
  - security/apparmor/file.c:audit_file_mask
```
**Symbols:**

```
ffffffff814a5fd0-ffffffff814a6047: aa_perm_mask_to_str (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>size_t str_size</code>
</li>
<li>
<b>Param reordered. </b>
<code>str, chrs, mask</code> ➡️ <code>str, str_size, chrs, mask</code>
</li>
</ul>
</details>
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
