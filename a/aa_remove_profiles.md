# Function: <code>aa_remove_profiles</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t aa_remove_profiles(struct aa_label *label, char *fqname, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff813817d0)
Location: security/apparmor/policy.c:1011
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
```
**Symbols:**

```
ffffffff813817d0-ffffffff81381a3d: aa_remove_profiles (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t aa_remove_profiles(struct aa_ns *view, struct aa_label *label, char *fqname, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff813bb220)
Location: security/apparmor/policy.c:1055
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
```
**Symbols:**

```
ffffffff813bb220-ffffffff813bb4af: aa_remove_profiles (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t aa_remove_profiles(struct aa_ns *view, struct aa_label *label, char *fqname, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff813d25e0)
Location: security/apparmor/policy.c:1057
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
```
**Symbols:**

```
ffffffff813d25e0-ffffffff813d29bf: aa_remove_profiles (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t aa_remove_profiles(struct aa_ns *policy_ns, struct aa_label *subj, char *fqname, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff813e5220)
Location: security/apparmor/policy.c:1086
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
```
**Symbols:**

```
ffffffff813e5220-ffffffff813e553d: aa_remove_profiles (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t aa_remove_profiles(struct aa_ns *policy_ns, struct aa_label *subj, char *fqname, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff8140c3f0)
Location: security/apparmor/policy.c:1090
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
```
**Symbols:**

```
ffffffff8140c3f0-ffffffff8140c717: aa_remove_profiles (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t aa_remove_profiles(struct aa_ns *policy_ns, struct aa_label *subj, char *fqname, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff8143dd30)
Location: security/apparmor/policy.c:1096
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
```
**Symbols:**

```
ffffffff8143dd30-ffffffff8143e06d: aa_remove_profiles (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t aa_remove_profiles(struct aa_ns *policy_ns, struct aa_label *subj, char *fqname, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff8145ab90)
Location: security/apparmor/policy.c:1096
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
```
**Symbols:**

```
ffffffff8145ab90-ffffffff8145aecd: aa_remove_profiles (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t aa_remove_profiles(struct aa_ns *policy_ns, struct aa_label *subj, char *fqname, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff814881c0)
Location: security/apparmor/policy.c:1091
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
```
**Symbols:**

```
ffffffff814881c0-ffffffff814884fa: aa_remove_profiles (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t aa_remove_profiles(struct aa_ns *policy_ns, struct aa_label *subj, char *fqname, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff814a2070)
Location: security/apparmor/policy.c:1091
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
```
**Symbols:**

```
ffffffff814a2070-ffffffff814a23aa: aa_remove_profiles (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t aa_remove_profiles(struct aa_ns *policy_ns, struct aa_label *subj, char *fqname, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff814fc270)
Location: security/apparmor/policy.c:1096
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
```
**Symbols:**

```
ffffffff814fc270-ffffffff814fc6ef: aa_remove_profiles (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t aa_remove_profiles(struct aa_ns *policy_ns, struct aa_label *subj, char *fqname, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff815194e0)
Location: security/apparmor/policy.c:1096
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
```
**Symbols:**

```
ffffffff815194e0-ffffffff8151995f: aa_remove_profiles (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t aa_remove_profiles(struct aa_ns *policy_ns, struct aa_label *subj, char *fqname, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff8151fdf0)
Location: security/apparmor/policy.c:1096
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
```
**Symbols:**

```
ffffffff8151fdf0-ffffffff81520267: aa_remove_profiles (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t aa_remove_profiles(struct aa_ns *policy_ns, struct aa_label *subj, char *fqname, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff8157df90)
Location: security/apparmor/policy.c:1096
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
```
**Symbols:**

```
ffffffff8157df90-ffffffff8157e407: aa_remove_profiles (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t aa_remove_profiles(struct aa_ns *policy_ns, struct aa_label *subj, char *fqname, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff8161c700)
Location: security/apparmor/policy.c:1187
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
```
**Symbols:**

```
ffffffff8161c700-ffffffff8161cb6b: aa_remove_profiles (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t aa_remove_profiles(struct aa_ns *policy_ns, struct aa_label *subj, char *fqname, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff816cf9a0)
Location: security/apparmor/policy.c:1288
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
```
**Symbols:**

```
ffffffff816cf9a0-ffffffff816cfe0b: aa_remove_profiles (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t aa_remove_profiles(struct aa_ns *policy_ns, struct aa_label *subj, char *fqname, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff817085c0)
Location: security/apparmor/policy.c:1322
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
```
**Symbols:**

```
ffffffff817085c0-ffffffff81708a2e: aa_remove_profiles (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t aa_remove_profiles(struct aa_ns *policy_ns, struct aa_label *subj, char *fqname, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff81746050)
Location: security/apparmor/policy.c:1354
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
```
**Symbols:**

```
ffffffff81746050-ffffffff817464be: aa_remove_profiles (STB_GLOBAL)
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
ssize_t aa_remove_profiles(struct aa_ns *policy_ns, struct aa_label *subj, char *fqname, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffff800010597bf8)
Location: security/apparmor/policy.c:1091
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
```
**Symbols:**

```
ffff800010597bf8-ffff800010597eec: aa_remove_profiles (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t aa_remove_profiles(struct aa_ns *policy_ns, struct aa_label *subj, char *fqname, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (c0748dd4)
Location: security/apparmor/policy.c:1091
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
```
**Symbols:**

```
c0748dd4-c07490e0: aa_remove_profiles (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t aa_remove_profiles(struct aa_ns *policy_ns, struct aa_label *subj, char *fqname, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (c00000000070e2d0)
Location: security/apparmor/policy.c:1091
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
```
**Symbols:**

```
c00000000070e2d0-c00000000070e754: aa_remove_profiles (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t aa_remove_profiles(struct aa_ns *policy_ns, struct aa_label *subj, char *fqname, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffe0003e46a2)
Location: security/apparmor/policy.c:1091
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
```
**Symbols:**

```
ffffffe0003e46a2-ffffffe0003e4984: aa_remove_profiles (STB_GLOBAL)
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
ssize_t aa_remove_profiles(struct aa_ns *policy_ns, struct aa_label *subj, char *fqname, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff8149a650)
Location: security/apparmor/policy.c:1091
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
```
**Symbols:**

```
ffffffff8149a650-ffffffff8149a98a: aa_remove_profiles (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t aa_remove_profiles(struct aa_ns *policy_ns, struct aa_label *subj, char *fqname, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff8148b070)
Location: security/apparmor/policy.c:1091
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
```
**Symbols:**

```
ffffffff8148b070-ffffffff8148b3aa: aa_remove_profiles (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t aa_remove_profiles(struct aa_ns *policy_ns, struct aa_label *subj, char *fqname, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff814966f0)
Location: security/apparmor/policy.c:1091
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
```
**Symbols:**

```
ffffffff814966f0-ffffffff81496a2a: aa_remove_profiles (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t aa_remove_profiles(struct aa_ns *policy_ns, struct aa_label *subj, char *fqname, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff814ae7c0)
Location: security/apparmor/policy.c:1091
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_remove
```
**Symbols:**

```
ffffffff814ae7c0-ffffffff814aeafa: aa_remove_profiles (STB_GLOBAL)
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
<b>Param reordered. </b>
<code>label, fqname, size</code> ➡️ <code>view, label, fqname, size</code>
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
<b>Param added. </b>
<code>struct aa_label *subj</code>
</li>
<li>
<b>Param removed. </b>
<code>struct aa_ns *view</code>
</li>
<li>
<b>Param removed. </b>
<code>struct aa_label *label</code>
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
