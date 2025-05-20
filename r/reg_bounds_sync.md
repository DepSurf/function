# Function: <code>reg_bounds_sync</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
void reg_bounds_sync(struct bpf_reg_state *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8127bc50)
Location: kernel/bpf/verifier.c:1565
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:__reg_combine_min_max
  - kernel/bpf/verifier.c:__reg_combine_min_max
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:__reg_combine_64_into_32
  - kernel/bpf/verifier.c:__reg_combine_32_into_64
  - kernel/bpf/verifier.c:__reg_combine_32_into_64
```
**Symbols:**

```
ffffffff8127bc50-ffffffff8127bea0: reg_bounds_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void reg_bounds_sync(struct bpf_reg_state *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812d2230)
Location: kernel/bpf/verifier.c:1779
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:__reg_combine_min_max
  - kernel/bpf/verifier.c:__reg_combine_min_max
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:__reg_combine_64_into_32
  - kernel/bpf/verifier.c:__reg_combine_32_into_64
  - kernel/bpf/verifier.c:__reg_combine_32_into_64
```
**Symbols:**

```
ffffffff812d2230-ffffffff812d2480: reg_bounds_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void reg_bounds_sync(struct bpf_reg_state *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff813076f0)
Location: kernel/bpf/verifier.c:2176
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:__reg_combine_min_max
  - kernel/bpf/verifier.c:__reg_combine_min_max
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:__reg_combine_64_into_32
  - kernel/bpf/verifier.c:__reg_combine_32_into_64
  - kernel/bpf/verifier.c:__reg_combine_32_into_64
```
**Symbols:**

```
ffffffff813076f0-ffffffff81307937: reg_bounds_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void reg_bounds_sync(struct bpf_reg_state *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81326f30)
Location: kernel/bpf/verifier.c:2176
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff81326f30-ffffffff81327158: reg_bounds_sync (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
