# Function: <code>tracing_resize_ring_buffer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8114c767)
Location: kernel/trace/trace.c:4286
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_entries_write
  - kernel/trace/trace.c:tracing_free_buffer_release
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811561ad)
Location: kernel/trace/trace.c:4683
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_entries_write
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
In kernel/trace/trace.c (ffffffff8116096d)
Location: kernel/trace/trace.c:4932
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_entries_write
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
In kernel/trace/trace.c (ffffffff81163f9d)
Location: kernel/trace/trace.c:5249
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_entries_write
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
In kernel/trace/trace.c (ffffffff81170efd)
Location: kernel/trace/trace.c:5253
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_entries_write
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
In kernel/trace/trace.c (ffffffff8118007d)
Location: kernel/trace/trace.c:5259
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_entries_write
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
In kernel/trace/trace.c (ffffffff8118d9ed)
Location: kernel/trace/trace.c:5282
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_entries_write
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
In kernel/trace/trace.c (ffffffff8119b473)
Location: kernel/trace/trace.c:5503
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_entries_write
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
In kernel/trace/trace.c (ffffffff811a66d3)
Location: kernel/trace/trace.c:5556
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_entries_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t tracing_resize_ring_buffer(struct trace_array *tr, long unsigned int size, int cpu_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bda55)
Location: kernel/trace/trace.c:5759
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_free_buffer_release
Direct callers:
  - kernel/trace/trace.c:tracing_entries_write
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
**Symbols:**

```
ffffffff811c4320-ffffffff811c4393: tracing_resize_ring_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
ssize_t tracing_resize_ring_buffer(struct trace_array *tr, long unsigned int size, int cpu_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bb675)
Location: kernel/trace/trace.c:5832
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_free_buffer_release
Direct callers:
  - kernel/trace/trace.c:tracing_entries_write
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
**Symbols:**

```
ffffffff811c1f30-ffffffff811c1fa3: tracing_resize_ring_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
ssize_t tracing_resize_ring_buffer(struct trace_array *tr, long unsigned int size, int cpu_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bb225)
Location: kernel/trace/trace.c:6169
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_free_buffer_release
Direct callers:
  - kernel/trace/trace.c:tracing_entries_write
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
**Symbols:**

```
ffffffff811c2fa0-ffffffff811c3013: tracing_resize_ring_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
ssize_t tracing_resize_ring_buffer(struct trace_array *tr, long unsigned int size, int cpu_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811e5b55)
Location: kernel/trace/trace.c:6247
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_free_buffer_release
Direct callers:
  - kernel/trace/trace.c:tracing_entries_write
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
**Symbols:**

```
ffffffff811edca0-ffffffff811edd13: tracing_resize_ring_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
ssize_t tracing_resize_ring_buffer(struct trace_array *tr, long unsigned int size, int cpu_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8121d1d5)
Location: kernel/trace/trace.c:6259
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_free_buffer_release
Direct callers:
  - kernel/trace/trace.c:tracing_entries_write
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
**Symbols:**

```
ffffffff81225eb0-ffffffff81225f27: tracing_resize_ring_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
ssize_t tracing_resize_ring_buffer(struct trace_array *tr, long unsigned int size, int cpu_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff812676d5)
Location: kernel/trace/trace.c:6292
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_free_buffer_release
Direct callers:
  - kernel/trace/trace.c:tracing_entries_write
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
**Symbols:**

```
ffffffff81271140-ffffffff812711b7: tracing_resize_ring_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
ssize_t tracing_resize_ring_buffer(struct trace_array *tr, long unsigned int size, int cpu_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8127e5a5)
Location: kernel/trace/trace.c:6415
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_free_buffer_release
Direct callers:
  - kernel/trace/trace.c:tracing_entries_write
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
**Symbols:**

```
ffffffff81288430-ffffffff812884a7: tracing_resize_ring_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t tracing_resize_ring_buffer(struct trace_array *tr, long unsigned int size, int cpu_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8129bb85)
Location: kernel/trace/trace.c:6428
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_free_buffer_release
Direct callers:
  - kernel/trace/trace.c:tracing_entries_write
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
**Symbols:**

```
ffffffff812a3750-ffffffff812a37ec: tracing_resize_ring_buffer (STB_GLOBAL)
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
In kernel/trace/trace.c (ffff8000102234f0)
Location: kernel/trace/trace.c:5556
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_entries_write
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
In kernel/trace/trace.c (c0460de8)
Location: kernel/trace/trace.c:5556
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_free_buffer_release
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
In kernel/trace/trace.c (c0000000002a7eac)
Location: kernel/trace/trace.c:5556
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_entries_write
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
In kernel/trace/trace.c (ffffffe00017ec38)
Location: kernel/trace/trace.c:5556
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_entries_write
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
In kernel/trace/trace.c (ffffffff8119ecf3)
Location: kernel/trace/trace.c:5556
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_entries_write
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
In kernel/trace/trace.c (ffffffff81191d43)
Location: kernel/trace/trace.c:5556
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_entries_write
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
In kernel/trace/trace.c (ffffffff8119cac3)
Location: kernel/trace/trace.c:5556
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_entries_write
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
In kernel/trace/trace.c (ffffffff811aa763)
Location: kernel/trace/trace.c:5556
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_entries_write
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
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
