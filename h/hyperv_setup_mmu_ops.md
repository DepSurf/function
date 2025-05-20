# Function: <code>hyperv_setup_mmu_ops</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void hyperv_setup_mmu_ops();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/mmu.c (ffffffff8102aec0)
Location: arch/x86/hyperv/mmu.c:276
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
**Symbols:**

```
ffffffff8102aec0-ffffffff8102af19: hyperv_setup_mmu_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void hyperv_setup_mmu_ops();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/mmu.c (0)
Location: arch/x86/hyperv/mmu.c:229
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
**Symbols:**

```
ffffffff8102bac9-ffffffff8102bb06: hyperv_setup_mmu_ops.cold.5 (STB_LOCAL)
ffffffff8102bab0-ffffffff8102bac9: hyperv_setup_mmu_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void hyperv_setup_mmu_ops();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/mmu.c (0)
Location: arch/x86/hyperv/mmu.c:228
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
**Symbols:**

```
ffffffff8102c6c8-ffffffff8102c6ef: hyperv_setup_mmu_ops.cold.8 (STB_LOCAL)
ffffffff8102c6b0-ffffffff8102c6c8: hyperv_setup_mmu_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void hyperv_setup_mmu_ops();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/mmu.c (0)
Location: arch/x86/hyperv/mmu.c:230
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
**Symbols:**

```
ffffffff8102e4a8-ffffffff8102e4cf: hyperv_setup_mmu_ops.cold (STB_LOCAL)
ffffffff8102e490-ffffffff8102e4a8: hyperv_setup_mmu_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void hyperv_setup_mmu_ops();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/mmu.c (0)
Location: arch/x86/hyperv/mmu.c:230
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
**Symbols:**

```
ffffffff8102edb8-ffffffff8102eddf: hyperv_setup_mmu_ops.cold (STB_LOCAL)
ffffffff8102eda0-ffffffff8102edb8: hyperv_setup_mmu_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void hyperv_setup_mmu_ops();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/mmu.c (0)
Location: arch/x86/hyperv/mmu.c:230
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
**Symbols:**

```
ffffffff810313f8-ffffffff8103141f: hyperv_setup_mmu_ops.cold (STB_LOCAL)
ffffffff810313e0-ffffffff810313f8: hyperv_setup_mmu_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void hyperv_setup_mmu_ops();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/mmu.c (0)
Location: arch/x86/hyperv/mmu.c:236
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
**Symbols:**

```
ffffffff81bd2f0c-ffffffff81bd2f33: hyperv_setup_mmu_ops.cold (STB_LOCAL)
ffffffff81032130-ffffffff81032148: hyperv_setup_mmu_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void hyperv_setup_mmu_ops();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/mmu.c (0)
Location: arch/x86/hyperv/mmu.c:236
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
**Symbols:**

```
ffffffff81bc5294-ffffffff81bc52bc: hyperv_setup_mmu_ops.cold (STB_LOCAL)
ffffffff81032c90-ffffffff81032ca3: hyperv_setup_mmu_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void hyperv_setup_mmu_ops();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/mmu.c (0)
Location: arch/x86/hyperv/mmu.c:235
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
**Symbols:**

```
ffffffff81c97e43-ffffffff81c97e6b: hyperv_setup_mmu_ops.cold (STB_LOCAL)
ffffffff81037e40-ffffffff81037e53: hyperv_setup_mmu_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void hyperv_setup_mmu_ops();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/mmu.c (0)
Location: arch/x86/hyperv/mmu.c:235
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
**Symbols:**

```
ffffffff81e4727e-ffffffff81e472ae: hyperv_setup_mmu_ops.cold (STB_LOCAL)
ffffffff8103e090-ffffffff8103e0ab: hyperv_setup_mmu_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void hyperv_setup_mmu_ops();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/mmu.c (ffffffff81046ef0)
Location: arch/x86/hyperv/mmu.c:235
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
**Symbols:**

```
ffffffff81046ef0-ffffffff81046f37: hyperv_setup_mmu_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void hyperv_setup_mmu_ops();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/mmu.c (ffffffff810471b0)
Location: arch/x86/hyperv/mmu.c:236
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
**Symbols:**

```
ffffffff810471b0-ffffffff810471f7: hyperv_setup_mmu_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void hyperv_setup_mmu_ops();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/mmu.c (ffffffff8104d850)
Location: arch/x86/hyperv/mmu.c:236
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
**Symbols:**

```
ffffffff8104d850-ffffffff8104d897: hyperv_setup_mmu_ops (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void hyperv_setup_mmu_ops();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/mmu.c (0)
Location: arch/x86/hyperv/mmu.c:230
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
**Symbols:**

```
ffffffff8102ef18-ffffffff8102ef3f: hyperv_setup_mmu_ops.cold (STB_LOCAL)
ffffffff8102ef00-ffffffff8102ef18: hyperv_setup_mmu_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void hyperv_setup_mmu_ops();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/mmu.c (0)
Location: arch/x86/hyperv/mmu.c:230
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
**Symbols:**

```
ffffffff8101e8b8-ffffffff8101e8df: hyperv_setup_mmu_ops.cold (STB_LOCAL)
ffffffff8101e8a0-ffffffff8101e8b8: hyperv_setup_mmu_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void hyperv_setup_mmu_ops();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/mmu.c (0)
Location: arch/x86/hyperv/mmu.c:230
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
**Symbols:**

```
ffffffff8102ed78-ffffffff8102ed9f: hyperv_setup_mmu_ops.cold (STB_LOCAL)
ffffffff8102ed60-ffffffff8102ed78: hyperv_setup_mmu_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void hyperv_setup_mmu_ops();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/mmu.c (0)
Location: arch/x86/hyperv/mmu.c:230
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
**Symbols:**

```
ffffffff8102fb88-ffffffff8102fbaf: hyperv_setup_mmu_ops.cold (STB_LOCAL)
ffffffff8102fb70-ffffffff8102fb88: hyperv_setup_mmu_ops (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
