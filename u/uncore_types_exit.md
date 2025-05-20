# Function: <code>uncore_types_exit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void uncore_types_exit(struct intel_uncore_type **types);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81f5ff49)
Location: arch/x86/events/intel/uncore.c:778
Inline: False
```
**Symbols:**

```
ffffffff81f5ff49-ffffffff81f5ff6f: uncore_types_exit (STB_LOCAL)
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
In arch/x86/events/intel/uncore.c (ffffffff820e6ef8)
Location: arch/x86/events/intel/uncore.c:813
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
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
In arch/x86/events/intel/uncore.c (ffffffff821ccdeb)
Location: arch/x86/events/intel/uncore.c:799
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
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
In arch/x86/events/intel/uncore.c (ffffffff822c1ef3)
Location: arch/x86/events/intel/uncore.c:799
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
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
In arch/x86/events/intel/uncore.c (ffffffff828d5073)
Location: arch/x86/events/intel/uncore.c:799
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
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
In arch/x86/events/intel/uncore.c (ffffffff829068d3)
Location: arch/x86/events/intel/uncore.c:859
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
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
In arch/x86/events/intel/uncore.c (ffffffff82ade643)
Location: arch/x86/events/intel/uncore.c:860
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
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
In arch/x86/events/intel/uncore.c (ffffffff82b03743)
Location: arch/x86/events/intel/uncore.c:870
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
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
In arch/x86/events/intel/uncore.c (ffffffff82b12633)
Location: arch/x86/events/intel/uncore.c:902
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void uncore_types_exit(struct intel_uncore_type **types);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81019f06)
Location: arch/x86/events/intel/uncore.c:902
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:uncore_pci_init
```
**Symbols:**

```
ffffffff81019f06-ffffffff81019fc8: uncore_types_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void uncore_types_exit(struct intel_uncore_type **types);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81bd2359)
Location: arch/x86/events/intel/uncore.c:912
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:uncore_pci_init
```
**Symbols:**

```
ffffffff81bd2359-ffffffff81bd2438: uncore_types_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void uncore_types_exit(struct intel_uncore_type **types);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81bc464d)
Location: arch/x86/events/intel/uncore.c:952
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:uncore_pci_init
```
**Symbols:**

```
ffffffff81bc464d-ffffffff81bc4742: uncore_types_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void uncore_types_exit(struct intel_uncore_type **types);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81c966ae)
Location: arch/x86/events/intel/uncore.c:959
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:uncore_pci_init
```
**Symbols:**

```
ffffffff81c966ae-ffffffff81c9678e: uncore_types_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void uncore_types_exit(struct intel_uncore_type **types);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81e45b4d)
Location: arch/x86/events/intel/uncore.c:959
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:uncore_pci_init
```
**Symbols:**

```
ffffffff81e45b4d-ffffffff81e45c33: uncore_types_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void uncore_types_exit(struct intel_uncore_type **types);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/uncore.c (0)
Location: arch/x86/events/intel/uncore.c:959
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:uncore_pci_init
```
**Symbols:**

```
ffffffff810231f0-ffffffff81023318: uncore_types_exit (STB_LOCAL)
ffffffff82051317-ffffffff8205132b: uncore_types_exit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void uncore_types_exit(struct intel_uncore_type **types);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/uncore.c (0)
Location: arch/x86/events/intel/uncore.c:980
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:uncore_pci_init
```
**Symbols:**

```
ffffffff81022ef0-ffffffff81023016: uncore_types_exit (STB_LOCAL)
ffffffff820cf749-ffffffff820cf75d: uncore_types_exit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void uncore_types_exit(struct intel_uncore_type **types);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/uncore.c (0)
Location: arch/x86/events/intel/uncore.c:980
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:uncore_pci_init
```
**Symbols:**

```
ffffffff81029020-ffffffff81029146: uncore_types_exit (STB_LOCAL)
ffffffff821aa0b7-ffffffff821aa0cb: uncore_types_exit.cold (STB_LOCAL)
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
In arch/x86/events/intel/uncore.c (ffffffff82af2853)
Location: arch/x86/events/intel/uncore.c:902
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
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
In arch/x86/events/intel/uncore.c (ffffffff82ac2c7b)
Location: arch/x86/events/intel/uncore.c:902
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
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
In arch/x86/events/intel/uncore.c (ffffffff82b0d91b)
Location: arch/x86/events/intel/uncore.c:902
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
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
In arch/x86/events/intel/uncore.c (ffffffff82b0246b)
Location: arch/x86/events/intel/uncore.c:902
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_exit
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/events/intel/uncore.c:intel_uncore_init
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
