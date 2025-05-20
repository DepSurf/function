# Function: <code>btf_int_offset</code>

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
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812b25bb)
Location: include/linux/btf.h:217
Inline: True
Inline callers:
  - kernel/bpf/btf.c:__bpf_core_types_are_compat
  - kernel/bpf/btf.c:__bpf_core_types_are_compat
```
```
In tools/lib/bpf/relo_core.c (ffffffff812c94d4)
Location: include/linux/btf.h:217
Inline: True
Inline callers:
  - tools/lib/bpf/relo_core.c:bpf_core_fields_are_compat
  - tools/lib/bpf/relo_core.c:bpf_core_fields_are_compat
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
In tools/lib/bpf/relo_core.c (ffffffff813304ec)
Location: include/linux/btf.h:304
Inline: True
Inline callers:
  - tools/lib/bpf/relo_core.c:bpf_core_fields_are_compat
  - tools/lib/bpf/relo_core.c:bpf_core_fields_are_compat
  - tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat
  - tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat
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
In tools/lib/bpf/relo_core.c (ffffffff813611f7)
Location: include/linux/btf.h:325
Inline: True
Inline callers:
  - tools/lib/bpf/relo_core.c:bpf_core_fields_are_compat
  - tools/lib/bpf/relo_core.c:bpf_core_fields_are_compat
  - tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat
  - tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat
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
In tools/lib/bpf/relo_core.c (ffffffff8138a0a7)
Location: include/linux/btf.h:336
Inline: True
Inline callers:
  - tools/lib/bpf/relo_core.c:bpf_core_fields_are_compat
  - tools/lib/bpf/relo_core.c:bpf_core_fields_are_compat
  - tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat
  - tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat
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
