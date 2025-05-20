# Function: <code>iosf_mbi_assert_punit_acquired</code>

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
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void iosf_mbi_assert_punit_acquired();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff81088275)
Location: arch/x86/platform/intel/iosf_mbi.c:251
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier_unlocked
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier_unlocked
```
**Symbols:**

```
ffffffff81088240-ffffffff8108824d: iosf_mbi_assert_punit_acquired.part.1 (STB_LOCAL)
ffffffff81088250-ffffffff81088270: iosf_mbi_assert_punit_acquired (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void iosf_mbi_assert_punit_acquired();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff8108fad5)
Location: arch/x86/platform/intel/iosf_mbi.c:423
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier_unlocked
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier_unlocked
```
**Symbols:**

```
ffffffff8108faa0-ffffffff8108faad: iosf_mbi_assert_punit_acquired.part.1 (STB_LOCAL)
ffffffff8108fab0-ffffffff8108fad0: iosf_mbi_assert_punit_acquired (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void iosf_mbi_assert_punit_acquired();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff81093765)
Location: arch/x86/platform/intel/iosf_mbi.c:414
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier_unlocked
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier_unlocked
```
**Symbols:**

```
ffffffff81093bc9-ffffffff81093be2: iosf_mbi_assert_punit_acquired.part.0 (STB_LOCAL)
ffffffff81093be2-ffffffff81093bec: iosf_mbi_assert_punit_acquired.cold (STB_LOCAL)
ffffffff81093740-ffffffff8109375e: iosf_mbi_assert_punit_acquired (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void iosf_mbi_assert_punit_acquired();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff81094575)
Location: arch/x86/platform/intel/iosf_mbi.c:438
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier_unlocked
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier_unlocked
```
**Symbols:**

```
ffffffff81094540-ffffffff8109454d: iosf_mbi_assert_punit_acquired.part.0 (STB_LOCAL)
ffffffff81094550-ffffffff8109456b: iosf_mbi_assert_punit_acquired (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void iosf_mbi_assert_punit_acquired();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff81099b74)
Location: arch/x86/platform/intel/iosf_mbi.c:438
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier
```
**Symbols:**

```
ffffffff81099ac0-ffffffff81099ad9: iosf_mbi_assert_punit_acquired (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void iosf_mbi_assert_punit_acquired();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff81098c64)
Location: arch/x86/platform/intel/iosf_mbi.c:438
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier
```
**Symbols:**

```
ffffffff81098bb0-ffffffff81098bc9: iosf_mbi_assert_punit_acquired (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void iosf_mbi_assert_punit_acquired();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810994a4)
Location: arch/x86/platform/intel/iosf_mbi.c:438
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier
```
**Symbols:**

```
ffffffff810993f0-ffffffff81099409: iosf_mbi_assert_punit_acquired (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void iosf_mbi_assert_punit_acquired();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810a9474)
Location: arch/x86/platform/intel/iosf_mbi.c:438
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier
```
**Symbols:**

```
ffffffff810a8d30-ffffffff810a8d49: iosf_mbi_assert_punit_acquired (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void iosf_mbi_assert_punit_acquired();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810becf4)
Location: arch/x86/platform/intel/iosf_mbi.c:438
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier
```
**Symbols:**

```
ffffffff810be460-ffffffff810be485: iosf_mbi_assert_punit_acquired (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void iosf_mbi_assert_punit_acquired();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810da914)
Location: arch/x86/platform/intel/iosf_mbi.c:438
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier
```
**Symbols:**

```
ffffffff810d9f10-ffffffff810d9f35: iosf_mbi_assert_punit_acquired (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void iosf_mbi_assert_punit_acquired();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810e5ea4)
Location: arch/x86/platform/intel/iosf_mbi.c:438
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier
```
**Symbols:**

```
ffffffff810e54a0-ffffffff810e54c5: iosf_mbi_assert_punit_acquired (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void iosf_mbi_assert_punit_acquired();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810ee294)
Location: arch/x86/platform/intel/iosf_mbi.c:438
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier
```
**Symbols:**

```
ffffffff810ed890-ffffffff810ed8b5: iosf_mbi_assert_punit_acquired (STB_GLOBAL)
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

```c
void iosf_mbi_assert_punit_acquired();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff81093535)
Location: arch/x86/platform/intel/iosf_mbi.c:438
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier_unlocked
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier_unlocked
```
**Symbols:**

```
ffffffff81093500-ffffffff8109350d: iosf_mbi_assert_punit_acquired.part.0 (STB_LOCAL)
ffffffff81093510-ffffffff8109352b: iosf_mbi_assert_punit_acquired (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void iosf_mbi_assert_punit_acquired();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff81081fc5)
Location: arch/x86/platform/intel/iosf_mbi.c:438
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier_unlocked
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier_unlocked
```
**Symbols:**

```
ffffffff81081f90-ffffffff81081f9d: iosf_mbi_assert_punit_acquired.part.0 (STB_LOCAL)
ffffffff81081fa0-ffffffff81081fbb: iosf_mbi_assert_punit_acquired (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void iosf_mbi_assert_punit_acquired();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810934e5)
Location: arch/x86/platform/intel/iosf_mbi.c:438
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier_unlocked
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier_unlocked
```
**Symbols:**

```
ffffffff810934b0-ffffffff810934bd: iosf_mbi_assert_punit_acquired.part.0 (STB_LOCAL)
ffffffff810934c0-ffffffff810934db: iosf_mbi_assert_punit_acquired (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void iosf_mbi_assert_punit_acquired();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff81095a35)
Location: arch/x86/platform/intel/iosf_mbi.c:438
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier_unlocked
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier_unlocked
```
**Symbols:**

```
ffffffff81095a00-ffffffff81095a0d: iosf_mbi_assert_punit_acquired.part.0 (STB_LOCAL)
ffffffff81095a10-ffffffff81095a2b: iosf_mbi_assert_punit_acquired (STB_GLOBAL)
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
