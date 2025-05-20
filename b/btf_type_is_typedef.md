# Function: <code>btf_type_is_typedef</code>

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
In kernel/bpf/verifier.c (ffffffff81206493)
Location: include/linux/btf.h:95
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_attach_btf_id
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
In kernel/bpf/verifier.c (ffffffff812140d9)
Location: include/linux/btf.h:140
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check_attach_target
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
In kernel/bpf/verifier.c (ffffffff8121690e)
Location: include/linux/btf.h:150
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check_attach_target
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
In kernel/bpf/verifier.c (ffffffff8124d048)
Location: include/linux/btf.h:151
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check_attach_target
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
In kernel/bpf/verifier.c (ffffffff81294024)
Location: include/linux/btf.h:232
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check_attach_target
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/btf.h:232
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
In kernel/bpf/verifier.c (ffffffff812eea63)
Location: include/linux/btf.h:319
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check_attach_target
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/btf.h:319
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
In kernel/bpf/verifier.c (ffffffff8131b446)
Location: include/linux/btf.h:335
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check_attach_target
```
```
In kernel/bpf/btf.c (0)
Location: include/linux/btf.h:335
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
In kernel/bpf/verifier.c (ffffffff8133d48a)
Location: include/linux/btf.h:346
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check_attach_target
```
```
In kernel/bpf/btf.c (ffffffff8136679f)
Location: include/linux/btf.h:346
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_validate_prog_ctx_type
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
