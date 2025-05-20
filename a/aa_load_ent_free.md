# Function: <code>aa_load_ent_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void aa_load_ent_free(struct aa_load_ent *ent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_unpack.c (ffffffff81382770)
Location: security/apparmor/policy_unpack.c:805
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy_unpack.c:aa_unpack
```
**Symbols:**

```
ffffffff81382770-ffffffff813827fa: aa_load_ent_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void aa_load_ent_free(struct aa_load_ent *ent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_unpack.c (ffffffff813bc910)
Location: security/apparmor/policy_unpack.c:884
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy_unpack.c:aa_unpack
```
**Symbols:**

```
ffffffff813bc910-ffffffff813bca2d: aa_load_ent_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void aa_load_ent_free(struct aa_load_ent *ent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_unpack.c (ffffffff813d3d40)
Location: security/apparmor/policy_unpack.c:884
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy_unpack.c:aa_unpack
```
**Symbols:**

```
ffffffff813d3d40-ffffffff813d3e5d: aa_load_ent_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void aa_load_ent_free(struct aa_load_ent *ent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/policy_unpack.c (ffffffff813e6f9a)
Location: security/apparmor/policy_unpack.c:969
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_unpack
Direct callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy_unpack.c:aa_unpack
```
**Symbols:**

```
ffffffff813e6820-ffffffff813e68a1: aa_load_ent_free.part.16 (STB_LOCAL)
ffffffff813e6c00-ffffffff813e6c17: aa_load_ent_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void aa_load_ent_free(struct aa_load_ent *ent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_unpack.c (ffffffff8140dd80)
Location: security/apparmor/policy_unpack.c:969
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy_unpack.c:aa_unpack
```
**Symbols:**

```
ffffffff8140dd80-ffffffff8140de18: aa_load_ent_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void aa_load_ent_free(struct aa_load_ent *ent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_unpack.c (ffffffff8143f9f0)
Location: security/apparmor/policy_unpack.c:1016
Inline: True
Direct callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy_unpack.c:aa_unpack
```
**Symbols:**

```
ffffffff8143f9f0-ffffffff8143fa9b: aa_load_ent_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void aa_load_ent_free(struct aa_load_ent *ent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_unpack.c (ffffffff8145c8e0)
Location: security/apparmor/policy_unpack.c:984
Inline: True
Direct callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy_unpack.c:aa_unpack
```
**Symbols:**

```
ffffffff8145c8e0-ffffffff8145c98b: aa_load_ent_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void aa_load_ent_free(struct aa_load_ent *ent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_unpack.c (ffffffff81489e80)
Location: security/apparmor/policy_unpack.c:1006
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy_unpack.c:aa_unpack
```
**Symbols:**

```
ffffffff81489e80-ffffffff81489f32: aa_load_ent_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void aa_load_ent_free(struct aa_load_ent *ent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_unpack.c (ffffffff814a3d40)
Location: security/apparmor/policy_unpack.c:1010
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy_unpack.c:aa_unpack
```
**Symbols:**

```
ffffffff814a3d40-ffffffff814a3df2: aa_load_ent_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void aa_load_ent_free(struct aa_load_ent *ent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_unpack.c (ffffffff814feba0)
Location: security/apparmor/policy_unpack.c:1083
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy_unpack.c:aa_unpack
```
**Symbols:**

```
ffffffff814feba0-ffffffff814feca1: aa_load_ent_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void aa_load_ent_free(struct aa_load_ent *ent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_unpack.c (ffffffff8151be00)
Location: security/apparmor/policy_unpack.c:1083
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy_unpack.c:aa_unpack
```
**Symbols:**

```
ffffffff8151be00-ffffffff8151bf01: aa_load_ent_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void aa_load_ent_free(struct aa_load_ent *ent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_unpack.c (ffffffff815224d0)
Location: security/apparmor/policy_unpack.c:1083
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy_unpack.c:aa_unpack
```
**Symbols:**

```
ffffffff815224d0-ffffffff815225d1: aa_load_ent_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void aa_load_ent_free(struct aa_load_ent *ent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_unpack.c (ffffffff81580720)
Location: security/apparmor/policy_unpack.c:1083
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy_unpack.c:aa_unpack
```
**Symbols:**

```
ffffffff81580720-ffffffff81580821: aa_load_ent_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void aa_load_ent_free(struct aa_load_ent *ent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_unpack.c (ffffffff8161f900)
Location: security/apparmor/policy_unpack.c:1300
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy_unpack.c:aa_unpack
```
**Symbols:**

```
ffffffff8161f900-ffffffff8161fa20: aa_load_ent_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void aa_load_ent_free(struct aa_load_ent *ent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_unpack.c (ffffffff816d2d20)
Location: security/apparmor/policy_unpack.c:1291
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy_unpack.c:aa_unpack
```
**Symbols:**

```
ffffffff816d2d20-ffffffff816d2e40: aa_load_ent_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void aa_load_ent_free(struct aa_load_ent *ent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_unpack.c (ffffffff8170bd20)
Location: security/apparmor/policy_unpack.c:1320
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy_unpack.c:aa_unpack
```
**Symbols:**

```
ffffffff8170bd20-ffffffff8170be40: aa_load_ent_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void aa_load_ent_free(struct aa_load_ent *ent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_unpack.c (ffffffff81749a00)
Location: security/apparmor/policy_unpack.c:1354
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy_unpack.c:aa_unpack
```
**Symbols:**

```
ffffffff81749a00-ffffffff81749b20: aa_load_ent_free (STB_GLOBAL)
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
void aa_load_ent_free(struct aa_load_ent *ent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_unpack.c (ffff800010599ab0)
Location: security/apparmor/policy_unpack.c:1010
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy_unpack.c:aa_unpack
```
**Symbols:**

```
ffff800010599ab0-ffff800010599b70: aa_load_ent_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void aa_load_ent_free(struct aa_load_ent *ent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_unpack.c (c074ac20)
Location: security/apparmor/policy_unpack.c:1010
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy_unpack.c:aa_unpack
```
**Symbols:**

```
c074ac20-c074acec: aa_load_ent_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void aa_load_ent_free(struct aa_load_ent *ent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/policy_unpack.c (c00000000071111c)
Location: security/apparmor/policy_unpack.c:1010
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_unpack
Direct callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy_unpack.c:aa_unpack
```
**Symbols:**

```
c00000000070f390-c00000000070f4dc: aa_load_ent_free.part.0 (STB_LOCAL)
c000000000710db0-c000000000710dcc: aa_load_ent_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void aa_load_ent_free(struct aa_load_ent *ent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_unpack.c (ffffffe0003e61a2)
Location: security/apparmor/policy_unpack.c:1010
Inline: True
Direct callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy_unpack.c:aa_unpack
```
**Symbols:**

```
ffffffe0003e61a2-ffffffe0003e6240: aa_load_ent_free (STB_GLOBAL)
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
void aa_load_ent_free(struct aa_load_ent *ent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_unpack.c (ffffffff8149c320)
Location: security/apparmor/policy_unpack.c:1010
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy_unpack.c:aa_unpack
```
**Symbols:**

```
ffffffff8149c320-ffffffff8149c3d2: aa_load_ent_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void aa_load_ent_free(struct aa_load_ent *ent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_unpack.c (ffffffff8148cd40)
Location: security/apparmor/policy_unpack.c:1010
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy_unpack.c:aa_unpack
```
**Symbols:**

```
ffffffff8148cd40-ffffffff8148cdf2: aa_load_ent_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void aa_load_ent_free(struct aa_load_ent *ent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_unpack.c (ffffffff814983c0)
Location: security/apparmor/policy_unpack.c:1010
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy_unpack.c:aa_unpack
```
**Symbols:**

```
ffffffff814983c0-ffffffff81498472: aa_load_ent_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void aa_load_ent_free(struct aa_load_ent *ent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_unpack.c (ffffffff814b0510)
Location: security/apparmor/policy_unpack.c:1010
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy_unpack.c:aa_unpack
```
**Symbols:**

```
ffffffff814b0510-ffffffff814b05c2: aa_load_ent_free (STB_GLOBAL)
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
