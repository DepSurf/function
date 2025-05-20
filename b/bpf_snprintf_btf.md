# Function: <code>bpf_snprintf_btf</code>

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
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 bpf_snprintf_btf(u64 str, u64 str_size, u64 ptr, u64 btf_ptr_size, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e6c30)
Location: kernel/trace/bpf_trace.c:1244
Inline: False
```
**Symbols:**

```
ffffffff811e6c30-ffffffff811e6cf9: bpf_snprintf_btf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 bpf_snprintf_btf(u64 str, u64 str_size, u64 ptr, u64 btf_ptr_size, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e7ed0)
Location: kernel/trace/bpf_trace.c:925
Inline: False
```
**Symbols:**

```
ffffffff811e7ed0-ffffffff811e7f99: bpf_snprintf_btf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 bpf_snprintf_btf(u64 str, u64 str_size, u64 ptr, u64 btf_ptr_size, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81218b50)
Location: kernel/trace/bpf_trace.c:940
Inline: False
```
**Symbols:**

```
ffffffff81218b50-ffffffff81218c19: bpf_snprintf_btf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 bpf_snprintf_btf(u64 str, u64 str_size, u64 ptr, u64 btf_ptr_size, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81256ee0)
Location: kernel/trace/bpf_trace.c:990
Inline: False
```
**Symbols:**

```
ffffffff81256ee0-ffffffff81256ff9: bpf_snprintf_btf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 bpf_snprintf_btf(u64 str, u64 str_size, u64 ptr, u64 btf_ptr_size, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812a61a0)
Location: kernel/trace/bpf_trace.c:999
Inline: False
```
**Symbols:**

```
ffffffff812a61a0-ffffffff812a62b9: bpf_snprintf_btf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 bpf_snprintf_btf(u64 str, u64 str_size, u64 ptr, u64 btf_ptr_size, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812c83b0)
Location: kernel/trace/bpf_trace.c:1012
Inline: False
```
**Symbols:**

```
ffffffff812c83b0-ffffffff812c84b8: bpf_snprintf_btf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 bpf_snprintf_btf(u64 str, u64 str_size, u64 ptr, u64 btf_ptr_size, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812e4e40)
Location: kernel/trace/bpf_trace.c:1012
Inline: False
```
**Symbols:**

```
ffffffff812e4e40-ffffffff812e4f48: bpf_snprintf_btf (STB_GLOBAL)
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
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
