# Function: <code>bpf_register_map_type</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void bpf_register_map_type(struct bpf_map_type_list *tl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81172e50)
Location: kernel/bpf/syscall.c:44
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:register_htab_map
  - kernel/bpf/arraymap.c:register_array_map
  - kernel/bpf/arraymap.c:register_prog_array_map
  - kernel/bpf/arraymap.c:register_perf_event_array_map
```
**Symbols:**

```
ffffffff81172e50-ffffffff81172e78: bpf_register_map_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void bpf_register_map_type(struct bpf_map_type_list *tl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81180d30)
Location: kernel/bpf/syscall.c:46
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:register_htab_map
  - kernel/bpf/hashtab.c:register_htab_map
  - kernel/bpf/arraymap.c:register_cgroup_array_map
  - kernel/bpf/arraymap.c:register_perf_event_array_map
  - kernel/bpf/arraymap.c:register_prog_array_map
  - kernel/bpf/arraymap.c:register_array_map
  - kernel/bpf/arraymap.c:register_array_map
  - kernel/bpf/stackmap.c:register_stack_map
```
**Symbols:**

```
ffffffff81180d30-ffffffff81180d58: bpf_register_map_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void bpf_register_map_type(struct bpf_map_type_list *tl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8118cd50)
Location: kernel/bpf/syscall.c:50
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:register_htab_map
  - kernel/bpf/hashtab.c:register_htab_map
  - kernel/bpf/hashtab.c:register_htab_map
  - kernel/bpf/hashtab.c:register_htab_map
  - kernel/bpf/arraymap.c:register_cgroup_array_map
  - kernel/bpf/arraymap.c:register_perf_event_array_map
  - kernel/bpf/arraymap.c:register_prog_array_map
  - kernel/bpf/arraymap.c:register_array_map
  - kernel/bpf/arraymap.c:register_array_map
  - kernel/bpf/stackmap.c:register_stack_map
```
**Symbols:**

```
ffffffff8118cd50-ffffffff8118cd78: bpf_register_map_type (STB_GLOBAL)
```
</details>
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
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
