# Function: <code>kcmp_epoll_target</code>

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
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kcmp.c (ffffffff810f94e8)
Location: kernel/kcmp.c:102
Inline: True
Inline callers:
  - kernel/kcmp.c:SyS_kcmp
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
In kernel/kcmp.c (ffffffff81103f68)
Location: kernel/kcmp.c:103
Inline: True
Inline callers:
  - kernel/kcmp.c:SyS_kcmp
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int kcmp_epoll_target(struct task_struct *task1, struct task_struct *task2, long unsigned int idx1, struct kcmp_epoll_slot *uslot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kcmp.c (ffffffff8110e940)
Location: kernel/kcmp.c:103
Inline: False
Direct callers:
  - kernel/kcmp.c:__ia32_sys_kcmp
  - kernel/kcmp.c:__x64_sys_kcmp
```
**Symbols:**

```
ffffffff8110e940-ffffffff8110ea96: kcmp_epoll_target (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int kcmp_epoll_target(struct task_struct *task1, struct task_struct *task2, long unsigned int idx1, struct kcmp_epoll_slot *uslot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kcmp.c (ffffffff81119ec0)
Location: kernel/kcmp.c:103
Inline: False
Direct callers:
  - kernel/kcmp.c:__ia32_sys_kcmp
  - kernel/kcmp.c:__x64_sys_kcmp
```
**Symbols:**

```
ffffffff81119ec0-ffffffff8111a016: kcmp_epoll_target (STB_LOCAL)
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
In kernel/kcmp.c (ffffffff81124b69)
Location: kernel/kcmp.c:103
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
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
In kernel/kcmp.c (ffffffff81130b29)
Location: kernel/kcmp.c:103
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int kcmp_epoll_target(struct task_struct *task1, struct task_struct *task2, long unsigned int idx1, struct kcmp_epoll_slot *uslot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kcmp.c (ffffffff8113fb90)
Location: kernel/kcmp.c:103
Inline: False
Direct callers:
  - kernel/kcmp.c:__do_sys_kcmp
```
**Symbols:**

```
ffffffff8113fb90-ffffffff8113fce1: kcmp_epoll_target (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kcmp_epoll_target(struct task_struct *task1, struct task_struct *task2, long unsigned int idx1, struct kcmp_epoll_slot *uslot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kcmp.c (ffffffff8113bf30)
Location: kernel/kcmp.c:98
Inline: False
Direct callers:
  - kernel/kcmp.c:__do_sys_kcmp
```
**Symbols:**

```
ffffffff8113bf30-ffffffff8113c023: kcmp_epoll_target (STB_LOCAL)
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
In kernel/kcmp.c (ffffffff8113d46e)
Location: kernel/kcmp.c:98
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kcmp.c (ffffffff811605ee)
Location: kernel/kcmp.c:98
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kcmp.c (ffffffff8119339b)
Location: kernel/kcmp.c:98
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kcmp.c (ffffffff811d0bdb)
Location: kernel/kcmp.c:98
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kcmp.c (ffffffff811e4f25)
Location: kernel/kcmp.c:98
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
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
In kernel/kcmp.c (ffffffff811fac75)
Location: kernel/kcmp.c:100
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
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
int kcmp_epoll_target(struct task_struct *task1, struct task_struct *task2, long unsigned int idx1, struct kcmp_epoll_slot *uslot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kcmp.c (ffff800010197920)
Location: kernel/kcmp.c:103
Inline: False
Direct callers:
  - kernel/kcmp.c:__arm64_sys_kcmp
```
**Symbols:**

```
ffff800010197920-ffff800010197c1c: kcmp_epoll_target (STB_LOCAL)
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
In kernel/kcmp.c (c03e2d44)
Location: kernel/kcmp.c:103
Inline: True
Inline callers:
  - kernel/kcmp.c:__se_sys_kcmp
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
In kernel/kcmp.c (c0000000001f7c70)
Location: kernel/kcmp.c:103
Inline: True
Inline callers:
  - kernel/kcmp.c:__se_sys_kcmp
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
In kernel/kcmp.c (ffffffe000128b9a)
Location: kernel/kcmp.c:103
Inline: True
Inline callers:
  - kernel/kcmp.c:__se_sys_kcmp
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
In kernel/kcmp.c (ffffffff811292d9)
Location: kernel/kcmp.c:103
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
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
In kernel/kcmp.c (ffffffff8111bb69)
Location: kernel/kcmp.c:103
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
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
In kernel/kcmp.c (ffffffff81126ff9)
Location: kernel/kcmp.c:103
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
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
In kernel/kcmp.c (ffffffff8113363f)
Location: kernel/kcmp.c:103
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
