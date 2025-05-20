# Function: <code>mark_reg_stack_read</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mark_reg_stack_read(struct bpf_verifier_env *env, struct bpf_func_state *ptr_state, int min_off, int max_off, int dst_regno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81208770)
Location: kernel/bpf/verifier.c:2802
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_stack_read
  - kernel/bpf/verifier.c:check_stack_read_fixed_off
```
**Symbols:**

```
ffffffff81208770-ffffffff81208847: mark_reg_stack_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mark_reg_stack_read(struct bpf_verifier_env *env, struct bpf_func_state *ptr_state, int min_off, int max_off, int dst_regno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8123c170)
Location: kernel/bpf/verifier.c:2868
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_stack_read
  - kernel/bpf/verifier.c:check_stack_read_fixed_off
```
**Symbols:**

```
ffffffff8123c170-ffffffff8123c320: mark_reg_stack_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mark_reg_stack_read(struct bpf_verifier_env *env, struct bpf_func_state *ptr_state, int min_off, int max_off, int dst_regno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81281cd0)
Location: kernel/bpf/verifier.c:3212
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_stack_read
  - kernel/bpf/verifier.c:check_stack_read_fixed_off
```
**Symbols:**

```
ffffffff81281cd0-ffffffff81281e94: mark_reg_stack_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mark_reg_stack_read(struct bpf_verifier_env *env, struct bpf_func_state *ptr_state, int min_off, int max_off, int dst_regno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812d7720)
Location: kernel/bpf/verifier.c:3654
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_stack_read
  - kernel/bpf/verifier.c:check_stack_read_fixed_off
```
**Symbols:**

```
ffffffff812d7720-ffffffff812d78e4: mark_reg_stack_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void mark_reg_stack_read(struct bpf_verifier_env *env, struct bpf_func_state *ptr_state, int min_off, int max_off, int dst_regno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:4536
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_stack_read_fixed_off
```
**Symbols:**

```
ffffffff81308210-ffffffff813084af: mark_reg_stack_read (STB_LOCAL)
ffffffff820df675-ffffffff820df6b9: mark_reg_stack_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void mark_reg_stack_read(struct bpf_verifier_env *env, struct bpf_func_state *ptr_state, int min_off, int max_off, int dst_regno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:4684
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_stack_read_fixed_off
```
**Symbols:**

```
ffffffff81321470-ffffffff81321685: mark_reg_stack_read (STB_LOCAL)
ffffffff821bb2e9-ffffffff821bb349: mark_reg_stack_read.cold (STB_LOCAL)
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
