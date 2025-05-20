# Function: <code>btf_type_name</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
const char *btf_type_name(const struct btf *btf, u32 id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81314c04)
Location: kernel/bpf/verifier.c:730
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:process_iter_arg
  - kernel/bpf/verifier.c:process_iter_arg
  - kernel/bpf/verifier.c:map_kptr_match_type
  - kernel/bpf/verifier.c:map_kptr_match_type
  - kernel/bpf/verifier.c:print_verifier_state
  - kernel/bpf/verifier.c:print_verifier_state
Direct callers:
  - kernel/bpf/verifier.c:check_reg_type
  - kernel/bpf/verifier.c:check_reg_type
```
**Symbols:**

```
ffffffff812f6600-ffffffff812f662a: btf_type_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline ⚠️</summary>

```c
const char *btf_type_name(const struct btf *btf, u32 id);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8133cd9d)
Location: kernel/bpf/verifier.c:344
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check_subprogs
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:map_kptr_match_type
  - kernel/bpf/verifier.c:map_kptr_match_type
Direct callers:
  - kernel/bpf/verifier.c:check_reg_type
  - kernel/bpf/verifier.c:check_reg_type
```
```
In kernel/bpf/log.c (ffffffff8134667f)
Location: kernel/bpf/log.c:388
Inline: True
Inline callers:
  - kernel/bpf/log.c:print_verifier_state
  - kernel/bpf/log.c:print_reg_state
```
**Symbols:**

```
ffffffff81315300-ffffffff8131532a: btf_type_name (STB_LOCAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
