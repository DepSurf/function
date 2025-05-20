# Function: <code>xen_update_mem_tables</code>

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
In arch/x86/xen/setup.c (ffffffff81f61237)
Location: arch/x86/xen/setup.c:287
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_remap_memory
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
In arch/x86/xen/setup.c (ffffffff81f893d9)
Location: arch/x86/xen/setup.c:287
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_remap_memory
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
In arch/x86/xen/setup.c (ffffffff81fc47cd)
Location: arch/x86/xen/setup.c:287
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_remap_memory
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
In arch/x86/xen/setup.c (ffffffff820a4627)
Location: arch/x86/xen/setup.c:286
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_remap_memory
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
In arch/x86/xen/setup.c (ffffffff826aad39)
Location: arch/x86/xen/setup.c:287
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_remap_memory
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
In arch/x86/xen/setup.c (ffffffff826d3eb8)
Location: arch/x86/xen/setup.c:287
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_remap_memory
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
In arch/x86/xen/setup.c (ffffffff82889f4b)
Location: arch/x86/xen/setup.c:287
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_remap_memory
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
In arch/x86/xen/setup.c (ffffffff828a12fc)
Location: arch/x86/xen/setup.c:288
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_remap_memory
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
In arch/x86/xen/setup.c (ffffffff828a43bc)
Location: arch/x86/xen/setup.c:288
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_remap_memory
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xen_update_mem_tables(long unsigned int pfn, long unsigned int mfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff82cc9f86)
Location: arch/x86/xen/setup.c:289
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_remap_memory
```
**Symbols:**

```
ffffffff82cc9f86-ffffffff82cca0ca: xen_update_mem_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xen_update_mem_tables(long unsigned int pfn, long unsigned int mfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff82fb5df4)
Location: arch/x86/xen/setup.c:288
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_remap_memory
```
**Symbols:**

```
ffffffff82fb5df4-ffffffff82fb5f38: xen_update_mem_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xen_update_mem_tables(long unsigned int pfn, long unsigned int mfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff831c05fd)
Location: arch/x86/xen/setup.c:288
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_remap_memory
```
**Symbols:**

```
ffffffff831c05fd-ffffffff831c0742: xen_update_mem_tables (STB_LOCAL)
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
In arch/x86/xen/setup.c (ffffffff832a1796)
Location: arch/x86/xen/setup.c:288
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_remap_memory
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
In arch/x86/xen/setup.c (ffffffff8345080e)
Location: arch/x86/xen/setup.c:288
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_remap_memory
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
In arch/x86/xen/setup.c (ffffffff83e6cd6e)
Location: arch/x86/xen/setup.c:289
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_remap_memory
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
In arch/x86/xen/setup.c (ffffffff8368d89e)
Location: arch/x86/xen/setup.c:290
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_remap_memory
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
In arch/x86/xen/setup.c (ffffffff838bd45e)
Location: arch/x86/xen/setup.c:293
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_remap_memory
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
In arch/x86/xen/setup.c (ffffffff828923e2)
Location: arch/x86/xen/setup.c:288
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_remap_memory
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
In arch/x86/xen/setup.c (ffffffff828a53bc)
Location: arch/x86/xen/setup.c:288
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_remap_memory
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
In arch/x86/xen/setup.c (ffffffff828a5390)
Location: arch/x86/xen/setup.c:288
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_remap_memory
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
</ul>
