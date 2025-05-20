# Function: <code>__register_btf_kfunc_id_set</code>

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
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int __register_btf_kfunc_id_set(enum btf_kfunc_hook hook, const struct btf_kfunc_id_set *kset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81313c60)
Location: kernel/bpf/btf.c:7626
Inline: True
Direct callers:
  - kernel/bpf/btf.c:register_btf_fmodret_id_set
  - kernel/bpf/btf.c:register_btf_kfunc_id_set
```
**Symbols:**

```
ffffffff81313c60-ffffffff81313ce9: __register_btf_kfunc_id_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __register_btf_kfunc_id_set(enum btf_kfunc_hook hook, const struct btf_kfunc_id_set *kset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81343910)
Location: kernel/bpf/btf.c:7880
Inline: False
Direct callers:
  - kernel/bpf/btf.c:register_btf_fmodret_id_set
  - kernel/bpf/btf.c:register_btf_kfunc_id_set
```
**Symbols:**

```
ffffffff81343910-ffffffff81343af9: __register_btf_kfunc_id_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __register_btf_kfunc_id_set(enum btf_kfunc_hook hook, const struct btf_kfunc_id_set *kset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff813698a0)
Location: kernel/bpf/btf.c:7945
Inline: False
Direct callers:
  - kernel/bpf/btf.c:register_btf_fmodret_id_set
  - kernel/bpf/btf.c:register_btf_kfunc_id_set
```
**Symbols:**

```
ffffffff813698a0-ffffffff81369a89: __register_btf_kfunc_id_set (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
