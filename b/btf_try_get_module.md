# Function: <code>btf_try_get_module</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct module *btf_try_get_module(const struct btf *btf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81231b40)
Location: kernel/bpf/btf.c:6079
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_pseudo_btf_id
```
**Symbols:**

```
ffffffff81231b40-ffffffff81231bb5: btf_try_get_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct module *btf_try_get_module(const struct btf *btf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8126ab00)
Location: kernel/bpf/btf.c:6132
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_pseudo_btf_id
```
**Symbols:**

```
ffffffff8126ab00-ffffffff8126ab75: btf_try_get_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct module *btf_try_get_module(const struct btf *btf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812b7990)
Location: kernel/bpf/btf.c:6887
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:__find_kfunc_desc_btf
  - kernel/bpf/btf.c:btf_parse_kptrs
```
**Symbols:**

```
ffffffff812b7990-ffffffff812b7a12: btf_try_get_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct module *btf_try_get_module(const struct btf *btf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81318fe0)
Location: kernel/bpf/btf.c:7366
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:__find_kfunc_desc_btf
  - kernel/bpf/btf.c:btf_parse_fields
```
**Symbols:**

```
ffffffff81318fe0-ffffffff81319062: btf_try_get_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct module *btf_try_get_module(const struct btf *btf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81348e00)
Location: kernel/bpf/btf.c:7468
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:__find_kfunc_desc_btf
  - kernel/bpf/btf.c:btf_parse_kptr
```
**Symbols:**

```
ffffffff81348e00-ffffffff81348e82: btf_try_get_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct module *btf_try_get_module(const struct btf *btf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8136f530)
Location: kernel/bpf/btf.c:7532
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:__find_kfunc_desc_btf
  - kernel/bpf/btf.c:btf_parse_kptr
```
**Symbols:**

```
ffffffff8136f530-ffffffff8136f5b2: btf_try_get_module (STB_GLOBAL)
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
