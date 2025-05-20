# Function: <code>sched_core_share_pid</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sched_core_share_pid(unsigned int cmd, pid_t pid, enum pid_type type, long unsigned int uaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core_sched.c (ffffffff8112c3d0)
Location: kernel/sched/core_sched.c:126
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prctl
```
**Symbols:**

```
ffffffff8112c3d0-ffffffff8112c8b3: sched_core_share_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sched_core_share_pid(unsigned int cmd, pid_t pid, enum pid_type type, long unsigned int uaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8114b610)
Location: kernel/sched/core_sched.c:128
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prctl
```
**Symbols:**

```
ffffffff8114b610-ffffffff8114bae3: sched_core_share_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sched_core_share_pid(unsigned int cmd, pid_t pid, enum pid_type type, long unsigned int uaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8117a0a0)
Location: kernel/sched/core_sched.c:129
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prctl
```
**Symbols:**

```
ffffffff8117a0a0-ffffffff8117a582: sched_core_share_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sched_core_share_pid(unsigned int cmd, pid_t pid, enum pid_type type, long unsigned int uaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8118ac00)
Location: kernel/sched/core_sched.c:129
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prctl
```
**Symbols:**

```
ffffffff8118ac00-ffffffff8118b0ed: sched_core_share_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sched_core_share_pid(unsigned int cmd, pid_t pid, enum pid_type type, long unsigned int uaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81199510)
Location: kernel/sched/core_sched.c:129
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prctl
```
**Symbols:**

```
ffffffff81199510-ffffffff81199a1a: sched_core_share_pid (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
