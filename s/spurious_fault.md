# Function: <code>spurious_fault</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int spurious_fault(long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8106a200)
Location: arch/x86/mm/fault.c:952
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
```
**Symbols:**

```
ffffffff8106a200-ffffffff8106a3f5: spurious_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int spurious_fault(long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81069e60)
Location: arch/x86/mm/fault.c:1050
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
```
**Symbols:**

```
ffffffff81069e60-ffffffff8106a060: spurious_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int spurious_fault(long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8106da00)
Location: arch/x86/mm/fault.c:1081
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
```
**Symbols:**

```
ffffffff8106da00-ffffffff8106dc00: spurious_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int spurious_fault(long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8106d730)
Location: arch/x86/mm/fault.c:1122
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
```
**Symbols:**

```
ffffffff8106d730-ffffffff8106d941: spurious_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int spurious_fault(long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81072130)
Location: arch/x86/mm/fault.c:1101
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
```
**Symbols:**

```
ffffffff81072130-ffffffff81072378: spurious_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int spurious_fault(long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff810751a0)
Location: arch/x86/mm/fault.c:1073
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
```
**Symbols:**

```
ffffffff810751a0-ffffffff810753ab: spurious_fault (STB_LOCAL)
```
</details>
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
</ul>
