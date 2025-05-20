# Function: <code>dax_iomap_pfn</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dax_iomap_pfn(struct iomap *iomap, loff_t pos, size_t size, pfn_t *pfnp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff812cc900)
Location: fs/dax.c:833
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_fault
```
**Symbols:**

```
ffffffff812cc900-ffffffff812cc9fe: dax_iomap_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int dax_iomap_pfn(struct iomap *iomap, loff_t pos, size_t size, pfn_t *pfnp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff812f6cc0)
Location: fs/dax.c:1080
Inline: False
```
**Symbols:**

```
ffffffff812f6cc0-ffffffff812f6dbb: dax_iomap_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dax_iomap_pfn(struct iomap *iomap, loff_t pos, size_t size, pfn_t *pfnp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8130bd70)
Location: fs/dax.c:985
Inline: False
```
**Symbols:**

```
ffffffff8130bd70-ffffffff8130be69: dax_iomap_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int dax_iomap_pfn(struct iomap *iomap, loff_t pos, size_t size, pfn_t *pfnp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81333290)
Location: fs/dax.c:990
Inline: False
```
**Symbols:**

```
ffffffff81333290-ffffffff8133339a: dax_iomap_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int dax_iomap_pfn(struct iomap *iomap, loff_t pos, size_t size, pfn_t *pfnp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81346e40)
Location: fs/dax.c:991
Inline: False
```
**Symbols:**

```
ffffffff81346e40-ffffffff81346f4a: dax_iomap_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dax_iomap_pfn(struct iomap *iomap, loff_t pos, size_t size, pfn_t *pfnp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8138c520)
Location: fs/dax.c:985
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
```
**Symbols:**

```
ffffffff8138c520-ffffffff8138c617: dax_iomap_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dax_iomap_pfn(struct iomap *iomap, loff_t pos, size_t size, pfn_t *pfnp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8139dc50)
Location: fs/dax.c:1001
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
```
**Symbols:**

```
ffffffff8139dc50-ffffffff8139dd47: dax_iomap_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dax_iomap_pfn(struct iomap *iomap, loff_t pos, size_t size, pfn_t *pfnp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813a4e60)
Location: fs/dax.c:1013
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
```
**Symbols:**

```
ffffffff813a4e60-ffffffff813a4f57: dax_iomap_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813f686c)
Location: fs/dax.c:1013
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81469030)
Location: fs/dax.c:934
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_iter
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffff800010409ffc)
Location: fs/dax.c:991
Inline: True
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dax_iomap_pfn(struct iomap *iomap, loff_t pos, size_t size, pfn_t *pfnp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (c0000000005128b0)
Location: fs/dax.c:991
Inline: False
```
**Symbols:**

```
c0000000005128b0-c000000000512a14: dax_iomap_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffe0002b3d94)
Location: fs/dax.c:991
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int dax_iomap_pfn(struct iomap *iomap, loff_t pos, size_t size, pfn_t *pfnp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8133f420)
Location: fs/dax.c:991
Inline: False
```
**Symbols:**

```
ffffffff8133f420-ffffffff8133f52a: dax_iomap_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int dax_iomap_pfn(struct iomap *iomap, loff_t pos, size_t size, pfn_t *pfnp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813300e0)
Location: fs/dax.c:991
Inline: False
```
**Symbols:**

```
ffffffff813300e0-ffffffff813301ea: dax_iomap_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int dax_iomap_pfn(struct iomap *iomap, loff_t pos, size_t size, pfn_t *pfnp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8133cef0)
Location: fs/dax.c:991
Inline: False
```
**Symbols:**

```
ffffffff8133cef0-ffffffff8133cffa: dax_iomap_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int dax_iomap_pfn(struct iomap *iomap, loff_t pos, size_t size, pfn_t *pfnp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81350600)
Location: fs/dax.c:991
Inline: False
```
**Symbols:**

```
ffffffff81350600-ffffffff8135070a: dax_iomap_pfn (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
