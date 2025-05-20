# Function: <code>btf_is_module</code>

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
bool btf_is_module(const struct btf *btf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81231ad0)
Location: kernel/bpf/btf.c:5939
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_pseudo_btf_id
```
**Symbols:**

```
ffffffff81231ad0-ffffffff81231afc: btf_is_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool btf_is_module(const struct btf *btf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812666b5)
Location: kernel/bpf/btf.c:5992
Inline: True
Inline callers:
  - kernel/bpf/btf.c:bpf_btf_find_by_name_kind
Direct callers:
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_pseudo_btf_id
```
**Symbols:**

```
ffffffff81cb95b2-ffffffff81cb95cd: btf_is_module.cold (STB_LOCAL)
ffffffff8126aa70-ffffffff8126aab3: btf_is_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool btf_is_module(const struct btf *btf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812b3a3b)
Location: kernel/bpf/btf.c:6725
Inline: True
Inline callers:
  - kernel/bpf/btf.c:register_btf_id_dtor_kfuncs
  - kernel/bpf/btf.c:bpf_btf_find_by_name_kind
  - kernel/bpf/btf.c:btf_parse_kptrs
  - kernel/bpf/btf.c:btf_free_kfunc_set_tab
  - kernel/bpf/btf.c:bpf_find_btf_id
Direct callers:
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:__find_kfunc_desc_btf
```
**Symbols:**

```
ffffffff81e6a92f-ffffffff81e6a94a: btf_is_module.cold (STB_LOCAL)
ffffffff812b78f0-ffffffff812b793b: btf_is_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool btf_is_module(const struct btf *btf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81313f1b)
Location: kernel/bpf/btf.c:7216
Inline: True
Inline callers:
  - kernel/bpf/btf.c:register_btf_id_dtor_kfuncs
  - kernel/bpf/btf.c:btf_populate_kfunc_set
  - kernel/bpf/btf.c:bpf_btf_find_by_name_kind
  - kernel/bpf/btf.c:btf_parse_fields
  - kernel/bpf/btf.c:btf_free_kfunc_set_tab
  - kernel/bpf/btf.c:bpf_find_btf_id
Direct callers:
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:__find_kfunc_desc_btf
```
**Symbols:**

```
ffffffff82061a0d-ffffffff82061a28: btf_is_module.cold (STB_LOCAL)
ffffffff81318f80-ffffffff81318fcb: btf_is_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool btf_is_module(const struct btf *btf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81343d36)
Location: kernel/bpf/btf.c:7315
Inline: True
Inline callers:
  - kernel/bpf/btf.c:register_btf_id_dtor_kfuncs
  - kernel/bpf/btf.c:btf_populate_kfunc_set
  - kernel/bpf/btf.c:bpf_btf_find_by_name_kind
  - kernel/bpf/btf.c:btf_parse_kptr
  - kernel/bpf/btf.c:btf_free_kfunc_set_tab
  - kernel/bpf/btf.c:bpf_find_btf_id
Direct callers:
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:__find_kfunc_desc_btf
```
**Symbols:**

```
ffffffff820e10c3-ffffffff820e10de: btf_is_module.cold (STB_LOCAL)
ffffffff81348da0-ffffffff81348deb: btf_is_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool btf_is_module(const struct btf *btf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81369cc6)
Location: kernel/bpf/btf.c:7379
Inline: True
Inline callers:
  - kernel/bpf/btf.c:register_btf_id_dtor_kfuncs
  - kernel/bpf/btf.c:btf_populate_kfunc_set
  - kernel/bpf/btf.c:bpf_btf_find_by_name_kind
  - kernel/bpf/btf.c:btf_parse_kptr
  - kernel/bpf/btf.c:btf_free_kfunc_set_tab
  - kernel/bpf/btf.c:bpf_find_btf_id
Direct callers:
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:__find_kfunc_desc_btf
```
**Symbols:**

```
ffffffff821bd8d0-ffffffff821bd8eb: btf_is_module.cold (STB_LOCAL)
ffffffff8136f4d0-ffffffff8136f51b: btf_is_module (STB_GLOBAL)
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
