# Function: <code>bpf_trampoline_put</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
void bpf_trampoline_put(struct bpf_trampoline *tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff8121f090)
Location: kernel/bpf/trampoline.c:334
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/verifier.c:check_attach_btf_id
```
**Symbols:**

```
ffffffff8121f090-ffffffff8121f1b2: bpf_trampoline_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bpf_trampoline_put(struct bpf_trampoline *tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff81222990)
Location: kernel/bpf/trampoline.c:468
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_tracing_link_release
```
**Symbols:**

```
ffffffff81222990-ffffffff81222a53: bpf_trampoline_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bpf_trampoline_put(struct bpf_trampoline *tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff81227130)
Location: kernel/bpf/trampoline.c:498
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_tracing_link_release
```
**Symbols:**

```
ffffffff81227130-ffffffff812271f3: bpf_trampoline_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void bpf_trampoline_put(struct bpf_trampoline *tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff8125f230)
Location: kernel/bpf/trampoline.c:504
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_tracing_link_release
```
**Symbols:**

```
ffffffff8125f230-ffffffff8125f2f3: bpf_trampoline_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void bpf_trampoline_put(struct bpf_trampoline *tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff812a9890)
Location: kernel/bpf/trampoline.c:516
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_tracing_link_release
```
**Symbols:**

```
ffffffff812a9890-ffffffff812a996c: bpf_trampoline_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void bpf_trampoline_put(struct bpf_trampoline *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff81308a14)
Location: kernel/bpf/trampoline.c:813
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_unlink_cgroup_shim
  - kernel/bpf/trampoline.c:bpf_trampoline_link_cgroup_shim
  - kernel/bpf/trampoline.c:bpf_trampoline_link_cgroup_shim
Direct callers:
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_tracing_link_release
  - kernel/bpf/trampoline.c:bpf_trampoline_unlink_cgroup_shim
  - kernel/bpf/trampoline.c:bpf_trampoline_link_cgroup_shim
```
**Symbols:**

```
ffffffff81308410-ffffffff81308500: bpf_trampoline_put.part.0 (STB_LOCAL)
ffffffff81308b00-ffffffff81308b22: bpf_trampoline_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void bpf_trampoline_put(struct bpf_trampoline *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff81337934)
Location: kernel/bpf/trampoline.c:791
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_unlink_cgroup_shim
  - kernel/bpf/trampoline.c:bpf_trampoline_link_cgroup_shim
  - kernel/bpf/trampoline.c:bpf_trampoline_link_cgroup_shim
Direct callers:
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_tracing_link_release
  - kernel/bpf/trampoline.c:bpf_trampoline_unlink_cgroup_shim
  - kernel/bpf/trampoline.c:bpf_trampoline_link_cgroup_shim
```
**Symbols:**

```
ffffffff813371f0-ffffffff813372e0: bpf_trampoline_put.part.0 (STB_LOCAL)
ffffffff81337a20-ffffffff81337a42: bpf_trampoline_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void bpf_trampoline_put(struct bpf_trampoline *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff8135d774)
Location: kernel/bpf/trampoline.c:802
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_unlink_cgroup_shim
  - kernel/bpf/trampoline.c:bpf_trampoline_link_cgroup_shim
  - kernel/bpf/trampoline.c:bpf_trampoline_link_cgroup_shim
Direct callers:
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_tracing_link_release
  - kernel/bpf/trampoline.c:bpf_trampoline_unlink_cgroup_shim
  - kernel/bpf/trampoline.c:bpf_trampoline_link_cgroup_shim
```
**Symbols:**

```
ffffffff8135d070-ffffffff8135d160: bpf_trampoline_put.part.0 (STB_LOCAL)
ffffffff8135d860-ffffffff8135d882: bpf_trampoline_put (STB_GLOBAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
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
