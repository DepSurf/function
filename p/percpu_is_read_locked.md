# Function: <code>percpu_is_read_locked</code>

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
bool percpu_is_read_locked(struct percpu_rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff8117da40)
Location: kernel/locking/percpu-rwsem.c:195
Inline: False
Direct callers:
  - kernel/events/hw_breakpoint.c:dbg_release_bp_slot
  - kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot
```
**Symbols:**

```
ffffffff8117da40-ffffffff8117dae6: percpu_is_read_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool percpu_is_read_locked(struct percpu_rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff8118e6e0)
Location: kernel/locking/percpu-rwsem.c:195
Inline: False
Direct callers:
  - kernel/events/hw_breakpoint.c:dbg_release_bp_slot
  - kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot
```
**Symbols:**

```
ffffffff8118e6e0-ffffffff8118e786: percpu_is_read_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool percpu_is_read_locked(struct percpu_rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff8119d090)
Location: kernel/locking/percpu-rwsem.c:195
Inline: False
Direct callers:
  - kernel/events/hw_breakpoint.c:dbg_release_bp_slot
  - kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot
```
**Symbols:**

```
ffffffff8119d090-ffffffff8119d136: percpu_is_read_locked (STB_GLOBAL)
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
