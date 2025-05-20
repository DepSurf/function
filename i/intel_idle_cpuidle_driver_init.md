# Function: <code>intel_idle_cpuidle_driver_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/idle/intel_idle.c (ffffffff81fa0414)
Location: drivers/idle/intel_idle.c:1114
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/idle/intel_idle.c (ffffffff81fcbc13)
Location: drivers/idle/intel_idle.c:1312
Inline: True
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
In drivers/idle/intel_idle.c (ffffffff82008c4e)
Location: drivers/idle/intel_idle.c:1324
Inline: True
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
In drivers/idle/intel_idle.c (ffffffff820e9f47)
Location: drivers/idle/intel_idle.c:1327
Inline: True
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
In drivers/idle/intel_idle.c (ffffffff826f2dea)
Location: drivers/idle/intel_idle.c:1338
Inline: True
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
In drivers/idle/intel_idle.c (ffffffff8271cd64)
Location: drivers/idle/intel_idle.c:1338
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_init
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
In drivers/idle/intel_idle.c (ffffffff828d4d7a)
Location: drivers/idle/intel_idle.c:1335
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void intel_idle_cpuidle_driver_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/idle/intel_idle.c (ffffffff828eec7e)
Location: drivers/idle/intel_idle.c:1324
Inline: False
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_init
```
**Symbols:**

```
ffffffff828eec7e-ffffffff828eefc4: intel_idle_cpuidle_driver_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void intel_idle_cpuidle_driver_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/idle/intel_idle.c (ffffffff828f7e12)
Location: drivers/idle/intel_idle.c:1324
Inline: False
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_init
```
**Symbols:**

```
ffffffff828f7e12-ffffffff828f8158: intel_idle_cpuidle_driver_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/idle/intel_idle.c (ffffffff82d0f341)
Location: drivers/idle/intel_idle.c:1500
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/idle/intel_idle.c (ffffffff82ffcdd2)
Location: drivers/idle/intel_idle.c:1565
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/idle/intel_idle.c (ffffffff83207bfc)
Location: drivers/idle/intel_idle.c:1566
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/idle/intel_idle.c (ffffffff832efca2)
Location: drivers/idle/intel_idle.c:1599
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/idle/intel_idle.c (ffffffff834a7df6)
Location: drivers/idle/intel_idle.c:1860
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/idle/intel_idle.c (ffffffff83edef93)
Location: drivers/idle/intel_idle.c:1926
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/idle/intel_idle.c (ffffffff83704a11)
Location: drivers/idle/intel_idle.c:1957
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/idle/intel_idle.c (ffffffff83937f21)
Location: drivers/idle/intel_idle.c:2068
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_init
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
void intel_idle_cpuidle_driver_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/idle/intel_idle.c (ffffffff828e0b7e)
Location: drivers/idle/intel_idle.c:1324
Inline: False
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_init
```
**Symbols:**

```
ffffffff828e0b7e-ffffffff828e0ec4: intel_idle_cpuidle_driver_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void intel_idle_cpuidle_driver_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/idle/intel_idle.c (ffffffff828d90a6)
Location: drivers/idle/intel_idle.c:1324
Inline: False
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_init
```
**Symbols:**

```
ffffffff828d90a6-ffffffff828d9384: intel_idle_cpuidle_driver_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void intel_idle_cpuidle_driver_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/idle/intel_idle.c (ffffffff828f3a0e)
Location: drivers/idle/intel_idle.c:1324
Inline: False
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_init
```
**Symbols:**

```
ffffffff828f3a0e-ffffffff828f3d54: intel_idle_cpuidle_driver_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void intel_idle_cpuidle_driver_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/idle/intel_idle.c (ffffffff828f8e66)
Location: drivers/idle/intel_idle.c:1324
Inline: False
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_init
```
**Symbols:**

```
ffffffff828f8e66-ffffffff828f91ac: intel_idle_cpuidle_driver_init (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
