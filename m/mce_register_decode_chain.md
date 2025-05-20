# Function: <code>mce_register_decode_chain</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void mce_register_decode_chain(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81043a50)
Location: arch/x86/kernel/cpu/mcheck/mce.c:212
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init
```
**Symbols:**

```
ffffffff81043a50-ffffffff81043a83: mce_register_decode_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void mce_register_decode_chain(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81f93369)
Location: arch/x86/kernel/cpu/mcheck/mce.c:209
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init
```
**Symbols:**

```
ffffffff81043b80-ffffffff81043bb3: mce_register_decode_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void mce_register_decode_chain(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff810455f0)
Location: arch/x86/kernel/cpu/mcheck/mce.c:216
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init
```
**Symbols:**

```
ffffffff810455f0-ffffffff8104562a: mce_register_decode_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void mce_register_decode_chain(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff810456f0)
Location: arch/x86/kernel/cpu/mcheck/mce.c:159
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init
  - arch/x86/kernel/cpu/mcheck/dev-mcelog.c:dev_mcelog_init_device
```
**Symbols:**

```
ffffffff810456f0-ffffffff81045721: mce_register_decode_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void mce_register_decode_chain(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81048fe0)
Location: arch/x86/kernel/cpu/mcheck/mce.c:168
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init
  - arch/x86/kernel/cpu/mcheck/dev-mcelog.c:dev_mcelog_init_device
```
**Symbols:**

```
ffffffff81048fe0-ffffffff81049012: mce_register_decode_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void mce_register_decode_chain(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104b910)
Location: arch/x86/kernel/cpu/mcheck/mce.c:163
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init
  - arch/x86/kernel/cpu/mcheck/dev-mcelog.c:dev_mcelog_init_device
```
**Symbols:**

```
ffffffff8104b910-ffffffff8104b942: mce_register_decode_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void mce_register_decode_chain(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81048fd0)
Location: arch/x86/kernel/cpu/mce/core.c:161
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device
```
**Symbols:**

```
ffffffff81048fd0-ffffffff81049002: mce_register_decode_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void mce_register_decode_chain(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: arch/x86/kernel/cpu/mce/core.c:178
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device
```
**Symbols:**

```
ffffffff8104eb67-ffffffff8104eb7a: mce_register_decode_chain.cold (STB_LOCAL)
ffffffff8104c0b0-ffffffff8104c0e2: mce_register_decode_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void mce_register_decode_chain(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104ca40)
Location: arch/x86/kernel/cpu/mce/core.c:178
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device
```
**Symbols:**

```
ffffffff8104ca40-ffffffff8104ca71: mce_register_decode_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void mce_register_decode_chain(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff82cd5879)
Location: arch/x86/kernel/cpu/mce/core.c:163
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
Direct callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device
  - drivers/ras/cec.c:cec_init
```
**Symbols:**

```
ffffffff810512c0-ffffffff810512da: mce_register_decode_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mce_register_decode_chain(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81050590)
Location: arch/x86/kernel/cpu/mce/core.c:163
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device
  - drivers/ras/cec.c:cec_init
```
**Symbols:**

```
ffffffff81050590-ffffffff810505b3: mce_register_decode_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mce_register_decode_chain(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff810520b0)
Location: arch/x86/kernel/cpu/mce/core.c:163
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device
  - drivers/ras/cec.c:cec_init
```
**Symbols:**

```
ffffffff810520b0-ffffffff810520d3: mce_register_decode_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mce_register_decode_chain(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8105a540)
Location: arch/x86/kernel/cpu/mce/core.c:163
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device
  - drivers/ras/cec.c:cec_init
```
**Symbols:**

```
ffffffff8105a540-ffffffff8105a563: mce_register_decode_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mce_register_decode_chain(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81066d30)
Location: arch/x86/kernel/cpu/mce/core.c:149
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device
  - drivers/ras/cec.c:cec_init
```
**Symbols:**

```
ffffffff81066d30-ffffffff81066d67: mce_register_decode_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void mce_register_decode_chain(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff83e7f825)
Location: arch/x86/kernel/cpu/mce/core.c:149
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
Direct callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device
  - drivers/ras/cec.c:cec_init
```
**Symbols:**

```
ffffffff810760a0-ffffffff810760d7: mce_register_decode_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void mce_register_decode_chain(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff836a2575)
Location: arch/x86/kernel/cpu/mce/core.c:143
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
Direct callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device
  - drivers/ras/cec.c:cec_init
```
**Symbols:**

```
ffffffff81078220-ffffffff81078257: mce_register_decode_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void mce_register_decode_chain(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff838d2675)
Location: arch/x86/kernel/cpu/mce/core.c:145
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
Direct callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device
  - drivers/ras/cec.c:cec_init
```
**Symbols:**

```
ffffffff8107f6d0-ffffffff8107f707: mce_register_decode_chain (STB_GLOBAL)
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
void mce_register_decode_chain(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104cbb0)
Location: arch/x86/kernel/cpu/mce/core.c:178
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device
```
**Symbols:**

```
ffffffff8104cbb0-ffffffff8104cbe1: mce_register_decode_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void mce_register_decode_chain(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8103bf60)
Location: arch/x86/kernel/cpu/mce/core.c:178
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device
  - drivers/acpi/nfit/mce.c:nfit_mce_register
  - drivers/edac/mce_amd.c:mce_amd_init
```
**Symbols:**

```
ffffffff8103bf60-ffffffff8103bf91: mce_register_decode_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void mce_register_decode_chain(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104c9f0)
Location: arch/x86/kernel/cpu/mce/core.c:178
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device
```
**Symbols:**

```
ffffffff8104c9f0-ffffffff8104ca21: mce_register_decode_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void mce_register_decode_chain(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104de00)
Location: arch/x86/kernel/cpu/mce/core.c:178
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device
```
**Symbols:**

```
ffffffff8104de00-ffffffff8104de31: mce_register_decode_chain (STB_GLOBAL)
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
