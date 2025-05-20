# Function: <code>cgroup_attach_permissions</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81177ff9)
Location: kernel/cgroup/cgroup.c:4710
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81174d18)
Location: kernel/cgroup/cgroup.c:4711
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_threads_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
  - kernel/cgroup/cgroup.c:cgroup_procs_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int cgroup_attach_permissions(struct cgroup *src_cgrp, struct cgroup *dst_cgrp, struct super_block *sb, bool threadgroup);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116cee0)
Location: kernel/cgroup/cgroup.c:4724
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
```
**Symbols:**

```
ffffffff8116cee0-ffffffff8116d06f: cgroup_attach_permissions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int cgroup_attach_permissions(struct cgroup *src_cgrp, struct cgroup *dst_cgrp, struct super_block *sb, bool threadgroup, struct cgroup_namespace *ns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81192bd0)
Location: kernel/cgroup/cgroup.c:4896
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
```
**Symbols:**

```
ffffffff81192bd0-ffffffff81192d4b: cgroup_attach_permissions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int cgroup_attach_permissions(struct cgroup *src_cgrp, struct cgroup *dst_cgrp, struct super_block *sb, bool threadgroup, struct cgroup_namespace *ns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811c3450)
Location: kernel/cgroup/cgroup.c:4907
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
```
**Symbols:**

```
ffffffff811c3450-ffffffff811c35e1: cgroup_attach_permissions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int cgroup_attach_permissions(struct cgroup *src_cgrp, struct cgroup *dst_cgrp, struct super_block *sb, bool threadgroup, struct cgroup_namespace *ns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81205510)
Location: kernel/cgroup/cgroup.c:5104
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
```
**Symbols:**

```
ffffffff81205510-ffffffff812056d8: cgroup_attach_permissions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int cgroup_attach_permissions(struct cgroup *src_cgrp, struct cgroup *dst_cgrp, struct super_block *sb, bool threadgroup, struct cgroup_namespace *ns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8121ad20)
Location: kernel/cgroup/cgroup.c:5081
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
```
**Symbols:**

```
ffffffff8121ad20-ffffffff8121aeee: cgroup_attach_permissions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int cgroup_attach_permissions(struct cgroup *src_cgrp, struct cgroup *dst_cgrp, struct super_block *sb, bool threadgroup, struct cgroup_namespace *ns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81232a90)
Location: kernel/cgroup/cgroup.c:5117
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
```
**Symbols:**

```
ffffffff81232a90-ffffffff81232c5e: cgroup_attach_permissions (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct cgroup_namespace *ns</code>
</li>
</ul>
</details>
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
