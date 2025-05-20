# Function: <code>bpf_ringbuf_area_alloc</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct bpf_ringbuf *bpf_ringbuf_area_alloc(size_t data_sz, int numa_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/ringbuf.c (ffffffff8121e2d0)
Location: kernel/bpf/ringbuf.c:61
Inline: False
```
**Symbols:**

```
ffffffff8121e2d0-ffffffff8121e407: bpf_ringbuf_area_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct bpf_ringbuf *bpf_ringbuf_area_alloc(size_t data_sz, int numa_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/ringbuf.c (ffffffff81221070)
Location: kernel/bpf/ringbuf.c:60
Inline: False
```
**Symbols:**

```
ffffffff81221070-ffffffff81221186: bpf_ringbuf_area_alloc (STB_LOCAL)
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
In kernel/bpf/ringbuf.c (ffffffff81224b35)
Location: kernel/bpf/ringbuf.c:61
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
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
In kernel/bpf/ringbuf.c (ffffffff8125ca75)
Location: kernel/bpf/ringbuf.c:61
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
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
In kernel/bpf/ringbuf.c (ffffffff812a68f4)
Location: kernel/bpf/ringbuf.c:62
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
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
In kernel/bpf/ringbuf.c (ffffffff81304db4)
Location: kernel/bpf/ringbuf.c:95
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
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
In kernel/bpf/ringbuf.c (ffffffff81333744)
Location: kernel/bpf/ringbuf.c:96
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
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
In kernel/bpf/ringbuf.c (ffffffff81357e34)
Location: kernel/bpf/ringbuf.c:87
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
