# Function: <code>btf_type_is_small_int</code>

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
In kernel/bpf/btf.c (ffffffff81224bf9)
Location: include/linux/btf.h:85
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
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
In kernel/bpf/verifier.c (ffffffff8120f6c1)
Location: include/linux/btf.h:130
Inline: True
```
```
In kernel/bpf/btf.c (ffffffff8122b58f)
Location: include/linux/btf.h:130
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
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
In kernel/bpf/verifier.c (ffffffff81211041)
Location: include/linux/btf.h:135
Inline: True
```
```
In kernel/bpf/btf.c (ffffffff8122ff92)
Location: include/linux/btf.h:135
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
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
In kernel/bpf/verifier.c (ffffffff812453c7)
Location: include/linux/btf.h:136
Inline: True
```
```
In kernel/bpf/btf.c (ffffffff81268c4c)
Location: include/linux/btf.h:136
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
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
In kernel/bpf/verifier.c (ffffffff8128af0e)
Location: include/linux/btf.h:170
Inline: True
```
```
In kernel/bpf/btf.c (ffffffff812b5f3d)
Location: include/linux/btf.h:170
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
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
In kernel/bpf/verifier.c (ffffffff812e344e)
Location: include/linux/btf.h:234
Inline: True
```
```
In kernel/bpf/btf.c (ffffffff81316e32)
Location: include/linux/btf.h:234
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
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
In kernel/bpf/verifier.c (ffffffff81305784)
Location: include/linux/btf.h:245
Inline: True
```
```
In kernel/bpf/btf.c (ffffffff81346d33)
Location: include/linux/btf.h:245
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
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
In kernel/bpf/verifier.c (ffffffff813268f7)
Location: include/linux/btf.h:256
Inline: True
```
```
In kernel/bpf/btf.c (ffffffff8136d126)
Location: include/linux/btf.h:256
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
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
