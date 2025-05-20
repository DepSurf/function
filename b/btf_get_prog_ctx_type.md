# Function: <code>btf_get_prog_ctx_type</code>

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
const struct btf_member *btf_get_prog_ctx_type(struct bpf_verifier_log *log, struct btf *btf, const struct btf_type *t, enum bpf_prog_type prog_type, int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8121f900)
Location: kernel/bpf/btf.c:3515
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_ctx_access
```
**Symbols:**

```
ffffffff8121f900-ffffffff8121fa32: btf_get_prog_ctx_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const struct btf_member *btf_get_prog_ctx_type(struct bpf_verifier_log *log, struct btf *btf, const struct btf_type *t, enum bpf_prog_type prog_type, int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81226ca0)
Location: kernel/bpf/btf.c:4306
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_ctx_access
```
**Symbols:**

```
ffffffff81226ca0-ffffffff81226e89: btf_get_prog_ctx_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const struct btf_member *btf_get_prog_ctx_type(struct bpf_verifier_log *log, const struct btf *btf, const struct btf_type *t, enum bpf_prog_type prog_type, int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8122b790)
Location: kernel/bpf/btf.c:4379
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_ctx_access
```
**Symbols:**

```
ffffffff8122b790-ffffffff8122b960: btf_get_prog_ctx_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const struct btf_member *btf_get_prog_ctx_type(struct bpf_verifier_log *log, const struct btf *btf, const struct btf_type *t, enum bpf_prog_type prog_type, int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81263fd0)
Location: kernel/bpf/btf.c:4427
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_ctx_access
```
**Symbols:**

```
ffffffff81263fd0-ffffffff812641cd: btf_get_prog_ctx_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const struct btf_member *btf_get_prog_ctx_type(struct bpf_verifier_log *log, const struct btf *btf, const struct btf_type *t, enum bpf_prog_type prog_type, int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812aeb70)
Location: kernel/bpf/btf.c:4978
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_ctx_access
```
**Symbols:**

```
ffffffff812aeb70-ffffffff812aedc9: btf_get_prog_ctx_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const struct btf_member *btf_get_prog_ctx_type(struct bpf_verifier_log *log, const struct btf *btf, const struct btf_type *t, enum bpf_prog_type prog_type, int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81316100)
Location: kernel/bpf/btf.c:5537
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:get_kfunc_ptr_arg_type
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_ctx_access
```
**Symbols:**

```
ffffffff81316100-ffffffff8131642e: btf_get_prog_ctx_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const struct btf_member *btf_get_prog_ctx_type(struct bpf_verifier_log *log, const struct btf *btf, const struct btf_type *t, enum bpf_prog_type prog_type, int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81345f70)
Location: kernel/bpf/btf.c:5611
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:get_kfunc_ptr_arg_type
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_ctx_access
```
**Symbols:**

```
ffffffff81345f70-ffffffff813462f1: btf_get_prog_ctx_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const struct btf_type *btf_get_prog_ctx_type(struct bpf_verifier_log *log, const struct btf *btf, const struct btf_type *t, enum bpf_prog_type prog_type, int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8136c8b0)
Location: kernel/bpf/btf.c:5651
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:get_kfunc_ptr_arg_type
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_ctx_access
```
**Symbols:**

```
ffffffff8136c8b0-ffffffff8136cc26: btf_get_prog_ctx_type (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct btf *btf</code> ➡️ <code>const struct btf *btf</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>const struct btf_member *</code> ➡️ <code>const struct btf_type *</code>
</li>
</ul>
</details>
</li>
</ul>
