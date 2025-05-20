# Function: <code>process_vm_rw_single_vec</code>

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
In mm/process_vm_access.c (ffffffff811d0890)
Location: mm/process_vm_access.c:77
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
In mm/process_vm_access.c (ffffffff811ed9d9)
Location: mm/process_vm_access.c:77
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
In mm/process_vm_access.c (ffffffff811fe2ae)
Location: mm/process_vm_access.c:77
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
In mm/process_vm_access.c (ffffffff81208e8e)
Location: mm/process_vm_access.c:78
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
In mm/process_vm_access.c (ffffffff81221fbe)
Location: mm/process_vm_access.c:78
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
In mm/process_vm_access.c (ffffffff81243ecd)
Location: mm/process_vm_access.c:78
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
In mm/process_vm_access.c (ffffffff812585cd)
Location: mm/process_vm_access.c:78
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
In mm/process_vm_access.c (ffffffff8126bd6c)
Location: mm/process_vm_access.c:74
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
In mm/process_vm_access.c (ffffffff8127ab7c)
Location: mm/process_vm_access.c:74
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int process_vm_rw_single_vec(long unsigned int addr, long unsigned int len, struct iov_iter *iter, struct page **process_pages, struct mm_struct *mm, struct task_struct *task, int vm_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/process_vm_access.c (ffffffff812acbf0)
Location: mm/process_vm_access.c:73
Inline: False
```
**Symbols:**

```
ffffffff812acbf0-ffffffff812acdff: process_vm_rw_single_vec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/process_vm_access.c (ffffffff812b87f0)
Location: mm/process_vm_access.c:71
Inline: True
```
**Symbols:**

```
ffffffff812b87f0-ffffffff812b8a2e: process_vm_rw_single_vec.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/process_vm_access.c (ffffffff812bdcc0)
Location: mm/process_vm_access.c:70
Inline: True
```
**Symbols:**

```
ffffffff812bdcc0-ffffffff812bdef8: process_vm_rw_single_vec.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/process_vm_access.c (ffffffff81300470)
Location: mm/process_vm_access.c:70
Inline: True
```
**Symbols:**

```
ffffffff81300470-ffffffff813006a2: process_vm_rw_single_vec.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/process_vm_access.c (ffffffff813677f0)
Location: mm/process_vm_access.c:70
Inline: True
```
**Symbols:**

```
ffffffff813677f0-ffffffff81367a45: process_vm_rw_single_vec.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/process_vm_access.c (ffffffff813e37b0)
Location: mm/process_vm_access.c:70
Inline: True
```
**Symbols:**

```
ffffffff813e37b0-ffffffff813e3a05: process_vm_rw_single_vec.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/process_vm_access.c (ffffffff81418500)
Location: mm/process_vm_access.c:70
Inline: True
```
**Symbols:**

```
ffffffff81418500-ffffffff81418753: process_vm_rw_single_vec.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/process_vm_access.c (ffffffff81445050)
Location: mm/process_vm_access.c:73
Inline: True
```
**Symbols:**

```
ffffffff81445050-ffffffff814452a3: process_vm_rw_single_vec.isra.0 (STB_LOCAL)
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
In mm/process_vm_access.c (ffff8000103121b0)
Location: mm/process_vm_access.c:74
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
In mm/process_vm_access.c (c052d000)
Location: mm/process_vm_access.c:74
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
In mm/process_vm_access.c (c0000000003e2fd8)
Location: mm/process_vm_access.c:74
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
In mm/process_vm_access.c (ffffffe000219826)
Location: mm/process_vm_access.c:74
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
In mm/process_vm_access.c (ffffffff812731cc)
Location: mm/process_vm_access.c:74
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
In mm/process_vm_access.c (ffffffff8126513c)
Location: mm/process_vm_access.c:74
Inline: True
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
In mm/process_vm_access.c (ffffffff81270f6c)
Location: mm/process_vm_access.c:74
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
In mm/process_vm_access.c (ffffffff812809dc)
Location: mm/process_vm_access.c:74
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
