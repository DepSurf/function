# Function: <code>memcpy_common</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8117b86b)
Location: kernel/events/internal.h:148
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
```
```
In kernel/events/ring_buffer.c (ffffffff811854f6)
Location: kernel/events/internal.h:148
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8118d8b0)
Location: kernel/events/internal.h:169
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
```
```
In kernel/events/ring_buffer.c (ffffffff811971f0)
Location: kernel/events/internal.h:169
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_copy
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8119d1a0)
Location: kernel/events/internal.h:169
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
```
```
In kernel/events/ring_buffer.c (ffffffff811a6be0)
Location: kernel/events/internal.h:169
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_copy
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a66a4)
Location: kernel/events/internal.h:169
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
```
```
In kernel/events/ring_buffer.c (ffffffff811ae380)
Location: kernel/events/internal.h:169
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_copy
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811b49c0)
Location: kernel/events/internal.h:170
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
```
```
In kernel/events/ring_buffer.c (ffffffff811c1ff0)
Location: kernel/events/internal.h:170
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_copy
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811da2b5)
Location: kernel/events/internal.h:170
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
```
```
In kernel/events/ring_buffer.c (ffffffff811e23c5)
Location: kernel/events/internal.h:170
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_copy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811eb145)
Location: kernel/events/internal.h:170
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
```
```
In kernel/events/ring_buffer.c (ffffffff811f2835)
Location: kernel/events/internal.h:170
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_copy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81200ac3)
Location: kernel/events/internal.h:171
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_ksymbol_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
```
```
In kernel/events/ring_buffer.c (ffffffff8120a500)
Location: kernel/events/internal.h:171
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_copy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120dba3)
Location: kernel/events/internal.h:171
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_ksymbol_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
```
```
In kernel/events/ring_buffer.c (ffffffff812177e0)
Location: kernel/events/internal.h:171
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_copy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81237851)
Location: kernel/events/internal.h:172
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_ksymbol_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_cgroup_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read_group
  - kernel/events/core.c:perf_output_read_group
```
```
In kernel/events/ring_buffer.c (ffffffff8124399a)
Location: kernel/events/internal.h:172
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_copy_aux
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812420a3)
Location: kernel/events/internal.h:172
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_text_poke_output
  - kernel/events/core.c:perf_event_text_poke_output
  - kernel/events/core.c:perf_event_text_poke_output
  - kernel/events/core.c:perf_event_ksymbol_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_cgroup_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read_group
  - kernel/events/core.c:perf_output_read_group
```
```
In kernel/events/ring_buffer.c (ffffffff8124e02a)
Location: kernel/events/internal.h:172
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_copy_aux
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812475d3)
Location: kernel/events/internal.h:172
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_text_poke_output
  - kernel/events/core.c:perf_event_text_poke_output
  - kernel/events/core.c:perf_event_text_poke_output
  - kernel/events/core.c:perf_event_ksymbol_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_cgroup_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read_group
  - kernel/events/core.c:perf_output_read_group
```
```
In kernel/events/ring_buffer.c (ffffffff81252975)
Location: kernel/events/internal.h:172
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_copy_aux
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81281933)
Location: kernel/events/internal.h:172
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_text_poke_output
  - kernel/events/core.c:perf_event_text_poke_output
  - kernel/events/core.c:perf_event_text_poke_output
  - kernel/events/core.c:perf_event_ksymbol_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_cgroup_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read_group
  - kernel/events/core.c:perf_output_read_group
```
```
In kernel/events/ring_buffer.c (ffffffff8128e235)
Location: kernel/events/internal.h:172
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_copy_aux
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812d74b5)
Location: kernel/events/internal.h:177
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_text_poke_output
  - kernel/events/core.c:perf_event_text_poke_output
  - kernel/events/core.c:perf_event_text_poke_output
  - kernel/events/core.c:perf_event_ksymbol_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_cgroup_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read_group
  - kernel/events/core.c:perf_output_read_group
```
```
In kernel/events/ring_buffer.c (ffffffff812e3095)
Location: kernel/events/internal.h:177
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_copy_aux
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81336226)
Location: kernel/events/internal.h:177
Inline: True
```
```
In kernel/events/ring_buffer.c (ffffffff8134aaa6)
Location: kernel/events/internal.h:177
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:__output_copy
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81366f66)
Location: kernel/events/internal.h:177
Inline: True
```
```
In kernel/events/ring_buffer.c (ffffffff8137bae6)
Location: kernel/events/internal.h:177
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:__output_copy
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff813900d6)
Location: kernel/events/internal.h:177
Inline: True
```
```
In kernel/events/ring_buffer.c (ffffffff813a4d26)
Location: kernel/events/internal.h:177
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:__output_copy
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff80001029595c)
Location: kernel/events/internal.h:171
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_ksymbol_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
```
```
In kernel/events/ring_buffer.c (ffff8000102a20f4)
Location: kernel/events/internal.h:171
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_copy
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04c6b20)
Location: kernel/events/internal.h:171
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_ksymbol_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
```
```
In kernel/events/ring_buffer.c (c04d1c18)
Location: kernel/events/internal.h:171
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_copy
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c0000000003452c4)
Location: kernel/events/internal.h:171
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_ksymbol_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
```
```
In kernel/events/ring_buffer.c (c000000000353fd0)
Location: kernel/events/internal.h:171
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_copy
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001c7ac6)
Location: kernel/events/internal.h:171
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_ksymbol_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
```
```
In kernel/events/ring_buffer.c (ffffffe0001d0f22)
Location: kernel/events/internal.h:171
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_copy
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812061c3)
Location: kernel/events/internal.h:171
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_ksymbol_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
```
```
In kernel/events/ring_buffer.c (ffffffff8120fe30)
Location: kernel/events/internal.h:171
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_copy
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811f8f43)
Location: kernel/events/internal.h:171
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_ksymbol_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
```
```
In kernel/events/ring_buffer.c (ffffffff81202bc0)
Location: kernel/events/internal.h:171
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_copy
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81203f93)
Location: kernel/events/internal.h:171
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_ksymbol_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
```
```
In kernel/events/ring_buffer.c (ffffffff8120dbd0)
Location: kernel/events/internal.h:171
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_copy
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81213bc3)
Location: kernel/events/internal.h:171
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_ksymbol_output
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
```
```
In kernel/events/ring_buffer.c (ffffffff8121ca80)
Location: kernel/events/internal.h:171
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_copy
```
</details>
</li>
</ul>

## Differences
