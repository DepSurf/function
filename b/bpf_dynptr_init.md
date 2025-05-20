# Function: <code>bpf_dynptr_init</code>

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
void bpf_dynptr_init(struct bpf_dynptr_kern *ptr, void *data, enum bpf_dynptr_type type, u32 offset, u32 size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff8129848e)
Location: kernel/bpf/helpers.c:1443
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_dynptr_from_mem
Direct callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_reserve_dynptr
```
**Symbols:**

```
ffffffff81298400-ffffffff81298429: bpf_dynptr_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void bpf_dynptr_init(struct bpf_dynptr_kern *ptr, void *data, enum bpf_dynptr_type type, u32 offset, u32 size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff812f36be)
Location: kernel/bpf/helpers.c:1427
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_dynptr_from_mem
Direct callers:
  - kernel/bpf/ringbuf.c:bpf_user_ringbuf_drain
  - kernel/bpf/ringbuf.c:bpf_ringbuf_reserve_dynptr
```
**Symbols:**

```
ffffffff812f3610-ffffffff812f3639: bpf_dynptr_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void bpf_dynptr_init(struct bpf_dynptr_kern *ptr, void *data, enum bpf_dynptr_type type, u32 offset, u32 size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff8132057e)
Location: kernel/bpf/helpers.c:1463
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_dynptr_from_mem
Direct callers:
  - kernel/bpf/ringbuf.c:bpf_user_ringbuf_drain
  - kernel/bpf/ringbuf.c:bpf_ringbuf_reserve_dynptr
  - net/core/filter.c:bpf_dynptr_from_xdp
  - net/core/filter.c:bpf_dynptr_from_skb
```
**Symbols:**

```
ffffffff813204d0-ffffffff813204f9: bpf_dynptr_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void bpf_dynptr_init(struct bpf_dynptr_kern *ptr, void *data, enum bpf_dynptr_type type, u32 offset, u32 size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff81342a7e)
Location: kernel/bpf/helpers.c:1482
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_dynptr_from_mem
Direct callers:
  - kernel/bpf/ringbuf.c:bpf_user_ringbuf_drain
  - kernel/bpf/ringbuf.c:bpf_ringbuf_reserve_dynptr
  - net/core/filter.c:bpf_dynptr_from_xdp
  - net/core/filter.c:bpf_dynptr_from_skb
```
**Symbols:**

```
ffffffff813429d0-ffffffff813429f9: bpf_dynptr_init (STB_GLOBAL)
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
