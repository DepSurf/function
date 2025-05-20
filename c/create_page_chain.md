# Function: <code>create_page_chain</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/zsmalloc.c (ffffffff8122a300)
Location: mm/zsmalloc.c:1074
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffffffff8122a300-ffffffff8122a370: create_page_chain.isra.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/zsmalloc.c (ffffffff8123c850)
Location: mm/zsmalloc.c:1074
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffffffff8123c850-ffffffff8123c8c0: create_page_chain.isra.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/zsmalloc.c (ffffffff81248480)
Location: mm/zsmalloc.c:1066
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffffffff81248480-ffffffff812484df: create_page_chain.isra.18 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/zsmalloc.c (ffffffff81268640)
Location: mm/zsmalloc.c:1070
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffffffff81268640-ffffffff812686a1: create_page_chain.isra.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/zsmalloc.c (ffffffff8128cfa0)
Location: mm/zsmalloc.c:1053
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffffffff8128cfa0-ffffffff8128d000: create_page_chain.isra.23 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/zsmalloc.c (ffffffff812a1f20)
Location: mm/zsmalloc.c:1040
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffffffff812a1f20-ffffffff812a1f80: create_page_chain.isra.25 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/zsmalloc.c (ffffffff812bd230)
Location: mm/zsmalloc.c:1030
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffffffff812bd230-ffffffff812bd292: create_page_chain.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/zsmalloc.c (ffffffff812cf120)
Location: mm/zsmalloc.c:1027
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffffffff812cf120-ffffffff812cf182: create_page_chain.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void create_page_chain(struct size_class *class, struct zspage *zspage, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff813056e0)
Location: mm/zsmalloc.c:1027
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:alloc_zspage
```
**Symbols:**

```
ffffffff813056e0-ffffffff81305746: create_page_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void create_page_chain(struct size_class *class, struct zspage *zspage, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81311440)
Location: mm/zsmalloc.c:1020
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:alloc_zspage
```
**Symbols:**

```
ffffffff81311440-ffffffff813114a6: create_page_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void create_page_chain(struct size_class *class, struct zspage *zspage, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81317510)
Location: mm/zsmalloc.c:1020
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:alloc_zspage
```
**Symbols:**

```
ffffffff81317510-ffffffff8131756f: create_page_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void create_page_chain(struct size_class *class, struct zspage *zspage, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81363a70)
Location: mm/zsmalloc.c:1020
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:alloc_zspage
```
**Symbols:**

```
ffffffff81363a70-ffffffff81363acf: create_page_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void create_page_chain(struct size_class *class, struct zspage *zspage, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff813dfef0)
Location: mm/zsmalloc.c:1017
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:alloc_zspage
```
**Symbols:**

```
ffffffff813dfef0-ffffffff813dff5d: create_page_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void create_page_chain(struct size_class *class, struct zspage *zspage, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81466dd0)
Location: mm/zsmalloc.c:1124
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:alloc_zspage
```
**Symbols:**

```
ffffffff81466dd0-ffffffff81466e3d: create_page_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void create_page_chain(struct size_class *class, struct zspage *zspage, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff8149c2e0)
Location: mm/zsmalloc.c:949
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:alloc_zspage
```
**Symbols:**

```
ffffffff8149c2e0-ffffffff8149c356: create_page_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void create_page_chain(struct size_class *class, struct zspage *zspage, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff814cba00)
Location: mm/zsmalloc.c:944
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:alloc_zspage
```
**Symbols:**

```
ffffffff814cba00-ffffffff814cba76: create_page_chain (STB_LOCAL)
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
In mm/zsmalloc.c (ffff8000103743b8)
Location: mm/zsmalloc.c:1027
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffff8000103743b8-ffff800010374480: create_page_chain.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void create_page_chain(struct size_class *class, struct zspage *zspage, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (c0560220)
Location: mm/zsmalloc.c:1027
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
c0560220-c05602bc: create_page_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void create_page_chain(struct size_class *class, struct zspage *zspage, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (c000000000465b50)
Location: mm/zsmalloc.c:1027
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
c000000000465b50-c000000000465c04: create_page_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void create_page_chain(struct size_class *class, struct zspage *zspage, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffe00024c82e)
Location: mm/zsmalloc.c:1027
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffffffe00024c82e-ffffffe00024c8a8: create_page_chain (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/zsmalloc.c (ffffffff812c7700)
Location: mm/zsmalloc.c:1027
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffffffff812c7700-ffffffff812c7762: create_page_chain.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/zsmalloc.c (ffffffff812b8740)
Location: mm/zsmalloc.c:1027
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffffffff812b8740-ffffffff812b87a2: create_page_chain.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/zsmalloc.c (ffffffff812c5510)
Location: mm/zsmalloc.c:1027
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffffffff812c5510-ffffffff812c5572: create_page_chain.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/zsmalloc.c (ffffffff812d5ff0)
Location: mm/zsmalloc.c:1027
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffffffff812d5ff0-ffffffff812d6052: create_page_chain.isra.0 (STB_LOCAL)
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
<b>Arch</b>
<ul>
</ul>
