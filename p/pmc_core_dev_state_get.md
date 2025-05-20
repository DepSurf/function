# Function: <code>pmc_core_dev_state_get</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pmc_core_dev_state_get(void *data, u64 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/x86/intel_pmc_core.c (ffffffff81747420)
Location: drivers/platform/x86/intel_pmc_core.c:80
Inline: False
```
**Symbols:**

```
ffffffff81747420-ffffffff8174743d: pmc_core_dev_state_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pmc_core_dev_state_get(void *data, u64 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/x86/intel_pmc_core.c (ffffffff8177a650)
Location: drivers/platform/x86/intel_pmc_core.c:172
Inline: False
```
**Symbols:**

```
ffffffff8177a650-ffffffff8177a66d: pmc_core_dev_state_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pmc_core_dev_state_get(void *data, u64 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/x86/intel_pmc_core.c (ffffffff81798ac0)
Location: drivers/platform/x86/intel_pmc_core.c:172
Inline: False
```
**Symbols:**

```
ffffffff81798ac0-ffffffff81798add: pmc_core_dev_state_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pmc_core_dev_state_get(void *data, u64 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/x86/intel_pmc_core.c (ffffffff8180f110)
Location: drivers/platform/x86/intel_pmc_core.c:231
Inline: False
```
**Symbols:**

```
ffffffff8180f110-ffffffff8180f131: pmc_core_dev_state_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pmc_core_dev_state_get(void *data, u64 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/x86/intel_pmc_core.c (ffffffff81858f90)
Location: drivers/platform/x86/intel_pmc_core.c:231
Inline: False
```
**Symbols:**

```
ffffffff81858f90-ffffffff81858fb1: pmc_core_dev_state_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pmc_core_dev_state_get(void *data, u64 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/x86/intel_pmc_core.c (ffffffff81877f40)
Location: drivers/platform/x86/intel_pmc_core.c:336
Inline: False
```
**Symbols:**

```
ffffffff81877f40-ffffffff81877f61: pmc_core_dev_state_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int pmc_core_dev_state_get(void *data, u64 *val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/platform/x86/intel_pmc_core.c (ffffffff818bd6fb)
Location: drivers/platform/x86/intel_pmc_core.c:388
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_resume
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_suspend
```
**Symbols:**

```
ffffffff818bcbc0-ffffffff818bcbec: pmc_core_dev_state_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int pmc_core_dev_state_get(void *data, u64 *val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/platform/x86/intel_pmc_core.c (ffffffff818f021b)
Location: drivers/platform/x86/intel_pmc_core.c:389
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_resume
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_suspend
```
**Symbols:**

```
ffffffff818ef6e0-ffffffff818ef70c: pmc_core_dev_state_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int pmc_core_dev_state_get(void *data, u64 *val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/platform/x86/intel_pmc_core.c (ffffffff819c482c)
Location: drivers/platform/x86/intel_pmc_core.c:594
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_resume
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_suspend
```
**Symbols:**

```
ffffffff819c3690-ffffffff819c36bc: pmc_core_dev_state_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int pmc_core_dev_state_get(void *data, u64 *val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/platform/x86/intel_pmc_core.c (ffffffff819c4b1c)
Location: drivers/platform/x86/intel_pmc_core.c:606
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_resume
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_suspend
```
**Symbols:**

```
ffffffff819c3a60-ffffffff819c3a8c: pmc_core_dev_state_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int pmc_core_dev_state_get(void *data, u64 *val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/platform/x86/intel_pmc_core.c (ffffffff819a99fc)
Location: drivers/platform/x86/intel_pmc_core.c:773
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_resume
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_suspend
```
**Symbols:**

```
ffffffff819a7fa0-ffffffff819a7fcc: pmc_core_dev_state_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int pmc_core_dev_state_get(void *data, u64 *val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/platform/x86/intel/pmc/core.c (ffffffff81a57152)
Location: drivers/platform/x86/intel/pmc/core.c:1073
Inline: True
Inline callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_resume
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_suspend
```
**Symbols:**

```
ffffffff81a552d0-ffffffff81a552fc: pmc_core_dev_state_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int pmc_core_dev_state_get(void *data, u64 *val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/platform/x86/intel/pmc/core.c (ffffffff81bc6960)
Location: drivers/platform/x86/intel/pmc/core.c:1073
Inline: True
Inline callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_resume
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_suspend
```
**Symbols:**

```
ffffffff81bc4a40-ffffffff81bc4a76: pmc_core_dev_state_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int pmc_core_dev_state_get(void *data, u64 *val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/platform/x86/intel/pmc/core.c (ffffffff81d6eb50)
Location: drivers/platform/x86/intel/pmc/core.c:181
Inline: True
Inline callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_resume
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_suspend
```
**Symbols:**

```
ffffffff81d6cc00-ffffffff81d6cc36: pmc_core_dev_state_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int pmc_core_dev_state_get(void *data, u64 *val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/platform/x86/intel/pmc/core.c (ffffffff81ddc86f)
Location: drivers/platform/x86/intel/pmc/core.c:195
Inline: True
Inline callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_resume_common
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_suspend
```
**Symbols:**

```
ffffffff81dd9ff0-ffffffff81dda051: pmc_core_dev_state_get (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
int pmc_core_dev_state_get(void *data, u64 *val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/platform/x86/intel_pmc_core.c (ffffffff8189154b)
Location: drivers/platform/x86/intel_pmc_core.c:389
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_resume
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_suspend
```
**Symbols:**

```
ffffffff81890a20-ffffffff81890a4c: pmc_core_dev_state_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int pmc_core_dev_state_get(void *data, u64 *val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/platform/x86/intel_pmc_core.c (ffffffff81849e1c)
Location: drivers/platform/x86/intel_pmc_core.c:389
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_resume
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_suspend
```
**Symbols:**

```
ffffffff81849d70-ffffffff81849d9c: pmc_core_dev_state_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int pmc_core_dev_state_get(void *data, u64 *val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/platform/x86/intel_pmc_core.c (ffffffff818e504b)
Location: drivers/platform/x86/intel_pmc_core.c:389
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_resume
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_suspend
```
**Symbols:**

```
ffffffff818e4510-ffffffff818e453c: pmc_core_dev_state_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int pmc_core_dev_state_get(void *data, u64 *val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/platform/x86/intel_pmc_core.c (ffffffff81901cab)
Location: drivers/platform/x86/intel_pmc_core.c:389
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_resume
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_suspend
```
**Symbols:**

```
ffffffff81901170-ffffffff8190119c: pmc_core_dev_state_get (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
