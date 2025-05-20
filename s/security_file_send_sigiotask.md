# Function: <code>security_file_send_sigiotask</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_file_send_sigiotask(struct task_struct *tsk, struct fown_struct *fown, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133e010)
Location: security/security.c:835
Inline: False
Direct callers:
  - fs/fcntl.c:send_sigio_to_task
  - fs/fcntl.c:send_sigurg
```
**Symbols:**

```
ffffffff8133e010-ffffffff8133e06b: security_file_send_sigiotask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_file_send_sigiotask(struct task_struct *tsk, struct fown_struct *fown, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81373670)
Location: security/security.c:857
Inline: False
Direct callers:
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio_to_task
```
**Symbols:**

```
ffffffff81373670-ffffffff813736cb: security_file_send_sigiotask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_file_send_sigiotask(struct task_struct *tsk, struct fown_struct *fown, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81389fa0)
Location: security/security.c:878
Inline: False
Direct callers:
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio_to_task
```
**Symbols:**

```
ffffffff81389fa0-ffffffff81389ffb: security_file_send_sigiotask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_file_send_sigiotask(struct task_struct *tsk, struct fown_struct *fown, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8139f3a0)
Location: security/security.c:1490
Inline: False
Direct callers:
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio_to_task
```
**Symbols:**

```
ffffffff8139f3a0-ffffffff8139f3fb: security_file_send_sigiotask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_file_send_sigiotask(struct task_struct *tsk, struct fown_struct *fown, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c4f00)
Location: security/security.c:1448
Inline: False
Direct callers:
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio_to_task
```
**Symbols:**

```
ffffffff813c4f00-ffffffff813c4f61: security_file_send_sigiotask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_file_send_sigiotask(struct task_struct *tsk, struct fown_struct *fown, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f5180)
Location: security/security.c:974
Inline: False
Direct callers:
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio_to_task
```
**Symbols:**

```
ffffffff813f5180-ffffffff813f51ce: security_file_send_sigiotask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_file_send_sigiotask(struct task_struct *tsk, struct fown_struct *fown, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814105c0)
Location: security/security.c:1510
Inline: False
Direct callers:
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio_to_task
```
**Symbols:**

```
ffffffff814105c0-ffffffff8141060e: security_file_send_sigiotask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_file_send_sigiotask(struct task_struct *tsk, struct fown_struct *fown, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143dd30)
Location: security/security.c:1529
Inline: False
Direct callers:
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio_to_task
```
**Symbols:**

```
ffffffff8143dd30-ffffffff8143dd87: security_file_send_sigiotask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_file_send_sigiotask(struct task_struct *tsk, struct fown_struct *fown, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81457800)
Location: security/security.c:1568
Inline: False
Direct callers:
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio_to_task
```
**Symbols:**

```
ffffffff81457800-ffffffff8145784c: security_file_send_sigiotask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_file_send_sigiotask(struct task_struct *tsk, struct fown_struct *fown, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814aa600)
Location: security/security.c:1744
Inline: False
Direct callers:
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio_to_task
```
**Symbols:**

```
ffffffff814aa600-ffffffff814aa64c: security_file_send_sigiotask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_file_send_sigiotask(struct task_struct *tsk, struct fown_struct *fown, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c7c10)
Location: security/security.c:1746
Inline: False
Direct callers:
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio_to_task
```
**Symbols:**

```
ffffffff814c7c10-ffffffff814c7c5c: security_file_send_sigiotask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_file_send_sigiotask(struct task_struct *tsk, struct fown_struct *fown, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814ce240)
Location: security/security.c:1796
Inline: False
Direct callers:
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio_to_task
```
**Symbols:**

```
ffffffff814ce240-ffffffff814ce28c: security_file_send_sigiotask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_file_send_sigiotask(struct task_struct *tsk, struct fown_struct *fown, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81526ff0)
Location: security/security.c:1804
Inline: False
Direct callers:
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio_to_task
```
**Symbols:**

```
ffffffff81526ff0-ffffffff8152703c: security_file_send_sigiotask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_file_send_sigiotask(struct task_struct *tsk, struct fown_struct *fown, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815bbc40)
Location: security/security.c:1809
Inline: False
Direct callers:
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio_to_task
```
**Symbols:**

```
ffffffff815bbc40-ffffffff815bbcab: security_file_send_sigiotask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_file_send_sigiotask(struct task_struct *tsk, struct fown_struct *fown, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81667a70)
Location: security/security.c:1851
Inline: False
Direct callers:
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio_to_task
```
**Symbols:**

```
ffffffff81667a70-ffffffff81667adb: security_file_send_sigiotask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_file_send_sigiotask(struct task_struct *tsk, struct fown_struct *fown, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816a0090)
Location: security/security.c:2924
Inline: False
Direct callers:
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio_to_task
```
**Symbols:**

```
ffffffff816a0090-ffffffff816a00fb: security_file_send_sigiotask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_file_send_sigiotask(struct task_struct *tsk, struct fown_struct *fown, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816dc980)
Location: security/security.c:3002
Inline: False
Direct callers:
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio_to_task
```
**Symbols:**

```
ffffffff816dc980-ffffffff816dc9eb: security_file_send_sigiotask (STB_GLOBAL)
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
int security_file_send_sigiotask(struct task_struct *tsk, struct fown_struct *fown, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800010543460)
Location: security/security.c:1568
Inline: False
Direct callers:
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio_to_task
```
**Symbols:**

```
ffff800010543460-ffff8000105434c4: security_file_send_sigiotask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_file_send_sigiotask(struct task_struct *tsk, struct fown_struct *fown, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06f93bc)
Location: security/security.c:1568
Inline: False
Direct callers:
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio_to_task
```
**Symbols:**

```
c06f93bc-c06f9420: security_file_send_sigiotask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_file_send_sigiotask(struct task_struct *tsk, struct fown_struct *fown, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c000000000697410)
Location: security/security.c:1568
Inline: False
Direct callers:
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio_to_task
```
**Symbols:**

```
c000000000697410-c0000000006974e0: security_file_send_sigiotask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_file_send_sigiotask(struct task_struct *tsk, struct fown_struct *fown, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe00039f9bc)
Location: security/security.c:1568
Inline: False
Direct callers:
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio_to_task
```
**Symbols:**

```
ffffffe00039f9bc-ffffffe00039fa08: security_file_send_sigiotask (STB_GLOBAL)
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
int security_file_send_sigiotask(struct task_struct *tsk, struct fown_struct *fown, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144fde0)
Location: security/security.c:1568
Inline: False
Direct callers:
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio_to_task
```
**Symbols:**

```
ffffffff8144fde0-ffffffff8144fe2c: security_file_send_sigiotask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_file_send_sigiotask(struct task_struct *tsk, struct fown_struct *fown, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81440830)
Location: security/security.c:1568
Inline: False
Direct callers:
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio_to_task
```
**Symbols:**

```
ffffffff81440830-ffffffff8144087c: security_file_send_sigiotask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_file_send_sigiotask(struct task_struct *tsk, struct fown_struct *fown, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144be80)
Location: security/security.c:1568
Inline: False
Direct callers:
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio_to_task
```
**Symbols:**

```
ffffffff8144be80-ffffffff8144becc: security_file_send_sigiotask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_file_send_sigiotask(struct task_struct *tsk, struct fown_struct *fown, int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81463250)
Location: security/security.c:1568
Inline: False
Direct callers:
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigurg
  - fs/fcntl.c:send_sigio_to_task
```
**Symbols:**

```
ffffffff81463250-ffffffff8146329c: security_file_send_sigiotask (STB_GLOBAL)
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
