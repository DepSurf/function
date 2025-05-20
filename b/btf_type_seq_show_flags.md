# Function: <code>btf_type_seq_show_flags</code>

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
int btf_type_seq_show_flags(const struct btf *btf, u32 type_id, void *obj, struct seq_file *m, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8122c760)
Location: kernel/bpf/btf.c:5504
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_seq_printf_btf
  - kernel/bpf/btf.c:btf_type_seq_show
```
**Symbols:**

```
ffffffff8122c760-ffffffff8122c7c0: btf_type_seq_show_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int btf_type_seq_show_flags(const struct btf *btf, u32 type_id, void *obj, struct seq_file *m, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81231520)
Location: kernel/bpf/btf.c:5697
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_seq_printf_btf
  - kernel/bpf/btf.c:btf_type_seq_show
```
**Symbols:**

```
ffffffff81231520-ffffffff81231580: btf_type_seq_show_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int btf_type_seq_show_flags(const struct btf *btf, u32 type_id, void *obj, struct seq_file *m, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8126a4b0)
Location: kernel/bpf/btf.c:5750
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_seq_printf_btf
  - kernel/bpf/btf.c:btf_type_seq_show
```
**Symbols:**

```
ffffffff8126a4b0-ffffffff8126a510: btf_type_seq_show_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int btf_type_seq_show_flags(const struct btf *btf, u32 type_id, void *obj, struct seq_file *m, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812b7270)
Location: kernel/bpf/btf.c:6483
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_seq_printf_btf
  - kernel/bpf/btf.c:btf_type_seq_show
```
**Symbols:**

```
ffffffff812b7270-ffffffff812b72ff: btf_type_seq_show_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int btf_type_seq_show_flags(const struct btf *btf, u32 type_id, void *obj, struct seq_file *m, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff813187c0)
Location: kernel/bpf/btf.c:6974
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_seq_printf_btf
  - kernel/bpf/btf.c:btf_type_seq_show
```
**Symbols:**

```
ffffffff813187c0-ffffffff81318909: btf_type_seq_show_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int btf_type_seq_show_flags(const struct btf *btf, u32 type_id, void *obj, struct seq_file *m, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81348770)
Location: kernel/bpf/btf.c:7076
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_seq_printf_btf
  - kernel/bpf/btf.c:btf_type_seq_show
```
**Symbols:**

```
ffffffff81348770-ffffffff813487ff: btf_type_seq_show_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int btf_type_seq_show_flags(const struct btf *btf, u32 type_id, void *obj, struct seq_file *m, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8136eea0)
Location: kernel/bpf/btf.c:7140
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_seq_printf_btf
  - kernel/bpf/btf.c:btf_type_seq_show
```
**Symbols:**

```
ffffffff8136eea0-ffffffff8136ef2f: btf_type_seq_show_flags (STB_GLOBAL)
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
