# Function: <code>btf_struct_access</code>

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
int btf_struct_access(struct bpf_verifier_log *log, const struct btf_type *t, int off, int size, enum bpf_access_type atype, u32 *next_btf_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81224f50)
Location: kernel/bpf/btf.c:3832
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_ptr_to_btf_access
  - kernel/bpf/btf.c:btf_struct_access
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_btf_struct_access
```
**Symbols:**

```
ffffffff81224f50-ffffffff812253c4: btf_struct_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int btf_struct_access(struct bpf_verifier_log *log, const struct btf *btf, const struct btf_type *t, int off, int size, enum bpf_access_type atype, u32 *next_btf_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8122b9f0)
Location: kernel/bpf/btf.c:4985
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_ptr_to_map_access
  - kernel/bpf/verifier.c:check_ptr_to_btf_access
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_btf_struct_access
```
**Symbols:**

```
ffffffff8122b9f0-ffffffff8122badf: btf_struct_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int btf_struct_access(struct bpf_verifier_log *log, const struct btf *btf, const struct btf_type *t, int off, int size, enum bpf_access_type atype, u32 *next_btf_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812303f0)
Location: kernel/bpf/btf.c:5058
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_ptr_to_map_access
  - kernel/bpf/verifier.c:check_ptr_to_btf_access
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_btf_struct_access
```
**Symbols:**

```
ffffffff812303f0-ffffffff812304df: btf_struct_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int btf_struct_access(struct bpf_verifier_log *log, const struct btf *btf, const struct btf_type *t, int off, int size, enum bpf_access_type atype, u32 *next_btf_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:5111
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_ptr_to_map_access
  - kernel/bpf/verifier.c:check_ptr_to_btf_access
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_btf_struct_access
```
**Symbols:**

```
ffffffff81cb94e2-ffffffff81cb94f6: btf_struct_access.cold (STB_LOCAL)
ffffffff81269170-ffffffff8126925d: btf_struct_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int btf_struct_access(struct bpf_verifier_log *log, const struct btf *btf, const struct btf_type *t, int off, int size, enum bpf_access_type atype, u32 *next_btf_id, enum bpf_type_flag *flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:5656
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_ptr_to_map_access
  - kernel/bpf/verifier.c:check_ptr_to_btf_access
  - net/bpf/bpf_dummy_struct_ops.c:bpf_dummy_ops_btf_struct_access
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_btf_struct_access
```
**Symbols:**

```
ffffffff81e6a8a0-ffffffff81e6a8b4: btf_struct_access.cold (STB_LOCAL)
ffffffff812b65e0-ffffffff812b6720: btf_struct_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int btf_struct_access(struct bpf_verifier_log *log, const struct bpf_reg_state *reg, int off, int size, enum bpf_access_type atype, u32 *next_btf_id, enum bpf_type_flag *flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:6295
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_ptr_to_map_access
  - kernel/bpf/verifier.c:check_ptr_to_btf_access
  - net/bpf/bpf_dummy_struct_ops.c:bpf_dummy_ops_btf_struct_access
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_btf_struct_access
```
**Symbols:**

```
ffffffff82061944-ffffffff82061958: btf_struct_access.cold (STB_LOCAL)
ffffffff813175a0-ffffffff81317886: btf_struct_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int btf_struct_access(struct bpf_verifier_log *log, const struct bpf_reg_state *reg, int off, int size, enum bpf_access_type atype, u32 *next_btf_id, enum bpf_type_flag *flag, const char **field_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:6382
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_ptr_to_map_access
  - kernel/bpf/verifier.c:check_ptr_to_btf_access
```
**Symbols:**

```
ffffffff820e0ffa-ffffffff820e100e: btf_struct_access.cold (STB_LOCAL)
ffffffff81347450-ffffffff81347787: btf_struct_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int btf_struct_access(struct bpf_verifier_log *log, const struct bpf_reg_state *reg, int off, int size, enum bpf_access_type atype, u32 *next_btf_id, enum bpf_type_flag *flag, const char **field_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:6554
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_ptr_to_map_access
  - kernel/bpf/verifier.c:check_ptr_to_btf_access
```
**Symbols:**

```
ffffffff821bd842-ffffffff821bd856: btf_struct_access.cold (STB_LOCAL)
ffffffff8136d890-ffffffff8136dbf7: btf_struct_access (STB_GLOBAL)
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
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct btf *btf</code>
</li>
<li>
<b>Param reordered. </b>
<code>log, t, off, size, atype, next_btf_id</code> ➡️ <code>log, btf, t, off, size, atype, next_btf_id</code>
</li>
</ul>
</details>
</li>
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
<code>enum bpf_type_flag *flag</code>
</li>
</ul>
</details>
</li>
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
<b>Param added. </b>
<code>const char **field_name</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
