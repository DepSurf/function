# Function: <code>btf_is_kernel</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool btf_is_kernel(const struct btf *btf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8122cd00)
Location: kernel/bpf/btf.c:5741
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff8122cd00-ffffffff8122cd12: btf_is_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool btf_is_kernel(const struct btf *btf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812308e7)
Location: kernel/bpf/btf.c:5934
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_func_arg_match
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff81231ab0-ffffffff81231ac2: btf_is_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool btf_is_kernel(const struct btf *btf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81269663)
Location: kernel/bpf/btf.c:5987
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_func_arg_match
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff81cb9592-ffffffff81cb95b2: btf_is_kernel.cold (STB_LOCAL)
ffffffff8126aa50-ffffffff8126aa68: btf_is_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool btf_is_kernel(const struct btf *btf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812b80ef)
Location: kernel/bpf/btf.c:6720
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_func_arg_match
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:map_kptr_match_type
```
**Symbols:**

```
ffffffff81e6a905-ffffffff81e6a92f: btf_is_kernel.cold (STB_LOCAL)
ffffffff812b78c0-ffffffff812b78e2: btf_is_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool btf_is_kernel(const struct btf *btf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:7211
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_ptr_to_btf_access
  - kernel/bpf/verifier.c:check_ptr_to_btf_access
  - kernel/bpf/verifier.c:map_kptr_match_type
```
**Symbols:**

```
ffffffff820619e3-ffffffff82061a0d: btf_is_kernel.cold (STB_LOCAL)
ffffffff81318f40-ffffffff81318f62: btf_is_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool btf_is_kernel(const struct btf *btf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81348fc3)
Location: kernel/bpf/btf.c:7310
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_kptr
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_obj_free_fields
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_ptr_to_btf_access
  - kernel/bpf/verifier.c:check_ptr_to_btf_access
  - kernel/bpf/verifier.c:map_kptr_match_type
```
**Symbols:**

```
ffffffff820e1099-ffffffff820e10c3: btf_is_kernel.cold (STB_LOCAL)
ffffffff81348d60-ffffffff81348d82: btf_is_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool btf_is_kernel(const struct btf *btf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8136f6f3)
Location: kernel/bpf/btf.c:7374
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_kptr
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_obj_free_fields
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:check_ptr_to_btf_access
  - kernel/bpf/verifier.c:check_ptr_to_btf_access
  - kernel/bpf/verifier.c:map_kptr_match_type
```
**Symbols:**

```
ffffffff821bd8a6-ffffffff821bd8d0: btf_is_kernel.cold (STB_LOCAL)
ffffffff8136f490-ffffffff8136f4b2: btf_is_kernel (STB_GLOBAL)
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
