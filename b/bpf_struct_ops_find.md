# Function: <code>bpf_struct_ops_find</code>

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
const struct bpf_struct_ops *bpf_struct_ops_find(u32 type_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_struct_ops.c (ffffffff81230010)
Location: kernel/bpf/bpf_struct_ops.c:216
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_struct_ops_btf_id
```
**Symbols:**

```
ffffffff81230010-ffffffff81230045: bpf_struct_ops_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const struct bpf_struct_ops *bpf_struct_ops_find(u32 type_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_struct_ops.c (ffffffff812384c0)
Location: kernel/bpf/bpf_struct_ops.c:216
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_struct_ops_btf_id
```
**Symbols:**

```
ffffffff812384c0-ffffffff812384f5: bpf_struct_ops_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const struct bpf_struct_ops *bpf_struct_ops_find(u32 type_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_struct_ops.c (ffffffff8123ccb0)
Location: kernel/bpf/bpf_struct_ops.c:216
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_struct_ops_btf_id
```
**Symbols:**

```
ffffffff8123ccb0-ffffffff8123cce5: bpf_struct_ops_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const struct bpf_struct_ops *bpf_struct_ops_find(u32 type_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_struct_ops.c (ffffffff81277730)
Location: kernel/bpf/bpf_struct_ops.c:217
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_struct_ops_btf_id
```
**Symbols:**

```
ffffffff81277730-ffffffff81277765: bpf_struct_ops_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const struct bpf_struct_ops *bpf_struct_ops_find(u32 type_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_struct_ops.c (ffffffff812c7310)
Location: kernel/bpf/bpf_struct_ops.c:221
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_struct_ops_btf_id
```
**Symbols:**

```
ffffffff812c7310-ffffffff812c7371: bpf_struct_ops_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const struct bpf_struct_ops *bpf_struct_ops_find(u32 type_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_struct_ops.c (ffffffff8132cca0)
Location: kernel/bpf/bpf_struct_ops.c:221
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_struct_ops_btf_id
```
**Symbols:**

```
ffffffff8132cca0-ffffffff8132cd01: bpf_struct_ops_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const struct bpf_struct_ops *bpf_struct_ops_find(u32 type_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_struct_ops.c (ffffffff8135d0e0)
Location: kernel/bpf/bpf_struct_ops.c:230
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_struct_ops_btf_id
```
**Symbols:**

```
ffffffff8135d0e0-ffffffff8135d141: bpf_struct_ops_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const struct bpf_struct_ops *bpf_struct_ops_find(u32 type_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_struct_ops.c (ffffffff813857f0)
Location: kernel/bpf/bpf_struct_ops.c:230
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_struct_ops_btf_id
```
**Symbols:**

```
ffffffff813857f0-ffffffff81385851: bpf_struct_ops_find (STB_GLOBAL)
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
