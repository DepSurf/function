# Function: <code>bpf_dynptr_slice</code>

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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void *bpf_dynptr_slice(const struct bpf_dynptr_kern *ptr, u32 offset, void *buffer__opt, u32 buffer__szk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/helpers.c (0)
Location: kernel/bpf/helpers.c:2221
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:bpf_dynptr_slice_rdwr
```
**Symbols:**

```
ffffffff820e097a-ffffffff820e0994: bpf_dynptr_slice.cold (STB_LOCAL)
ffffffff813216b0-ffffffff8132182d: bpf_dynptr_slice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void *bpf_dynptr_slice(const struct bpf_dynptr_kern *ptr, u32 offset, void *buffer__opt, u32 buffer__szk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/helpers.c (0)
Location: kernel/bpf/helpers.c:2317
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:__bpf_dynptr_data_rw
  - kernel/bpf/helpers.c:bpf_dynptr_slice_rdwr
```
**Symbols:**

```
ffffffff821bd073-ffffffff821bd08d: bpf_dynptr_slice.cold (STB_LOCAL)
ffffffff81343e40-ffffffff81343fdb: bpf_dynptr_slice (STB_GLOBAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
