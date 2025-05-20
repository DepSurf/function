# Function: <code>cpa_process_alias</code>

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
In arch/x86/mm/pageattr.c (ffffffff8106dfb5)
Location: arch/x86/mm/pageattr.c:1260
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
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
In arch/x86/mm/pageattr.c (ffffffff8106dceb)
Location: arch/x86/mm/pageattr.c:1266
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
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
In arch/x86/mm/pageattr.c (ffffffff8107195b)
Location: arch/x86/mm/pageattr.c:1266
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
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
In arch/x86/mm/pageattr.c (ffffffff8107104b)
Location: arch/x86/mm/pageattr.c:1312
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
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
In arch/x86/mm/pageattr.c (ffffffff810767cb)
Location: arch/x86/mm/pageattr.c:1312
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
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
In arch/x86/mm/pageattr.c (ffffffff81079369)
Location: arch/x86/mm/pageattr.c:1317
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
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
In arch/x86/mm/pageattr.c (ffffffff8107fd15)
Location: arch/x86/mm/pageattr.c:1553
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
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
In arch/x86/mm/pageattr.c (ffffffff81083698)
Location: arch/x86/mm/pageattr.c:1564
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
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
In arch/x86/mm/pageattr.c (ffffffff81084768)
Location: arch/x86/mm/pageattr.c:1564
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cpa_process_alias(struct cpa_data *cpa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108e360)
Location: arch/x86/mm/pat/set_memory.c:1584
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr_set_clr
```
**Symbols:**

```
ffffffff8108e360-ffffffff8108e53d: cpa_process_alias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cpa_process_alias(struct cpa_data *cpa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108e230)
Location: arch/x86/mm/pat/set_memory.c:1584
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr_set_clr
```
**Symbols:**

```
ffffffff8108e230-ffffffff8108e40d: cpa_process_alias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cpa_process_alias(struct cpa_data *cpa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108edf0)
Location: arch/x86/mm/pat/set_memory.c:1592
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr_set_clr
```
**Symbols:**

```
ffffffff8108edf0-ffffffff8108efcd: cpa_process_alias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int cpa_process_alias(struct cpa_data *cpa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8109e8a0)
Location: arch/x86/mm/pat/set_memory.c:1592
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr_set_clr
```
**Symbols:**

```
ffffffff8109e8a0-ffffffff8109ea7d: cpa_process_alias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int cpa_process_alias(struct cpa_data *cpa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810b2280)
Location: arch/x86/mm/pat/set_memory.c:1584
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr_set_clr
```
**Symbols:**

```
ffffffff810b2280-ffffffff810b247c: cpa_process_alias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cpa_process_alias(struct cpa_data *cpa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810ccb90)
Location: arch/x86/mm/pat/set_memory.c:1667
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr_set_clr
```
**Symbols:**

```
ffffffff810ccb90-ffffffff810ccdd0: cpa_process_alias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cpa_process_alias(struct cpa_data *cpa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810d01c0)
Location: arch/x86/mm/pat/set_memory.c:1668
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr_set_clr
```
**Symbols:**

```
ffffffff810d01c0-ffffffff810d0400: cpa_process_alias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cpa_process_alias(struct cpa_data *cpa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810d88a0)
Location: arch/x86/mm/pat/set_memory.c:1672
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr_set_clr
```
**Symbols:**

```
ffffffff810d88a0-ffffffff810d8ae0: cpa_process_alias (STB_LOCAL)
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
In arch/x86/mm/pageattr.c (ffffffff81083768)
Location: arch/x86/mm/pageattr.c:1564
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
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
In arch/x86/mm/pageattr.c (ffffffff8107229b)
Location: arch/x86/mm/pageattr.c:1564
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
In arch/x86/mm/pageattr.c (ffffffff81083718)
Location: arch/x86/mm/pageattr.c:1564
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
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
In arch/x86/mm/pageattr.c (ffffffff81085853)
Location: arch/x86/mm/pageattr.c:1564
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
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
