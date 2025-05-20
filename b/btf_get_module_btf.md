# Function: <code>btf_get_module_btf</code>

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
struct btf *btf_get_module_btf(const struct module *module);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812ac790)
Location: kernel/bpf/btf.c:6917
Inline: True
Direct callers:
  - kernel/bpf/btf.c:register_btf_id_dtor_kfuncs
```
**Symbols:**

```
ffffffff812ac790-ffffffff812ac88c: btf_get_module_btf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct btf *btf_get_module_btf(const struct module *module);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8130c2f0)
Location: kernel/bpf/btf.c:7396
Inline: True
Direct callers:
  - kernel/bpf/btf.c:register_btf_id_dtor_kfuncs
```
**Symbols:**

```
ffffffff8130c2f0-ffffffff8130c3ec: btf_get_module_btf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct btf *btf_get_module_btf(const struct module *module);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8133b690)
Location: kernel/bpf/btf.c:7498
Inline: True
Direct callers:
  - kernel/bpf/btf.c:register_btf_id_dtor_kfuncs
  - kernel/bpf/btf.c:__register_btf_kfunc_id_set
```
**Symbols:**

```
ffffffff8133b690-ffffffff8133b78c: btf_get_module_btf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct btf *btf_get_module_btf(const struct module *module);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81361850)
Location: kernel/bpf/btf.c:7562
Inline: True
Direct callers:
  - kernel/bpf/btf.c:register_btf_id_dtor_kfuncs
  - kernel/bpf/btf.c:__register_btf_kfunc_id_set
```
**Symbols:**

```
ffffffff81361850-ffffffff8136194c: btf_get_module_btf (STB_LOCAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
