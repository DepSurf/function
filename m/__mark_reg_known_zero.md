# Function: <code>__mark_reg_known_zero</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811a17bc)
Location: kernel/bpf/verifier.c:447
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:mark_map_reg
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811b6989)
Location: kernel/bpf/verifier.c:567
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:mark_map_reg
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
In kernel/bpf/verifier.c (ffffffff811c625b)
Location: kernel/bpf/verifier.c:816
Inline: True
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
In kernel/bpf/verifier.c (ffffffff811d8582)
Location: kernel/bpf/verifier.c:875
Inline: True
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
In kernel/bpf/verifier.c (ffffffff811e4c72)
Location: kernel/bpf/verifier.c:876
Inline: True
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
In kernel/bpf/verifier.c (ffffffff81202f3b)
Location: kernel/bpf/verifier.c:1020
Inline: True
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
In kernel/bpf/verifier.c (ffffffff81203204)
Location: kernel/bpf/verifier.c:1052
Inline: True
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
In kernel/bpf/verifier.c (ffffffff81216436)
Location: kernel/bpf/verifier.c:1101
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:map_set_for_each_callback_args
  - kernel/bpf/verifier.c:map_set_for_each_callback_args
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
In kernel/bpf/verifier.c (ffffffff8124c786)
Location: kernel/bpf/verifier.c:1110
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:set_timer_callback_state
  - kernel/bpf/verifier.c:set_timer_callback_state
  - kernel/bpf/verifier.c:set_timer_callback_state
  - kernel/bpf/verifier.c:map_set_for_each_callback_args
  - kernel/bpf/verifier.c:map_set_for_each_callback_args
  - kernel/bpf/verifier.c:init_reg_state
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
In kernel/bpf/verifier.c (ffffffff812938fb)
Location: kernel/bpf/verifier.c:1337
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:set_find_vma_callback_state
  - kernel/bpf/verifier.c:set_timer_callback_state
  - kernel/bpf/verifier.c:set_timer_callback_state
  - kernel/bpf/verifier.c:set_timer_callback_state
  - kernel/bpf/verifier.c:map_set_for_each_callback_args
  - kernel/bpf/verifier.c:map_set_for_each_callback_args
  - kernel/bpf/verifier.c:init_reg_state
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
In kernel/bpf/verifier.c (ffffffff812ee38c)
Location: kernel/bpf/verifier.c:1538
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:set_user_ringbuf_callback_state
  - kernel/bpf/verifier.c:set_find_vma_callback_state
  - kernel/bpf/verifier.c:set_timer_callback_state
  - kernel/bpf/verifier.c:set_timer_callback_state
  - kernel/bpf/verifier.c:set_timer_callback_state
  - kernel/bpf/verifier.c:map_set_for_each_callback_args
  - kernel/bpf/verifier.c:map_set_for_each_callback_args
  - kernel/bpf/verifier.c:check_ptr_to_map_access
  - kernel/bpf/verifier.c:init_reg_state
  - kernel/bpf/verifier.c:mark_stack_slots_dynptr
  - kernel/bpf/verifier.c:mark_stack_slots_dynptr
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
In kernel/bpf/verifier.c (ffffffff8131ac5c)
Location: kernel/bpf/verifier.c:1917
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:set_rbtree_add_callback_state
  - kernel/bpf/verifier.c:set_rbtree_add_callback_state
  - kernel/bpf/verifier.c:set_user_ringbuf_callback_state
  - kernel/bpf/verifier.c:set_find_vma_callback_state
  - kernel/bpf/verifier.c:set_timer_callback_state
  - kernel/bpf/verifier.c:set_timer_callback_state
  - kernel/bpf/verifier.c:set_timer_callback_state
  - kernel/bpf/verifier.c:map_set_for_each_callback_args
  - kernel/bpf/verifier.c:map_set_for_each_callback_args
  - kernel/bpf/verifier.c:process_iter_arg
  - kernel/bpf/verifier.c:check_ptr_to_map_access
  - kernel/bpf/verifier.c:init_reg_state
  - kernel/bpf/verifier.c:mark_stack_slots_dynptr
  - kernel/bpf/verifier.c:mark_stack_slots_dynptr
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
In kernel/bpf/verifier.c (ffffffff8133cb60)
Location: kernel/bpf/verifier.c:1767
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:set_rbtree_add_callback_state
  - kernel/bpf/verifier.c:set_rbtree_add_callback_state
  - kernel/bpf/verifier.c:set_user_ringbuf_callback_state
  - kernel/bpf/verifier.c:set_find_vma_callback_state
  - kernel/bpf/verifier.c:set_timer_callback_state
  - kernel/bpf/verifier.c:set_timer_callback_state
  - kernel/bpf/verifier.c:set_timer_callback_state
  - kernel/bpf/verifier.c:map_set_for_each_callback_args
  - kernel/bpf/verifier.c:map_set_for_each_callback_args
  - kernel/bpf/verifier.c:process_iter_arg
  - kernel/bpf/verifier.c:check_ptr_to_map_access
  - kernel/bpf/verifier.c:init_reg_state
  - kernel/bpf/verifier.c:mark_stack_slots_dynptr
  - kernel/bpf/verifier.c:mark_stack_slots_dynptr
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
In kernel/bpf/verifier.c (ffff800010267588)
Location: kernel/bpf/verifier.c:876
Inline: True
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
In kernel/bpf/verifier.c (c049a264)
Location: kernel/bpf/verifier.c:876
Inline: True
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
In kernel/bpf/verifier.c (c00000000030cc2c)
Location: kernel/bpf/verifier.c:876
Inline: True
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
In kernel/bpf/verifier.c (ffffffe0001a2ac4)
Location: kernel/bpf/verifier.c:876
Inline: True
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
In kernel/bpf/verifier.c (ffffffff811dd292)
Location: kernel/bpf/verifier.c:876
Inline: True
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
In kernel/bpf/verifier.c (ffffffff811d0052)
Location: kernel/bpf/verifier.c:876
Inline: True
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
In kernel/bpf/verifier.c (ffffffff811db062)
Location: kernel/bpf/verifier.c:876
Inline: True
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
In kernel/bpf/verifier.c (ffffffff811e9472)
Location: kernel/bpf/verifier.c:876
Inline: True
```
</details>
</li>
</ul>

## Differences
