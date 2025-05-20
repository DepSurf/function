# Function: <code>vmemmap_populate_hugepages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8181ca33)
Location: arch/x86/mm/init_64.c:1238
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81896b3e)
Location: arch/x86/mm/init_64.c:1170
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff818cb229)
Location: arch/x86/mm/init_64.c:1160
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81902808)
Location: arch/x86/mm/init_64.c:1338
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8198c76d)
Location: arch/x86/mm/init_64.c:1352
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/mm/init_64.c:1406
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/mm/init_64.c:1394
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/mm/init_64.c:1451
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/mm/init_64.c:1449
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vmemmap_populate_hugepages(long unsigned int start, long unsigned int end, int node, struct vmem_altmap *altmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81bc3ec0)
Location: arch/x86/mm/init_64.c:1437
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
```
**Symbols:**

```
ffffffff81bc3ec0-ffffffff81bc40e0: vmemmap_populate_hugepages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vmemmap_populate_hugepages(long unsigned int start, long unsigned int end, int node, struct vmem_altmap *altmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81c3cdd8)
Location: arch/x86/mm/init_64.c:1492
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
```
**Symbols:**

```
ffffffff81c3cdd8-ffffffff81c3cfeb: vmemmap_populate_hugepages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vmemmap_populate_hugepages(long unsigned int start, long unsigned int end, int node, struct vmem_altmap *altmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81c2f185)
Location: arch/x86/mm/init_64.c:1535
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
```
**Symbols:**

```
ffffffff81c2f185-ffffffff81c2f419: vmemmap_populate_hugepages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int vmemmap_populate_hugepages(long unsigned int start, long unsigned int end, int node, struct vmem_altmap *altmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81d4d886)
Location: arch/x86/mm/init_64.c:1535
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
```
**Symbols:**

```
ffffffff81d4d886-ffffffff81d4db18: vmemmap_populate_hugepages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vmemmap_populate_hugepages(long unsigned int start, long unsigned int end, int node, struct vmem_altmap *altmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81f1d5b9)
Location: arch/x86/mm/init_64.c:1535
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
```
**Symbols:**

```
ffffffff81f1d5b9-ffffffff81f1d872: vmemmap_populate_hugepages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int vmemmap_populate_hugepages(long unsigned int start, long unsigned int end, int node, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff820cbd70)
Location: mm/sparse-vmemmap.c:309
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
```
**Symbols:**

```
ffffffff820cbd70-ffffffff820cbf63: vmemmap_populate_hugepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vmemmap_populate_hugepages(long unsigned int start, long unsigned int end, int node, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff82150020)
Location: mm/sparse-vmemmap.c:309
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
```
**Symbols:**

```
ffffffff82150020-ffffffff82150213: vmemmap_populate_hugepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int vmemmap_populate_hugepages(long unsigned int start, long unsigned int end, int node, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff82232e50)
Location: mm/sparse-vmemmap.c:309
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
```
**Symbols:**

```
ffffffff82232e50-ffffffff82233043: vmemmap_populate_hugepages (STB_GLOBAL)
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/mm/init_64.c:1449
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/mm/init_64.c:1449
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/mm/init_64.c:1449
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/mm/init_64.c:1449
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
