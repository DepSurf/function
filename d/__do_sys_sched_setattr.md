# Function: <code>__do_sys_sched_setattr</code>

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
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bdd67)
Location: kernel/sched/core.c:4578
Inline: True
Inline callers:
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
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
In kernel/sched/core.c (ffffffff810c6f17)
Location: kernel/sched/core.c:4563
Inline: True
Inline callers:
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
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
In kernel/sched/core.c (ffffffff810cd467)
Location: kernel/sched/core.c:5004
Inline: True
Inline callers:
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
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
In kernel/sched/core.c (ffffffff810d6e97)
Location: kernel/sched/core.c:5195
Inline: True
Inline callers:
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e1397)
Location: kernel/sched/core.c:5428
Inline: True
Inline callers:
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810de6a7)
Location: kernel/sched/core.c:6247
Inline: True
Inline callers:
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e0297)
Location: kernel/sched/core.c:6548
Inline: True
Inline callers:
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __do_sys_sched_setattr(pid_t pid, struct sched_attr *uattr, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810f54c0)
Location: kernel/sched/core.c:7722
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
```
**Symbols:**

```
ffffffff810f54c0-ffffffff810f567d: __do_sys_sched_setattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __do_sys_sched_setattr(pid_t pid, struct sched_attr *uattr, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81111f10)
Location: kernel/sched/core.c:7830
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
```
**Symbols:**

```
ffffffff81111f10-ffffffff81112101: __do_sys_sched_setattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __do_sys_sched_setattr(pid_t pid, struct sched_attr *uattr, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81138f00)
Location: kernel/sched/core.c:7972
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
```
**Symbols:**

```
ffffffff81138f00-ffffffff811390f1: __do_sys_sched_setattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __do_sys_sched_setattr(pid_t pid, struct sched_attr *uattr, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81148170)
Location: kernel/sched/core.c:8081
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
```
**Symbols:**

```
ffffffff81148170-ffffffff81148368: __do_sys_sched_setattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff811539dd)
Location: kernel/sched/core.c:8132
Inline: True
Inline callers:
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
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
In kernel/sched/core.c (ffff8000101376f0)
Location: kernel/sched/core.c:5195
Inline: True
Inline callers:
  - kernel/sched/core.c:__arm64_sys_sched_setattr
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
In kernel/sched/core.c (c038c2d8)
Location: kernel/sched/core.c:5195
Inline: True
Inline callers:
  - kernel/sched/core.c:__se_sys_sched_setattr
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
In kernel/sched/core.c (c000000000182d38)
Location: kernel/sched/core.c:5195
Inline: True
Inline callers:
  - kernel/sched/core.c:__se_sys_sched_setattr
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
In kernel/sched/core.c (ffffffe0000eb978)
Location: kernel/sched/core.c:5195
Inline: True
Inline callers:
  - kernel/sched/core.c:__se_sys_sched_setattr
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
In kernel/sched/core.c (ffffffff810d1467)
Location: kernel/sched/core.c:5195
Inline: True
Inline callers:
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
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
In kernel/sched/core.c (ffffffff810bf7d7)
Location: kernel/sched/core.c:5195
Inline: True
Inline callers:
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
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
In kernel/sched/core.c (ffffffff810cf527)
Location: kernel/sched/core.c:5195
Inline: True
Inline callers:
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
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
In kernel/sched/core.c (ffffffff810d8b47)
Location: kernel/sched/core.c:5195
Inline: True
Inline callers:
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
</ul>
