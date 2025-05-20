# Function: <code>aa_free_profile</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void aa_free_profile(struct aa_profile *profile);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff8137f8e0)
Location: security/apparmor/policy.c:200
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_alloc_profile
  - security/apparmor/policy.c:aa_null_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_ns.c:aa_free_ns
```
**Symbols:**

```
ffffffff8137f8e0-ffffffff8137fa13: aa_free_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void aa_free_profile(struct aa_profile *profile);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff813b9140)
Location: security/apparmor/policy.c:214
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_null_profile
  - security/apparmor/policy.c:aa_alloc_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_ns.c:aa_free_ns
```
**Symbols:**

```
ffffffff813b9140-ffffffff813b93dd: aa_free_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void aa_free_profile(struct aa_profile *profile);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff813d0500)
Location: security/apparmor/policy.c:214
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_null_profile
  - security/apparmor/policy.c:aa_alloc_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_ns.c:aa_free_ns
```
**Symbols:**

```
ffffffff813d0500-ffffffff813d079d: aa_free_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void aa_free_profile(struct aa_profile *profile);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff813e3bb0)
Location: security/apparmor/policy.c:210
Inline: True
Direct callers:
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_alloc_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
**Symbols:**

```
ffffffff813e3bb0-ffffffff813e3d80: aa_free_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void aa_free_profile(struct aa_profile *profile);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff8140a9c0)
Location: security/apparmor/policy.c:210
Inline: True
Direct callers:
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_alloc_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
**Symbols:**

```
ffffffff8140a9c0-ffffffff8140ab5b: aa_free_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void aa_free_profile(struct aa_profile *profile);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff8143c1e0)
Location: security/apparmor/policy.c:210
Inline: True
Direct callers:
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_alloc_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
**Symbols:**

```
ffffffff8143c1e0-ffffffff8143c419: aa_free_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void aa_free_profile(struct aa_profile *profile);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff81459050)
Location: security/apparmor/policy.c:210
Inline: True
Direct callers:
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_alloc_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
**Symbols:**

```
ffffffff81459050-ffffffff81459289: aa_free_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void aa_free_profile(struct aa_profile *profile);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff814867d0)
Location: security/apparmor/policy.c:205
Inline: True
Direct callers:
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_alloc_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
**Symbols:**

```
ffffffff814867d0-ffffffff81486a22: aa_free_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void aa_free_profile(struct aa_profile *profile);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff814a0680)
Location: security/apparmor/policy.c:205
Inline: True
Direct callers:
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_alloc_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
**Symbols:**

```
ffffffff814a0680-ffffffff814a08d2: aa_free_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void aa_free_profile(struct aa_profile *profile);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff814fa650)
Location: security/apparmor/policy.c:205
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_alloc_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
**Symbols:**

```
ffffffff814fa650-ffffffff814fa98b: aa_free_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void aa_free_profile(struct aa_profile *profile);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff815173d0)
Location: security/apparmor/policy.c:205
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_alloc_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
**Symbols:**

```
ffffffff815173d0-ffffffff8151770b: aa_free_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void aa_free_profile(struct aa_profile *profile);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff8151dc80)
Location: security/apparmor/policy.c:205
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_alloc_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
ffffffff8151dc80-ffffffff8151dfbb: aa_free_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void aa_free_profile(struct aa_profile *profile);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/policy.c (0)
Location: security/apparmor/policy.c:205
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_alloc_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_ns.c:__aa_create_ns
```
**Symbols:**

```
ffffffff81cd64cd-ffffffff81cd64e1: aa_free_profile.cold (STB_LOCAL)
ffffffff8157bd70-ffffffff8157c0b7: aa_free_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void aa_free_profile(struct aa_profile *profile);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/policy.c (0)
Location: security/apparmor/policy.c:242
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_alloc_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
**Symbols:**

```
ffffffff81e892e2-ffffffff81e892f6: aa_free_profile.cold (STB_LOCAL)
ffffffff8161a3e0-ffffffff8161a79e: aa_free_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void aa_free_profile(struct aa_profile *profile);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/policy.c (ffffffff816ce0ed)
Location: security/apparmor/policy.c:245
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_learning_profile
Direct callers:
  - security/apparmor/policy.c:aa_new_learning_profile
  - security/apparmor/policy.c:aa_alloc_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
**Symbols:**

```
ffffffff816cce70-ffffffff816cd1cb: aa_free_profile.part.0 (STB_LOCAL)
ffffffff816cd6f0-ffffffff816cd759: aa_free_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void aa_free_profile(struct aa_profile *profile);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/policy.c (ffffffff81706ce3)
Location: security/apparmor/policy.c:282
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_learning_profile
  - security/apparmor/policy.c:aa_new_learning_profile
  - security/apparmor/policy.c:aa_alloc_profile
Direct callers:
  - security/apparmor/policy.c:aa_new_learning_profile
  - security/apparmor/policy.c:aa_alloc_profile
  - security/apparmor/policy.c:aa_alloc_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
**Symbols:**

```
ffffffff81705c60-ffffffff81706053: aa_free_profile.part.0 (STB_LOCAL)
ffffffff81706330-ffffffff81706382: aa_free_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void aa_free_profile(struct aa_profile *profile);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/policy.c (ffffffff81744783)
Location: security/apparmor/policy.c:283
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_new_learning_profile
  - security/apparmor/policy.c:aa_new_learning_profile
  - security/apparmor/policy.c:aa_alloc_profile
Direct callers:
  - security/apparmor/policy.c:aa_new_learning_profile
  - security/apparmor/policy.c:aa_alloc_profile
  - security/apparmor/policy.c:aa_alloc_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
**Symbols:**

```
ffffffff81743560-ffffffff8174396b: aa_free_profile.part.0 (STB_LOCAL)
ffffffff81743c90-ffffffff81743ce2: aa_free_profile (STB_GLOBAL)
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
void aa_free_profile(struct aa_profile *profile);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffff800010596450)
Location: security/apparmor/policy.c:205
Inline: True
Direct callers:
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_alloc_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
**Symbols:**

```
ffff800010596450-ffff80001059665c: aa_free_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void aa_free_profile(struct aa_profile *profile);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (c074751c)
Location: security/apparmor/policy.c:205
Inline: True
Direct callers:
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_alloc_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
**Symbols:**

```
c074751c-c0747764: aa_free_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void aa_free_profile(struct aa_profile *profile);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (c00000000070bfe0)
Location: security/apparmor/policy.c:205
Inline: True
Direct callers:
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_alloc_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
**Symbols:**

```
c00000000070bfe0-c00000000070c350: aa_free_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void aa_free_profile(struct aa_profile *profile);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffe0003e3206)
Location: security/apparmor/policy.c:205
Inline: True
Direct callers:
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_alloc_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
**Symbols:**

```
ffffffe0003e3206-ffffffe0003e33fa: aa_free_profile (STB_GLOBAL)
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
void aa_free_profile(struct aa_profile *profile);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff81498c60)
Location: security/apparmor/policy.c:205
Inline: True
Direct callers:
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_alloc_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
**Symbols:**

```
ffffffff81498c60-ffffffff81498eb2: aa_free_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void aa_free_profile(struct aa_profile *profile);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff81489680)
Location: security/apparmor/policy.c:205
Inline: True
Direct callers:
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_alloc_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
**Symbols:**

```
ffffffff81489680-ffffffff814898d2: aa_free_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void aa_free_profile(struct aa_profile *profile);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff81494d00)
Location: security/apparmor/policy.c:205
Inline: True
Direct callers:
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_alloc_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
**Symbols:**

```
ffffffff81494d00-ffffffff81494f52: aa_free_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void aa_free_profile(struct aa_profile *profile);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff814acd20)
Location: security/apparmor/policy.c:205
Inline: True
Direct callers:
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_alloc_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
**Symbols:**

```
ffffffff814acd20-ffffffff814acf72: aa_free_profile (STB_GLOBAL)
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
