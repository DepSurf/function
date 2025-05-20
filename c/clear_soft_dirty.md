# Function: <code>clear_soft_dirty</code>

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
In fs/proc/task_mmu.c (ffffffff81278f07)
Location: fs/proc/task_mmu.c:777
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In fs/proc/task_mmu.c (ffffffff812a598c)
Location: fs/proc/task_mmu.c:880
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In fs/proc/task_mmu.c (ffffffff812bb2d4)
Location: fs/proc/task_mmu.c:873
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In fs/proc/task_mmu.c (ffffffff812c6907)
Location: fs/proc/task_mmu.c:876
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In fs/proc/task_mmu.c (ffffffff812ece2a)
Location: fs/proc/task_mmu.c:951
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In fs/proc/task_mmu.c (ffffffff813192d4)
Location: fs/proc/task_mmu.c:939
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In fs/proc/task_mmu.c (ffffffff813308ec)
Location: fs/proc/task_mmu.c:942
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In fs/proc/task_mmu.c (ffffffff81358714)
Location: fs/proc/task_mmu.c:983
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In fs/proc/task_mmu.c (ffffffff81370964)
Location: fs/proc/task_mmu.c:991
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In fs/proc/task_mmu.c (ffffffff813b8e27)
Location: fs/proc/task_mmu.c:965
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void clear_soft_dirty(struct vm_area_struct *vma, long unsigned int addr, pte_t *pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff813c7f10)
Location: fs/proc/task_mmu.c:1060
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff813c7f10-ffffffff813c8030: clear_soft_dirty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void clear_soft_dirty(struct vm_area_struct *vma, long unsigned int addr, pte_t *pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff813cef40)
Location: fs/proc/task_mmu.c:1058
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff813cef40-ffffffff813cf060: clear_soft_dirty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void clear_soft_dirty(struct vm_area_struct *vma, long unsigned int addr, pte_t *pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff81420420)
Location: fs/proc/task_mmu.c:1074
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff81420420-ffffffff81420547: clear_soft_dirty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void clear_soft_dirty(struct vm_area_struct *vma, long unsigned int addr, pte_t *pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff8149a810)
Location: fs/proc/task_mmu.c:1090
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff8149a810-ffffffff8149a94a: clear_soft_dirty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void clear_soft_dirty(struct vm_area_struct *vma, long unsigned int addr, pte_t *pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff8152ed30)
Location: fs/proc/task_mmu.c:1107
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff8152ed30-ffffffff8152ee6a: clear_soft_dirty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void clear_soft_dirty(struct vm_area_struct *vma, long unsigned int addr, pte_t *pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff81567040)
Location: fs/proc/task_mmu.c:1102
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff81567040-ffffffff8156717a: clear_soft_dirty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void clear_soft_dirty(struct vm_area_struct *vma, long unsigned int addr, pte_t *pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff8159cbb0)
Location: fs/proc/task_mmu.c:1095
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff8159cbb0-ffffffff8159cd1e: clear_soft_dirty (STB_LOCAL)
```
</details>
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
In fs/proc/task_mmu.c (0)
Location: fs/proc/task_mmu.c:1015
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (0)
Location: fs/proc/task_mmu.c:1015
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (0)
Location: fs/proc/task_mmu.c:1015
Inline: True
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
In fs/proc/task_mmu.c (0)
Location: fs/proc/task_mmu.c:1015
Inline: True
```
</details>
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
In fs/proc/task_mmu.c (ffffffff81368f44)
Location: fs/proc/task_mmu.c:991
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In fs/proc/task_mmu.c (ffffffff8135a1dc)
Location: fs/proc/task_mmu.c:991
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In fs/proc/task_mmu.c (ffffffff81366a14)
Location: fs/proc/task_mmu.c:991
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In fs/proc/task_mmu.c (ffffffff8137a070)
Location: fs/proc/task_mmu.c:991
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
