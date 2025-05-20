# Function: <code>bpf_ctx_narrow_access_offset</code>

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
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811eb700)
Location: include/linux/filter.h:752
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:convert_ctx_accesses
```
```
In kernel/bpf/cgroup.c (0)
Location: include/linux/filter.h:752
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8120a832)
Location: include/linux/filter.h:783
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:convert_ctx_accesses
```
```
In kernel/bpf/cgroup.c (0)
Location: include/linux/filter.h:783
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8120c9ef)
Location: include/linux/filter.h:792
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:convert_ctx_accesses
```
```
In kernel/bpf/cgroup.c (0)
Location: include/linux/filter.h:792
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8120e402)
Location: include/linux/filter.h:835
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:convert_ctx_accesses
```
```
In kernel/bpf/cgroup.c (0)
Location: include/linux/filter.h:835
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81242b15)
Location: include/linux/filter.h:856
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:convert_ctx_accesses
```
```
In kernel/bpf/cgroup.c (0)
Location: include/linux/filter.h:856
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81288218)
Location: include/linux/filter.h:859
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:convert_ctx_accesses
```
```
In kernel/bpf/cgroup.c (0)
Location: include/linux/filter.h:859
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812deb01)
Location: include/linux/filter.h:831
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:convert_ctx_accesses
```
```
In kernel/bpf/cgroup.c (0)
Location: include/linux/filter.h:831
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812fd937)
Location: include/linux/filter.h:831
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:convert_ctx_accesses
```
```
In kernel/bpf/cgroup.c (0)
Location: include/linux/filter.h:831
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8131ce5c)
Location: include/linux/filter.h:865
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:convert_ctx_accesses
```
```
In kernel/bpf/cgroup.c (0)
Location: include/linux/filter.h:865
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffff80001026f004)
Location: include/linux/filter.h:752
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:convert_ctx_accesses
```
```
In kernel/bpf/cgroup.c (0)
Location: include/linux/filter.h:752
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c04a1458)
Location: include/linux/filter.h:752
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:convert_ctx_accesses
```
```
In kernel/bpf/cgroup.c (0)
Location: include/linux/filter.h:752
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c000000000315a58)
Location: include/linux/filter.h:752
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:convert_ctx_accesses
```
```
In kernel/bpf/cgroup.c (0)
Location: include/linux/filter.h:752
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffe0001a8b08)
Location: include/linux/filter.h:752
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:convert_ctx_accesses
```
```
In kernel/bpf/cgroup.c (0)
Location: include/linux/filter.h:752
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e3d20)
Location: include/linux/filter.h:752
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:convert_ctx_accesses
```
```
In kernel/bpf/cgroup.c (0)
Location: include/linux/filter.h:752
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d6ae0)
Location: include/linux/filter.h:752
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:convert_ctx_accesses
```
```
In kernel/bpf/cgroup.c (0)
Location: include/linux/filter.h:752
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e1af0)
Location: include/linux/filter.h:752
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:convert_ctx_accesses
```
```
In kernel/bpf/cgroup.c (0)
Location: include/linux/filter.h:752
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811eff00)
Location: include/linux/filter.h:752
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:convert_ctx_accesses
```
```
In kernel/bpf/cgroup.c (0)
Location: include/linux/filter.h:752
Inline: True
```
</details>
</li>
</ul>

## Differences
