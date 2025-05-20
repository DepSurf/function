# Function: <code>phys_p4d_init</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff819026f3)
Location: arch/x86/mm/init_64.c:628
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
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
In arch/x86/mm/init_64.c (ffffffff8198c675)
Location: arch/x86/mm/init_64.c:628
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
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
In arch/x86/mm/init_64.c (ffffffff819e8f3a)
Location: arch/x86/mm/init_64.c:639
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
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
In arch/x86/mm/init_64.c (ffffffff81a247be)
Location: arch/x86/mm/init_64.c:636
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
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
In arch/x86/mm/init_64.c (ffffffff81a94b0e)
Location: arch/x86/mm/init_64.c:671
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
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
In arch/x86/mm/init_64.c (ffffffff81acc3f1)
Location: arch/x86/mm/init_64.c:671
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int phys_p4d_init(p4d_t *p4d_page, long unsigned int paddr, long unsigned int paddr_end, long unsigned int page_size_mask, pgprot_t prot, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81bc4bbb)
Location: arch/x86/mm/init_64.c:679
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
```
**Symbols:**

```
ffffffff81bc4bbb-ffffffff81bc4e2e: phys_p4d_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int phys_p4d_init(p4d_t *p4d_page, long unsigned int paddr, long unsigned int paddr_end, long unsigned int page_size_mask, pgprot_t prot, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81c3dab4)
Location: arch/x86/mm/init_64.c:674
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
```
**Symbols:**

```
ffffffff81c3dab4-ffffffff81c3dd27: phys_p4d_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int phys_p4d_init(p4d_t *p4d_page, long unsigned int paddr, long unsigned int paddr_end, long unsigned int page_size_mask, pgprot_t prot, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81c2fdf8)
Location: arch/x86/mm/init_64.c:674
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
```
**Symbols:**

```
ffffffff81c2fdf8-ffffffff81c3006a: phys_p4d_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int phys_p4d_init(p4d_t *p4d_page, long unsigned int paddr, long unsigned int paddr_end, long unsigned int page_size_mask, pgprot_t prot, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81d4e547)
Location: arch/x86/mm/init_64.c:675
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
```
**Symbols:**

```
ffffffff81d4e547-ffffffff81d4e7b9: phys_p4d_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int phys_p4d_init(p4d_t *p4d_page, long unsigned int paddr, long unsigned int paddr_end, long unsigned int page_size_mask, pgprot_t prot, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81f1e31f)
Location: arch/x86/mm/init_64.c:674
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
```
**Symbols:**

```
ffffffff81f1e31f-ffffffff81f1e5ac: phys_p4d_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int phys_p4d_init(p4d_t *p4d_page, long unsigned int paddr, long unsigned int paddr_end, long unsigned int page_size_mask, pgprot_t prot, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff820c6af0)
Location: arch/x86/mm/init_64.c:675
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
```
**Symbols:**

```
ffffffff820c6af0-ffffffff820c6eb5: phys_p4d_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int phys_p4d_init(p4d_t *p4d_page, long unsigned int paddr, long unsigned int paddr_end, long unsigned int page_size_mask, pgprot_t prot, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8214ab40)
Location: arch/x86/mm/init_64.c:675
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
```
**Symbols:**

```
ffffffff8214ab40-ffffffff8214af30: phys_p4d_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int phys_p4d_init(p4d_t *p4d_page, long unsigned int paddr, long unsigned int paddr_end, long unsigned int page_size_mask, pgprot_t prot, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8222d5f0)
Location: arch/x86/mm/init_64.c:675
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
```
**Symbols:**

```
ffffffff8222d5f0-ffffffff8222d9e0: phys_p4d_init (STB_LOCAL)
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
In arch/x86/mm/init_64.c (ffffffff81a6b261)
Location: arch/x86/mm/init_64.c:671
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
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
In arch/x86/mm/init_64.c (ffffffff81a27826)
Location: arch/x86/mm/init_64.c:671
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
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
In arch/x86/mm/init_64.c (ffffffff81ad7671)
Location: arch/x86/mm/init_64.c:671
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
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
In arch/x86/mm/init_64.c (ffffffff81ae3b31)
Location: arch/x86/mm/init_64.c:671
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
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
