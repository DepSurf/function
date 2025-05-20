# Function: <code>realloc_array</code>

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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *realloc_array(void *arr, size_t old_n, size_t new_n, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812350e0)
Location: kernel/bpf/verifier.c:779
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_stack_write_var_off
  - kernel/bpf/verifier.c:check_stack_write_fixed_off
```
**Symbols:**

```
ffffffff812350e0-ffffffff81235174: realloc_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *realloc_array(void *arr, size_t old_n, size_t new_n, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81278d10)
Location: kernel/bpf/verifier.c:1006
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_stack_write_var_off
  - kernel/bpf/verifier.c:check_stack_write_fixed_off
  - kernel/bpf/verifier.c:acquire_reference_state
```
**Symbols:**

```
ffffffff81278d10-ffffffff81278db2: realloc_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *realloc_array(void *arr, size_t old_n, size_t new_n, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812cf1f0)
Location: kernel/bpf/verifier.c:1197
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_stack_write_var_off
  - kernel/bpf/verifier.c:check_stack_write_fixed_off
  - kernel/bpf/verifier.c:acquire_reference_state
```
**Symbols:**

```
ffffffff812cf1f0-ffffffff812cf2af: realloc_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *realloc_array(void *arr, size_t old_n, size_t new_n, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812f7670)
Location: kernel/bpf/verifier.c:1574
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_stack_write_var_off
  - kernel/bpf/verifier.c:check_stack_write_fixed_off
  - kernel/bpf/verifier.c:acquire_reference_state
```
**Symbols:**

```
ffffffff812f7670-ffffffff812f774a: realloc_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *realloc_array(void *arr, size_t old_n, size_t new_n, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81316a60)
Location: kernel/bpf/verifier.c:1215
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_stack_access_within_bounds
  - kernel/bpf/verifier.c:acquire_reference_state
```
**Symbols:**

```
ffffffff81316a60-ffffffff81316b3a: realloc_array (STB_LOCAL)
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
