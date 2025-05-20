# Function: <code>btf_record_free</code>

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
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void btf_record_free(struct btf_record *rec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812c9320)
Location: kernel/bpf/syscall.c:522
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:map_check_btf
  - kernel/bpf/syscall.c:bpf_map_free_deferred
  - kernel/bpf/syscall.c:btf_record_dup
  - kernel/bpf/map_in_map.c:bpf_map_meta_alloc
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_parse_fields
  - kernel/bpf/btf.c:btf_parse_fields
  - kernel/bpf/btf.c:btf_free
```
**Symbols:**

```
ffffffff812c9320-ffffffff812c93d0: btf_record_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void btf_record_free(struct btf_record *rec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812f0a40)
Location: kernel/bpf/syscall.c:505
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:map_check_btf
  - kernel/bpf/syscall.c:bpf_map_free_deferred
  - kernel/bpf/syscall.c:btf_record_dup
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_parse_fields
  - kernel/bpf/btf.c:btf_free
```
**Symbols:**

```
ffffffff812f0a40-ffffffff812f0b2b: btf_record_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void btf_record_free(struct btf_record *rec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8130f820)
Location: kernel/bpf/syscall.c:506
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:map_check_btf
  - kernel/bpf/syscall.c:bpf_map_free_deferred
  - kernel/bpf/syscall.c:btf_record_dup
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_parse_fields
  - kernel/bpf/btf.c:btf_free
```
**Symbols:**

```
ffffffff8130f820-ffffffff8130f917: btf_record_free (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
