# Function: <code>populate_pud</code>

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
In arch/x86/mm/pageattr.c (ffffffff8106cd24)
Location: arch/x86/mm/pageattr.c:1001
Inline: True
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
In arch/x86/mm/pageattr.c (ffffffff8106ca03)
Location: arch/x86/mm/pageattr.c:994
Inline: True
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
In arch/x86/mm/pageattr.c (ffffffff81070643)
Location: arch/x86/mm/pageattr.c:994
Inline: True
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
In arch/x86/mm/pageattr.c (ffffffff8106fe08)
Location: arch/x86/mm/pageattr.c:1030
Inline: True
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
In arch/x86/mm/pageattr.c (ffffffff810752bd)
Location: arch/x86/mm/pageattr.c:1030
Inline: True
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
In arch/x86/mm/pageattr.c (ffffffff81077d50)
Location: arch/x86/mm/pageattr.c:1041
Inline: True
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
In arch/x86/mm/pageattr.c (ffffffff8107e500)
Location: arch/x86/mm/pageattr.c:1303
Inline: True
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
In arch/x86/mm/pageattr.c (ffffffff81081dfc)
Location: arch/x86/mm/pageattr.c:1313
Inline: True
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
In arch/x86/mm/pageattr.c (ffffffff81082ebc)
Location: arch/x86/mm/pageattr.c:1313
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int populate_pud(struct cpa_data *cpa, long unsigned int start, p4d_t *p4d, pgprot_t pgprot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108c470)
Location: arch/x86/mm/pat/set_memory.c:1333
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
```
**Symbols:**

```
ffffffff8108c470-ffffffff8108c7b5: populate_pud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int populate_pud(struct cpa_data *cpa, long unsigned int start, p4d_t *p4d, pgprot_t pgprot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108c710)
Location: arch/x86/mm/pat/set_memory.c:1333
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
```
**Symbols:**

```
ffffffff8108c710-ffffffff8108ca55: populate_pud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int populate_pud(struct cpa_data *cpa, long unsigned int start, p4d_t *p4d, pgprot_t pgprot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108d140)
Location: arch/x86/mm/pat/set_memory.c:1341
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
```
**Symbols:**

```
ffffffff8108d140-ffffffff8108d466: populate_pud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int populate_pud(struct cpa_data *cpa, long unsigned int start, p4d_t *p4d, pgprot_t pgprot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8109c9c0)
Location: arch/x86/mm/pat/set_memory.c:1341
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
```
**Symbols:**

```
ffffffff8109c9c0-ffffffff8109ccee: populate_pud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int populate_pud(struct cpa_data *cpa, long unsigned int start, p4d_t *p4d, pgprot_t pgprot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810b01d0)
Location: arch/x86/mm/pat/set_memory.c:1333
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
```
**Symbols:**

```
ffffffff810b01d0-ffffffff810b0518: populate_pud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int populate_pud(struct cpa_data *cpa, long unsigned int start, p4d_t *p4d, pgprot_t pgprot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810ca860)
Location: arch/x86/mm/pat/set_memory.c:1410
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
```
**Symbols:**

```
ffffffff810ca860-ffffffff810cabb4: populate_pud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int populate_pud(struct cpa_data *cpa, long unsigned int start, p4d_t *p4d, pgprot_t pgprot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810cdea0)
Location: arch/x86/mm/pat/set_memory.c:1411
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
```
**Symbols:**

```
ffffffff810cdea0-ffffffff810ce1ee: populate_pud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int populate_pud(struct cpa_data *cpa, long unsigned int start, p4d_t *p4d, pgprot_t pgprot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810d6580)
Location: arch/x86/mm/pat/set_memory.c:1415
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
```
**Symbols:**

```
ffffffff810d6580-ffffffff810d68ce: populate_pud (STB_LOCAL)
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
In arch/x86/mm/pageattr.c (ffffffff81081ebc)
Location: arch/x86/mm/pageattr.c:1313
Inline: True
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
In arch/x86/mm/pageattr.c (ffffffff81070bfe)
Location: arch/x86/mm/pageattr.c:1313
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pgd
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
In arch/x86/mm/pageattr.c (ffffffff81081e6c)
Location: arch/x86/mm/pageattr.c:1313
Inline: True
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
In arch/x86/mm/pageattr.c (ffffffff81083f8c)
Location: arch/x86/mm/pageattr.c:1313
Inline: True
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
