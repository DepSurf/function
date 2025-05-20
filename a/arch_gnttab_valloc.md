# Function: <code>arch_gnttab_valloc</code>

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
In arch/x86/xen/grant-table.c (ffffffff81023e12)
Location: arch/x86/xen/grant-table.c:90
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_init
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
In arch/x86/xen/grant-table.c (ffffffff810230b2)
Location: arch/x86/xen/grant-table.c:90
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_init
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
In arch/x86/xen/grant-table.c (ffffffff81023802)
Location: arch/x86/xen/grant-table.c:90
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_init
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
In arch/x86/xen/grant-table.c (ffffffff8101b4e2)
Location: arch/x86/xen/grant-table.c:90
Inline: True
Inline callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int arch_gnttab_valloc(struct gnttab_vm_area *area, unsigned int nr_frames);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff8101bf10)
Location: arch/x86/xen/grant-table.c:117
Inline: False
Direct callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_init
  - arch/x86/xen/grant-table.c:arch_gnttab_init
```
**Symbols:**

```
ffffffff8101bf10-ffffffff8101bf74: arch_gnttab_valloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff8101c8e0)
Location: arch/x86/xen/grant-table.c:117
Inline: True
Direct callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_init
  - arch/x86/xen/grant-table.c:arch_gnttab_init
```
**Symbols:**

```
ffffffff8101c8e0-ffffffff8101c949: arch_gnttab_valloc.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff8101c170)
Location: arch/x86/xen/grant-table.c:94
Inline: True
Direct callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_init
  - arch/x86/xen/grant-table.c:arch_gnttab_init
```
**Symbols:**

```
ffffffff8101c170-ffffffff8101c1d9: arch_gnttab_valloc.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff8101dcd0)
Location: arch/x86/xen/grant-table.c:94
Inline: True
Direct callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_init
  - arch/x86/xen/grant-table.c:arch_gnttab_init
```
**Symbols:**

```
ffffffff8101dcd0-ffffffff8101dd39: arch_gnttab_valloc.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff8101e650)
Location: arch/x86/xen/grant-table.c:94
Inline: True
Direct callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_init
  - arch/x86/xen/grant-table.c:arch_gnttab_init
```
**Symbols:**

```
ffffffff8101e650-ffffffff8101e6b9: arch_gnttab_valloc.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int arch_gnttab_valloc(struct gnttab_vm_area *area, unsigned int nr_frames);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff81020bf0)
Location: arch/x86/xen/grant-table.c:93
Inline: False
Direct callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_init
  - arch/x86/xen/grant-table.c:arch_gnttab_init
```
**Symbols:**

```
ffffffff81020bf0-ffffffff81020c54: arch_gnttab_valloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int arch_gnttab_valloc(struct gnttab_vm_area *area, unsigned int nr_frames);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff81021470)
Location: arch/x86/xen/grant-table.c:102
Inline: False
Direct callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_init
  - arch/x86/xen/grant-table.c:arch_gnttab_init
```
**Symbols:**

```
ffffffff81021470-ffffffff810214ff: arch_gnttab_valloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int arch_gnttab_valloc(struct gnttab_vm_area *area, unsigned int nr_frames);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff81023810)
Location: arch/x86/xen/grant-table.c:102
Inline: False
Direct callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_init
  - arch/x86/xen/grant-table.c:arch_gnttab_init
```
**Symbols:**

```
ffffffff81023810-ffffffff8102389f: arch_gnttab_valloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int arch_gnttab_valloc(struct gnttab_vm_area *area, unsigned int nr_frames);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff81027ab0)
Location: arch/x86/xen/grant-table.c:102
Inline: False
Direct callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_init
  - arch/x86/xen/grant-table.c:arch_gnttab_init
```
**Symbols:**

```
ffffffff81027ab0-ffffffff81027b3f: arch_gnttab_valloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int arch_gnttab_valloc(struct gnttab_vm_area *area, unsigned int nr_frames);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff8102bee0)
Location: arch/x86/xen/grant-table.c:102
Inline: False
Direct callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_init
  - arch/x86/xen/grant-table.c:arch_gnttab_init
```
**Symbols:**

```
ffffffff8102bee0-ffffffff8102bf76: arch_gnttab_valloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int arch_gnttab_valloc(struct gnttab_vm_area *area, unsigned int nr_frames);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff81032df0)
Location: arch/x86/xen/grant-table.c:102
Inline: False
Direct callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_init
  - arch/x86/xen/grant-table.c:arch_gnttab_init
```
**Symbols:**

```
ffffffff81032df0-ffffffff81032e86: arch_gnttab_valloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int arch_gnttab_valloc(struct gnttab_vm_area *area, unsigned int nr_frames);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff81032d90)
Location: arch/x86/xen/grant-table.c:102
Inline: False
Direct callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_init
  - arch/x86/xen/grant-table.c:arch_gnttab_init
```
**Symbols:**

```
ffffffff81032d90-ffffffff81032e26: arch_gnttab_valloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int arch_gnttab_valloc(struct gnttab_vm_area *area, unsigned int nr_frames);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff81039080)
Location: arch/x86/xen/grant-table.c:102
Inline: False
Direct callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_init
  - arch/x86/xen/grant-table.c:arch_gnttab_init
```
**Symbols:**

```
ffffffff81039080-ffffffff81039116: arch_gnttab_valloc (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff8101e660)
Location: arch/x86/xen/grant-table.c:94
Inline: True
Direct callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_init
  - arch/x86/xen/grant-table.c:arch_gnttab_init
```
**Symbols:**

```
ffffffff8101e660-ffffffff8101e6c9: arch_gnttab_valloc.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff8101e610)
Location: arch/x86/xen/grant-table.c:94
Inline: True
Direct callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_init
  - arch/x86/xen/grant-table.c:arch_gnttab_init
```
**Symbols:**

```
ffffffff8101e610-ffffffff8101e679: arch_gnttab_valloc.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff8101e860)
Location: arch/x86/xen/grant-table.c:94
Inline: True
Direct callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_init
  - arch/x86/xen/grant-table.c:arch_gnttab_init
```
**Symbols:**

```
ffffffff8101e860-ffffffff8101e8c9: arch_gnttab_valloc.isra.0 (STB_LOCAL)
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
