# Function: <code>smca_configure</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff8104a8aa)
Location: arch/x86/kernel/cpu/mcheck/mce_amd.c:167
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init
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
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff8104e2e9)
Location: arch/x86/kernel/cpu/mcheck/mce_amd.c:169
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init
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
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff81050f78)
Location: arch/x86/kernel/cpu/mcheck/mce_amd.c:192
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init
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
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8104e3e8)
Location: arch/x86/kernel/cpu/mce/amd.c:193
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
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
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81051420)
Location: arch/x86/kernel/cpu/mce/amd.c:229
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
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
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81051d80)
Location: arch/x86/kernel/cpu/mce/amd.c:231
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void smca_configure(unsigned int bank, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: arch/x86/kernel/cpu/mce/amd.c:236
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
```
**Symbols:**

```
ffffffff81055c10-ffffffff81055dbd: smca_configure (STB_LOCAL)
ffffffff81056f4b-ffffffff81056f5f: smca_configure.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void smca_configure(unsigned int bank, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: arch/x86/kernel/cpu/mce/amd.c:236
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
```
**Symbols:**

```
ffffffff81054b10-ffffffff81054cb4: smca_configure (STB_LOCAL)
ffffffff81bd5a38-ffffffff81bd5a4c: smca_configure.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void smca_configure(unsigned int bank, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: arch/x86/kernel/cpu/mce/amd.c:236
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
```
**Symbols:**

```
ffffffff81056da0-ffffffff81056f44: smca_configure (STB_LOCAL)
ffffffff81bc7e79-ffffffff81bc7e8d: smca_configure.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void smca_configure(unsigned int bank, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: arch/x86/kernel/cpu/mce/amd.c:249
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
```
**Symbols:**

```
ffffffff8105f9f0-ffffffff8105fcd1: smca_configure (STB_LOCAL)
ffffffff81c9bb28-ffffffff81c9bb55: smca_configure.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void smca_configure(unsigned int bank, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: arch/x86/kernel/cpu/mce/amd.c:274
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
```
**Symbols:**

```
ffffffff8106c290-ffffffff8106c4db: smca_configure (STB_LOCAL)
ffffffff81e4af44-ffffffff81e4af71: smca_configure.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void smca_configure(unsigned int bank, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: arch/x86/kernel/cpu/mce/amd.c:274
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
```
**Symbols:**

```
ffffffff8107c2c0-ffffffff8107c51f: smca_configure (STB_LOCAL)
ffffffff82052edb-ffffffff82052ef4: smca_configure.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void smca_configure(unsigned int bank, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: arch/x86/kernel/cpu/mce/amd.c:274
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
```
**Symbols:**

```
ffffffff8107e5e0-ffffffff8107e870: smca_configure (STB_LOCAL)
ffffffff820d143c-ffffffff820d1455: smca_configure.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void smca_configure(unsigned int bank, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: arch/x86/kernel/cpu/mce/amd.c:266
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
```
**Symbols:**

```
ffffffff81085af0-ffffffff81085d80: smca_configure (STB_LOCAL)
ffffffff821abfb0-ffffffff821abfc9: smca_configure.cold (STB_LOCAL)
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
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81051e80)
Location: arch/x86/kernel/cpu/mce/amd.c:231
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
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
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81041761)
Location: arch/x86/kernel/cpu/mce/amd.c:231
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
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
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81051d30)
Location: arch/x86/kernel/cpu/mce/amd.c:231
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
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
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81053170)
Location: arch/x86/kernel/cpu/mce/amd.c:231
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
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
