# Function: <code>__kfunc_param_match_suffix</code>

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
<summary>In <code>6.2</code>: ✅</summary>

```c
bool __kfunc_param_match_suffix(const struct btf *btf, const struct btf_param *arg, const char *suffix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812cf5c0)
Location: kernel/bpf/verifier.c:8436
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:get_kfunc_ptr_arg_type
  - kernel/bpf/verifier.c:get_kfunc_ptr_arg_type
```
**Symbols:**

```
ffffffff812cf5c0-ffffffff812cf63c: __kfunc_param_match_suffix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool __kfunc_param_match_suffix(const struct btf *btf, const struct btf_param *arg, const char *suffix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812f82d0)
Location: kernel/bpf/verifier.c:9850
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:get_kfunc_ptr_arg_type
  - kernel/bpf/verifier.c:get_kfunc_ptr_arg_type
  - kernel/bpf/verifier.c:get_kfunc_ptr_arg_type
```
**Symbols:**

```
ffffffff812f82d0-ffffffff812f834c: __kfunc_param_match_suffix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool __kfunc_param_match_suffix(const struct btf *btf, const struct btf_param *arg, const char *suffix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81317200)
Location: kernel/bpf/verifier.c:10623
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:get_kfunc_ptr_arg_type
  - kernel/bpf/verifier.c:get_kfunc_ptr_arg_type
  - kernel/bpf/verifier.c:get_kfunc_ptr_arg_type
  - kernel/bpf/verifier.c:get_kfunc_ptr_arg_type
  - kernel/bpf/verifier.c:get_kfunc_ptr_arg_type
```
**Symbols:**

```
ffffffff81317200-ffffffff8131727c: __kfunc_param_match_suffix (STB_LOCAL)
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
