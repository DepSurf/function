# Function: <code>__bpf_spin_unlock_irqrestore</code>

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
void __bpf_spin_unlock_irqrestore(struct bpf_spin_lock *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff8124f730)
Location: kernel/bpf/helpers.c:314
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:bpf_timer_cancel_and_free
  - kernel/bpf/helpers.c:bpf_timer_cancel_and_free
  - kernel/bpf/helpers.c:bpf_timer_cancel
  - kernel/bpf/helpers.c:bpf_timer_cancel
  - kernel/bpf/helpers.c:bpf_timer_cancel
  - kernel/bpf/helpers.c:bpf_timer_start
  - kernel/bpf/helpers.c:bpf_timer_set_callback
  - kernel/bpf/helpers.c:bpf_timer_init
  - kernel/bpf/helpers.c:copy_map_value_locked
  - kernel/bpf/helpers.c:bpf_spin_unlock
```
**Symbols:**

```
ffffffff8124f730-ffffffff8124f753: __bpf_spin_unlock_irqrestore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __bpf_spin_unlock_irqrestore(struct bpf_spin_lock *lock);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff812976a0)
Location: kernel/bpf/helpers.c:328
Inline: True
Direct callers:
  - kernel/bpf/helpers.c:bpf_timer_cancel_and_free
  - kernel/bpf/helpers.c:bpf_timer_cancel_and_free
  - kernel/bpf/helpers.c:bpf_timer_cancel
  - kernel/bpf/helpers.c:bpf_timer_cancel
  - kernel/bpf/helpers.c:bpf_timer_cancel
  - kernel/bpf/helpers.c:bpf_timer_start
  - kernel/bpf/helpers.c:bpf_timer_set_callback
  - kernel/bpf/helpers.c:bpf_timer_init
  - kernel/bpf/helpers.c:copy_map_value_locked
  - kernel/bpf/helpers.c:bpf_spin_unlock
```
**Symbols:**

```
ffffffff812976a0-ffffffff812976c9: __bpf_spin_unlock_irqrestore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __bpf_spin_unlock_irqrestore(struct bpf_spin_lock *lock);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff812f2520)
Location: kernel/bpf/helpers.c:344
Inline: True
Direct callers:
  - kernel/bpf/helpers.c:bpf_list_head_free
  - kernel/bpf/helpers.c:bpf_list_head_free
  - kernel/bpf/helpers.c:bpf_timer_cancel_and_free
  - kernel/bpf/helpers.c:bpf_timer_cancel_and_free
  - kernel/bpf/helpers.c:bpf_timer_cancel
  - kernel/bpf/helpers.c:bpf_timer_cancel
  - kernel/bpf/helpers.c:bpf_timer_cancel
  - kernel/bpf/helpers.c:bpf_timer_start
  - kernel/bpf/helpers.c:bpf_timer_set_callback
  - kernel/bpf/helpers.c:bpf_timer_init
  - kernel/bpf/helpers.c:copy_map_value_locked
  - kernel/bpf/helpers.c:bpf_spin_unlock
```
**Symbols:**

```
ffffffff812f2520-ffffffff812f2554: __bpf_spin_unlock_irqrestore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __bpf_spin_unlock_irqrestore(struct bpf_spin_lock *lock);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff8131f0a0)
Location: kernel/bpf/helpers.c:345
Inline: True
Direct callers:
  - kernel/bpf/helpers.c:bpf_rb_root_free
  - kernel/bpf/helpers.c:bpf_list_head_free
  - kernel/bpf/helpers.c:bpf_list_head_free
  - kernel/bpf/helpers.c:bpf_timer_cancel_and_free
  - kernel/bpf/helpers.c:bpf_timer_cancel_and_free
  - kernel/bpf/helpers.c:bpf_timer_cancel
  - kernel/bpf/helpers.c:bpf_timer_cancel
  - kernel/bpf/helpers.c:bpf_timer_cancel
  - kernel/bpf/helpers.c:bpf_timer_start
  - kernel/bpf/helpers.c:bpf_timer_set_callback
  - kernel/bpf/helpers.c:bpf_timer_init
  - kernel/bpf/helpers.c:copy_map_value_locked
  - kernel/bpf/helpers.c:bpf_spin_unlock
```
**Symbols:**

```
ffffffff8131f0a0-ffffffff8131f0d4: __bpf_spin_unlock_irqrestore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __bpf_spin_unlock_irqrestore(struct bpf_spin_lock *lock);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff813414d0)
Location: kernel/bpf/helpers.c:351
Inline: True
Direct callers:
  - kernel/bpf/helpers.c:bpf_rb_root_free
  - kernel/bpf/helpers.c:bpf_list_head_free
  - kernel/bpf/helpers.c:bpf_list_head_free
  - kernel/bpf/helpers.c:bpf_timer_cancel_and_free
  - kernel/bpf/helpers.c:bpf_timer_cancel_and_free
  - kernel/bpf/helpers.c:bpf_timer_cancel
  - kernel/bpf/helpers.c:bpf_timer_cancel
  - kernel/bpf/helpers.c:bpf_timer_cancel
  - kernel/bpf/helpers.c:bpf_timer_start
  - kernel/bpf/helpers.c:bpf_timer_set_callback
  - kernel/bpf/helpers.c:bpf_timer_init
  - kernel/bpf/helpers.c:copy_map_value_locked
  - kernel/bpf/helpers.c:bpf_spin_unlock
```
**Symbols:**

```
ffffffff813414d0-ffffffff81341514: __bpf_spin_unlock_irqrestore (STB_LOCAL)
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
