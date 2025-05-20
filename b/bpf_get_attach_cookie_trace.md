# Function: <code>bpf_get_attach_cookie_trace</code>

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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 bpf_get_attach_cookie_trace(u64 ctx, u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81217e30)
Location: kernel/trace/bpf_trace.c:993
Inline: False
```
**Symbols:**

```
ffffffff81217e30-ffffffff81217e44: bpf_get_attach_cookie_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
u64 bpf_get_attach_cookie_trace(u64 ctx, u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81255c70)
Location: kernel/trace/bpf_trace.c:1067
Inline: True
```
**Symbols:**

```
ffffffff81255c70-ffffffff81255c88: bpf_get_attach_cookie_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
u64 bpf_get_attach_cookie_trace(u64 ctx, u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812a51d0)
Location: kernel/trace/bpf_trace.c:1095
Inline: True
```
**Symbols:**

```
ffffffff812a51d0-ffffffff812a51e8: bpf_get_attach_cookie_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
u64 bpf_get_attach_cookie_trace(u64 ctx, u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812c7680)
Location: kernel/trace/bpf_trace.c:1108
Inline: True
```
**Symbols:**

```
ffffffff812c7680-ffffffff812c7698: bpf_get_attach_cookie_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
u64 bpf_get_attach_cookie_trace(u64 ctx, u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812e4000)
Location: kernel/trace/bpf_trace.c:1141
Inline: True
```
**Symbols:**

```
ffffffff812e4000-ffffffff812e4018: bpf_get_attach_cookie_trace (STB_GLOBAL)
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
