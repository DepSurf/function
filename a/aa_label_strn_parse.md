# Function: <code>aa_label_strn_parse</code>

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
struct aa_label *aa_label_strn_parse(struct aa_label *base, const char *str, size_t n, gfp_t gfp, bool create, bool force_stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814492e0)
Location: security/apparmor/label.c:1859
Inline: False
Direct callers:
  - security/apparmor/secid.c:apparmor_secctx_to_secid
  - security/apparmor/label.c:aa_label_parse
```
**Symbols:**

```
ffffffff814492e0-ffffffff81449742: aa_label_strn_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct aa_label *aa_label_strn_parse(struct aa_label *base, const char *str, size_t n, gfp_t gfp, bool create, bool force_stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81466270)
Location: security/apparmor/label.c:1860
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_parse
```
**Symbols:**

```
ffffffff81466270-ffffffff814666d2: aa_label_strn_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct aa_label *aa_label_strn_parse(struct aa_label *base, const char *str, size_t n, gfp_t gfp, bool create, bool force_stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814937a0)
Location: security/apparmor/label.c:1856
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_parse
```
**Symbols:**

```
ffffffff814937a0-ffffffff81493c15: aa_label_strn_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct aa_label *aa_label_strn_parse(struct aa_label *base, const char *str, size_t n, gfp_t gfp, bool create, bool force_stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814ad6d0)
Location: security/apparmor/label.c:1885
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_parse
```
**Symbols:**

```
ffffffff814ad6d0-ffffffff814adb45: aa_label_strn_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct aa_label *aa_label_strn_parse(struct aa_label *base, const char *str, size_t n, gfp_t gfp, bool create, bool force_stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8150c440)
Location: security/apparmor/label.c:1882
Inline: False
Direct callers:
  - security/apparmor/secid.c:apparmor_secctx_to_secid
  - security/apparmor/label.c:aa_label_parse
  - security/apparmor/net.c:apparmor_secmark_init
```
**Symbols:**

```
ffffffff8150c440-ffffffff8150ca5e: aa_label_strn_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct aa_label *aa_label_strn_parse(struct aa_label *base, const char *str, size_t n, gfp_t gfp, bool create, bool force_stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff815292f0)
Location: security/apparmor/label.c:1882
Inline: False
Direct callers:
  - security/apparmor/secid.c:apparmor_secctx_to_secid
  - security/apparmor/label.c:aa_label_parse
  - security/apparmor/net.c:apparmor_secmark_init
```
**Symbols:**

```
ffffffff815292f0-ffffffff81529920: aa_label_strn_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct aa_label *aa_label_strn_parse(struct aa_label *base, const char *str, size_t n, gfp_t gfp, bool create, bool force_stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8152f460)
Location: security/apparmor/label.c:1882
Inline: False
Direct callers:
  - security/apparmor/secid.c:apparmor_secctx_to_secid
  - security/apparmor/label.c:aa_label_parse
  - security/apparmor/net.c:apparmor_secmark_check
```
**Symbols:**

```
ffffffff8152f460-ffffffff8152facc: aa_label_strn_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct aa_label *aa_label_strn_parse(struct aa_label *base, const char *str, size_t n, gfp_t gfp, bool create, bool force_stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8158d880)
Location: security/apparmor/label.c:1882
Inline: False
Direct callers:
  - security/apparmor/secid.c:apparmor_secctx_to_secid
  - security/apparmor/label.c:aa_label_parse
  - security/apparmor/net.c:apparmor_secmark_check
```
**Symbols:**

```
ffffffff8158d880-ffffffff8158deec: aa_label_strn_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct aa_label *aa_label_strn_parse(struct aa_label *base, const char *str, size_t n, gfp_t gfp, bool create, bool force_stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/label.c (0)
Location: security/apparmor/label.c:1891
Inline: False
Direct callers:
  - security/apparmor/secid.c:apparmor_secctx_to_secid
  - security/apparmor/label.c:aa_label_parse
  - security/apparmor/net.c:apparmor_secmark_check
```
**Symbols:**

```
ffffffff81e896fa-ffffffff81e8970f: aa_label_strn_parse.cold (STB_LOCAL)
ffffffff8162e550-ffffffff8162ec89: aa_label_strn_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct aa_label *aa_label_strn_parse(struct aa_label *base, const char *str, size_t n, gfp_t gfp, bool create, bool force_stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff816e3120)
Location: security/apparmor/label.c:1885
Inline: False
Direct callers:
  - security/apparmor/secid.c:apparmor_secctx_to_secid
  - security/apparmor/label.c:aa_label_parse
  - security/apparmor/net.c:apparmor_secmark_check
```
**Symbols:**

```
ffffffff816e3120-ffffffff816e3855: aa_label_strn_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct aa_label *aa_label_strn_parse(struct aa_label *base, const char *str, size_t n, gfp_t gfp, bool create, bool force_stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8171c690)
Location: security/apparmor/label.c:1885
Inline: False
Direct callers:
  - security/apparmor/secid.c:apparmor_secctx_to_secid
  - security/apparmor/label.c:aa_label_parse
  - security/apparmor/net.c:apparmor_secmark_check
```
**Symbols:**

```
ffffffff8171c690-ffffffff8171cdb3: aa_label_strn_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct aa_label *aa_label_strn_parse(struct aa_label *base, const char *str, size_t n, gfp_t gfp, bool create, bool force_stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8175b0e0)
Location: security/apparmor/label.c:1891
Inline: False
Direct callers:
  - security/apparmor/secid.c:apparmor_secctx_to_secid
  - security/apparmor/label.c:aa_label_parse
  - security/apparmor/net.c:apparmor_secmark_check
```
**Symbols:**

```
ffffffff8175b0e0-ffffffff8175b802: aa_label_strn_parse (STB_GLOBAL)
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
struct aa_label *aa_label_strn_parse(struct aa_label *base, const char *str, size_t n, gfp_t gfp, bool create, bool force_stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffff8000105a4ba0)
Location: security/apparmor/label.c:1885
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_parse
```
**Symbols:**

```
ffff8000105a4ba0-ffff8000105a4fd4: aa_label_strn_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct aa_label *aa_label_strn_parse(struct aa_label *base, const char *str, size_t n, gfp_t gfp, bool create, bool force_stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (c0754dcc)
Location: security/apparmor/label.c:1885
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_parse
```
**Symbols:**

```
c0754dcc-c0755270: aa_label_strn_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct aa_label *aa_label_strn_parse(struct aa_label *base, const char *str, size_t n, gfp_t gfp, bool create, bool force_stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (c0000000007209b0)
Location: security/apparmor/label.c:1885
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_parse
```
**Symbols:**

```
c0000000007209b0-c000000000720f90: aa_label_strn_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct aa_label *aa_label_strn_parse(struct aa_label *base, const char *str, size_t n, gfp_t gfp, bool create, bool force_stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffe0003eeae6)
Location: security/apparmor/label.c:1885
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_parse
```
**Symbols:**

```
ffffffe0003eeae6-ffffffe0003eee1e: aa_label_strn_parse (STB_GLOBAL)
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
struct aa_label *aa_label_strn_parse(struct aa_label *base, const char *str, size_t n, gfp_t gfp, bool create, bool force_stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814a5cb0)
Location: security/apparmor/label.c:1885
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_parse
```
**Symbols:**

```
ffffffff814a5cb0-ffffffff814a6125: aa_label_strn_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct aa_label *aa_label_strn_parse(struct aa_label *base, const char *str, size_t n, gfp_t gfp, bool create, bool force_stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814966d0)
Location: security/apparmor/label.c:1885
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_parse
```
**Symbols:**

```
ffffffff814966d0-ffffffff81496b45: aa_label_strn_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct aa_label *aa_label_strn_parse(struct aa_label *base, const char *str, size_t n, gfp_t gfp, bool create, bool force_stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814a1d50)
Location: security/apparmor/label.c:1885
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_parse
```
**Symbols:**

```
ffffffff814a1d50-ffffffff814a21c5: aa_label_strn_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct aa_label *aa_label_strn_parse(struct aa_label *base, const char *str, size_t n, gfp_t gfp, bool create, bool force_stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814ba510)
Location: security/apparmor/label.c:1885
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_parse
```
**Symbols:**

```
ffffffff814ba510-ffffffff814ba985: aa_label_strn_parse (STB_GLOBAL)
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
