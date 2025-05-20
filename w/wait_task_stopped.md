# Function: <code>wait_task_stopped</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff81082973)
Location: kernel/exit.c:1151
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810859c6)
Location: kernel/exit.c:1236
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8108a936)
Location: kernel/exit.c:1226
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810878f9)
Location: kernel/exit.c:1211
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8108e689)
Location: kernel/exit.c:1210
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8109218b)
Location: kernel/exit.c:1210
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8109a492)
Location: kernel/exit.c:1213
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8109efea)
Location: kernel/exit.c:1217
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a557a)
Location: kernel/exit.c:1133
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int wait_task_stopped(struct wait_opts *wo, int ptrace, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810ac170)
Location: kernel/exit.c:1137
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
```
**Symbols:**

```
ffffffff810ac170-ffffffff810ac3af: wait_task_stopped (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int wait_task_stopped(struct wait_opts *wo, int ptrace, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a7810)
Location: kernel/exit.c:1156
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
```
**Symbols:**

```
ffffffff810a7810-ffffffff810a7a56: wait_task_stopped (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int wait_task_stopped(struct wait_opts *wo, int ptrace, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a88a0)
Location: kernel/exit.c:1156
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
```
**Symbols:**

```
ffffffff810a88a0-ffffffff810a8ae2: wait_task_stopped (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int wait_task_stopped(struct wait_opts *wo, int ptrace, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810ba380)
Location: kernel/exit.c:1156
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
```
**Symbols:**

```
ffffffff810ba380-ffffffff810ba5c1: wait_task_stopped (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int wait_task_stopped(struct wait_opts *wo, int ptrace, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810d0f20)
Location: kernel/exit.c:1160
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
```
**Symbols:**

```
ffffffff810d0f20-ffffffff810d1136: wait_task_stopped (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int wait_task_stopped(struct wait_opts *wo, int ptrace, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810ef920)
Location: kernel/exit.c:1254
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
```
**Symbols:**

```
ffffffff810ef920-ffffffff810efb36: wait_task_stopped (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int wait_task_stopped(struct wait_opts *wo, int ptrace, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810fb8e0)
Location: kernel/exit.c:1259
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
```
**Symbols:**

```
ffffffff810fb8e0-ffffffff810fbaf6: wait_task_stopped (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int wait_task_stopped(struct wait_opts *wo, int ptrace, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff81104de0)
Location: kernel/exit.c:1231
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
```
**Symbols:**

```
ffffffff81104de0-ffffffff81104ff6: wait_task_stopped (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffff8000100fb51c)
Location: kernel/exit.c:1133
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
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
In kernel/exit.c (c03597a4)
Location: kernel/exit.c:1133
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/exit.c (c000000000142994)
Location: kernel/exit.c:1133
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
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
In kernel/exit.c (ffffffe0000c5114)
Location: kernel/exit.c:1133
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8109ee9a)
Location: kernel/exit.c:1133
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8108d8da)
Location: kernel/exit.c:1133
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8109ee4a)
Location: kernel/exit.c:1133
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a6d8a)
Location: kernel/exit.c:1133
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
```
</details>
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
