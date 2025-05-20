# Function: <code>pci_mmconfig_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct pci_mmcfg_region *pci_mmconfig_add(int segment, int start, int end, u64 addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff81fb89d1)
Location: arch/x86/pci/mmconfig-shared.c:96
Inline: False
Direct callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_intel_945
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_e7520
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_amd_fam10h
```
**Symbols:**

```
ffffffff81fb89d1-ffffffff81fb8a41: pci_mmconfig_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct pci_mmcfg_region *pci_mmconfig_add(int segment, int start, int end, u64 addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff81fe65ad)
Location: arch/x86/pci/mmconfig-shared.c:96
Inline: False
Direct callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_amd_fam10h
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_intel_945
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_e7520
```
**Symbols:**

```
ffffffff81fe65ad-ffffffff81fe661d: pci_mmconfig_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct pci_mmcfg_region *pci_mmconfig_add(int segment, int start, int end, u64 addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff82024df1)
Location: arch/x86/pci/mmconfig-shared.c:96
Inline: False
Direct callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_amd_fam10h
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_intel_945
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_e7520
```
**Symbols:**

```
ffffffff82024df1-ffffffff82024e61: pci_mmconfig_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct pci_mmcfg_region *pci_mmconfig_add(int segment, int start, int end, u64 addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff821082a6)
Location: arch/x86/pci/mmconfig-shared.c:96
Inline: False
Direct callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_amd_fam10h
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_intel_945
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_e7520
```
**Symbols:**

```
ffffffff821082a6-ffffffff8210831b: pci_mmconfig_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct pci_mmcfg_region *pci_mmconfig_add(int segment, int start, int end, u64 addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff82711bec)
Location: arch/x86/pci/mmconfig-shared.c:97
Inline: False
Direct callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_amd_fam10h
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_intel_945
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_e7520
```
**Symbols:**

```
ffffffff82711bec-ffffffff82711c61: pci_mmconfig_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct pci_mmcfg_region *pci_mmconfig_add(int segment, int start, int end, u64 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff8273c032)
Location: arch/x86/pci/mmconfig-shared.c:97
Inline: False
Direct callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_pci_arch_init
  - arch/x86/pci/mmconfig-shared.c:pci_parse_mcfg
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_nvidia_mcp55
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_amd_fam10h
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_intel_945
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_e7520
```
**Symbols:**

```
ffffffff8273c032-ffffffff8273c0a7: pci_mmconfig_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct pci_mmcfg_region *pci_mmconfig_add(int segment, int start, int end, u64 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff828f6044)
Location: arch/x86/pci/mmconfig-shared.c:97
Inline: False
Direct callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_pci_arch_init
  - arch/x86/pci/mmconfig-shared.c:pci_parse_mcfg
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_nvidia_mcp55
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_amd_fam10h
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_intel_945
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_e7520
```
**Symbols:**

```
ffffffff828f6044-ffffffff828f60b9: pci_mmconfig_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct pci_mmcfg_region *pci_mmconfig_add(int segment, int start, int end, u64 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff82911a92)
Location: arch/x86/pci/mmconfig-shared.c:97
Inline: False
Direct callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_pci_arch_init
  - arch/x86/pci/mmconfig-shared.c:pci_parse_mcfg
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_nvidia_mcp55
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_amd_fam10h
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_intel_945
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_e7520
```
**Symbols:**

```
ffffffff82911a92-ffffffff82911b08: pci_mmconfig_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct pci_mmcfg_region *pci_mmconfig_add(int segment, int start, int end, u64 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff8291b82b)
Location: arch/x86/pci/mmconfig-shared.c:98
Inline: False
Direct callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_pci_arch_init
  - arch/x86/pci/mmconfig-shared.c:pci_parse_mcfg
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_nvidia_mcp55
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_amd_fam10h
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_intel_945
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_e7520
```
**Symbols:**

```
ffffffff8291b82b-ffffffff8291b8a1: pci_mmconfig_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct pci_mmcfg_region *pci_mmconfig_add(int segment, int start, int end, u64 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff82d315b0)
Location: arch/x86/pci/mmconfig-shared.c:98
Inline: False
Direct callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_pci_arch_init
  - arch/x86/pci/mmconfig-shared.c:pci_parse_mcfg
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_nvidia_mcp55
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_amd_fam10h
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_intel_945
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_e7520
```
**Symbols:**

```
ffffffff82d315b0-ffffffff82d31626: pci_mmconfig_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct pci_mmcfg_region *pci_mmconfig_add(int segment, int start, int end, u64 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff8302053a)
Location: arch/x86/pci/mmconfig-shared.c:98
Inline: False
Direct callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_pci_arch_init
  - arch/x86/pci/mmconfig-shared.c:pci_parse_mcfg
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_nvidia_mcp55
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_amd_fam10h
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_intel_945
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_e7520
```
**Symbols:**

```
ffffffff8302053a-ffffffff830205b0: pci_mmconfig_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct pci_mmcfg_region *pci_mmconfig_add(int segment, int start, int end, u64 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff8322b706)
Location: arch/x86/pci/mmconfig-shared.c:98
Inline: False
Direct callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_pci_arch_init
  - arch/x86/pci/mmconfig-shared.c:pci_parse_mcfg
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_nvidia_mcp55
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_amd_fam10h
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_intel_945
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_e7520
```
**Symbols:**

```
ffffffff8322b706-ffffffff8322b77c: pci_mmconfig_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct pci_mmcfg_region *pci_mmconfig_add(int segment, int start, int end, u64 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff83315f15)
Location: arch/x86/pci/mmconfig-shared.c:98
Inline: False
Direct callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_pci_arch_init
  - arch/x86/pci/mmconfig-shared.c:pci_parse_mcfg
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_nvidia_mcp55
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_amd_fam10h
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_intel_945
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_e7520
```
**Symbols:**

```
ffffffff83315f15-ffffffff83315f8b: pci_mmconfig_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct pci_mmcfg_region *pci_mmconfig_add(int segment, int start, int end, u64 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff834d0806)
Location: arch/x86/pci/mmconfig-shared.c:98
Inline: False
Direct callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_pci_arch_init
  - arch/x86/pci/mmconfig-shared.c:pci_parse_mcfg
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_nvidia_mcp55
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_amd_fam10h
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_intel_945
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_e7520
```
**Symbols:**

```
ffffffff834d0806-ffffffff834d088d: pci_mmconfig_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct pci_mmcfg_region *pci_mmconfig_add(int segment, int start, int end, u64 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff83f14850)
Location: arch/x86/pci/mmconfig-shared.c:99
Inline: False
Direct callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_pci_arch_init
  - arch/x86/pci/mmconfig-shared.c:pci_parse_mcfg
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_nvidia_mcp55
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_amd_fam10h
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_intel_945
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_e7520
```
**Symbols:**

```
ffffffff83f14850-ffffffff83f148d7: pci_mmconfig_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct pci_mmcfg_region *pci_mmconfig_add(int segment, int start, int end, u64 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff8373afd0)
Location: arch/x86/pci/mmconfig-shared.c:99
Inline: False
Direct callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_pci_arch_init
  - arch/x86/pci/mmconfig-shared.c:pci_parse_mcfg
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_nvidia_mcp55
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_amd_fam10h
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_intel_945
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_e7520
```
**Symbols:**

```
ffffffff8373afd0-ffffffff8373b057: pci_mmconfig_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct pci_mmcfg_region *pci_mmconfig_add(int segment, int start, int end, u64 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff8396f940)
Location: arch/x86/pci/mmconfig-shared.c:99
Inline: False
Direct callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_pci_arch_init
  - arch/x86/pci/mmconfig-shared.c:pci_parse_mcfg
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_nvidia_mcp55
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_amd_fam10h
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_intel_945
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_e7520
```
**Symbols:**

```
ffffffff8396f940-ffffffff8396f9c7: pci_mmconfig_add (STB_GLOBAL)
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
struct pci_mmcfg_region *pci_mmconfig_add(int segment, int start, int end, u64 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff8290052f)
Location: arch/x86/pci/mmconfig-shared.c:98
Inline: False
Direct callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_pci_arch_init
  - arch/x86/pci/mmconfig-shared.c:pci_parse_mcfg
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_nvidia_mcp55
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_amd_fam10h
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_intel_945
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_e7520
```
**Symbols:**

```
ffffffff8290052f-ffffffff829005a5: pci_mmconfig_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct pci_mmcfg_region *pci_mmconfig_add(int segment, int start, int end, u64 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff828f8b30)
Location: arch/x86/pci/mmconfig-shared.c:98
Inline: False
Direct callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_pci_arch_init
  - arch/x86/pci/mmconfig-shared.c:pci_parse_mcfg
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_nvidia_mcp55
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_amd_fam10h
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_intel_945
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_e7520
```
**Symbols:**

```
ffffffff828f8b30-ffffffff828f8ba6: pci_mmconfig_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct pci_mmcfg_region *pci_mmconfig_add(int segment, int start, int end, u64 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff82915b36)
Location: arch/x86/pci/mmconfig-shared.c:98
Inline: False
Direct callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_pci_arch_init
  - arch/x86/pci/mmconfig-shared.c:pci_parse_mcfg
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_nvidia_mcp55
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_amd_fam10h
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_intel_945
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_e7520
```
**Symbols:**

```
ffffffff82915b36-ffffffff82915bac: pci_mmconfig_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct pci_mmcfg_region *pci_mmconfig_add(int segment, int start, int end, u64 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff8291c88d)
Location: arch/x86/pci/mmconfig-shared.c:98
Inline: False
Direct callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_pci_arch_init
  - arch/x86/pci/mmconfig-shared.c:pci_parse_mcfg
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_nvidia_mcp55
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_amd_fam10h
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_intel_945
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_e7520
```
**Symbols:**

```
ffffffff8291c88d-ffffffff8291c903: pci_mmconfig_add (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
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
