# Function: <code>imc_uncore_find_dev</code>

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
In arch/x86/events/intel/uncore_snb.c (ffffffff81019398)
Location: arch/x86/events/intel/uncore_snb.c:568
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:bdw_uncore_pci_init
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
In arch/x86/events/intel/uncore_snb.c (ffffffff81018798)
Location: arch/x86/events/intel/uncore_snb.c:676
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:skl_uncore_pci_init
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
In arch/x86/events/intel/uncore_snb.c (ffffffff81018968)
Location: arch/x86/events/intel/uncore_snb.c:690
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:skl_uncore_pci_init
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
In arch/x86/events/intel/uncore_snb.c (ffffffff81016e46)
Location: arch/x86/events/intel/uncore_snb.c:690
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_pci_init
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
In arch/x86/events/intel/uncore_snb.c (ffffffff810176c6)
Location: arch/x86/events/intel/uncore_snb.c:691
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_pci_init
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
In arch/x86/events/intel/uncore_snb.c (ffffffff81018065)
Location: arch/x86/events/intel/uncore_snb.c:628
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_pci_init
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
In arch/x86/events/intel/uncore_snb.c (ffffffff81018835)
Location: arch/x86/events/intel/uncore_snb.c:747
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_pci_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct pci_driver *imc_uncore_find_dev();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snb.c (ffffffff81019e00)
Location: arch/x86/events/intel/uncore_snb.c:864
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snb.c:skl_uncore_pci_init
  - arch/x86/events/intel/uncore_snb.c:bdw_uncore_pci_init
  - arch/x86/events/intel/uncore_snb.c:hsw_uncore_pci_init
  - arch/x86/events/intel/uncore_snb.c:ivb_uncore_pci_init
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_pci_init
```
**Symbols:**

```
ffffffff81019e00-ffffffff81019e38: imc_uncore_find_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct pci_driver *imc_uncore_find_dev();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snb.c (ffffffff8101a780)
Location: arch/x86/events/intel/uncore_snb.c:870
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snb.c:skl_uncore_pci_init
  - arch/x86/events/intel/uncore_snb.c:bdw_uncore_pci_init
  - arch/x86/events/intel/uncore_snb.c:hsw_uncore_pci_init
  - arch/x86/events/intel/uncore_snb.c:ivb_uncore_pci_init
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_pci_init
```
**Symbols:**

```
ffffffff8101a780-ffffffff8101a7b8: imc_uncore_find_dev (STB_LOCAL)
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
In arch/x86/events/intel/uncore_snb.c (ffffffff8101c215)
Location: arch/x86/events/intel/uncore_snb.c:875
Inline: True
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
In arch/x86/events/intel/uncore_snb.c (ffffffff8101c7a5)
Location: arch/x86/events/intel/uncore_snb.c:1047
Inline: True
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
In arch/x86/events/intel/uncore_snb.c (ffffffff8101dc55)
Location: arch/x86/events/intel/uncore_snb.c:1170
Inline: True
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
In arch/x86/events/intel/uncore_snb.c (ffffffff81020d55)
Location: arch/x86/events/intel/uncore_snb.c:1170
Inline: True
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
In arch/x86/events/intel/uncore_snb.c (ffffffff81024295)
Location: arch/x86/events/intel/uncore_snb.c:1077
Inline: True
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
In arch/x86/events/intel/uncore_snb.c (ffffffff810293b5)
Location: arch/x86/events/intel/uncore_snb.c:1225
Inline: True
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
In arch/x86/events/intel/uncore_snb.c (ffffffff810293e5)
Location: arch/x86/events/intel/uncore_snb.c:1225
Inline: True
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
In arch/x86/events/intel/uncore_snb.c (ffffffff8102f545)
Location: arch/x86/events/intel/uncore_snb.c:1225
Inline: True
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
struct pci_driver *imc_uncore_find_dev();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snb.c (ffffffff8101a780)
Location: arch/x86/events/intel/uncore_snb.c:870
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snb.c:skl_uncore_pci_init
  - arch/x86/events/intel/uncore_snb.c:bdw_uncore_pci_init
  - arch/x86/events/intel/uncore_snb.c:hsw_uncore_pci_init
  - arch/x86/events/intel/uncore_snb.c:ivb_uncore_pci_init
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_pci_init
```
**Symbols:**

```
ffffffff8101a780-ffffffff8101a7b8: imc_uncore_find_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct pci_driver *imc_uncore_find_dev();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snb.c (ffffffff81019ee0)
Location: arch/x86/events/intel/uncore_snb.c:870
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snb.c:skl_uncore_pci_init
  - arch/x86/events/intel/uncore_snb.c:bdw_uncore_pci_init
  - arch/x86/events/intel/uncore_snb.c:hsw_uncore_pci_init
  - arch/x86/events/intel/uncore_snb.c:ivb_uncore_pci_init
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_pci_init
```
**Symbols:**

```
ffffffff81019ee0-ffffffff81019f18: imc_uncore_find_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct pci_driver *imc_uncore_find_dev();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snb.c (ffffffff8101a740)
Location: arch/x86/events/intel/uncore_snb.c:870
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snb.c:skl_uncore_pci_init
  - arch/x86/events/intel/uncore_snb.c:bdw_uncore_pci_init
  - arch/x86/events/intel/uncore_snb.c:hsw_uncore_pci_init
  - arch/x86/events/intel/uncore_snb.c:ivb_uncore_pci_init
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_pci_init
```
**Symbols:**

```
ffffffff8101a740-ffffffff8101a778: imc_uncore_find_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct pci_driver *imc_uncore_find_dev();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snb.c (ffffffff8101a980)
Location: arch/x86/events/intel/uncore_snb.c:870
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snb.c:skl_uncore_pci_init
  - arch/x86/events/intel/uncore_snb.c:bdw_uncore_pci_init
  - arch/x86/events/intel/uncore_snb.c:hsw_uncore_pci_init
  - arch/x86/events/intel/uncore_snb.c:ivb_uncore_pci_init
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_pci_init
```
**Symbols:**

```
ffffffff8101a980-ffffffff8101a9b8: imc_uncore_find_dev (STB_LOCAL)
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
