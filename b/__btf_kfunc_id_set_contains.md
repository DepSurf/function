# Function: <code>__btf_kfunc_id_set_contains</code>

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
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812b7fde)
Location: kernel/bpf/btf.c:7095
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_kfunc_id_set_contains
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8131ac7b)
Location: kernel/bpf/btf.c:7557
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_kfunc_is_modify_return
  - kernel/bpf/btf.c:btf_kfunc_id_set_contains
  - kernel/bpf/btf.c:btf_kfunc_id_set_contains
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u32 *__btf_kfunc_id_set_contains(const struct btf *btf, enum btf_kfunc_hook hook, u32 kfunc_btf_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81339020)
Location: kernel/bpf/btf.c:7787
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_kfunc_is_modify_return
  - kernel/bpf/btf.c:btf_kfunc_id_set_contains
  - kernel/bpf/btf.c:btf_kfunc_id_set_contains
```
**Symbols:**

```
ffffffff81339020-ffffffff81339184: __btf_kfunc_id_set_contains (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u32 *__btf_kfunc_id_set_contains(const struct btf *btf, enum btf_kfunc_hook hook, u32 kfunc_btf_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8135f150)
Location: kernel/bpf/btf.c:7851
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_kfunc_is_modify_return
  - kernel/bpf/btf.c:btf_kfunc_id_set_contains
  - kernel/bpf/btf.c:btf_kfunc_id_set_contains
```
**Symbols:**

```
ffffffff8135f150-ffffffff8135f2b4: __btf_kfunc_id_set_contains (STB_LOCAL)
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
