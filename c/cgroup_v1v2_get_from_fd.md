# Function: <code>cgroup_v1v2_get_from_fd</code>

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
struct cgroup *cgroup_v1v2_get_from_fd(int fd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81210a75)
Location: kernel/cgroup/cgroup.c:6856
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
Direct callers:
  - kernel/bpf/cgroup_iter.c:bpf_iter_attach_cgroup
```
**Symbols:**

```
ffffffff81210b80-ffffffff81210bd1: cgroup_v1v2_get_from_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct cgroup *cgroup_v1v2_get_from_fd(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff812264c0)
Location: kernel/cgroup/cgroup.c:6839
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/bpf/cgroup_iter.c:bpf_iter_attach_cgroup
```
**Symbols:**

```
ffffffff812264c0-ffffffff8122653d: cgroup_v1v2_get_from_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct cgroup *cgroup_v1v2_get_from_fd(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8123e150)
Location: kernel/cgroup/cgroup.c:6880
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/bpf/cgroup_iter.c:bpf_iter_attach_cgroup
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_delete_elem
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_update_elem
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_lookup_elem
```
**Symbols:**

```
ffffffff8123e150-ffffffff8123e1cd: cgroup_v1v2_get_from_fd (STB_GLOBAL)
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
