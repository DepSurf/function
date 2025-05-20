# Function: <code>aa_lookupn_profile</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct aa_profile *aa_lookupn_profile(struct aa_ns *ns, const char *hname, size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff8137fff0)
Location: security/apparmor/policy.c:507
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_lookup_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
```
**Symbols:**

```
ffffffff8137fff0-ffffffff81380300: aa_lookupn_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct aa_profile *aa_lookupn_profile(struct aa_ns *ns, const char *hname, size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff813b99b0)
Location: security/apparmor/policy.c:532
Inline: True
Direct callers:
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_lookup_profile
```
**Symbols:**

```
ffffffff813b99b0-ffffffff813b9cb7: aa_lookupn_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct aa_profile *aa_lookupn_profile(struct aa_ns *ns, const char *hname, size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff813d0d70)
Location: security/apparmor/policy.c:533
Inline: True
Direct callers:
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_lookup_profile
```
**Symbols:**

```
ffffffff813d0d70-ffffffff813d1077: aa_lookupn_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct aa_profile *aa_lookupn_profile(struct aa_ns *ns, const char *hname, size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff813e3ed0)
Location: security/apparmor/policy.c:430
Inline: True
Direct callers:
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_lookup_profile
```
**Symbols:**

```
ffffffff813e3ed0-ffffffff813e3ff7: aa_lookupn_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct aa_profile *aa_lookupn_profile(struct aa_ns *ns, const char *hname, size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff8140acd0)
Location: security/apparmor/policy.c:430
Inline: True
Direct callers:
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_lookup_profile
```
**Symbols:**

```
ffffffff8140acd0-ffffffff8140aec0: aa_lookupn_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct aa_profile *aa_lookupn_profile(struct aa_ns *ns, const char *hname, size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff8143c5a0)
Location: security/apparmor/policy.c:435
Inline: True
Direct callers:
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_lookup_profile
```
**Symbols:**

```
ffffffff8143c5a0-ffffffff8143c77e: aa_lookupn_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct aa_profile *aa_lookupn_profile(struct aa_ns *ns, const char *hname, size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff81459410)
Location: security/apparmor/policy.c:435
Inline: True
Direct callers:
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_lookup_profile
```
**Symbols:**

```
ffffffff81459410-ffffffff814595f1: aa_lookupn_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct aa_profile *aa_lookupn_profile(struct aa_ns *ns, const char *hname, size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff81486b90)
Location: security/apparmor/policy.c:430
Inline: True
Direct callers:
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_lookup_profile
```
**Symbols:**

```
ffffffff81486b90-ffffffff81486cfe: aa_lookupn_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct aa_profile *aa_lookupn_profile(struct aa_ns *ns, const char *hname, size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff814a0a40)
Location: security/apparmor/policy.c:430
Inline: True
Direct callers:
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_lookup_profile
```
**Symbols:**

```
ffffffff814a0a40-ffffffff814a0bae: aa_lookupn_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct aa_profile *aa_lookupn_profile(struct aa_ns *ns, const char *hname, size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff814fab30)
Location: security/apparmor/policy.c:434
Inline: True
Direct callers:
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_lookup_profile
```
**Symbols:**

```
ffffffff814fab30-ffffffff814fabe1: aa_lookupn_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct aa_profile *aa_lookupn_profile(struct aa_ns *ns, const char *hname, size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff815178c0)
Location: security/apparmor/policy.c:434
Inline: True
Direct callers:
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_lookup_profile
```
**Symbols:**

```
ffffffff815178c0-ffffffff81517adc: aa_lookupn_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct aa_profile *aa_lookupn_profile(struct aa_ns *ns, const char *hname, size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff8151e170)
Location: security/apparmor/policy.c:434
Inline: True
Direct callers:
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_lookup_profile
```
**Symbols:**

```
ffffffff8151e170-ffffffff8151e36b: aa_lookupn_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct aa_profile *aa_lookupn_profile(struct aa_ns *ns, const char *hname, size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff8157c2c0)
Location: security/apparmor/policy.c:434
Inline: True
Direct callers:
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_lookup_profile
```
**Symbols:**

```
ffffffff8157c2c0-ffffffff8157c4bb: aa_lookupn_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct aa_profile *aa_lookupn_profile(struct aa_ns *ns, const char *hname, size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff8161aa20)
Location: security/apparmor/policy.c:477
Inline: True
Direct callers:
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_lookup_profile
```
**Symbols:**

```
ffffffff8161aa20-ffffffff8161aaed: aa_lookupn_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct aa_profile *aa_lookupn_profile(struct aa_ns *ns, const char *hname, size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff816cda30)
Location: security/apparmor/policy.c:534
Inline: True
Direct callers:
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_lookup_profile
```
**Symbols:**

```
ffffffff816cda30-ffffffff816cdafd: aa_lookupn_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct aa_profile *aa_lookupn_profile(struct aa_ns *ns, const char *hname, size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff81706690)
Location: security/apparmor/policy.c:570
Inline: True
Direct callers:
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_lookup_profile
```
**Symbols:**

```
ffffffff81706690-ffffffff81706759: aa_lookupn_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct aa_profile *aa_lookupn_profile(struct aa_ns *ns, const char *hname, size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff81744110)
Location: security/apparmor/policy.c:597
Inline: True
Direct callers:
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_lookup_profile
```
**Symbols:**

```
ffffffff81744110-ffffffff817441d9: aa_lookupn_profile (STB_GLOBAL)
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
struct aa_profile *aa_lookupn_profile(struct aa_ns *ns, const char *hname, size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffff8000105967b8)
Location: security/apparmor/policy.c:430
Inline: True
Direct callers:
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_lookup_profile
```
**Symbols:**

```
ffff8000105967b8-ffff8000105968f0: aa_lookupn_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct aa_profile *aa_lookupn_profile(struct aa_ns *ns, const char *hname, size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (c0747884)
Location: security/apparmor/policy.c:430
Inline: True
Direct callers:
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_lookup_profile
```
**Symbols:**

```
c0747884-c07479a8: aa_lookupn_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct aa_profile *aa_lookupn_profile(struct aa_ns *ns, const char *hname, size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (c00000000070c540)
Location: security/apparmor/policy.c:430
Inline: True
Direct callers:
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_lookup_profile
```
**Symbols:**

```
c00000000070c540-c00000000070c7a4: aa_lookupn_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct aa_profile *aa_lookupn_profile(struct aa_ns *ns, const char *hname, size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffe0003e356c)
Location: security/apparmor/policy.c:430
Inline: True
Direct callers:
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_lookup_profile
```
**Symbols:**

```
ffffffe0003e356c-ffffffe0003e369e: aa_lookupn_profile (STB_GLOBAL)
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
struct aa_profile *aa_lookupn_profile(struct aa_ns *ns, const char *hname, size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff81499020)
Location: security/apparmor/policy.c:430
Inline: True
Direct callers:
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_lookup_profile
```
**Symbols:**

```
ffffffff81499020-ffffffff8149918e: aa_lookupn_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct aa_profile *aa_lookupn_profile(struct aa_ns *ns, const char *hname, size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff81489a40)
Location: security/apparmor/policy.c:430
Inline: True
Direct callers:
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_lookup_profile
```
**Symbols:**

```
ffffffff81489a40-ffffffff81489bae: aa_lookupn_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct aa_profile *aa_lookupn_profile(struct aa_ns *ns, const char *hname, size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff814950c0)
Location: security/apparmor/policy.c:430
Inline: True
Direct callers:
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_lookup_profile
```
**Symbols:**

```
ffffffff814950c0-ffffffff8149522e: aa_lookupn_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct aa_profile *aa_lookupn_profile(struct aa_ns *ns, const char *hname, size_t n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff814ad100)
Location: security/apparmor/policy.c:430
Inline: True
Direct callers:
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_lookup_profile
```
**Symbols:**

```
ffffffff814ad100-ffffffff814ad291: aa_lookupn_profile (STB_GLOBAL)
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
