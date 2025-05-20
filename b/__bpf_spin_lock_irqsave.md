# Function: <code>__bpf_spin_lock_irqsave</code>

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
void __bpf_spin_lock_irqsave(struct bpf_spin_lock *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff8124f940)
Location: kernel/bpf/helpers.c:292
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:bpf_timer_cancel_and_free
  - kernel/bpf/helpers.c:bpf_timer_cancel
  - kernel/bpf/helpers.c:bpf_timer_start
  - kernel/bpf/helpers.c:bpf_timer_set_callback
  - kernel/bpf/helpers.c:bpf_timer_init
  - kernel/bpf/helpers.c:copy_map_value_locked
  - kernel/bpf/helpers.c:bpf_spin_lock
```
**Symbols:**

```
ffffffff8124f940-ffffffff8124f97c: __bpf_spin_lock_irqsave (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __bpf_spin_lock_irqsave(struct bpf_spin_lock *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff81296ba0)
Location: kernel/bpf/helpers.c:306
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:bpf_timer_cancel_and_free
  - kernel/bpf/helpers.c:bpf_timer_cancel
  - kernel/bpf/helpers.c:bpf_timer_start
  - kernel/bpf/helpers.c:bpf_timer_set_callback
  - kernel/bpf/helpers.c:bpf_timer_init
  - kernel/bpf/helpers.c:copy_map_value_locked
  - kernel/bpf/helpers.c:bpf_spin_lock
```
**Symbols:**

```
ffffffff81296ba0-ffffffff81296bf3: __bpf_spin_lock_irqsave (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __bpf_spin_lock_irqsave(struct bpf_spin_lock *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff812f1b10)
Location: kernel/bpf/helpers.c:321
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:bpf_list_head_free
  - kernel/bpf/helpers.c:bpf_timer_cancel_and_free
  - kernel/bpf/helpers.c:bpf_timer_cancel
  - kernel/bpf/helpers.c:bpf_timer_start
  - kernel/bpf/helpers.c:bpf_timer_set_callback
  - kernel/bpf/helpers.c:bpf_timer_init
  - kernel/bpf/helpers.c:copy_map_value_locked
  - kernel/bpf/helpers.c:bpf_spin_lock
```
**Symbols:**

```
ffffffff812f1b10-ffffffff812f1b6a: __bpf_spin_lock_irqsave (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __bpf_spin_lock_irqsave(struct bpf_spin_lock *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff8131e6f0)
Location: kernel/bpf/helpers.c:322
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:bpf_rb_root_free
  - kernel/bpf/helpers.c:bpf_list_head_free
  - kernel/bpf/helpers.c:bpf_timer_cancel_and_free
  - kernel/bpf/helpers.c:bpf_timer_cancel
  - kernel/bpf/helpers.c:bpf_timer_start
  - kernel/bpf/helpers.c:bpf_timer_set_callback
  - kernel/bpf/helpers.c:bpf_timer_init
  - kernel/bpf/helpers.c:copy_map_value_locked
  - kernel/bpf/helpers.c:bpf_spin_lock
```
**Symbols:**

```
ffffffff8131e6f0-ffffffff8131e74a: __bpf_spin_lock_irqsave (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __bpf_spin_lock_irqsave(struct bpf_spin_lock *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff81340b10)
Location: kernel/bpf/helpers.c:328
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:bpf_rb_root_free
  - kernel/bpf/helpers.c:bpf_list_head_free
  - kernel/bpf/helpers.c:bpf_timer_cancel_and_free
  - kernel/bpf/helpers.c:bpf_timer_cancel
  - kernel/bpf/helpers.c:bpf_timer_start
  - kernel/bpf/helpers.c:bpf_timer_set_callback
  - kernel/bpf/helpers.c:bpf_timer_init
  - kernel/bpf/helpers.c:copy_map_value_locked
  - kernel/bpf/helpers.c:bpf_spin_lock
```
**Symbols:**

```
ffffffff81340b10-ffffffff81340b71: __bpf_spin_lock_irqsave (STB_LOCAL)
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
