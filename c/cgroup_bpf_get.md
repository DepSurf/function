# Function: <code>cgroup_bpf_get</code>

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
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115b199)
Location: include/linux/cgroup.h:941
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81166e57)
Location: include/linux/cgroup.h:943
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
```
```
In kernel/bpf/cgroup.c (ffffffff81205d8a)
Location: include/linux/cgroup.h:943
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
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
In kernel/cgroup/cgroup.c (ffffffff811785ee)
Location: include/linux/cgroup.h:945
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_clone
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
```
```
In kernel/bpf/cgroup.c (ffffffff8122d50a)
Location: include/linux/cgroup.h:945
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
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
In kernel/cgroup/cgroup.c (ffffffff81175382)
Location: include/linux/cgroup.h:944
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_clone
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
```
```
In kernel/bpf/cgroup.c (ffffffff81235a1a)
Location: include/linux/cgroup.h:944
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
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
In kernel/cgroup/cgroup.c (ffffffff81175f09)
Location: include/linux/cgroup.h:944
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_clone
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
```
```
In kernel/bpf/cgroup.c (ffffffff81239c6a)
Location: include/linux/cgroup.h:944
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
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
In kernel/cgroup/cgroup.c (ffffffff8119d4d3)
Location: include/linux/cgroup.h:919
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_clone
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
```
```
In kernel/bpf/cgroup.c (ffffffff812743d1)
Location: include/linux/cgroup.h:919
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
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
In kernel/cgroup/cgroup.c (ffffffff811cd7f3)
Location: include/linux/cgroup.h:916
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_clone
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
```
```
In kernel/bpf/cgroup.c (ffffffff812c4a80)
Location: include/linux/cgroup.h:916
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
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
In kernel/cgroup/cgroup.c (ffffffff81210e93)
Location: include/linux/cgroup.h:843
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_clone
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
```
```
In kernel/bpf/cgroup.c (ffffffff81329f63)
Location: include/linux/cgroup.h:843
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
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
In kernel/cgroup/cgroup.c (ffffffff81226883)
Location: include/linux/cgroup.h:841
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_clone
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
```
```
In kernel/bpf/cgroup.c (ffffffff8135a0a3)
Location: include/linux/cgroup.h:841
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
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
In kernel/cgroup/cgroup.c (ffffffff8123e513)
Location: include/linux/cgroup.h:839
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_clone
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
```
```
In kernel/bpf/cgroup.c (ffffffff81382c53)
Location: include/linux/cgroup.h:839
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
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
In kernel/cgroup/cgroup.c (ffff8000101d8cdc)
Location: include/linux/cgroup.h:943
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
```
```
In kernel/bpf/cgroup.c (ffff80001028f03c)
Location: include/linux/cgroup.h:943
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
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
In kernel/cgroup/cgroup.c (c041ba48)
Location: include/linux/cgroup.h:943
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
```
```
In kernel/bpf/cgroup.c (c04be864)
Location: include/linux/cgroup.h:943
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
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
In kernel/cgroup/cgroup.c (c0000000002460b0)
Location: include/linux/cgroup.h:943
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
```
```
In kernel/bpf/cgroup.c (c00000000033bc20)
Location: include/linux/cgroup.h:943
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
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
In kernel/cgroup/cgroup.c (ffffffe000151c42)
Location: include/linux/cgroup.h:943
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
```
```
In kernel/bpf/cgroup.c (ffffffe0001c2178)
Location: include/linux/cgroup.h:943
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
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
In kernel/cgroup/cgroup.c (ffffffff8115f477)
Location: include/linux/cgroup.h:943
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
```
```
In kernel/bpf/cgroup.c (ffffffff811fe3aa)
Location: include/linux/cgroup.h:943
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
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
In kernel/cgroup/cgroup.c (ffffffff81152707)
Location: include/linux/cgroup.h:943
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
```
```
In kernel/bpf/cgroup.c (ffffffff811f10fa)
Location: include/linux/cgroup.h:943
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
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
In kernel/cgroup/cgroup.c (ffffffff8115d247)
Location: include/linux/cgroup.h:943
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
```
```
In kernel/bpf/cgroup.c (ffffffff811fc17a)
Location: include/linux/cgroup.h:943
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
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
In kernel/cgroup/cgroup.c (ffffffff8116a3ac)
Location: include/linux/cgroup.h:943
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
```
```
In kernel/bpf/cgroup.c (ffffffff8120ad9a)
Location: include/linux/cgroup.h:943
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
```
</details>
</li>
</ul>

## Differences
