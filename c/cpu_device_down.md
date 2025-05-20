# Function: <code>cpu_device_down</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
int cpu_device_down(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810aaf70)
Location: kernel/cpu.c:1078
Inline: False
Direct callers:
  - drivers/base/cpu.c:cpu_subsys_offline
```
**Symbols:**

```
ffffffff810aaf70-ffffffff810aafc4: cpu_device_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cpu_device_down(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a6800)
Location: kernel/cpu.c:1082
Inline: False
Direct callers:
  - drivers/base/cpu.c:cpu_subsys_offline
```
**Symbols:**

```
ffffffff810a6800-ffffffff810a6854: cpu_device_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cpu_device_down(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a7870)
Location: kernel/cpu.c:1187
Inline: False
Direct callers:
  - drivers/base/cpu.c:cpu_subsys_offline
```
**Symbols:**

```
ffffffff810a7870-ffffffff810a78c4: cpu_device_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int cpu_device_down(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810b92c0)
Location: kernel/cpu.c:1213
Inline: False
Direct callers:
  - drivers/base/cpu.c:cpu_subsys_offline
```
**Symbols:**

```
ffffffff810b92c0-ffffffff810b9314: cpu_device_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int cpu_device_down(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810cfc80)
Location: kernel/cpu.c:1225
Inline: False
Direct callers:
  - drivers/base/cpu.c:cpu_subsys_offline
```
**Symbols:**

```
ffffffff810cfc80-ffffffff810cfced: cpu_device_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cpu_device_down(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810ee0b0)
Location: kernel/cpu.c:1251
Inline: False
Direct callers:
  - drivers/base/cpu.c:cpu_subsys_offline
```
**Symbols:**

```
ffffffff810ee0b0-ffffffff810ee11d: cpu_device_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cpu_device_down(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810fa140)
Location: kernel/cpu.c:1525
Inline: False
Direct callers:
  - drivers/base/cpu.c:cpu_subsys_offline
```
**Symbols:**

```
ffffffff810fa140-ffffffff810fa183: cpu_device_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cpu_device_down(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81103560)
Location: kernel/cpu.c:1563
Inline: False
Direct callers:
  - drivers/base/cpu.c:cpu_subsys_offline
```
**Symbols:**

```
ffffffff81103560-ffffffff811035a3: cpu_device_down (STB_GLOBAL)
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
