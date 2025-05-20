# Function: <code>i845_tseg_size</code>

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
In arch/x86/kernel/early-quirks.c (ffffffff81f6f0dc)
Location: arch/x86/kernel/early-quirks.c:261
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:i845_stolen_base
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
In arch/x86/kernel/early-quirks.c (ffffffff81f9754e)
Location: arch/x86/kernel/early-quirks.c:258
Inline: True
Inline callers:
  - arch/x86/kernel/early-quirks.c:i845_stolen_base
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
size_t i845_tseg_size();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/early-quirks.c (ffffffff81fd2a15)
Location: arch/x86/kernel/early-quirks.c:258
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:i865_stolen_base
  - arch/x86/kernel/early-quirks.c:i845_stolen_base
```
**Symbols:**

```
ffffffff81fd2a15-ffffffff81fd2a68: i845_tseg_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
size_t i845_tseg_size();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/early-quirks.c (ffffffff820b3595)
Location: arch/x86/kernel/early-quirks.c:258
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:i865_stolen_base
  - arch/x86/kernel/early-quirks.c:i845_stolen_base
```
**Symbols:**

```
ffffffff820b3595-ffffffff820b35e5: i845_tseg_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
size_t i845_tseg_size();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/early-quirks.c (ffffffff826b9ea9)
Location: arch/x86/kernel/early-quirks.c:259
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:i865_stolen_base
  - arch/x86/kernel/early-quirks.c:i845_stolen_base
```
**Symbols:**

```
ffffffff826b9ea9-ffffffff826b9ef9: i845_tseg_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
resource_size_t i845_tseg_size();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/early-quirks.c (ffffffff826e3e83)
Location: arch/x86/kernel/early-quirks.c:257
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:i865_stolen_base
  - arch/x86/kernel/early-quirks.c:i845_stolen_base
```
**Symbols:**

```
ffffffff826e3e83-ffffffff826e3ed2: i845_tseg_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
resource_size_t i845_tseg_size();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/early-quirks.c (ffffffff8289a925)
Location: arch/x86/kernel/early-quirks.c:288
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:i865_stolen_base
  - arch/x86/kernel/early-quirks.c:i845_stolen_base
```
**Symbols:**

```
ffffffff8289a925-ffffffff8289a974: i845_tseg_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
resource_size_t i845_tseg_size();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/early-quirks.c (ffffffff828b2675)
Location: arch/x86/kernel/early-quirks.c:288
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:i865_stolen_base
  - arch/x86/kernel/early-quirks.c:i845_stolen_base
```
**Symbols:**

```
ffffffff828b2675-ffffffff828b26c9: i845_tseg_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
resource_size_t i845_tseg_size();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/early-quirks.c (ffffffff828b5ac7)
Location: arch/x86/kernel/early-quirks.c:288
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:i865_stolen_base
  - arch/x86/kernel/early-quirks.c:i845_stolen_base
```
**Symbols:**

```
ffffffff828b5ac7-ffffffff828b5b1b: i845_tseg_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
resource_size_t i845_tseg_size();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/early-quirks.c (ffffffff82cdacbb)
Location: arch/x86/kernel/early-quirks.c:288
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:i865_stolen_base
  - arch/x86/kernel/early-quirks.c:i845_stolen_base
```
**Symbols:**

```
ffffffff82cdacbb-ffffffff82cdad0f: i845_tseg_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
resource_size_t i845_tseg_size();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/early-quirks.c (ffffffff82fc710f)
Location: arch/x86/kernel/early-quirks.c:288
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:i865_stolen_base
  - arch/x86/kernel/early-quirks.c:i845_stolen_base
```
**Symbols:**

```
ffffffff82fc710f-ffffffff82fc7163: i845_tseg_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
resource_size_t i845_tseg_size();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/early-quirks.c (ffffffff831d19c4)
Location: arch/x86/kernel/early-quirks.c:288
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:i865_stolen_base
  - arch/x86/kernel/early-quirks.c:i845_stolen_base
```
**Symbols:**

```
ffffffff831d19c4-ffffffff831d1a18: i845_tseg_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
resource_size_t i845_tseg_size();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/early-quirks.c (ffffffff832b3ddd)
Location: arch/x86/kernel/early-quirks.c:288
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:i865_stolen_base
  - arch/x86/kernel/early-quirks.c:i845_stolen_base
```
**Symbols:**

```
ffffffff832b3ddd-ffffffff832b3e31: i845_tseg_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
resource_size_t i845_tseg_size();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/early-quirks.c (ffffffff83465587)
Location: arch/x86/kernel/early-quirks.c:289
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:i865_stolen_base
  - arch/x86/kernel/early-quirks.c:i845_stolen_base
```
**Symbols:**

```
ffffffff83465587-ffffffff834655e1: i845_tseg_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
resource_size_t i845_tseg_size();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/early-quirks.c (ffffffff83e88a50)
Location: arch/x86/kernel/early-quirks.c:289
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:i865_stolen_base
  - arch/x86/kernel/early-quirks.c:i845_stolen_base
```
**Symbols:**

```
ffffffff83e88a50-ffffffff83e88aaa: i845_tseg_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
resource_size_t i845_tseg_size();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/early-quirks.c (ffffffff836abf70)
Location: arch/x86/kernel/early-quirks.c:289
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:i865_stolen_base
  - arch/x86/kernel/early-quirks.c:i845_stolen_base
```
**Symbols:**

```
ffffffff836abf70-ffffffff836abfca: i845_tseg_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
resource_size_t i845_tseg_size();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/early-quirks.c (ffffffff838dc700)
Location: arch/x86/kernel/early-quirks.c:289
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:i865_stolen_base
  - arch/x86/kernel/early-quirks.c:i845_stolen_base
```
**Symbols:**

```
ffffffff838dc700-ffffffff838dc75a: i845_tseg_size (STB_LOCAL)
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
resource_size_t i845_tseg_size();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/early-quirks.c (ffffffff828a3ad3)
Location: arch/x86/kernel/early-quirks.c:288
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:i865_stolen_base
  - arch/x86/kernel/early-quirks.c:i845_stolen_base
```
**Symbols:**

```
ffffffff828a3ad3-ffffffff828a3b27: i845_tseg_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
resource_size_t i845_tseg_size();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/early-quirks.c (ffffffff8289bc15)
Location: arch/x86/kernel/early-quirks.c:288
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:i865_stolen_base
  - arch/x86/kernel/early-quirks.c:i845_stolen_base
```
**Symbols:**

```
ffffffff8289bc15-ffffffff8289bc69: i845_tseg_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
resource_size_t i845_tseg_size();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/early-quirks.c (ffffffff828b69e3)
Location: arch/x86/kernel/early-quirks.c:288
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:i865_stolen_base
  - arch/x86/kernel/early-quirks.c:i845_stolen_base
```
**Symbols:**

```
ffffffff828b69e3-ffffffff828b6a37: i845_tseg_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
resource_size_t i845_tseg_size();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/early-quirks.c (ffffffff828b6aca)
Location: arch/x86/kernel/early-quirks.c:288
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:i865_stolen_base
  - arch/x86/kernel/early-quirks.c:i845_stolen_base
```
**Symbols:**

```
ffffffff828b6aca-ffffffff828b6b1e: i845_tseg_size (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>size_t</code> ➡️ <code>resource_size_t</code>
</li>
</ul>
</details>
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
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
