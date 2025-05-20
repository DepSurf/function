# Function: <code>__process_kf_arg_ptr_to_graph_node</code>

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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __process_kf_arg_ptr_to_graph_node(struct bpf_verifier_env *env, struct bpf_reg_state *reg, u32 regno, struct bpf_kfunc_call_arg_meta *meta, enum btf_field_type head_field_type, enum btf_field_type node_field_type, struct btf_field **node_field);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8130fde0)
Location: kernel/bpf/verifier.c:10577
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_kfunc_args
```
**Symbols:**

```
ffffffff8130fde0-ffffffff813100c5: __process_kf_arg_ptr_to_graph_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __process_kf_arg_ptr_to_graph_node(struct bpf_verifier_env *env, struct bpf_reg_state *reg, u32 regno, struct bpf_kfunc_call_arg_meta *meta, enum btf_field_type head_field_type, enum btf_field_type node_field_type, struct btf_field **node_field);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81331d90)
Location: kernel/bpf/verifier.c:11386
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_kfunc_args
```
**Symbols:**

```
ffffffff81331d90-ffffffff81332078: __process_kf_arg_ptr_to_graph_node (STB_LOCAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
