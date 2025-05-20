# Function: <code>timeval_to_jiffies</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int timeval_to_jiffies(const struct timeval *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810eade0)
Location: kernel/time/time.c:605
Inline: False
Direct callers:
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:set_cpu_itimer
```
**Symbols:**

```
ffffffff810eade0-ffffffff810eae3d: timeval_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int timeval_to_jiffies(const struct timeval *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810f1a80)
Location: kernel/time/time.c:612
Inline: False
Direct callers:
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:set_cpu_itimer
```
**Symbols:**

```
ffffffff810f1a80-ffffffff810f1ade: timeval_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int timeval_to_jiffies(const struct timeval *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810f8c00)
Location: kernel/time/time.c:612
Inline: False
Direct callers:
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:set_cpu_itimer
```
**Symbols:**

```
ffffffff810f8c00-ffffffff810f8c5e: timeval_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int timeval_to_jiffies(const struct timeval *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810fac20)
Location: kernel/time/time.c:702
Inline: False
```
**Symbols:**

```
ffffffff810fac20-ffffffff810fac7e: timeval_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int timeval_to_jiffies(const struct timeval *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811055b0)
Location: kernel/time/time.c:669
Inline: False
```
**Symbols:**

```
ffffffff811055b0-ffffffff8110560e: timeval_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int timeval_to_jiffies(const struct timeval *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81110410)
Location: kernel/time/time.c:681
Inline: False
```
**Symbols:**

```
ffffffff81110410-ffffffff8111046c: timeval_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int timeval_to_jiffies(const struct timeval *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8111ba00)
Location: kernel/time/time.c:619
Inline: False
```
**Symbols:**

```
ffffffff8111ba00-ffffffff8111ba5c: timeval_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int timeval_to_jiffies(const struct timeval *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81126420)
Location: kernel/time/time.c:687
Inline: False
```
**Symbols:**

```
ffffffff81126420-ffffffff81126473: timeval_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int timeval_to_jiffies(const struct timeval *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811323c0)
Location: kernel/time/time.c:687
Inline: False
```
**Symbols:**

```
ffffffff811323c0-ffffffff81132413: timeval_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
long unsigned int timeval_to_jiffies(const struct timeval *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffff800010199e60)
Location: kernel/time/time.c:687
Inline: False
```
**Symbols:**

```
ffff800010199e60-ffff800010199ee8: timeval_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int timeval_to_jiffies(const struct timeval *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (c03e4858)
Location: kernel/time/time.c:687
Inline: False
```
**Symbols:**

```
c03e4858-c03e48e0: timeval_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int timeval_to_jiffies(const struct timeval *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (c0000000001fa100)
Location: kernel/time/time.c:687
Inline: False
```
**Symbols:**

```
c0000000001fa100-c0000000001fa174: timeval_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int timeval_to_jiffies(const struct timeval *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffe00012a330)
Location: kernel/time/time.c:687
Inline: False
```
**Symbols:**

```
ffffffe00012a330-ffffffe00012a3a6: timeval_to_jiffies (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
long unsigned int timeval_to_jiffies(const struct timeval *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8112ab70)
Location: kernel/time/time.c:687
Inline: False
```
**Symbols:**

```
ffffffff8112ab70-ffffffff8112abc3: timeval_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int timeval_to_jiffies(const struct timeval *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8111d3e0)
Location: kernel/time/time.c:687
Inline: False
```
**Symbols:**

```
ffffffff8111d3e0-ffffffff8111d433: timeval_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int timeval_to_jiffies(const struct timeval *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81128890)
Location: kernel/time/time.c:687
Inline: False
```
**Symbols:**

```
ffffffff81128890-ffffffff811288e3: timeval_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int timeval_to_jiffies(const struct timeval *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81134f10)
Location: kernel/time/time.c:687
Inline: False
```
**Symbols:**

```
ffffffff81134f10-ffffffff81134f63: timeval_to_jiffies (STB_GLOBAL)
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
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
