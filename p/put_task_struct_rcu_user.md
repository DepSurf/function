# Function: <code>put_task_struct_rcu_user</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void put_task_struct_rcu_user(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a4ac0)
Location: kernel/exit.c:185
Inline: True
Direct callers:
  - kernel/exit.c:release_task
  - kernel/sched/core.c:finish_task_switch
```
**Symbols:**

```
ffffffff810a4ac0-ffffffff810a4af1: put_task_struct_rcu_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void put_task_struct_rcu_user(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810ac550)
Location: kernel/exit.c:175
Inline: False
Direct callers:
  - kernel/exit.c:release_task
  - kernel/sched/core.c:finish_task_switch
```
**Symbols:**

```
ffffffff810ac550-ffffffff810ac598: put_task_struct_rcu_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void put_task_struct_rcu_user(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a7c10)
Location: kernel/exit.c:176
Inline: False
Direct callers:
  - kernel/exit.c:release_task
```
**Symbols:**

```
ffffffff810a7c10-ffffffff810a7c58: put_task_struct_rcu_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void put_task_struct_rcu_user(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a8af0)
Location: kernel/exit.c:176
Inline: False
Direct callers:
  - kernel/exit.c:release_task
```
**Symbols:**

```
ffffffff810a8af0-ffffffff810a8b38: put_task_struct_rcu_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void put_task_struct_rcu_user(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810ba5d0)
Location: kernel/exit.c:176
Inline: False
Direct callers:
  - kernel/exit.c:release_task
```
**Symbols:**

```
ffffffff810ba5d0-ffffffff810ba618: put_task_struct_rcu_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void put_task_struct_rcu_user(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810d1140)
Location: kernel/exit.c:180
Inline: True
Direct callers:
  - kernel/exit.c:release_task
  - kernel/exit.c:release_task
```
**Symbols:**

```
ffffffff810d1140-ffffffff810d11ac: put_task_struct_rcu_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void put_task_struct_rcu_user(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810efb50)
Location: kernel/exit.c:228
Inline: True
Direct callers:
  - kernel/exit.c:release_task
  - kernel/exit.c:release_task
```
**Symbols:**

```
ffffffff810efb50-ffffffff810efbbc: put_task_struct_rcu_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void put_task_struct_rcu_user(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810fbb10)
Location: kernel/exit.c:229
Inline: True
Direct callers:
  - kernel/exit.c:release_task
  - kernel/exit.c:release_task
  - kernel/bpf/helpers.c:bpf_task_release
```
**Symbols:**

```
ffffffff810fbb10-ffffffff810fbb80: put_task_struct_rcu_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void put_task_struct_rcu_user(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff81105010)
Location: kernel/exit.c:232
Inline: True
Direct callers:
  - kernel/exit.c:release_task
  - kernel/exit.c:release_task
  - kernel/bpf/helpers.c:bpf_task_release_dtor
  - kernel/bpf/helpers.c:bpf_task_release
```
**Symbols:**

```
ffffffff81105010-ffffffff81105080: put_task_struct_rcu_user (STB_GLOBAL)
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
void put_task_struct_rcu_user(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffff8000100fa8f8)
Location: kernel/exit.c:185
Inline: False
Direct callers:
  - kernel/exit.c:release_task
  - kernel/sched/core.c:finish_task_switch
```
**Symbols:**

```
ffff8000100fa8f8-ffff8000100fa94c: put_task_struct_rcu_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void put_task_struct_rcu_user(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (c035871c)
Location: kernel/exit.c:185
Inline: False
Direct callers:
  - kernel/exit.c:release_task
  - kernel/sched/core.c:finish_task_switch
```
**Symbols:**

```
c035871c-c035875c: put_task_struct_rcu_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void put_task_struct_rcu_user(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (c000000000141c00)
Location: kernel/exit.c:185
Inline: False
Direct callers:
  - kernel/exit.c:release_task
  - kernel/sched/core.c:finish_task_switch
```
**Symbols:**

```
c000000000141c00-c000000000141c68: put_task_struct_rcu_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void put_task_struct_rcu_user(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffe0000c47c0)
Location: kernel/exit.c:185
Inline: True
Inline callers:
  - kernel/exit.c:release_task
Direct callers:
  - kernel/sched/core.c:finish_task_switch
```
**Symbols:**

```
ffffffe0000c4734-ffffffe0000c4784: put_task_struct_rcu_user (STB_GLOBAL)
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
void put_task_struct_rcu_user(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8109e3e0)
Location: kernel/exit.c:185
Inline: True
Direct callers:
  - kernel/exit.c:release_task
  - kernel/sched/core.c:finish_task_switch
```
**Symbols:**

```
ffffffff8109e3e0-ffffffff8109e411: put_task_struct_rcu_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void put_task_struct_rcu_user(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8108cdf0)
Location: kernel/exit.c:185
Inline: True
Direct callers:
  - kernel/exit.c:release_task
  - kernel/sched/core.c:finish_task_switch
```
**Symbols:**

```
ffffffff8108cdf0-ffffffff8108ce21: put_task_struct_rcu_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void put_task_struct_rcu_user(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8109e390)
Location: kernel/exit.c:185
Inline: True
Direct callers:
  - kernel/exit.c:release_task
  - kernel/sched/core.c:finish_task_switch
```
**Symbols:**

```
ffffffff8109e390-ffffffff8109e3c1: put_task_struct_rcu_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void put_task_struct_rcu_user(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a62a0)
Location: kernel/exit.c:185
Inline: True
Direct callers:
  - kernel/exit.c:release_task
  - kernel/exit.c:release_task
  - kernel/sched/core.c:finish_task_switch
```
**Symbols:**

```
ffffffff810a62a0-ffffffff810a62d1: put_task_struct_rcu_user (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
