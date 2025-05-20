# Function: <code>read_ldt</code>

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
In arch/x86/kernel/ldt.c (ffffffff81033068)
Location: arch/x86/kernel/ldt.c:153
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:sys_modify_ldt
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
In arch/x86/kernel/ldt.c (ffffffff8103220e)
Location: arch/x86/kernel/ldt.c:153
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:sys_modify_ldt
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
In arch/x86/kernel/ldt.c (ffffffff81031e8e)
Location: arch/x86/kernel/ldt.c:153
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:sys_modify_ldt
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
In arch/x86/kernel/ldt.c (ffffffff8103009e)
Location: arch/x86/kernel/ldt.c:154
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:sys_modify_ldt
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
In arch/x86/kernel/ldt.c (ffffffff810324b1)
Location: arch/x86/kernel/ldt.c:303
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:SyS_modify_ldt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int read_ldt(void *ptr, long unsigned int bytecount);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81032ea0)
Location: arch/x86/kernel/ldt.c:307
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__x64_sys_modify_ldt
```
**Symbols:**

```
ffffffff81032ea0-ffffffff81032f7d: read_ldt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int read_ldt(void *ptr, long unsigned int bytecount);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81034160)
Location: arch/x86/kernel/ldt.c:410
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__x64_sys_modify_ldt
```
**Symbols:**

```
ffffffff81034160-ffffffff8103423d: read_ldt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int read_ldt(void *ptr, long unsigned int bytecount);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81035ff0)
Location: arch/x86/kernel/ldt.c:410
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__x64_sys_modify_ldt
```
**Symbols:**

```
ffffffff81035ff0-ffffffff810360d3: read_ldt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int read_ldt(void *ptr, long unsigned int bytecount);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81036810)
Location: arch/x86/kernel/ldt.c:410
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__x64_sys_modify_ldt
```
**Symbols:**

```
ffffffff81036810-ffffffff810368f3: read_ldt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int read_ldt(void *ptr, long unsigned int bytecount);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff810386e0)
Location: arch/x86/kernel/ldt.c:494
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__x64_sys_modify_ldt
```
**Symbols:**

```
ffffffff810386e0-ffffffff810387c3: read_ldt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int read_ldt(void *ptr, long unsigned int bytecount);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81039090)
Location: arch/x86/kernel/ldt.c:494
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__x64_sys_modify_ldt
```
**Symbols:**

```
ffffffff81039090-ffffffff81039173: read_ldt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int read_ldt(void *ptr, long unsigned int bytecount);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff8103ab70)
Location: arch/x86/kernel/ldt.c:500
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__x64_sys_modify_ldt
```
**Symbols:**

```
ffffffff8103ab70-ffffffff8103ac4c: read_ldt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int read_ldt(void *ptr, long unsigned int bytecount);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81040590)
Location: arch/x86/kernel/ldt.c:500
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__x64_sys_modify_ldt
```
**Symbols:**

```
ffffffff81040590-ffffffff8104066c: read_ldt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int read_ldt(void *ptr, long unsigned int bytecount);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81047ef0)
Location: arch/x86/kernel/ldt.c:500
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__x64_sys_modify_ldt
```
**Symbols:**

```
ffffffff81047ef0-ffffffff81047fce: read_ldt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int read_ldt(void *ptr, long unsigned int bytecount);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81052be0)
Location: arch/x86/kernel/ldt.c:500
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__x64_sys_modify_ldt
```
**Symbols:**

```
ffffffff81052be0-ffffffff81052ce3: read_ldt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int read_ldt(void *ptr, long unsigned int bytecount);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81053bd0)
Location: arch/x86/kernel/ldt.c:502
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__x64_sys_modify_ldt
```
**Symbols:**

```
ffffffff81053bd0-ffffffff81053cce: read_ldt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int read_ldt(void *ptr, long unsigned int bytecount);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff8105adf0)
Location: arch/x86/kernel/ldt.c:502
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__x64_sys_modify_ldt
```
**Symbols:**

```
ffffffff8105adf0-ffffffff8105aeee: read_ldt (STB_LOCAL)
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
int read_ldt(void *ptr, long unsigned int bytecount);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81036970)
Location: arch/x86/kernel/ldt.c:410
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__x64_sys_modify_ldt
```
**Symbols:**

```
ffffffff81036970-ffffffff81036a53: read_ldt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int read_ldt(void *ptr, long unsigned int bytecount);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff810262b0)
Location: arch/x86/kernel/ldt.c:410
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__x64_sys_modify_ldt
```
**Symbols:**

```
ffffffff810262b0-ffffffff81026393: read_ldt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int read_ldt(void *ptr, long unsigned int bytecount);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff810367d0)
Location: arch/x86/kernel/ldt.c:410
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__x64_sys_modify_ldt
```
**Symbols:**

```
ffffffff810367d0-ffffffff810368b3: read_ldt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int read_ldt(void *ptr, long unsigned int bytecount);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff810377d0)
Location: arch/x86/kernel/ldt.c:410
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__x64_sys_modify_ldt
```
**Symbols:**

```
ffffffff810377d0-ffffffff810378b3: read_ldt (STB_LOCAL)
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
