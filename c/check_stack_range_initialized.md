# Function: <code>check_stack_range_initialized</code>

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
int check_stack_range_initialized(struct bpf_verifier_env *env, int regno, int off, int access_size, bool zero_size_allowed, enum stack_access_src type, struct bpf_call_arg_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81206dd0)
Location: kernel/bpf/verifier.c:4349
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_stack_read
```
**Symbols:**

```
ffffffff81206dd0-ffffffff81207184: check_stack_range_initialized (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int check_stack_range_initialized(struct bpf_verifier_env *env, int regno, int off, int access_size, bool zero_size_allowed, enum stack_access_src type, struct bpf_call_arg_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:4463
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_stack_read
```
**Symbols:**

```
ffffffff8123a170-ffffffff8123a646: check_stack_range_initialized (STB_LOCAL)
ffffffff81cb7dd6-ffffffff81cb7ea3: check_stack_range_initialized.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int check_stack_range_initialized(struct bpf_verifier_env *env, int regno, int off, int access_size, bool zero_size_allowed, enum bpf_access_src type, struct bpf_call_arg_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:5041
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_stack_read
```
**Symbols:**

```
ffffffff8127e2f0-ffffffff8127e7e5: check_stack_range_initialized (STB_LOCAL)
ffffffff81e68f03-ffffffff81e68fd4: check_stack_range_initialized.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int check_stack_range_initialized(struct bpf_verifier_env *env, int regno, int off, int access_size, bool zero_size_allowed, enum bpf_access_src type, struct bpf_call_arg_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:5546
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_stack_read
```
**Symbols:**

```
ffffffff812d6a10-ffffffff812d6fb8: check_stack_range_initialized (STB_LOCAL)
ffffffff8205ff3b-ffffffff82060049: check_stack_range_initialized.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int check_stack_range_initialized(struct bpf_verifier_env *env, int regno, int off, int access_size, bool zero_size_allowed, enum bpf_access_src type, struct bpf_call_arg_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:6626
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff812f8fe0-ffffffff812f96a2: check_stack_range_initialized (STB_LOCAL)
ffffffff820deaa8-ffffffff820debfb: check_stack_range_initialized.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int check_stack_range_initialized(struct bpf_verifier_env *env, int regno, int off, int access_size, bool zero_size_allowed, enum bpf_access_src type, struct bpf_call_arg_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:6997
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff81318c70-ffffffff8131927d: check_stack_range_initialized (STB_LOCAL)
ffffffff821bab91-ffffffff821baccb: check_stack_range_initialized.cold (STB_LOCAL)
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
<code>enum stack_access_src type</code> ➡️ <code>enum bpf_access_src type</code>
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
