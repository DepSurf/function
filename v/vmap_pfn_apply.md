# Function: <code>vmap_pfn_apply</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vmap_pfn_apply(pte_t *pte, long unsigned int addr, void *private);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812b21e0)
Location: mm/vmalloc.c:2440
Inline: False
```
**Symbols:**

```
ffffffff812b21e0-ffffffff812b22e0: vmap_pfn_apply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vmap_pfn_apply(pte_t *pte, long unsigned int addr, void *private);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812b78f0)
Location: mm/vmalloc.c:2724
Inline: False
```
**Symbols:**

```
ffffffff812b78f0-ffffffff812b798e: vmap_pfn_apply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int vmap_pfn_apply(pte_t *pte, long unsigned int addr, void *private);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812fa020)
Location: mm/vmalloc.c:2777
Inline: False
```
**Symbols:**

```
ffffffff812fa020-ffffffff812fa0be: vmap_pfn_apply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vmap_pfn_apply(pte_t *pte, long unsigned int addr, void *private);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff813602c0)
Location: mm/vmalloc.c:2828
Inline: False
```
**Symbols:**

```
ffffffff813602c0-ffffffff8136041b: vmap_pfn_apply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int vmap_pfn_apply(pte_t *pte, long unsigned int addr, void *private);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff813dc2e0)
Location: mm/vmalloc.c:2890
Inline: False
```
**Symbols:**

```
ffffffff813dc2e0-ffffffff813dc43e: vmap_pfn_apply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vmap_pfn_apply(pte_t *pte, long unsigned int addr, void *private);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81410c00)
Location: mm/vmalloc.c:2944
Inline: False
```
**Symbols:**

```
ffffffff81410c00-ffffffff81410d5c: vmap_pfn_apply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int vmap_pfn_apply(pte_t *pte, long unsigned int addr, void *private);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8143ee70)
Location: mm/vmalloc.c:2944
Inline: False
```
**Symbols:**

```
ffffffff8143ee70-ffffffff8143f008: vmap_pfn_apply (STB_LOCAL)
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
