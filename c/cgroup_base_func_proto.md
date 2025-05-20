# Function: <code>cgroup_base_func_proto</code>

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
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811f7c30)
Location: kernel/bpf/cgroup.c:776
Inline: True
Direct callers:
  - kernel/bpf/cgroup.c:cg_sockopt_func_proto
  - kernel/bpf/cgroup.c:sysctl_func_proto
  - kernel/bpf/cgroup.c:cgroup_dev_func_proto
```
**Symbols:**

```
ffffffff811f7c30-ffffffff811f7cf4: cgroup_base_func_proto.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81204bd0)
Location: kernel/bpf/cgroup.c:786
Inline: True
Direct callers:
  - kernel/bpf/cgroup.c:cg_sockopt_func_proto
  - kernel/bpf/cgroup.c:sysctl_func_proto
  - kernel/bpf/cgroup.c:cgroup_dev_func_proto
```
**Symbols:**

```
ffffffff81204bd0-ffffffff81204c94: cgroup_base_func_proto.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8122ca79)
Location: kernel/bpf/cgroup.c:1122
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cg_sockopt_func_proto
  - kernel/bpf/cgroup.c:sysctl_func_proto
  - kernel/bpf/cgroup.c:cgroup_dev_func_proto
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
In kernel/bpf/cgroup.c (ffffffff81234ef9)
Location: kernel/bpf/cgroup.c:1146
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cg_sockopt_func_proto
  - kernel/bpf/cgroup.c:sysctl_func_proto
  - kernel/bpf/cgroup.c:cgroup_dev_func_proto
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
In kernel/bpf/cgroup.c (ffffffff81238879)
Location: kernel/bpf/cgroup.c:1150
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cg_sockopt_func_proto
  - kernel/bpf/cgroup.c:sysctl_func_proto
  - kernel/bpf/cgroup.c:cgroup_dev_func_proto
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
In kernel/bpf/cgroup.c (ffffffff81273e4e)
Location: kernel/bpf/cgroup.c:1180
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cg_sockopt_func_proto
  - kernel/bpf/cgroup.c:sysctl_func_proto
  - kernel/bpf/cgroup.c:cgroup_dev_func_proto
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
In kernel/bpf/cgroup.c (ffffffff812c3ac3)
Location: kernel/bpf/cgroup.c:1357
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cg_sockopt_func_proto
  - kernel/bpf/cgroup.c:sysctl_func_proto
  - kernel/bpf/cgroup.c:cgroup_dev_func_proto
```
</details>
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
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/cgroup.c (ffff80001028d130)
Location: kernel/bpf/cgroup.c:786
Inline: True
Direct callers:
  - kernel/bpf/cgroup.c:cg_sockopt_func_proto
  - kernel/bpf/cgroup.c:sysctl_func_proto
  - kernel/bpf/cgroup.c:cgroup_dev_func_proto
```
**Symbols:**

```
ffff80001028d130-ffff80001028d248: cgroup_base_func_proto.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/cgroup.c (c04bd088)
Location: kernel/bpf/cgroup.c:786
Inline: True
Direct callers:
  - kernel/bpf/cgroup.c:cg_sockopt_func_proto
  - kernel/bpf/cgroup.c:sysctl_func_proto
  - kernel/bpf/cgroup.c:cgroup_dev_func_proto
```
**Symbols:**

```
c04bd088-c04bd1c4: cgroup_base_func_proto.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/cgroup.c (c0000000003397c0)
Location: kernel/bpf/cgroup.c:786
Inline: True
Direct callers:
  - kernel/bpf/cgroup.c:cg_sockopt_func_proto
  - kernel/bpf/cgroup.c:sysctl_func_proto
  - kernel/bpf/cgroup.c:cgroup_dev_func_proto
```
**Symbols:**

```
c0000000003397c0-c00000000033994c: cgroup_base_func_proto.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffe0001c11d8)
Location: kernel/bpf/cgroup.c:786
Inline: True
Direct callers:
  - kernel/bpf/cgroup.c:cg_sockopt_func_proto
  - kernel/bpf/cgroup.c:sysctl_func_proto
  - kernel/bpf/cgroup.c:cgroup_dev_func_proto
```
**Symbols:**

```
ffffffe0001c11d8-ffffffe0001c12d0: cgroup_base_func_proto.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811fd1f0)
Location: kernel/bpf/cgroup.c:786
Inline: True
Direct callers:
  - kernel/bpf/cgroup.c:cg_sockopt_func_proto
  - kernel/bpf/cgroup.c:sysctl_func_proto
  - kernel/bpf/cgroup.c:cgroup_dev_func_proto
```
**Symbols:**

```
ffffffff811fd1f0-ffffffff811fd2b4: cgroup_base_func_proto.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811eff40)
Location: kernel/bpf/cgroup.c:786
Inline: True
Direct callers:
  - kernel/bpf/cgroup.c:cg_sockopt_func_proto
  - kernel/bpf/cgroup.c:sysctl_func_proto
  - kernel/bpf/cgroup.c:cgroup_dev_func_proto
```
**Symbols:**

```
ffffffff811eff40-ffffffff811f0004: cgroup_base_func_proto.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811fafc0)
Location: kernel/bpf/cgroup.c:786
Inline: True
Direct callers:
  - kernel/bpf/cgroup.c:cg_sockopt_func_proto
  - kernel/bpf/cgroup.c:sysctl_func_proto
  - kernel/bpf/cgroup.c:cgroup_dev_func_proto
```
**Symbols:**

```
ffffffff811fafc0-ffffffff811fb084: cgroup_base_func_proto.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81209b30)
Location: kernel/bpf/cgroup.c:786
Inline: True
Direct callers:
  - kernel/bpf/cgroup.c:cg_sockopt_func_proto
  - kernel/bpf/cgroup.c:sysctl_func_proto
  - kernel/bpf/cgroup.c:cgroup_dev_func_proto
```
**Symbols:**

```
ffffffff81209b30-ffffffff81209bf4: cgroup_base_func_proto.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
