# Function: <code>populate_extra_pte</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
pte_t *populate_extra_pte(long unsigned int vaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81f77b5f)
Location: arch/x86/mm/init_64.c:314
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/kernel/setup_percpu.c:pcpup_populate_pte
```
**Symbols:**

```
ffffffff81f77b5f-ffffffff81f77b7a: populate_extra_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
pte_t *populate_extra_pte(long unsigned int vaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81fa02a2)
Location: arch/x86/mm/init_64.c:243
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/kernel/setup_percpu.c:pcpup_populate_pte
```
**Symbols:**

```
ffffffff81fa02a2-ffffffff81fa02bd: populate_extra_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
pte_t *populate_extra_pte(long unsigned int vaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81fdb80c)
Location: arch/x86/mm/init_64.c:233
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/kernel/setup_percpu.c:pcpup_populate_pte
```
**Symbols:**

```
ffffffff81fdb80c-ffffffff81fdb827: populate_extra_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
pte_t *populate_extra_pte(long unsigned int vaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff820bc7c7)
Location: arch/x86/mm/init_64.c:307
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/kernel/setup_percpu.c:pcpup_populate_pte
```
**Symbols:**

```
ffffffff820bc7c7-ffffffff820bc7e7: populate_extra_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
pte_t *populate_extra_pte(long unsigned int vaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff826c3214)
Location: arch/x86/mm/init_64.c:307
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/kernel/setup_percpu.c:pcpup_populate_pte
```
**Symbols:**

```
ffffffff826c3214-ffffffff826c3234: populate_extra_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
pte_t *populate_extra_pte(long unsigned int vaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff826ed438)
Location: arch/x86/mm/init_64.c:318
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/kernel/setup_percpu.c:pcpup_populate_pte
```
**Symbols:**

```
ffffffff826ed438-ffffffff826ed458: populate_extra_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
pte_t *populate_extra_pte(long unsigned int vaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff828a3fca)
Location: arch/x86/mm/init_64.c:317
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/p2m.c:xen_vmalloc_p2m_tree
  - arch/x86/xen/enlighten_pv.c:xen_pv_init_platform
  - arch/x86/kernel/setup_percpu.c:pcpup_populate_pte
```
**Symbols:**

```
ffffffff828a3fca-ffffffff828a3fea: populate_extra_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
pte_t *populate_extra_pte(long unsigned int vaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff828bc466)
Location: arch/x86/mm/init_64.c:349
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/enlighten_pv.c:xen_pv_init_platform
  - arch/x86/kernel/setup_percpu.c:pcpup_populate_pte
```
**Symbols:**

```
ffffffff828bc466-ffffffff828bc488: populate_extra_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
pte_t *populate_extra_pte(long unsigned int vaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff828c290d)
Location: arch/x86/mm/init_64.c:349
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/enlighten_pv.c:xen_pv_init_platform
  - arch/x86/kernel/setup_percpu.c:pcpup_populate_pte
```
**Symbols:**

```
ffffffff828c290d-ffffffff828c292f: populate_extra_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
pte_t *populate_extra_pte(long unsigned int vaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff82ce5d35)
Location: arch/x86/mm/init_64.c:354
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/enlighten_pv.c:xen_pv_init_platform
  - arch/x86/kernel/setup_percpu.c:pcpup_populate_pte
```
**Symbols:**

```
ffffffff82ce5d35-ffffffff82ce5d57: populate_extra_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
pte_t *populate_extra_pte(long unsigned int vaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff82fd36c0)
Location: arch/x86/mm/init_64.c:349
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/enlighten_pv.c:xen_pv_init_platform
  - arch/x86/kernel/setup_percpu.c:pcpup_populate_pte
```
**Symbols:**

```
ffffffff82fd36c0-ffffffff82fd36e2: populate_extra_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
pte_t *populate_extra_pte(long unsigned int vaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff831de2f0)
Location: arch/x86/mm/init_64.c:349
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/enlighten_pv.c:xen_pv_init_platform
  - arch/x86/kernel/setup_percpu.c:pcpup_populate_pte
```
**Symbols:**

```
ffffffff831de2f0-ffffffff831de312: populate_extra_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
pte_t *populate_extra_pte(long unsigned int vaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff832c157e)
Location: arch/x86/mm/init_64.c:350
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/enlighten_pv.c:xen_pv_init_platform
  - arch/x86/kernel/setup_percpu.c:pcpup_populate_pte
```
**Symbols:**

```
ffffffff832c157e-ffffffff832c15a0: populate_extra_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
pte_t *populate_extra_pte(long unsigned int vaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff83473be9)
Location: arch/x86/mm/init_64.c:349
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/enlighten_pv.c:xen_pv_init_platform
  - arch/x86/kernel/setup_percpu.c:pcpu_populate_pte
```
**Symbols:**

```
ffffffff83473be9-ffffffff83473c11: populate_extra_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
pte_t *populate_extra_pte(long unsigned int vaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff83e9b7a0)
Location: arch/x86/mm/init_64.c:355
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/enlighten_pv.c:xen_pv_init_platform
  - arch/x86/kernel/setup_percpu.c:pcpu_populate_pte
```
**Symbols:**

```
ffffffff83e9b7a0-ffffffff83e9b7cb: populate_extra_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
pte_t *populate_extra_pte(long unsigned int vaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff836bf240)
Location: arch/x86/mm/init_64.c:355
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/enlighten_pv.c:xen_pv_init_platform
  - arch/x86/kernel/setup_percpu.c:pcpu_populate_pte
```
**Symbols:**

```
ffffffff836bf240-ffffffff836bf26b: populate_extra_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
pte_t *populate_extra_pte(long unsigned int vaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff838efce0)
Location: arch/x86/mm/init_64.c:355
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/enlighten_pv.c:xen_pv_init_platform
  - arch/x86/kernel/setup_percpu.c:pcpu_populate_pte
```
**Symbols:**

```
ffffffff838efce0-ffffffff838efd0b: populate_extra_pte (STB_GLOBAL)
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
pte_t *populate_extra_pte(long unsigned int vaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff828ad8e3)
Location: arch/x86/mm/init_64.c:349
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/enlighten_pv.c:xen_pv_init_platform
  - arch/x86/kernel/setup_percpu.c:pcpup_populate_pte
```
**Symbols:**

```
ffffffff828ad8e3-ffffffff828ad905: populate_extra_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
pte_t *populate_extra_pte(long unsigned int vaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff828a5ba9)
Location: arch/x86/mm/init_64.c:349
Inline: False
Direct callers:
  - arch/x86/kernel/setup_percpu.c:pcpup_populate_pte
```
**Symbols:**

```
ffffffff828a5ba9-ffffffff828a5bcb: populate_extra_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
pte_t *populate_extra_pte(long unsigned int vaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff828c07e2)
Location: arch/x86/mm/init_64.c:349
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/enlighten_pv.c:xen_pv_init_platform
  - arch/x86/kernel/setup_percpu.c:pcpup_populate_pte
```
**Symbols:**

```
ffffffff828c07e2-ffffffff828c0804: populate_extra_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
pte_t *populate_extra_pte(long unsigned int vaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff828c392d)
Location: arch/x86/mm/init_64.c:349
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/p2m.c:xen_rebuild_p2m_list
  - arch/x86/xen/enlighten_pv.c:xen_pv_init_platform
  - arch/x86/kernel/setup_percpu.c:pcpup_populate_pte
```
**Symbols:**

```
ffffffff828c392d-ffffffff828c394f: populate_extra_pte (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
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
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
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
<b>Arch</b>
<ul>
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
