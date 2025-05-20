# Function: <code>detect_ht_early</code>

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
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int detect_ht_early(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:664
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
**Symbols:**

```
ffffffff81043447-ffffffff8104345f: detect_ht_early.cold.19 (STB_LOCAL)
ffffffff81042170-ffffffff81042201: detect_ht_early (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int detect_ht_early(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:664
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
**Symbols:**

```
ffffffff81044ac7-ffffffff81044adf: detect_ht_early.cold.20 (STB_LOCAL)
ffffffff81043790-ffffffff81043821: detect_ht_early (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int detect_ht_early(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81045d5a)
Location: arch/x86/kernel/cpu/common.c:728
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
**Symbols:**

```
ffffffff81047063-ffffffff8104707b: detect_ht_early.cold (STB_LOCAL)
ffffffff81045cf0-ffffffff81045d8a: detect_ht_early (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int detect_ht_early(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff810464ba)
Location: arch/x86/kernel/cpu/common.c:728
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
**Symbols:**

```
ffffffff810477f9-ffffffff81047811: detect_ht_early.cold (STB_LOCAL)
ffffffff81046450-ffffffff810464ea: detect_ht_early (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int detect_ht_early(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:733
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
**Symbols:**

```
ffffffff8104b576-ffffffff8104b58e: detect_ht_early.cold (STB_LOCAL)
ffffffff8104a410-ffffffff8104a4a6: detect_ht_early (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int detect_ht_early(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:751
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
**Symbols:**

```
ffffffff81bd4f44-ffffffff81bd4f5c: detect_ht_early.cold (STB_LOCAL)
ffffffff810498b0-ffffffff81049946: detect_ht_early (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int detect_ht_early(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:749
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
**Symbols:**

```
ffffffff81bc72db-ffffffff81bc72f3: detect_ht_early.cold (STB_LOCAL)
ffffffff8104b030-ffffffff8104b0c6: detect_ht_early (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int detect_ht_early(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:752
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
**Symbols:**

```
ffffffff81c9a9f1-ffffffff81c9aa1f: detect_ht_early.cold (STB_LOCAL)
ffffffff81052100-ffffffff81052183: detect_ht_early (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int detect_ht_early(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:860
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
**Symbols:**

```
ffffffff81e49e79-ffffffff81e49e8d: detect_ht_early.cold (STB_LOCAL)
ffffffff8105db20-ffffffff8105dbdb: detect_ht_early (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int detect_ht_early(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:881
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
**Symbols:**

```
ffffffff820528dd-ffffffff820528f1: detect_ht_early.cold (STB_LOCAL)
ffffffff8106c010-ffffffff8106c0f8: detect_ht_early (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int detect_ht_early(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:870
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
**Symbols:**

```
ffffffff820d0d98-ffffffff820d0dac: detect_ht_early.cold (STB_LOCAL)
ffffffff8106d9b0-ffffffff8106da98: detect_ht_early (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int detect_ht_early(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:867
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
**Symbols:**

```
ffffffff821ab8bc-ffffffff821ab8d0: detect_ht_early.cold (STB_LOCAL)
ffffffff81074c20-ffffffff81074d08: detect_ht_early (STB_GLOBAL)
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
int detect_ht_early(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8104663a)
Location: arch/x86/kernel/cpu/common.c:728
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
**Symbols:**

```
ffffffff81047969-ffffffff81047981: detect_ht_early.cold (STB_LOCAL)
ffffffff810465d0-ffffffff8104666a: detect_ht_early (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int detect_ht_early(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff810358ba)
Location: arch/x86/kernel/cpu/common.c:728
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
**Symbols:**

```
ffffffff81036c69-ffffffff81036c81: detect_ht_early.cold (STB_LOCAL)
ffffffff81035870-ffffffff810358e7: detect_ht_early (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int detect_ht_early(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8104647a)
Location: arch/x86/kernel/cpu/common.c:728
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
**Symbols:**

```
ffffffff810477a9-ffffffff810477c1: detect_ht_early.cold (STB_LOCAL)
ffffffff81046410-ffffffff810464aa: detect_ht_early (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int detect_ht_early(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8104787a)
Location: arch/x86/kernel/cpu/common.c:728
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/common.c:detect_ht
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
**Symbols:**

```
ffffffff81048bb9-ffffffff81048bd1: detect_ht_early.cold (STB_LOCAL)
ffffffff81047810-ffffffff810478aa: detect_ht_early (STB_GLOBAL)
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
