# Function: <code>aa_replace_profiles</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t aa_replace_profiles(struct aa_label *label, u32 mask, void *udata, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff81380c60)
Location: security/apparmor/policy.c:834
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
ffffffff81380c60-ffffffff813817c8: aa_replace_profiles (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t aa_replace_profiles(struct aa_ns *view, struct aa_label *label, u32 mask, struct aa_loaddata *udata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff813ba510)
Location: security/apparmor/policy.c:864
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
ffffffff813ba510-ffffffff813bb217: aa_replace_profiles (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t aa_replace_profiles(struct aa_ns *view, struct aa_label *label, u32 mask, struct aa_loaddata *udata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff813d18d0)
Location: security/apparmor/policy.c:865
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
ffffffff813d18d0-ffffffff813d25df: aa_replace_profiles (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t aa_replace_profiles(struct aa_ns *policy_ns, struct aa_label *label, u32 mask, struct aa_loaddata *udata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff813e4770)
Location: security/apparmor/policy.c:852
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
ffffffff813e4770-ffffffff813e521c: aa_replace_profiles (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t aa_replace_profiles(struct aa_ns *policy_ns, struct aa_label *label, u32 mask, struct aa_loaddata *udata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff8140b720)
Location: security/apparmor/policy.c:853
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
ffffffff8140b720-ffffffff8140c3e2: aa_replace_profiles (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t aa_replace_profiles(struct aa_ns *policy_ns, struct aa_label *label, u32 mask, struct aa_loaddata *udata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff8143d070)
Location: security/apparmor/policy.c:859
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
ffffffff8143d070-ffffffff8143dd2a: aa_replace_profiles (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t aa_replace_profiles(struct aa_ns *policy_ns, struct aa_label *label, u32 mask, struct aa_loaddata *udata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff81459ed0)
Location: security/apparmor/policy.c:859
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
ffffffff81459ed0-ffffffff8145ab8c: aa_replace_profiles (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t aa_replace_profiles(struct aa_ns *policy_ns, struct aa_label *label, u32 mask, struct aa_loaddata *udata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff81487540)
Location: security/apparmor/policy.c:854
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
ffffffff81487540-ffffffff814881b2: aa_replace_profiles (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t aa_replace_profiles(struct aa_ns *policy_ns, struct aa_label *label, u32 mask, struct aa_loaddata *udata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff814a13f0)
Location: security/apparmor/policy.c:854
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
ffffffff814a13f0-ffffffff814a2062: aa_replace_profiles (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t aa_replace_profiles(struct aa_ns *policy_ns, struct aa_label *label, u32 mask, struct aa_loaddata *udata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff814fb590)
Location: security/apparmor/policy.c:858
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
ffffffff814fb590-ffffffff814fc26a: aa_replace_profiles (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t aa_replace_profiles(struct aa_ns *policy_ns, struct aa_label *label, u32 mask, struct aa_loaddata *udata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff815185e0)
Location: security/apparmor/policy.c:858
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
ffffffff815185e0-ffffffff815194db: aa_replace_profiles (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t aa_replace_profiles(struct aa_ns *policy_ns, struct aa_label *label, u32 mask, struct aa_loaddata *udata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff8151ee40)
Location: security/apparmor/policy.c:858
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
ffffffff8151ee40-ffffffff8151fde6: aa_replace_profiles (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t aa_replace_profiles(struct aa_ns *policy_ns, struct aa_label *label, u32 mask, struct aa_loaddata *udata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff8157cfe0)
Location: security/apparmor/policy.c:858
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
ffffffff8157cfe0-ffffffff8157df86: aa_replace_profiles (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t aa_replace_profiles(struct aa_ns *policy_ns, struct aa_label *label, u32 mask, struct aa_loaddata *udata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/policy.c (0)
Location: security/apparmor/policy.c:944
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
ffffffff81e89372-ffffffff81e893b9: aa_replace_profiles.cold (STB_LOCAL)
ffffffff8161b650-ffffffff8161c6f2: aa_replace_profiles (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
ssize_t aa_replace_profiles(struct aa_ns *policy_ns, struct aa_label *label, u32 mask, struct aa_loaddata *udata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/policy.c (0)
Location: security/apparmor/policy.c:1026
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
ffffffff82074b7d-ffffffff82074bc2: aa_replace_profiles.cold (STB_LOCAL)
ffffffff816ce720-ffffffff816cf98a: aa_replace_profiles (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
ssize_t aa_replace_profiles(struct aa_ns *policy_ns, struct aa_label *label, u32 mask, struct aa_loaddata *udata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/policy.c (0)
Location: security/apparmor/policy.c:1060
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
ffffffff820f4782-ffffffff820f47c7: aa_replace_profiles.cold (STB_LOCAL)
ffffffff81707340-ffffffff817085ad: aa_replace_profiles (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
ssize_t aa_replace_profiles(struct aa_ns *policy_ns, struct aa_label *label, u32 mask, struct aa_loaddata *udata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/policy.c (0)
Location: security/apparmor/policy.c:1092
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
ffffffff821d1bbc-ffffffff821d1c01: aa_replace_profiles.cold (STB_LOCAL)
ffffffff81744dd0-ffffffff81746040: aa_replace_profiles (STB_GLOBAL)
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
ssize_t aa_replace_profiles(struct aa_ns *policy_ns, struct aa_label *label, u32 mask, struct aa_loaddata *udata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffff800010597188)
Location: security/apparmor/policy.c:854
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
ffff800010597188-ffff800010597bf8: aa_replace_profiles (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t aa_replace_profiles(struct aa_ns *policy_ns, struct aa_label *label, u32 mask, struct aa_loaddata *udata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (c0748248)
Location: security/apparmor/policy.c:854
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
c0748248-c0748dd4: aa_replace_profiles (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t aa_replace_profiles(struct aa_ns *policy_ns, struct aa_label *label, u32 mask, struct aa_loaddata *udata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (c00000000070d360)
Location: security/apparmor/policy.c:854
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
c00000000070d360-c00000000070e2d0: aa_replace_profiles (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t aa_replace_profiles(struct aa_ns *policy_ns, struct aa_label *label, u32 mask, struct aa_loaddata *udata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffe0003e3dee)
Location: security/apparmor/policy.c:854
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
ffffffe0003e3dee-ffffffe0003e46a2: aa_replace_profiles (STB_GLOBAL)
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
ssize_t aa_replace_profiles(struct aa_ns *policy_ns, struct aa_label *label, u32 mask, struct aa_loaddata *udata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff814999d0)
Location: security/apparmor/policy.c:854
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
ffffffff814999d0-ffffffff8149a642: aa_replace_profiles (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t aa_replace_profiles(struct aa_ns *policy_ns, struct aa_label *label, u32 mask, struct aa_loaddata *udata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff8148a3f0)
Location: security/apparmor/policy.c:854
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
ffffffff8148a3f0-ffffffff8148b062: aa_replace_profiles (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t aa_replace_profiles(struct aa_ns *policy_ns, struct aa_label *label, u32 mask, struct aa_loaddata *udata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff81495a70)
Location: security/apparmor/policy.c:854
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
ffffffff81495a70-ffffffff814966e2: aa_replace_profiles (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t aa_replace_profiles(struct aa_ns *policy_ns, struct aa_label *label, u32 mask, struct aa_loaddata *udata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff814adb00)
Location: security/apparmor/policy.c:854
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:policy_update
```
**Symbols:**

```
ffffffff814adb00-ffffffff814ae7b8: aa_replace_profiles (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct aa_ns *view</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t size</code>
</li>
<li>
<b>Param reordered. </b>
<code>label, mask, udata, size</code> ➡️ <code>view, label, mask, udata</code>
</li>
<li>
<b>Param type changed. </b>
<code>void *udata</code> ➡️ <code>struct aa_loaddata *udata</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct aa_ns *policy_ns</code>
</li>
<li>
<b>Param removed. </b>
<code>struct aa_ns *view</code>
</li>
</ul>
</details>
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
