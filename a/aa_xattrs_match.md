# Function: <code>aa_xattrs_match</code>

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
int aa_xattrs_match(const struct linux_binprm *bprm, struct aa_profile *profile, unsigned int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff81437140)
Location: security/apparmor/domain.c:313
Inline: False
Direct callers:
  - security/apparmor/domain.c:profile_transition
```
**Symbols:**

```
ffffffff81437140-ffffffff81437289: aa_xattrs_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int aa_xattrs_match(const struct linux_binprm *bprm, struct aa_profile *profile, unsigned int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff81453da0)
Location: security/apparmor/domain.c:313
Inline: False
Direct callers:
  - security/apparmor/domain.c:profile_transition
```
**Symbols:**

```
ffffffff81453da0-ffffffff81453ee9: aa_xattrs_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int aa_xattrs_match(const struct linux_binprm *bprm, struct aa_profile *profile, unsigned int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff81481740)
Location: security/apparmor/domain.c:309
Inline: False
Direct callers:
  - security/apparmor/domain.c:profile_transition
```
**Symbols:**

```
ffffffff81481740-ffffffff81481884: aa_xattrs_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int aa_xattrs_match(const struct linux_binprm *bprm, struct aa_profile *profile, unsigned int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff8149b470)
Location: security/apparmor/domain.c:309
Inline: False
Direct callers:
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
```
**Symbols:**

```
ffffffff8149b470-ffffffff8149b5bd: aa_xattrs_match (STB_LOCAL)
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
In security/apparmor/domain.c (ffffffff814f4c3f)
Location: security/apparmor/domain.c:309
Inline: True
Inline callers:
  - security/apparmor/domain.c:find_attach
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
In security/apparmor/domain.c (ffffffff81512044)
Location: security/apparmor/domain.c:309
Inline: True
Inline callers:
  - security/apparmor/domain.c:find_attach
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
In security/apparmor/domain.c (ffffffff8151897c)
Location: security/apparmor/domain.c:311
Inline: True
Inline callers:
  - security/apparmor/domain.c:find_attach
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
In security/apparmor/domain.c (ffffffff8157698c)
Location: security/apparmor/domain.c:311
Inline: True
Inline callers:
  - security/apparmor/domain.c:find_attach
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
In security/apparmor/domain.c (ffffffff81614840)
Location: security/apparmor/domain.c:298
Inline: True
Inline callers:
  - security/apparmor/domain.c:find_attach
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
In security/apparmor/domain.c (ffffffff816c755d)
Location: security/apparmor/domain.c:305
Inline: True
Inline callers:
  - security/apparmor/domain.c:find_attach
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
In security/apparmor/domain.c (ffffffff816ffb33)
Location: security/apparmor/domain.c:305
Inline: True
Inline callers:
  - security/apparmor/domain.c:find_attach
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
In security/apparmor/domain.c (ffffffff8173d10f)
Location: security/apparmor/domain.c:309
Inline: True
Inline callers:
  - security/apparmor/domain.c:find_attach
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
int aa_xattrs_match(const struct linux_binprm *bprm, struct aa_profile *profile, unsigned int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffff8000105917b0)
Location: security/apparmor/domain.c:309
Inline: False
Direct callers:
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
```
**Symbols:**

```
ffff8000105917b0-ffff800010591914: aa_xattrs_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int aa_xattrs_match(const struct linux_binprm *bprm, struct aa_profile *profile, unsigned int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (c07423c4)
Location: security/apparmor/domain.c:309
Inline: False
Direct callers:
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
```
**Symbols:**

```
c07423c4-c0742530: aa_xattrs_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int aa_xattrs_match(const struct linux_binprm *bprm, struct aa_profile *profile, unsigned int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (c000000000705490)
Location: security/apparmor/domain.c:309
Inline: False
Direct callers:
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
```
**Symbols:**

```
c000000000705490-c0000000007056a4: aa_xattrs_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int aa_xattrs_match(const struct linux_binprm *bprm, struct aa_profile *profile, unsigned int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffe0003df2ba)
Location: security/apparmor/domain.c:309
Inline: False
Direct callers:
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
```
**Symbols:**

```
ffffffe0003df2ba-ffffffe0003df3ca: aa_xattrs_match (STB_LOCAL)
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
int aa_xattrs_match(const struct linux_binprm *bprm, struct aa_profile *profile, unsigned int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff81493a50)
Location: security/apparmor/domain.c:309
Inline: False
Direct callers:
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
```
**Symbols:**

```
ffffffff81493a50-ffffffff81493b9d: aa_xattrs_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int aa_xattrs_match(const struct linux_binprm *bprm, struct aa_profile *profile, unsigned int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff81484470)
Location: security/apparmor/domain.c:309
Inline: False
Direct callers:
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
```
**Symbols:**

```
ffffffff81484470-ffffffff814845bd: aa_xattrs_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int aa_xattrs_match(const struct linux_binprm *bprm, struct aa_profile *profile, unsigned int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff8148faf0)
Location: security/apparmor/domain.c:309
Inline: False
Direct callers:
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
```
**Symbols:**

```
ffffffff8148faf0-ffffffff8148fc3d: aa_xattrs_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int aa_xattrs_match(const struct linux_binprm *bprm, struct aa_profile *profile, unsigned int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff814a7a00)
Location: security/apparmor/domain.c:309
Inline: False
Direct callers:
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
```
**Symbols:**

```
ffffffff814a7a00-ffffffff814a7b44: aa_xattrs_match (STB_LOCAL)
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
