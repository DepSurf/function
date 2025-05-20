# Function: <code>bpf_trampoline_get</code>

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
<summary>In <code>5.11</code>: ✅</summary>

```c
struct bpf_trampoline *bpf_trampoline_get(u64 key, struct bpf_attach_target_info *tgt_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff81222920)
Location: kernel/bpf/trampoline.c:448
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/verifier.c:check_attach_btf_id
```
**Symbols:**

```
ffffffff81222920-ffffffff81222989: bpf_trampoline_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct bpf_trampoline *bpf_trampoline_get(u64 key, struct bpf_attach_target_info *tgt_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff81226f90)
Location: kernel/bpf/trampoline.c:478
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/verifier.c:check_attach_btf_id
```
**Symbols:**

```
ffffffff81226f90-ffffffff81227122: bpf_trampoline_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct bpf_trampoline *bpf_trampoline_get(u64 key, struct bpf_attach_target_info *tgt_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff8125f090)
Location: kernel/bpf/trampoline.c:484
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/verifier.c:check_attach_btf_id
```
**Symbols:**

```
ffffffff8125f090-ffffffff8125f222: bpf_trampoline_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct bpf_trampoline *bpf_trampoline_get(u64 key, struct bpf_attach_target_info *tgt_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff812a96d0)
Location: kernel/bpf/trampoline.c:496
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/verifier.c:check_attach_btf_id
```
**Symbols:**

```
ffffffff812a96d0-ffffffff812a9887: bpf_trampoline_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct bpf_trampoline *bpf_trampoline_get(u64 key, struct bpf_attach_target_info *tgt_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff81308a70)
Location: kernel/bpf/trampoline.c:793
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/verifier.c:check_attach_btf_id
  - kernel/bpf/trampoline.c:bpf_trampoline_link_cgroup_shim
```
**Symbols:**

```
ffffffff81308a70-ffffffff81308aec: bpf_trampoline_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct bpf_trampoline *bpf_trampoline_get(u64 key, struct bpf_attach_target_info *tgt_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff81337990)
Location: kernel/bpf/trampoline.c:771
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/verifier.c:check_attach_btf_id
  - kernel/bpf/trampoline.c:bpf_trampoline_link_cgroup_shim
```
**Symbols:**

```
ffffffff81337990-ffffffff81337a0a: bpf_trampoline_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct bpf_trampoline *bpf_trampoline_get(u64 key, struct bpf_attach_target_info *tgt_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff8135d7d0)
Location: kernel/bpf/trampoline.c:782
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/verifier.c:check_attach_btf_id
  - kernel/bpf/verifier.c:check_attach_btf_id
  - kernel/bpf/trampoline.c:bpf_trampoline_link_cgroup_shim
```
**Symbols:**

```
ffffffff8135d7d0-ffffffff8135d84a: bpf_trampoline_get (STB_GLOBAL)
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
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
