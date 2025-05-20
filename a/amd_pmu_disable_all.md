# Function: <code>amd_pmu_disable_all</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void amd_pmu_disable_all();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81008ca0)
Location: arch/x86/events/amd/core.c:587
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_virt
  - arch/x86/events/amd/core.c:amd_pmu_enable_virt
```
**Symbols:**

```
ffffffff81008ca0-ffffffff81008d01: amd_pmu_disable_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void amd_pmu_disable_all();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81009000)
Location: arch/x86/events/amd/core.c:608
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_virt
  - arch/x86/events/amd/core.c:amd_pmu_enable_virt
```
**Symbols:**

```
ffffffff81009000-ffffffff81009061: amd_pmu_disable_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void amd_pmu_disable_all();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff8100a0b0)
Location: arch/x86/events/amd/core.c:608
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_virt
  - arch/x86/events/amd/core.c:amd_pmu_enable_virt
```
**Symbols:**

```
ffffffff8100a0b0-ffffffff8100a111: amd_pmu_disable_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void amd_pmu_disable_all();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81008f30)
Location: arch/x86/events/amd/core.c:608
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_virt
  - arch/x86/events/amd/core.c:amd_pmu_enable_virt
```
**Symbols:**

```
ffffffff81008f30-ffffffff81008f91: amd_pmu_disable_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void amd_pmu_disable_all();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff810098d0)
Location: arch/x86/events/amd/core.c:608
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_virt
  - arch/x86/events/amd/core.c:amd_pmu_enable_virt
```
**Symbols:**

```
ffffffff810098d0-ffffffff81009931: amd_pmu_disable_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void amd_pmu_disable_all();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff8100a8b0)
Location: arch/x86/events/amd/core.c:608
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_virt
  - arch/x86/events/amd/core.c:amd_pmu_enable_virt
```
**Symbols:**

```
ffffffff8100a8b0-ffffffff8100a911: amd_pmu_disable_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void amd_pmu_disable_all();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff8100ab53)
Location: arch/x86/events/amd/core.c:824
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_virt
  - arch/x86/events/amd/core.c:amd_pmu_enable_virt
  - arch/x86/events/amd/core.c:amd_pmu_handle_irq
```
**Symbols:**

```
ffffffff8100a7f0-ffffffff8100a80e: amd_pmu_disable_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void amd_pmu_disable_all();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff8100ca63)
Location: arch/x86/events/amd/core.c:780
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_virt
  - arch/x86/events/amd/core.c:amd_pmu_enable_virt
```
**Symbols:**

```
ffffffff8100c4c0-ffffffff8100c4de: amd_pmu_disable_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void amd_pmu_disable_all();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff8100c303)
Location: arch/x86/events/amd/core.c:780
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_virt
  - arch/x86/events/amd/core.c:amd_pmu_enable_virt
```
**Symbols:**

```
ffffffff8100bc80-ffffffff8100bc9e: amd_pmu_disable_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void amd_pmu_disable_all();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81011a03)
Location: arch/x86/events/amd/core.c:782
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_virt
  - arch/x86/events/amd/core.c:amd_pmu_enable_virt
```
**Symbols:**

```
ffffffff81011460-ffffffff8101147e: amd_pmu_disable_all (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void amd_pmu_disable_all();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81009000)
Location: arch/x86/events/amd/core.c:608
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_virt
  - arch/x86/events/amd/core.c:amd_pmu_enable_virt
```
**Symbols:**

```
ffffffff81009000-ffffffff81009061: amd_pmu_disable_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void amd_pmu_disable_all();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81007790)
Location: arch/x86/events/amd/core.c:608
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_virt
  - arch/x86/events/amd/core.c:amd_pmu_enable_virt
```
**Symbols:**

```
ffffffff81007790-ffffffff810077f1: amd_pmu_disable_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void amd_pmu_disable_all();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81008fc0)
Location: arch/x86/events/amd/core.c:608
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_virt
  - arch/x86/events/amd/core.c:amd_pmu_enable_virt
```
**Symbols:**

```
ffffffff81008fc0-ffffffff81009021: amd_pmu_disable_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void amd_pmu_disable_all();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81009120)
Location: arch/x86/events/amd/core.c:608
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_virt
  - arch/x86/events/amd/core.c:amd_pmu_enable_virt
```
**Symbols:**

```
ffffffff81009120-ffffffff81009181: amd_pmu_disable_all (STB_LOCAL)
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
