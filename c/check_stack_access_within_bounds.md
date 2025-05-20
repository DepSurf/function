# Function: <code>check_stack_access_within_bounds</code>

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
int check_stack_access_within_bounds(struct bpf_verifier_env *env, int regno, int off, int access_size, enum stack_access_src src, enum bpf_access_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81206930)
Location: kernel/bpf/verifier.c:3973
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_stack_range_initialized
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff81206930-ffffffff81206aad: check_stack_access_within_bounds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int check_stack_access_within_bounds(struct bpf_verifier_env *env, int regno, int off, int access_size, enum stack_access_src src, enum bpf_access_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81239b50)
Location: kernel/bpf/verifier.c:4074
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_stack_range_initialized
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff81239b50-ffffffff81239d5d: check_stack_access_within_bounds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int check_stack_access_within_bounds(struct bpf_verifier_env *env, int regno, int off, int access_size, enum bpf_access_src src, enum bpf_access_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8127dc20)
Location: kernel/bpf/verifier.c:4623
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_stack_range_initialized
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff8127dc20-ffffffff8127de56: check_stack_access_within_bounds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int check_stack_access_within_bounds(struct bpf_verifier_env *env, int regno, int off, int access_size, enum bpf_access_src src, enum bpf_access_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812d6310)
Location: kernel/bpf/verifier.c:5129
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_stack_range_initialized
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff812d6310-ffffffff812d6546: check_stack_access_within_bounds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int check_stack_access_within_bounds(struct bpf_verifier_env *env, int regno, int off, int access_size, enum bpf_access_src src, enum bpf_access_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812f6dc0)
Location: kernel/bpf/verifier.c:6209
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_stack_range_initialized
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff812f6dc0-ffffffff812f6ff6: check_stack_access_within_bounds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int check_stack_access_within_bounds(struct bpf_verifier_env *env, int regno, int off, int access_size, enum bpf_access_src src, enum bpf_access_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:6584
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_stack_range_initialized
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff81317830-ffffffff81317b99: check_stack_access_within_bounds (STB_LOCAL)
ffffffff821baa0f-ffffffff821baa56: check_stack_access_within_bounds.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>enum stack_access_src src</code> ➡️ <code>enum bpf_access_src src</code>
</li>
</ul>
</details>
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
