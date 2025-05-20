# Function: <code>__remove_profile</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __remove_profile(struct aa_profile *profile);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff8137f810)
Location: security/apparmor/policy.c:162
Inline: False
Direct callers:
  - security/apparmor/policy.c:__aa_profile_list_release
  - security/apparmor/policy.c:aa_remove_profiles
```
**Symbols:**

```
ffffffff8137f810-ffffffff8137f8d2: __remove_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __remove_profile(struct aa_profile *profile);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff813b9070)
Location: security/apparmor/policy.c:176
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:__aa_profile_list_release
```
**Symbols:**

```
ffffffff813b9070-ffffffff813b9132: __remove_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __remove_profile(struct aa_profile *profile);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff813d0430)
Location: security/apparmor/policy.c:176
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:__aa_profile_list_release
```
**Symbols:**

```
ffffffff813d0430-ffffffff813d04fa: __remove_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __remove_profile(struct aa_profile *profile);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff813e3b40)
Location: security/apparmor/policy.c:159
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:__aa_profile_list_release
```
**Symbols:**

```
ffffffff813e3b40-ffffffff813e3bac: __remove_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __remove_profile(struct aa_profile *profile);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff8140a950)
Location: security/apparmor/policy.c:159
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:__aa_profile_list_release
```
**Symbols:**

```
ffffffff8140a950-ffffffff8140a9bd: __remove_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __remove_profile(struct aa_profile *profile);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff8143c160)
Location: security/apparmor/policy.c:159
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:__aa_profile_list_release
```
**Symbols:**

```
ffffffff8143c160-ffffffff8143c1d2: __remove_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __remove_profile(struct aa_profile *profile);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff81458fd0)
Location: security/apparmor/policy.c:159
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:__aa_profile_list_release
```
**Symbols:**

```
ffffffff81458fd0-ffffffff81459042: __remove_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __remove_profile(struct aa_profile *profile);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff81486750)
Location: security/apparmor/policy.c:154
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:__aa_profile_list_release
```
**Symbols:**

```
ffffffff81486750-ffffffff814867c2: __remove_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __remove_profile(struct aa_profile *profile);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff814a0600)
Location: security/apparmor/policy.c:154
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:__aa_profile_list_release
```
**Symbols:**

```
ffffffff814a0600-ffffffff814a0672: __remove_profile (STB_LOCAL)
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
In security/apparmor/policy.c (ffffffff814fc363)
Location: security/apparmor/policy.c:154
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:__aa_profile_list_release
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
In security/apparmor/policy.c (ffffffff815195d3)
Location: security/apparmor/policy.c:154
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:__aa_profile_list_release
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
In security/apparmor/policy.c (ffffffff8151fedb)
Location: security/apparmor/policy.c:154
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:__aa_profile_list_release
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
In security/apparmor/policy.c (ffffffff8157e07b)
Location: security/apparmor/policy.c:154
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:__aa_profile_list_release
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
In security/apparmor/policy.c (ffffffff8161c7ed)
Location: security/apparmor/policy.c:156
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:__aa_profile_list_release
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
In security/apparmor/policy.c (ffffffff816cfa8d)
Location: security/apparmor/policy.c:158
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:__aa_profile_list_release
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
In security/apparmor/policy.c (ffffffff817086ad)
Location: security/apparmor/policy.c:195
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:__aa_profile_list_release
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
In security/apparmor/policy.c (ffffffff8174613d)
Location: security/apparmor/policy.c:196
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:__aa_profile_list_release
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
void __remove_profile(struct aa_profile *profile);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffff8000105963d0)
Location: security/apparmor/policy.c:154
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:__aa_profile_list_release
```
**Symbols:**

```
ffff8000105963d0-ffff800010596450: __remove_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __remove_profile(struct aa_profile *profile);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (c07474b0)
Location: security/apparmor/policy.c:154
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:__aa_profile_list_release
```
**Symbols:**

```
c07474b0-c074751c: __remove_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __remove_profile(struct aa_profile *profile);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (c00000000070bef0)
Location: security/apparmor/policy.c:154
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:__aa_profile_list_release
```
**Symbols:**

```
c00000000070bef0-c00000000070bfd4: __remove_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __remove_profile(struct aa_profile *profile);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffe0003e31ba)
Location: security/apparmor/policy.c:154
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:__aa_profile_list_release
```
**Symbols:**

```
ffffffe0003e31ba-ffffffe0003e3206: __remove_profile (STB_LOCAL)
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
void __remove_profile(struct aa_profile *profile);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff81498be0)
Location: security/apparmor/policy.c:154
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:__aa_profile_list_release
```
**Symbols:**

```
ffffffff81498be0-ffffffff81498c52: __remove_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __remove_profile(struct aa_profile *profile);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff81489600)
Location: security/apparmor/policy.c:154
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:__aa_profile_list_release
```
**Symbols:**

```
ffffffff81489600-ffffffff81489672: __remove_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __remove_profile(struct aa_profile *profile);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff81494c80)
Location: security/apparmor/policy.c:154
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:__aa_profile_list_release
```
**Symbols:**

```
ffffffff81494c80-ffffffff81494cf2: __remove_profile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __remove_profile(struct aa_profile *profile);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff814acca0)
Location: security/apparmor/policy.c:154
Inline: False
Direct callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:__aa_profile_list_release
```
**Symbols:**

```
ffffffff814acca0-ffffffff814acd12: __remove_profile (STB_LOCAL)
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
