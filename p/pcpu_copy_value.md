# Function: <code>pcpu_copy_value</code>

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
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void pcpu_copy_value(struct bpf_htab *htab, void *pptr, void *value, bool onallcpus);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81193460)
Location: kernel/bpf/hashtab.c:555
Inline: True
Direct callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
**Symbols:**

```
ffffffff81193460-ffffffff81193541: pcpu_copy_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void pcpu_copy_value(struct bpf_htab *htab, void *pptr, void *value, bool onallcpus);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8119a690)
Location: kernel/bpf/hashtab.c:637
Inline: True
Direct callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
**Symbols:**

```
ffffffff8119a690-ffffffff8119a76b: pcpu_copy_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void pcpu_copy_value(struct bpf_htab *htab, void *pptr, void *value, bool onallcpus);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811a9ea0)
Location: kernel/bpf/hashtab.c:669
Inline: True
Direct callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
**Symbols:**

```
ffffffff811a9ea0-ffffffff811a9f59: pcpu_copy_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void pcpu_copy_value(struct bpf_htab *htab, void *pptr, void *value, bool onallcpus);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811c1440)
Location: kernel/bpf/hashtab.c:683
Inline: True
Direct callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
**Symbols:**

```
ffffffff811c1440-ffffffff811c14f7: pcpu_copy_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void pcpu_copy_value(struct bpf_htab *htab, void *pptr, void *value, bool onallcpus);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811d2ca0)
Location: kernel/bpf/hashtab.c:697
Inline: True
Direct callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
**Symbols:**

```
ffffffff811d2ca0-ffffffff811d2d57: pcpu_copy_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void pcpu_copy_value(struct bpf_htab *htab, void *pptr, void *value, bool onallcpus);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811e7400)
Location: kernel/bpf/hashtab.c:697
Inline: True
Direct callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
**Symbols:**

```
ffffffff811e7400-ffffffff811e74c2: pcpu_copy_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void pcpu_copy_value(struct bpf_htab *htab, void *pptr, void *value, bool onallcpus);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811f3b60)
Location: kernel/bpf/hashtab.c:697
Inline: True
Direct callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
**Symbols:**

```
ffffffff811f3b60-ffffffff811f3c22: pcpu_copy_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81217a20)
Location: kernel/bpf/hashtab.c:806
Inline: True
Direct callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
**Symbols:**

```
ffffffff81217a20-ffffffff81217ae4: pcpu_copy_value.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81219c10)
Location: kernel/bpf/hashtab.c:827
Inline: True
Direct callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
**Symbols:**

```
ffffffff81219c10-ffffffff81219cd4: pcpu_copy_value.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8121d530)
Location: kernel/bpf/hashtab.c:827
Inline: True
Direct callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
```
**Symbols:**

```
ffffffff8121d530-ffffffff8121d5f4: pcpu_copy_value.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81254500)
Location: kernel/bpf/hashtab.c:869
Inline: True
Direct callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
```
**Symbols:**

```
ffffffff81254500-ffffffff812545fb: pcpu_copy_value.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8129cbf0)
Location: kernel/bpf/hashtab.c:888
Inline: True
Direct callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
```
**Symbols:**

```
ffffffff8129cbf0-ffffffff8129cd04: pcpu_copy_value.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff812f9670)
Location: kernel/bpf/hashtab.c:916
Inline: True
Direct callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
```
**Symbols:**

```
ffffffff812f9670-ffffffff812f9795: pcpu_copy_value.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void pcpu_copy_value(struct bpf_htab *htab, void *pptr, void *value, bool onallcpus);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81327640)
Location: kernel/bpf/hashtab.c:931
Inline: True
Direct callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
**Symbols:**

```
ffffffff81327640-ffffffff81327753: pcpu_copy_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void pcpu_copy_value(struct bpf_htab *htab, void *pptr, void *value, bool onallcpus);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8134bce0)
Location: kernel/bpf/hashtab.c:948
Inline: True
Direct callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
**Symbols:**

```
ffffffff8134bce0-ffffffff8134bdf3: pcpu_copy_value (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/hashtab.c (ffff800010278198)
Location: kernel/bpf/hashtab.c:697
Inline: True
Direct callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
**Symbols:**

```
ffff800010278198-ffff8000102782b4: pcpu_copy_value.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void pcpu_copy_value(struct bpf_htab *htab, void *pptr, void *value, bool onallcpus);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (c04aa2d8)
Location: kernel/bpf/hashtab.c:697
Inline: True
Direct callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
**Symbols:**

```
c04aa2d8-c04aa3a8: pcpu_copy_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void pcpu_copy_value(struct bpf_htab *htab, void *pptr, void *value, bool onallcpus);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (c0000000003203a0)
Location: kernel/bpf/hashtab.c:697
Inline: True
Direct callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
**Symbols:**

```
c0000000003203a0-c00000000032052c: pcpu_copy_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void pcpu_copy_value(struct bpf_htab *htab, void *pptr, void *value, bool onallcpus);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffe0001af9ea)
Location: kernel/bpf/hashtab.c:697
Inline: True
Direct callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
**Symbols:**

```
ffffffe0001af9ea-ffffffe0001afaf6: pcpu_copy_value (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void pcpu_copy_value(struct bpf_htab *htab, void *pptr, void *value, bool onallcpus);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811ec180)
Location: kernel/bpf/hashtab.c:697
Inline: True
Direct callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
**Symbols:**

```
ffffffff811ec180-ffffffff811ec242: pcpu_copy_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void pcpu_copy_value(struct bpf_htab *htab, void *pptr, void *value, bool onallcpus);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811def10)
Location: kernel/bpf/hashtab.c:697
Inline: True
Direct callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
**Symbols:**

```
ffffffff811def10-ffffffff811defd2: pcpu_copy_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void pcpu_copy_value(struct bpf_htab *htab, void *pptr, void *value, bool onallcpus);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811e9f50)
Location: kernel/bpf/hashtab.c:697
Inline: True
Direct callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
**Symbols:**

```
ffffffff811e9f50-ffffffff811ea012: pcpu_copy_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void pcpu_copy_value(struct bpf_htab *htab, void *pptr, void *value, bool onallcpus);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811f8330)
Location: kernel/bpf/hashtab.c:697
Inline: True
Direct callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
**Symbols:**

```
ffffffff811f8330-ffffffff811f83f2: pcpu_copy_value (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
