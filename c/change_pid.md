# Function: <code>change_pid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void change_pid(struct task_struct *task, enum pid_type type, struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff8109e650)
Location: kernel/pid.c:420
Inline: False
Direct callers:
  - kernel/sys.c:SyS_setpgid
  - kernel/sys.c:sys_setsid
  - kernel/sys.c:sys_setsid
```
**Symbols:**

```
ffffffff8109e650-ffffffff8109e6b0: change_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void change_pid(struct task_struct *task, enum pid_type type, struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a1cf0)
Location: kernel/pid.c:420
Inline: False
Direct callers:
  - kernel/sys.c:sys_setsid
  - kernel/sys.c:sys_setsid
  - kernel/sys.c:SyS_setpgid
```
**Symbols:**

```
ffffffff810a1cf0-ffffffff810a1d4c: change_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void change_pid(struct task_struct *task, enum pid_type type, struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a6db0)
Location: kernel/pid.c:420
Inline: False
Direct callers:
  - kernel/sys.c:sys_setsid
  - kernel/sys.c:sys_setsid
  - kernel/sys.c:SyS_setpgid
```
**Symbols:**

```
ffffffff810a6db0-ffffffff810a6e0c: change_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void change_pid(struct task_struct *task, enum pid_type type, struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a3cf0)
Location: kernel/pid.c:421
Inline: False
Direct callers:
  - kernel/sys.c:sys_setsid
  - kernel/sys.c:sys_setsid
  - kernel/sys.c:SyS_setpgid
```
**Symbols:**

```
ffffffff810a3cf0-ffffffff810a3d4c: change_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void change_pid(struct task_struct *task, enum pid_type type, struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810aa2e0)
Location: kernel/pid.c:290
Inline: False
Direct callers:
  - kernel/sys.c:sys_setsid
  - kernel/sys.c:sys_setsid
  - kernel/sys.c:SyS_setpgid
```
**Symbols:**

```
ffffffff810aa2e0-ffffffff810aa33c: change_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void change_pid(struct task_struct *task, enum pid_type type, struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810b0ef0)
Location: kernel/pid.c:302
Inline: False
Direct callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
```
**Symbols:**

```
ffffffff810b0ef0-ffffffff810b0f4c: change_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void change_pid(struct task_struct *task, enum pid_type type, struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810ba010)
Location: kernel/pid.c:310
Inline: False
Direct callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
```
**Symbols:**

```
ffffffff810ba010-ffffffff810ba087: change_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void change_pid(struct task_struct *task, enum pid_type type, struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810bff20)
Location: kernel/pid.c:313
Inline: False
Direct callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - fs/exec.c:de_thread
```
**Symbols:**

```
ffffffff810bff20-ffffffff810bff96: change_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void change_pid(struct task_struct *task, enum pid_type type, struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c62f0)
Location: kernel/pid.c:313
Inline: False
Direct callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - fs/exec.c:de_thread
```
**Symbols:**

```
ffffffff810c62f0-ffffffff810c6367: change_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void change_pid(struct task_struct *task, enum pid_type type, struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810ce160)
Location: kernel/pid.c:360
Inline: False
Direct callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__do_sys_setpgid
```
**Symbols:**

```
ffffffff810ce160-ffffffff810ce1ca: change_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void change_pid(struct task_struct *task, enum pid_type type, struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c8c30)
Location: kernel/pid.c:361
Inline: False
Direct callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__do_sys_setpgid
```
**Symbols:**

```
ffffffff810c8c30-ffffffff810c8c9e: change_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void change_pid(struct task_struct *task, enum pid_type type, struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810ca6d0)
Location: kernel/pid.c:361
Inline: False
Direct callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__do_sys_setpgid
```
**Symbols:**

```
ffffffff810ca6d0-ffffffff810ca73b: change_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void change_pid(struct task_struct *task, enum pid_type type, struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810dd570)
Location: kernel/pid.c:361
Inline: False
Direct callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__do_sys_setpgid
```
**Symbols:**

```
ffffffff810dd570-ffffffff810dd627: change_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void change_pid(struct task_struct *task, enum pid_type type, struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810f6e70)
Location: kernel/pid.c:361
Inline: False
Direct callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__do_sys_setpgid
```
**Symbols:**

```
ffffffff810f6e70-ffffffff810f6f33: change_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void change_pid(struct task_struct *task, enum pid_type type, struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff81119590)
Location: kernel/pid.c:361
Inline: False
Direct callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__do_sys_setpgid
```
**Symbols:**

```
ffffffff81119590-ffffffff81119657: change_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void change_pid(struct task_struct *task, enum pid_type type, struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff81126a70)
Location: kernel/pid.c:364
Inline: False
Direct callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__do_sys_setpgid
```
**Symbols:**

```
ffffffff81126a70-ffffffff81126b3e: change_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void change_pid(struct task_struct *task, enum pid_type type, struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff81131050)
Location: kernel/pid.c:364
Inline: False
Direct callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__do_sys_setpgid
```
**Symbols:**

```
ffffffff81131050-ffffffff81131113: change_pid (STB_GLOBAL)
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
void change_pid(struct task_struct *task, enum pid_type type, struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffff800010124b28)
Location: kernel/pid.c:313
Inline: False
Direct callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__arm64_sys_setpgid
  - fs/exec.c:de_thread
```
**Symbols:**

```
ffff800010124b28-ffff800010124bb8: change_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void change_pid(struct task_struct *task, enum pid_type type, struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (c0377b0c)
Location: kernel/pid.c:313
Inline: False
Direct callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__se_sys_setpgid
  - fs/exec.c:de_thread
```
**Symbols:**

```
c0377b0c-c0377b74: change_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void change_pid(struct task_struct *task, enum pid_type type, struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (c00000000016e8b0)
Location: kernel/pid.c:313
Inline: False
Direct callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__se_sys_setpgid
  - fs/exec.c:de_thread
```
**Symbols:**

```
c00000000016e8b0-c00000000016e964: change_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void change_pid(struct task_struct *task, enum pid_type type, struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffe0000dcad0)
Location: kernel/pid.c:313
Inline: False
Direct callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__se_sys_setpgid
  - fs/exec.c:de_thread
```
**Symbols:**

```
ffffffe0000dcad0-ffffffe0000dcb5a: change_pid (STB_GLOBAL)
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
void change_pid(struct task_struct *task, enum pid_type type, struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c0670)
Location: kernel/pid.c:313
Inline: False
Direct callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - fs/exec.c:de_thread
```
**Symbols:**

```
ffffffff810c0670-ffffffff810c06e6: change_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void change_pid(struct task_struct *task, enum pid_type type, struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810aee70)
Location: kernel/pid.c:313
Inline: False
Direct callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - fs/exec.c:de_thread
```
**Symbols:**

```
ffffffff810aee70-ffffffff810aeee7: change_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void change_pid(struct task_struct *task, enum pid_type type, struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810bfbc0)
Location: kernel/pid.c:313
Inline: False
Direct callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - fs/exec.c:de_thread
```
**Symbols:**

```
ffffffff810bfbc0-ffffffff810bfc37: change_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void change_pid(struct task_struct *task, enum pid_type type, struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c7fd0)
Location: kernel/pid.c:313
Inline: False
Direct callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - fs/exec.c:de_thread
```
**Symbols:**

```
ffffffff810c7fd0-ffffffff810c8046: change_pid (STB_GLOBAL)
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
