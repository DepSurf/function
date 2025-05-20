# Function: <code>bpf_cgrp_storage_free</code>

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
<summary>In <code>6.2</code>: ✅</summary>

```c
void bpf_cgrp_storage_free(struct cgroup *cgroup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_cgrp_storage.c (ffffffff81325c20)
Location: kernel/bpf/bpf_cgrp_storage.c:46
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
**Symbols:**

```
ffffffff81325c20-ffffffff81325ce1: bpf_cgrp_storage_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bpf_cgrp_storage_free(struct cgroup *cgroup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_cgrp_storage.c (ffffffff81355e70)
Location: kernel/bpf/bpf_cgrp_storage.c:46
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
**Symbols:**

```
ffffffff81355e70-ffffffff81355ebf: bpf_cgrp_storage_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bpf_cgrp_storage_free(struct cgroup *cgroup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_cgrp_storage.c (ffffffff8137e9a0)
Location: kernel/bpf/bpf_cgrp_storage.c:46
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
**Symbols:**

```
ffffffff8137e9a0-ffffffff8137e9ef: bpf_cgrp_storage_free (STB_GLOBAL)
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
