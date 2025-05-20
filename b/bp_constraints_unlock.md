# Function: <code>bp_constraints_unlock</code>

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
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void bp_constraints_unlock(struct mutex *tsk_mtx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff8134cd80)
Location: kernel/events/hw_breakpoint.c:139
Inline: True
Direct callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check
  - kernel/events/hw_breakpoint.c:register_perf_hw_breakpoint
  - kernel/events/hw_breakpoint.c:release_bp_slot
  - kernel/events/hw_breakpoint.c:release_bp_slot
```
**Symbols:**

```
ffffffff8134cd80-ffffffff8134ce0b: bp_constraints_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void bp_constraints_unlock(struct mutex *tsk_mtx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff8137dbd0)
Location: kernel/events/hw_breakpoint.c:139
Inline: True
Direct callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check
  - kernel/events/hw_breakpoint.c:register_perf_hw_breakpoint
  - kernel/events/hw_breakpoint.c:release_bp_slot
  - kernel/events/hw_breakpoint.c:release_bp_slot
```
**Symbols:**

```
ffffffff8137dbd0-ffffffff8137dc5b: bp_constraints_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void bp_constraints_unlock(struct mutex *tsk_mtx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff813a6e30)
Location: kernel/events/hw_breakpoint.c:139
Inline: True
Direct callers:
  - kernel/events/hw_breakpoint.c:bp_perf_event_destroy
  - kernel/events/hw_breakpoint.c:bp_perf_event_destroy
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check
  - kernel/events/hw_breakpoint.c:register_perf_hw_breakpoint
  - kernel/events/hw_breakpoint.c:register_perf_hw_breakpoint
```
**Symbols:**

```
ffffffff813a6e30-ffffffff813a6ebb: bp_constraints_unlock (STB_LOCAL)
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
