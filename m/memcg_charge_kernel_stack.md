# Function: <code>memcg_charge_kernel_stack</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109432e)
Location: kernel/fork.c:392
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
In kernel/fork.c (ffffffff81098a42)
Location: kernel/fork.c:398
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
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
In kernel/fork.c (ffffffff8109f000)
Location: kernel/fork.c:407
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int memcg_charge_kernel_stack(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a43c0)
Location: kernel/fork.c:411
Inline: False
Direct callers:
  - kernel/fork.c:dup_task_struct
```
**Symbols:**

```
ffffffff810a43c0-ffffffff810a444b: memcg_charge_kernel_stack (STB_LOCAL)
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
In kernel/fork.c (ffffffff810a1328)
Location: kernel/fork.c:397
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
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
In kernel/fork.c (ffffffff810a2098)
Location: kernel/fork.c:401
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
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
In kernel/fork.c (ffffffff810b2e84)
Location: kernel/fork.c:401
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/fork.c (ffffffff810c82a3)
Location: kernel/fork.c:255
Inline: True
Inline callers:
  - kernel/fork.c:alloc_thread_stack_node
  - kernel/fork.c:alloc_thread_stack_node
Direct callers:
  - kernel/fork.c:alloc_thread_stack_node
  - kernel/fork.c:alloc_thread_stack_node
```
**Symbols:**

```
ffffffff810c81d0-ffffffff810c8254: memcg_charge_kernel_stack.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/fork.c (ffffffff810e54b3)
Location: kernel/fork.c:254
Inline: True
Inline callers:
  - kernel/fork.c:alloc_thread_stack_node
  - kernel/fork.c:alloc_thread_stack_node
Direct callers:
  - kernel/fork.c:alloc_thread_stack_node
  - kernel/fork.c:alloc_thread_stack_node
```
**Symbols:**

```
ffffffff810e53d0-ffffffff810e5454: memcg_charge_kernel_stack.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/fork.c (ffffffff810f0b63)
Location: kernel/fork.c:256
Inline: True
Inline callers:
  - kernel/fork.c:alloc_thread_stack_node
  - kernel/fork.c:alloc_thread_stack_node
Direct callers:
  - kernel/fork.c:alloc_thread_stack_node
  - kernel/fork.c:alloc_thread_stack_node
```
**Symbols:**

```
ffffffff810f0a70-ffffffff810f0b07: memcg_charge_kernel_stack.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/fork.c (ffffffff810f9f53)
Location: kernel/fork.c:254
Inline: True
Inline callers:
  - kernel/fork.c:alloc_thread_stack_node
  - kernel/fork.c:alloc_thread_stack_node
Direct callers:
  - kernel/fork.c:alloc_thread_stack_node
  - kernel/fork.c:alloc_thread_stack_node
```
**Symbols:**

```
ffffffff810f9e60-ffffffff810f9ef7: memcg_charge_kernel_stack.part.0 (STB_LOCAL)
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
In kernel/fork.c (ffff8000100f32a4)
Location: kernel/fork.c:407
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
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
In kernel/fork.c (0)
Location: kernel/fork.c:407
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
In kernel/fork.c (0)
Location: kernel/fork.c:407
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
In kernel/fork.c (0)
Location: kernel/fork.c:407
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
In kernel/fork.c (ffffffff81098920)
Location: kernel/fork.c:407
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
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
In kernel/fork.c (ffffffff8108738a)
Location: kernel/fork.c:407
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
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
In kernel/fork.c (ffffffff810988d0)
Location: kernel/fork.c:407
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
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
In kernel/fork.c (ffffffff810a04f7)
Location: kernel/fork.c:407
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
