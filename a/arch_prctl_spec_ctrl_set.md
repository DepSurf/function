# Function: <code>arch_prctl_spec_ctrl_set</code>

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
int arch_prctl_spec_ctrl_set(struct task_struct *task, long unsigned int which, long unsigned int ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81043920)
Location: arch/x86/kernel/cpu/bugs.c:587
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
```
**Symbols:**

```
ffffffff81043920-ffffffff8104393e: arch_prctl_spec_ctrl_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int arch_prctl_spec_ctrl_set(struct task_struct *task, long unsigned int which, long unsigned int ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff810450c0)
Location: arch/x86/kernel/cpu/bugs.c:856
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
```
**Symbols:**

```
ffffffff810450c0-ffffffff810451b0: arch_prctl_spec_ctrl_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int arch_prctl_spec_ctrl_set(struct task_struct *task, long unsigned int which, long unsigned int ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81047bf0)
Location: arch/x86/kernel/cpu/bugs.c:1064
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
```
**Symbols:**

```
ffffffff81047bf0-ffffffff81047c7e: arch_prctl_spec_ctrl_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int arch_prctl_spec_ctrl_set(struct task_struct *task, long unsigned int which, long unsigned int ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81048440)
Location: arch/x86/kernel/cpu/bugs.c:1194
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
```
**Symbols:**

```
ffffffff81048440-ffffffff810484ce: arch_prctl_spec_ctrl_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int arch_prctl_spec_ctrl_set(struct task_struct *task, long unsigned int which, long unsigned int ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104bfd0)
Location: arch/x86/kernel/cpu/bugs.c:1308
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prctl
```
**Symbols:**

```
ffffffff8104bfd0-ffffffff8104c0b4: arch_prctl_spec_ctrl_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int arch_prctl_spec_ctrl_set(struct task_struct *task, long unsigned int which, long unsigned int ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104b510)
Location: arch/x86/kernel/cpu/bugs.c:1319
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prctl
```
**Symbols:**

```
ffffffff8104b510-ffffffff8104b5fa: arch_prctl_spec_ctrl_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int arch_prctl_spec_ctrl_set(struct task_struct *task, long unsigned int which, long unsigned int ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104d280)
Location: arch/x86/kernel/cpu/bugs.c:1319
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prctl
```
**Symbols:**

```
ffffffff8104d280-ffffffff8104d2af: arch_prctl_spec_ctrl_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int arch_prctl_spec_ctrl_set(struct task_struct *task, long unsigned int which, long unsigned int ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81054970)
Location: arch/x86/kernel/cpu/bugs.c:1459
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prctl
```
**Symbols:**

```
ffffffff81054970-ffffffff810549d1: arch_prctl_spec_ctrl_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int arch_prctl_spec_ctrl_set(struct task_struct *task, long unsigned int which, long unsigned int ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81060690)
Location: arch/x86/kernel/cpu/bugs.c:1961
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prctl
```
**Symbols:**

```
ffffffff81060690-ffffffff8106072d: arch_prctl_spec_ctrl_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int arch_prctl_spec_ctrl_set(struct task_struct *task, long unsigned int which, long unsigned int ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff8106eee0)
Location: arch/x86/kernel/cpu/bugs.c:2012
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prctl
```
**Symbols:**

```
ffffffff8106eee0-ffffffff8106ef7d: arch_prctl_spec_ctrl_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int arch_prctl_spec_ctrl_set(struct task_struct *task, long unsigned int which, long unsigned int ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff810707c0)
Location: arch/x86/kernel/cpu/bugs.c:2123
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prctl
```
**Symbols:**

```
ffffffff810707c0-ffffffff8107084f: arch_prctl_spec_ctrl_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int arch_prctl_spec_ctrl_set(struct task_struct *task, long unsigned int which, long unsigned int ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff810780a0)
Location: arch/x86/kernel/cpu/bugs.c:2264
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prctl
```
**Symbols:**

```
ffffffff810780a0-ffffffff8107812f: arch_prctl_spec_ctrl_set (STB_GLOBAL)
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
int arch_prctl_spec_ctrl_set(struct task_struct *task, long unsigned int which, long unsigned int ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/ssbd.c (ffff8000100abf20)
Location: arch/arm64/kernel/ssbd.c:90
Inline: False
Direct callers:
  - kernel/sys.c:__arm64_sys_prctl
```
**Symbols:**

```
ffff8000100abf20-ffff8000100ac124: arch_prctl_spec_ctrl_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int arch_prctl_spec_ctrl_set(struct task_struct *t, long unsigned int which, long unsigned int ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (c036e324)
Location: kernel/sys.c:2271
Inline: False
Direct callers:
  - kernel/sys.c:__se_sys_prctl
```
**Symbols:**

```
c036e324-c036e340: arch_prctl_spec_ctrl_set (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int arch_prctl_spec_ctrl_set(struct task_struct *t, long unsigned int which, long unsigned int ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (c0000000001616f0)
Location: kernel/sys.c:2271
Inline: False
Direct callers:
  - kernel/sys.c:__se_sys_prctl
```
**Symbols:**

```
c0000000001616f0-c000000000161700: arch_prctl_spec_ctrl_set (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int arch_prctl_spec_ctrl_set(struct task_struct *t, long unsigned int which, long unsigned int ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffe0000d49c0)
Location: kernel/sys.c:2271
Inline: False
Direct callers:
  - kernel/sys.c:__se_sys_prctl
```
**Symbols:**

```
ffffffe0000d49c0-ffffffe0000d49dc: arch_prctl_spec_ctrl_set (STB_WEAK)
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
int arch_prctl_spec_ctrl_set(struct task_struct *task, long unsigned int which, long unsigned int ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff810485b0)
Location: arch/x86/kernel/cpu/bugs.c:1194
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
```
**Symbols:**

```
ffffffff810485b0-ffffffff8104863e: arch_prctl_spec_ctrl_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int arch_prctl_spec_ctrl_set(struct task_struct *task, long unsigned int which, long unsigned int ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81037910)
Location: arch/x86/kernel/cpu/bugs.c:1194
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
```
**Symbols:**

```
ffffffff81037910-ffffffff8103799e: arch_prctl_spec_ctrl_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int arch_prctl_spec_ctrl_set(struct task_struct *task, long unsigned int which, long unsigned int ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff810483f0)
Location: arch/x86/kernel/cpu/bugs.c:1194
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
```
**Symbols:**

```
ffffffff810483f0-ffffffff8104847e: arch_prctl_spec_ctrl_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int arch_prctl_spec_ctrl_set(struct task_struct *task, long unsigned int which, long unsigned int ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81049800)
Location: arch/x86/kernel/cpu/bugs.c:1194
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
```
**Symbols:**

```
ffffffff81049800-ffffffff8104988e: arch_prctl_spec_ctrl_set (STB_GLOBAL)
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
<details>
<summary>Changed between <code>amd64</code> and <code>armhf</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct task_struct *t</code>
</li>
<li>
<b>Param removed. </b>
<code>struct task_struct *task</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>ppc64el</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct task_struct *t</code>
</li>
<li>
<b>Param removed. </b>
<code>struct task_struct *task</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>riscv64</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct task_struct *t</code>
</li>
<li>
<b>Param removed. </b>
<code>struct task_struct *task</code>
</li>
</ul>
</details>
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
