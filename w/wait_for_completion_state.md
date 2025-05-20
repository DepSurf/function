# Function: <code>wait_for_completion_state</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int wait_for_completion_state(struct completion *x, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff820ce470)
Location: kernel/sched/completion.c:252
Inline: False
Direct callers:
  - kernel/fork.c:kernel_clone
  - kernel/umh.c:call_usermodehelper_exec
  - kernel/umh.c:call_usermodehelper_exec
  - fs/coredump.c:coredump_wait
```
**Symbols:**

```
ffffffff820ce470-ffffffff820ce657: wait_for_completion_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int wait_for_completion_state(struct completion *x, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff82152700)
Location: kernel/sched/completion.c:252
Inline: False
Direct callers:
  - kernel/fork.c:kernel_clone
  - kernel/umh.c:call_usermodehelper_exec
  - kernel/umh.c:call_usermodehelper_exec
  - fs/coredump.c:coredump_wait
```
**Symbols:**

```
ffffffff82152700-ffffffff821528e7: wait_for_completion_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int wait_for_completion_state(struct completion *x, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff82235560)
Location: kernel/sched/completion.c:262
Inline: False
Direct callers:
  - kernel/fork.c:kernel_clone
  - kernel/umh.c:call_usermodehelper_exec
  - kernel/umh.c:call_usermodehelper_exec
  - fs/coredump.c:coredump_wait
```
**Symbols:**

```
ffffffff82235560-ffffffff82235747: wait_for_completion_state (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
