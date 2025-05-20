# Function: <code>ptrace_check_attach</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ptrace_check_attach(struct task_struct *child, bool ignore_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff8108b690)
Location: kernel/ptrace.c:172
Inline: False
Direct callers:
  - kernel/ptrace.c:SyS_ptrace
  - kernel/ptrace.c:compat_SyS_ptrace
```
**Symbols:**

```
ffffffff8108b690-ffffffff8108b7ae: ptrace_check_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ptrace_check_attach(struct task_struct *child, bool ignore_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff8108e690)
Location: kernel/ptrace.c:171
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_SyS_ptrace
  - kernel/ptrace.c:SyS_ptrace
```
**Symbols:**

```
ffffffff8108e690-ffffffff8108e7ae: ptrace_check_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ptrace_check_attach(struct task_struct *child, bool ignore_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff81093220)
Location: kernel/ptrace.c:209
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_SyS_ptrace
  - kernel/ptrace.c:SyS_ptrace
```
**Symbols:**

```
ffffffff81093220-ffffffff81093350: ptrace_check_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ptrace_check_attach(struct task_struct *child, bool ignore_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff81090340)
Location: kernel/ptrace.c:224
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_SyS_ptrace
  - kernel/ptrace.c:SyS_ptrace
```
**Symbols:**

```
ffffffff81090340-ffffffff8109044c: ptrace_check_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ptrace_check_attach(struct task_struct *child, bool ignore_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810971b0)
Location: kernel/ptrace.c:224
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_SyS_ptrace
  - kernel/ptrace.c:SyS_ptrace
```
**Symbols:**

```
ffffffff810971b0-ffffffff810972bc: ptrace_check_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ptrace_check_attach(struct task_struct *child, bool ignore_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff8109a670)
Location: kernel/ptrace.c:224
Inline: False
Direct callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
**Symbols:**

```
ffffffff8109a670-ffffffff8109a77c: ptrace_check_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ptrace_check_attach(struct task_struct *child, bool ignore_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810a28b0)
Location: kernel/ptrace.c:224
Inline: False
Direct callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
**Symbols:**

```
ffffffff810a28b0-ffffffff810a29b0: ptrace_check_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ptrace_check_attach(struct task_struct *child, bool ignore_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/ptrace.c (0)
Location: kernel/ptrace.c:229
Inline: False
Direct callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
**Symbols:**

```
ffffffff810a7530-ffffffff810a763b: ptrace_check_attach (STB_LOCAL)
ffffffff810a8c0c-ffffffff810a8c38: ptrace_check_attach.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ptrace_check_attach(struct task_struct *child, bool ignore_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810adb60)
Location: kernel/ptrace.c:229
Inline: False
Direct callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
**Symbols:**

```
ffffffff810adb60-ffffffff810adc57: ptrace_check_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ptrace_check_attach(struct task_struct *child, bool ignore_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810b5640)
Location: kernel/ptrace.c:229
Inline: False
Direct callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
**Symbols:**

```
ffffffff810b5640-ffffffff810b5737: ptrace_check_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ptrace_check_attach(struct task_struct *child, bool ignore_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810b0840)
Location: kernel/ptrace.c:229
Inline: False
Direct callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
**Symbols:**

```
ffffffff810b0840-ffffffff810b0937: ptrace_check_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ptrace_check_attach(struct task_struct *child, bool ignore_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810b1dc0)
Location: kernel/ptrace.c:246
Inline: False
Direct callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
**Symbols:**

```
ffffffff810b1dc0-ffffffff810b1edf: ptrace_check_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ptrace_check_attach(struct task_struct *child, bool ignore_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810c4280)
Location: kernel/ptrace.c:246
Inline: False
Direct callers:
  - kernel/ptrace.c:__x64_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
**Symbols:**

```
ffffffff810c4280-ffffffff810c4399: ptrace_check_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ptrace_check_attach(struct task_struct *child, bool ignore_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810daa30)
Location: kernel/ptrace.c:249
Inline: False
Direct callers:
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
**Symbols:**

```
ffffffff810daa30-ffffffff810dab52: ptrace_check_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ptrace_check_attach(struct task_struct *child, bool ignore_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810fab40)
Location: kernel/ptrace.c:249
Inline: False
Direct callers:
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
**Symbols:**

```
ffffffff810fab40-ffffffff810fac62: ptrace_check_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ptrace_check_attach(struct task_struct *child, bool ignore_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff81106cc0)
Location: kernel/ptrace.c:250
Inline: False
Direct callers:
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
**Symbols:**

```
ffffffff81106cc0-ffffffff81106de2: ptrace_check_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ptrace_check_attach(struct task_struct *child, bool ignore_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff81110610)
Location: kernel/ptrace.c:239
Inline: False
Direct callers:
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
**Symbols:**

```
ffffffff81110610-ffffffff81110732: ptrace_check_attach (STB_LOCAL)
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
int ptrace_check_attach(struct task_struct *child, bool ignore_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffff800010107b28)
Location: kernel/ptrace.c:229
Inline: False
Direct callers:
  - kernel/ptrace.c:__arm64_compat_sys_ptrace
  - kernel/ptrace.c:__arm64_sys_ptrace
```
**Symbols:**

```
ffff800010107b28-ffff800010107ce0: ptrace_check_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (c036241c)
Location: kernel/ptrace.c:229
Inline: True
Inline callers:
  - kernel/ptrace.c:__se_sys_ptrace
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ptrace_check_attach(struct task_struct *child, bool ignore_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (c00000000014ee40)
Location: kernel/ptrace.c:229
Inline: False
Direct callers:
  - kernel/ptrace.c:__se_compat_sys_ptrace
  - kernel/ptrace.c:__se_sys_ptrace
```
**Symbols:**

```
c00000000014ee40-c00000000014f02c: ptrace_check_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffe0000cc2f0)
Location: kernel/ptrace.c:229
Inline: True
Inline callers:
  - kernel/ptrace.c:__se_sys_ptrace
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
int ptrace_check_attach(struct task_struct *child, bool ignore_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810a7ed0)
Location: kernel/ptrace.c:229
Inline: False
Direct callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
**Symbols:**

```
ffffffff810a7ed0-ffffffff810a7fc7: ptrace_check_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ptrace_check_attach(struct task_struct *child, bool ignore_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff81096890)
Location: kernel/ptrace.c:229
Inline: False
Direct callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
**Symbols:**

```
ffffffff81096890-ffffffff81096981: ptrace_check_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ptrace_check_attach(struct task_struct *child, bool ignore_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810a7430)
Location: kernel/ptrace.c:229
Inline: False
Direct callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
**Symbols:**

```
ffffffff810a7430-ffffffff810a7527: ptrace_check_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int ptrace_check_attach(struct task_struct *child, bool ignore_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810aedf0)
Location: kernel/ptrace.c:229
Inline: True
Direct callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
**Symbols:**

```
ffffffff810aedf0-ffffffff810aeee6: ptrace_check_attach (STB_LOCAL)
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
