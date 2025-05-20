# Function: <code>cea_map_percpu_pages</code>

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
void cea_map_percpu_pages(void *cea_vaddr, void *ptr, int pages, pgprot_t prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/cpu_entry_area.c (ffffffff826c3ab9)
Location: arch/x86/mm/cpu_entry_area.c:35
Inline: False
Direct callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
```
**Symbols:**

```
ffffffff826c3ab9-ffffffff826c3b11: cea_map_percpu_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void cea_map_percpu_pages(void *cea_vaddr, void *ptr, int pages, pgprot_t prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/cpu_entry_area.c (ffffffff826edd3e)
Location: arch/x86/mm/cpu_entry_area.c:47
Inline: False
Direct callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
```
**Symbols:**

```
ffffffff826edd3e-ffffffff826edd8a: cea_map_percpu_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void cea_map_percpu_pages(void *cea_vaddr, void *ptr, int pages, pgprot_t prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/cpu_entry_area.c (ffffffff828a4a62)
Location: arch/x86/mm/cpu_entry_area.c:49
Inline: False
Direct callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
```
**Symbols:**

```
ffffffff828a4a62-ffffffff828a4aae: cea_map_percpu_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void cea_map_percpu_pages(void *cea_vaddr, void *ptr, int pages, pgprot_t prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/cpu_entry_area.c (ffffffff828bcf46)
Location: arch/x86/mm/cpu_entry_area.c:49
Inline: False
Direct callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
```
**Symbols:**

```
ffffffff828bcf46-ffffffff828bcf96: cea_map_percpu_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cea_map_percpu_pages(void *cea_vaddr, void *ptr, int pages, pgprot_t prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/cpu_entry_area.c (ffffffff828c33d0)
Location: arch/x86/mm/cpu_entry_area.c:49
Inline: False
Direct callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
```
**Symbols:**

```
ffffffff828c33d0-ffffffff828c3420: cea_map_percpu_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void cea_map_percpu_pages(void *cea_vaddr, void *ptr, int pages, pgprot_t prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/cpu_entry_area.c (ffffffff82ce65d6)
Location: arch/x86/mm/cpu_entry_area.c:53
Inline: False
Direct callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_area
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_area
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_area
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
```
**Symbols:**

```
ffffffff82ce65d6-ffffffff82ce6622: cea_map_percpu_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void cea_map_percpu_pages(void *cea_vaddr, void *ptr, int pages, pgprot_t prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/cpu_entry_area.c (ffffffff82fd3f47)
Location: arch/x86/mm/cpu_entry_area.c:54
Inline: False
Direct callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_area
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_area
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_area
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
```
**Symbols:**

```
ffffffff82fd3f47-ffffffff82fd3f93: cea_map_percpu_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void cea_map_percpu_pages(void *cea_vaddr, void *ptr, int pages, pgprot_t prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/cpu_entry_area.c (ffffffff831dea88)
Location: arch/x86/mm/cpu_entry_area.c:54
Inline: False
Direct callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_area
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_area
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_area
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_area
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_area
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_area
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_area
```
**Symbols:**

```
ffffffff831dea88-ffffffff831dead4: cea_map_percpu_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void cea_map_percpu_pages(void *cea_vaddr, void *ptr, int pages, pgprot_t prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/cpu_entry_area.c (ffffffff832c1dfe)
Location: arch/x86/mm/cpu_entry_area.c:54
Inline: False
Direct callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_area
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_area
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_area
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
```
**Symbols:**

```
ffffffff832c1dfe-ffffffff832c1e4a: cea_map_percpu_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void cea_map_percpu_pages(void *cea_vaddr, void *ptr, int pages, pgprot_t prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/cpu_entry_area.c (ffffffff834744b4)
Location: arch/x86/mm/cpu_entry_area.c:54
Inline: False
Direct callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_area
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_area
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_area
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
```
**Symbols:**

```
ffffffff834744b4-ffffffff8347450e: cea_map_percpu_pages (STB_LOCAL)
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
In arch/x86/mm/cpu_entry_area.c (ffffffff83e9c7c9)
Location: arch/x86/mm/cpu_entry_area.c:92
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
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
In arch/x86/mm/cpu_entry_area.c (ffffffff836c02e9)
Location: arch/x86/mm/cpu_entry_area.c:99
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
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
In arch/x86/mm/cpu_entry_area.c (ffffffff838f0e09)
Location: arch/x86/mm/cpu_entry_area.c:99
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
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
void cea_map_percpu_pages(void *cea_vaddr, void *ptr, int pages, pgprot_t prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/cpu_entry_area.c (ffffffff828ae3a6)
Location: arch/x86/mm/cpu_entry_area.c:49
Inline: False
Direct callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
```
**Symbols:**

```
ffffffff828ae3a6-ffffffff828ae3f6: cea_map_percpu_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cea_map_percpu_pages(void *cea_vaddr, void *ptr, int pages, pgprot_t prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/cpu_entry_area.c (ffffffff828a6598)
Location: arch/x86/mm/cpu_entry_area.c:49
Inline: False
Direct callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
```
**Symbols:**

```
ffffffff828a6598-ffffffff828a65e8: cea_map_percpu_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cea_map_percpu_pages(void *cea_vaddr, void *ptr, int pages, pgprot_t prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/cpu_entry_area.c (ffffffff828c12a5)
Location: arch/x86/mm/cpu_entry_area.c:49
Inline: False
Direct callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
```
**Symbols:**

```
ffffffff828c12a5-ffffffff828c12f5: cea_map_percpu_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cea_map_percpu_pages(void *cea_vaddr, void *ptr, int pages, pgprot_t prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/cpu_entry_area.c (ffffffff828c43f0)
Location: arch/x86/mm/cpu_entry_area.c:49
Inline: False
Direct callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
```
**Symbols:**

```
ffffffff828c43f0-ffffffff828c4440: cea_map_percpu_pages (STB_LOCAL)
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
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
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
