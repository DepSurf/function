# Function: <code>__update_reg64_bounds</code>

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
In kernel/bpf/verifier.c (ffffffff81203faf)
Location: kernel/bpf/verifier.c:1114
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:__reg_combine_min_max
  - kernel/bpf/verifier.c:__reg_combine_min_max
  - kernel/bpf/verifier.c:__reg_combine_min_max
  - kernel/bpf/verifier.c:__reg_combine_min_max
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:__reg_combine_64_into_32
  - kernel/bpf/verifier.c:__reg_combine_32_into_64
  - kernel/bpf/verifier.c:__reg_combine_32_into_64
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
In kernel/bpf/verifier.c (ffffffff81203f3f)
Location: kernel/bpf/verifier.c:1146
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:__reg_combine_min_max
  - kernel/bpf/verifier.c:__reg_combine_min_max
  - kernel/bpf/verifier.c:__reg_combine_min_max
  - kernel/bpf/verifier.c:__reg_combine_min_max
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:__reg_combine_64_into_32
  - kernel/bpf/verifier.c:__reg_combine_32_into_64
  - kernel/bpf/verifier.c:__reg_combine_32_into_64
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
In kernel/bpf/verifier.c (ffffffff81204f17)
Location: kernel/bpf/verifier.c:1240
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:__reg_combine_min_max
  - kernel/bpf/verifier.c:__reg_combine_min_max
  - kernel/bpf/verifier.c:__reg_combine_min_max
  - kernel/bpf/verifier.c:__reg_combine_min_max
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:__reg_combine_64_into_32
  - kernel/bpf/verifier.c:__reg_combine_32_into_64
  - kernel/bpf/verifier.c:__reg_combine_32_into_64
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
In kernel/bpf/verifier.c (ffffffff81237a47)
Location: kernel/bpf/verifier.c:1254
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:__reg_combine_min_max
  - kernel/bpf/verifier.c:__reg_combine_min_max
  - kernel/bpf/verifier.c:__reg_combine_min_max
  - kernel/bpf/verifier.c:__reg_combine_min_max
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:__reg_combine_64_into_32
  - kernel/bpf/verifier.c:__reg_combine_32_into_64
  - kernel/bpf/verifier.c:__reg_combine_32_into_64
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81282e47)
Location: kernel/bpf/verifier.c:1458
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:reg_bounds_sync
  - kernel/bpf/verifier.c:reg_bounds_sync
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
In kernel/bpf/verifier.c (ffffffff812da987)
Location: kernel/bpf/verifier.c:1672
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:reg_bounds_sync
  - kernel/bpf/verifier.c:reg_bounds_sync
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
In kernel/bpf/verifier.c (ffffffff8131073b)
Location: kernel/bpf/verifier.c:2069
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:reg_bounds_sync
  - kernel/bpf/verifier.c:reg_bounds_sync
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
In kernel/bpf/verifier.c (ffffffff813312cb)
Location: kernel/bpf/verifier.c:1923
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:reg_bounds_sync
  - kernel/bpf/verifier.c:reg_bounds_sync
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
