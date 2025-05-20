# Function: <code>__llist_add_batch</code>

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
In kernel/kprobes.c (ffffffff81193493)
Location: include/linux/llist.h:201
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
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
In kernel/kprobes.c (ffffffff81194443)
Location: include/linux/llist.h:201
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
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
In kernel/kprobes.c (ffffffff811bd2e3)
Location: include/linux/llist.h:201
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
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
In kernel/trace/rethook.c (ffffffff81268d3d)
Location: include/linux/llist.h:203
Inline: True
Inline callers:
  - kernel/trace/rethook.c:rethook_hook
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
In kernel/trace/rethook.c (ffffffff812bb00d)
Location: include/linux/llist.h:203
Inline: True
Inline callers:
  - kernel/trace/rethook.c:rethook_hook
```
```
In kernel/bpf/memalloc.c (ffffffff8131b9bf)
Location: include/linux/llist.h:203
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:unit_free
  - kernel/bpf/memalloc.c:bpf_mem_refill
  - kernel/bpf/memalloc.c:bpf_mem_refill
  - kernel/bpf/memalloc.c:bpf_mem_refill
  - kernel/bpf/memalloc.c:alloc_bulk
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
In kernel/trace/rethook.c (ffffffff812dec0d)
Location: include/linux/llist.h:203
Inline: True
Inline callers:
  - kernel/trace/rethook.c:rethook_hook
```
```
In kernel/bpf/memalloc.c (ffffffff8134b3ff)
Location: include/linux/llist.h:203
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:unit_free
  - kernel/bpf/memalloc.c:bpf_mem_refill
  - kernel/bpf/memalloc.c:bpf_mem_refill
  - kernel/bpf/memalloc.c:bpf_mem_refill
  - kernel/bpf/memalloc.c:alloc_bulk
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
In kernel/trace/rethook.c (ffffffff812fcd1d)
Location: include/linux/llist.h:230
Inline: True
Inline callers:
  - kernel/trace/rethook.c:rethook_hook
```
```
In kernel/bpf/memalloc.c (ffffffff81371dc7)
Location: include/linux/llist.h:230
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:unit_free_rcu
  - kernel/bpf/memalloc.c:unit_free
  - kernel/bpf/memalloc.c:bpf_mem_refill
  - kernel/bpf/memalloc.c:alloc_bulk
  - kernel/bpf/memalloc.c:alloc_bulk
  - kernel/bpf/memalloc.c:alloc_bulk
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
