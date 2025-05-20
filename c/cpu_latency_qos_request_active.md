# Function: <code>cpu_latency_qos_request_active</code>

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
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool cpu_latency_qos_request_active(struct pm_qos_request *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff811116f0)
Location: kernel/power/qos.c:238
Inline: True
Inline callers:
  - kernel/power/qos.c:cpu_latency_qos_write
  - kernel/power/qos.c:cpu_latency_qos_read
  - kernel/power/qos.c:cpu_latency_qos_release
```
**Symbols:**

```
ffffffff81111280-ffffffff81111296: cpu_latency_qos_request_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool cpu_latency_qos_request_active(struct pm_qos_request *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8110e55e)
Location: kernel/power/qos.c:238
Inline: True
Inline callers:
  - kernel/power/qos.c:cpu_latency_qos_read
  - kernel/power/qos.c:cpu_latency_qos_release
```
**Symbols:**

```
ffffffff8110e400-ffffffff8110e416: cpu_latency_qos_request_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool cpu_latency_qos_request_active(struct pm_qos_request *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8110f03e)
Location: kernel/power/qos.c:238
Inline: True
Inline callers:
  - kernel/power/qos.c:cpu_latency_qos_read
```
**Symbols:**

```
ffffffff8110ef00-ffffffff8110ef16: cpu_latency_qos_request_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool cpu_latency_qos_request_active(struct pm_qos_request *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8112e892)
Location: kernel/power/qos.c:238
Inline: True
Inline callers:
  - kernel/power/qos.c:cpu_latency_qos_read
```
**Symbols:**

```
ffffffff8112e7a0-ffffffff8112e7b6: cpu_latency_qos_request_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool cpu_latency_qos_request_active(struct pm_qos_request *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8114fcc8)
Location: kernel/power/qos.c:238
Inline: True
Inline callers:
  - kernel/power/qos.c:cpu_latency_qos_read
  - kernel/power/qos.c:cpu_latency_qos_remove_request
```
**Symbols:**

```
ffffffff8114fb70-ffffffff8114fb8c: cpu_latency_qos_request_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool cpu_latency_qos_request_active(struct pm_qos_request *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8117e578)
Location: kernel/power/qos.c:238
Inline: True
Inline callers:
  - kernel/power/qos.c:cpu_latency_qos_read
  - kernel/power/qos.c:cpu_latency_qos_remove_request
```
**Symbols:**

```
ffffffff8117e3f0-ffffffff8117e40c: cpu_latency_qos_request_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool cpu_latency_qos_request_active(struct pm_qos_request *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8118f1d8)
Location: kernel/power/qos.c:238
Inline: True
Inline callers:
  - kernel/power/qos.c:cpu_latency_qos_read
  - kernel/power/qos.c:cpu_latency_qos_remove_request
```
**Symbols:**

```
ffffffff8118f050-ffffffff8118f06c: cpu_latency_qos_request_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool cpu_latency_qos_request_active(struct pm_qos_request *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff8119db88)
Location: kernel/power/qos.c:243
Inline: True
Inline callers:
  - kernel/power/qos.c:cpu_latency_qos_read
  - kernel/power/qos.c:cpu_latency_qos_remove_request
```
**Symbols:**

```
ffffffff8119da00-ffffffff8119da1c: cpu_latency_qos_request_active (STB_GLOBAL)
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
