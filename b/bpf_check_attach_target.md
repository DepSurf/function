# Function: <code>bpf_check_attach_target</code>

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
int bpf_check_attach_target(struct bpf_verifier_log *log, const struct bpf_prog *prog, const struct bpf_prog *tgt_prog, u32 btf_id, struct bpf_attach_target_info *tgt_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81213d50)
Location: kernel/bpf/verifier.c:11643
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/verifier.c:check_attach_btf_id
```
**Symbols:**

```
ffffffff81213d50-ffffffff812144c7: bpf_check_attach_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_check_attach_target(struct bpf_verifier_log *log, const struct bpf_prog *prog, const struct bpf_prog *tgt_prog, u32 btf_id, struct bpf_attach_target_info *tgt_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81216580)
Location: kernel/bpf/verifier.c:12954
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/verifier.c:check_attach_btf_id
```
**Symbols:**

```
ffffffff81216580-ffffffff81216cff: bpf_check_attach_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int bpf_check_attach_target(struct bpf_verifier_log *log, const struct bpf_prog *prog, const struct bpf_prog *tgt_prog, u32 btf_id, struct bpf_attach_target_info *tgt_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:13390
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/verifier.c:check_attach_btf_id
```
**Symbols:**

```
ffffffff81cb8efe-ffffffff81cb8f3e: bpf_check_attach_target.cold (STB_LOCAL)
ffffffff8124ccb0-ffffffff8124d42a: bpf_check_attach_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int bpf_check_attach_target(struct bpf_verifier_log *log, const struct bpf_prog *prog, const struct bpf_prog *tgt_prog, u32 btf_id, struct bpf_attach_target_info *tgt_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:14554
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/verifier.c:check_attach_btf_id
```
**Symbols:**

```
ffffffff81e6a1bf-ffffffff81e6a1fd: bpf_check_attach_target.cold (STB_LOCAL)
ffffffff81293ce0-ffffffff812943b9: bpf_check_attach_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int bpf_check_attach_target(struct bpf_verifier_log *log, const struct bpf_prog *prog, const struct bpf_prog *tgt_prog, u32 btf_id, struct bpf_attach_target_info *tgt_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:16711
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/verifier.c:check_attach_btf_id
  - kernel/bpf/trampoline.c:bpf_trampoline_link_cgroup_shim
```
**Symbols:**

```
ffffffff820612b3-ffffffff820612fc: bpf_check_attach_target.cold (STB_LOCAL)
ffffffff812ee7b0-ffffffff812eef10: bpf_check_attach_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int bpf_check_attach_target(struct bpf_verifier_log *log, const struct bpf_prog *prog, const struct bpf_prog *tgt_prog, u32 btf_id, struct bpf_attach_target_info *tgt_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:18995
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/verifier.c:check_attach_btf_id
  - kernel/bpf/trampoline.c:bpf_trampoline_link_cgroup_shim
```
**Symbols:**

```
ffffffff820e0734-ffffffff820e0786: bpf_check_attach_target.cold (STB_LOCAL)
ffffffff8131b080-ffffffff8131b885: bpf_check_attach_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int bpf_check_attach_target(struct bpf_verifier_log *log, const struct bpf_prog *prog, const struct bpf_prog *tgt_prog, u32 btf_id, struct bpf_attach_target_info *tgt_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:20322
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/verifier.c:check_attach_btf_id
  - kernel/bpf/trampoline.c:bpf_trampoline_link_cgroup_shim
```
**Symbols:**

```
ffffffff821bcdeb-ffffffff821bce9a: bpf_check_attach_target.cold (STB_LOCAL)
ffffffff8133d2e0-ffffffff8133dbfe: bpf_check_attach_target (STB_GLOBAL)
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
