# Function: <code>get_kfunc_ptr_arg_type</code>

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
enum kfunc_ptr_arg_type get_kfunc_ptr_arg_type(struct bpf_verifier_env *env, struct bpf_kfunc_call_arg_meta *meta, const struct btf_type *t, const struct btf_type *ref_t, const char *ref_tname, const struct btf_param *args, int argno, int nargs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812dc0c0)
Location: kernel/bpf/verifier.c:8652
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_kfunc_args
```
**Symbols:**

```
ffffffff812dc0c0-ffffffff812dc438: get_kfunc_ptr_arg_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
enum kfunc_ptr_arg_type get_kfunc_ptr_arg_type(struct bpf_verifier_env *env, struct bpf_kfunc_call_arg_meta *meta, const struct btf_type *t, const struct btf_type *ref_t, const char *ref_tname, const struct btf_param *args, int argno, int nargs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812fb140)
Location: kernel/bpf/verifier.c:10161
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_kfunc_args
```
**Symbols:**

```
ffffffff812fb140-ffffffff812fb517: get_kfunc_ptr_arg_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
enum kfunc_ptr_arg_type get_kfunc_ptr_arg_type(struct bpf_verifier_env *env, struct bpf_kfunc_call_arg_meta *meta, const struct btf_type *t, const struct btf_type *ref_t, const char *ref_tname, const struct btf_param *args, int argno, int nargs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8131afd0)
Location: kernel/bpf/verifier.c:10955
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_kfunc_args
```
**Symbols:**

```
ffffffff8131afd0-ffffffff8131b421: get_kfunc_ptr_arg_type (STB_LOCAL)
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
