# Function: <code>profile_transition</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct aa_label *profile_transition(struct aa_profile *profile, const char *name, struct path_cond *cond, bool *secure_exec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff8137b550)
Location: security/apparmor/domain.c:490
Inline: False
Direct callers:
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
```
**Symbols:**

```
ffffffff8137b550-ffffffff8137beae: profile_transition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct aa_label *profile_transition(struct aa_profile *profile, const struct linux_binprm *bprm, char *buffer, struct path_cond *cond, bool *secure_exec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff813b4600)
Location: security/apparmor/domain.c:490
Inline: False
Direct callers:
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
```
**Symbols:**

```
ffffffff813b4600-ffffffff813b51ff: profile_transition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct aa_label *profile_transition(struct aa_profile *profile, const struct linux_binprm *bprm, char *buffer, struct path_cond *cond, bool *secure_exec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff813cb810)
Location: security/apparmor/domain.c:490
Inline: False
Direct callers:
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
```
**Symbols:**

```
ffffffff813cb810-ffffffff813cc55c: profile_transition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct aa_label *profile_transition(struct aa_profile *profile, const struct linux_binprm *bprm, char *buffer, struct path_cond *cond, bool *secure_exec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff813e09c0)
Location: security/apparmor/domain.c:488
Inline: False
Direct callers:
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
```
**Symbols:**

```
ffffffff813e09c0-ffffffff813e1199: profile_transition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct aa_label *profile_transition(struct aa_profile *profile, const struct linux_binprm *bprm, char *buffer, struct path_cond *cond, bool *secure_exec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff81407420)
Location: security/apparmor/domain.c:509
Inline: False
Direct callers:
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
```
**Symbols:**

```
ffffffff81407420-ffffffff81407d3e: profile_transition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct aa_label *profile_transition(struct aa_profile *profile, const struct linux_binprm *bprm, char *buffer, struct path_cond *cond, bool *secure_exec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff81438b00)
Location: security/apparmor/domain.c:617
Inline: False
Direct callers:
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
```
**Symbols:**

```
ffffffff81438b00-ffffffff814393c2: profile_transition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct aa_label *profile_transition(struct aa_profile *profile, const struct linux_binprm *bprm, char *buffer, struct path_cond *cond, bool *secure_exec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff81455770)
Location: security/apparmor/domain.c:617
Inline: False
Direct callers:
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
```
**Symbols:**

```
ffffffff81455770-ffffffff8145604e: profile_transition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct aa_label *profile_transition(struct aa_profile *profile, const struct linux_binprm *bprm, char *buffer, struct path_cond *cond, bool *secure_exec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff814831b0)
Location: security/apparmor/domain.c:613
Inline: False
Direct callers:
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
```
**Symbols:**

```
ffffffff814831b0-ffffffff81483a0a: profile_transition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct aa_label *profile_transition(struct aa_profile *profile, const struct linux_binprm *bprm, char *buffer, struct path_cond *cond, bool *secure_exec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff8149d0c0)
Location: security/apparmor/domain.c:617
Inline: False
Direct callers:
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
```
**Symbols:**

```
ffffffff8149d0c0-ffffffff8149d924: profile_transition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct aa_label *profile_transition(struct aa_profile *profile, const struct linux_binprm *bprm, char *buffer, struct path_cond *cond, bool *secure_exec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff814f5f30)
Location: security/apparmor/domain.c:622
Inline: False
Direct callers:
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
```
**Symbols:**

```
ffffffff814f5f30-ffffffff814f6893: profile_transition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct aa_label *profile_transition(struct aa_profile *profile, const struct linux_binprm *bprm, char *buffer, struct path_cond *cond, bool *secure_exec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff815130a0)
Location: security/apparmor/domain.c:622
Inline: False
Direct callers:
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
```
**Symbols:**

```
ffffffff815130a0-ffffffff81513a5e: profile_transition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct aa_label *profile_transition(struct aa_profile *profile, const struct linux_binprm *bprm, char *buffer, struct path_cond *cond, bool *secure_exec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff815199c0)
Location: security/apparmor/domain.c:624
Inline: False
Direct callers:
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
```
**Symbols:**

```
ffffffff815199c0-ffffffff8151a36f: profile_transition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct aa_label *profile_transition(struct aa_profile *profile, const struct linux_binprm *bprm, char *buffer, struct path_cond *cond, bool *secure_exec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/domain.c (0)
Location: security/apparmor/domain.c:624
Inline: False
Direct callers:
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
```
**Symbols:**

```
ffffffff815779e0-ffffffff815783c2: profile_transition (STB_LOCAL)
ffffffff81cd6360-ffffffff81cd63c0: profile_transition.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct aa_label *profile_transition(struct aa_profile *profile, const struct linux_binprm *bprm, char *buffer, struct path_cond *cond, bool *secure_exec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/domain.c (0)
Location: security/apparmor/domain.c:623
Inline: False
Direct callers:
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
```
**Symbols:**

```
ffffffff81615930-ffffffff816162ae: profile_transition (STB_LOCAL)
ffffffff81e8919b-ffffffff81e891ee: profile_transition.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct aa_label *profile_transition(const struct cred *subj_cred, struct aa_profile *profile, const struct linux_binprm *bprm, char *buffer, struct path_cond *cond, bool *secure_exec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff816c8710)
Location: security/apparmor/domain.c:629
Inline: False
Direct callers:
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
```
**Symbols:**

```
ffffffff816c8710-ffffffff816c906f: profile_transition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct aa_label *profile_transition(const struct cred *subj_cred, struct aa_profile *profile, const struct linux_binprm *bprm, char *buffer, struct path_cond *cond, bool *secure_exec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff81701450)
Location: security/apparmor/domain.c:629
Inline: False
Direct callers:
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
```
**Symbols:**

```
ffffffff81701450-ffffffff81701e93: profile_transition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct aa_label *profile_transition(const struct cred *subj_cred, struct aa_profile *profile, const struct linux_binprm *bprm, char *buffer, struct path_cond *cond, bool *secure_exec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff8173ea70)
Location: security/apparmor/domain.c:636
Inline: False
Direct callers:
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
```
**Symbols:**

```
ffffffff8173ea70-ffffffff8173f68f: profile_transition (STB_LOCAL)
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
struct aa_label *profile_transition(struct aa_profile *profile, const struct linux_binprm *bprm, char *buffer, struct path_cond *cond, bool *secure_exec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffff8000105931b0)
Location: security/apparmor/domain.c:617
Inline: False
Direct callers:
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
```
**Symbols:**

```
ffff8000105931b0-ffff800010593968: profile_transition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct aa_label *profile_transition(struct aa_profile *profile, const struct linux_binprm *bprm, char *buffer, struct path_cond *cond, bool *secure_exec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (c0743e88)
Location: security/apparmor/domain.c:617
Inline: False
Direct callers:
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
```
**Symbols:**

```
c0743e88-c07446ec: profile_transition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct aa_label *profile_transition(struct aa_profile *profile, const struct linux_binprm *bprm, char *buffer, struct path_cond *cond, bool *secure_exec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (c000000000707ab0)
Location: security/apparmor/domain.c:617
Inline: False
Direct callers:
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
```
**Symbols:**

```
c000000000707ab0-c000000000708524: profile_transition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct aa_label *profile_transition(struct aa_profile *profile, const struct linux_binprm *bprm, char *buffer, struct path_cond *cond, bool *secure_exec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffe0003e07e6)
Location: security/apparmor/domain.c:617
Inline: False
Direct callers:
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
```
**Symbols:**

```
ffffffe0003e07e6-ffffffe0003e0e9c: profile_transition (STB_LOCAL)
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
struct aa_label *profile_transition(struct aa_profile *profile, const struct linux_binprm *bprm, char *buffer, struct path_cond *cond, bool *secure_exec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff814956a0)
Location: security/apparmor/domain.c:617
Inline: False
Direct callers:
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
```
**Symbols:**

```
ffffffff814956a0-ffffffff81495f04: profile_transition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct aa_label *profile_transition(struct aa_profile *profile, const struct linux_binprm *bprm, char *buffer, struct path_cond *cond, bool *secure_exec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff814860c0)
Location: security/apparmor/domain.c:617
Inline: False
Direct callers:
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
```
**Symbols:**

```
ffffffff814860c0-ffffffff81486924: profile_transition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct aa_label *profile_transition(struct aa_profile *profile, const struct linux_binprm *bprm, char *buffer, struct path_cond *cond, bool *secure_exec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff81491740)
Location: security/apparmor/domain.c:617
Inline: False
Direct callers:
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
```
**Symbols:**

```
ffffffff81491740-ffffffff81491fa4: profile_transition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct aa_label *profile_transition(struct aa_profile *profile, const struct linux_binprm *bprm, char *buffer, struct path_cond *cond, bool *secure_exec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff814a96e0)
Location: security/apparmor/domain.c:617
Inline: False
Direct callers:
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
```
**Symbols:**

```
ffffffff814a96e0-ffffffff814a9fe3: profile_transition (STB_LOCAL)
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
<code>const char *name</code>
</li>
<li>
<b>Param reordered. </b>
<code>profile, name, cond, secure_exec</code> ➡️ <code>profile, bprm, buffer, cond, secure_exec</code>
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
<code>profile, bprm, buffer, cond, secure_exec</code> ➡️ <code>subj_cred, profile, bprm, buffer, cond, secure_exec</code>
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
