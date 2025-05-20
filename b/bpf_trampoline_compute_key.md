# Function: <code>bpf_trampoline_compute_key</code>

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
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812003dc)
Location: include/linux/bpf_verifier.h:472
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
```
```
In kernel/bpf/verifier.c (ffffffff812145f9)
Location: include/linux/bpf_verifier.h:472
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_attach_btf_id
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
In kernel/bpf/syscall.c (ffffffff81200d8c)
Location: include/linux/bpf_verifier.h:491
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
```
```
In kernel/bpf/verifier.c (ffffffff81216e35)
Location: include/linux/bpf_verifier.h:491
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_attach_btf_id
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
In kernel/bpf/syscall.c (ffffffff81232afc)
Location: include/linux/bpf_verifier.h:514
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
```
```
In kernel/bpf/verifier.c (ffffffff8124d5b6)
Location: include/linux/bpf_verifier.h:514
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_attach_btf_id
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
In kernel/bpf/syscall.c (ffffffff81275f2b)
Location: include/linux/bpf_verifier.h:553
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
```
```
In kernel/bpf/verifier.c (ffffffff81294533)
Location: include/linux/bpf_verifier.h:553
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_attach_btf_id
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
In kernel/bpf/syscall.c (ffffffff812cc061)
Location: include/linux/bpf_verifier.h:623
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
```
```
In kernel/bpf/verifier.c (ffffffff812ef095)
Location: include/linux/bpf_verifier.h:623
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_attach_btf_id
```
```
In kernel/bpf/trampoline.c (ffffffff8130896c)
Location: include/linux/bpf_verifier.h:623
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_unlink_cgroup_shim
  - kernel/bpf/trampoline.c:bpf_trampoline_unlink_cgroup_shim
  - kernel/bpf/trampoline.c:bpf_trampoline_link_cgroup_shim
  - kernel/bpf/trampoline.c:bpf_trampoline_link_cgroup_shim
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
In kernel/bpf/syscall.c (ffffffff812f3af9)
Location: include/linux/bpf_verifier.h:687
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
```
```
In kernel/bpf/verifier.c (ffffffff8131ba48)
Location: include/linux/bpf_verifier.h:687
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_attach_btf_id
```
```
In kernel/bpf/trampoline.c (ffffffff8133788c)
Location: include/linux/bpf_verifier.h:687
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_unlink_cgroup_shim
  - kernel/bpf/trampoline.c:bpf_trampoline_unlink_cgroup_shim
  - kernel/bpf/trampoline.c:bpf_trampoline_link_cgroup_shim
  - kernel/bpf/trampoline.c:bpf_trampoline_link_cgroup_shim
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
In kernel/bpf/syscall.c (ffffffff813129ba)
Location: include/linux/bpf_verifier.h:789
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
```
```
In kernel/bpf/verifier.c (ffffffff8133ddc3)
Location: include/linux/bpf_verifier.h:789
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_attach_btf_id
```
```
In kernel/bpf/trampoline.c (ffffffff8135d6cc)
Location: include/linux/bpf_verifier.h:789
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_unlink_cgroup_shim
  - kernel/bpf/trampoline.c:bpf_trampoline_unlink_cgroup_shim
  - kernel/bpf/trampoline.c:bpf_trampoline_link_cgroup_shim
  - kernel/bpf/trampoline.c:bpf_trampoline_link_cgroup_shim
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
