# Function: <code>btf_free_kfunc_set_tab</code>

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
void btf_free_kfunc_set_tab(struct btf *btf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:1607
Inline: False
Direct callers:
  - kernel/bpf/btf.c:__btf_populate_kfunc_set
  - kernel/bpf/btf.c:btf_free
```
**Symbols:**

```
ffffffff812abd30-ffffffff812abde2: btf_free_kfunc_set_tab (STB_LOCAL)
ffffffff81e6a68c-ffffffff81e6a6a0: btf_free_kfunc_set_tab.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void btf_free_kfunc_set_tab(struct btf *btf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:1610
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_populate_kfunc_set
  - kernel/bpf/btf.c:btf_free
```
**Symbols:**

```
ffffffff8130b8d0-ffffffff8130b957: btf_free_kfunc_set_tab (STB_LOCAL)
ffffffff8206181e-ffffffff82061832: btf_free_kfunc_set_tab.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void btf_free_kfunc_set_tab(struct btf *btf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:1642
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_populate_kfunc_set
  - kernel/bpf/btf.c:btf_free
```
**Symbols:**

```
ffffffff8133a920-ffffffff8133a9b5: btf_free_kfunc_set_tab (STB_LOCAL)
ffffffff820e0ec4-ffffffff820e0ed8: btf_free_kfunc_set_tab.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void btf_free_kfunc_set_tab(struct btf *btf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:1643
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_populate_kfunc_set
  - kernel/bpf/btf.c:btf_free
```
**Symbols:**

```
ffffffff81360a50-ffffffff81360ae5: btf_free_kfunc_set_tab (STB_LOCAL)
ffffffff821bd70c-ffffffff821bd720: btf_free_kfunc_set_tab.cold (STB_LOCAL)
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
