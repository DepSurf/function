# Function: <code>perf_event_namespaces</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void perf_event_namespaces(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff811acc04)
Location: kernel/events/core.c:6710
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_fork
Direct callers:
  - kernel/fork.c:SyS_unshare
  - kernel/nsproxy.c:SyS_setns
  - kernel/events/core.c:perf_event_fork
```
**Symbols:**

```
ffffffff811a4860-ffffffff811a49b4: perf_event_namespaces.part.101 (STB_LOCAL)
ffffffff811acdb0-ffffffff811acdc7: perf_event_namespaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void perf_event_namespaces(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff811c0754)
Location: kernel/events/core.c:6702
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_fork
Direct callers:
  - kernel/fork.c:SyS_unshare
  - kernel/nsproxy.c:SyS_setns
  - kernel/events/core.c:perf_event_fork
```
**Symbols:**

```
ffffffff811b8820-ffffffff811b8974: perf_event_namespaces.part.104 (STB_LOCAL)
ffffffff811c0900-ffffffff811c0917: perf_event_namespaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void perf_event_namespaces(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff811e0b74)
Location: kernel/events/core.c:7076
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_fork
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/nsproxy.c:__ia32_sys_setns
  - kernel/nsproxy.c:__x64_sys_setns
  - kernel/events/core.c:perf_event_fork
```
**Symbols:**

```
ffffffff811d8190-ffffffff811d8303: perf_event_namespaces.part.120 (STB_LOCAL)
ffffffff811e0d00-ffffffff811e0d16: perf_event_namespaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void perf_event_namespaces(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff811f0fd4)
Location: kernel/events/core.c:7085
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_fork
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/nsproxy.c:__ia32_sys_setns
  - kernel/nsproxy.c:__x64_sys_setns
  - kernel/events/core.c:perf_event_fork
```
**Symbols:**

```
ffffffff811e7e60-ffffffff811e7fd3: perf_event_namespaces.part.120 (STB_LOCAL)
ffffffff811f1160-ffffffff811f1176: perf_event_namespaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void perf_event_namespaces(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff812087d5)
Location: kernel/events/core.c:7167
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_fork
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/nsproxy.c:__ia32_sys_setns
  - kernel/nsproxy.c:__x64_sys_setns
  - kernel/events/core.c:perf_event_fork
```
**Symbols:**

```
ffffffff811ff4b0-ffffffff811ff5db: perf_event_namespaces.part.0 (STB_LOCAL)
ffffffff81208970-ffffffff81208986: perf_event_namespaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void perf_event_namespaces(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff81215b45)
Location: kernel/events/core.c:7283
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_fork
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/nsproxy.c:__ia32_sys_setns
  - kernel/nsproxy.c:__x64_sys_setns
  - kernel/events/core.c:perf_event_fork
```
**Symbols:**

```
ffffffff8120c520-ffffffff8120c64b: perf_event_namespaces.part.0 (STB_LOCAL)
ffffffff81215ce0-ffffffff81215cf6: perf_event_namespaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void perf_event_namespaces(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff81241e6c)
Location: kernel/events/core.c:7735
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_fork
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/events/core.c:perf_event_fork
```
**Symbols:**

```
ffffffff81233a50-ffffffff81233b55: perf_event_namespaces.part.0 (STB_LOCAL)
ffffffff81241f30-ffffffff81241f46: perf_event_namespaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void perf_event_namespaces(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff8124c5ac)
Location: kernel/events/core.c:7917
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_fork
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/events/core.c:perf_event_fork
```
**Symbols:**

```
ffffffff8123d820-ffffffff8123d925: perf_event_namespaces.part.0 (STB_LOCAL)
ffffffff8124c670-ffffffff8124c686: perf_event_namespaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void perf_event_namespaces(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff81250b5c)
Location: kernel/events/core.c:8028
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_fork
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/events/core.c:perf_event_fork
```
**Symbols:**

```
ffffffff81242290-ffffffff81242395: perf_event_namespaces.part.0 (STB_LOCAL)
ffffffff81250cb0-ffffffff81250cc6: perf_event_namespaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void perf_event_namespaces(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff8128b91c)
Location: kernel/events/core.c:8152
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_fork
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/events/core.c:perf_event_fork
```
**Symbols:**

```
ffffffff8127cba0-ffffffff8127cca5: perf_event_namespaces.part.0 (STB_LOCAL)
ffffffff8128ba70-ffffffff8128ba86: perf_event_namespaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void perf_event_namespaces(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff812e0183)
Location: kernel/events/core.c:8057
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_fork
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/events/core.c:perf_event_fork
```
**Symbols:**

```
ffffffff812d13e0-ffffffff812d150f: perf_event_namespaces.part.0 (STB_LOCAL)
ffffffff812e02f0-ffffffff812e031b: perf_event_namespaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void perf_event_namespaces(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff813485a3)
Location: kernel/events/core.c:8339
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_fork
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/events/core.c:perf_event_fork
```
**Symbols:**

```
ffffffff81338bf0-ffffffff81338d1f: perf_event_namespaces.part.0 (STB_LOCAL)
ffffffff81348740-ffffffff8134876b: perf_event_namespaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void perf_event_namespaces(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff81379763)
Location: kernel/events/core.c:8367
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_fork
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/events/core.c:perf_event_fork
```
**Symbols:**

```
ffffffff813699e0-ffffffff81369b0f: perf_event_namespaces.part.0 (STB_LOCAL)
ffffffff81379850-ffffffff8137987b: perf_event_namespaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void perf_event_namespaces(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff813a2a73)
Location: kernel/events/core.c:8448
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_fork
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/nsproxy.c:__do_sys_setns
  - kernel/events/core.c:perf_event_fork
```
**Symbols:**

```
ffffffff813928c0-ffffffff813929ef: perf_event_namespaces.part.0 (STB_LOCAL)
ffffffff813a2b60-ffffffff813a2b8b: perf_event_namespaces (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void perf_event_namespaces(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffff80001029fc34)
Location: kernel/events/core.c:7283
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_fork
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/nsproxy.c:__arm64_sys_setns
  - kernel/events/core.c:perf_event_fork
```
**Symbols:**

```
ffff800010297eb0-ffff800010298008: perf_event_namespaces.part.0 (STB_LOCAL)
ffff80001029fd78-ffff80001029fda0: perf_event_namespaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void perf_event_namespaces(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (c04cfacc)
Location: kernel/events/core.c:7283
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_fork
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/nsproxy.c:__se_sys_setns
  - kernel/events/core.c:perf_event_fork
```
**Symbols:**

```
c04c599c-c04c5ab8: perf_event_namespaces.part.0 (STB_LOCAL)
c04cfc28-c04cfc50: perf_event_namespaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void perf_event_namespaces(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (c0000000003511c8)
Location: kernel/events/core.c:7283
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_fork
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/nsproxy.c:__se_sys_setns
  - kernel/events/core.c:perf_event_fork
```
**Symbols:**

```
c0000000003446f0-c000000000344834: perf_event_namespaces.part.0 (STB_LOCAL)
c0000000003513c0-c0000000003513dc: perf_event_namespaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void perf_event_namespaces(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffe0001cf3f4)
Location: kernel/events/core.c:7283
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_fork
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/nsproxy.c:__se_sys_setns
  - kernel/events/core.c:perf_event_fork
```
**Symbols:**

```
ffffffe0001c70d0-ffffffe0001c71dc: perf_event_namespaces.part.0 (STB_LOCAL)
ffffffe0001cf4ac-ffffffe0001cf4d0: perf_event_namespaces (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void perf_event_namespaces(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff8120e195)
Location: kernel/events/core.c:7283
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_fork
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/nsproxy.c:__ia32_sys_setns
  - kernel/nsproxy.c:__x64_sys_setns
  - kernel/events/core.c:perf_event_fork
```
**Symbols:**

```
ffffffff81204b40-ffffffff81204c6b: perf_event_namespaces.part.0 (STB_LOCAL)
ffffffff8120e330-ffffffff8120e346: perf_event_namespaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void perf_event_namespaces(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff81200f45)
Location: kernel/events/core.c:7283
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_fork
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/nsproxy.c:__ia32_sys_setns
  - kernel/nsproxy.c:__x64_sys_setns
  - kernel/events/core.c:perf_event_fork
```
**Symbols:**

```
ffffffff811f78d0-ffffffff811f79fb: perf_event_namespaces.part.0 (STB_LOCAL)
ffffffff812010e0-ffffffff812010f6: perf_event_namespaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void perf_event_namespaces(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff8120bf35)
Location: kernel/events/core.c:7283
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_fork
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/nsproxy.c:__ia32_sys_setns
  - kernel/nsproxy.c:__x64_sys_setns
  - kernel/events/core.c:perf_event_fork
```
**Symbols:**

```
ffffffff81202910-ffffffff81202a3b: perf_event_namespaces.part.0 (STB_LOCAL)
ffffffff8120c0d0-ffffffff8120c0e6: perf_event_namespaces (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void perf_event_namespaces(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff8121ada5)
Location: kernel/events/core.c:7283
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_fork
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/nsproxy.c:__ia32_sys_setns
  - kernel/nsproxy.c:__x64_sys_setns
  - kernel/events/core.c:perf_event_fork
```
**Symbols:**

```
ffffffff812124e0-ffffffff8121260b: perf_event_namespaces.part.0 (STB_LOCAL)
ffffffff8121af40-ffffffff8121af56: perf_event_namespaces (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
