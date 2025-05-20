# Function: <code>__thaw_task</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __thaw_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff810e9db0)
Location: kernel/freezer.c:149
Inline: False
Direct callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_kernel_threads
  - kernel/cgroup_freezer.c:freezer_apply_state
  - kernel/cgroup_freezer.c:freezer_attach
```
**Symbols:**

```
ffffffff810e9db0-ffffffff810e9df0: __thaw_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __thaw_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff810f0b00)
Location: kernel/freezer.c:149
Inline: False
Direct callers:
  - kernel/power/process.c:thaw_kernel_threads
  - kernel/power/process.c:thaw_processes
  - kernel/cgroup_freezer.c:freezer_apply_state
  - kernel/cgroup_freezer.c:freezer_attach
```
**Symbols:**

```
ffffffff810f0b00-ffffffff810f0b40: __thaw_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __thaw_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff810f7c60)
Location: kernel/freezer.c:149
Inline: False
Direct callers:
  - kernel/power/process.c:thaw_kernel_threads
  - kernel/power/process.c:thaw_processes
  - kernel/cgroup_freezer.c:freezer_apply_state
  - kernel/cgroup_freezer.c:freezer_attach
  - mm/oom_kill.c:mark_oom_victim
```
**Symbols:**

```
ffffffff810f7c60-ffffffff810f7ca0: __thaw_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __thaw_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff810f9b30)
Location: kernel/freezer.c:149
Inline: False
Direct callers:
  - kernel/power/process.c:thaw_kernel_threads
  - kernel/power/process.c:thaw_processes
  - kernel/cgroup/freezer.c:freezer_apply_state
  - kernel/cgroup/freezer.c:freezer_attach
  - mm/oom_kill.c:mark_oom_victim
```
**Symbols:**

```
ffffffff810f9b30-ffffffff810f9b79: __thaw_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __thaw_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff81104600)
Location: kernel/freezer.c:149
Inline: False
Direct callers:
  - kernel/power/process.c:thaw_kernel_threads
  - kernel/power/process.c:thaw_processes
  - kernel/cgroup/freezer.c:unfreeze_cgroup
  - kernel/cgroup/freezer.c:freezer_attach
  - mm/oom_kill.c:mark_oom_victim
```
**Symbols:**

```
ffffffff81104600-ffffffff81104649: __thaw_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __thaw_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff8110f400)
Location: kernel/freezer.c:149
Inline: False
Direct callers:
  - kernel/power/process.c:thaw_kernel_threads
  - kernel/power/process.c:thaw_processes
  - kernel/cgroup/freezer.c:unfreeze_cgroup
  - kernel/cgroup/freezer.c:freezer_attach
  - mm/oom_kill.c:mark_oom_victim
```
**Symbols:**

```
ffffffff8110f400-ffffffff8110f442: __thaw_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __thaw_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff8111aa40)
Location: kernel/freezer.c:151
Inline: False
Direct callers:
  - kernel/power/process.c:thaw_kernel_threads
  - kernel/power/process.c:thaw_processes
  - kernel/cgroup/freezer.c:unfreeze_cgroup
  - kernel/cgroup/freezer.c:freezer_attach
  - mm/oom_kill.c:mark_oom_victim
```
**Symbols:**

```
ffffffff8111aa40-ffffffff8111aa82: __thaw_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __thaw_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff81125140)
Location: kernel/freezer.c:152
Inline: False
Direct callers:
  - kernel/power/process.c:thaw_kernel_threads
  - kernel/power/process.c:thaw_processes
  - kernel/cgroup/legacy_freezer.c:unfreeze_cgroup
  - kernel/cgroup/legacy_freezer.c:freezer_attach
  - mm/oom_kill.c:mark_oom_victim
```
**Symbols:**

```
ffffffff81125140-ffffffff81125186: __thaw_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __thaw_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff81131100)
Location: kernel/freezer.c:146
Inline: False
Direct callers:
  - kernel/power/process.c:thaw_kernel_threads
  - kernel/power/process.c:thaw_processes
  - kernel/cgroup/legacy_freezer.c:unfreeze_cgroup
  - kernel/cgroup/legacy_freezer.c:freezer_attach
  - mm/oom_kill.c:mark_oom_victim
```
**Symbols:**

```
ffffffff81131100-ffffffff81131146: __thaw_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __thaw_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff811404d0)
Location: kernel/freezer.c:146
Inline: False
Direct callers:
  - kernel/power/process.c:thaw_kernel_threads
  - kernel/power/process.c:thaw_processes
  - kernel/cgroup/legacy_freezer.c:unfreeze_cgroup
  - kernel/cgroup/legacy_freezer.c:freezer_attach
  - mm/oom_kill.c:mark_oom_victim
```
**Symbols:**

```
ffffffff811404d0-ffffffff81140516: __thaw_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __thaw_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff8113c840)
Location: kernel/freezer.c:146
Inline: False
Direct callers:
  - kernel/power/process.c:thaw_kernel_threads
  - kernel/power/process.c:thaw_processes
  - kernel/cgroup/legacy_freezer.c:unfreeze_cgroup
  - kernel/cgroup/legacy_freezer.c:freezer_attach
  - mm/oom_kill.c:mark_oom_victim
```
**Symbols:**

```
ffffffff8113c840-ffffffff8113c886: __thaw_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __thaw_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff8113da90)
Location: kernel/freezer.c:146
Inline: False
Direct callers:
  - kernel/power/process.c:thaw_kernel_threads
  - kernel/power/process.c:thaw_processes
  - kernel/cgroup/legacy_freezer.c:unfreeze_cgroup
  - kernel/cgroup/legacy_freezer.c:freezer_attach
  - mm/oom_kill.c:mark_oom_victim
```
**Symbols:**

```
ffffffff8113da90-ffffffff8113dad6: __thaw_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __thaw_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff81160c10)
Location: kernel/freezer.c:146
Inline: False
Direct callers:
  - kernel/power/process.c:thaw_kernel_threads
  - kernel/power/process.c:thaw_processes
  - kernel/cgroup/legacy_freezer.c:unfreeze_cgroup
  - kernel/cgroup/legacy_freezer.c:freezer_attach
  - mm/oom_kill.c:mark_oom_victim
```
**Symbols:**

```
ffffffff81160c10-ffffffff81160c56: __thaw_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __thaw_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff811939a0)
Location: kernel/freezer.c:146
Inline: False
Direct callers:
  - kernel/power/process.c:thaw_kernel_threads
  - kernel/power/process.c:thaw_processes
  - kernel/cgroup/legacy_freezer.c:unfreeze_cgroup
  - kernel/cgroup/legacy_freezer.c:freezer_attach
  - mm/oom_kill.c:mark_oom_victim
```
**Symbols:**

```
ffffffff811939a0-ffffffff811939ec: __thaw_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __thaw_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff811d1370)
Location: kernel/freezer.c:194
Inline: False
Direct callers:
  - kernel/power/process.c:thaw_kernel_threads
  - kernel/power/process.c:thaw_processes
  - kernel/cgroup/legacy_freezer.c:unfreeze_cgroup
  - kernel/cgroup/legacy_freezer.c:freezer_attach
  - mm/oom_kill.c:mark_oom_victim
```
**Symbols:**

```
ffffffff811d1370-ffffffff811d1442: __thaw_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __thaw_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff811e55e0)
Location: kernel/freezer.c:194
Inline: False
Direct callers:
  - kernel/power/process.c:thaw_kernel_threads
  - kernel/power/process.c:thaw_processes
  - kernel/cgroup/legacy_freezer.c:unfreeze_cgroup
  - kernel/cgroup/legacy_freezer.c:freezer_attach
  - mm/oom_kill.c:mark_oom_victim
```
**Symbols:**

```
ffffffff811e55e0-ffffffff811e56b2: __thaw_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __thaw_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff811fb390)
Location: kernel/freezer.c:197
Inline: False
Direct callers:
  - kernel/power/process.c:thaw_kernel_threads
  - kernel/power/process.c:thaw_processes
  - kernel/cgroup/legacy_freezer.c:unfreeze_cgroup
  - kernel/cgroup/legacy_freezer.c:freezer_attach
  - mm/oom_kill.c:mark_oom_victim
```
**Symbols:**

```
ffffffff811fb390-ffffffff811fb40c: __thaw_task (STB_GLOBAL)
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
void __thaw_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffff800010198480)
Location: kernel/freezer.c:146
Inline: False
Direct callers:
  - kernel/power/process.c:thaw_kernel_threads
  - kernel/power/process.c:thaw_processes
  - kernel/cgroup/legacy_freezer.c:unfreeze_cgroup
  - kernel/cgroup/legacy_freezer.c:freezer_attach
  - mm/oom_kill.c:mark_oom_victim
```
**Symbols:**

```
ffff800010198480-ffff800010198548: __thaw_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __thaw_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (c03e3404)
Location: kernel/freezer.c:146
Inline: False
Direct callers:
  - kernel/power/process.c:thaw_kernel_threads
  - kernel/power/process.c:thaw_processes
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
  - kernel/cgroup/legacy_freezer.c:freezer_attach
  - mm/oom_kill.c:mark_oom_victim
```
**Symbols:**

```
c03e3404-c03e3454: __thaw_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __thaw_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (c0000000001f83a0)
Location: kernel/freezer.c:146
Inline: False
Direct callers:
  - kernel/power/process.c:thaw_kernel_threads
  - kernel/power/process.c:thaw_processes
  - kernel/cgroup/legacy_freezer.c:unfreeze_cgroup
  - kernel/cgroup/legacy_freezer.c:freezer_attach
  - mm/oom_kill.c:mark_oom_victim
```
**Symbols:**

```
c0000000001f83a0-c0000000001f8448: __thaw_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __thaw_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffe000129110)
Location: kernel/freezer.c:146
Inline: False
Direct callers:
  - kernel/power/process.c:thaw_kernel_threads
  - kernel/power/process.c:thaw_processes
  - kernel/cgroup/legacy_freezer.c:unfreeze_cgroup
  - kernel/cgroup/legacy_freezer.c:freezer_attach
```
**Symbols:**

```
ffffffe000129110-ffffffe000129188: __thaw_task (STB_GLOBAL)
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
void __thaw_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff811298b0)
Location: kernel/freezer.c:146
Inline: False
Direct callers:
  - kernel/power/process.c:thaw_kernel_threads
  - kernel/power/process.c:thaw_processes
  - kernel/cgroup/legacy_freezer.c:unfreeze_cgroup
  - kernel/cgroup/legacy_freezer.c:freezer_attach
  - mm/oom_kill.c:mark_oom_victim
```
**Symbols:**

```
ffffffff811298b0-ffffffff811298f6: __thaw_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __thaw_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff8111c140)
Location: kernel/freezer.c:146
Inline: False
Direct callers:
  - kernel/power/process.c:thaw_kernel_threads
  - kernel/power/process.c:thaw_processes
  - kernel/cgroup/legacy_freezer.c:unfreeze_cgroup
  - kernel/cgroup/legacy_freezer.c:freezer_attach
  - mm/oom_kill.c:mark_oom_victim
```
**Symbols:**

```
ffffffff8111c140-ffffffff8111c186: __thaw_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __thaw_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff811275d0)
Location: kernel/freezer.c:146
Inline: False
Direct callers:
  - kernel/power/process.c:thaw_kernel_threads
  - kernel/power/process.c:thaw_processes
  - kernel/cgroup/legacy_freezer.c:unfreeze_cgroup
  - kernel/cgroup/legacy_freezer.c:freezer_attach
  - mm/oom_kill.c:mark_oom_victim
```
**Symbols:**

```
ffffffff811275d0-ffffffff81127616: __thaw_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __thaw_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff81133c10)
Location: kernel/freezer.c:146
Inline: False
Direct callers:
  - kernel/power/process.c:thaw_kernel_threads
  - kernel/power/process.c:thaw_processes
  - kernel/cgroup/legacy_freezer.c:unfreeze_cgroup
  - kernel/cgroup/legacy_freezer.c:freezer_attach
  - mm/oom_kill.c:mark_oom_victim
```
**Symbols:**

```
ffffffff81133c10-ffffffff81133c56: __thaw_task (STB_GLOBAL)
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
