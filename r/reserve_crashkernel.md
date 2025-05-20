# Function: <code>reserve_crashkernel</code>

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
In arch/x86/kernel/setup.c (ffffffff81f66734)
Location: arch/x86/kernel/setup.c:553
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
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
In arch/x86/kernel/setup.c (ffffffff81f8e585)
Location: arch/x86/kernel/setup.c:556
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
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
In arch/x86/kernel/setup.c (ffffffff81fc991d)
Location: arch/x86/kernel/setup.c:556
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
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
In arch/x86/kernel/setup.c (ffffffff820aa061)
Location: arch/x86/kernel/setup.c:537
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
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
In arch/x86/kernel/setup.c (ffffffff826b0b35)
Location: arch/x86/kernel/setup.c:522
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
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
In arch/x86/kernel/setup.c (ffffffff826da1da)
Location: arch/x86/kernel/setup.c:520
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
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
In arch/x86/kernel/setup.c (ffffffff828905bf)
Location: arch/x86/kernel/setup.c:520
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void reserve_crashkernel();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (ffffffff828a716b)
Location: arch/x86/kernel/setup.c:530
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
```
**Symbols:**

```
ffffffff828a716b-ffffffff828a7444: reserve_crashkernel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void reserve_crashkernel();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (ffffffff828aa1a3)
Location: arch/x86/kernel/setup.c:530
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
```
**Symbols:**

```
ffffffff828aa1a3-ffffffff828aa47c: reserve_crashkernel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void reserve_crashkernel();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (ffffffff82ccf66b)
Location: arch/x86/kernel/setup.c:482
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
```
**Symbols:**

```
ffffffff82ccf66b-ffffffff82ccf83d: reserve_crashkernel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void reserve_crashkernel();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (ffffffff82fbb4c0)
Location: arch/x86/kernel/setup.c:465
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
```
**Symbols:**

```
ffffffff82fbb4c0-ffffffff82fbb669: reserve_crashkernel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void reserve_crashkernel();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (ffffffff831c5a82)
Location: arch/x86/kernel/setup.c:465
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
```
**Symbols:**

```
ffffffff831c5a82-ffffffff831c5d14: reserve_crashkernel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void reserve_crashkernel();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (ffffffff832a69f2)
Location: arch/x86/kernel/setup.c:487
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
```
**Symbols:**

```
ffffffff832a69f2-ffffffff832a6c84: reserve_crashkernel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void reserve_crashkernel();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (ffffffff83455c61)
Location: arch/x86/kernel/setup.c:481
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
```
**Symbols:**

```
ffffffff83455c61-ffffffff83455f25: reserve_crashkernel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void reserve_crashkernel();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (ffffffff83e73dd0)
Location: arch/x86/kernel/setup.c:556
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
```
**Symbols:**

```
ffffffff83e73dd0-ffffffff83e740c0: reserve_crashkernel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void reserve_crashkernel();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (ffffffff836958a0)
Location: arch/x86/kernel/setup.c:550
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
```
**Symbols:**

```
ffffffff836958a0-ffffffff83695b90: reserve_crashkernel (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In arch/arm64/mm/init.c (ffff800011437584)
Location: arch/arm64/mm/init.c:69
Inline: True
Inline callers:
  - arch/arm64/mm/init.c:arm64_memblock_init
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
In arch/arm/kernel/setup.c (c1504e58)
Location: arch/arm/kernel/setup.c:988
Inline: True
Inline callers:
  - arch/arm/kernel/setup.c:setup_arch
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void reserve_crashkernel();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/machine_kexec.c (c000000001352cc0)
Location: arch/powerpc/kernel/machine_kexec.c:115
Inline: False
Direct callers:
  - arch/powerpc/kernel/prom.c:early_init_devtree
```
**Symbols:**

```
c000000001352cc0-c000000001352f20: reserve_crashkernel (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void reserve_crashkernel();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (ffffffff828981b3)
Location: arch/x86/kernel/setup.c:530
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
```
**Symbols:**

```
ffffffff828981b3-ffffffff8289848c: reserve_crashkernel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void reserve_crashkernel();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (ffffffff828904dd)
Location: arch/x86/kernel/setup.c:530
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
```
**Symbols:**

```
ffffffff828904dd-ffffffff8289079c: reserve_crashkernel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void reserve_crashkernel();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (ffffffff828ab1a3)
Location: arch/x86/kernel/setup.c:530
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
```
**Symbols:**

```
ffffffff828ab1a3-ffffffff828ab47c: reserve_crashkernel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void reserve_crashkernel();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (ffffffff828ab1b3)
Location: arch/x86/kernel/setup.c:530
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
```
**Symbols:**

```
ffffffff828ab1b3-ffffffff828ab48c: reserve_crashkernel (STB_LOCAL)
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
