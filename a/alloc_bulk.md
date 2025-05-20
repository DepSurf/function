# Function: <code>alloc_bulk</code>

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
<summary>In <code>6.2</code>: ✅</summary>

```c
void alloc_bulk(struct bpf_mem_cache *c, int cnt, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/memalloc.c (ffffffff8131bd20)
Location: kernel/bpf/memalloc.c:164
Inline: False
Direct callers:
  - kernel/bpf/memalloc.c:prefill_mem_cache
  - kernel/bpf/memalloc.c:prefill_mem_cache
  - kernel/bpf/memalloc.c:bpf_mem_refill
```
**Symbols:**

```
ffffffff8131bd20-ffffffff8131bf0b: alloc_bulk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void alloc_bulk(struct bpf_mem_cache *c, int cnt, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/memalloc.c (ffffffff8134b7d0)
Location: kernel/bpf/memalloc.c:157
Inline: False
Direct callers:
  - kernel/bpf/memalloc.c:prefill_mem_cache
  - kernel/bpf/memalloc.c:prefill_mem_cache
  - kernel/bpf/memalloc.c:bpf_mem_refill
```
**Symbols:**

```
ffffffff8134b7d0-ffffffff8134b9bf: alloc_bulk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void alloc_bulk(struct bpf_mem_cache *c, int cnt, int node, bool atomic);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/memalloc.c (ffffffff81372250)
Location: kernel/bpf/memalloc.c:206
Inline: False
Direct callers:
  - kernel/bpf/memalloc.c:bpf_mem_alloc_percpu_unit_init
  - kernel/bpf/memalloc.c:bpf_mem_alloc_init
  - kernel/bpf/memalloc.c:bpf_mem_alloc_init
  - kernel/bpf/memalloc.c:bpf_mem_refill
```
**Symbols:**

```
ffffffff81372250-ffffffff81372477: alloc_bulk (STB_LOCAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool atomic</code>
</li>
</ul>
</details>
</li>
</ul>
