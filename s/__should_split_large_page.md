# Function: <code>__should_split_large_page</code>

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
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8107f085)
Location: arch/x86/mm/pageattr.c:736
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
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
In arch/x86/mm/pageattr.c (ffffffff81082f20)
Location: arch/x86/mm/pageattr.c:745
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
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
In arch/x86/mm/pageattr.c (ffffffff81083ff0)
Location: arch/x86/mm/pageattr.c:745
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __should_split_large_page(pte_t *kpte, long unsigned int address, struct cpa_data *cpa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108dbc0)
Location: arch/x86/mm/pat/set_memory.c:765
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
```
**Symbols:**

```
ffffffff8108dbc0-ffffffff8108dfe8: __should_split_large_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __should_split_large_page(pte_t *kpte, long unsigned int address, struct cpa_data *cpa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108da90)
Location: arch/x86/mm/pat/set_memory.c:765
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
```
**Symbols:**

```
ffffffff8108da90-ffffffff8108deb8: __should_split_large_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __should_split_large_page(pte_t *kpte, long unsigned int address, struct cpa_data *cpa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108e670)
Location: arch/x86/mm/pat/set_memory.c:773
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
```
**Symbols:**

```
ffffffff8108e670-ffffffff8108ea7f: __should_split_large_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __should_split_large_page(pte_t *kpte, long unsigned int address, struct cpa_data *cpa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (0)
Location: arch/x86/mm/pat/set_memory.c:773
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
```
**Symbols:**

```
ffffffff8109e190-ffffffff8109e57a: __should_split_large_page (STB_LOCAL)
ffffffff81ca13ad-ffffffff81ca13de: __should_split_large_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __should_split_large_page(pte_t *kpte, long unsigned int address, struct cpa_data *cpa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (0)
Location: arch/x86/mm/pat/set_memory.c:765
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
```
**Symbols:**

```
ffffffff810b1ad0-ffffffff810b1f41: __should_split_large_page (STB_LOCAL)
ffffffff81e5099d-ffffffff81e509ca: __should_split_large_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __should_split_large_page(pte_t *kpte, long unsigned int address, struct cpa_data *cpa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (0)
Location: arch/x86/mm/pat/set_memory.c:840
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
```
**Symbols:**

```
ffffffff810cc250-ffffffff810cc782: __should_split_large_page (STB_LOCAL)
ffffffff82054dfd-ffffffff82054e5d: __should_split_large_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __should_split_large_page(pte_t *kpte, long unsigned int address, struct cpa_data *cpa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (0)
Location: arch/x86/mm/pat/set_memory.c:841
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
```
**Symbols:**

```
ffffffff810cf870-ffffffff810cfdab: __should_split_large_page (STB_LOCAL)
ffffffff820d33d3-ffffffff820d3434: __should_split_large_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __should_split_large_page(pte_t *kpte, long unsigned int address, struct cpa_data *cpa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (0)
Location: arch/x86/mm/pat/set_memory.c:845
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
```
**Symbols:**

```
ffffffff810d7f50-ffffffff810d848b: __should_split_large_page (STB_LOCAL)
ffffffff821ae241-ffffffff821ae2a2: __should_split_large_page.cold (STB_LOCAL)
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
In arch/x86/mm/pageattr.c (ffffffff81082ff0)
Location: arch/x86/mm/pageattr.c:745
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
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
In arch/x86/mm/pageattr.c (ffffffff810717d1)
Location: arch/x86/mm/pageattr.c:745
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
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
In arch/x86/mm/pageattr.c (ffffffff81082fa0)
Location: arch/x86/mm/pageattr.c:745
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
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
In arch/x86/mm/pageattr.c (ffffffff810850c0)
Location: arch/x86/mm/pageattr.c:745
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
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
