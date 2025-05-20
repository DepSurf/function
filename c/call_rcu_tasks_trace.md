# Function: <code>call_rcu_tasks_trace</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void call_rcu_tasks_trace(struct callback_head *rhp, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff81130d00)
Location: kernel/rcu/tasks.h:1111
Inline: False
```
**Symbols:**

```
ffffffff81130d00-ffffffff81130d80: call_rcu_tasks_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void call_rcu_tasks_trace(struct callback_head *rhp, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff8112c530)
Location: kernel/rcu/tasks.h:1135
Inline: False
Direct callers:
  - kernel/bpf/trampoline.c:bpf_tramp_image_put
```
**Symbols:**

```
ffffffff8112c530-ffffffff8112c5b0: call_rcu_tasks_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void call_rcu_tasks_trace(struct callback_head *rhp, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff8112ca60)
Location: kernel/rcu/tasks.h:1169
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__bpf_prog_put_noref
  - kernel/bpf/trampoline.c:bpf_tramp_image_put
```
**Symbols:**

```
ffffffff8112ca60-ffffffff8112cae0: call_rcu_tasks_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void call_rcu_tasks_trace(struct callback_head *rhp, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff8114d760)
Location: kernel/rcu/tasks.h:1223
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__bpf_prog_put_noref
  - kernel/bpf/trampoline.c:bpf_tramp_image_put
```
**Symbols:**

```
ffffffff8114d760-ffffffff8114d7e0: call_rcu_tasks_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void call_rcu_tasks_trace(struct callback_head *rhp, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff81173910)
Location: kernel/rcu/tasks.h:1592
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__bpf_prog_put_noref
  - kernel/bpf/bpf_local_storage.c:__bpf_selem_unlink_storage
  - kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_storage_nolock
```
**Symbols:**

```
ffffffff81173910-ffffffff81173931: call_rcu_tasks_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void call_rcu_tasks_trace(struct callback_head *rhp, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff811aad70)
Location: kernel/rcu/tasks.h:1717
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_array_free_sleepable
  - kernel/bpf/syscall.c:__bpf_prog_put_noref
  - kernel/bpf/bpf_local_storage.c:__bpf_selem_unlink_storage
  - kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_storage_nolock
  - kernel/bpf/memalloc.c:bpf_mem_refill
```
**Symbols:**

```
ffffffff811aad70-ffffffff811aad91: call_rcu_tasks_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void call_rcu_tasks_trace(struct callback_head *rhp, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff811bcca0)
Location: kernel/rcu/tasks.h:1754
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_array_free_sleepable
  - kernel/bpf/syscall.c:__bpf_prog_put_noref
  - kernel/bpf/memalloc.c:bpf_mem_refill
```
**Symbols:**

```
ffffffff811bcca0-ffffffff811bccc1: call_rcu_tasks_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void call_rcu_tasks_trace(struct callback_head *rhp, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff811cbb60)
Location: kernel/rcu/tasks.h:1870
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_array_free_sleepable
  - kernel/bpf/syscall.c:__bpf_prog_put_noref
```
**Symbols:**

```
ffffffff811cbb60-ffffffff811cbb81: call_rcu_tasks_trace (STB_GLOBAL)
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
