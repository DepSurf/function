# Function: <code>free_thread_stack</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8107fe1f)
Location: kernel/fork.c:176
Inline: True
Inline callers:
  - kernel/fork.c:free_task
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81084818)
Location: kernel/fork.c:219
Inline: True
Inline callers:
  - kernel/fork.c:put_task_stack
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81081739)
Location: kernel/fork.c:247
Inline: True
Inline callers:
  - kernel/fork.c:put_task_stack
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8108801a)
Location: kernel/fork.c:253
Inline: True
Inline callers:
  - kernel/fork.c:put_task_stack
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
In kernel/fork.c (ffffffff8108bd6c)
Location: kernel/fork.c:253
Inline: True
Inline callers:
  - kernel/fork.c:put_task_stack
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
In kernel/fork.c (ffffffff810935eb)
Location: kernel/fork.c:258
Inline: True
Inline callers:
  - kernel/fork.c:put_task_stack
  - kernel/fork.c:put_task_stack
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
In kernel/fork.c (ffffffff81098b82)
Location: kernel/fork.c:264
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:put_task_stack
  - kernel/fork.c:put_task_stack
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
In kernel/fork.c (ffffffff8109f144)
Location: kernel/fork.c:273
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:put_task_stack
  - kernel/fork.c:put_task_stack
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void free_thread_stack(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a4650)
Location: kernel/fork.c:276
Inline: True
Direct callers:
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:put_task_stack
```
**Symbols:**

```
ffffffff810a4650-ffffffff810a475c: free_thread_stack (STB_LOCAL)
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
In kernel/fork.c (ffffffff810a147e)
Location: kernel/fork.c:277
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:put_task_stack
  - kernel/fork.c:put_task_stack
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
In kernel/fork.c (ffffffff810a21f9)
Location: kernel/fork.c:278
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:put_task_stack
  - kernel/fork.c:put_task_stack
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
In kernel/fork.c (ffffffff810b3005)
Location: kernel/fork.c:278
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:put_task_stack
  - kernel/fork.c:put_task_stack
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
In kernel/fork.c (ffffffff810c9069)
Location: kernel/fork.c:341
Inline: True
Inline callers:
  - kernel/fork.c:put_task_stack
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
In kernel/fork.c (ffffffff810e6539)
Location: kernel/fork.c:340
Inline: True
Inline callers:
  - kernel/fork.c:put_task_stack
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
In kernel/fork.c (ffffffff810f1ea9)
Location: kernel/fork.c:338
Inline: True
Inline callers:
  - kernel/fork.c:put_task_stack
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
In kernel/fork.c (ffffffff810fbb09)
Location: kernel/fork.c:336
Inline: True
Inline callers:
  - kernel/fork.c:put_task_stack
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void free_thread_stack(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffff8000100f18c0)
Location: kernel/fork.c:273
Inline: True
Direct callers:
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:put_task_stack
```
**Symbols:**

```
ffff8000100f18c0-ffff8000100f1a04: free_thread_stack (STB_LOCAL)
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
In kernel/fork.c (c0352220)
Location: kernel/fork.c:273
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:free_task
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
In kernel/fork.c (c000000000139990)
Location: kernel/fork.c:316
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:put_task_stack
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
In kernel/fork.c (ffffffe0000c01d8)
Location: kernel/fork.c:273
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:release_task_stack
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
In kernel/fork.c (ffffffff81098a64)
Location: kernel/fork.c:273
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:put_task_stack
  - kernel/fork.c:put_task_stack
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
In kernel/fork.c (ffffffff810874c8)
Location: kernel/fork.c:273
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:put_task_stack
  - kernel/fork.c:put_task_stack
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
In kernel/fork.c (ffffffff81098a14)
Location: kernel/fork.c:273
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:put_task_stack
  - kernel/fork.c:put_task_stack
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
In kernel/fork.c (ffffffff810a0632)
Location: kernel/fork.c:273
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:put_task_stack
  - kernel/fork.c:put_task_stack
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
<b>Arch</b>
<ul>
</ul>
