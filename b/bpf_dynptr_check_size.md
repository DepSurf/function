# Function: <code>bpf_dynptr_check_size</code>

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
int bpf_dynptr_check_size(u32 size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff81298459)
Location: kernel/bpf/helpers.c:1438
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_dynptr_from_mem
Direct callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_reserve_dynptr
```
**Symbols:**

```
ffffffff812983e0-ffffffff812983fe: bpf_dynptr_check_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int bpf_dynptr_check_size(u32 size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff812f3689)
Location: kernel/bpf/helpers.c:1422
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_dynptr_from_mem
Direct callers:
  - kernel/bpf/ringbuf.c:bpf_user_ringbuf_drain
  - kernel/bpf/ringbuf.c:bpf_ringbuf_reserve_dynptr
```
**Symbols:**

```
ffffffff812f35e0-ffffffff812f35fe: bpf_dynptr_check_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int bpf_dynptr_check_size(u32 size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff81320549)
Location: kernel/bpf/helpers.c:1458
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_dynptr_from_mem
Direct callers:
  - kernel/bpf/ringbuf.c:bpf_user_ringbuf_drain
  - kernel/bpf/ringbuf.c:bpf_ringbuf_reserve_dynptr
```
**Symbols:**

```
ffffffff813204a0-ffffffff813204be: bpf_dynptr_check_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int bpf_dynptr_check_size(u32 size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff81342a49)
Location: kernel/bpf/helpers.c:1477
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_dynptr_from_mem
Direct callers:
  - kernel/bpf/ringbuf.c:bpf_user_ringbuf_drain
  - kernel/bpf/ringbuf.c:bpf_ringbuf_reserve_dynptr
```
**Symbols:**

```
ffffffff813429a0-ffffffff813429be: bpf_dynptr_check_size (STB_GLOBAL)
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
