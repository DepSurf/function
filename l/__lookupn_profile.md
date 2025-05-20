# Function: <code>__lookupn_profile</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct aa_profile *__lookupn_profile(struct aa_policy *base, const char *hname, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff8137f020)
Location: security/apparmor/policy.c:470
Inline: False
Direct callers:
  - security/apparmor/policy.c:__lookup_replace
  - security/apparmor/policy.c:aa_lookupn_profile
  - security/apparmor/policy.c:aa_remove_profiles
```
**Symbols:**

```
ffffffff8137f020-ffffffff8137f12f: __lookupn_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct aa_profile *__lookupn_profile(struct aa_policy *base, const char *hname, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff813b8790)
Location: security/apparmor/policy.c:495
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:__lookup_replace
```
**Symbols:**

```
ffffffff813b8790-ffffffff813b889f: __lookupn_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct aa_profile *__lookupn_profile(struct aa_policy *base, const char *hname, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff813cfb30)
Location: security/apparmor/policy.c:496
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:__lookup_replace
```
**Symbols:**

```
ffffffff813cfb30-ffffffff813cfc3f: __lookupn_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct aa_profile *__lookupn_profile(struct aa_policy *base, const char *hname, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff813e3730)
Location: security/apparmor/policy.c:393
Inline: False
Direct callers:
  - security/apparmor/policy.c:__lookup_profile
```
**Symbols:**

```
ffffffff813e3730-ffffffff813e3830: __lookupn_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct aa_profile *__lookupn_profile(struct aa_policy *base, const char *hname, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff8140a520)
Location: security/apparmor/policy.c:393
Inline: False
Direct callers:
  - security/apparmor/policy.c:__lookup_profile
```
**Symbols:**

```
ffffffff8140a520-ffffffff8140a620: __lookupn_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct aa_profile *__lookupn_profile(struct aa_policy *base, const char *hname, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff8143bc90)
Location: security/apparmor/policy.c:398
Inline: False
Direct callers:
  - security/apparmor/policy.c:__lookup_profile
```
**Symbols:**

```
ffffffff8143bc90-ffffffff8143bda9: __lookupn_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct aa_profile *__lookupn_profile(struct aa_policy *base, const char *hname, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff81458b00)
Location: security/apparmor/policy.c:398
Inline: False
Direct callers:
  - security/apparmor/policy.c:__lookup_profile
```
**Symbols:**

```
ffffffff81458b00-ffffffff81458c19: __lookupn_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct aa_profile *__lookupn_profile(struct aa_policy *base, const char *hname, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff81486280)
Location: security/apparmor/policy.c:393
Inline: False
Direct callers:
  - security/apparmor/policy.c:__lookup_profile
```
**Symbols:**

```
ffffffff81486280-ffffffff81486399: __lookupn_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct aa_profile *__lookupn_profile(struct aa_policy *base, const char *hname, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff814a0130)
Location: security/apparmor/policy.c:393
Inline: False
Direct callers:
  - security/apparmor/policy.c:__lookup_profile
```
**Symbols:**

```
ffffffff814a0130-ffffffff814a0249: __lookupn_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct aa_profile *__lookupn_profile(struct aa_policy *base, const char *hname, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff814f9bd0)
Location: security/apparmor/policy.c:397
Inline: False
Direct callers:
  - security/apparmor/policy.c:__lookup_profile
```
**Symbols:**

```
ffffffff814f9bd0-ffffffff814f9ce9: __lookupn_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct aa_profile *__lookupn_profile(struct aa_policy *base, const char *hname, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff81516d00)
Location: security/apparmor/policy.c:397
Inline: False
Direct callers:
  - security/apparmor/policy.c:__lookup_profile
```
**Symbols:**

```
ffffffff81516d00-ffffffff81516e19: __lookupn_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct aa_profile *__lookupn_profile(struct aa_policy *base, const char *hname, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff8151d5b0)
Location: security/apparmor/policy.c:397
Inline: False
Direct callers:
  - security/apparmor/policy.c:__lookup_profile
```
**Symbols:**

```
ffffffff8151d5b0-ffffffff8151d6c6: __lookupn_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct aa_profile *__lookupn_profile(struct aa_policy *base, const char *hname, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff8157b6a0)
Location: security/apparmor/policy.c:397
Inline: False
Direct callers:
  - security/apparmor/policy.c:__lookup_profile
```
**Symbols:**

```
ffffffff8157b6a0-ffffffff8157b7b6: __lookupn_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct aa_profile *__lookupn_profile(struct aa_policy *base, const char *hname, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff81619a80)
Location: security/apparmor/policy.c:440
Inline: False
Direct callers:
  - security/apparmor/policy.c:__lookup_profile
```
**Symbols:**

```
ffffffff81619a80-ffffffff81619bb1: __lookupn_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct aa_profile *__lookupn_profile(struct aa_policy *base, const char *hname, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff816cc9a0)
Location: security/apparmor/policy.c:497
Inline: False
Direct callers:
  - security/apparmor/policy.c:__lookup_profile
```
**Symbols:**

```
ffffffff816cc9a0-ffffffff816ccad1: __lookupn_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct aa_profile *__lookupn_profile(struct aa_policy *base, const char *hname, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff81705440)
Location: security/apparmor/policy.c:533
Inline: False
Direct callers:
  - security/apparmor/policy.c:__lookup_profile
```
**Symbols:**

```
ffffffff81705440-ffffffff81705571: __lookupn_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct aa_profile *__lookupn_profile(struct aa_policy *base, const char *hname, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff81742d40)
Location: security/apparmor/policy.c:560
Inline: False
Direct callers:
  - security/apparmor/policy.c:__lookup_profile
```
**Symbols:**

```
ffffffff81742d40-ffffffff81742e71: __lookupn_profile (STB_LOCAL)
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
struct aa_profile *__lookupn_profile(struct aa_policy *base, const char *hname, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffff800010595f20)
Location: security/apparmor/policy.c:393
Inline: False
Direct callers:
  - security/apparmor/policy.c:__lookup_profile
```
**Symbols:**

```
ffff800010595f20-ffff800010596068: __lookupn_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct aa_profile *__lookupn_profile(struct aa_policy *base, const char *hname, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (c0747018)
Location: security/apparmor/policy.c:393
Inline: False
Direct callers:
  - security/apparmor/policy.c:__lookup_profile
```
**Symbols:**

```
c0747018-c0747150: __lookupn_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct aa_profile *__lookupn_profile(struct aa_policy *base, const char *hname, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (c00000000070b710)
Location: security/apparmor/policy.c:393
Inline: False
Direct callers:
  - security/apparmor/policy.c:__lookup_profile
```
**Symbols:**

```
c00000000070b710-c00000000070b8e8: __lookupn_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct aa_profile *__lookupn_profile(struct aa_policy *base, const char *hname, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffe0003e2fe4)
Location: security/apparmor/policy.c:393
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:__lookup_replace
```
**Symbols:**

```
ffffffe0003e2fe4-ffffffe0003e30e4: __lookupn_profile (STB_LOCAL)
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
struct aa_profile *__lookupn_profile(struct aa_policy *base, const char *hname, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff81498710)
Location: security/apparmor/policy.c:393
Inline: False
Direct callers:
  - security/apparmor/policy.c:__lookup_profile
```
**Symbols:**

```
ffffffff81498710-ffffffff81498829: __lookupn_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct aa_profile *__lookupn_profile(struct aa_policy *base, const char *hname, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff81489130)
Location: security/apparmor/policy.c:393
Inline: False
Direct callers:
  - security/apparmor/policy.c:__lookup_profile
```
**Symbols:**

```
ffffffff81489130-ffffffff81489249: __lookupn_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct aa_profile *__lookupn_profile(struct aa_policy *base, const char *hname, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff814947b0)
Location: security/apparmor/policy.c:393
Inline: False
Direct callers:
  - security/apparmor/policy.c:__lookup_profile
```
**Symbols:**

```
ffffffff814947b0-ffffffff814948c9: __lookupn_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct aa_profile *__lookupn_profile(struct aa_policy *base, const char *hname, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff814ac7d0)
Location: security/apparmor/policy.c:393
Inline: False
Direct callers:
  - security/apparmor/policy.c:__lookup_profile
```
**Symbols:**

```
ffffffff814ac7d0-ffffffff814ac8e9: __lookupn_profile (STB_LOCAL)
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
