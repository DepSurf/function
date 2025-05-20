# Function: <code>uncore_pci_init</code>

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
In arch/x86/events/intel/uncore.c (ffffffff81f6014a)
Location: arch/x86/events/intel/uncore.c:964
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
In arch/x86/events/intel/uncore.c (ffffffff81f87e14)
Location: arch/x86/events/intel/uncore.c:1010
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
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
In arch/x86/events/intel/uncore.c (ffffffff81fc328e)
Location: arch/x86/events/intel/uncore.c:996
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
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
In arch/x86/events/intel/uncore.c (ffffffff820a351f)
Location: arch/x86/events/intel/uncore.c:996
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
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
In arch/x86/events/intel/uncore.c (ffffffff826a9839)
Location: arch/x86/events/intel/uncore.c:1004
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
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
In arch/x86/events/intel/uncore.c (ffffffff826d29df)
Location: arch/x86/events/intel/uncore.c:1065
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
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
In arch/x86/events/intel/uncore.c (ffffffff82888cfb)
Location: arch/x86/events/intel/uncore.c:1066
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
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
In arch/x86/events/intel/uncore.c (ffffffff8289fee8)
Location: arch/x86/events/intel/uncore.c:1078
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
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
In arch/x86/events/intel/uncore.c (ffffffff828a2fc4)
Location: arch/x86/events/intel/uncore.c:1110
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int uncore_pci_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff82cc9011)
Location: arch/x86/events/intel/uncore.c:1110
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
```
**Symbols:**

```
ffffffff82cc9011-ffffffff82cc90c2: uncore_pci_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int uncore_pci_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff82fb4e4f)
Location: arch/x86/events/intel/uncore.c:1265
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
```
**Symbols:**

```
ffffffff82fb4e4f-ffffffff82fb4f13: uncore_pci_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int uncore_pci_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff831bf3c9)
Location: arch/x86/events/intel/uncore.c:1370
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
```
**Symbols:**

```
ffffffff831bf3c9-ffffffff831bf65f: uncore_pci_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int uncore_pci_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8329f839)
Location: arch/x86/events/intel/uncore.c:1377
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
```
**Symbols:**

```
ffffffff8329f839-ffffffff8329facf: uncore_pci_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int uncore_pci_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8344e642)
Location: arch/x86/events/intel/uncore.c:1377
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
```
**Symbols:**

```
ffffffff8344e642-ffffffff8344e8e8: uncore_pci_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int uncore_pci_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff83e69c30)
Location: arch/x86/events/intel/uncore.c:1377
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
```
**Symbols:**

```
ffffffff83e69c30-ffffffff83e69fe7: uncore_pci_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int uncore_pci_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8368a5c0)
Location: arch/x86/events/intel/uncore.c:1398
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
```
**Symbols:**

```
ffffffff8368a5c0-ffffffff8368a97f: uncore_pci_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int uncore_pci_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff838ba180)
Location: arch/x86/events/intel/uncore.c:1398
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
```
**Symbols:**

```
ffffffff838ba180-ffffffff838ba53c: uncore_pci_init (STB_LOCAL)
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
In arch/x86/events/intel/uncore.c (ffffffff82890fc4)
Location: arch/x86/events/intel/uncore.c:1110
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
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
In arch/x86/events/intel/uncore.c (ffffffff8288eea9)
Location: arch/x86/events/intel/uncore.c:1110
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
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
In arch/x86/events/intel/uncore.c (ffffffff828a3fc4)
Location: arch/x86/events/intel/uncore.c:1110
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
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
In arch/x86/events/intel/uncore.c (ffffffff828a3fd8)
Location: arch/x86/events/intel/uncore.c:1110
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
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
