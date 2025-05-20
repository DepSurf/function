# Function: <code>cmci_discover</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void cmci_discover(int banks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff810470b0)
Location: arch/x86/kernel/cpu/mcheck/mce_intel.c:261
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_rediscover_work_func
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_reenable
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
```
**Symbols:**

```
ffffffff810470b0-ffffffff81047303: cmci_discover (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void cmci_discover(int banks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff81047280)
Location: arch/x86/kernel/cpu/mcheck/mce_intel.c:261
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_reenable
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_rediscover_work_func
```
**Symbols:**

```
ffffffff81047280-ffffffff81047490: cmci_discover (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void cmci_discover(int banks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff81048e20)
Location: arch/x86/kernel/cpu/mcheck/mce_intel.c:263
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_reenable
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_rediscover_work_func
```
**Symbols:**

```
ffffffff81048e20-ffffffff81049030: cmci_discover (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void cmci_discover(int banks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff810487b0)
Location: arch/x86/kernel/cpu/mcheck/mce_intel.c:263
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_reenable
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_rediscover_work_func
```
**Symbols:**

```
ffffffff810487b0-ffffffff810489d3: cmci_discover (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void cmci_discover(int banks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff8104c3e0)
Location: arch/x86/kernel/cpu/mcheck/mce_intel.c:264
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_reenable
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_rediscover_work_func
```
**Symbols:**

```
ffffffff8104c3e0-ffffffff8104c603: cmci_discover (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void cmci_discover(int banks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce_intel.c (0)
Location: arch/x86/kernel/cpu/mcheck/mce_intel.c:264
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_reenable
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_rediscover_work_func
```
**Symbols:**

```
ffffffff8104f0f0-ffffffff8104f2e0: cmci_discover (STB_LOCAL)
ffffffff8104f84d-ffffffff8104f87d: cmci_discover.cold.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void cmci_discover(int banks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/intel.c (0)
Location: arch/x86/kernel/cpu/mce/intel.c:264
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mce/intel.c:cmci_reenable
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover_work_func
```
**Symbols:**

```
ffffffff8104c7c0-ffffffff8104c9b0: cmci_discover (STB_LOCAL)
ffffffff8104cf0d-ffffffff8104cf3d: cmci_discover.cold.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void cmci_discover(int banks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/intel.c (0)
Location: arch/x86/kernel/cpu/mce/intel.c:264
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mce/intel.c:cmci_reenable
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover_work_func
```
**Symbols:**

```
ffffffff8104f6e0-ffffffff8104f8cc: cmci_discover (STB_LOCAL)
ffffffff8104fe3d-ffffffff8104fe80: cmci_discover.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void cmci_discover(int banks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/intel.c (0)
Location: arch/x86/kernel/cpu/mce/intel.c:264
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mce/intel.c:cmci_reenable
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover_work_func
```
**Symbols:**

```
ffffffff81050060-ffffffff81050253: cmci_discover (STB_LOCAL)
ffffffff810507cd-ffffffff810507fd: cmci_discover.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void cmci_discover(int banks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/intel.c (0)
Location: arch/x86/kernel/cpu/mce/intel.c:267
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/intel.c:intel_init_cmci
  - arch/x86/kernel/cpu/mce/intel.c:cmci_reenable
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover_work_func
```
**Symbols:**

```
ffffffff81054510-ffffffff810546f8: cmci_discover (STB_LOCAL)
ffffffff81054ecf-ffffffff81054eff: cmci_discover.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void cmci_discover(int banks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/intel.c (0)
Location: arch/x86/kernel/cpu/mce/intel.c:267
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/intel.c:intel_init_cmci
  - arch/x86/kernel/cpu/mce/intel.c:cmci_reenable
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover_work_func
```
**Symbols:**

```
ffffffff81053450-ffffffff81053638: cmci_discover (STB_LOCAL)
ffffffff81bd58c7-ffffffff81bd58f7: cmci_discover.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void cmci_discover(int banks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/intel.c (0)
Location: arch/x86/kernel/cpu/mce/intel.c:267
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/intel.c:intel_init_cmci
  - arch/x86/kernel/cpu/mce/intel.c:cmci_reenable
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover_work_func
```
**Symbols:**

```
ffffffff81054d20-ffffffff81054f05: cmci_discover (STB_LOCAL)
ffffffff81bc7d26-ffffffff81bc7d56: cmci_discover.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void cmci_discover(int banks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/intel.c (0)
Location: arch/x86/kernel/cpu/mce/intel.c:267
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/intel.c:intel_init_cmci
  - arch/x86/kernel/cpu/mce/intel.c:cmci_reenable
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover_work_func
```
**Symbols:**

```
ffffffff8105d670-ffffffff8105d86d: cmci_discover (STB_LOCAL)
ffffffff81c9b91b-ffffffff81c9b973: cmci_discover.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void cmci_discover(int banks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/intel.c (0)
Location: arch/x86/kernel/cpu/mce/intel.c:267
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/intel.c:intel_init_cmci
  - arch/x86/kernel/cpu/mce/intel.c:cmci_reenable
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover_work_func
```
**Symbols:**

```
ffffffff81069bd0-ffffffff81069e33: cmci_discover (STB_LOCAL)
ffffffff81e4add3-ffffffff81e4ae2b: cmci_discover.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void cmci_discover(int banks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/intel.c (0)
Location: arch/x86/kernel/cpu/mce/intel.c:267
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/intel.c:intel_init_cmci
  - arch/x86/kernel/cpu/mce/intel.c:cmci_reenable
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover_work_func
```
**Symbols:**

```
ffffffff810799b0-ffffffff81079c1a: cmci_discover (STB_LOCAL)
ffffffff82052e19-ffffffff82052e41: cmci_discover.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void cmci_discover(int banks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/intel.c (0)
Location: arch/x86/kernel/cpu/mce/intel.c:267
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/intel.c:intel_init_cmci
  - arch/x86/kernel/cpu/mce/intel.c:cmci_reenable
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover_work_func
```
**Symbols:**

```
ffffffff8107bc60-ffffffff8107beca: cmci_discover (STB_LOCAL)
ffffffff820d1348-ffffffff820d1370: cmci_discover.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void cmci_discover(int banks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/intel.c (0)
Location: arch/x86/kernel/cpu/mce/intel.c:276
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/intel.c:intel_init_cmci
  - arch/x86/kernel/cpu/mce/intel.c:cmci_reenable
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover_work_func
```
**Symbols:**

```
ffffffff810832d0-ffffffff8108341a: cmci_discover (STB_LOCAL)
ffffffff821abebc-ffffffff821abee4: cmci_discover.cold (STB_LOCAL)
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
void cmci_discover(int banks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/intel.c (0)
Location: arch/x86/kernel/cpu/mce/intel.c:264
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mce/intel.c:cmci_reenable
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover_work_func
```
**Symbols:**

```
ffffffff81050160-ffffffff81050353: cmci_discover (STB_LOCAL)
ffffffff810508cd-ffffffff810508fd: cmci_discover.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void cmci_discover(int banks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/intel.c (0)
Location: arch/x86/kernel/cpu/mce/intel.c:264
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mce/intel.c:cmci_reenable
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover_work_func
```
**Symbols:**

```
ffffffff8103f640-ffffffff8103f88c: cmci_discover (STB_LOCAL)
ffffffff8103ffed-ffffffff8104001d: cmci_discover.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void cmci_discover(int banks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/intel.c (0)
Location: arch/x86/kernel/cpu/mce/intel.c:264
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mce/intel.c:cmci_reenable
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover_work_func
```
**Symbols:**

```
ffffffff81050010-ffffffff81050203: cmci_discover (STB_LOCAL)
ffffffff8105077d-ffffffff810507ad: cmci_discover.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void cmci_discover(int banks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/intel.c (0)
Location: arch/x86/kernel/cpu/mce/intel.c:264
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
  - arch/x86/kernel/cpu/mce/intel.c:cmci_reenable
  - arch/x86/kernel/cpu/mce/intel.c:cmci_rediscover_work_func
```
**Symbols:**

```
ffffffff81051450-ffffffff81051643: cmci_discover (STB_LOCAL)
ffffffff81051bbd-ffffffff81051bed: cmci_discover.cold (STB_LOCAL)
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
