# Function: <code>mce_device_create</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mce_device_create(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81046280)
Location: arch/x86/kernel/cpu/mcheck/mce.c:2304
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_callback
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
```
**Symbols:**

```
ffffffff81046280-ffffffff81046418: mce_device_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int mce_device_create(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff810462a0)
Location: arch/x86/kernel/cpu/mcheck/mce.c:2387
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_callback
```
**Symbols:**

```
ffffffff810462a0-ffffffff8104645a: mce_device_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81047f48)
Location: arch/x86/kernel/cpu/mcheck/mce.c:2450
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81047807)
Location: arch/x86/kernel/cpu/mcheck/mce.c:2161
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104b2c7)
Location: arch/x86/kernel/cpu/mcheck/mce.c:2190
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104dc08)
Location: arch/x86/kernel/cpu/mcheck/mce.c:2183
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104b2f8)
Location: arch/x86/kernel/cpu/mce/core.c:2206
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104e1e8)
Location: arch/x86/kernel/cpu/mce/core.c:2261
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104eb88)
Location: arch/x86/kernel/cpu/mce/core.c:2261
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81052ea0)
Location: arch/x86/kernel/cpu/mce/core.c:2389
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
```
**Symbols:**

```
ffffffff81052ea0-ffffffff8105306f: mce_device_create.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81051ff0)
Location: arch/x86/kernel/cpu/mce/core.c:2465
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
```
**Symbols:**

```
ffffffff81051ff0-ffffffff810521bf: mce_device_create.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff810536b0)
Location: arch/x86/kernel/cpu/mce/core.c:2476
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
```
**Symbols:**

```
ffffffff810536b0-ffffffff8105387f: mce_device_create.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8105bd90)
Location: arch/x86/kernel/cpu/mce/core.c:2539
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
```
**Symbols:**

```
ffffffff8105bd90-ffffffff8105c098: mce_device_create.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81068360)
Location: arch/x86/kernel/cpu/mce/core.c:2551
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
```
**Symbols:**

```
ffffffff81068360-ffffffff81068695: mce_device_create.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81077f10)
Location: arch/x86/kernel/cpu/mce/core.c:2551
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
```
**Symbols:**

```
ffffffff81077f10-ffffffff81078245: mce_device_create.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8107a1c0)
Location: arch/x86/kernel/cpu/mce/core.c:2568
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
```
**Symbols:**

```
ffffffff8107a1c0-ffffffff8107a4f5: mce_device_create.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81080850)
Location: arch/x86/kernel/cpu/mce/core.c:2597
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
```
**Symbols:**

```
ffffffff81080850-ffffffff81080b87: mce_device_create.isra.0 (STB_LOCAL)
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104ece8)
Location: arch/x86/kernel/cpu/mce/core.c:2261
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8103e1b8)
Location: arch/x86/kernel/cpu/mce/core.c:2261
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104eb38)
Location: arch/x86/kernel/cpu/mce/core.c:2261
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104ff78)
Location: arch/x86/kernel/cpu/mce/core.c:2261
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
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
</ul>
