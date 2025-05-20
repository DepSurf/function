# Function: <code>xen_phys_memcpy</code>

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
In arch/x86/xen/setup.c (ffffffff81f61985)
Location: arch/x86/xen/setup.c:688
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_memory_setup
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
In arch/x86/xen/setup.c (ffffffff81f89af4)
Location: arch/x86/xen/setup.c:673
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_memory_setup
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
In arch/x86/xen/setup.c (ffffffff81fc4eee)
Location: arch/x86/xen/setup.c:673
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_memory_setup
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
In arch/x86/xen/setup.c (ffffffff820a4d15)
Location: arch/x86/xen/setup.c:669
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_memory_setup
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
In arch/x86/xen/setup.c (ffffffff826ab417)
Location: arch/x86/xen/setup.c:668
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_memory_setup
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
In arch/x86/xen/setup.c (ffffffff826d4590)
Location: arch/x86/xen/setup.c:668
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_memory_setup
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
In arch/x86/xen/setup.c (ffffffff8288a620)
Location: arch/x86/xen/setup.c:668
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_memory_setup
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
In arch/x86/xen/setup.c (ffffffff828a19e5)
Location: arch/x86/xen/setup.c:677
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_memory_setup
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
In arch/x86/xen/setup.c (ffffffff828a4aa5)
Location: arch/x86/xen/setup.c:677
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_memory_setup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xen_phys_memcpy(phys_addr_t dest, phys_addr_t src, phys_addr_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff82cca215)
Location: arch/x86/xen/setup.c:678
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
```
**Symbols:**

```
ffffffff82cca215-ffffffff82cca303: xen_phys_memcpy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xen_phys_memcpy(phys_addr_t dest, phys_addr_t src, phys_addr_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff82fb6083)
Location: arch/x86/xen/setup.c:674
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
```
**Symbols:**

```
ffffffff82fb6083-ffffffff82fb6171: xen_phys_memcpy (STB_LOCAL)
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
In arch/x86/xen/setup.c (ffffffff831c143f)
Location: arch/x86/xen/setup.c:674
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_memory_setup
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
In arch/x86/xen/setup.c (ffffffff832a1eec)
Location: arch/x86/xen/setup.c:674
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_memory_setup
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
In arch/x86/xen/setup.c (ffffffff83450f60)
Location: arch/x86/xen/setup.c:670
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_memory_setup
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xen_phys_memcpy(phys_addr_t dest, phys_addr_t src, phys_addr_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff83e6c250)
Location: arch/x86/xen/setup.c:671
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
```
**Symbols:**

```
ffffffff83e6c250-ffffffff83e6c35d: xen_phys_memcpy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xen_phys_memcpy(phys_addr_t dest, phys_addr_t src, phys_addr_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff8368cd20)
Location: arch/x86/xen/setup.c:672
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
```
**Symbols:**

```
ffffffff8368cd20-ffffffff8368ce2d: xen_phys_memcpy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xen_phys_memcpy(phys_addr_t dest, phys_addr_t src, phys_addr_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/setup.c (ffffffff838bc8e0)
Location: arch/x86/xen/setup.c:675
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
```
**Symbols:**

```
ffffffff838bc8e0-ffffffff838bc9ed: xen_phys_memcpy (STB_LOCAL)
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
In arch/x86/xen/setup.c (ffffffff82892abd)
Location: arch/x86/xen/setup.c:677
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_memory_setup
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
In arch/x86/xen/setup.c (ffffffff828a5aa5)
Location: arch/x86/xen/setup.c:677
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_memory_setup
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
In arch/x86/xen/setup.c (ffffffff828a5a79)
Location: arch/x86/xen/setup.c:677
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_memory_setup
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
