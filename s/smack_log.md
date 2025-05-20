# Function: <code>smack_log</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void smack_log(char *subject_label, char *object_label, int request, int result, struct smk_audit_info *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff813626b0)
Location: security/smack/smack_access.c:349
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
  - security/smack/smack_access.c:smk_access
  - security/smack/smack_access.c:smk_tskacc
```
**Symbols:**

```
ffffffff813626b0-ffffffff813627c7: smack_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void smack_log(char *subject_label, char *object_label, int request, int result, struct smk_audit_info *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff81398880)
Location: security/smack/smack_access.c:349
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smack_access.c:smk_access
```
**Symbols:**

```
ffffffff81398880-ffffffff81398998: smack_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void smack_log(char *subject_label, char *object_label, int request, int result, struct smk_audit_info *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff813af460)
Location: security/smack/smack_access.c:344
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smack_access.c:smk_access
```
**Symbols:**

```
ffffffff813af460-ffffffff813af578: smack_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void smack_log(char *subject_label, char *object_label, int request, int result, struct smk_audit_info *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff813c6000)
Location: security/smack/smack_access.c:344
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smack_access.c:smk_access
```
**Symbols:**

```
ffffffff813c6000-ffffffff813c6122: smack_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void smack_log(char *subject_label, char *object_label, int request, int result, struct smk_audit_info *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff813ec2f0)
Location: security/smack/smack_access.c:344
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smack_access.c:smk_access
```
**Symbols:**

```
ffffffff813ec2f0-ffffffff813ec412: smack_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void smack_log(char *subject_label, char *object_label, int request, int result, struct smk_audit_info *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff8141d120)
Location: security/smack/smack_access.c:344
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smack_access.c:smk_access
```
**Symbols:**

```
ffffffff8141d120-ffffffff8141d242: smack_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void smack_log(char *subject_label, char *object_label, int request, int result, struct smk_audit_info *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff81439710)
Location: security/smack/smack_access.c:344
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smack_access.c:smk_access
```
**Symbols:**

```
ffffffff81439710-ffffffff81439832: smack_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void smack_log(char *subject_label, char *object_label, int request, int result, struct smk_audit_info *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff81467330)
Location: security/smack/smack_access.c:340
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smack_access.c:smk_access
```
**Symbols:**

```
ffffffff81467330-ffffffff8146744f: smack_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void smack_log(char *subject_label, char *object_label, int request, int result, struct smk_audit_info *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff81481110)
Location: security/smack/smack_access.c:340
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smack_access.c:smk_access
```
**Symbols:**

```
ffffffff81481110-ffffffff8148122f: smack_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void smack_log(char *subject_label, char *object_label, int request, int result, struct smk_audit_info *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff814d7070)
Location: security/smack/smack_access.c:340
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smack_access.c:smk_access
```
**Symbols:**

```
ffffffff814d7070-ffffffff814d718a: smack_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void smack_log(char *subject_label, char *object_label, int request, int result, struct smk_audit_info *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff814f44e0)
Location: security/smack/smack_access.c:340
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smack_access.c:smk_access
```
**Symbols:**

```
ffffffff814f44e0-ffffffff814f45fa: smack_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void smack_log(char *subject_label, char *object_label, int request, int result, struct smk_audit_info *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff814fb450)
Location: security/smack/smack_access.c:340
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smack_access.c:smk_access
```
**Symbols:**

```
ffffffff814fb450-ffffffff814fb56c: smack_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void smack_log(char *subject_label, char *object_label, int request, int result, struct smk_audit_info *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff815560c0)
Location: security/smack/smack_access.c:339
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smack_access.c:smk_access
```
**Symbols:**

```
ffffffff815560c0-ffffffff815561dc: smack_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void smack_log(char *subject_label, char *object_label, int request, int result, struct smk_audit_info *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff815f0440)
Location: security/smack/smack_access.c:339
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smack_access.c:smk_access
```
**Symbols:**

```
ffffffff815f0440-ffffffff815f0580: smack_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void smack_log(char *subject_label, char *object_label, int request, int result, struct smk_audit_info *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff816a0820)
Location: security/smack/smack_access.c:339
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smack_access.c:smk_access
```
**Symbols:**

```
ffffffff816a0820-ffffffff816a0960: smack_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void smack_log(char *subject_label, char *object_label, int request, int result, struct smk_audit_info *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff816d9160)
Location: security/smack/smack_access.c:339
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smack_access.c:smk_access
```
**Symbols:**

```
ffffffff816d9160-ffffffff816d92a0: smack_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void smack_log(char *subject_label, char *object_label, int request, int result, struct smk_audit_info *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff81715bc0)
Location: security/smack/smack_access.c:339
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smack_access.c:smk_access
```
**Symbols:**

```
ffffffff81715bc0-ffffffff81715d00: smack_log (STB_GLOBAL)
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
void smack_log(char *subject_label, char *object_label, int request, int result, struct smk_audit_info *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffff800010572978)
Location: security/smack/smack_access.c:340
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smack_access.c:smk_access
```
**Symbols:**

```
ffff800010572978-ffff800010572ad4: smack_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void smack_log(char *subject_label, char *object_label, int request, int result, struct smk_audit_info *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (c0725bb8)
Location: security/smack/smack_access.c:340
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smack_access.c:smk_access
```
**Symbols:**

```
c0725bb8-c0725d00: smack_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void smack_log(char *subject_label, char *object_label, int request, int result, struct smk_audit_info *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (c0000000006da7a0)
Location: security/smack/smack_access.c:340
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smack_access.c:smk_access
```
**Symbols:**

```
c0000000006da7a0-c0000000006da950: smack_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void smack_log(char *subject_label, char *object_label, int request, int result, struct smk_audit_info *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffe0003c5fc6)
Location: security/smack/smack_access.c:340
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smack_access.c:smk_access
```
**Symbols:**

```
ffffffe0003c5fc6-ffffffe0003c60e4: smack_log (STB_GLOBAL)
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
void smack_log(char *subject_label, char *object_label, int request, int result, struct smk_audit_info *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff814796f0)
Location: security/smack/smack_access.c:340
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smack_access.c:smk_access
```
**Symbols:**

```
ffffffff814796f0-ffffffff8147980f: smack_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void smack_log(char *subject_label, char *object_label, int request, int result, struct smk_audit_info *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff8146a110)
Location: security/smack/smack_access.c:340
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smack_access.c:smk_access
```
**Symbols:**

```
ffffffff8146a110-ffffffff8146a22f: smack_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void smack_log(char *subject_label, char *object_label, int request, int result, struct smk_audit_info *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff81475790)
Location: security/smack/smack_access.c:340
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smack_access.c:smk_access
```
**Symbols:**

```
ffffffff81475790-ffffffff814758af: smack_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void smack_log(char *subject_label, char *object_label, int request, int result, struct smk_audit_info *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff8148d190)
Location: security/smack/smack_access.c:340
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_file_send_sigiotask
  - security/smack/smack_lsm.c:smk_ptrace_rule_check
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smack_access.c:smk_access
```
**Symbols:**

```
ffffffff8148d190-ffffffff8148d2af: smack_log (STB_GLOBAL)
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
