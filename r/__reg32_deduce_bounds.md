# Function: <code>__reg32_deduce_bounds</code>

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
void __reg32_deduce_bounds(struct bpf_reg_state *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81201d10)
Location: kernel/bpf/verifier.c:1134
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:__reg_combine_min_max
  - kernel/bpf/verifier.c:__reg_combine_min_max
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:__reg_combine_64_into_32
  - kernel/bpf/verifier.c:__reg_combine_32_into_64
```
**Symbols:**

```
ffffffff81201d10-ffffffff81201d6d: __reg32_deduce_bounds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __reg32_deduce_bounds(struct bpf_reg_state *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812017a0)
Location: kernel/bpf/verifier.c:1166
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:__reg_combine_min_max
  - kernel/bpf/verifier.c:__reg_combine_min_max
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:__reg_combine_64_into_32
  - kernel/bpf/verifier.c:__reg_combine_32_into_64
```
**Symbols:**

```
ffffffff812017a0-ffffffff812017fd: __reg32_deduce_bounds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __reg32_deduce_bounds(struct bpf_reg_state *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81202640)
Location: kernel/bpf/verifier.c:1260
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:__reg_combine_min_max
  - kernel/bpf/verifier.c:__reg_combine_min_max
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:__reg_combine_64_into_32
  - kernel/bpf/verifier.c:__reg_combine_32_into_64
```
**Symbols:**

```
ffffffff81202640-ffffffff812026a4: __reg32_deduce_bounds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __reg32_deduce_bounds(struct bpf_reg_state *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812346a0)
Location: kernel/bpf/verifier.c:1274
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
```
**Symbols:**

```
ffffffff812346a0-ffffffff81234704: __reg32_deduce_bounds (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffff8127bcd4)
Location: kernel/bpf/verifier.c:1478
Inline: True
Inline callers:
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
In kernel/bpf/verifier.c (ffffffff812d22b4)
Location: kernel/bpf/verifier.c:1692
Inline: True
Inline callers:
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
In kernel/bpf/verifier.c (ffffffff81307773)
Location: kernel/bpf/verifier.c:2089
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:reg_bounds_sync
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __reg32_deduce_bounds(struct bpf_reg_state *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81314880)
Location: kernel/bpf/verifier.c:1943
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:reg_bounds_sync
  - kernel/bpf/verifier.c:reg_bounds_sync
```
**Symbols:**

```
ffffffff81314880-ffffffff81314a09: __reg32_deduce_bounds (STB_LOCAL)
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
</ul>
