# Function: <code>fqlookupn_profile</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct aa_profile *fqlookupn_profile(struct aa_label *base, struct aa_label *currentbase, const char *str, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813db800)
Location: security/apparmor/label.c:1860
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_parse
  - security/apparmor/label.c:aa_label_parse
```
**Symbols:**

```
ffffffff813db800-ffffffff813db852: fqlookupn_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct aa_profile *fqlookupn_profile(struct aa_label *base, struct aa_label *currentbase, const char *str, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813ec800)
Location: security/apparmor/label.c:1833
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_parse
  - security/apparmor/label.c:aa_label_parse
```
**Symbols:**

```
ffffffff813ec800-ffffffff813ec859: fqlookupn_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct aa_profile *fqlookupn_profile(struct aa_label *base, struct aa_label *currentbase, const char *str, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81414190)
Location: security/apparmor/label.c:1833
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_parse
  - security/apparmor/label.c:aa_label_parse
```
**Symbols:**

```
ffffffff81414190-ffffffff814141e9: fqlookupn_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct aa_profile *fqlookupn_profile(struct aa_label *base, struct aa_label *currentbase, const char *str, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81446510)
Location: security/apparmor/label.c:1835
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
```
**Symbols:**

```
ffffffff81446510-ffffffff81446562: fqlookupn_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct aa_profile *fqlookupn_profile(struct aa_label *base, struct aa_label *currentbase, const char *str, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81463430)
Location: security/apparmor/label.c:1836
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
```
**Symbols:**

```
ffffffff81463430-ffffffff81463482: fqlookupn_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct aa_profile *fqlookupn_profile(struct aa_label *base, struct aa_label *currentbase, const char *str, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81490700)
Location: security/apparmor/label.c:1832
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
```
**Symbols:**

```
ffffffff81490700-ffffffff81490754: fqlookupn_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct aa_profile *fqlookupn_profile(struct aa_label *base, struct aa_label *currentbase, const char *str, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814aa5c0)
Location: security/apparmor/label.c:1861
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
```
**Symbols:**

```
ffffffff814aa5c0-ffffffff814aa614: fqlookupn_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8150c6d3)
Location: security/apparmor/label.c:1858
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
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
In security/apparmor/label.c (ffffffff81529570)
Location: security/apparmor/label.c:1858
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
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
In security/apparmor/label.c (ffffffff8152f723)
Location: security/apparmor/label.c:1858
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
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
In security/apparmor/label.c (ffffffff8158db43)
Location: security/apparmor/label.c:1858
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
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
In security/apparmor/label.c (ffffffff8162e7f5)
Location: security/apparmor/label.c:1867
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
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
In security/apparmor/label.c (ffffffff816e33b5)
Location: security/apparmor/label.c:1861
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
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
In security/apparmor/label.c (ffffffff8171c927)
Location: security/apparmor/label.c:1861
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
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
In security/apparmor/label.c (ffffffff8175b376)
Location: security/apparmor/label.c:1867
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
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
struct aa_profile *fqlookupn_profile(struct aa_label *base, struct aa_label *currentbase, const char *str, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffff8000105a12b8)
Location: security/apparmor/label.c:1861
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
```
**Symbols:**

```
ffff8000105a12b8-ffff8000105a1328: fqlookupn_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct aa_profile *fqlookupn_profile(struct aa_label *base, struct aa_label *currentbase, const char *str, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (c0751c00)
Location: security/apparmor/label.c:1861
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
```
**Symbols:**

```
c0751c00-c0751c64: fqlookupn_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct aa_profile *fqlookupn_profile(struct aa_label *base, struct aa_label *currentbase, const char *str, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (c00000000071bab0)
Location: security/apparmor/label.c:1861
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
```
**Symbols:**

```
c00000000071bab0-c00000000071bb50: fqlookupn_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct aa_profile *fqlookupn_profile(struct aa_label *base, struct aa_label *currentbase, const char *str, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffe0003ebf06)
Location: security/apparmor/label.c:1861
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
```
**Symbols:**

```
ffffffe0003ebf06-ffffffe0003ebf6c: fqlookupn_profile (STB_LOCAL)
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
struct aa_profile *fqlookupn_profile(struct aa_label *base, struct aa_label *currentbase, const char *str, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814a2ba0)
Location: security/apparmor/label.c:1861
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
```
**Symbols:**

```
ffffffff814a2ba0-ffffffff814a2bf4: fqlookupn_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct aa_profile *fqlookupn_profile(struct aa_label *base, struct aa_label *currentbase, const char *str, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814935c0)
Location: security/apparmor/label.c:1861
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
```
**Symbols:**

```
ffffffff814935c0-ffffffff81493614: fqlookupn_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct aa_profile *fqlookupn_profile(struct aa_label *base, struct aa_label *currentbase, const char *str, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8149ec40)
Location: security/apparmor/label.c:1861
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
```
**Symbols:**

```
ffffffff8149ec40-ffffffff8149ec94: fqlookupn_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct aa_profile *fqlookupn_profile(struct aa_label *base, struct aa_label *currentbase, const char *str, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814b7270)
Location: security/apparmor/label.c:1861
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
```
**Symbols:**

```
ffffffff814b7270-ffffffff814b72c4: fqlookupn_profile (STB_LOCAL)
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
