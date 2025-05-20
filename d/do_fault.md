# Function: <code>do_fault</code>

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
In mm/memory.c (ffffffff811bef91)
Location: mm/memory.c:3114
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
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
In mm/memory.c (ffffffff811db09f)
Location: mm/memory.c:3313
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
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
In mm/memory.c (ffffffff811eacc1)
Location: mm/memory.c:3344
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
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
In mm/memory.c (ffffffff811f5c3e)
Location: mm/memory.c:3548
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
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
In mm/memory.c (ffffffff8120d6c4)
Location: mm/memory.c:3717
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
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
In mm/memory.c (ffffffff8122e1a7)
Location: mm/memory.c:3762
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
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
In mm/memory.c (ffffffff81241f73)
Location: mm/memory.c:3525
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
vm_fault_t do_fault(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81253a60)
Location: mm/memory.c:3574
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffffffff81253a60-ffffffff8125409f: do_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
vm_fault_t do_fault(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81261fc0)
Location: mm/memory.c:3599
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffffffff81261fc0-ffffffff812625f6: do_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
vm_fault_t do_fault(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81292000)
Location: mm/memory.c:3960
Inline: False
Direct callers:
  - mm/memory.c:handle_pte_fault
```
**Symbols:**

```
ffffffff81292000-ffffffff812921f8: do_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
vm_fault_t do_fault(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8129c8c0)
Location: mm/memory.c:4120
Inline: False
Direct callers:
  - mm/memory.c:handle_pte_fault
```
**Symbols:**

```
ffffffff8129c8c0-ffffffff8129caa9: do_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
vm_fault_t do_fault(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812a1f00)
Location: mm/memory.c:4128
Inline: False
Direct callers:
  - mm/memory.c:handle_pte_fault
```
**Symbols:**

```
ffffffff812a1f00-ffffffff812a21be: do_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
vm_fault_t do_fault(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812e2e40)
Location: mm/memory.c:4275
Inline: False
Direct callers:
  - mm/memory.c:handle_pte_fault
```
**Symbols:**

```
ffffffff812e2e40-ffffffff812e3118: do_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
vm_fault_t do_fault(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81343770)
Location: mm/memory.c:4608
Inline: False
Direct callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_marker
```
**Symbols:**

```
ffffffff81343770-ffffffff81343a61: do_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
vm_fault_t do_fault(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813bb800)
Location: mm/memory.c:4611
Inline: False
Direct callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_marker
```
**Symbols:**

```
ffffffff813bb800-ffffffff813bbae8: do_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
vm_fault_t do_fault(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813f03c0)
Location: mm/memory.c:4641
Inline: False
Direct callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_marker
```
**Symbols:**

```
ffffffff813f03c0-ffffffff813f052c: do_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
vm_fault_t do_fault(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8141b940)
Location: mm/memory.c:4859
Inline: False
Direct callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_marker
```
**Symbols:**

```
ffffffff8141b940-ffffffff8141bc88: do_fault (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
vm_fault_t do_fault(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffff8000102f9280)
Location: mm/memory.c:3599
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffff8000102f9280-ffff8000102f9810: do_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
vm_fault_t do_fault(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c051b6b4)
Location: mm/memory.c:3599
Inline: False
Direct callers:
  - mm/memory.c:handle_mm_fault
```
**Symbols:**

```
c051b6b4-c051bc0c: do_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
vm_fault_t do_fault(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003c2e40)
Location: mm/memory.c:3599
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
c0000000003c2e40-c0000000003c3754: do_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
vm_fault_t do_fault(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffe000209274)
Location: mm/memory.c:3599
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffffffe000209274-ffffffe000209748: do_fault (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
vm_fault_t do_fault(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125a610)
Location: mm/memory.c:3599
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffffffff8125a610-ffffffff8125ac46: do_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
vm_fault_t do_fault(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8124ca30)
Location: mm/memory.c:3599
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffffffff8124ca30-ffffffff8124d011: do_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
vm_fault_t do_fault(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812583b0)
Location: mm/memory.c:3599
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffffffff812583b0-ffffffff812589e6: do_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
vm_fault_t do_fault(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81267d90)
Location: mm/memory.c:3599
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffffffff81267d90-ffffffff812683e4: do_fault (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
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
