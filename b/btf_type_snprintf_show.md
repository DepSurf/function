# Function: <code>btf_type_snprintf_show</code>

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
int btf_type_snprintf_show(const struct btf *btf, u32 type_id, void *obj, char *buf, int len, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8122c7e0)
Location: kernel/bpf/btf.c:5554
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_snprintf_btf
```
**Symbols:**

```
ffffffff8122c7e0-ffffffff8122c851: btf_type_snprintf_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int btf_type_snprintf_show(const struct btf *btf, u32 type_id, void *obj, char *buf, int len, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812315a0)
Location: kernel/bpf/btf.c:5747
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_snprintf_btf
```
**Symbols:**

```
ffffffff812315a0-ffffffff81231611: btf_type_snprintf_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int btf_type_snprintf_show(const struct btf *btf, u32 type_id, void *obj, char *buf, int len, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8126a530)
Location: kernel/bpf/btf.c:5800
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_snprintf_btf
```
**Symbols:**

```
ffffffff8126a530-ffffffff8126a5a1: btf_type_snprintf_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int btf_type_snprintf_show(const struct btf *btf, u32 type_id, void *obj, char *buf, int len, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812b7330)
Location: kernel/bpf/btf.c:6533
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_snprintf_btf
```
**Symbols:**

```
ffffffff812b7330-ffffffff812b73cf: btf_type_snprintf_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int btf_type_snprintf_show(const struct btf *btf, u32 type_id, void *obj, char *buf, int len, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81318960)
Location: kernel/bpf/btf.c:7024
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_snprintf_btf
```
**Symbols:**

```
ffffffff81318960-ffffffff81318ac4: btf_type_snprintf_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int btf_type_snprintf_show(const struct btf *btf, u32 type_id, void *obj, char *buf, int len, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81348850)
Location: kernel/bpf/btf.c:7126
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_snprintf_btf
```
**Symbols:**

```
ffffffff81348850-ffffffff813488ef: btf_type_snprintf_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int btf_type_snprintf_show(const struct btf *btf, u32 type_id, void *obj, char *buf, int len, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8136ef80)
Location: kernel/bpf/btf.c:7190
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_snprintf_btf
```
**Symbols:**

```
ffffffff8136ef80-ffffffff8136f01f: btf_type_snprintf_show (STB_GLOBAL)
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
