# Function: <code>security_bprm_creds_from_file</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_bprm_creds_from_file(struct linux_binprm *bprm, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814a9490)
Location: security/security.c:1001
Inline: False
Direct callers:
  - fs/exec.c:begin_new_exec
```
**Symbols:**

```
ffffffff814a9490-ffffffff814a94d4: security_bprm_creds_from_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_bprm_creds_from_file(struct linux_binprm *bprm, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c6a90)
Location: security/security.c:1003
Inline: False
Direct callers:
  - fs/exec.c:begin_new_exec
```
**Symbols:**

```
ffffffff814c6a90-ffffffff814c6ad4: security_bprm_creds_from_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_bprm_creds_from_file(struct linux_binprm *bprm, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814ccb80)
Location: security/security.c:1027
Inline: False
Direct callers:
  - fs/exec.c:begin_new_exec
```
**Symbols:**

```
ffffffff814ccb80-ffffffff814ccbc4: security_bprm_creds_from_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_bprm_creds_from_file(struct linux_binprm *bprm, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81525d00)
Location: security/security.c:1027
Inline: False
Direct callers:
  - fs/exec.c:begin_new_exec
```
**Symbols:**

```
ffffffff81525d00-ffffffff81525d44: security_bprm_creds_from_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_bprm_creds_from_file(struct linux_binprm *bprm, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815ba000)
Location: security/security.c:1026
Inline: False
Direct callers:
  - fs/exec.c:begin_new_exec
```
**Symbols:**

```
ffffffff815ba000-ffffffff815ba05d: security_bprm_creds_from_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_bprm_creds_from_file(struct linux_binprm *bprm, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816658b0)
Location: security/security.c:1024
Inline: False
Direct callers:
  - fs/exec.c:begin_new_exec
```
**Symbols:**

```
ffffffff816658b0-ffffffff8166590d: security_bprm_creds_from_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_bprm_creds_from_file(struct linux_binprm *bprm, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8169de30)
Location: security/security.c:1217
Inline: False
Direct callers:
  - fs/exec.c:begin_new_exec
```
**Symbols:**

```
ffffffff8169de30-ffffffff8169de8d: security_bprm_creds_from_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_bprm_creds_from_file(struct linux_binprm *bprm, const struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816da760)
Location: security/security.c:1260
Inline: False
Direct callers:
  - fs/exec.c:begin_new_exec
```
**Symbols:**

```
ffffffff816da760-ffffffff816da7bd: security_bprm_creds_from_file (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct file *file</code> ➡️ <code>const struct file *file</code>
</li>
</ul>
</details>
</li>
</ul>
