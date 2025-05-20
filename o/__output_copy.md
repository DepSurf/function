# Function: <code>__output_copy</code>

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
In kernel/events/core.c (ffffffff8117b864)
Location: kernel/events/internal.h:154
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
In kernel/events/ring_buffer.c (ffffffff811854ef)
Location: kernel/events/internal.h:154
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
In kernel/events/core.c (ffffffff8118d8a8)
Location: kernel/events/internal.h:175
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
In kernel/events/ring_buffer.c (ffffffff811971e9)
Location: kernel/events/internal.h:175
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
In kernel/events/core.c (ffffffff8119d198)
Location: kernel/events/internal.h:175
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
In kernel/events/ring_buffer.c (ffffffff811a6bd9)
Location: kernel/events/internal.h:175
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
In kernel/events/core.c (ffffffff811a669a)
Location: kernel/events/internal.h:175
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
In kernel/events/ring_buffer.c (ffffffff811ae379)
Location: kernel/events/internal.h:175
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
In kernel/events/core.c (ffffffff811b49b6)
Location: kernel/events/internal.h:176
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
In kernel/events/ring_buffer.c (ffffffff811c1fe9)
Location: kernel/events/internal.h:176
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
In kernel/events/core.c (ffffffff811da298)
Location: kernel/events/internal.h:176
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
In kernel/events/ring_buffer.c (ffffffff811e23a7)
Location: kernel/events/internal.h:176
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
In kernel/events/core.c (ffffffff811eb128)
Location: kernel/events/internal.h:176
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
In kernel/events/ring_buffer.c (ffffffff811f2817)
Location: kernel/events/internal.h:176
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
In kernel/events/core.c (ffffffff81200aac)
Location: kernel/events/internal.h:177
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
In kernel/events/ring_buffer.c (ffffffff8120a4e7)
Location: kernel/events/internal.h:177
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
In kernel/events/core.c (ffffffff8120db8c)
Location: kernel/events/internal.h:177
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
In kernel/events/ring_buffer.c (ffffffff812177c7)
Location: kernel/events/internal.h:177
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
In kernel/events/core.c (ffffffff8123783b)
Location: kernel/events/internal.h:178
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
In kernel/events/ring_buffer.c (ffffffff8124398e)
Location: kernel/events/internal.h:178
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
In kernel/events/core.c (ffffffff81242089)
Location: kernel/events/internal.h:178
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
In kernel/events/ring_buffer.c (ffffffff8124e01e)
Location: kernel/events/internal.h:178
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
In kernel/events/core.c (ffffffff812475b9)
Location: kernel/events/internal.h:178
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
In kernel/events/ring_buffer.c (ffffffff81252960)
Location: kernel/events/internal.h:178
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
In kernel/events/core.c (ffffffff81281919)
Location: kernel/events/internal.h:178
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
In kernel/events/ring_buffer.c (ffffffff8128e220)
Location: kernel/events/internal.h:178
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
In kernel/events/core.c (ffffffff812d749b)
Location: kernel/events/internal.h:183
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
In kernel/events/ring_buffer.c (ffffffff812e3080)
Location: kernel/events/internal.h:183
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_copy_aux
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int __output_copy(struct perf_output_handle *handle, const void *buf, long unsigned int len);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff81336200)
Location: kernel/events/internal.h:183
Inline: True
Direct callers:
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
In kernel/events/ring_buffer.c (ffffffff8134aa80)
Location: kernel/events/internal.h:183
Inline: False
Direct callers:
  - kernel/events/ring_buffer.c:perf_output_copy_aux
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
**Symbols:**

```
ffffffff81336200-ffffffff81336288: __output_copy.isra.0 (STB_LOCAL)
ffffffff8134aa80-ffffffff8134ab08: __output_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int __output_copy(struct perf_output_handle *handle, const void *buf, long unsigned int len);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff81366f40)
Location: kernel/events/internal.h:183
Inline: True
Direct callers:
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
In kernel/events/ring_buffer.c (ffffffff8137bac0)
Location: kernel/events/internal.h:183
Inline: False
Direct callers:
  - kernel/events/ring_buffer.c:perf_output_copy_aux
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
**Symbols:**

```
ffffffff81366f40-ffffffff81366fc8: __output_copy.isra.0 (STB_LOCAL)
ffffffff8137bac0-ffffffff8137bb48: __output_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int __output_copy(struct perf_output_handle *handle, const void *buf, long unsigned int len);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff813900b0)
Location: kernel/events/internal.h:183
Inline: True
Direct callers:
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
In kernel/events/ring_buffer.c (ffffffff813a4d00)
Location: kernel/events/internal.h:183
Inline: False
Direct callers:
  - kernel/events/ring_buffer.c:perf_output_copy_aux
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
**Symbols:**

```
ffffffff813900b0-ffffffff81390138: __output_copy.isra.0 (STB_LOCAL)
ffffffff813a4d00-ffffffff813a4d88: __output_copy (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int __output_copy(struct perf_output_handle *handle, const void *buf, long unsigned int len);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff800010295940)
Location: kernel/events/internal.h:177
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_ksymbol_output
  - kernel/events/core.c:perf_event_comm_output
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
  - kernel/events/core.c:perf_output_read
Direct callers:
  - kernel/events/core.c:perf_event_mmap_output
  - kernel/events/core.c:perf_output_sample
```
```
In kernel/events/ring_buffer.c (ffff8000102a20dc)
Location: kernel/events/internal.h:177
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_copy
```
**Symbols:**

```
ffff8000102916d0-ffff80001029178c: __output_copy (STB_LOCAL)
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
In kernel/events/core.c (c04c6b08)
Location: kernel/events/internal.h:177
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
In kernel/events/ring_buffer.c (c04d1bf0)
Location: kernel/events/internal.h:177
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
In kernel/events/core.c (c0000000003452ac)
Location: kernel/events/internal.h:177
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
In kernel/events/ring_buffer.c (c000000000353fb4)
Location: kernel/events/internal.h:177
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
In kernel/events/core.c (ffffffe0001c7ac4)
Location: kernel/events/internal.h:177
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
In kernel/events/ring_buffer.c (ffffffe0001d0f20)
Location: kernel/events/internal.h:177
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
In kernel/events/core.c (ffffffff812061ac)
Location: kernel/events/internal.h:177
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
In kernel/events/ring_buffer.c (ffffffff8120fe17)
Location: kernel/events/internal.h:177
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
In kernel/events/core.c (ffffffff811f8f2c)
Location: kernel/events/internal.h:177
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
In kernel/events/ring_buffer.c (ffffffff81202ba7)
Location: kernel/events/internal.h:177
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
In kernel/events/core.c (ffffffff81203f7c)
Location: kernel/events/internal.h:177
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
In kernel/events/ring_buffer.c (ffffffff8120dbb7)
Location: kernel/events/internal.h:177
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
In kernel/events/core.c (ffffffff81213bac)
Location: kernel/events/internal.h:177
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
In kernel/events/ring_buffer.c (ffffffff8121ca67)
Location: kernel/events/internal.h:177
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_copy
```
</details>
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
<b>Arch</b>
<ul>
</ul>
