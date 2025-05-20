# Function: <code>setup_APIC_eilvt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int setup_APIC_eilvt(u8 offset, u8 vector, u8 msg_type, u8 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81053340)
Location: arch/x86/kernel/apic/apic.c:421
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init
```
**Symbols:**

```
ffffffff81053340-ffffffff8105349c: setup_APIC_eilvt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int setup_APIC_eilvt(u8 offset, u8 vector, u8 msg_type, u8 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81053450)
Location: arch/x86/kernel/apic/apic.c:429
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/amd/ibs.c:clear_APIC_ibs
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:prepare_threshold_block
```
**Symbols:**

```
ffffffff81053450-ffffffff810535b5: setup_APIC_eilvt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int setup_APIC_eilvt(u8 offset, u8 vector, u8 msg_type, u8 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81056140)
Location: arch/x86/kernel/apic/apic.c:430
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/amd/ibs.c:clear_APIC_ibs
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:prepare_threshold_block
```
**Symbols:**

```
ffffffff81056140-ffffffff810562a5: setup_APIC_eilvt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int setup_APIC_eilvt(u8 offset, u8 vector, u8 msg_type, u8 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81055a70)
Location: arch/x86/kernel/apic/apic.c:432
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/amd/ibs.c:clear_APIC_ibs
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:prepare_threshold_block
```
**Symbols:**

```
ffffffff81055a70-ffffffff81055bc4: setup_APIC_eilvt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int setup_APIC_eilvt(u8 offset, u8 vector, u8 msg_type, u8 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff810595a0)
Location: arch/x86/kernel/apic/apic.c:423
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/amd/ibs.c:clear_APIC_ibs
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:prepare_threshold_block
```
**Symbols:**

```
ffffffff810595a0-ffffffff810596fa: setup_APIC_eilvt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int setup_APIC_eilvt(u8 offset, u8 vector, u8 msg_type, u8 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8105c870)
Location: arch/x86/kernel/apic/apic.c:424
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/amd/ibs.c:clear_APIC_ibs
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:prepare_threshold_block
```
**Symbols:**

```
ffffffff8105c870-ffffffff8105c9cd: setup_APIC_eilvt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int setup_APIC_eilvt(u8 offset, u8 vector, u8 msg_type, u8 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff810624f0)
Location: arch/x86/kernel/apic/apic.c:430
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/amd/ibs.c:clear_APIC_ibs
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block
```
**Symbols:**

```
ffffffff810624f0-ffffffff8106265a: setup_APIC_eilvt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int setup_APIC_eilvt(u8 offset, u8 vector, u8 msg_type, u8 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:431
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/amd/ibs.c:clear_APIC_ibs
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block
```
**Symbols:**

```
ffffffff81066dfe-ffffffff81066e40: setup_APIC_eilvt.cold (STB_LOCAL)
ffffffff81065bb0-ffffffff81065ce3: setup_APIC_eilvt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int setup_APIC_eilvt(u8 offset, u8 vector, u8 msg_type, u8 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:431
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/amd/ibs.c:clear_APIC_ibs
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block
```
**Symbols:**

```
ffffffff81067473-ffffffff810674b5: setup_APIC_eilvt.cold (STB_LOCAL)
ffffffff810661e0-ffffffff81066313: setup_APIC_eilvt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int setup_APIC_eilvt(u8 offset, u8 vector, u8 msg_type, u8 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:429
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu
  - arch/x86/events/amd/ibs.c:perf_ibs_suspend
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block
```
**Symbols:**

```
ffffffff8106e0a6-ffffffff8106e0e8: setup_APIC_eilvt.cold (STB_LOCAL)
ffffffff8106ca90-ffffffff8106cbc2: setup_APIC_eilvt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int setup_APIC_eilvt(u8 offset, u8 vector, u8 msg_type, u8 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:435
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu
  - arch/x86/events/amd/ibs.c:perf_ibs_suspend
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block
```
**Symbols:**

```
ffffffff81bd6e0e-ffffffff81bd6e50: setup_APIC_eilvt.cold (STB_LOCAL)
ffffffff8106e240-ffffffff8106e372: setup_APIC_eilvt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int setup_APIC_eilvt(u8 offset, u8 vector, u8 msg_type, u8 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:435
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu
  - arch/x86/events/amd/ibs.c:perf_ibs_suspend
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block
```
**Symbols:**

```
ffffffff81bc8f9b-ffffffff81bc8fdd: setup_APIC_eilvt.cold (STB_LOCAL)
ffffffff8106ec60-ffffffff8106ed91: setup_APIC_eilvt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int setup_APIC_eilvt(u8 offset, u8 vector, u8 msg_type, u8 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:432
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu
  - arch/x86/events/amd/ibs.c:perf_ibs_suspend
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block
```
**Symbols:**

```
ffffffff81c9d9ef-ffffffff81c9da3a: setup_APIC_eilvt.cold (STB_LOCAL)
ffffffff8107a5e0-ffffffff8107a79b: setup_APIC_eilvt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int setup_APIC_eilvt(u8 offset, u8 vector, u8 msg_type, u8 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:441
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu
  - arch/x86/events/amd/ibs.c:perf_ibs_suspend
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block
```
**Symbols:**

```
ffffffff81e4cd2e-ffffffff81e4cd79: setup_APIC_eilvt.cold (STB_LOCAL)
ffffffff81088e20-ffffffff81088fc7: setup_APIC_eilvt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int setup_APIC_eilvt(u8 offset, u8 vector, u8 msg_type, u8 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8109ca90)
Location: arch/x86/kernel/apic/apic.c:442
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu
  - arch/x86/events/amd/ibs.c:perf_ibs_suspend
  - arch/x86/events/amd/ibs.c:setup_APIC_ibs
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block
```
**Symbols:**

```
ffffffff8109ca90-ffffffff8109cca3: setup_APIC_eilvt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int setup_APIC_eilvt(u8 offset, u8 vector, u8 msg_type, u8 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8109f9b0)
Location: arch/x86/kernel/apic/apic.c:444
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu
  - arch/x86/events/amd/ibs.c:perf_ibs_suspend
  - arch/x86/events/amd/ibs.c:setup_APIC_ibs
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block
```
**Symbols:**

```
ffffffff8109f9b0-ffffffff8109fbc5: setup_APIC_eilvt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int setup_APIC_eilvt(u8 offset, u8 vector, u8 msg_type, u8 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff810a6f20)
Location: arch/x86/kernel/apic/apic.c:411
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu
  - arch/x86/events/amd/ibs.c:perf_ibs_suspend
  - arch/x86/events/amd/ibs.c:setup_APIC_ibs
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block
```
**Symbols:**

```
ffffffff810a6f20-ffffffff810a711f: setup_APIC_eilvt (STB_GLOBAL)
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
int setup_APIC_eilvt(u8 offset, u8 vector, u8 msg_type, u8 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:431
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/amd/ibs.c:clear_APIC_ibs
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block
```
**Symbols:**

```
ffffffff81066f63-ffffffff81066fa5: setup_APIC_eilvt.cold (STB_LOCAL)
ffffffff81065cd0-ffffffff81065e03: setup_APIC_eilvt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int setup_APIC_eilvt(u8 offset, u8 vector, u8 msg_type, u8 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:431
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/amd/ibs.c:clear_APIC_ibs
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block
```
**Symbols:**

```
ffffffff81057320-ffffffff81057362: setup_APIC_eilvt.cold (STB_LOCAL)
ffffffff81056050-ffffffff81056183: setup_APIC_eilvt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int setup_APIC_eilvt(u8 offset, u8 vector, u8 msg_type, u8 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:431
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/amd/ibs.c:clear_APIC_ibs
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block
```
**Symbols:**

```
ffffffff81067413-ffffffff81067455: setup_APIC_eilvt.cold (STB_LOCAL)
ffffffff81066180-ffffffff810662b3: setup_APIC_eilvt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int setup_APIC_eilvt(u8 offset, u8 vector, u8 msg_type, u8 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:431
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/amd/ibs.c:clear_APIC_ibs
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init
  - arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block
```
**Symbols:**

```
ffffffff810689f3-ffffffff81068a35: setup_APIC_eilvt.cold (STB_LOCAL)
ffffffff81067760-ffffffff81067893: setup_APIC_eilvt (STB_GLOBAL)
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
