# Function: <code>bpf_ctx_off_adjust_machine</code>

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
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/filter.h:644
Inline: True
```
```
In kernel/bpf/verifier.c (ffffffff811be09e)
Location: include/linux/filter.h:644
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:convert_ctx_accesses
```
```
In kernel/bpf/cgroup.c (0)
Location: include/linux/filter.h:644
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/filter.h:644
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811cc5ed)
Location: include/linux/filter.h:679
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:convert_ctx_accesses
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811dee68)
Location: include/linux/filter.h:735
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:convert_ctx_accesses
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811eb62c)
Location: include/linux/filter.h:735
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:convert_ctx_accesses
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
In kernel/bpf/verifier.c (ffffffff8120a759)
Location: include/linux/filter.h:766
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:convert_ctx_accesses
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
In kernel/bpf/verifier.c (ffffffff8120c913)
Location: include/linux/filter.h:775
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:convert_ctx_accesses
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
In kernel/bpf/verifier.c (ffffffff8120e315)
Location: include/linux/filter.h:818
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:convert_ctx_accesses
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
In kernel/bpf/verifier.c (ffffffff81242a31)
Location: include/linux/filter.h:839
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:convert_ctx_accesses
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
In kernel/bpf/verifier.c (ffffffff81288152)
Location: include/linux/filter.h:842
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:convert_ctx_accesses
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
In kernel/bpf/verifier.c (ffffffff812dea3b)
Location: include/linux/filter.h:814
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:convert_ctx_accesses
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
In kernel/bpf/verifier.c (ffffffff812fd887)
Location: include/linux/filter.h:814
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:convert_ctx_accesses
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
In kernel/bpf/verifier.c (ffffffff8131cd9e)
Location: include/linux/filter.h:848
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:convert_ctx_accesses
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffff80001026ef68)
Location: include/linux/filter.h:735
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:convert_ctx_accesses
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c04a1390)
Location: include/linux/filter.h:735
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:convert_ctx_accesses
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c0000000003159a8)
Location: include/linux/filter.h:735
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:convert_ctx_accesses
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffe0001a8a84)
Location: include/linux/filter.h:735
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:convert_ctx_accesses
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e3c4c)
Location: include/linux/filter.h:735
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:convert_ctx_accesses
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d6a0c)
Location: include/linux/filter.h:735
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:convert_ctx_accesses
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e1a1c)
Location: include/linux/filter.h:735
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:convert_ctx_accesses
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811efe2c)
Location: include/linux/filter.h:735
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:convert_ctx_accesses
```
</details>
</li>
</ul>

## Differences
