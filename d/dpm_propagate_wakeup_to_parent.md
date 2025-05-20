# Function: <code>dpm_propagate_wakeup_to_parent</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dpm_propagate_wakeup_to_parent(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81691c40)
Location: drivers/base/power/main.c:1447
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
```
**Symbols:**

```
ffffffff81691c40-ffffffff81691c9d: dpm_propagate_wakeup_to_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dpm_propagate_wakeup_to_parent(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816b22a0)
Location: drivers/base/power/main.c:1449
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
```
**Symbols:**

```
ffffffff816b22a0-ffffffff816b22fd: dpm_propagate_wakeup_to_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void dpm_propagate_wakeup_to_parent(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816eb510)
Location: drivers/base/power/main.c:1437
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
```
**Symbols:**

```
ffffffff816eb510-ffffffff816eb56e: dpm_propagate_wakeup_to_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dpm_propagate_wakeup_to_parent(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff8170f5d0)
Location: drivers/base/power/main.c:1458
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
```
**Symbols:**

```
ffffffff8170f5d0-ffffffff8170f62e: dpm_propagate_wakeup_to_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dpm_propagate_wakeup_to_parent(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff817cb3e0)
Location: drivers/base/power/main.c:1354
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
```
**Symbols:**

```
ffffffff817cb3e0-ffffffff817cb441: dpm_propagate_wakeup_to_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dpm_propagate_wakeup_to_parent(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff817dfe70)
Location: drivers/base/power/main.c:1353
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
```
**Symbols:**

```
ffffffff817dfe70-ffffffff817dfed1: dpm_propagate_wakeup_to_parent (STB_LOCAL)
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
In drivers/base/power/main.c (ffffffff817c5049)
Location: drivers/base/power/main.c:1354
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
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
In drivers/base/power/main.c (ffffffff8184f42d)
Location: drivers/base/power/main.c:1368
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
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
In drivers/base/power/main.c (ffffffff819944eb)
Location: drivers/base/power/main.c:1363
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
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
In drivers/base/power/main.c (ffffffff81b04f0b)
Location: drivers/base/power/main.c:1363
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
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
In drivers/base/power/main.c (ffffffff81b5273a)
Location: drivers/base/power/main.c:1363
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
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
In drivers/base/power/main.c (ffffffff81baadea)
Location: drivers/base/power/main.c:1362
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void dpm_propagate_wakeup_to_parent(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffff8000109007b0)
Location: drivers/base/power/main.c:1458
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
```
**Symbols:**

```
ffff8000109007b0-ffff800010900864: dpm_propagate_wakeup_to_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dpm_propagate_wakeup_to_parent(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (c09e9950)
Location: drivers/base/power/main.c:1458
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
```
**Symbols:**

```
c09e9950-c09e99bc: dpm_propagate_wakeup_to_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dpm_propagate_wakeup_to_parent(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (c00000000099d060)
Location: drivers/base/power/main.c:1458
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
```
**Symbols:**

```
c00000000099d060-c00000000099d130: dpm_propagate_wakeup_to_parent (STB_LOCAL)
```
</details>
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
void dpm_propagate_wakeup_to_parent(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816d5310)
Location: drivers/base/power/main.c:1458
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
```
**Symbols:**

```
ffffffff816d5310-ffffffff816d536e: dpm_propagate_wakeup_to_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dpm_propagate_wakeup_to_parent(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816affc0)
Location: drivers/base/power/main.c:1458
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
```
**Symbols:**

```
ffffffff816affc0-ffffffff816b0018: dpm_propagate_wakeup_to_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dpm_propagate_wakeup_to_parent(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81703290)
Location: drivers/base/power/main.c:1458
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
```
**Symbols:**

```
ffffffff81703290-ffffffff817032ee: dpm_propagate_wakeup_to_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dpm_propagate_wakeup_to_parent(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff8171d4d0)
Location: drivers/base/power/main.c:1458
Inline: False
Direct callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
```
**Symbols:**

```
ffffffff8171d4d0-ffffffff8171d528: dpm_propagate_wakeup_to_parent (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
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
