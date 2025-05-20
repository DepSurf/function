# Function: <code>check_reg_type</code>

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
int check_reg_type(struct bpf_verifier_env *env, u32 regno, enum bpf_arg_type arg_type, const u32 *arg_btf_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8120a1c0)
Location: kernel/bpf/verifier.c:4090
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
```
**Symbols:**

```
ffffffff8120a1c0-ffffffff8120a3cc: check_reg_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int check_reg_type(struct bpf_verifier_env *env, u32 regno, enum bpf_arg_type arg_type, const u32 *arg_btf_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8120c6e0)
Location: kernel/bpf/verifier.c:4800
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
```
**Symbols:**

```
ffffffff8120c6e0-ffffffff8120c8ec: check_reg_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int check_reg_type(struct bpf_verifier_env *env, u32 regno, enum bpf_arg_type arg_type, const u32 *arg_btf_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812406d0)
Location: kernel/bpf/verifier.c:4964
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
```
**Symbols:**

```
ffffffff812406d0-ffffffff81240aaf: check_reg_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int check_reg_type(struct bpf_verifier_env *env, u32 regno, enum bpf_arg_type arg_type, const u32 *arg_btf_id, struct bpf_call_arg_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81285b80)
Location: kernel/bpf/verifier.c:5699
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
```
**Symbols:**

```
ffffffff81285b80-ffffffff81285eff: check_reg_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int check_reg_type(struct bpf_verifier_env *env, u32 regno, enum bpf_arg_type arg_type, const u32 *arg_btf_id, struct bpf_call_arg_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812dca60)
Location: kernel/bpf/verifier.c:6389
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
```
**Symbols:**

```
ffffffff812dca60-ffffffff812dce57: check_reg_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int check_reg_type(struct bpf_verifier_env *env, u32 regno, enum bpf_arg_type arg_type, const u32 *arg_btf_id, struct bpf_call_arg_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81300da0)
Location: kernel/bpf/verifier.c:7631
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
```
**Symbols:**

```
ffffffff81300da0-ffffffff81301307: check_reg_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int check_reg_type(struct bpf_verifier_env *env, u32 regno, enum bpf_arg_type arg_type, const u32 *arg_btf_id, struct bpf_call_arg_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8131e8d0)
Location: kernel/bpf/verifier.c:8130
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
```
**Symbols:**

```
ffffffff8131e8d0-ffffffff8131ee51: check_reg_type (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bpf_call_arg_meta *meta</code>
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
