# Function: <code>handle_onexec</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct aa_label *handle_onexec(struct aa_label *label, struct aa_label *onexec, bool stack, const char *xname, struct path_cond *cond, bool *unsafe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff8137beb0)
Location: security/apparmor/domain.c:619
Inline: False
Direct callers:
  - security/apparmor/domain.c:apparmor_bprm_set_creds
```
**Symbols:**

```
ffffffff8137beb0-ffffffff8137ce06: handle_onexec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct aa_label *handle_onexec(struct aa_label *label, struct aa_label *onexec, bool stack, const struct linux_binprm *bprm, char *buffer, struct path_cond *cond, bool *unsafe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff813b5200)
Location: security/apparmor/domain.c:651
Inline: False
Direct callers:
  - security/apparmor/domain.c:apparmor_bprm_set_creds
```
**Symbols:**

```
ffffffff813b5200-ffffffff813b6420: handle_onexec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct aa_label *handle_onexec(struct aa_label *label, struct aa_label *onexec, bool stack, const struct linux_binprm *bprm, char *buffer, struct path_cond *cond, bool *unsafe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff813cc560)
Location: security/apparmor/domain.c:685
Inline: False
Direct callers:
  - security/apparmor/domain.c:apparmor_bprm_set_creds
```
**Symbols:**

```
ffffffff813cc560-ffffffff813cd780: handle_onexec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct aa_label *handle_onexec(struct aa_label *label, struct aa_label *onexec, bool stack, const struct linux_binprm *bprm, char *buffer, struct path_cond *cond, bool *unsafe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff813e11a0)
Location: security/apparmor/domain.c:687
Inline: False
Direct callers:
  - security/apparmor/domain.c:apparmor_bprm_set_creds
```
**Symbols:**

```
ffffffff813e11a0-ffffffff813e1dda: handle_onexec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct aa_label *handle_onexec(struct aa_label *label, struct aa_label *onexec, bool stack, const struct linux_binprm *bprm, char *buffer, struct path_cond *cond, bool *unsafe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff81407d40)
Location: security/apparmor/domain.c:720
Inline: False
Direct callers:
  - security/apparmor/domain.c:apparmor_bprm_set_creds
```
**Symbols:**

```
ffffffff81407d40-ffffffff814089e2: handle_onexec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct aa_label *handle_onexec(struct aa_label *label, struct aa_label *onexec, bool stack, const struct linux_binprm *bprm, char *buffer, struct path_cond *cond, bool *unsafe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff814393d0)
Location: security/apparmor/domain.c:815
Inline: False
Direct callers:
  - security/apparmor/domain.c:apparmor_bprm_set_creds
```
**Symbols:**

```
ffffffff814393d0-ffffffff8143a0a6: handle_onexec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct aa_label *handle_onexec(struct aa_label *label, struct aa_label *onexec, bool stack, const struct linux_binprm *bprm, char *buffer, struct path_cond *cond, bool *unsafe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff81456050)
Location: security/apparmor/domain.c:815
Inline: False
Direct callers:
  - security/apparmor/domain.c:apparmor_bprm_set_creds
```
**Symbols:**

```
ffffffff81456050-ffffffff81456dcd: handle_onexec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct aa_label *handle_onexec(struct aa_label *label, struct aa_label *onexec, bool stack, const struct linux_binprm *bprm, char *buffer, struct path_cond *cond, bool *unsafe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff81483a10)
Location: security/apparmor/domain.c:811
Inline: False
Direct callers:
  - security/apparmor/domain.c:apparmor_bprm_set_creds
```
**Symbols:**

```
ffffffff81483a10-ffffffff81484678: handle_onexec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct aa_label *handle_onexec(struct aa_label *label, struct aa_label *onexec, bool stack, const struct linux_binprm *bprm, char *buffer, struct path_cond *cond, bool *unsafe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff8149d930)
Location: security/apparmor/domain.c:815
Inline: False
Direct callers:
  - security/apparmor/domain.c:apparmor_bprm_set_creds
```
**Symbols:**

```
ffffffff8149d930-ffffffff8149e598: handle_onexec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct aa_label *handle_onexec(struct aa_label *label, struct aa_label *onexec, bool stack, const struct linux_binprm *bprm, char *buffer, struct path_cond *cond, bool *unsafe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff814f68a0)
Location: security/apparmor/domain.c:792
Inline: False
Direct callers:
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
```
**Symbols:**

```
ffffffff814f68a0-ffffffff814f7876: handle_onexec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct aa_label *handle_onexec(struct aa_label *label, struct aa_label *onexec, bool stack, const struct linux_binprm *bprm, char *buffer, struct path_cond *cond, bool *unsafe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff81513a60)
Location: security/apparmor/domain.c:792
Inline: False
Direct callers:
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
```
**Symbols:**

```
ffffffff81513a60-ffffffff815149c7: handle_onexec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct aa_label *handle_onexec(struct aa_label *label, struct aa_label *onexec, bool stack, const struct linux_binprm *bprm, char *buffer, struct path_cond *cond, bool *unsafe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff8151a370)
Location: security/apparmor/domain.c:794
Inline: False
Direct callers:
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
```
**Symbols:**

```
ffffffff8151a370-ffffffff8151b279: handle_onexec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct aa_label *handle_onexec(struct aa_label *label, struct aa_label *onexec, bool stack, const struct linux_binprm *bprm, char *buffer, struct path_cond *cond, bool *unsafe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/domain.c (0)
Location: security/apparmor/domain.c:794
Inline: False
Direct callers:
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
```
**Symbols:**

```
ffffffff815783d0-ffffffff815792f7: handle_onexec (STB_LOCAL)
ffffffff81cd63c0-ffffffff81cd63ea: handle_onexec.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct aa_label *handle_onexec(struct aa_label *label, struct aa_label *onexec, bool stack, const struct linux_binprm *bprm, char *buffer, struct path_cond *cond, bool *unsafe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/domain.c (0)
Location: security/apparmor/domain.c:797
Inline: False
Direct callers:
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
```
**Symbols:**

```
ffffffff816162b0-ffffffff816173ee: handle_onexec (STB_LOCAL)
ffffffff81e891ee-ffffffff81e89218: handle_onexec.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/domain.c (ffffffff816c9080)
Location: security/apparmor/domain.c:806
Inline: True
Direct callers:
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
```
**Symbols:**

```
ffffffff816c9080-ffffffff816ca247: handle_onexec.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct aa_label *handle_onexec(const struct cred *subj_cred, struct aa_label *label, struct aa_label *onexec, bool stack, const struct linux_binprm *bprm, char *buffer, struct path_cond *cond, bool *unsafe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff81701eb0)
Location: security/apparmor/domain.c:806
Inline: False
Direct callers:
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
```
**Symbols:**

```
ffffffff81701eb0-ffffffff81702efb: handle_onexec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct aa_label *handle_onexec(const struct cred *subj_cred, struct aa_label *label, struct aa_label *onexec, bool stack, const struct linux_binprm *bprm, char *buffer, struct path_cond *cond, bool *unsafe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff8173f6a0)
Location: security/apparmor/domain.c:813
Inline: False
Direct callers:
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
```
**Symbols:**

```
ffffffff8173f6a0-ffffffff817406eb: handle_onexec (STB_LOCAL)
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
struct aa_label *handle_onexec(struct aa_label *label, struct aa_label *onexec, bool stack, const struct linux_binprm *bprm, char *buffer, struct path_cond *cond, bool *unsafe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffff800010593968)
Location: security/apparmor/domain.c:815
Inline: False
Direct callers:
  - security/apparmor/domain.c:apparmor_bprm_set_creds
```
**Symbols:**

```
ffff800010593968-ffff8000105944a8: handle_onexec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct aa_label *handle_onexec(struct aa_label *label, struct aa_label *onexec, bool stack, const struct linux_binprm *bprm, char *buffer, struct path_cond *cond, bool *unsafe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (c07446ec)
Location: security/apparmor/domain.c:815
Inline: False
Direct callers:
  - security/apparmor/domain.c:apparmor_bprm_set_creds
```
**Symbols:**

```
c07446ec-c0745348: handle_onexec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct aa_label *handle_onexec(struct aa_label *label, struct aa_label *onexec, bool stack, const struct linux_binprm *bprm, char *buffer, struct path_cond *cond, bool *unsafe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (c000000000708530)
Location: security/apparmor/domain.c:815
Inline: False
Direct callers:
  - security/apparmor/domain.c:apparmor_bprm_set_creds
```
**Symbols:**

```
c000000000708530-c0000000007093b4: handle_onexec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct aa_label *handle_onexec(struct aa_label *label, struct aa_label *onexec, bool stack, const struct linux_binprm *bprm, char *buffer, struct path_cond *cond, bool *unsafe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffe0003e0e9c)
Location: security/apparmor/domain.c:815
Inline: False
Direct callers:
  - security/apparmor/domain.c:apparmor_bprm_set_creds
```
**Symbols:**

```
ffffffe0003e0e9c-ffffffe0003e1794: handle_onexec (STB_LOCAL)
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
struct aa_label *handle_onexec(struct aa_label *label, struct aa_label *onexec, bool stack, const struct linux_binprm *bprm, char *buffer, struct path_cond *cond, bool *unsafe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff81495f10)
Location: security/apparmor/domain.c:815
Inline: False
Direct callers:
  - security/apparmor/domain.c:apparmor_bprm_set_creds
```
**Symbols:**

```
ffffffff81495f10-ffffffff81496b78: handle_onexec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct aa_label *handle_onexec(struct aa_label *label, struct aa_label *onexec, bool stack, const struct linux_binprm *bprm, char *buffer, struct path_cond *cond, bool *unsafe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff81486930)
Location: security/apparmor/domain.c:815
Inline: False
Direct callers:
  - security/apparmor/domain.c:apparmor_bprm_set_creds
```
**Symbols:**

```
ffffffff81486930-ffffffff81487598: handle_onexec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct aa_label *handle_onexec(struct aa_label *label, struct aa_label *onexec, bool stack, const struct linux_binprm *bprm, char *buffer, struct path_cond *cond, bool *unsafe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff81491fb0)
Location: security/apparmor/domain.c:815
Inline: False
Direct callers:
  - security/apparmor/domain.c:apparmor_bprm_set_creds
```
**Symbols:**

```
ffffffff81491fb0-ffffffff81492c18: handle_onexec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct aa_label *handle_onexec(struct aa_label *label, struct aa_label *onexec, bool stack, const struct linux_binprm *bprm, char *buffer, struct path_cond *cond, bool *unsafe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff814a9ff0)
Location: security/apparmor/domain.c:815
Inline: False
Direct callers:
  - security/apparmor/domain.c:apparmor_bprm_set_creds
```
**Symbols:**

```
ffffffff814a9ff0-ffffffff814aac71: handle_onexec (STB_LOCAL)
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
<code>label, onexec, stack, xname, cond, unsafe</code> ➡️ <code>label, onexec, stack, bprm, buffer, cond, unsafe</code>
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
