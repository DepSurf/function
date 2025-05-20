# Function: <code>skipn_spaces</code>

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
In security/apparmor/lib.c (ffffffff81378365)
Location: security/apparmor/lib.c:79
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_splitn_fqname
  - security/apparmor/lib.c:aa_splitn_fqname
  - security/apparmor/lib.c:aa_splitn_fqname
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
In security/apparmor/lib.c (ffffffff813b1191)
Location: security/apparmor/lib.c:79
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_splitn_fqname
  - security/apparmor/lib.c:aa_splitn_fqname
  - security/apparmor/lib.c:aa_splitn_fqname
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
const char *skipn_spaces(const char *str, size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff813c8351)
Location: security/apparmor/lib.c:79
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_splitn_fqname
  - security/apparmor/lib.c:aa_splitn_fqname
  - security/apparmor/lib.c:aa_splitn_fqname
Direct callers:
  - security/apparmor/label.c:fqlookupn_profile
```
**Symbols:**

```
ffffffff813c8270-ffffffff813c82ad: skipn_spaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
const char *skipn_spaces(const char *str, size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff813ddb41)
Location: security/apparmor/lib.c:78
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_splitn_fqname
  - security/apparmor/lib.c:aa_splitn_fqname
  - security/apparmor/lib.c:aa_splitn_fqname
Direct callers:
  - security/apparmor/label.c:fqlookupn_profile
```
**Symbols:**

```
ffffffff813dda60-ffffffff813dda9d: skipn_spaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
const char *skipn_spaces(const char *str, size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff814044e1)
Location: security/apparmor/lib.c:78
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_splitn_fqname
  - security/apparmor/lib.c:aa_splitn_fqname
  - security/apparmor/lib.c:aa_splitn_fqname
Direct callers:
  - security/apparmor/label.c:fqlookupn_profile
```
**Symbols:**

```
ffffffff81404400-ffffffff8140443d: skipn_spaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
const char *skipn_spaces(const char *str, size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff814355b1)
Location: security/apparmor/lib.c:78
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_splitn_fqname
  - security/apparmor/lib.c:aa_splitn_fqname
  - security/apparmor/lib.c:aa_splitn_fqname
Direct callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:fqlookupn_profile
```
**Symbols:**

```
ffffffff814354d0-ffffffff8143550d: skipn_spaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
const char *skipn_spaces(const char *str, size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff814521b1)
Location: security/apparmor/lib.c:78
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_splitn_fqname
  - security/apparmor/lib.c:aa_splitn_fqname
  - security/apparmor/lib.c:aa_splitn_fqname
Direct callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:fqlookupn_profile
```
**Symbols:**

```
ffffffff814520c0-ffffffff814520fd: skipn_spaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
const char *skipn_spaces(const char *str, size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff8147fbb0)
Location: security/apparmor/lib.c:74
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_splitn_fqname
  - security/apparmor/lib.c:aa_splitn_fqname
  - security/apparmor/lib.c:aa_splitn_fqname
Direct callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:fqlookupn_profile
```
**Symbols:**

```
ffffffff8147fac0-ffffffff8147faf1: skipn_spaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
const char *skipn_spaces(const char *str, size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff814998b0)
Location: security/apparmor/lib.c:74
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_splitn_fqname
  - security/apparmor/lib.c:aa_splitn_fqname
  - security/apparmor/lib.c:aa_splitn_fqname
Direct callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:fqlookupn_profile
```
**Symbols:**

```
ffffffff814997c0-ffffffff814997f1: skipn_spaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
const char *skipn_spaces(const char *str, size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff814f1f7f)
Location: security/apparmor/lib.c:74
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_splitn_fqname
  - security/apparmor/lib.c:aa_splitn_fqname
  - security/apparmor/lib.c:aa_splitn_fqname
Direct callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
```
**Symbols:**

```
ffffffff814f1eb0-ffffffff814f1ee1: skipn_spaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
const char *skipn_spaces(const char *str, size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff8150f17f)
Location: security/apparmor/lib.c:74
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_splitn_fqname
  - security/apparmor/lib.c:aa_splitn_fqname
  - security/apparmor/lib.c:aa_splitn_fqname
Direct callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
```
**Symbols:**

```
ffffffff8150f0b0-ffffffff8150f0e1: skipn_spaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
const char *skipn_spaces(const char *str, size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff81515b98)
Location: security/apparmor/lib.c:74
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_splitn_fqname
  - security/apparmor/lib.c:aa_splitn_fqname
  - security/apparmor/lib.c:aa_splitn_fqname
Direct callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
```
**Symbols:**

```
ffffffff81515aa0-ffffffff81515ad1: skipn_spaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
const char *skipn_spaces(const char *str, size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff81573b98)
Location: security/apparmor/lib.c:74
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_splitn_fqname
  - security/apparmor/lib.c:aa_splitn_fqname
  - security/apparmor/lib.c:aa_splitn_fqname
Direct callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
```
**Symbols:**

```
ffffffff81573aa0-ffffffff81573ad1: skipn_spaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
const char *skipn_spaces(const char *str, size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff81611474)
Location: security/apparmor/lib.c:93
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_splitn_fqname
  - security/apparmor/lib.c:aa_splitn_fqname
  - security/apparmor/lib.c:aa_splitn_fqname
Direct callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
```
**Symbols:**

```
ffffffff81611390-ffffffff816113cf: skipn_spaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
const char *skipn_spaces(const char *str, size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff816c40e4)
Location: security/apparmor/lib.c:185
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_splitn_fqname
  - security/apparmor/lib.c:aa_splitn_fqname
  - security/apparmor/lib.c:aa_splitn_fqname
Direct callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
```
**Symbols:**

```
ffffffff816c3ff0-ffffffff816c402f: skipn_spaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
const char *skipn_spaces(const char *str, size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff816fccb4)
Location: security/apparmor/lib.c:185
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_splitn_fqname
  - security/apparmor/lib.c:aa_splitn_fqname
  - security/apparmor/lib.c:aa_splitn_fqname
Direct callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
```
**Symbols:**

```
ffffffff816fcbc0-ffffffff816fcbff: skipn_spaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
const char *skipn_spaces(const char *str, size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff8173a214)
Location: security/apparmor/lib.c:187
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_splitn_fqname
  - security/apparmor/lib.c:aa_splitn_fqname
  - security/apparmor/lib.c:aa_splitn_fqname
Direct callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
```
**Symbols:**

```
ffffffff8173a120-ffffffff8173a15f: skipn_spaces (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
const char *skipn_spaces(const char *str, size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffff80001058f654)
Location: security/apparmor/lib.c:74
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_splitn_fqname
  - security/apparmor/lib.c:aa_splitn_fqname
  - security/apparmor/lib.c:aa_splitn_fqname
Direct callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:fqlookupn_profile
```
**Symbols:**

```
ffff80001058f548-ffff80001058f5b0: skipn_spaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
const char *skipn_spaces(const char *str, size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (c0740510)
Location: security/apparmor/lib.c:74
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_splitn_fqname
  - security/apparmor/lib.c:aa_splitn_fqname
  - security/apparmor/lib.c:aa_splitn_fqname
Direct callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:fqlookupn_profile
```
**Symbols:**

```
c0740350-c07403a0: skipn_spaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
const char *skipn_spaces(const char *str, size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (c0000000007028e4)
Location: security/apparmor/lib.c:74
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_splitn_fqname
  - security/apparmor/lib.c:aa_splitn_fqname
  - security/apparmor/lib.c:aa_splitn_fqname
Direct callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:fqlookupn_profile
```
**Symbols:**

```
c0000000007027b0-c000000000702800: skipn_spaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
const char *skipn_spaces(const char *str, size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffe0003dd33c)
Location: security/apparmor/lib.c:74
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_splitn_fqname
  - security/apparmor/lib.c:aa_splitn_fqname
  - security/apparmor/lib.c:aa_splitn_fqname
Direct callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:fqlookupn_profile
```
**Symbols:**

```
ffffffe0003dd264-ffffffe0003dd2c2: skipn_spaces (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
const char *skipn_spaces(const char *str, size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff81491e90)
Location: security/apparmor/lib.c:74
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_splitn_fqname
  - security/apparmor/lib.c:aa_splitn_fqname
  - security/apparmor/lib.c:aa_splitn_fqname
Direct callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:fqlookupn_profile
```
**Symbols:**

```
ffffffff81491da0-ffffffff81491dd1: skipn_spaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
const char *skipn_spaces(const char *str, size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff814828b0)
Location: security/apparmor/lib.c:74
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_splitn_fqname
  - security/apparmor/lib.c:aa_splitn_fqname
  - security/apparmor/lib.c:aa_splitn_fqname
Direct callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:fqlookupn_profile
```
**Symbols:**

```
ffffffff814827c0-ffffffff814827f1: skipn_spaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
const char *skipn_spaces(const char *str, size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff8148df30)
Location: security/apparmor/lib.c:74
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_splitn_fqname
  - security/apparmor/lib.c:aa_splitn_fqname
  - security/apparmor/lib.c:aa_splitn_fqname
Direct callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:fqlookupn_profile
```
**Symbols:**

```
ffffffff8148de40-ffffffff8148de71: skipn_spaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
const char *skipn_spaces(const char *str, size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/lib.c (ffffffff814a5e40)
Location: security/apparmor/lib.c:74
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_splitn_fqname
  - security/apparmor/lib.c:aa_splitn_fqname
  - security/apparmor/lib.c:aa_splitn_fqname
Direct callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:fqlookupn_profile
```
**Symbols:**

```
ffffffff814a5d50-ffffffff814a5d81: skipn_spaces (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
