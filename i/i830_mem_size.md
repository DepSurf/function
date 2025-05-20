# Function: <code>i830_mem_size</code>

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
In arch/x86/kernel/early-quirks.c (ffffffff81f6f0c3)
Location: arch/x86/kernel/early-quirks.c:289
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:i845_stolen_base
  - arch/x86/kernel/early-quirks.c:i830_stolen_base
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
In arch/x86/kernel/early-quirks.c (ffffffff81f97535)
Location: arch/x86/kernel/early-quirks.c:285
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:i845_stolen_base
  - arch/x86/kernel/early-quirks.c:i830_stolen_base
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
In arch/x86/kernel/early-quirks.c (ffffffff81fd2a91)
Location: arch/x86/kernel/early-quirks.c:285
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:i845_stolen_base
  - arch/x86/kernel/early-quirks.c:i830_stolen_base
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
In arch/x86/kernel/early-quirks.c (ffffffff820b3618)
Location: arch/x86/kernel/early-quirks.c:285
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:i845_stolen_base
  - arch/x86/kernel/early-quirks.c:i830_stolen_base
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
In arch/x86/kernel/early-quirks.c (ffffffff826b9f2c)
Location: arch/x86/kernel/early-quirks.c:286
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:i845_stolen_base
  - arch/x86/kernel/early-quirks.c:i830_stolen_base
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
In arch/x86/kernel/early-quirks.c (ffffffff826e3f03)
Location: arch/x86/kernel/early-quirks.c:284
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:i845_stolen_base
  - arch/x86/kernel/early-quirks.c:i830_stolen_base
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
In arch/x86/kernel/early-quirks.c (ffffffff8289a9a5)
Location: arch/x86/kernel/early-quirks.c:315
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:i845_stolen_base
  - arch/x86/kernel/early-quirks.c:i830_stolen_base
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
In arch/x86/kernel/early-quirks.c (ffffffff828b26fa)
Location: arch/x86/kernel/early-quirks.c:315
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:i845_stolen_base
  - arch/x86/kernel/early-quirks.c:i830_stolen_base
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
In arch/x86/kernel/early-quirks.c (ffffffff828b5b4c)
Location: arch/x86/kernel/early-quirks.c:315
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:i845_stolen_base
  - arch/x86/kernel/early-quirks.c:i830_stolen_base
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
resource_size_t i830_mem_size();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/early-quirks.c (ffffffff82cda70a)
Location: arch/x86/kernel/early-quirks.c:315
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:i845_stolen_base
  - arch/x86/kernel/early-quirks.c:i830_stolen_base
```
**Symbols:**

```
ffffffff82cda70a-ffffffff82cda72c: i830_mem_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
resource_size_t i830_mem_size();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/early-quirks.c (ffffffff82fc6b5e)
Location: arch/x86/kernel/early-quirks.c:315
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:i845_stolen_base
  - arch/x86/kernel/early-quirks.c:i830_stolen_base
```
**Symbols:**

```
ffffffff82fc6b5e-ffffffff82fc6b80: i830_mem_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
resource_size_t i830_mem_size();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/early-quirks.c (ffffffff831d1413)
Location: arch/x86/kernel/early-quirks.c:315
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:i845_stolen_base
  - arch/x86/kernel/early-quirks.c:i830_stolen_base
```
**Symbols:**

```
ffffffff831d1413-ffffffff831d1435: i830_mem_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
resource_size_t i830_mem_size();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/early-quirks.c (ffffffff832b3af6)
Location: arch/x86/kernel/early-quirks.c:315
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:i845_stolen_base
  - arch/x86/kernel/early-quirks.c:i830_stolen_base
```
**Symbols:**

```
ffffffff832b3af6-ffffffff832b3b18: i830_mem_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
resource_size_t i830_mem_size();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/early-quirks.c (ffffffff83465240)
Location: arch/x86/kernel/early-quirks.c:316
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:i845_stolen_base
  - arch/x86/kernel/early-quirks.c:i830_stolen_base
```
**Symbols:**

```
ffffffff83465240-ffffffff8346526e: i830_mem_size (STB_LOCAL)
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
In arch/x86/kernel/early-quirks.c (ffffffff83e88b15)
Location: arch/x86/kernel/early-quirks.c:316
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:i845_stolen_base
  - arch/x86/kernel/early-quirks.c:i830_stolen_base
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
In arch/x86/kernel/early-quirks.c (ffffffff836ac035)
Location: arch/x86/kernel/early-quirks.c:316
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:i845_stolen_base
  - arch/x86/kernel/early-quirks.c:i830_stolen_base
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
In arch/x86/kernel/early-quirks.c (ffffffff838dc7c5)
Location: arch/x86/kernel/early-quirks.c:316
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:i845_stolen_base
  - arch/x86/kernel/early-quirks.c:i830_stolen_base
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
In arch/x86/kernel/early-quirks.c (ffffffff828a3b58)
Location: arch/x86/kernel/early-quirks.c:315
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:i845_stolen_base
  - arch/x86/kernel/early-quirks.c:i830_stolen_base
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
In arch/x86/kernel/early-quirks.c (ffffffff8289bc9a)
Location: arch/x86/kernel/early-quirks.c:315
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:i845_stolen_base
  - arch/x86/kernel/early-quirks.c:i830_stolen_base
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
In arch/x86/kernel/early-quirks.c (ffffffff828b6a68)
Location: arch/x86/kernel/early-quirks.c:315
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:i845_stolen_base
  - arch/x86/kernel/early-quirks.c:i830_stolen_base
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
In arch/x86/kernel/early-quirks.c (ffffffff828b6b4f)
Location: arch/x86/kernel/early-quirks.c:315
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:i845_stolen_base
  - arch/x86/kernel/early-quirks.c:i830_stolen_base
```
</details>
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
</ul>
