# Function: <code>do_numa_page</code>

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
In mm/memory.c (ffffffff811bf5cb)
Location: mm/memory.c:3149
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
In mm/memory.c (ffffffff811db2ee)
Location: mm/memory.c:3343
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
In mm/memory.c (ffffffff811eae3b)
Location: mm/memory.c:3382
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
In mm/memory.c (ffffffff811f5f57)
Location: mm/memory.c:3586
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
In mm/memory.c (ffffffff8120db85)
Location: mm/memory.c:3755
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
In mm/memory.c (ffffffff8122e601)
Location: mm/memory.c:3800
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
In mm/memory.c (ffffffff81242503)
Location: mm/memory.c:3590
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
vm_fault_t do_numa_page(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81251250)
Location: mm/memory.c:3639
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffffffff81251250-ffffffff8125155d: do_numa_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
vm_fault_t do_numa_page(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125f800)
Location: mm/memory.c:3664
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffffffff8125f800-ffffffff8125fb0d: do_numa_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
vm_fault_t do_numa_page(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8128fcb0)
Location: mm/memory.c:4025
Inline: False
Direct callers:
  - mm/memory.c:handle_pte_fault
```
**Symbols:**

```
ffffffff8128fcb0-ffffffff8128ff8d: do_numa_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
vm_fault_t do_numa_page(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8129a730)
Location: mm/memory.c:4185
Inline: False
Direct callers:
  - mm/memory.c:handle_pte_fault
```
**Symbols:**

```
ffffffff8129a730-ffffffff8129aa1b: do_numa_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
vm_fault_t do_numa_page(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8129fb90)
Location: mm/memory.c:4193
Inline: False
Direct callers:
  - mm/memory.c:handle_pte_fault
```
**Symbols:**

```
ffffffff8129fb90-ffffffff8129ff57: do_numa_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
vm_fault_t do_numa_page(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812e3170)
Location: mm/memory.c:4339
Inline: False
Direct callers:
  - mm/memory.c:handle_pte_fault
```
**Symbols:**

```
ffffffff812e3170-ffffffff812e3526: do_numa_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
vm_fault_t do_numa_page(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813444f0)
Location: mm/memory.c:4672
Inline: False
Direct callers:
  - mm/memory.c:handle_pte_fault
```
**Symbols:**

```
ffffffff813444f0-ffffffff813448ba: do_numa_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
vm_fault_t do_numa_page(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813bc640)
Location: mm/memory.c:4675
Inline: False
Direct callers:
  - mm/memory.c:handle_pte_fault
```
**Symbols:**

```
ffffffff813bc640-ffffffff813bcaa8: do_numa_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
vm_fault_t do_numa_page(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813f1050)
Location: mm/memory.c:4702
Inline: False
Direct callers:
  - mm/memory.c:handle_pte_fault
```
**Symbols:**

```
ffffffff813f1050-ffffffff813f14b2: do_numa_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
vm_fault_t do_numa_page(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8141bd40)
Location: mm/memory.c:4920
Inline: False
Direct callers:
  - mm/memory.c:handle_pte_fault
```
**Symbols:**

```
ffffffff8141bd40-ffffffff8141c314: do_numa_page (STB_LOCAL)
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
In mm/memory.c (ffff8000102fa000)
Location: mm/memory.c:3664
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
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
In mm/memory.c (0)
Location: mm/memory.c:3664
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
vm_fault_t do_numa_page(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003bf370)
Location: mm/memory.c:3664
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
c0000000003bf370-c0000000003bf880: do_numa_page (STB_LOCAL)
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
In mm/memory.c (0)
Location: mm/memory.c:3664
Inline: False
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
vm_fault_t do_numa_page(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81257e50)
Location: mm/memory.c:3664
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffffffff81257e50-ffffffff8125815d: do_numa_page (STB_LOCAL)
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
In mm/memory.c (ffffffff8124d9b4)
Location: mm/memory.c:3664
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
vm_fault_t do_numa_page(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81255bf0)
Location: mm/memory.c:3664
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffffffff81255bf0-ffffffff81255efd: do_numa_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
vm_fault_t do_numa_page(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81265680)
Location: mm/memory.c:3664
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffffffff81265680-ffffffff81265999: do_numa_page (STB_LOCAL)
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
