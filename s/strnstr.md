# Function: <code>strnstr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
char *strnstr(const char *s1, const char *s2, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff813f1e00)
Location: lib/string.c:835
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:regex_match_middle
  - security/apparmor/policy.c:__lookupn_profile
```
**Symbols:**

```
ffffffff813f1e00-ffffffff813f1e4e: strnstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
char *strnstr(const char *s1, const char *s2, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff814387a0)
Location: lib/string.c:832
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:regex_match_middle
  - security/apparmor/policy.c:__lookupn_profile
```
**Symbols:**

```
ffffffff814387a0-ffffffff814387ee: strnstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
char *strnstr(const char *s1, const char *s2, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81455790)
Location: lib/string.c:832
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:regex_match_middle
  - security/apparmor/policy.c:__lookupn_profile
```
**Symbols:**

```
ffffffff81455790-ffffffff814557de: strnstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
char *strnstr(const char *s1, const char *s2, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff818f71f0)
Location: lib/string.c:858
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:regex_match_middle
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
```
**Symbols:**

```
ffffffff818f71f0-ffffffff818f7252: strnstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
char *strnstr(const char *s1, const char *s2, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff8197dbf0)
Location: lib/string.c:925
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:regex_match_middle
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
```
**Symbols:**

```
ffffffff8197dbf0-ffffffff8197dc52: strnstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
char *strnstr(const char *s1, const char *s2, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff819da0e0)
Location: lib/string.c:925
Inline: False
Direct callers:
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
```
**Symbols:**

```
ffffffff819da0e0-ffffffff819da147: strnstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
char *strnstr(const char *s1, const char *s2, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81a12300)
Location: lib/string.c:926
Inline: False
Direct callers:
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
```
**Symbols:**

```
ffffffff81a12300-ffffffff81a12367: strnstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
char *strnstr(const char *s1, const char *s2, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81a81780)
Location: lib/string.c:988
Inline: False
Direct callers:
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
```
**Symbols:**

```
ffffffff81a81780-ffffffff81a817ea: strnstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
char *strnstr(const char *s1, const char *s2, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81ab8850)
Location: lib/string.c:969
Inline: False
Direct callers:
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
```
**Symbols:**

```
ffffffff81ab8850-ffffffff81ab88ba: strnstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
char *strnstr(const char *s1, const char *s2, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff815f34b0)
Location: lib/string.c:1026
Inline: False
Direct callers:
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
```
**Symbols:**

```
ffffffff815f34b0-ffffffff815f3518: strnstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
char *strnstr(const char *s1, const char *s2, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81617b50)
Location: lib/string.c:1022
Inline: False
Direct callers:
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
```
**Symbols:**

```
ffffffff81617b50-ffffffff81617bac: strnstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
char *strnstr(const char *s1, const char *s2, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff815fb1b0)
Location: lib/string.c:1022
Inline: False
Direct callers:
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
```
**Symbols:**

```
ffffffff815fb1b0-ffffffff815fb1fd: strnstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
char *strnstr(const char *s1, const char *s2, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81668a70)
Location: lib/string.c:1038
Inline: False
Direct callers:
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
```
**Symbols:**

```
ffffffff81668a70-ffffffff81668acc: strnstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
char *strnstr(const char *s1, const char *s2, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81782220)
Location: lib/string.c:851
Inline: False
Direct callers:
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
```
**Symbols:**

```
ffffffff81782220-ffffffff817822d2: strnstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
char *strnstr(const char *s1, const char *s2, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff8203f090)
Location: lib/string.c:777
Inline: False
Direct callers:
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
```
**Symbols:**

```
ffffffff8203f090-ffffffff8203f12d: strnstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
char *strnstr(const char *s1, const char *s2, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff820bd500)
Location: lib/string.c:775
Inline: False
Direct callers:
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
```
**Symbols:**

```
ffffffff820bd500-ffffffff820bd59d: strnstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
char *strnstr(const char *s1, const char *s2, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff82197e00)
Location: lib/string.c:760
Inline: False
Direct callers:
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
```
**Symbols:**

```
ffffffff82197e00-ffffffff82197e9d: strnstr (STB_GLOBAL)
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
char *strnstr(const char *s1, const char *s2, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffff800010d93010)
Location: lib/string.c:969
Inline: False
Direct callers:
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
```
**Symbols:**

```
ffff800010d93010-ffff800010d9309c: strnstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
char *strnstr(const char *s1, const char *s2, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (c0e8f534)
Location: lib/string.c:969
Inline: False
Direct callers:
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
```
**Symbols:**

```
c0e8f534-c0e8f5a8: strnstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
char *strnstr(const char *s1, const char *s2, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (c000000000ed7060)
Location: lib/string.c:969
Inline: False
Direct callers:
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
```
**Symbols:**

```
c000000000ed7060-c000000000ed7128: strnstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
char *strnstr(const char *s1, const char *s2, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffe0008bcea2)
Location: lib/string.c:969
Inline: False
Direct callers:
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
```
**Symbols:**

```
ffffffe0008bcea2-ffffffe0008bcf04: strnstr (STB_GLOBAL)
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
char *strnstr(const char *s1, const char *s2, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81a576a0)
Location: lib/string.c:969
Inline: False
Direct callers:
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
```
**Symbols:**

```
ffffffff81a576a0-ffffffff81a5770a: strnstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
char *strnstr(const char *s1, const char *s2, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81a14780)
Location: lib/string.c:969
Inline: False
Direct callers:
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
```
**Symbols:**

```
ffffffff81a14780-ffffffff81a147ea: strnstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
char *strnstr(const char *s1, const char *s2, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81ac3a90)
Location: lib/string.c:969
Inline: False
Direct callers:
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
```
**Symbols:**

```
ffffffff81ac3a90-ffffffff81ac3afa: strnstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
char *strnstr(const char *s1, const char *s2, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81acff60)
Location: lib/string.c:969
Inline: False
Direct callers:
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy.c:__lookupn_profile
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
  - security/apparmor/policy_ns.c:__aa_lookupn_ns
```
**Symbols:**

```
ffffffff81acff60-ffffffff81acffca: strnstr (STB_GLOBAL)
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
