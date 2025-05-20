# Function: <code>bpf_struct_ops_prepare_trampoline</code>

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
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int bpf_struct_ops_prepare_trampoline(struct bpf_tramp_links *tlinks, struct bpf_tramp_link *link, const struct btf_func_model *model, void *image, void *image_end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_struct_ops.c (ffffffff812c6d41)
Location: kernel/bpf/bpf_struct_ops.c:335
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
Direct callers:
  - net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run
```
**Symbols:**

```
ffffffff812c7490-ffffffff812c74e4: bpf_struct_ops_prepare_trampoline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int bpf_struct_ops_prepare_trampoline(struct bpf_tramp_links *tlinks, struct bpf_tramp_link *link, const struct btf_func_model *model, void *image, void *image_end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_struct_ops.c (ffffffff8132c5a0)
Location: kernel/bpf/bpf_struct_ops.c:335
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
Direct callers:
  - net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run
```
**Symbols:**

```
ffffffff8132ce50-ffffffff8132cea4: bpf_struct_ops_prepare_trampoline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int bpf_struct_ops_prepare_trampoline(struct bpf_tramp_links *tlinks, struct bpf_tramp_link *link, const struct btf_func_model *model, void *image, void *image_end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_struct_ops.c (ffffffff8135cb60)
Location: kernel/bpf/bpf_struct_ops.c:352
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
Direct callers:
  - net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run
```
**Symbols:**

```
ffffffff8135d2a0-ffffffff8135d2f4: bpf_struct_ops_prepare_trampoline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_struct_ops_prepare_trampoline(struct bpf_tramp_links *tlinks, struct bpf_tramp_link *link, const struct btf_func_model *model, void *stub_func, void *image, void *image_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_struct_ops.c (ffffffff813859b0)
Location: kernel/bpf/bpf_struct_ops.c:352
Inline: False
Direct callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run
```
**Symbols:**

```
ffffffff813859b0-ffffffff81385a5a: bpf_struct_ops_prepare_trampoline (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>void *stub_func</code>
</li>
<li>
<b>Param reordered. </b>
<code>tlinks, link, model, image, image_end</code> ➡️ <code>tlinks, link, model, stub_func, image, image_end</code>
</li>
</ul>
</details>
</li>
</ul>
