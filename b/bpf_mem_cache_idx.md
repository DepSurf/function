# Function: <code>bpf_mem_cache_idx</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/memalloc.c (ffffffff8131c771)
Location: kernel/bpf/memalloc.c:66
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:bpf_mem_free
  - kernel/bpf/memalloc.c:bpf_mem_alloc
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
In kernel/bpf/memalloc.c (ffffffff8134c271)
Location: kernel/bpf/memalloc.c:66
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:bpf_mem_free
  - kernel/bpf/memalloc.c:bpf_mem_alloc
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
In kernel/bpf/memalloc.c (ffffffff813737ad)
Location: kernel/bpf/memalloc.c:66
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:bpf_mem_free_rcu
  - kernel/bpf/memalloc.c:bpf_mem_free_rcu
  - kernel/bpf/memalloc.c:bpf_mem_free
  - kernel/bpf/memalloc.c:bpf_mem_free
  - kernel/bpf/memalloc.c:bpf_mem_alloc
  - kernel/bpf/memalloc.c:bpf_mem_alloc
  - kernel/bpf/memalloc.c:bpf_mem_alloc_percpu_unit_init
  - kernel/bpf/memalloc.c:bpf_mem_alloc_percpu_unit_init
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
