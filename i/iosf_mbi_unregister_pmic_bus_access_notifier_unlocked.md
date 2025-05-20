# Function: <code>iosf_mbi_unregister_pmic_bus_access_notifier_unlocked</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int iosf_mbi_unregister_pmic_bus_access_notifier_unlocked(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff81088270)
Location: arch/x86/platform/intel/iosf_mbi.c:221
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier
```
**Symbols:**

```
ffffffff81088270-ffffffff810882ac: iosf_mbi_unregister_pmic_bus_access_notifier_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int iosf_mbi_unregister_pmic_bus_access_notifier_unlocked(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff8108fad0)
Location: arch/x86/platform/intel/iosf_mbi.c:400
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier
```
**Symbols:**

```
ffffffff8108fad0-ffffffff8108fb0c: iosf_mbi_unregister_pmic_bus_access_notifier_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int iosf_mbi_unregister_pmic_bus_access_notifier_unlocked(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (0)
Location: arch/x86/platform/intel/iosf_mbi.c:391
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier
```
**Symbols:**

```
ffffffff81093bec-ffffffff81093bfe: iosf_mbi_unregister_pmic_bus_access_notifier_unlocked.cold (STB_LOCAL)
ffffffff81093760-ffffffff81093791: iosf_mbi_unregister_pmic_bus_access_notifier_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int iosf_mbi_unregister_pmic_bus_access_notifier_unlocked(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff81094570)
Location: arch/x86/platform/intel/iosf_mbi.c:415
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier
```
**Symbols:**

```
ffffffff81094570-ffffffff810945b3: iosf_mbi_unregister_pmic_bus_access_notifier_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int iosf_mbi_unregister_pmic_bus_access_notifier_unlocked(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff81099b74)
Location: arch/x86/platform/intel/iosf_mbi.c:415
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier
```
**Symbols:**

```
ffffffff81099880-ffffffff810998b4: iosf_mbi_unregister_pmic_bus_access_notifier_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int iosf_mbi_unregister_pmic_bus_access_notifier_unlocked(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff81098c64)
Location: arch/x86/platform/intel/iosf_mbi.c:415
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier
```
**Symbols:**

```
ffffffff81098970-ffffffff810989a4: iosf_mbi_unregister_pmic_bus_access_notifier_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int iosf_mbi_unregister_pmic_bus_access_notifier_unlocked(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810994a4)
Location: arch/x86/platform/intel/iosf_mbi.c:415
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier
```
**Symbols:**

```
ffffffff810991b0-ffffffff810991e4: iosf_mbi_unregister_pmic_bus_access_notifier_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int iosf_mbi_unregister_pmic_bus_access_notifier_unlocked(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810a9474)
Location: arch/x86/platform/intel/iosf_mbi.c:415
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier
```
**Symbols:**

```
ffffffff810a9240-ffffffff810a9274: iosf_mbi_unregister_pmic_bus_access_notifier_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int iosf_mbi_unregister_pmic_bus_access_notifier_unlocked(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810becf4)
Location: arch/x86/platform/intel/iosf_mbi.c:415
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier
```
**Symbols:**

```
ffffffff810bea40-ffffffff810bea84: iosf_mbi_unregister_pmic_bus_access_notifier_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int iosf_mbi_unregister_pmic_bus_access_notifier_unlocked(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810da914)
Location: arch/x86/platform/intel/iosf_mbi.c:415
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier
```
**Symbols:**

```
ffffffff810da5d0-ffffffff810da614: iosf_mbi_unregister_pmic_bus_access_notifier_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int iosf_mbi_unregister_pmic_bus_access_notifier_unlocked(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810e5ea4)
Location: arch/x86/platform/intel/iosf_mbi.c:415
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier
```
**Symbols:**

```
ffffffff810e5b70-ffffffff810e5bb4: iosf_mbi_unregister_pmic_bus_access_notifier_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int iosf_mbi_unregister_pmic_bus_access_notifier_unlocked(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810ee294)
Location: arch/x86/platform/intel/iosf_mbi.c:415
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier
```
**Symbols:**

```
ffffffff810edf60-ffffffff810edfa4: iosf_mbi_unregister_pmic_bus_access_notifier_unlocked (STB_GLOBAL)
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
int iosf_mbi_unregister_pmic_bus_access_notifier_unlocked(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff81093530)
Location: arch/x86/platform/intel/iosf_mbi.c:415
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier
```
**Symbols:**

```
ffffffff81093530-ffffffff81093573: iosf_mbi_unregister_pmic_bus_access_notifier_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int iosf_mbi_unregister_pmic_bus_access_notifier_unlocked(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff81081fc0)
Location: arch/x86/platform/intel/iosf_mbi.c:415
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier
```
**Symbols:**

```
ffffffff81081fc0-ffffffff81082003: iosf_mbi_unregister_pmic_bus_access_notifier_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int iosf_mbi_unregister_pmic_bus_access_notifier_unlocked(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810934e0)
Location: arch/x86/platform/intel/iosf_mbi.c:415
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier
```
**Symbols:**

```
ffffffff810934e0-ffffffff81093523: iosf_mbi_unregister_pmic_bus_access_notifier_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int iosf_mbi_unregister_pmic_bus_access_notifier_unlocked(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff81095a30)
Location: arch/x86/platform/intel/iosf_mbi.c:415
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier
```
**Symbols:**

```
ffffffff81095a30-ffffffff81095a73: iosf_mbi_unregister_pmic_bus_access_notifier_unlocked (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
