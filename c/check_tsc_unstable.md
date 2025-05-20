# Function: <code>check_tsc_unstable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int check_tsc_unstable();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff81037730)
Location: arch/x86/kernel/tsc.c:332
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/amd.c:early_init_amd
```
**Symbols:**

```
ffffffff81037730-ffffffff8103773c: check_tsc_unstable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int check_tsc_unstable();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff81036950)
Location: arch/x86/kernel/tsc.c:333
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/amd.c:early_init_amd
```
**Symbols:**

```
ffffffff81036950-ffffffff8103695c: check_tsc_unstable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int check_tsc_unstable();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff81036670)
Location: arch/x86/kernel/tsc.c:334
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
  - arch/x86/kernel/cpu/amd.c:early_init_amd
```
**Symbols:**

```
ffffffff81036670-ffffffff8103667c: check_tsc_unstable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int check_tsc_unstable();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff81034680)
Location: arch/x86/kernel/tsc.c:241
Inline: True
```
**Symbols:**

```
ffffffff81034680-ffffffff8103468c: check_tsc_unstable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int check_tsc_unstable();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff810369e0)
Location: arch/x86/kernel/tsc.c:241
Inline: True
Direct callers:
  - arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust
```
**Symbols:**

```
ffffffff810369e0-ffffffff810369ec: check_tsc_unstable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int check_tsc_unstable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff81037a20)
Location: arch/x86/kernel/tsc.c:242
Inline: False
Direct callers:
  - arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust
```
**Symbols:**

```
ffffffff81037a20-ffffffff81037a27: check_tsc_unstable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int check_tsc_unstable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff81038c40)
Location: arch/x86/kernel/tsc.c:259
Inline: False
Direct callers:
  - arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust
```
**Symbols:**

```
ffffffff81038c40-ffffffff81038c47: check_tsc_unstable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int check_tsc_unstable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103b1d0)
Location: arch/x86/kernel/tsc.c:259
Inline: False
Direct callers:
  - arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
**Symbols:**

```
ffffffff8103b1d0-ffffffff8103b1d7: check_tsc_unstable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int check_tsc_unstable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103b9a0)
Location: arch/x86/kernel/tsc.c:259
Inline: False
Direct callers:
  - arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
**Symbols:**

```
ffffffff8103b9a0-ffffffff8103b9a7: check_tsc_unstable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int check_tsc_unstable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103e650)
Location: arch/x86/kernel/tsc.c:266
Inline: False
Direct callers:
  - arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
**Symbols:**

```
ffffffff8103e650-ffffffff8103e657: check_tsc_unstable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int check_tsc_unstable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103e700)
Location: arch/x86/kernel/tsc.c:266
Inline: False
Direct callers:
  - arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
**Symbols:**

```
ffffffff8103e700-ffffffff8103e707: check_tsc_unstable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int check_tsc_unstable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff810400d0)
Location: arch/x86/kernel/tsc.c:267
Inline: False
Direct callers:
  - arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
**Symbols:**

```
ffffffff810400d0-ffffffff810400d7: check_tsc_unstable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int check_tsc_unstable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff810460f0)
Location: arch/x86/kernel/tsc.c:267
Inline: False
Direct callers:
  - arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
**Symbols:**

```
ffffffff810460f0-ffffffff810460f7: check_tsc_unstable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int check_tsc_unstable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8104ed00)
Location: arch/x86/kernel/tsc.c:267
Inline: False
Direct callers:
  - arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
**Symbols:**

```
ffffffff8104ed00-ffffffff8104ed0b: check_tsc_unstable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int check_tsc_unstable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8105bc30)
Location: arch/x86/kernel/tsc.c:267
Inline: False
Direct callers:
  - arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
**Symbols:**

```
ffffffff8105bc30-ffffffff8105bc3b: check_tsc_unstable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int check_tsc_unstable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8105d160)
Location: arch/x86/kernel/tsc.c:288
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
**Symbols:**

```
ffffffff8105d160-ffffffff8105d16b: check_tsc_unstable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int check_tsc_unstable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff81064220)
Location: arch/x86/kernel/tsc.c:288
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
**Symbols:**

```
ffffffff81064220-ffffffff8106422b: check_tsc_unstable (STB_GLOBAL)
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
int check_tsc_unstable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103bb00)
Location: arch/x86/kernel/tsc.c:259
Inline: False
Direct callers:
  - arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
**Symbols:**

```
ffffffff8103bb00-ffffffff8103bb07: check_tsc_unstable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int check_tsc_unstable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8102b280)
Location: arch/x86/kernel/tsc.c:259
Inline: False
Direct callers:
  - arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
**Symbols:**

```
ffffffff8102b280-ffffffff8102b287: check_tsc_unstable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int check_tsc_unstable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103b960)
Location: arch/x86/kernel/tsc.c:259
Inline: False
Direct callers:
  - arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
**Symbols:**

```
ffffffff8103b960-ffffffff8103b967: check_tsc_unstable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int check_tsc_unstable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103c980)
Location: arch/x86/kernel/tsc.c:259
Inline: False
Direct callers:
  - arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust
  - arch/x86/kernel/kvmclock.c:kvmclock_init
```
**Symbols:**

```
ffffffff8103c980-ffffffff8103c987: check_tsc_unstable (STB_GLOBAL)
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
