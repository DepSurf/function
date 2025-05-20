# Function: <code>alloc_p2m_pmd</code>

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
In arch/x86/xen/p2m.c (ffffffff81024a66)
Location: arch/x86/xen/p2m.c:470
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
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
In arch/x86/xen/p2m.c (ffffffff81023d96)
Location: arch/x86/xen/p2m.c:470
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
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
In arch/x86/xen/p2m.c (ffffffff810244c6)
Location: arch/x86/xen/p2m.c:470
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
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
In arch/x86/xen/p2m.c (ffffffff8101d5c3)
Location: arch/x86/xen/p2m.c:470
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
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
In arch/x86/xen/p2m.c (ffffffff8101e36b)
Location: arch/x86/xen/p2m.c:463
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
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
In arch/x86/xen/p2m.c (0)
Location: arch/x86/xen/p2m.c:463
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
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
In arch/x86/xen/p2m.c (0)
Location: arch/x86/xen/p2m.c:465
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
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
In arch/x86/xen/p2m.c (0)
Location: arch/x86/xen/p2m.c:472
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
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
In arch/x86/xen/p2m.c (0)
Location: arch/x86/xen/p2m.c:472
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
pte_t *alloc_p2m_pmd(long unsigned int addr, pte_t *pte_pg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff81022db0)
Location: arch/x86/xen/p2m.c:472
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
**Symbols:**

```
ffffffff81022db0-ffffffff81022f81: alloc_p2m_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
pte_t *alloc_p2m_pmd(long unsigned int addr, pte_t *pte_pg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff81023380)
Location: arch/x86/xen/p2m.c:468
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
**Symbols:**

```
ffffffff81023380-ffffffff81023551: alloc_p2m_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
pte_t *alloc_p2m_pmd(long unsigned int addr, pte_t *pte_pg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff81025830)
Location: arch/x86/xen/p2m.c:468
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
**Symbols:**

```
ffffffff81025830-ffffffff81025a04: alloc_p2m_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
pte_t *alloc_p2m_pmd(long unsigned int addr, pte_t *pte_pg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff81029d40)
Location: arch/x86/xen/p2m.c:468
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
**Symbols:**

```
ffffffff81029d40-ffffffff81029f14: alloc_p2m_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
pte_t *alloc_p2m_pmd(long unsigned int addr, pte_t *pte_pg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff8102e800)
Location: arch/x86/xen/p2m.c:468
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
**Symbols:**

```
ffffffff8102e800-ffffffff8102e9ec: alloc_p2m_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
pte_t *alloc_p2m_pmd(long unsigned int addr, pte_t *pte_pg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff81035800)
Location: arch/x86/xen/p2m.c:463
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
**Symbols:**

```
ffffffff81035800-ffffffff810359e7: alloc_p2m_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
pte_t *alloc_p2m_pmd(long unsigned int addr, pte_t *pte_pg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff81035780)
Location: arch/x86/xen/p2m.c:463
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
**Symbols:**

```
ffffffff81035780-ffffffff81035967: alloc_p2m_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
pte_t *alloc_p2m_pmd(long unsigned int addr, pte_t *pte_pg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff8103bce0)
Location: arch/x86/xen/p2m.c:463
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
**Symbols:**

```
ffffffff8103bce0-ffffffff8103bec7: alloc_p2m_pmd (STB_LOCAL)
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
In arch/x86/xen/p2m.c (0)
Location: arch/x86/xen/p2m.c:472
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (0)
Location: arch/x86/xen/p2m.c:472
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
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
In arch/x86/xen/p2m.c (0)
Location: arch/x86/xen/p2m.c:472
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
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
