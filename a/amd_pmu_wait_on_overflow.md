# Function: <code>amd_pmu_wait_on_overflow</code>

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
void amd_pmu_wait_on_overflow(int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81008be0)
Location: arch/x86/events/amd/core.c:567
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
  - arch/x86/events/amd/core.c:amd_pmu_disable_all
```
**Symbols:**

```
ffffffff81008be0-ffffffff81008c48: amd_pmu_wait_on_overflow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void amd_pmu_wait_on_overflow(int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81008f00)
Location: arch/x86/events/amd/core.c:588
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
  - arch/x86/events/amd/core.c:amd_pmu_disable_all
```
**Symbols:**

```
ffffffff81008f00-ffffffff81008f68: amd_pmu_wait_on_overflow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void amd_pmu_wait_on_overflow(int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff8100a040)
Location: arch/x86/events/amd/core.c:588
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
  - arch/x86/events/amd/core.c:amd_pmu_disable_all
```
**Symbols:**

```
ffffffff8100a040-ffffffff8100a0a8: amd_pmu_wait_on_overflow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void amd_pmu_wait_on_overflow(int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81008ec0)
Location: arch/x86/events/amd/core.c:588
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
  - arch/x86/events/amd/core.c:amd_pmu_disable_all
```
**Symbols:**

```
ffffffff81008ec0-ffffffff81008f28: amd_pmu_wait_on_overflow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void amd_pmu_wait_on_overflow(int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81009860)
Location: arch/x86/events/amd/core.c:588
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
  - arch/x86/events/amd/core.c:amd_pmu_disable_all
```
**Symbols:**

```
ffffffff81009860-ffffffff810098c8: amd_pmu_wait_on_overflow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void amd_pmu_wait_on_overflow(int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/core.c (0)
Location: arch/x86/events/amd/core.c:588
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
  - arch/x86/events/amd/core.c:amd_pmu_disable_all
```
**Symbols:**

```
ffffffff8100a830-ffffffff8100a8ab: amd_pmu_wait_on_overflow (STB_LOCAL)
ffffffff81c95480-ffffffff81c954a1: amd_pmu_wait_on_overflow.cold (STB_LOCAL)
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
In arch/x86/events/amd/core.c (ffffffff8100a7b0)
Location: arch/x86/events/amd/core.c:721
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_check_overflow
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
In arch/x86/events/amd/core.c (ffffffff8100c470)
Location: arch/x86/events/amd/core.c:671
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_check_overflow
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
In arch/x86/events/amd/core.c (ffffffff8100bc2e)
Location: arch/x86/events/amd/core.c:671
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_check_overflow
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
In arch/x86/events/amd/core.c (ffffffff8101140e)
Location: arch/x86/events/amd/core.c:673
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_check_overflow
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
void amd_pmu_wait_on_overflow(int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81008f00)
Location: arch/x86/events/amd/core.c:588
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
  - arch/x86/events/amd/core.c:amd_pmu_disable_all
```
**Symbols:**

```
ffffffff81008f00-ffffffff81008f68: amd_pmu_wait_on_overflow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void amd_pmu_wait_on_overflow(int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81007710)
Location: arch/x86/events/amd/core.c:588
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
  - arch/x86/events/amd/core.c:amd_pmu_disable_all
```
**Symbols:**

```
ffffffff81007710-ffffffff81007790: amd_pmu_wait_on_overflow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void amd_pmu_wait_on_overflow(int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81008ec0)
Location: arch/x86/events/amd/core.c:588
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
  - arch/x86/events/amd/core.c:amd_pmu_disable_all
```
**Symbols:**

```
ffffffff81008ec0-ffffffff81008f28: amd_pmu_wait_on_overflow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void amd_pmu_wait_on_overflow(int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81009020)
Location: arch/x86/events/amd/core.c:588
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
  - arch/x86/events/amd/core.c:amd_pmu_disable_all
```
**Symbols:**

```
ffffffff81009020-ffffffff81009088: amd_pmu_wait_on_overflow (STB_LOCAL)
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
