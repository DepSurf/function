# Function: <code>smack_privileged_cred</code>

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
bool smack_privileged_cred(int cap, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff8141d7a0)
Location: security/smack/smack_access.c:636
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_access.c:smack_privileged
```
**Symbols:**

```
ffffffff8141d7a0-ffffffff8141d815: smack_privileged_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool smack_privileged_cred(int cap, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff81439d90)
Location: security/smack/smack_access.c:636
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
  - security/smack/smack_access.c:smack_privileged
```
**Symbols:**

```
ffffffff81439d90-ffffffff81439e0a: smack_privileged_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool smack_privileged_cred(int cap, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff81467950)
Location: security/smack/smack_access.c:632
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
  - security/smack/smack_access.c:smack_privileged
```
**Symbols:**

```
ffffffff81467950-ffffffff814679c4: smack_privileged_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool smack_privileged_cred(int cap, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff81481730)
Location: security/smack/smack_access.c:632
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
  - security/smack/smack_access.c:smack_privileged
```
**Symbols:**

```
ffffffff81481730-ffffffff814817a4: smack_privileged_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool smack_privileged_cred(int cap, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff814d7730)
Location: security/smack/smack_access.c:632
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_watch_key
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
  - security/smack/smack_access.c:smk_tskacc
```
**Symbols:**

```
ffffffff814d7730-ffffffff814d77aa: smack_privileged_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool smack_privileged_cred(int cap, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff814f4c90)
Location: security/smack/smack_access.c:654
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_watch_key
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
  - security/smack/smack_access.c:smk_tskacc
```
**Symbols:**

```
ffffffff814f4c90-ffffffff814f4d14: smack_privileged_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool smack_privileged_cred(int cap, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff814fbc00)
Location: security/smack/smack_access.c:654
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_watch_key
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
  - security/smack/smack_access.c:smk_tskacc
```
**Symbols:**

```
ffffffff814fbc00-ffffffff814fbc84: smack_privileged_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool smack_privileged_cred(int cap, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff81556870)
Location: security/smack/smack_access.c:656
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_watch_key
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
  - security/smack/smack_access.c:smk_tskacc
```
**Symbols:**

```
ffffffff81556870-ffffffff815568f4: smack_privileged_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool smack_privileged_cred(int cap, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff815f0c80)
Location: security/smack/smack_access.c:653
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_uring_sqpoll
  - security/smack/smack_lsm.c:smack_uring_override_creds
  - security/smack/smack_lsm.c:smack_watch_key
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
  - security/smack/smack_access.c:smk_tskacc
```
**Symbols:**

```
ffffffff815f0c80-ffffffff815f0d1d: smack_privileged_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool smack_privileged_cred(int cap, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff816a10e0)
Location: security/smack/smack_access.c:650
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_uring_sqpoll
  - security/smack/smack_lsm.c:smack_uring_override_creds
  - security/smack/smack_lsm.c:smack_watch_key
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
  - security/smack/smack_access.c:smk_tskacc
```
**Symbols:**

```
ffffffff816a10e0-ffffffff816a117d: smack_privileged_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool smack_privileged_cred(int cap, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff816d9a20)
Location: security/smack/smack_access.c:650
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_uring_sqpoll
  - security/smack/smack_lsm.c:smack_uring_override_creds
  - security/smack/smack_lsm.c:smack_watch_key
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
  - security/smack/smack_access.c:smk_tskacc
```
**Symbols:**

```
ffffffff816d9a20-ffffffff816d9abd: smack_privileged_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool smack_privileged_cred(int cap, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff817164c0)
Location: security/smack/smack_access.c:650
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_uring_sqpoll
  - security/smack/smack_lsm.c:smack_uring_override_creds
  - security/smack/smack_lsm.c:smack_watch_key
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
  - security/smack/smack_access.c:smk_tskacc
```
**Symbols:**

```
ffffffff817164c0-ffffffff81716560: smack_privileged_cred (STB_GLOBAL)
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
bool smack_privileged_cred(int cap, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffff800010573120)
Location: security/smack/smack_access.c:632
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
  - security/smack/smack_access.c:smack_privileged
```
**Symbols:**

```
ffff800010573120-ffff8000105731dc: smack_privileged_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool smack_privileged_cred(int cap, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (c072629c)
Location: security/smack/smack_access.c:632
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
  - security/smack/smack_access.c:smack_privileged
```
**Symbols:**

```
c072629c-c072633c: smack_privileged_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool smack_privileged_cred(int cap, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (c0000000006db3b0)
Location: security/smack/smack_access.c:632
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
  - security/smack/smack_access.c:smack_privileged
```
**Symbols:**

```
c0000000006db3b0-c0000000006db4a8: smack_privileged_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool smack_privileged_cred(int cap, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffe0003c6620)
Location: security/smack/smack_access.c:632
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
  - security/smack/smack_access.c:smack_privileged
```
**Symbols:**

```
ffffffe0003c6620-ffffffe0003c66b8: smack_privileged_cred (STB_GLOBAL)
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
bool smack_privileged_cred(int cap, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff81479d10)
Location: security/smack/smack_access.c:632
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
  - security/smack/smack_access.c:smack_privileged
```
**Symbols:**

```
ffffffff81479d10-ffffffff81479d84: smack_privileged_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool smack_privileged_cred(int cap, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff8146a730)
Location: security/smack/smack_access.c:632
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
  - security/smack/smack_access.c:smack_privileged
```
**Symbols:**

```
ffffffff8146a730-ffffffff8146a7a4: smack_privileged_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool smack_privileged_cred(int cap, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff81475db0)
Location: security/smack/smack_access.c:632
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
  - security/smack/smack_access.c:smack_privileged
```
**Symbols:**

```
ffffffff81475db0-ffffffff81475e24: smack_privileged_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool smack_privileged_cred(int cap, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff8148d820)
Location: security/smack/smack_access.c:632
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_key_permission
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
  - security/smack/smack_access.c:smack_privileged
```
**Symbols:**

```
ffffffff8148d820-ffffffff8148d8a6: smack_privileged_cred (STB_GLOBAL)
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
