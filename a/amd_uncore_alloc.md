# Function: <code>amd_uncore_alloc</code>

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
In arch/x86/events/amd/uncore.c (ffffffff81008ace)
Location: arch/x86/events/amd/uncore.c:287
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare
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
In arch/x86/events/amd/uncore.c (ffffffff81008c1f)
Location: arch/x86/events/amd/uncore.c:291
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare
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
In arch/x86/events/amd/uncore.c (ffffffff81008c5f)
Location: arch/x86/events/amd/uncore.c:291
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare
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
In arch/x86/events/amd/uncore.c (ffffffff8100899e)
Location: arch/x86/events/amd/uncore.c:313
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare
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
In arch/x86/events/amd/uncore.c (ffffffff81008bbe)
Location: arch/x86/events/amd/uncore.c:313
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare
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
In arch/x86/events/amd/uncore.c (ffffffff810092de)
Location: arch/x86/events/amd/uncore.c:314
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct amd_uncore *amd_uncore_alloc(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/uncore.c (ffffffff81008fa0)
Location: arch/x86/events/amd/uncore.c:322
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare
```
**Symbols:**

```
ffffffff81008fa0-ffffffff81008fd6: amd_uncore_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct amd_uncore *amd_uncore_alloc(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/uncore.c (ffffffff81009430)
Location: arch/x86/events/amd/uncore.c:323
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare
```
**Symbols:**

```
ffffffff81009430-ffffffff81009466: amd_uncore_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct amd_uncore *amd_uncore_alloc(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/uncore.c (ffffffff81009830)
Location: arch/x86/events/amd/uncore.c:320
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare
```
**Symbols:**

```
ffffffff81009830-ffffffff81009866: amd_uncore_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct amd_uncore *amd_uncore_alloc(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/uncore.c (ffffffff8100aba0)
Location: arch/x86/events/amd/uncore.c:338
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare
```
**Symbols:**

```
ffffffff8100aba0-ffffffff8100abd6: amd_uncore_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct amd_uncore *amd_uncore_alloc(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/uncore.c (ffffffff81009b30)
Location: arch/x86/events/amd/uncore.c:365
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare
```
**Symbols:**

```
ffffffff81009b30-ffffffff81009b66: amd_uncore_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct amd_uncore *amd_uncore_alloc(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/uncore.c (ffffffff8100a510)
Location: arch/x86/events/amd/uncore.c:365
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare
```
**Symbols:**

```
ffffffff8100a510-ffffffff8100a546: amd_uncore_alloc (STB_LOCAL)
```
</details>
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
struct amd_uncore *amd_uncore_alloc(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/uncore.c (ffffffff81009830)
Location: arch/x86/events/amd/uncore.c:320
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare
```
**Symbols:**

```
ffffffff81009830-ffffffff81009866: amd_uncore_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct amd_uncore *amd_uncore_alloc(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/uncore.c (ffffffff81007fd0)
Location: arch/x86/events/amd/uncore.c:320
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare
```
**Symbols:**

```
ffffffff81007fd0-ffffffff81008006: amd_uncore_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct amd_uncore *amd_uncore_alloc(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/uncore.c (ffffffff810097f0)
Location: arch/x86/events/amd/uncore.c:320
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare
```
**Symbols:**

```
ffffffff810097f0-ffffffff81009826: amd_uncore_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct amd_uncore *amd_uncore_alloc(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/uncore.c (ffffffff81009950)
Location: arch/x86/events/amd/uncore.c:320
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare
  - arch/x86/events/amd/uncore.c:amd_uncore_cpu_up_prepare
```
**Symbols:**

```
ffffffff81009950-ffffffff81009986: amd_uncore_alloc (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
