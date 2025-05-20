# Function: <code>__llist_del_all</code>

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
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81192e5e)
Location: include/linux/llist.h:240
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_flush_task
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
In kernel/kprobes.c (ffffffff81193cfe)
Location: include/linux/llist.h:240
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_flush_task
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
In kernel/kprobes.c (ffffffff811bcbbe)
Location: include/linux/llist.h:240
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_flush_task
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
In kernel/trace/rethook.c (ffffffff81268fb0)
Location: include/linux/llist.h:242
Inline: True
Inline callers:
  - kernel/trace/rethook.c:rethook_flush_task
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
In kernel/trace/rethook.c (ffffffff812bb2d0)
Location: include/linux/llist.h:242
Inline: True
Inline callers:
  - kernel/trace/rethook.c:rethook_flush_task
```
```
In kernel/bpf/memalloc.c (ffffffff8131bbe5)
Location: include/linux/llist.h:242
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:drain_mem_cache
  - kernel/bpf/memalloc.c:drain_mem_cache
  - kernel/bpf/memalloc.c:drain_mem_cache
  - kernel/bpf/memalloc.c:bpf_mem_refill
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
In kernel/trace/rethook.c (ffffffff812deed0)
Location: include/linux/llist.h:242
Inline: True
Inline callers:
  - kernel/trace/rethook.c:rethook_flush_task
```
```
In kernel/bpf/memalloc.c (ffffffff8134b65b)
Location: include/linux/llist.h:242
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:drain_mem_cache
  - kernel/bpf/memalloc.c:drain_mem_cache
  - kernel/bpf/memalloc.c:drain_mem_cache
  - kernel/bpf/memalloc.c:bpf_mem_refill
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
In kernel/trace/rethook.c (ffffffff812fce40)
Location: include/linux/llist.h:269
Inline: True
Inline callers:
  - kernel/trace/rethook.c:rethook_flush_task
```
```
In kernel/bpf/memalloc.c (ffffffff813725a5)
Location: include/linux/llist.h:269
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:drain_mem_cache
  - kernel/bpf/memalloc.c:drain_mem_cache
  - kernel/bpf/memalloc.c:drain_mem_cache
  - kernel/bpf/memalloc.c:drain_mem_cache
  - kernel/bpf/memalloc.c:bpf_mem_refill
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
