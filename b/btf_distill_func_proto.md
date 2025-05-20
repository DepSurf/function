# Function: <code>btf_distill_func_proto</code>

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
int btf_distill_func_proto(struct bpf_verifier_log *log, struct btf *btf, const struct btf_type *func, const char *tname, struct btf_func_model *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81225430)
Location: kernel/bpf/btf.c:4173
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_attach_btf_id
  - kernel/bpf/verifier.c:check_attach_btf_id
  - kernel/bpf/verifier.c:check_attach_btf_id
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
```
**Symbols:**

```
ffffffff81225430-ffffffff812255c3: btf_distill_func_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int btf_distill_func_proto(struct bpf_verifier_log *log, struct btf *btf, const struct btf_type *func, const char *tname, struct btf_func_model *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8122bca0)
Location: kernel/bpf/btf.c:5097
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
```
**Symbols:**

```
ffffffff8122bca0-ffffffff8122be0c: btf_distill_func_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int btf_distill_func_proto(struct bpf_verifier_log *log, struct btf *btf, const struct btf_type *func, const char *tname, struct btf_func_model *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81230ca0)
Location: kernel/bpf/btf.c:5170
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:add_kfunc_call
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
```
**Symbols:**

```
ffffffff81230ca0-ffffffff81230e6c: btf_distill_func_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int btf_distill_func_proto(struct bpf_verifier_log *log, struct btf *btf, const struct btf_type *func, const char *tname, struct btf_func_model *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81269b70)
Location: kernel/bpf/btf.c:5223
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:add_kfunc_call
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
```
**Symbols:**

```
ffffffff81269b70-ffffffff81269d74: btf_distill_func_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int btf_distill_func_proto(struct bpf_verifier_log *log, struct btf *btf, const struct btf_type *func, const char *tname, struct btf_func_model *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812b6960)
Location: kernel/bpf/btf.c:5777
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:add_kfunc_call
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
```
**Symbols:**

```
ffffffff812b6960-ffffffff812b6b72: btf_distill_func_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int btf_distill_func_proto(struct bpf_verifier_log *log, struct btf *btf, const struct btf_type *func, const char *tname, struct btf_func_model *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81317b90)
Location: kernel/bpf/btf.c:6445
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:add_kfunc_call
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
```
**Symbols:**

```
ffffffff81317b90-ffffffff81317e94: btf_distill_func_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int btf_distill_func_proto(struct bpf_verifier_log *log, struct btf *btf, const struct btf_type *func, const char *tname, struct btf_func_model *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81347a90)
Location: kernel/bpf/btf.c:6545
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:add_kfunc_call
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
```
**Symbols:**

```
ffffffff81347a90-ffffffff81347e28: btf_distill_func_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int btf_distill_func_proto(struct bpf_verifier_log *log, struct btf *btf, const struct btf_type *func, const char *tname, struct btf_func_model *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8136df00)
Location: kernel/bpf/btf.c:6717
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:add_kfunc_call
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
```
**Symbols:**

```
ffffffff8136df00-ffffffff8136e298: btf_distill_func_proto (STB_GLOBAL)
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
