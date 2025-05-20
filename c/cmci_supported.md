# Function: <code>cmci_supported</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int cmci_supported(int *banks);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff810473a0)
Location: arch/x86/kernel/cpu/mcheck/mce_intel.c:73
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_rediscover_work_func
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_clear
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_rediscover
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_reenable
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_disable_bank
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
```
**Symbols:**

```
ffffffff810473a0-ffffffff81047437: cmci_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int cmci_supported(int *banks);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff810474f0)
Location: arch/x86/kernel/cpu/mcheck/mce_intel.c:73
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_disable_bank
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_reenable
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_rediscover
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_rediscover_work_func
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_clear
```
**Symbols:**

```
ffffffff810474f0-ffffffff81047556: cmci_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int cmci_supported(int *banks);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff81049090)
Location: arch/x86/kernel/cpu/mcheck/mce_intel.c:75
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_disable_bank
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_reenable
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_rediscover
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_rediscover_work_func
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_clear
```
**Symbols:**

```
ffffffff81049090-ffffffff810490f6: cmci_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int cmci_supported(int *banks);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff81048a40)
Location: arch/x86/kernel/cpu/mcheck/mce_intel.c:75
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_disable_bank
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_reenable
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_rediscover
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_rediscover_work_func
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_clear
```
**Symbols:**

```
ffffffff81048a40-ffffffff81048aa6: cmci_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int cmci_supported(int *banks);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff8104c180)
Location: arch/x86/kernel/cpu/mcheck/mce_intel.c:76
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_disable_bank
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_reenable
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_rediscover
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_rediscover_work_func
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_clear
```
**Symbols:**

```
ffffffff8104c180-ffffffff8104c1e6: cmci_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int cmci_supported(int *banks);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff8104ee90)
Location: arch/x86/kernel/cpu/mcheck/mce_intel.c:76
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_disable_bank
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_reenable
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_rediscover
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_rediscover_work_func
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_clear
```
**Symbols:**

```
ffffffff8104ee90-ffffffff8104eef6: cmci_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int cmci_supported(int *banks);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8104c560)
Location: arch/x86/kernel/cpu/mce/intel.c:76
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mce/intel.c:cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_reenable
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover_work_func
  - arch/x86/kernel/cpu/mce/intel.c:cmci_clear
```
**Symbols:**

```
ffffffff8104c560-ffffffff8104c5c6: cmci_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int cmci_supported(int *banks);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8104f4f0)
Location: arch/x86/kernel/cpu/mce/intel.c:76
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mce/intel.c:cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_reenable
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover_work_func
  - arch/x86/kernel/cpu/mce/intel.c:cmci_clear
```
**Symbols:**

```
ffffffff8104f4f0-ffffffff8104f555: cmci_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int cmci_supported(int *banks);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8104fe70)
Location: arch/x86/kernel/cpu/mce/intel.c:76
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mce/intel.c:cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_reenable
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover_work_func
  - arch/x86/kernel/cpu/mce/intel.c:cmci_clear
```
**Symbols:**

```
ffffffff8104fe70-ffffffff8104fed5: cmci_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int cmci_supported(int *banks);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81054760)
Location: arch/x86/kernel/cpu/mce/intel.c:76
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/intel.c:intel_init_cmci
  - arch/x86/kernel/cpu/mce/intel.c:intel_init_cmci
  - arch/x86/kernel/cpu/mce/intel.c:cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_reenable
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover_work_func
  - arch/x86/kernel/cpu/mce/intel.c:cmci_clear
  - arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer
```
**Symbols:**

```
ffffffff81054760-ffffffff810547d1: cmci_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int cmci_supported(int *banks);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff810536a0)
Location: arch/x86/kernel/cpu/mce/intel.c:76
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/intel.c:intel_init_cmci
  - arch/x86/kernel/cpu/mce/intel.c:intel_init_cmci
  - arch/x86/kernel/cpu/mce/intel.c:cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_reenable
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover_work_func
  - arch/x86/kernel/cpu/mce/intel.c:cmci_clear
  - arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer
```
**Symbols:**

```
ffffffff810536a0-ffffffff81053711: cmci_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int cmci_supported(int *banks);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81054f70)
Location: arch/x86/kernel/cpu/mce/intel.c:76
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/intel.c:intel_init_cmci
  - arch/x86/kernel/cpu/mce/intel.c:intel_init_cmci
  - arch/x86/kernel/cpu/mce/intel.c:cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_reenable
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover_work_func
  - arch/x86/kernel/cpu/mce/intel.c:cmci_clear
  - arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer
```
**Symbols:**

```
ffffffff81054f70-ffffffff81054fe1: cmci_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int cmci_supported(int *banks);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8105d8d0)
Location: arch/x86/kernel/cpu/mce/intel.c:76
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/intel.c:intel_init_cmci
  - arch/x86/kernel/cpu/mce/intel.c:intel_init_cmci
  - arch/x86/kernel/cpu/mce/intel.c:cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_reenable
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover_work_func
  - arch/x86/kernel/cpu/mce/intel.c:cmci_clear
  - arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer
```
**Symbols:**

```
ffffffff8105d8d0-ffffffff8105d941: cmci_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int cmci_supported(int *banks);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81069f50)
Location: arch/x86/kernel/cpu/mce/intel.c:76
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/intel.c:intel_init_cmci
  - arch/x86/kernel/cpu/mce/intel.c:intel_init_cmci
  - arch/x86/kernel/cpu/mce/intel.c:cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_reenable
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover_work_func
  - arch/x86/kernel/cpu/mce/intel.c:cmci_clear
  - arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer
```
**Symbols:**

```
ffffffff81069f50-ffffffff8106a008: cmci_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int cmci_supported(int *banks);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81079cd0)
Location: arch/x86/kernel/cpu/mce/intel.c:76
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/intel.c:intel_init_cmci
  - arch/x86/kernel/cpu/mce/intel.c:intel_init_cmci
  - arch/x86/kernel/cpu/mce/intel.c:cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_reenable
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover_work_func
  - arch/x86/kernel/cpu/mce/intel.c:cmci_clear
  - arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer
```
**Symbols:**

```
ffffffff81079cd0-ffffffff81079d88: cmci_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int cmci_supported(int *banks);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8107bf80)
Location: arch/x86/kernel/cpu/mce/intel.c:76
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/intel.c:intel_init_cmci
  - arch/x86/kernel/cpu/mce/intel.c:intel_init_cmci
  - arch/x86/kernel/cpu/mce/intel.c:cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_reenable
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover_work_func
  - arch/x86/kernel/cpu/mce/intel.c:cmci_clear
  - arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer
```
**Symbols:**

```
ffffffff8107bf80-ffffffff8107c038: cmci_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int cmci_supported(int *banks);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81083945)
Location: arch/x86/kernel/cpu/mce/intel.c:78
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:cmci_reenable
  - arch/x86/kernel/cpu/mce/intel.c:cmci_reenable
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover_work_func
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover_work_func
Direct callers:
  - arch/x86/kernel/cpu/mce/intel.c:intel_init_cmci
  - arch/x86/kernel/cpu/mce/intel.c:intel_init_cmci
  - arch/x86/kernel/cpu/mce/intel.c:cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_clear
```
**Symbols:**

```
ffffffff810834d0-ffffffff81083588: cmci_supported (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int cmci_supported(int *banks);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8104ff70)
Location: arch/x86/kernel/cpu/mce/intel.c:76
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mce/intel.c:cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_reenable
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover_work_func
  - arch/x86/kernel/cpu/mce/intel.c:cmci_clear
```
**Symbols:**

```
ffffffff8104ff70-ffffffff8104ffd5: cmci_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int cmci_supported(int *banks);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8103f5b0)
Location: arch/x86/kernel/cpu/mce/intel.c:76
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mce/intel.c:cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_reenable
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover_work_func
  - arch/x86/kernel/cpu/mce/intel.c:cmci_clear
```
**Symbols:**

```
ffffffff8103f5b0-ffffffff8103f63c: cmci_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int cmci_supported(int *banks);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8104fe20)
Location: arch/x86/kernel/cpu/mce/intel.c:76
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mce/intel.c:cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_reenable
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover_work_func
  - arch/x86/kernel/cpu/mce/intel.c:cmci_clear
```
**Symbols:**

```
ffffffff8104fe20-ffffffff8104fe85: cmci_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int cmci_supported(int *banks);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81051260)
Location: arch/x86/kernel/cpu/mce/intel.c:76
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mce/intel.c:cmci_disable_bank
  - arch/x86/kernel/cpu/mce/intel.c:cmci_reenable
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover_work_func
  - arch/x86/kernel/cpu/mce/intel.c:cmci_clear
```
**Symbols:**

```
ffffffff81051260-ffffffff810512c5: cmci_supported (STB_LOCAL)
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
