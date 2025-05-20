# Function: <code>env_stack_push</code>

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
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int env_stack_push(struct btf_verifier_env *env, const struct btf_type *t, u32 type_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811c7810)
Location: kernel/bpf/btf.c:762
Inline: True
Direct callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
```
**Symbols:**

```
ffffffff811c7810-ffffffff811c78a2: env_stack_push (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int env_stack_push(struct btf_verifier_env *env, const struct btf_type *t, u32 type_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811dabb0)
Location: kernel/bpf/btf.c:894
Inline: True
Direct callers:
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
```
**Symbols:**

```
ffffffff811dabb0-ffffffff811dac42: env_stack_push (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int env_stack_push(struct btf_verifier_env *env, const struct btf_type *t, u32 type_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811ef9e0)
Location: kernel/bpf/btf.c:995
Inline: True
Direct callers:
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
```
**Symbols:**

```
ffffffff811ef9e0-ffffffff811efa83: env_stack_push (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int env_stack_push(struct btf_verifier_env *env, const struct btf_type *t, u32 type_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811fc100)
Location: kernel/bpf/btf.c:995
Inline: True
Direct callers:
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
```
**Symbols:**

```
ffffffff811fc100-ffffffff811fc1a3: env_stack_push (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int env_stack_push(struct btf_verifier_env *env, const struct btf_type *t, u32 type_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8121fad0)
Location: kernel/bpf/btf.c:1023
Inline: True
Direct callers:
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
```
**Symbols:**

```
ffffffff8121fad0-ffffffff8121fb73: env_stack_push (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int env_stack_push(struct btf_verifier_env *env, const struct btf_type *t, u32 type_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81223140)
Location: kernel/bpf/btf.c:1617
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
```
**Symbols:**

```
ffffffff81223140-ffffffff812231ef: env_stack_push (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int env_stack_push(struct btf_verifier_env *env, const struct btf_type *t, u32 type_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81227be0)
Location: kernel/bpf/btf.c:1618
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
```
**Symbols:**

```
ffffffff81227be0-ffffffff81227c92: env_stack_push (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int env_stack_push(struct btf_verifier_env *env, const struct btf_type *t, u32 type_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8125fe70)
Location: kernel/bpf/btf.c:1618
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
```
**Symbols:**

```
ffffffff8125fe70-ffffffff8125ff82: env_stack_push (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int env_stack_push(struct btf_verifier_env *env, const struct btf_type *t, u32 type_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812aa690)
Location: kernel/bpf/btf.c:1746
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_decl_tag_resolve
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
```
**Symbols:**

```
ffffffff812aa690-ffffffff812aa7a7: env_stack_push (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int env_stack_push(struct btf_verifier_env *env, const struct btf_type *t, u32 type_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81309e40)
Location: kernel/bpf/btf.c:1769
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_decl_tag_resolve
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
```
**Symbols:**

```
ffffffff81309e40-ffffffff81309f57: env_stack_push (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int env_stack_push(struct btf_verifier_env *env, const struct btf_type *t, u32 type_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81338c80)
Location: kernel/bpf/btf.c:1799
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_decl_tag_resolve
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
```
**Symbols:**

```
ffffffff81338c80-ffffffff81338da6: env_stack_push (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int env_stack_push(struct btf_verifier_env *env, const struct btf_type *t, u32 type_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8135edb0)
Location: kernel/bpf/btf.c:1800
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_decl_tag_resolve
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
```
**Symbols:**

```
ffffffff8135edb0-ffffffff8135eed6: env_stack_push (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int env_stack_push(struct btf_verifier_env *env, const struct btf_type *t, u32 type_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffff8000102825f0)
Location: kernel/bpf/btf.c:995
Inline: True
Direct callers:
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
```
**Symbols:**

```
ffff8000102825f0-ffff8000102826c4: env_stack_push (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int env_stack_push(struct btf_verifier_env *env, const struct btf_type *t, u32 type_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (c04b222c)
Location: kernel/bpf/btf.c:995
Inline: True
Direct callers:
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
```
**Symbols:**

```
c04b222c-c04b22e4: env_stack_push (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int env_stack_push(struct btf_verifier_env *env, const struct btf_type *t, u32 type_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (c00000000032cc90)
Location: kernel/bpf/btf.c:995
Inline: True
Direct callers:
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
```
**Symbols:**

```
c00000000032cc90-c00000000032cd50: env_stack_push (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int env_stack_push(struct btf_verifier_env *env, const struct btf_type *t, u32 type_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffe0001b86a4)
Location: kernel/bpf/btf.c:995
Inline: True
Direct callers:
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
```
**Symbols:**

```
ffffffe0001b86a4-ffffffe0001b8760: env_stack_push (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int env_stack_push(struct btf_verifier_env *env, const struct btf_type *t, u32 type_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811f4720)
Location: kernel/bpf/btf.c:995
Inline: True
Direct callers:
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
```
**Symbols:**

```
ffffffff811f4720-ffffffff811f47c3: env_stack_push (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int env_stack_push(struct btf_verifier_env *env, const struct btf_type *t, u32 type_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811e7470)
Location: kernel/bpf/btf.c:995
Inline: True
Direct callers:
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
```
**Symbols:**

```
ffffffff811e7470-ffffffff811e7513: env_stack_push (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int env_stack_push(struct btf_verifier_env *env, const struct btf_type *t, u32 type_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811f24f0)
Location: kernel/bpf/btf.c:995
Inline: True
Direct callers:
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
```
**Symbols:**

```
ffffffff811f24f0-ffffffff811f2593: env_stack_push (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int env_stack_push(struct btf_verifier_env *env, const struct btf_type *t, u32 type_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81200a00)
Location: kernel/bpf/btf.c:995
Inline: True
Direct callers:
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
```
**Symbols:**

```
ffffffff81200a00-ffffffff81200aa3: env_stack_push (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
