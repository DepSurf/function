# Function: <code>bpf_dummy_ops_btf_struct_access</code>

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
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_dummy_ops_btf_struct_access(struct bpf_verifier_log *log, const struct btf *btf, const struct btf_type *t, int off, int size, enum bpf_access_type atype, u32 *next_btf_id, enum bpf_type_flag *flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/bpf_dummy_struct_ops.c (ffffffff81cb6730)
Location: net/bpf/bpf_dummy_struct_ops.c:158
Inline: False
```
**Symbols:**

```
ffffffff81cb6730-ffffffff81cb67e9: bpf_dummy_ops_btf_struct_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_dummy_ops_btf_struct_access(struct bpf_verifier_log *log, const struct bpf_reg_state *reg, int off, int size, enum bpf_access_type atype, u32 *next_btf_id, enum bpf_type_flag *flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/bpf_dummy_struct_ops.c (ffffffff81e74c70)
Location: net/bpf/bpf_dummy_struct_ops.c:157
Inline: False
```
**Symbols:**

```
ffffffff81e74c70-ffffffff81e74d40: bpf_dummy_ops_btf_struct_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_dummy_ops_btf_struct_access(struct bpf_verifier_log *log, const struct bpf_reg_state *reg, int off, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/bpf_dummy_struct_ops.c (ffffffff81ed0df0)
Location: net/bpf/bpf_dummy_struct_ops.c:174
Inline: False
```
**Symbols:**

```
ffffffff81ed0df0-ffffffff81ed0eab: bpf_dummy_ops_btf_struct_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_dummy_ops_btf_struct_access(struct bpf_verifier_log *log, const struct bpf_reg_state *reg, int off, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/bpf_dummy_struct_ops.c (ffffffff81f947b0)
Location: net/bpf/bpf_dummy_struct_ops.c:179
Inline: False
```
**Symbols:**

```
ffffffff81f947b0-ffffffff81f9486b: bpf_dummy_ops_btf_struct_access (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct bpf_reg_state *reg</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct btf *btf</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct btf_type *t</code>
</li>
<li>
<b>Param reordered. </b>
<code>log, btf, t, off, size, atype, next_btf_id, flag</code> ➡️ <code>log, reg, off, size, atype, next_btf_id, flag</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>enum bpf_access_type atype</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 *next_btf_id</code>
</li>
<li>
<b>Param removed. </b>
<code>enum bpf_type_flag *flag</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
