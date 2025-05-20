# Function: <code>bpf_cgroup_atype_find</code>

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
enum cgroup_bpf_attach_type bpf_cgroup_atype_find(enum bpf_attach_type attach_type, u32 attach_btf_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81326d30)
Location: kernel/bpf/cgroup.c:138
Inline: True
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_replace
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
```
**Symbols:**

```
ffffffff81326d30-ffffffff81326e1d: bpf_cgroup_atype_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
enum cgroup_bpf_attach_type bpf_cgroup_atype_find(enum bpf_attach_type attach_type, u32 attach_btf_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81357080)
Location: kernel/bpf/cgroup.c:138
Inline: True
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_replace
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
```
**Symbols:**

```
ffffffff81357080-ffffffff8135716d: bpf_cgroup_atype_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
enum cgroup_bpf_attach_type bpf_cgroup_atype_find(enum bpf_attach_type attach_type, u32 attach_btf_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8137fbb0)
Location: kernel/bpf/cgroup.c:138
Inline: True
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_replace
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
```
**Symbols:**

```
ffffffff8137fbb0-ffffffff8137fc9d: bpf_cgroup_atype_find (STB_LOCAL)
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
