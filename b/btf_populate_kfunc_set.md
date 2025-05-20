# Function: <code>btf_populate_kfunc_set</code>

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
In kernel/bpf/btf.c (ffffffff812b37ec)
Location: kernel/bpf/btf.c:7078
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int btf_populate_kfunc_set(struct btf *btf, enum btf_kfunc_hook hook, struct btf_id_set8 *add_set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:7469
Inline: False
```
**Symbols:**

```
ffffffff8130bfa0-ffffffff8130c13f: btf_populate_kfunc_set (STB_LOCAL)
ffffffff82061832-ffffffff82061846: btf_populate_kfunc_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int btf_populate_kfunc_set(struct btf *btf, enum btf_kfunc_hook hook, const struct btf_kfunc_id_set *kset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:7673
Inline: False
Direct callers:
  - kernel/bpf/btf.c:__register_btf_kfunc_id_set
```
**Symbols:**

```
ffffffff8133b090-ffffffff8133b565: btf_populate_kfunc_set (STB_LOCAL)
ffffffff820e0ed8-ffffffff820e0efc: btf_populate_kfunc_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int btf_populate_kfunc_set(struct btf *btf, enum btf_kfunc_hook hook, const struct btf_kfunc_id_set *kset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:7737
Inline: False
Direct callers:
  - kernel/bpf/btf.c:__register_btf_kfunc_id_set
```
**Symbols:**

```
ffffffff81361220-ffffffff8136172c: btf_populate_kfunc_set (STB_LOCAL)
ffffffff821bd720-ffffffff821bd744: btf_populate_kfunc_set.cold (STB_LOCAL)
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
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct btf_kfunc_id_set *kset</code>
</li>
<li>
<b>Param removed. </b>
<code>struct btf_id_set8 *add_set</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
