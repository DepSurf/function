# Function: <code>split_set_pte</code>

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
In arch/x86/mm/pageattr.c (ffffffff8107f381)
Location: arch/x86/mm/pageattr.c:894
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
In arch/x86/mm/pageattr.c (ffffffff81082bb1)
Location: arch/x86/mm/pageattr.c:903
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__split_large_page
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
In arch/x86/mm/pageattr.c (ffffffff81083c81)
Location: arch/x86/mm/pageattr.c:903
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__split_large_page
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
In arch/x86/mm/pat/set_memory.c (ffffffff8108d971)
Location: arch/x86/mm/pat/set_memory.c:923
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__split_large_page
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
In arch/x86/mm/pat/set_memory.c (ffffffff8108d841)
Location: arch/x86/mm/pat/set_memory.c:923
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__split_large_page
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
In arch/x86/mm/pat/set_memory.c (ffffffff8108e3c9)
Location: arch/x86/mm/pat/set_memory.c:931
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__split_large_page
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
In arch/x86/mm/pat/set_memory.c (ffffffff8109deaf)
Location: arch/x86/mm/pat/set_memory.c:931
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__split_large_page
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
In arch/x86/mm/pat/set_memory.c (ffffffff810b17f5)
Location: arch/x86/mm/pat/set_memory.c:923
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__split_large_page
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
In arch/x86/mm/pat/set_memory.c (ffffffff810cbf35)
Location: arch/x86/mm/pat/set_memory.c:1000
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__split_large_page
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
In arch/x86/mm/pat/set_memory.c (ffffffff810cf57e)
Location: arch/x86/mm/pat/set_memory.c:1001
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__split_large_page
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
In arch/x86/mm/pat/set_memory.c (ffffffff810d7c5e)
Location: arch/x86/mm/pat/set_memory.c:1005
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__split_large_page
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
In arch/x86/mm/pageattr.c (ffffffff81082c81)
Location: arch/x86/mm/pageattr.c:903
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__split_large_page
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
In arch/x86/mm/pageattr.c (ffffffff81071977)
Location: arch/x86/mm/pageattr.c:903
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
In arch/x86/mm/pageattr.c (ffffffff81082c31)
Location: arch/x86/mm/pageattr.c:903
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__split_large_page
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
In arch/x86/mm/pageattr.c (ffffffff81084d4f)
Location: arch/x86/mm/pageattr.c:903
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__split_large_page
```
</details>
</li>
</ul>

## Differences
