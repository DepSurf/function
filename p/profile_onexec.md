# Function: <code>profile_onexec</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int profile_onexec(struct aa_profile *profile, struct aa_label *onexec, bool stack, const char *xname, struct path_cond *cond, bool *secure_exec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff8137a3d0)
Location: security/apparmor/domain.c:567
Inline: False
Direct callers:
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
```
**Symbols:**

```
ffffffff8137a3d0-ffffffff8137a586: profile_onexec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int profile_onexec(struct aa_profile *profile, struct aa_label *onexec, bool stack, const struct linux_binprm *bprm, char *buffer, struct path_cond *cond, bool *secure_exec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff813b30c0)
Location: security/apparmor/domain.c:581
Inline: False
Direct callers:
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
```
**Symbols:**

```
ffffffff813b30c0-ffffffff813b343c: profile_onexec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int profile_onexec(struct aa_profile *profile, struct aa_label *onexec, bool stack, const struct linux_binprm *bprm, char *buffer, struct path_cond *cond, bool *secure_exec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff813ca280)
Location: security/apparmor/domain.c:600
Inline: False
Direct callers:
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
```
**Symbols:**

```
ffffffff813ca280-ffffffff813ca645: profile_onexec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int profile_onexec(struct aa_profile *profile, struct aa_label *onexec, bool stack, const struct linux_binprm *bprm, char *buffer, struct path_cond *cond, bool *secure_exec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff813dfaf0)
Location: security/apparmor/domain.c:600
Inline: False
Direct callers:
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
```
**Symbols:**

```
ffffffff813dfaf0-ffffffff813dfdbb: profile_onexec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int profile_onexec(struct aa_profile *profile, struct aa_label *onexec, bool stack, const struct linux_binprm *bprm, char *buffer, struct path_cond *cond, bool *secure_exec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff81406370)
Location: security/apparmor/domain.c:633
Inline: False
Direct callers:
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
```
**Symbols:**

```
ffffffff81406370-ffffffff8140663b: profile_onexec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int profile_onexec(struct aa_profile *profile, struct aa_label *onexec, bool stack, const struct linux_binprm *bprm, char *buffer, struct path_cond *cond, bool *secure_exec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff81437b40)
Location: security/apparmor/domain.c:743
Inline: False
Direct callers:
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
```
**Symbols:**

```
ffffffff81437b40-ffffffff81437de4: profile_onexec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int profile_onexec(struct aa_profile *profile, struct aa_label *onexec, bool stack, const struct linux_binprm *bprm, char *buffer, struct path_cond *cond, bool *secure_exec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff81454700)
Location: security/apparmor/domain.c:743
Inline: False
Direct callers:
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
```
**Symbols:**

```
ffffffff81454700-ffffffff814549a4: profile_onexec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int profile_onexec(struct aa_profile *profile, struct aa_label *onexec, bool stack, const struct linux_binprm *bprm, char *buffer, struct path_cond *cond, bool *secure_exec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff814820c0)
Location: security/apparmor/domain.c:739
Inline: False
Direct callers:
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
```
**Symbols:**

```
ffffffff814820c0-ffffffff81482341: profile_onexec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int profile_onexec(struct aa_profile *profile, struct aa_label *onexec, bool stack, const struct linux_binprm *bprm, char *buffer, struct path_cond *cond, bool *secure_exec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff8149bdf0)
Location: security/apparmor/domain.c:743
Inline: False
Direct callers:
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
```
**Symbols:**

```
ffffffff8149bdf0-ffffffff8149c071: profile_onexec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int profile_onexec(struct aa_profile *profile, struct aa_label *onexec, bool stack, const struct linux_binprm *bprm, char *buffer, struct path_cond *cond, bool *secure_exec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff814f4850)
Location: security/apparmor/domain.c:720
Inline: False
Direct callers:
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
```
**Symbols:**

```
ffffffff814f4850-ffffffff814f4ad1: profile_onexec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int profile_onexec(struct aa_profile *profile, struct aa_label *onexec, bool stack, const struct linux_binprm *bprm, char *buffer, struct path_cond *cond, bool *secure_exec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff81511990)
Location: security/apparmor/domain.c:720
Inline: False
Direct callers:
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
```
**Symbols:**

```
ffffffff81511990-ffffffff81511c11: profile_onexec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int profile_onexec(struct aa_profile *profile, struct aa_label *onexec, bool stack, const struct linux_binprm *bprm, char *buffer, struct path_cond *cond, bool *secure_exec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff815182f0)
Location: security/apparmor/domain.c:722
Inline: False
Direct callers:
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
```
**Symbols:**

```
ffffffff815182f0-ffffffff8151856f: profile_onexec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int profile_onexec(struct aa_profile *profile, struct aa_label *onexec, bool stack, const struct linux_binprm *bprm, char *buffer, struct path_cond *cond, bool *secure_exec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/domain.c (0)
Location: security/apparmor/domain.c:722
Inline: False
Direct callers:
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
```
**Symbols:**

```
ffffffff815762f0-ffffffff8157657f: profile_onexec (STB_LOCAL)
ffffffff81cd6322-ffffffff81cd634b: profile_onexec.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int profile_onexec(struct aa_profile *profile, struct aa_label *onexec, bool stack, const struct linux_binprm *bprm, char *buffer, struct path_cond *cond, bool *secure_exec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/domain.c (0)
Location: security/apparmor/domain.c:723
Inline: False
Direct callers:
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
```
**Symbols:**

```
ffffffff81614390-ffffffff81614699: profile_onexec (STB_LOCAL)
ffffffff81e89141-ffffffff81e89179: profile_onexec.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int profile_onexec(const struct cred *subj_cred, struct aa_profile *profile, struct aa_label *onexec, bool stack, const struct linux_binprm *bprm, char *buffer, struct path_cond *cond, bool *secure_exec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff816c70b0)
Location: security/apparmor/domain.c:730
Inline: False
```
**Symbols:**

```
ffffffff816c70b0-ffffffff816c73ad: profile_onexec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int profile_onexec(const struct cred *subj_cred, struct aa_profile *profile, struct aa_label *onexec, bool stack, const struct linux_binprm *bprm, char *buffer, struct path_cond *cond, bool *secure_exec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff81700490)
Location: security/apparmor/domain.c:730
Inline: False
Direct callers:
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
```
**Symbols:**

```
ffffffff81700490-ffffffff81700773: profile_onexec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int profile_onexec(const struct cred *subj_cred, struct aa_profile *profile, struct aa_label *onexec, bool stack, const struct linux_binprm *bprm, char *buffer, struct path_cond *cond, bool *secure_exec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff8173daa0)
Location: security/apparmor/domain.c:737
Inline: False
Direct callers:
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
```
**Symbols:**

```
ffffffff8173daa0-ffffffff8173dd9e: profile_onexec (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/domain.c (ffff800010592560)
Location: security/apparmor/domain.c:743
Inline: True
Direct callers:
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
```
**Symbols:**

```
ffff800010592560-ffff800010592804: profile_onexec.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int profile_onexec(struct aa_profile *profile, struct aa_label *onexec, bool stack, const struct linux_binprm *bprm, char *buffer, struct path_cond *cond, bool *secure_exec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (c0743164)
Location: security/apparmor/domain.c:743
Inline: False
Direct callers:
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
```
**Symbols:**

```
c0743164-c0743440: profile_onexec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/domain.c (c0000000007064a0)
Location: security/apparmor/domain.c:743
Inline: True
Direct callers:
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
```
**Symbols:**

```
c0000000007064a0-c000000000706800: profile_onexec.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/domain.c (ffffffe0003dfb7e)
Location: security/apparmor/domain.c:743
Inline: True
Direct callers:
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
```
**Symbols:**

```
ffffffe0003dfb7e-ffffffe0003dfde2: profile_onexec.isra.0 (STB_LOCAL)
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
int profile_onexec(struct aa_profile *profile, struct aa_label *onexec, bool stack, const struct linux_binprm *bprm, char *buffer, struct path_cond *cond, bool *secure_exec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff814943d0)
Location: security/apparmor/domain.c:743
Inline: False
Direct callers:
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
```
**Symbols:**

```
ffffffff814943d0-ffffffff81494651: profile_onexec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int profile_onexec(struct aa_profile *profile, struct aa_label *onexec, bool stack, const struct linux_binprm *bprm, char *buffer, struct path_cond *cond, bool *secure_exec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff81484df0)
Location: security/apparmor/domain.c:743
Inline: False
Direct callers:
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
```
**Symbols:**

```
ffffffff81484df0-ffffffff81485071: profile_onexec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int profile_onexec(struct aa_profile *profile, struct aa_label *onexec, bool stack, const struct linux_binprm *bprm, char *buffer, struct path_cond *cond, bool *secure_exec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff81490470)
Location: security/apparmor/domain.c:743
Inline: False
Direct callers:
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
```
**Symbols:**

```
ffffffff81490470-ffffffff814906f1: profile_onexec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int profile_onexec(struct aa_profile *profile, struct aa_label *onexec, bool stack, const struct linux_binprm *bprm, char *buffer, struct path_cond *cond, bool *secure_exec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff814a8380)
Location: security/apparmor/domain.c:743
Inline: False
Direct callers:
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
```
**Symbols:**

```
ffffffff814a8380-ffffffff814a8601: profile_onexec (STB_LOCAL)
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
<code>const struct linux_binprm *bprm</code>
</li>
<li>
<b>Param added. </b>
<code>char *buffer</code>
</li>
<li>
<b>Param removed. </b>
<code>const char *xname</code>
</li>
<li>
<b>Param reordered. </b>
<code>profile, onexec, stack, xname, cond, secure_exec</code> ➡️ <code>profile, onexec, stack, bprm, buffer, cond, secure_exec</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct cred *subj_cred</code>
</li>
<li>
<b>Param reordered. </b>
<code>profile, onexec, stack, bprm, buffer, cond, secure_exec</code> ➡️ <code>subj_cred, profile, onexec, stack, bprm, buffer, cond, secure_exec</code>
</li>
</ul>
</details>
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
