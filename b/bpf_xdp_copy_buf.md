# Function: <code>bpf_xdp_copy_buf</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
void bpf_xdp_copy_buf(struct xdp_buff *xdp, long unsigned int off, void *buf, long unsigned int len, bool flush);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81c3c6e0)
Location: net/core/filter.c:3847
Inline: False
Direct callers:
  - net/core/filter.c:bpf_xdp_copy
  - net/core/filter.c:bpf_xdp_store_bytes
  - net/core/filter.c:bpf_xdp_load_bytes
```
**Symbols:**

```
ffffffff81c3c6e0-ffffffff81c3c813: bpf_xdp_copy_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bpf_xdp_copy_buf(struct xdp_buff *xdp, long unsigned int off, void *buf, long unsigned int len, bool flush);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81df4350)
Location: net/core/filter.c:3857
Inline: False
Direct callers:
  - net/core/filter.c:bpf_xdp_copy
  - net/core/filter.c:bpf_xdp_store_bytes
  - net/core/filter.c:bpf_xdp_load_bytes
```
**Symbols:**

```
ffffffff81df4350-ffffffff81df4470: bpf_xdp_copy_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bpf_xdp_copy_buf(struct xdp_buff *xdp, long unsigned int off, void *buf, long unsigned int len, bool flush);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e73490)
Location: net/core/filter.c:3902
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:bpf_dynptr_slice
  - net/core/filter.c:bpf_xdp_copy
  - net/core/filter.c:__bpf_xdp_store_bytes
  - net/core/filter.c:bpf_xdp_store_bytes
  - net/core/filter.c:__bpf_xdp_load_bytes
  - net/core/filter.c:bpf_xdp_load_bytes
```
**Symbols:**

```
ffffffff81e73490-ffffffff81e735fe: bpf_xdp_copy_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bpf_xdp_copy_buf(struct xdp_buff *xdp, long unsigned int off, void *buf, long unsigned int len, bool flush);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f32c50)
Location: net/core/filter.c:3936
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:bpf_dynptr_slice
  - net/core/filter.c:bpf_xdp_copy
  - net/core/filter.c:__bpf_xdp_store_bytes
  - net/core/filter.c:bpf_xdp_store_bytes
  - net/core/filter.c:__bpf_xdp_load_bytes
  - net/core/filter.c:bpf_xdp_load_bytes
```
**Symbols:**

```
ffffffff81f32c50-ffffffff81f32dbe: bpf_xdp_copy_buf (STB_GLOBAL)
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
