# Function: <code>numa_add_memblk_to</code>

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
In arch/x86/mm/numa.c (ffffffff81f782f0)
Location: arch/x86/mm/numa.c:131
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_add_memblk
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
In arch/x86/mm/numa.c (ffffffff81fa0aab)
Location: arch/x86/mm/numa.c:130
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_add_memblk
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
In arch/x86/mm/numa.c (ffffffff81fdc372)
Location: arch/x86/mm/numa.c:130
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_add_memblk
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
In arch/x86/mm/numa.c (ffffffff820bd38e)
Location: arch/x86/mm/numa.c:130
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_add_memblk
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
In arch/x86/mm/numa.c (ffffffff826c41cd)
Location: arch/x86/mm/numa.c:130
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_add_memblk
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
In arch/x86/mm/numa.c (ffffffff826ee468)
Location: arch/x86/mm/numa.c:130
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_add_memblk
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
In arch/x86/mm/numa.c (ffffffff828a5156)
Location: arch/x86/mm/numa.c:129
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_add_memblk
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
In arch/x86/mm/numa.c (ffffffff828bd6d6)
Location: arch/x86/mm/numa.c:130
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_add_memblk
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
In arch/x86/mm/numa.c (ffffffff828c3b60)
Location: arch/x86/mm/numa.c:130
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_add_memblk
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
In arch/x86/mm/numa.c (ffffffff82ce714e)
Location: arch/x86/mm/numa.c:127
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_add_memblk
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
In arch/x86/mm/numa.c (ffffffff82fd4ac3)
Location: arch/x86/mm/numa.c:125
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_add_memblk
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int numa_add_memblk_to(int nid, u64 start, u64 end, struct numa_meminfo *mi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff831def8f)
Location: arch/x86/mm/numa.c:125
Inline: False
Direct callers:
  - arch/x86/mm/numa.c:numa_cleanup_meminfo
  - arch/x86/mm/numa.c:numa_add_memblk
```
**Symbols:**

```
ffffffff831def8f-ffffffff831df005: numa_add_memblk_to (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int numa_add_memblk_to(int nid, u64 start, u64 end, struct numa_meminfo *mi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff832c24b4)
Location: arch/x86/mm/numa.c:125
Inline: False
Direct callers:
  - arch/x86/mm/numa.c:numa_cleanup_meminfo
  - arch/x86/mm/numa.c:numa_add_memblk
```
**Symbols:**

```
ffffffff832c24b4-ffffffff832c252a: numa_add_memblk_to (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int numa_add_memblk_to(int nid, u64 start, u64 end, struct numa_meminfo *mi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff83474c93)
Location: arch/x86/mm/numa.c:125
Inline: False
Direct callers:
  - arch/x86/mm/numa.c:numa_cleanup_meminfo
  - arch/x86/mm/numa.c:numa_add_memblk
```
**Symbols:**

```
ffffffff83474c93-ffffffff83474d26: numa_add_memblk_to (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int numa_add_memblk_to(int nid, u64 start, u64 end, struct numa_meminfo *mi);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff83e9d1c0)
Location: arch/x86/mm/numa.c:125
Inline: True
Direct callers:
  - arch/x86/mm/numa.c:dummy_numa_init
  - arch/x86/mm/numa.c:numa_cleanup_meminfo
```
**Symbols:**

```
ffffffff83e9d1c0-ffffffff83e9d263: numa_add_memblk_to (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int numa_add_memblk_to(int nid, u64 start, u64 end, struct numa_meminfo *mi);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff836c0cb0)
Location: arch/x86/mm/numa.c:125
Inline: True
Direct callers:
  - arch/x86/mm/numa.c:dummy_numa_init
  - arch/x86/mm/numa.c:numa_cleanup_meminfo
```
**Symbols:**

```
ffffffff836c0cb0-ffffffff836c0df3: numa_add_memblk_to (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int numa_add_memblk_to(int nid, u64 start, u64 end, struct numa_meminfo *mi);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff838f1820)
Location: arch/x86/mm/numa.c:127
Inline: True
Direct callers:
  - arch/x86/mm/numa.c:dummy_numa_init
  - arch/x86/mm/numa.c:numa_cleanup_meminfo
```
**Symbols:**

```
ffffffff838f1820-ffffffff838f1963: numa_add_memblk_to (STB_LOCAL)
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
In arch/x86/mm/numa.c (ffffffff828aeb36)
Location: arch/x86/mm/numa.c:130
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_add_memblk
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
In arch/x86/mm/numa.c (ffffffff828a6d28)
Location: arch/x86/mm/numa.c:130
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_add_memblk
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
In arch/x86/mm/numa.c (ffffffff828c1a35)
Location: arch/x86/mm/numa.c:130
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_add_memblk
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
In arch/x86/mm/numa.c (ffffffff828c4b80)
Location: arch/x86/mm/numa.c:130
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_add_memblk
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
