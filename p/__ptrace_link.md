# Function: <code>__ptrace_link</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __ptrace_link(struct task_struct *child, struct task_struct *new_parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/ptrace.c (ffffffff8108ac30)
Location: kernel/ptrace.c:37
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
```
**Symbols:**

```
ffffffff8108ac30-ffffffff8108ac3b: __ptrace_link.part.9 (STB_LOCAL)
ffffffff8108b7b0-ffffffff8108b7fd: __ptrace_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __ptrace_link(struct task_struct *child, struct task_struct *new_parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/ptrace.c (ffffffff8108dc75)
Location: kernel/ptrace.c:37
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
Direct callers:
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
```
**Symbols:**

```
ffffffff8108dc20-ffffffff8108dc2b: __ptrace_link.part.11 (STB_LOCAL)
ffffffff8108e7b0-ffffffff8108e800: __ptrace_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void __ptrace_link(struct task_struct *child, struct task_struct *new_parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff81093430)
Location: kernel/ptrace.c:66
Inline: True
Direct callers:
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_attach
```
**Symbols:**

```
ffffffff81093430-ffffffff8109348f: __ptrace_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __ptrace_link(struct task_struct *child, struct task_struct *new_parent, const struct cred *ptracer_cred);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff81090520)
Location: kernel/ptrace.c:63
Inline: True
Direct callers:
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_attach
```
**Symbols:**

```
ffffffff81090520-ffffffff81090578: __ptrace_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __ptrace_link(struct task_struct *child, struct task_struct *new_parent, const struct cred *ptracer_cred);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff81097390)
Location: kernel/ptrace.c:63
Inline: True
Direct callers:
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_attach
```
**Symbols:**

```
ffffffff81097390-ffffffff810973e8: __ptrace_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __ptrace_link(struct task_struct *child, struct task_struct *new_parent, const struct cred *ptracer_cred);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff8109a860)
Location: kernel/ptrace.c:63
Inline: True
Direct callers:
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_attach
```
**Symbols:**

```
ffffffff8109a860-ffffffff8109a8b8: __ptrace_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __ptrace_link(struct task_struct *child, struct task_struct *new_parent, const struct cred *ptracer_cred);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810a2a90)
Location: kernel/ptrace.c:63
Inline: True
Direct callers:
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_attach
```
**Symbols:**

```
ffffffff810a2a90-ffffffff810a2aed: __ptrace_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void __ptrace_link(struct task_struct *child, struct task_struct *new_parent, const struct cred *ptracer_cred);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810a7730)
Location: kernel/ptrace.c:67
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_attach
```
**Symbols:**

```
ffffffff810a7730-ffffffff810a7797: __ptrace_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __ptrace_link(struct task_struct *child, struct task_struct *new_parent, const struct cred *ptracer_cred);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810add50)
Location: kernel/ptrace.c:67
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_attach
```
**Symbols:**

```
ffffffff810add50-ffffffff810addb7: __ptrace_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __ptrace_link(struct task_struct *child, struct task_struct *new_parent, const struct cred *ptracer_cred);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810b5830)
Location: kernel/ptrace.c:67
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_attach
```
**Symbols:**

```
ffffffff810b5830-ffffffff810b5897: __ptrace_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __ptrace_link(struct task_struct *child, struct task_struct *new_parent, const struct cred *ptracer_cred);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810b0a20)
Location: kernel/ptrace.c:67
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_attach
```
**Symbols:**

```
ffffffff810b0a20-ffffffff810b0a87: __ptrace_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __ptrace_link(struct task_struct *child, struct task_struct *new_parent, const struct cred *ptracer_cred);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810b1fc0)
Location: kernel/ptrace.c:68
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_attach
```
**Symbols:**

```
ffffffff810b1fc0-ffffffff810b2027: __ptrace_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __ptrace_link(struct task_struct *child, struct task_struct *new_parent, const struct cred *ptracer_cred);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810c3cdd)
Location: kernel/ptrace.c:68
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff810c4980-ffffffff810c49e7: __ptrace_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __ptrace_link(struct task_struct *child, struct task_struct *new_parent, const struct cred *ptracer_cred);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810db46f)
Location: kernel/ptrace.c:68
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff810dbc80-ffffffff810dbcf5: __ptrace_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __ptrace_link(struct task_struct *child, struct task_struct *new_parent, const struct cred *ptracer_cred);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810fb2ff)
Location: kernel/ptrace.c:68
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff810fbd80-ffffffff810fbdf5: __ptrace_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __ptrace_link(struct task_struct *child, struct task_struct *new_parent, const struct cred *ptracer_cred);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff811075bf)
Location: kernel/ptrace.c:69
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff81107e20-ffffffff81107e95: __ptrace_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __ptrace_link(struct task_struct *child, struct task_struct *new_parent, const struct cred *ptracer_cred);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff81110f0f)
Location: kernel/ptrace.c:69
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff811117c0-ffffffff81111837: __ptrace_link (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void __ptrace_link(struct task_struct *child, struct task_struct *new_parent, const struct cred *ptracer_cred);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffff800010107de0)
Location: kernel/ptrace.c:67
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_attach
```
**Symbols:**

```
ffff800010107de0-ffff800010107e78: __ptrace_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void __ptrace_link(struct task_struct *child, struct task_struct *new_parent, const struct cred *ptracer_cred);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (c0361e30)
Location: kernel/ptrace.c:67
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/ptrace.c:__se_sys_ptrace
  - kernel/ptrace.c:__se_sys_ptrace
  - kernel/ptrace.c:__se_sys_ptrace
```
**Symbols:**

```
c0361e30-c0361ea8: __ptrace_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __ptrace_link(struct task_struct *child, struct task_struct *new_parent, const struct cred *ptracer_cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (c00000000014f1a0)
Location: kernel/ptrace.c:67
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_attach
```
**Symbols:**

```
c00000000014f1a0-c00000000014f204: __ptrace_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __ptrace_link(struct task_struct *child, struct task_struct *new_parent, const struct cred *ptracer_cred);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/ptrace.c (ffffffe0000cb9d8)
Location: kernel/ptrace.c:67
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_link
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/ptrace.c:ptrace_link
```
**Symbols:**

```
ffffffe0000cb9aa-ffffffe0000cb9be: __ptrace_link.part.0 (STB_LOCAL)
ffffffe0000cbe26-ffffffe0000cbe92: __ptrace_link (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void __ptrace_link(struct task_struct *child, struct task_struct *new_parent, const struct cred *ptracer_cred);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810a80c0)
Location: kernel/ptrace.c:67
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_attach
```
**Symbols:**

```
ffffffff810a80c0-ffffffff810a8127: __ptrace_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __ptrace_link(struct task_struct *child, struct task_struct *new_parent, const struct cred *ptracer_cred);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff81096a80)
Location: kernel/ptrace.c:67
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_attach
```
**Symbols:**

```
ffffffff81096a80-ffffffff81096ae7: __ptrace_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __ptrace_link(struct task_struct *child, struct task_struct *new_parent, const struct cred *ptracer_cred);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810a7620)
Location: kernel/ptrace.c:67
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_attach
```
**Symbols:**

```
ffffffff810a7620-ffffffff810a7687: __ptrace_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __ptrace_link(struct task_struct *child, struct task_struct *new_parent, const struct cred *ptracer_cred);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810af750)
Location: kernel/ptrace.c:67
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_attach
```
**Symbols:**

```
ffffffff810af750-ffffffff810af7b7: __ptrace_link (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct cred *ptracer_cred</code>
</li>
</ul>
</details>
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
