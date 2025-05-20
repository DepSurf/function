# Function: <code>read_agp</code>

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
In arch/x86/kernel/aperture_64.c (ffffffff81f7572a)
Location: arch/x86/kernel/aperture_64.c:121
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
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
In arch/x86/kernel/aperture_64.c (ffffffff81f9df61)
Location: arch/x86/kernel/aperture_64.c:121
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
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
In arch/x86/kernel/aperture_64.c (ffffffff81fd94e4)
Location: arch/x86/kernel/aperture_64.c:121
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
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
In arch/x86/kernel/aperture_64.c (ffffffff820ba34b)
Location: arch/x86/kernel/aperture_64.c:121
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
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
In arch/x86/kernel/aperture_64.c (ffffffff826c0cfa)
Location: arch/x86/kernel/aperture_64.c:150
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
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
In arch/x86/kernel/aperture_64.c (ffffffff826eaf09)
Location: arch/x86/kernel/aperture_64.c:150
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
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
In arch/x86/kernel/aperture_64.c (ffffffff828a1b31)
Location: arch/x86/kernel/aperture_64.c:124
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
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
In arch/x86/kernel/aperture_64.c (ffffffff828b9df4)
Location: arch/x86/kernel/aperture_64.c:130
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
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
In arch/x86/kernel/aperture_64.c (ffffffff828c02d7)
Location: arch/x86/kernel/aperture_64.c:130
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u32 read_agp(int bus, int slot, int func, int cap, u32 *order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/aperture_64.c (ffffffff82ce464d)
Location: arch/x86/kernel/aperture_64.c:130
Inline: False
Direct callers:
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
```
**Symbols:**

```
ffffffff82ce464d-ffffffff82ce47fd: read_agp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u32 read_agp(int bus, int slot, int func, int cap, u32 *order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/aperture_64.c (ffffffff82fd1eae)
Location: arch/x86/kernel/aperture_64.c:130
Inline: False
Direct callers:
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
```
**Symbols:**

```
ffffffff82fd1eae-ffffffff82fd205e: read_agp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u32 read_agp(int bus, int slot, int func, int cap, u32 *order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/aperture_64.c (ffffffff831dcaaf)
Location: arch/x86/kernel/aperture_64.c:130
Inline: False
Direct callers:
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
```
**Symbols:**

```
ffffffff831dcaaf-ffffffff831dcc53: read_agp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u32 read_agp(int bus, int slot, int func, int cap, u32 *order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/aperture_64.c (ffffffff832bfb81)
Location: arch/x86/kernel/aperture_64.c:129
Inline: False
Direct callers:
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
```
**Symbols:**

```
ffffffff832bfb81-ffffffff832bfe07: read_agp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u32 read_agp(int bus, int slot, int func, int cap, u32 *order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/aperture_64.c (ffffffff83472034)
Location: arch/x86/kernel/aperture_64.c:140
Inline: False
```
**Symbols:**

```
ffffffff83472034-ffffffff834722ce: read_agp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u32 read_agp(int bus, int slot, int func, int cap, u32 *order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/aperture_64.c (ffffffff83e994e0)
Location: arch/x86/kernel/aperture_64.c:140
Inline: False
```
**Symbols:**

```
ffffffff83e994e0-ffffffff83e9983c: read_agp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u32 read_agp(int bus, int slot, int func, int cap, u32 *order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/aperture_64.c (ffffffff836bcf00)
Location: arch/x86/kernel/aperture_64.c:140
Inline: False
```
**Symbols:**

```
ffffffff836bcf00-ffffffff836bd250: read_agp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u32 read_agp(int bus, int slot, int func, int cap, u32 *order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/aperture_64.c (ffffffff838ed9c0)
Location: arch/x86/kernel/aperture_64.c:140
Inline: False
```
**Symbols:**

```
ffffffff838ed9c0-ffffffff838edd10: read_agp (STB_LOCAL)
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
In arch/x86/kernel/aperture_64.c (ffffffff828ab2ad)
Location: arch/x86/kernel/aperture_64.c:130
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
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
In arch/x86/kernel/aperture_64.c (ffffffff828a3574)
Location: arch/x86/kernel/aperture_64.c:130
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
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
In arch/x86/kernel/aperture_64.c (ffffffff828be1ac)
Location: arch/x86/kernel/aperture_64.c:130
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
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
In arch/x86/kernel/aperture_64.c (ffffffff828c12f9)
Location: arch/x86/kernel/aperture_64.c:130
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
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
