# Function: <code>try_to_free_pmd_page</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool try_to_free_pmd_page(pmd_t *pmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8106c140)
Location: arch/x86/mm/pageattr.c:744
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:unmap_pmd_range
```
**Symbols:**

```
ffffffff8106c140-ffffffff8106c178: try_to_free_pmd_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool try_to_free_pmd_page(pmd_t *pmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8106fd60)
Location: arch/x86/mm/pageattr.c:744
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:unmap_pmd_range
```
**Symbols:**

```
ffffffff8106fd60-ffffffff8106fd98: try_to_free_pmd_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool try_to_free_pmd_page(pmd_t *pmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8106f490)
Location: arch/x86/mm/pageattr.c:780
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:unmap_pmd_range
```
**Symbols:**

```
ffffffff8106f490-ffffffff8106f4c8: try_to_free_pmd_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool try_to_free_pmd_page(pmd_t *pmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81074830)
Location: arch/x86/mm/pageattr.c:780
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:unmap_pmd_range
```
**Symbols:**

```
ffffffff81074830-ffffffff81074868: try_to_free_pmd_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool try_to_free_pmd_page(pmd_t *pmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810772a0)
Location: arch/x86/mm/pageattr.c:803
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:unmap_pmd_range
```
**Symbols:**

```
ffffffff810772a0-ffffffff810772d8: try_to_free_pmd_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool try_to_free_pmd_page(pmd_t *pmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8107d9d0)
Location: arch/x86/mm/pageattr.c:1065
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:unmap_pmd_range
```
**Symbols:**

```
ffffffff8107d9d0-ffffffff8107da08: try_to_free_pmd_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool try_to_free_pmd_page(pmd_t *pmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810812d0)
Location: arch/x86/mm/pageattr.c:1075
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:unmap_pmd_range
```
**Symbols:**

```
ffffffff810812d0-ffffffff81081308: try_to_free_pmd_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool try_to_free_pmd_page(pmd_t *pmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81082390)
Location: arch/x86/mm/pageattr.c:1075
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:unmap_pmd_range
```
**Symbols:**

```
ffffffff81082390-ffffffff810823c8: try_to_free_pmd_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108caf1)
Location: arch/x86/mm/pat/set_memory.c:1095
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108c374)
Location: arch/x86/mm/pat/set_memory.c:1095
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108d614)
Location: arch/x86/mm/pat/set_memory.c:1103
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
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
In arch/x86/mm/pat/set_memory.c (ffffffff8109ce92)
Location: arch/x86/mm/pat/set_memory.c:1103
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
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
In arch/x86/mm/pat/set_memory.c (ffffffff810b073e)
Location: arch/x86/mm/pat/set_memory.c:1095
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810cadfa)
Location: arch/x86/mm/pat/set_memory.c:1172
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810ce42a)
Location: arch/x86/mm/pat/set_memory.c:1173
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810d6b0a)
Location: arch/x86/mm/pat/set_memory.c:1177
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
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
bool try_to_free_pmd_page(pmd_t *pmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81081390)
Location: arch/x86/mm/pageattr.c:1075
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:unmap_pmd_range
```
**Symbols:**

```
ffffffff81081390-ffffffff810813c8: try_to_free_pmd_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool try_to_free_pmd_page(pmd_t *pmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810703a0)
Location: arch/x86/mm/pageattr.c:1075
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:unmap_pmd_range
```
**Symbols:**

```
ffffffff810703a0-ffffffff810703d8: try_to_free_pmd_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool try_to_free_pmd_page(pmd_t *pmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81081340)
Location: arch/x86/mm/pageattr.c:1075
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:unmap_pmd_range
```
**Symbols:**

```
ffffffff81081340-ffffffff81081378: try_to_free_pmd_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool try_to_free_pmd_page(pmd_t *pmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81083460)
Location: arch/x86/mm/pageattr.c:1075
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:unmap_pmd_range
```
**Symbols:**

```
ffffffff81083460-ffffffff81083498: try_to_free_pmd_page (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
