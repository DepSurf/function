# Function: <code>remap_oldmem_pfn_checked</code>

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
In fs/proc/vmcore.c (ffffffff812879e4)
Location: fs/proc/vmcore.c:343
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
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
In fs/proc/vmcore.c (ffffffff812b4d27)
Location: fs/proc/vmcore.c:345
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
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
In fs/proc/vmcore.c (ffffffff812ca5b7)
Location: fs/proc/vmcore.c:345
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
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
In fs/proc/vmcore.c (ffffffff812d7b4e)
Location: fs/proc/vmcore.c:345
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
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
In fs/proc/vmcore.c (ffffffff812fc22e)
Location: fs/proc/vmcore.c:345
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
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
In fs/proc/vmcore.c (ffffffff81329dbb)
Location: fs/proc/vmcore.c:459
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
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
In fs/proc/vmcore.c (ffffffff81340beb)
Location: fs/proc/vmcore.c:481
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
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
In fs/proc/vmcore.c (ffffffff81368fb5)
Location: fs/proc/vmcore.c:486
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
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
In fs/proc/vmcore.c (ffffffff81381215)
Location: fs/proc/vmcore.c:486
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int remap_oldmem_pfn_checked(struct vm_area_struct *vma, long unsigned int from, long unsigned int pfn, long unsigned int size, pgprot_t prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff813cb440)
Location: fs/proc/vmcore.c:486
Inline: False
Direct callers:
  - fs/proc/vmcore.c:mmap_vmcore
```
**Symbols:**

```
ffffffff813cb440-ffffffff813cb57b: remap_oldmem_pfn_checked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int remap_oldmem_pfn_checked(struct vm_area_struct *vma, long unsigned int from, long unsigned int pfn, long unsigned int size, pgprot_t prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff813dd0f0)
Location: fs/proc/vmcore.c:486
Inline: False
Direct callers:
  - fs/proc/vmcore.c:mmap_vmcore
```
**Symbols:**

```
ffffffff813dd0f0-ffffffff813dd22b: remap_oldmem_pfn_checked (STB_LOCAL)
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
In fs/proc/vmcore.c (ffffffff813e4303)
Location: fs/proc/vmcore.c:486
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
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
In fs/proc/vmcore.c (ffffffff81435eb3)
Location: fs/proc/vmcore.c:490
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
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
In fs/proc/vmcore.c (ffffffff814b02ce)
Location: fs/proc/vmcore.c:502
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
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
In fs/proc/vmcore.c (ffffffff81546b78)
Location: fs/proc/vmcore.c:501
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
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
In fs/proc/vmcore.c (ffffffff8157e657)
Location: fs/proc/vmcore.c:501
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
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
In fs/proc/vmcore.c (ffffffff815b7097)
Location: fs/proc/vmcore.c:501
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
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
In fs/proc/vmcore.c (ffff80001044eef4)
Location: fs/proc/vmcore.c:486
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
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
In fs/proc/vmcore.c (c0612420)
Location: fs/proc/vmcore.c:486
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
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
In fs/proc/vmcore.c (c000000000566ab8)
Location: fs/proc/vmcore.c:486
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
```
</details>
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
In fs/proc/vmcore.c (ffffffff813797f5)
Location: fs/proc/vmcore.c:486
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
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
In fs/proc/vmcore.c (ffffffff8136a2c5)
Location: fs/proc/vmcore.c:486
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
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
In fs/proc/vmcore.c (ffffffff813772c5)
Location: fs/proc/vmcore.c:486
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
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
In fs/proc/vmcore.c (ffffffff8138ad75)
Location: fs/proc/vmcore.c:486
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
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
</ul>
