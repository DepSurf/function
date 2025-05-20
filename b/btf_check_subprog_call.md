# Function: <code>btf_check_subprog_call</code>

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
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int btf_check_subprog_call(struct bpf_verifier_env *env, int subprog, struct bpf_reg_state *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:6808
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:__check_func_call
  - kernel/bpf/verifier.c:__check_func_call
```
**Symbols:**

```
ffffffff82061981-ffffffff820619aa: btf_check_subprog_call.cold (STB_LOCAL)
ffffffff81318080-ffffffff81318158: btf_check_subprog_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int btf_check_subprog_call(struct bpf_verifier_env *env, int subprog, struct bpf_reg_state *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:6910
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:__check_func_call
```
**Symbols:**

```
ffffffff820e1037-ffffffff820e1060: btf_check_subprog_call.cold (STB_LOCAL)
ffffffff81348010-ffffffff813480e8: btf_check_subprog_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int btf_check_subprog_call(struct bpf_verifier_env *env, int subprog, struct bpf_reg_state *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:9322
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:push_callback_call
```
**Symbols:**

```
ffffffff81335830-ffffffff813358d7: btf_check_subprog_call (STB_LOCAL)
ffffffff821bc701-ffffffff821bc71e: btf_check_subprog_call.cold (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
