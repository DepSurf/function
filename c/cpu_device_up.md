# Function: <code>cpu_device_up</code>

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
int cpu_device_up(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810ab160)
Location: kernel/cpu.c:1291
Inline: False
Direct callers:
  - drivers/base/cpu.c:cpu_subsys_online
```
**Symbols:**

```
ffffffff810ab160-ffffffff810ab17b: cpu_device_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cpu_device_up(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a69f0)
Location: kernel/cpu.c:1295
Inline: False
Direct callers:
  - drivers/base/cpu.c:cpu_subsys_online
```
**Symbols:**

```
ffffffff810a69f0-ffffffff810a6a0b: cpu_device_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cpu_device_up(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a7aa0)
Location: kernel/cpu.c:1399
Inline: False
Direct callers:
  - drivers/base/cpu.c:cpu_subsys_online
```
**Symbols:**

```
ffffffff810a7aa0-ffffffff810a7abb: cpu_device_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int cpu_device_up(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810b9500)
Location: kernel/cpu.c:1427
Inline: False
Direct callers:
  - drivers/base/cpu.c:cpu_subsys_online
```
**Symbols:**

```
ffffffff810b9500-ffffffff810b951b: cpu_device_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int cpu_device_up(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810cff20)
Location: kernel/cpu.c:1439
Inline: False
Direct callers:
  - drivers/base/cpu.c:cpu_subsys_online
```
**Symbols:**

```
ffffffff810cff20-ffffffff810cff43: cpu_device_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cpu_device_up(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810ee360)
Location: kernel/cpu.c:1463
Inline: False
Direct callers:
  - drivers/base/cpu.c:cpu_subsys_online
```
**Symbols:**

```
ffffffff810ee360-ffffffff810ee383: cpu_device_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cpu_device_up(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810fa3c0)
Location: kernel/cpu.c:1745
Inline: False
Direct callers:
  - drivers/base/cpu.c:cpu_subsys_online
```
**Symbols:**

```
ffffffff810fa3c0-ffffffff810fa3e3: cpu_device_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cpu_device_up(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff811037e0)
Location: kernel/cpu.c:1780
Inline: False
Direct callers:
  - drivers/base/cpu.c:cpu_subsys_online
  - drivers/base/cpu.c:cpu_subsys_online
```
**Symbols:**

```
ffffffff811037e0-ffffffff81103803: cpu_device_up (STB_GLOBAL)
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
