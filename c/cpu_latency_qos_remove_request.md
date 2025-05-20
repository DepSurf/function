# Function: <code>cpu_latency_qos_remove_request</code>

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
void cpu_latency_qos_remove_request(struct pm_qos_request *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/power/qos.c (ffffffff8111186d)
Location: kernel/power/qos.c:316
Inline: True
Inline callers:
  - kernel/power/qos.c:cpu_latency_qos_release
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - kernel/power/qos.c:cpu_latency_qos_release
```
**Symbols:**

```
ffffffff81111760-ffffffff81111801: cpu_latency_qos_remove_request.part.0 (STB_LOCAL)
ffffffff81111810-ffffffff81111847: cpu_latency_qos_remove_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cpu_latency_qos_remove_request(struct pm_qos_request *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/power/qos.c (ffffffff8110e96d)
Location: kernel/power/qos.c:316
Inline: True
Inline callers:
  - kernel/power/qos.c:cpu_latency_qos_release
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - kernel/power/qos.c:cpu_latency_qos_release
```
**Symbols:**

```
ffffffff8110e880-ffffffff8110e90b: cpu_latency_qos_remove_request.part.0 (STB_LOCAL)
ffffffff8110e910-ffffffff8110e947: cpu_latency_qos_remove_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void cpu_latency_qos_remove_request(struct pm_qos_request *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8110f450)
Location: kernel/power/qos.c:316
Inline: True
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - kernel/power/qos.c:cpu_latency_qos_release
```
**Symbols:**

```
ffffffff8110f450-ffffffff8110f50d: cpu_latency_qos_remove_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void cpu_latency_qos_remove_request(struct pm_qos_request *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8112eda0)
Location: kernel/power/qos.c:316
Inline: True
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - kernel/power/qos.c:cpu_latency_qos_release
```
**Symbols:**

```
ffffffff8112eda0-ffffffff8112ee5a: cpu_latency_qos_remove_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void cpu_latency_qos_remove_request(struct pm_qos_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff811502c0)
Location: kernel/power/qos.c:316
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - kernel/power/qos.c:cpu_latency_qos_release
```
**Symbols:**

```
ffffffff811502c0-ffffffff811503be: cpu_latency_qos_remove_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void cpu_latency_qos_remove_request(struct pm_qos_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8117ec00)
Location: kernel/power/qos.c:316
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - kernel/power/qos.c:cpu_latency_qos_release
```
**Symbols:**

```
ffffffff8117ec00-ffffffff8117ecfe: cpu_latency_qos_remove_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void cpu_latency_qos_remove_request(struct pm_qos_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8118f850)
Location: kernel/power/qos.c:316
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - kernel/power/qos.c:cpu_latency_qos_release
```
**Symbols:**

```
ffffffff8118f850-ffffffff8118f94e: cpu_latency_qos_remove_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void cpu_latency_qos_remove_request(struct pm_qos_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8119e210)
Location: kernel/power/qos.c:321
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - kernel/power/qos.c:cpu_latency_qos_release
```
**Symbols:**

```
ffffffff8119e210-ffffffff8119e30e: cpu_latency_qos_remove_request (STB_GLOBAL)
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
