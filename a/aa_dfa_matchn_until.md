# Function: <code>aa_dfa_matchn_until</code>

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
unsigned int aa_dfa_matchn_until(struct aa_dfa *dfa, unsigned int start, const char *str, int n, const char **retpos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff814369a0)
Location: security/apparmor/match.c:576
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
```
**Symbols:**

```
ffffffff814369a0-ffffffff81436ab3: aa_dfa_matchn_until (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int aa_dfa_matchn_until(struct aa_dfa *dfa, unsigned int start, const char *str, int n, const char **retpos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff81453600)
Location: security/apparmor/match.c:576
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
```
**Symbols:**

```
ffffffff81453600-ffffffff81453713: aa_dfa_matchn_until (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned int aa_dfa_matchn_until(struct aa_dfa *dfa, unsigned int start, const char *str, int n, const char **retpos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff81480f90)
Location: security/apparmor/match.c:572
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
```
**Symbols:**

```
ffffffff81480f90-ffffffff8148109d: aa_dfa_matchn_until (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int aa_dfa_matchn_until(struct aa_dfa *dfa, unsigned int start, const char *str, int n, const char **retpos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff8149ac90)
Location: security/apparmor/match.c:587
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
```
**Symbols:**

```
ffffffff8149ac90-ffffffff8149ad9d: aa_dfa_matchn_until (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int aa_dfa_matchn_until(struct aa_dfa *dfa, unsigned int start, const char *str, int n, const char **retpos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff814f37e0)
Location: security/apparmor/match.c:628
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
```
**Symbols:**

```
ffffffff814f37e0-ffffffff814f38fb: aa_dfa_matchn_until (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int aa_dfa_matchn_until(struct aa_dfa *dfa, unsigned int start, const char *str, int n, const char **retpos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff815109b0)
Location: security/apparmor/match.c:628
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
```
**Symbols:**

```
ffffffff815109b0-ffffffff81510acb: aa_dfa_matchn_until (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int aa_dfa_matchn_until(struct aa_dfa *dfa, unsigned int start, const char *str, int n, const char **retpos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff81517360)
Location: security/apparmor/match.c:628
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
```
**Symbols:**

```
ffffffff81517360-ffffffff8151747b: aa_dfa_matchn_until (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned int aa_dfa_matchn_until(struct aa_dfa *dfa, unsigned int start, const char *str, int n, const char **retpos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff81575360)
Location: security/apparmor/match.c:628
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
```
**Symbols:**

```
ffffffff81575360-ffffffff8157547b: aa_dfa_matchn_until (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int aa_dfa_matchn_until(struct aa_dfa *dfa, unsigned int start, const char *str, int n, const char **retpos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff81612e10)
Location: security/apparmor/match.c:626
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
```
**Symbols:**

```
ffffffff81612e10-ffffffff81612f3f: aa_dfa_matchn_until (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int aa_dfa_matchn_until(struct aa_dfa *dfa, unsigned int start, const char *str, int n, const char **retpos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff816c5a20)
Location: security/apparmor/match.c:626
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
```
**Symbols:**

```
ffffffff816c5a20-ffffffff816c5b4f: aa_dfa_matchn_until (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int aa_dfa_matchn_until(struct aa_dfa *dfa, unsigned int start, const char *str, int n, const char **retpos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff816fe800)
Location: security/apparmor/match.c:582
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
```
**Symbols:**

```
ffffffff816fe800-ffffffff816fe92f: aa_dfa_matchn_until (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int aa_dfa_matchn_until(struct aa_dfa *dfa, unsigned int start, const char *str, int n, const char **retpos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff8173bd90)
Location: security/apparmor/match.c:582
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
```
**Symbols:**

```
ffffffff8173bd90-ffffffff8173bebf: aa_dfa_matchn_until (STB_GLOBAL)
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
unsigned int aa_dfa_matchn_until(struct aa_dfa *dfa, unsigned int start, const char *str, int n, const char **retpos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffff800010590e60)
Location: security/apparmor/match.c:587
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
```
**Symbols:**

```
ffff800010590e60-ffff800010590fb8: aa_dfa_matchn_until (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
unsigned int aa_dfa_matchn_until(struct aa_dfa *dfa, unsigned int start, const char *str, int n, const char **retpos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (c0741b68)
Location: security/apparmor/match.c:587
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
```
**Symbols:**

```
c0741b68-c0741c80: aa_dfa_matchn_until (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
unsigned int aa_dfa_matchn_until(struct aa_dfa *dfa, unsigned int start, const char *str, int n, const char **retpos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (c0000000007047f0)
Location: security/apparmor/match.c:587
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
```
**Symbols:**

```
c0000000007047f0-c000000000704970: aa_dfa_matchn_until (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
unsigned int aa_dfa_matchn_until(struct aa_dfa *dfa, unsigned int start, const char *str, int n, const char **retpos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffe0003de90e)
Location: security/apparmor/match.c:587
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
```
**Symbols:**

```
ffffffe0003de90e-ffffffe0003dea6a: aa_dfa_matchn_until (STB_GLOBAL)
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
unsigned int aa_dfa_matchn_until(struct aa_dfa *dfa, unsigned int start, const char *str, int n, const char **retpos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff81493270)
Location: security/apparmor/match.c:587
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
```
**Symbols:**

```
ffffffff81493270-ffffffff8149337d: aa_dfa_matchn_until (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int aa_dfa_matchn_until(struct aa_dfa *dfa, unsigned int start, const char *str, int n, const char **retpos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff81483c90)
Location: security/apparmor/match.c:587
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
```
**Symbols:**

```
ffffffff81483c90-ffffffff81483d9d: aa_dfa_matchn_until (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int aa_dfa_matchn_until(struct aa_dfa *dfa, unsigned int start, const char *str, int n, const char **retpos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff8148f310)
Location: security/apparmor/match.c:587
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
```
**Symbols:**

```
ffffffff8148f310-ffffffff8148f41d: aa_dfa_matchn_until (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int aa_dfa_matchn_until(struct aa_dfa *dfa, unsigned int start, const char *str, int n, const char **retpos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff814a7220)
Location: security/apparmor/match.c:587
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
```
**Symbols:**

```
ffffffff814a7220-ffffffff814a732d: aa_dfa_matchn_until (STB_GLOBAL)
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
