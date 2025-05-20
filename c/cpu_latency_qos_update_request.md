# Function: <code>cpu_latency_qos_update_request</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cpu_latency_qos_update_request(struct pm_qos_request *req, s32 new_value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/power/qos.c (ffffffff811116eb)
Location: kernel/power/qos.c:290
Inline: True
Inline callers:
  - kernel/power/qos.c:cpu_latency_qos_write
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_reset_semaphore
  - kernel/power/qos.c:cpu_latency_qos_write
```
**Symbols:**

```
ffffffff811115d0-ffffffff81111656: cpu_latency_qos_update_request.part.0 (STB_LOCAL)
ffffffff81111660-ffffffff81111697: cpu_latency_qos_update_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void cpu_latency_qos_update_request(struct pm_qos_request *req, s32 new_value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8110e740)
Location: kernel/power/qos.c:290
Inline: True
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_reset_semaphore
  - kernel/power/qos.c:cpu_latency_qos_write
```
**Symbols:**

```
ffffffff8110e740-ffffffff8110e7df: cpu_latency_qos_update_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void cpu_latency_qos_update_request(struct pm_qos_request *req, s32 new_value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8110f220)
Location: kernel/power/qos.c:290
Inline: True
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_reset_semaphore
  - kernel/power/qos.c:cpu_latency_qos_write
```
**Symbols:**

```
ffffffff8110f220-ffffffff8110f2bf: cpu_latency_qos_update_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void cpu_latency_qos_update_request(struct pm_qos_request *req, s32 new_value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8112eb70)
Location: kernel/power/qos.c:290
Inline: True
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_reset_semaphore
  - kernel/power/qos.c:cpu_latency_qos_write
```
**Symbols:**

```
ffffffff8112eb70-ffffffff8112ec0c: cpu_latency_qos_update_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void cpu_latency_qos_update_request(struct pm_qos_request *req, s32 new_value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8114fff0)
Location: kernel/power/qos.c:290
Inline: True
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_reset_semaphore
  - kernel/power/qos.c:cpu_latency_qos_write
```
**Symbols:**

```
ffffffff8114fff0-ffffffff811500c7: cpu_latency_qos_update_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void cpu_latency_qos_update_request(struct pm_qos_request *req, s32 new_value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8117e8d0)
Location: kernel/power/qos.c:290
Inline: True
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_reset_semaphore
  - kernel/power/qos.c:cpu_latency_qos_write
```
**Symbols:**

```
ffffffff8117e8d0-ffffffff8117e9a7: cpu_latency_qos_update_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void cpu_latency_qos_update_request(struct pm_qos_request *req, s32 new_value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8118f520)
Location: kernel/power/qos.c:290
Inline: True
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_reset_semaphore
  - kernel/power/qos.c:cpu_latency_qos_write
```
**Symbols:**

```
ffffffff8118f520-ffffffff8118f5f7: cpu_latency_qos_update_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void cpu_latency_qos_update_request(struct pm_qos_request *req, s32 new_value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8119ded0)
Location: kernel/power/qos.c:295
Inline: True
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_reset_semaphore
  - kernel/power/qos.c:cpu_latency_qos_write
```
**Symbols:**

```
ffffffff8119ded0-ffffffff8119df96: cpu_latency_qos_update_request (STB_GLOBAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
