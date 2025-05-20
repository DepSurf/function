# Function: <code>bpf_dynptr_set_null</code>

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
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void bpf_dynptr_set_null(struct bpf_dynptr_kern *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff81298430)
Location: kernel/bpf/helpers.c:1452
Inline: True
Direct callers:
  - kernel/bpf/helpers.c:bpf_dynptr_from_mem
  - kernel/bpf/ringbuf.c:bpf_ringbuf_discard_dynptr
  - kernel/bpf/ringbuf.c:bpf_ringbuf_discard_dynptr
  - kernel/bpf/ringbuf.c:bpf_ringbuf_submit_dynptr
  - kernel/bpf/ringbuf.c:bpf_ringbuf_submit_dynptr
  - kernel/bpf/ringbuf.c:bpf_ringbuf_reserve_dynptr
  - kernel/bpf/ringbuf.c:bpf_ringbuf_reserve_dynptr
```
**Symbols:**

```
ffffffff81298430-ffffffff81298450: bpf_dynptr_set_null (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bpf_dynptr_set_null(struct bpf_dynptr_kern *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff812f3650)
Location: kernel/bpf/helpers.c:1436
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:bpf_dynptr_from_mem
  - kernel/bpf/ringbuf.c:bpf_ringbuf_discard_dynptr
  - kernel/bpf/ringbuf.c:bpf_ringbuf_discard_dynptr
  - kernel/bpf/ringbuf.c:bpf_ringbuf_submit_dynptr
  - kernel/bpf/ringbuf.c:bpf_ringbuf_submit_dynptr
  - kernel/bpf/ringbuf.c:bpf_ringbuf_reserve_dynptr
  - kernel/bpf/ringbuf.c:bpf_ringbuf_reserve_dynptr
```
**Symbols:**

```
ffffffff812f3650-ffffffff812f3670: bpf_dynptr_set_null (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bpf_dynptr_set_null(struct bpf_dynptr_kern *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff81320510)
Location: kernel/bpf/helpers.c:1472
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:bpf_dynptr_clone
  - kernel/bpf/helpers.c:bpf_dynptr_from_mem
  - kernel/bpf/ringbuf.c:bpf_ringbuf_discard_dynptr
  - kernel/bpf/ringbuf.c:bpf_ringbuf_discard_dynptr
  - kernel/bpf/ringbuf.c:bpf_ringbuf_submit_dynptr
  - kernel/bpf/ringbuf.c:bpf_ringbuf_submit_dynptr
  - kernel/bpf/ringbuf.c:bpf_ringbuf_reserve_dynptr
  - kernel/bpf/ringbuf.c:bpf_ringbuf_reserve_dynptr
  - net/core/filter.c:bpf_dynptr_from_xdp
  - net/core/filter.c:bpf_dynptr_from_skb
```
**Symbols:**

```
ffffffff81320510-ffffffff81320530: bpf_dynptr_set_null (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bpf_dynptr_set_null(struct bpf_dynptr_kern *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff81342a10)
Location: kernel/bpf/helpers.c:1491
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:bpf_dynptr_clone
  - kernel/bpf/helpers.c:bpf_dynptr_from_mem
  - kernel/bpf/ringbuf.c:bpf_ringbuf_discard_dynptr
  - kernel/bpf/ringbuf.c:bpf_ringbuf_discard_dynptr
  - kernel/bpf/ringbuf.c:bpf_ringbuf_submit_dynptr
  - kernel/bpf/ringbuf.c:bpf_ringbuf_submit_dynptr
  - kernel/bpf/ringbuf.c:bpf_ringbuf_reserve_dynptr
  - kernel/bpf/ringbuf.c:bpf_ringbuf_reserve_dynptr
  - net/core/filter.c:bpf_dynptr_from_xdp
  - net/core/filter.c:bpf_dynptr_from_skb
```
**Symbols:**

```
ffffffff81342a10-ffffffff81342a30: bpf_dynptr_set_null (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
