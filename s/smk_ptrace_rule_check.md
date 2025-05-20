# Function: <code>smk_ptrace_rule_check</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int smk_ptrace_rule_check(struct task_struct *tracer, struct smack_known *tracee_known, unsigned int mode, const char *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81360490)
Location: security/smack/smack_lsm.c:418
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_bprm_set_creds
  - security/smack/smack_lsm.c:smack_ptrace_traceme
  - security/smack/smack_lsm.c:smack_ptrace_access_check
```
**Symbols:**

```
ffffffff81360490-ffffffff813605ad: smk_ptrace_rule_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int smk_ptrace_rule_check(struct task_struct *tracer, struct smack_known *tracee_known, unsigned int mode, const char *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81396a00)
Location: security/smack/smack_lsm.c:418
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_bprm_set_creds
  - security/smack/smack_lsm.c:smack_ptrace_traceme
  - security/smack/smack_lsm.c:smack_ptrace_access_check
```
**Symbols:**

```
ffffffff81396a00-ffffffff81396b1d: smk_ptrace_rule_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int smk_ptrace_rule_check(struct task_struct *tracer, struct smack_known *tracee_known, unsigned int mode, const char *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff813ad190)
Location: security/smack/smack_lsm.c:418
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_bprm_set_creds
  - security/smack/smack_lsm.c:smack_ptrace_traceme
  - security/smack/smack_lsm.c:smack_ptrace_access_check
```
**Symbols:**

```
ffffffff813ad190-ffffffff813ad2ad: smk_ptrace_rule_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int smk_ptrace_rule_check(struct task_struct *tracer, struct smack_known *tracee_known, unsigned int mode, const char *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff813c58f0)
Location: security/smack/smack_lsm.c:400
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_bprm_set_creds
  - security/smack/smack_lsm.c:smack_ptrace_traceme
  - security/smack/smack_lsm.c:smack_ptrace_access_check
```
**Symbols:**

```
ffffffff813c58f0-ffffffff813c5a14: smk_ptrace_rule_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int smk_ptrace_rule_check(struct task_struct *tracer, struct smack_known *tracee_known, unsigned int mode, const char *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff813ebbe0)
Location: security/smack/smack_lsm.c:400
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_bprm_set_creds
  - security/smack/smack_lsm.c:smack_ptrace_traceme
  - security/smack/smack_lsm.c:smack_ptrace_access_check
```
**Symbols:**

```
ffffffff813ebbe0-ffffffff813ebd04: smk_ptrace_rule_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int smk_ptrace_rule_check(struct task_struct *tracer, struct smack_known *tracee_known, unsigned int mode, const char *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff8141c550)
Location: security/smack/smack_lsm.c:415
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_bprm_set_creds
  - security/smack/smack_lsm.c:smack_ptrace_traceme
  - security/smack/smack_lsm.c:smack_ptrace_access_check
```
**Symbols:**

```
ffffffff8141c550-ffffffff8141c66a: smk_ptrace_rule_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int smk_ptrace_rule_check(struct task_struct *tracer, struct smack_known *tracee_known, unsigned int mode, const char *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81439210)
Location: security/smack/smack_lsm.c:418
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_bprm_set_creds
  - security/smack/smack_lsm.c:smack_ptrace_traceme
  - security/smack/smack_lsm.c:smack_ptrace_access_check
```
**Symbols:**

```
ffffffff81439210-ffffffff8143932f: smk_ptrace_rule_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int smk_ptrace_rule_check(struct task_struct *tracer, struct smack_known *tracee_known, unsigned int mode, const char *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81466f70)
Location: security/smack/smack_lsm.c:419
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_bprm_set_creds
  - security/smack/smack_lsm.c:smack_ptrace_traceme
  - security/smack/smack_lsm.c:smack_ptrace_access_check
```
**Symbols:**

```
ffffffff81466f70-ffffffff81467091: smk_ptrace_rule_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int smk_ptrace_rule_check(struct task_struct *tracer, struct smack_known *tracee_known, unsigned int mode, const char *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81480d50)
Location: security/smack/smack_lsm.c:419
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_bprm_set_creds
  - security/smack/smack_lsm.c:smack_ptrace_traceme
  - security/smack/smack_lsm.c:smack_ptrace_access_check
```
**Symbols:**

```
ffffffff81480d50-ffffffff81480e71: smk_ptrace_rule_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int smk_ptrace_rule_check(struct task_struct *tracer, struct smack_known *tracee_known, unsigned int mode, const char *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff814d6320)
Location: security/smack/smack_lsm.c:415
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_bprm_creds_for_exec
  - security/smack/smack_lsm.c:smack_ptrace_traceme
  - security/smack/smack_lsm.c:smack_ptrace_access_check
```
**Symbols:**

```
ffffffff814d6320-ffffffff814d6441: smk_ptrace_rule_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int smk_ptrace_rule_check(struct task_struct *tracer, struct smack_known *tracee_known, unsigned int mode, const char *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff814f3ff0)
Location: security/smack/smack_lsm.c:415
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_bprm_creds_for_exec
  - security/smack/smack_lsm.c:smack_ptrace_traceme
  - security/smack/smack_lsm.c:smack_ptrace_access_check
```
**Symbols:**

```
ffffffff814f3ff0-ffffffff814f4121: smk_ptrace_rule_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int smk_ptrace_rule_check(struct task_struct *tracer, struct smack_known *tracee_known, unsigned int mode, const char *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff814faf80)
Location: security/smack/smack_lsm.c:415
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_bprm_creds_for_exec
  - security/smack/smack_lsm.c:smack_ptrace_traceme
  - security/smack/smack_lsm.c:smack_ptrace_access_check
```
**Symbols:**

```
ffffffff814faf80-ffffffff814fb0a8: smk_ptrace_rule_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int smk_ptrace_rule_check(struct task_struct *tracer, struct smack_known *tracee_known, unsigned int mode, const char *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81555bf0)
Location: security/smack/smack_lsm.c:415
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_bprm_creds_for_exec
  - security/smack/smack_lsm.c:smack_ptrace_traceme
  - security/smack/smack_lsm.c:smack_ptrace_access_check
```
**Symbols:**

```
ffffffff81555bf0-ffffffff81555d18: smk_ptrace_rule_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int smk_ptrace_rule_check(struct task_struct *tracer, struct smack_known *tracee_known, unsigned int mode, const char *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff815ef9d0)
Location: security/smack/smack_lsm.c:418
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_bprm_creds_for_exec
  - security/smack/smack_lsm.c:smack_ptrace_traceme
  - security/smack/smack_lsm.c:smack_ptrace_access_check
```
**Symbols:**

```
ffffffff815ef9d0-ffffffff815efb29: smk_ptrace_rule_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int smk_ptrace_rule_check(struct task_struct *tracer, struct smack_known *tracee_known, unsigned int mode, const char *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff8169fd30)
Location: security/smack/smack_lsm.c:419
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_bprm_creds_for_exec
  - security/smack/smack_lsm.c:smack_ptrace_traceme
  - security/smack/smack_lsm.c:smack_ptrace_access_check
```
**Symbols:**

```
ffffffff8169fd30-ffffffff8169fe7c: smk_ptrace_rule_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int smk_ptrace_rule_check(struct task_struct *tracer, struct smack_known *tracee_known, unsigned int mode, const char *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff816d85c0)
Location: security/smack/smack_lsm.c:419
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_bprm_creds_for_exec
  - security/smack/smack_lsm.c:smack_ptrace_traceme
  - security/smack/smack_lsm.c:smack_ptrace_access_check
```
**Symbols:**

```
ffffffff816d85c0-ffffffff816d870c: smk_ptrace_rule_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int smk_ptrace_rule_check(struct task_struct *tracer, struct smack_known *tracee_known, unsigned int mode, const char *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81714d90)
Location: security/smack/smack_lsm.c:429
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_bprm_creds_for_exec
  - security/smack/smack_lsm.c:smack_ptrace_traceme
  - security/smack/smack_lsm.c:smack_ptrace_access_check
```
**Symbols:**

```
ffffffff81714d90-ffffffff81714edf: smk_ptrace_rule_check (STB_LOCAL)
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
int smk_ptrace_rule_check(struct task_struct *tracer, struct smack_known *tracee_known, unsigned int mode, const char *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffff8000105724a8)
Location: security/smack/smack_lsm.c:419
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_bprm_set_creds
  - security/smack/smack_lsm.c:smack_ptrace_traceme
  - security/smack/smack_lsm.c:smack_ptrace_access_check
```
**Symbols:**

```
ffff8000105724a8-ffff8000105725ec: smk_ptrace_rule_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int smk_ptrace_rule_check(struct task_struct *tracer, struct smack_known *tracee_known, unsigned int mode, const char *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (c0725784)
Location: security/smack/smack_lsm.c:419
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_bprm_set_creds
  - security/smack/smack_lsm.c:smack_ptrace_traceme
  - security/smack/smack_lsm.c:smack_ptrace_access_check
```
**Symbols:**

```
c0725784-c07258cc: smk_ptrace_rule_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int smk_ptrace_rule_check(struct task_struct *tracer, struct smack_known *tracee_known, unsigned int mode, const char *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (c0000000006da1c0)
Location: security/smack/smack_lsm.c:419
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_bprm_set_creds
  - security/smack/smack_lsm.c:smack_ptrace_traceme
  - security/smack/smack_lsm.c:smack_ptrace_access_check
```
**Symbols:**

```
c0000000006da1c0-c0000000006da378: smk_ptrace_rule_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int smk_ptrace_rule_check(struct task_struct *tracer, struct smack_known *tracee_known, unsigned int mode, const char *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffe0003c3ed2)
Location: security/smack/smack_lsm.c:419
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_bprm_set_creds
  - security/smack/smack_lsm.c:smack_ptrace_traceme
  - security/smack/smack_lsm.c:smack_ptrace_access_check
```
**Symbols:**

```
ffffffe0003c3ed2-ffffffe0003c3fc4: smk_ptrace_rule_check (STB_LOCAL)
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
int smk_ptrace_rule_check(struct task_struct *tracer, struct smack_known *tracee_known, unsigned int mode, const char *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81479330)
Location: security/smack/smack_lsm.c:419
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_bprm_set_creds
  - security/smack/smack_lsm.c:smack_ptrace_traceme
  - security/smack/smack_lsm.c:smack_ptrace_access_check
```
**Symbols:**

```
ffffffff81479330-ffffffff81479451: smk_ptrace_rule_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int smk_ptrace_rule_check(struct task_struct *tracer, struct smack_known *tracee_known, unsigned int mode, const char *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81469d50)
Location: security/smack/smack_lsm.c:419
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_bprm_set_creds
  - security/smack/smack_lsm.c:smack_ptrace_traceme
  - security/smack/smack_lsm.c:smack_ptrace_access_check
```
**Symbols:**

```
ffffffff81469d50-ffffffff81469e71: smk_ptrace_rule_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int smk_ptrace_rule_check(struct task_struct *tracer, struct smack_known *tracee_known, unsigned int mode, const char *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff814753d0)
Location: security/smack/smack_lsm.c:419
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_bprm_set_creds
  - security/smack/smack_lsm.c:smack_ptrace_traceme
  - security/smack/smack_lsm.c:smack_ptrace_access_check
```
**Symbols:**

```
ffffffff814753d0-ffffffff814754f1: smk_ptrace_rule_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int smk_ptrace_rule_check(struct task_struct *tracer, struct smack_known *tracee_known, unsigned int mode, const char *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff8148cd70)
Location: security/smack/smack_lsm.c:419
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_bprm_set_creds
  - security/smack/smack_lsm.c:smack_ptrace_traceme
  - security/smack/smack_lsm.c:smack_ptrace_access_check
```
**Symbols:**

```
ffffffff8148cd70-ffffffff8148ceac: smk_ptrace_rule_check (STB_LOCAL)
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
