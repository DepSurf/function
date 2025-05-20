# Function: <code>register_btf_id_dtor_kfuncs</code>

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
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int register_btf_id_dtor_kfuncs(const struct btf_id_dtor_kfunc *dtors, u32 add_cnt, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:7232
Inline: False
Direct callers:
  - net/bpf/test_run.c:bpf_prog_test_run_init
```
**Symbols:**

```
ffffffff81e6a7fc-ffffffff81e6a857: register_btf_id_dtor_kfuncs.cold (STB_LOCAL)
ffffffff812b3890-ffffffff812b3c06: register_btf_id_dtor_kfuncs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int register_btf_id_dtor_kfuncs(const struct btf_id_dtor_kfunc *dtors, u32 add_cnt, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:7725
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:kfunc_init
  - net/bpf/test_run.c:bpf_prog_test_run_init
```
**Symbols:**

```
ffffffff820618f5-ffffffff8206190a: register_btf_id_dtor_kfuncs.cold (STB_LOCAL)
ffffffff81313d70-ffffffff813140eb: register_btf_id_dtor_kfuncs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int register_btf_id_dtor_kfuncs(const struct btf_id_dtor_kfunc *dtors, u32 add_cnt, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:7986
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:kfunc_init
  - kernel/bpf/cpumask.c:cpumask_kfunc_init
  - net/bpf/test_run.c:bpf_prog_test_run_init
```
**Symbols:**

```
ffffffff820e0fab-ffffffff820e0fc0: register_btf_id_dtor_kfuncs.cold (STB_LOCAL)
ffffffff81343b80-ffffffff81343f56: register_btf_id_dtor_kfuncs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int register_btf_id_dtor_kfuncs(const struct btf_id_dtor_kfunc *dtors, u32 add_cnt, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:8051
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:kfunc_init
  - kernel/bpf/cpumask.c:cpumask_kfunc_init
  - net/bpf/test_run.c:bpf_prog_test_run_init
```
**Symbols:**

```
ffffffff821bd7f3-ffffffff821bd808: register_btf_id_dtor_kfuncs.cold (STB_LOCAL)
ffffffff81369b10-ffffffff81369ee6: register_btf_id_dtor_kfuncs (STB_GLOBAL)
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
