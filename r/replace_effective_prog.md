# Function: <code>replace_effective_prog</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void replace_effective_prog(struct cgroup *cgrp, enum bpf_attach_type type, struct bpf_cgroup_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8122cd10)
Location: kernel/bpf/cgroup.c:509
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_replace
```
**Symbols:**

```
ffffffff8122cd10-ffffffff8122ce05: replace_effective_prog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void replace_effective_prog(struct cgroup *cgrp, enum bpf_attach_type type, struct bpf_cgroup_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff812351c0)
Location: kernel/bpf/cgroup.c:522
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_replace
```
**Symbols:**

```
ffffffff812351c0-ffffffff812352cf: replace_effective_prog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff812389ee)
Location: kernel/bpf/cgroup.c:522
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_replace
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81273043)
Location: kernel/bpf/cgroup.c:529
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_replace
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff812c294d)
Location: kernel/bpf/cgroup.c:582
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_replace
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8132711a)
Location: kernel/bpf/cgroup.c:741
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_replace
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81357451)
Location: kernel/bpf/cgroup.c:741
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_replace
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8137ff81)
Location: kernel/bpf/cgroup.c:741
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_replace
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
