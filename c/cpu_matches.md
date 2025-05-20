# Function: <code>cpu_matches</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool cpu_matches(long unsigned int which);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff828abd2f)
Location: arch/x86/kernel/cpu/common.c:1087
Inline: False
```
**Symbols:**

```
ffffffff828abd2f-ffffffff828abd5c: cpu_matches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool cpu_matches(long unsigned int which);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff828aed3d)
Location: arch/x86/kernel/cpu/common.c:1091
Inline: False
```
**Symbols:**

```
ffffffff828aed3d-ffffffff828aed6a: cpu_matches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool cpu_matches(const struct x86_cpu_id *table, long unsigned int which);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff82cd3bde)
Location: arch/x86/kernel/cpu/common.c:1097
Inline: False
```
**Symbols:**

```
ffffffff82cd3bde-ffffffff82cd3c04: cpu_matches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool cpu_matches(const struct x86_cpu_id *table, long unsigned int which);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff82fbfb66)
Location: arch/x86/kernel/cpu/common.c:1115
Inline: False
```
**Symbols:**

```
ffffffff82fbfb66-ffffffff82fbfb8c: cpu_matches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool cpu_matches(const struct x86_cpu_id *table, long unsigned int which);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff831ca208)
Location: arch/x86/kernel/cpu/common.c:1116
Inline: False
```
**Symbols:**

```
ffffffff831ca208-ffffffff831ca22e: cpu_matches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool cpu_matches(const struct x86_cpu_id *table, long unsigned int which);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff832ab62b)
Location: arch/x86/kernel/cpu/common.c:1119
Inline: False
```
**Symbols:**

```
ffffffff832ab62b-ffffffff832ab651: cpu_matches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool cpu_matches(const struct x86_cpu_id *table, long unsigned int which);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8345b70a)
Location: arch/x86/kernel/cpu/common.c:1274
Inline: False
```
**Symbols:**

```
ffffffff8345b70a-ffffffff8345b73a: cpu_matches (STB_LOCAL)
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
In arch/x86/kernel/cpu/common.c (ffffffff83e7bc69)
Location: arch/x86/kernel/cpu/common.c:1297
Inline: True
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
In arch/x86/kernel/cpu/common.c (ffffffff8369e329)
Location: arch/x86/kernel/cpu/common.c:1296
Inline: True
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
In arch/x86/kernel/cpu/common.c (ffffffff838cdf19)
Location: arch/x86/kernel/cpu/common.c:1321
Inline: True
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
bool cpu_matches(long unsigned int which);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8289cd5c)
Location: arch/x86/kernel/cpu/common.c:1091
Inline: False
```
**Symbols:**

```
ffffffff8289cd5c-ffffffff8289cd89: cpu_matches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool cpu_matches(long unsigned int which);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff82894eef)
Location: arch/x86/kernel/cpu/common.c:1091
Inline: False
```
**Symbols:**

```
ffffffff82894eef-ffffffff82894f1c: cpu_matches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool cpu_matches(long unsigned int which);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff828afd1f)
Location: arch/x86/kernel/cpu/common.c:1091
Inline: False
```
**Symbols:**

```
ffffffff828afd1f-ffffffff828afd4c: cpu_matches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool cpu_matches(long unsigned int which);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff828afd4d)
Location: arch/x86/kernel/cpu/common.c:1091
Inline: False
```
**Symbols:**

```
ffffffff828afd4d-ffffffff828afd7a: cpu_matches (STB_LOCAL)
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
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct x86_cpu_id *table</code>
</li>
<li>
<b>Param reordered. </b>
<code>which</code> ➡️ <code>table, which</code>
</li>
</ul>
</details>
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
