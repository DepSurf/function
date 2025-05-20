# Function: <code>freeze_task</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool freeze_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff810e9cb0)
Location: kernel/freezer.c:118
Inline: False
Direct callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/cgroup_freezer.c:freezer_fork
  - kernel/cgroup_freezer.c:freezer_apply_state
  - kernel/cgroup_freezer.c:freezer_attach
```
**Symbols:**

```
ffffffff810e9cb0-ffffffff810e9da8: freeze_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool freeze_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff810f0a10)
Location: kernel/freezer.c:118
Inline: False
Direct callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/cgroup_freezer.c:freezer_apply_state
  - kernel/cgroup_freezer.c:freezer_fork
  - kernel/cgroup_freezer.c:freezer_attach
```
**Symbols:**

```
ffffffff810f0a10-ffffffff810f0aff: freeze_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool freeze_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff810f7b70)
Location: kernel/freezer.c:118
Inline: False
Direct callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/cgroup_freezer.c:freezer_apply_state
  - kernel/cgroup_freezer.c:freezer_fork
  - kernel/cgroup_freezer.c:freezer_attach
```
**Symbols:**

```
ffffffff810f7b70-ffffffff810f7c5f: freeze_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool freeze_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff810f9a40)
Location: kernel/freezer.c:118
Inline: False
Direct callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/cgroup/freezer.c:freezer_apply_state
  - kernel/cgroup/freezer.c:freezer_attach
```
**Symbols:**

```
ffffffff810f9a40-ffffffff810f9b2f: freeze_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool freeze_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff81104500)
Location: kernel/freezer.c:118
Inline: False
Direct callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/cgroup/freezer.c:freeze_cgroup
  - kernel/cgroup/freezer.c:freezer_attach
```
**Symbols:**

```
ffffffff81104500-ffffffff811045f2: freeze_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool freeze_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff8110f300)
Location: kernel/freezer.c:118
Inline: False
Direct callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/cgroup/freezer.c:freeze_cgroup
  - kernel/cgroup/freezer.c:freezer_attach
```
**Symbols:**

```
ffffffff8110f300-ffffffff8110f3f2: freeze_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool freeze_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff8111a940)
Location: kernel/freezer.c:120
Inline: False
Direct callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/cgroup/freezer.c:freeze_cgroup
  - kernel/cgroup/freezer.c:freezer_attach
```
**Symbols:**

```
ffffffff8111a940-ffffffff8111aa3a: freeze_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool freeze_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff81125040)
Location: kernel/freezer.c:121
Inline: False
Direct callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/cgroup/legacy_freezer.c:freeze_cgroup
  - kernel/cgroup/legacy_freezer.c:freezer_attach
```
**Symbols:**

```
ffffffff81125040-ffffffff81125139: freeze_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool freeze_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff81131000)
Location: kernel/freezer.c:115
Inline: False
Direct callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/cgroup/legacy_freezer.c:freeze_cgroup
  - kernel/cgroup/legacy_freezer.c:freezer_attach
```
**Symbols:**

```
ffffffff81131000-ffffffff811310f9: freeze_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool freeze_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff811403d0)
Location: kernel/freezer.c:115
Inline: False
Direct callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/cgroup/legacy_freezer.c:freeze_cgroup
  - kernel/cgroup/legacy_freezer.c:freezer_attach
```
**Symbols:**

```
ffffffff811403d0-ffffffff811404c9: freeze_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool freeze_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff8113c740)
Location: kernel/freezer.c:115
Inline: False
Direct callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/cgroup/legacy_freezer.c:freeze_cgroup
  - kernel/cgroup/legacy_freezer.c:freezer_attach
```
**Symbols:**

```
ffffffff8113c740-ffffffff8113c839: freeze_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool freeze_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff8113d990)
Location: kernel/freezer.c:115
Inline: False
Direct callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/cgroup/legacy_freezer.c:freeze_cgroup
  - kernel/cgroup/legacy_freezer.c:freezer_attach
```
**Symbols:**

```
ffffffff8113d990-ffffffff8113da89: freeze_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool freeze_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff81160b10)
Location: kernel/freezer.c:115
Inline: False
Direct callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/cgroup/legacy_freezer.c:freeze_cgroup
  - kernel/cgroup/legacy_freezer.c:freezer_attach
```
**Symbols:**

```
ffffffff81160b10-ffffffff81160c09: freeze_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool freeze_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff81193890)
Location: kernel/freezer.c:115
Inline: False
Direct callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/cgroup/legacy_freezer.c:freeze_cgroup
  - kernel/cgroup/legacy_freezer.c:freezer_attach
```
**Symbols:**

```
ffffffff81193890-ffffffff81193991: freeze_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool freeze_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff811d1260)
Location: kernel/freezer.c:153
Inline: False
Direct callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/cgroup/legacy_freezer.c:freeze_cgroup
  - kernel/cgroup/legacy_freezer.c:freezer_attach
```
**Symbols:**

```
ffffffff811d1260-ffffffff811d135f: freeze_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool freeze_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff811e54d0)
Location: kernel/freezer.c:153
Inline: False
Direct callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/cgroup/legacy_freezer.c:freeze_cgroup
  - kernel/cgroup/legacy_freezer.c:freezer_attach
```
**Symbols:**

```
ffffffff811e54d0-ffffffff811e55cf: freeze_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool freeze_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff811fb280)
Location: kernel/freezer.c:158
Inline: False
Direct callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/cgroup/legacy_freezer.c:freeze_cgroup
  - kernel/cgroup/legacy_freezer.c:freezer_attach
```
**Symbols:**

```
ffffffff811fb280-ffffffff811fb37f: freeze_task (STB_GLOBAL)
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
bool freeze_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffff800010198300)
Location: kernel/freezer.c:115
Inline: False
Direct callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/cgroup/legacy_freezer.c:freeze_cgroup
  - kernel/cgroup/legacy_freezer.c:freezer_attach
```
**Symbols:**

```
ffff800010198300-ffff800010198480: freeze_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool freeze_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (c03e32f0)
Location: kernel/freezer.c:115
Inline: False
Direct callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
  - kernel/cgroup/legacy_freezer.c:freezer_attach
```
**Symbols:**

```
c03e32f0-c03e3404: freeze_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool freeze_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (c0000000001f8230)
Location: kernel/freezer.c:115
Inline: False
Direct callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/cgroup/legacy_freezer.c:freeze_cgroup
  - kernel/cgroup/legacy_freezer.c:freezer_attach
```
**Symbols:**

```
c0000000001f8230-c0000000001f83a0: freeze_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool freeze_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffe000129028)
Location: kernel/freezer.c:115
Inline: False
Direct callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/cgroup/legacy_freezer.c:freeze_cgroup
  - kernel/cgroup/legacy_freezer.c:freezer_attach
```
**Symbols:**

```
ffffffe000129028-ffffffe000129110: freeze_task (STB_GLOBAL)
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
bool freeze_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff811297b0)
Location: kernel/freezer.c:115
Inline: False
Direct callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/cgroup/legacy_freezer.c:freeze_cgroup
  - kernel/cgroup/legacy_freezer.c:freezer_attach
```
**Symbols:**

```
ffffffff811297b0-ffffffff811298a9: freeze_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool freeze_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff8111c040)
Location: kernel/freezer.c:115
Inline: False
Direct callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/cgroup/legacy_freezer.c:freeze_cgroup
  - kernel/cgroup/legacy_freezer.c:freezer_attach
```
**Symbols:**

```
ffffffff8111c040-ffffffff8111c139: freeze_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool freeze_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff811274d0)
Location: kernel/freezer.c:115
Inline: False
Direct callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/cgroup/legacy_freezer.c:freeze_cgroup
  - kernel/cgroup/legacy_freezer.c:freezer_attach
```
**Symbols:**

```
ffffffff811274d0-ffffffff811275c9: freeze_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool freeze_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff81133b10)
Location: kernel/freezer.c:115
Inline: False
Direct callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/cgroup/legacy_freezer.c:freeze_cgroup
  - kernel/cgroup/legacy_freezer.c:freezer_attach
```
**Symbols:**

```
ffffffff81133b10-ffffffff81133c09: freeze_task (STB_GLOBAL)
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
