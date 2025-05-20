# Function: <code>ptracer_capable</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool ptracer_capable(struct task_struct *tsk, struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff81092780)
Location: kernel/capability.c:498
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_access_vm
```
**Symbols:**

```
ffffffff81092780-ffffffff810927ac: ptracer_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool ptracer_capable(struct task_struct *tsk, struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff8108f8c0)
Location: kernel/capability.c:498
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_access_vm
  - security/commoncap.c:cap_bprm_set_creds
```
**Symbols:**

```
ffffffff8108f8c0-ffffffff8108f8ec: ptracer_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool ptracer_capable(struct task_struct *tsk, struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff81096780)
Location: kernel/capability.c:499
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_access_vm
  - security/commoncap.c:cap_bprm_set_creds
```
**Symbols:**

```
ffffffff81096780-ffffffff810967ac: ptracer_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool ptracer_capable(struct task_struct *tsk, struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff81099ca0)
Location: kernel/capability.c:499
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_access_vm
  - security/commoncap.c:cap_bprm_set_creds
```
**Symbols:**

```
ffffffff81099ca0-ffffffff81099ccc: ptracer_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool ptracer_capable(struct task_struct *tsk, struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810a2020)
Location: kernel/capability.c:501
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_access_vm
  - security/commoncap.c:cap_bprm_set_creds
```
**Symbols:**

```
ffffffff810a2020-ffffffff810a2051: ptracer_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool ptracer_capable(struct task_struct *tsk, struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810a6a50)
Location: kernel/capability.c:518
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_access_vm
  - security/commoncap.c:cap_bprm_set_creds
```
**Symbols:**

```
ffffffff810a6a50-ffffffff810a6a81: ptracer_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool ptracer_capable(struct task_struct *tsk, struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810ad030)
Location: kernel/capability.c:518
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_access_vm
  - security/commoncap.c:cap_bprm_set_creds
```
**Symbols:**

```
ffffffff810ad030-ffffffff810ad061: ptracer_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool ptracer_capable(struct task_struct *tsk, struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810b4ae0)
Location: kernel/capability.c:518
Inline: False
Direct callers:
  - security/commoncap.c:cap_bprm_creds_from_file
```
**Symbols:**

```
ffffffff810b4ae0-ffffffff810b4b11: ptracer_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool ptracer_capable(struct task_struct *tsk, struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810afd00)
Location: kernel/capability.c:518
Inline: False
Direct callers:
  - security/commoncap.c:cap_bprm_creds_from_file
```
**Symbols:**

```
ffffffff810afd00-ffffffff810afd40: ptracer_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool ptracer_capable(struct task_struct *tsk, struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810b1290)
Location: kernel/capability.c:522
Inline: False
Direct callers:
  - security/commoncap.c:cap_bprm_creds_from_file
```
**Symbols:**

```
ffffffff810b1290-ffffffff810b12d0: ptracer_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool ptracer_capable(struct task_struct *tsk, struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810c3350)
Location: kernel/capability.c:522
Inline: False
Direct callers:
  - security/commoncap.c:cap_bprm_creds_from_file
```
**Symbols:**

```
ffffffff810c3350-ffffffff810c3390: ptracer_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool ptracer_capable(struct task_struct *tsk, struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810da8a0)
Location: kernel/capability.c:523
Inline: False
Direct callers:
  - security/commoncap.c:cap_bprm_creds_from_file
```
**Symbols:**

```
ffffffff810da8a0-ffffffff810da8f7: ptracer_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool ptracer_capable(struct task_struct *tsk, struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810fa980)
Location: kernel/capability.c:523
Inline: False
Direct callers:
  - security/commoncap.c:cap_bprm_creds_from_file
```
**Symbols:**

```
ffffffff810fa980-ffffffff810fa9d7: ptracer_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool ptracer_capable(struct task_struct *tsk, struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff811069c0)
Location: kernel/capability.c:511
Inline: False
Direct callers:
  - security/commoncap.c:cap_bprm_creds_from_file
```
**Symbols:**

```
ffffffff811069c0-ffffffff81106a17: ptracer_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool ptracer_capable(struct task_struct *tsk, struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff81110310)
Location: kernel/capability.c:511
Inline: False
Direct callers:
  - security/commoncap.c:cap_bprm_creds_from_file
```
**Symbols:**

```
ffffffff81110310-ffffffff81110367: ptracer_capable (STB_GLOBAL)
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
bool ptracer_capable(struct task_struct *tsk, struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffff800010106888)
Location: kernel/capability.c:518
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_access_vm
  - security/commoncap.c:cap_bprm_set_creds
```
**Symbols:**

```
ffff800010106888-ffff8000101068e0: ptracer_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool ptracer_capable(struct task_struct *tsk, struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (c0361570)
Location: kernel/capability.c:518
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_access_vm
  - security/commoncap.c:cap_bprm_set_creds
```
**Symbols:**

```
c0361570-c03615ac: ptracer_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool ptracer_capable(struct task_struct *tsk, struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (c00000000014dc80)
Location: kernel/capability.c:518
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_access_vm
  - security/commoncap.c:cap_bprm_set_creds
```
**Symbols:**

```
c00000000014dc80-c00000000014dcd8: ptracer_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool ptracer_capable(struct task_struct *tsk, struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffe0000cb5e6)
Location: kernel/capability.c:518
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_access_vm
  - security/commoncap.c:cap_bprm_set_creds
```
**Symbols:**

```
ffffffe0000cb5e6-ffffffe0000cb632: ptracer_capable (STB_GLOBAL)
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
bool ptracer_capable(struct task_struct *tsk, struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810a73a0)
Location: kernel/capability.c:518
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_access_vm
  - security/commoncap.c:cap_bprm_set_creds
```
**Symbols:**

```
ffffffff810a73a0-ffffffff810a73d1: ptracer_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool ptracer_capable(struct task_struct *tsk, struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff81095d80)
Location: kernel/capability.c:518
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_access_vm
  - security/commoncap.c:cap_bprm_set_creds
```
**Symbols:**

```
ffffffff81095d80-ffffffff81095db1: ptracer_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool ptracer_capable(struct task_struct *tsk, struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810a6900)
Location: kernel/capability.c:518
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_access_vm
  - security/commoncap.c:cap_bprm_set_creds
```
**Symbols:**

```
ffffffff810a6900-ffffffff810a6931: ptracer_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool ptracer_capable(struct task_struct *tsk, struct user_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810aea30)
Location: kernel/capability.c:518
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_access_vm
  - security/commoncap.c:cap_bprm_set_creds
```
**Symbols:**

```
ffffffff810aea30-ffffffff810aea82: ptracer_capable (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
