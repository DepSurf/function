# Function: <code>__cpa_addr</code>

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
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
long unsigned int __cpa_addr(struct cpa_data *cpa, long unsigned int idx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8107da10)
Location: arch/x86/mm/pageattr.c:256
Inline: True
Direct callers:
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:cpa_flush
  - arch/x86/mm/pageattr.c:__cpa_flush_tlb
```
**Symbols:**

```
ffffffff8107da10-ffffffff8107da59: __cpa_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
long unsigned int __cpa_addr(struct cpa_data *cpa, long unsigned int idx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81081310)
Location: arch/x86/mm/pageattr.c:257
Inline: True
Direct callers:
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:cpa_flush
  - arch/x86/mm/pageattr.c:__cpa_flush_tlb
```
**Symbols:**

```
ffffffff81081310-ffffffff81081359: __cpa_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
long unsigned int __cpa_addr(struct cpa_data *cpa, long unsigned int idx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810823d0)
Location: arch/x86/mm/pageattr.c:257
Inline: True
Direct callers:
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:cpa_flush
  - arch/x86/mm/pageattr.c:__cpa_flush_tlb
```
**Symbols:**

```
ffffffff810823d0-ffffffff81082419: __cpa_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int __cpa_addr(struct cpa_data *cpa, long unsigned int idx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108be94)
Location: arch/x86/mm/pat/set_memory.c:264
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__cpa_flush_tlb
  - arch/x86/mm/pat/set_memory.c:__cpa_flush_tlb
Direct callers:
  - arch/x86/mm/pat/set_memory.c:cpa_process_alias
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:cpa_flush
```
**Symbols:**

```
ffffffff8108bc60-ffffffff8108bca9: __cpa_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
long unsigned int __cpa_addr(struct cpa_data *cpa, long unsigned int idx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108bdd4)
Location: arch/x86/mm/pat/set_memory.c:264
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__cpa_flush_tlb
  - arch/x86/mm/pat/set_memory.c:__cpa_flush_tlb
Direct callers:
  - arch/x86/mm/pat/set_memory.c:cpa_process_alias
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:cpa_flush
```
**Symbols:**

```
ffffffff8108bc80-ffffffff8108bcc9: __cpa_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long unsigned int __cpa_addr(struct cpa_data *cpa, long unsigned int idx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108ca54)
Location: arch/x86/mm/pat/set_memory.c:272
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__cpa_flush_tlb
  - arch/x86/mm/pat/set_memory.c:__cpa_flush_tlb
Direct callers:
  - arch/x86/mm/pat/set_memory.c:cpa_process_alias
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:cpa_flush
```
**Symbols:**

```
ffffffff8108c880-ffffffff8108c8c9: __cpa_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long unsigned int __cpa_addr(struct cpa_data *cpa, long unsigned int idx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8109c2b4)
Location: arch/x86/mm/pat/set_memory.c:272
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__cpa_flush_tlb
  - arch/x86/mm/pat/set_memory.c:__cpa_flush_tlb
Direct callers:
  - arch/x86/mm/pat/set_memory.c:cpa_process_alias
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:cpa_flush
```
**Symbols:**

```
ffffffff8109c0e0-ffffffff8109c129: __cpa_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
long unsigned int __cpa_addr(struct cpa_data *cpa, long unsigned int idx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810afa34)
Location: arch/x86/mm/pat/set_memory.c:275
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__cpa_flush_tlb
  - arch/x86/mm/pat/set_memory.c:__cpa_flush_tlb
Direct callers:
  - arch/x86/mm/pat/set_memory.c:cpa_process_alias
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:cpa_flush
```
**Symbols:**

```
ffffffff810af7f0-ffffffff810af857: __cpa_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long unsigned int __cpa_addr(struct cpa_data *cpa, long unsigned int idx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810ca054)
Location: arch/x86/mm/pat/set_memory.c:293
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__cpa_flush_tlb
  - arch/x86/mm/pat/set_memory.c:__cpa_flush_tlb
Direct callers:
  - arch/x86/mm/pat/set_memory.c:cpa_process_alias
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:cpa_flush
```
**Symbols:**

```
ffffffff810c9db0-ffffffff810c9e17: __cpa_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long unsigned int __cpa_addr(struct cpa_data *cpa, long unsigned int idx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810cd6a4)
Location: arch/x86/mm/pat/set_memory.c:294
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__cpa_flush_tlb
  - arch/x86/mm/pat/set_memory.c:__cpa_flush_tlb
Direct callers:
  - arch/x86/mm/pat/set_memory.c:cpa_process_alias
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:cpa_flush
```
**Symbols:**

```
ffffffff810cd400-ffffffff810cd467: __cpa_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int __cpa_addr(struct cpa_data *cpa, long unsigned int idx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810d5ce4)
Location: arch/x86/mm/pat/set_memory.c:294
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__cpa_flush_tlb
  - arch/x86/mm/pat/set_memory.c:__cpa_flush_tlb
Direct callers:
  - arch/x86/mm/pat/set_memory.c:cpa_process_alias
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:cpa_flush
```
**Symbols:**

```
ffffffff810d5ae0-ffffffff810d5b47: __cpa_addr (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
long unsigned int __cpa_addr(struct cpa_data *cpa, long unsigned int idx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810813d0)
Location: arch/x86/mm/pageattr.c:257
Inline: True
Direct callers:
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:cpa_flush
  - arch/x86/mm/pageattr.c:__cpa_flush_tlb
```
**Symbols:**

```
ffffffff810813d0-ffffffff81081419: __cpa_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
long unsigned int __cpa_addr(struct cpa_data *cpa, long unsigned int idx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810703e0)
Location: arch/x86/mm/pageattr.c:257
Inline: True
Direct callers:
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:cpa_flush
  - arch/x86/mm/pageattr.c:__cpa_flush_tlb
```
**Symbols:**

```
ffffffff810703e0-ffffffff81070429: __cpa_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
long unsigned int __cpa_addr(struct cpa_data *cpa, long unsigned int idx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81081380)
Location: arch/x86/mm/pageattr.c:257
Inline: True
Direct callers:
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:cpa_flush
  - arch/x86/mm/pageattr.c:__cpa_flush_tlb
```
**Symbols:**

```
ffffffff81081380-ffffffff810813c9: __cpa_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
long unsigned int __cpa_addr(struct cpa_data *cpa, long unsigned int idx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810834a0)
Location: arch/x86/mm/pageattr.c:257
Inline: True
Direct callers:
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:cpa_flush
  - arch/x86/mm/pageattr.c:__cpa_flush_tlb
```
**Symbols:**

```
ffffffff810834a0-ffffffff810834e9: __cpa_addr (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
