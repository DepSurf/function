# Function: <code>__mark_reg_not_init</code>

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
In kernel/bpf/verifier.c (ffffffff811a34c0)
Location: kernel/bpf/verifier.c:579
Inline: True
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
In kernel/bpf/verifier.c (ffffffff811b7cde)
Location: kernel/bpf/verifier.c:707
Inline: True
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
In kernel/bpf/verifier.c (ffffffff811cd6eb)
Location: kernel/bpf/verifier.c:958
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
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
In kernel/bpf/verifier.c (ffffffff811e0789)
Location: kernel/bpf/verifier.c:1021
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:is_state_visited
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
In kernel/bpf/verifier.c (ffffffff811ecf76)
Location: kernel/bpf/verifier.c:1021
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:is_state_visited
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
In kernel/bpf/verifier.c (ffffffff8120234c)
Location: kernel/bpf/verifier.c:1333
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:clean_func_state
  - kernel/bpf/verifier.c:clean_func_state
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
In kernel/bpf/verifier.c (ffffffff8120202c)
Location: kernel/bpf/verifier.c:1363
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:clean_func_state
  - kernel/bpf/verifier.c:clean_func_state
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
In kernel/bpf/verifier.c (ffffffff8120449e)
Location: kernel/bpf/verifier.c:1455
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:clean_live_states
  - kernel/bpf/verifier.c:clean_live_states
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
In kernel/bpf/verifier.c (ffffffff81236b4b)
Location: kernel/bpf/verifier.c:1475
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:clean_live_states
  - kernel/bpf/verifier.c:clean_live_states
  - kernel/bpf/verifier.c:set_timer_callback_state
  - kernel/bpf/verifier.c:set_timer_callback_state
  - kernel/bpf/verifier.c:map_set_for_each_callback_args
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
In kernel/bpf/verifier.c (ffffffff8127b2ae)
Location: kernel/bpf/verifier.c:1678
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:clean_live_states
  - kernel/bpf/verifier.c:clean_live_states
  - kernel/bpf/verifier.c:set_find_vma_callback_state
  - kernel/bpf/verifier.c:set_find_vma_callback_state
  - kernel/bpf/verifier.c:set_timer_callback_state
  - kernel/bpf/verifier.c:set_timer_callback_state
  - kernel/bpf/verifier.c:set_loop_callback_state
  - kernel/bpf/verifier.c:set_loop_callback_state
  - kernel/bpf/verifier.c:set_loop_callback_state
  - kernel/bpf/verifier.c:map_set_for_each_callback_args
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
In kernel/bpf/verifier.c (ffffffff812e5f3f)
Location: kernel/bpf/verifier.c:1892
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:set_user_ringbuf_callback_state
  - kernel/bpf/verifier.c:set_user_ringbuf_callback_state
  - kernel/bpf/verifier.c:set_user_ringbuf_callback_state
  - kernel/bpf/verifier.c:set_user_ringbuf_callback_state
  - kernel/bpf/verifier.c:set_find_vma_callback_state
  - kernel/bpf/verifier.c:set_find_vma_callback_state
  - kernel/bpf/verifier.c:set_timer_callback_state
  - kernel/bpf/verifier.c:set_timer_callback_state
  - kernel/bpf/verifier.c:set_loop_callback_state
  - kernel/bpf/verifier.c:set_loop_callback_state
  - kernel/bpf/verifier.c:set_loop_callback_state
  - kernel/bpf/verifier.c:map_set_for_each_callback_args
  - kernel/bpf/verifier.c:destroy_if_dynptr_stack_slot
  - kernel/bpf/verifier.c:destroy_if_dynptr_stack_slot
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
In kernel/bpf/verifier.c (ffffffff81300044)
Location: kernel/bpf/verifier.c:2291
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:clean_live_states
  - kernel/bpf/verifier.c:clean_live_states
  - kernel/bpf/verifier.c:set_rbtree_add_callback_state
  - kernel/bpf/verifier.c:set_rbtree_add_callback_state
  - kernel/bpf/verifier.c:set_rbtree_add_callback_state
  - kernel/bpf/verifier.c:set_user_ringbuf_callback_state
  - kernel/bpf/verifier.c:set_user_ringbuf_callback_state
  - kernel/bpf/verifier.c:set_user_ringbuf_callback_state
  - kernel/bpf/verifier.c:set_user_ringbuf_callback_state
  - kernel/bpf/verifier.c:set_find_vma_callback_state
  - kernel/bpf/verifier.c:set_find_vma_callback_state
  - kernel/bpf/verifier.c:set_timer_callback_state
  - kernel/bpf/verifier.c:set_timer_callback_state
  - kernel/bpf/verifier.c:set_loop_callback_state
  - kernel/bpf/verifier.c:set_loop_callback_state
  - kernel/bpf/verifier.c:set_loop_callback_state
  - kernel/bpf/verifier.c:map_set_for_each_callback_args
  - kernel/bpf/verifier.c:clear_all_pkt_pointers
  - kernel/bpf/verifier.c:clear_all_pkt_pointers
  - kernel/bpf/verifier.c:process_iter_arg
  - kernel/bpf/verifier.c:process_spin_lock
  - kernel/bpf/verifier.c:process_spin_lock
  - kernel/bpf/verifier.c:mark_reg_stack_read
  - kernel/bpf/verifier.c:destroy_if_dynptr_stack_slot
  - kernel/bpf/verifier.c:destroy_if_dynptr_stack_slot
  - kernel/bpf/verifier.c:destroy_if_dynptr_stack_slot
  - kernel/bpf/verifier.c:destroy_if_dynptr_stack_slot
  - kernel/bpf/verifier.c:invalidate_dynptr
  - kernel/bpf/verifier.c:invalidate_dynptr
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
In kernel/bpf/verifier.c (ffffffff813298d9)
Location: kernel/bpf/verifier.c:2297
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:set_rbtree_add_callback_state
  - kernel/bpf/verifier.c:set_rbtree_add_callback_state
  - kernel/bpf/verifier.c:set_rbtree_add_callback_state
  - kernel/bpf/verifier.c:set_user_ringbuf_callback_state
  - kernel/bpf/verifier.c:set_user_ringbuf_callback_state
  - kernel/bpf/verifier.c:set_user_ringbuf_callback_state
  - kernel/bpf/verifier.c:set_user_ringbuf_callback_state
  - kernel/bpf/verifier.c:set_find_vma_callback_state
  - kernel/bpf/verifier.c:set_find_vma_callback_state
  - kernel/bpf/verifier.c:set_timer_callback_state
  - kernel/bpf/verifier.c:set_timer_callback_state
  - kernel/bpf/verifier.c:set_loop_callback_state
  - kernel/bpf/verifier.c:set_loop_callback_state
  - kernel/bpf/verifier.c:set_loop_callback_state
  - kernel/bpf/verifier.c:map_set_for_each_callback_args
  - kernel/bpf/verifier.c:invalidate_non_owning_refs
  - kernel/bpf/verifier.c:invalidate_non_owning_refs
  - kernel/bpf/verifier.c:clear_all_pkt_pointers
  - kernel/bpf/verifier.c:clear_all_pkt_pointers
  - kernel/bpf/verifier.c:process_iter_arg
  - kernel/bpf/verifier.c:destroy_if_dynptr_stack_slot
  - kernel/bpf/verifier.c:destroy_if_dynptr_stack_slot
  - kernel/bpf/verifier.c:destroy_if_dynptr_stack_slot
  - kernel/bpf/verifier.c:destroy_if_dynptr_stack_slot
  - kernel/bpf/verifier.c:invalidate_dynptr
  - kernel/bpf/verifier.c:invalidate_dynptr
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
In kernel/bpf/verifier.c (ffff8000102708ac)
Location: kernel/bpf/verifier.c:1021
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:is_state_visited
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
In kernel/bpf/verifier.c (c04a2bb8)
Location: kernel/bpf/verifier.c:1021
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:is_state_visited
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
In kernel/bpf/verifier.c (c000000000317a10)
Location: kernel/bpf/verifier.c:1021
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:is_state_visited
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
In kernel/bpf/verifier.c (ffffffe0001a9b22)
Location: kernel/bpf/verifier.c:1021
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:is_state_visited
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
In kernel/bpf/verifier.c (ffffffff811e5596)
Location: kernel/bpf/verifier.c:1021
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:is_state_visited
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
In kernel/bpf/verifier.c (ffffffff811d8356)
Location: kernel/bpf/verifier.c:1021
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:is_state_visited
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
In kernel/bpf/verifier.c (ffffffff811e3366)
Location: kernel/bpf/verifier.c:1021
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:is_state_visited
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
In kernel/bpf/verifier.c (ffffffff811f1736)
Location: kernel/bpf/verifier.c:1021
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:is_state_visited
```
</details>
</li>
</ul>

## Differences
