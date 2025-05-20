# Function: <code>write_ldt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int write_ldt(void *ptr, long unsigned int bytecount, int oldmode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81032c20)
Location: arch/x86/kernel/ldt.c:207
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:sys_modify_ldt
  - arch/x86/kernel/ldt.c:sys_modify_ldt
```
**Symbols:**

```
ffffffff81032c20-ffffffff81032ea7: write_ldt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int write_ldt(void *ptr, long unsigned int bytecount, int oldmode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81031dc0)
Location: arch/x86/kernel/ldt.c:207
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:sys_modify_ldt
  - arch/x86/kernel/ldt.c:sys_modify_ldt
```
**Symbols:**

```
ffffffff81031dc0-ffffffff8103203e: write_ldt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int write_ldt(void *ptr, long unsigned int bytecount, int oldmode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81031a40)
Location: arch/x86/kernel/ldt.c:207
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:sys_modify_ldt
  - arch/x86/kernel/ldt.c:sys_modify_ldt
```
**Symbols:**

```
ffffffff81031a40-ffffffff81031cb3: write_ldt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int write_ldt(void *ptr, long unsigned int bytecount, int oldmode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff8102fc50)
Location: arch/x86/kernel/ldt.c:208
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:sys_modify_ldt
  - arch/x86/kernel/ldt.c:sys_modify_ldt
```
**Symbols:**

```
ffffffff8102fc50-ffffffff8102fec1: write_ldt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int write_ldt(void *ptr, long unsigned int bytecount, int oldmode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81031f50)
Location: arch/x86/kernel/ldt.c:357
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:SyS_modify_ldt
  - arch/x86/kernel/ldt.c:SyS_modify_ldt
```
**Symbols:**

```
ffffffff81031f50-ffffffff81032262: write_ldt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int write_ldt(void *ptr, long unsigned int bytecount, int oldmode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81033310)
Location: arch/x86/kernel/ldt.c:361
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__x64_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__x64_sys_modify_ldt
```
**Symbols:**

```
ffffffff81033310-ffffffff81033635: write_ldt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int write_ldt(void *ptr, long unsigned int bytecount, int oldmode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff810345c0)
Location: arch/x86/kernel/ldt.c:464
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__x64_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__x64_sys_modify_ldt
```
**Symbols:**

```
ffffffff810345c0-ffffffff8103499c: write_ldt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int write_ldt(void *ptr, long unsigned int bytecount, int oldmode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81036460)
Location: arch/x86/kernel/ldt.c:464
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__x64_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__x64_sys_modify_ldt
```
**Symbols:**

```
ffffffff81036460-ffffffff81036848: write_ldt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int write_ldt(void *ptr, long unsigned int bytecount, int oldmode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81036c90)
Location: arch/x86/kernel/ldt.c:464
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__x64_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__x64_sys_modify_ldt
```
**Symbols:**

```
ffffffff81036c90-ffffffff81037078: write_ldt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int write_ldt(void *ptr, long unsigned int bytecount, int oldmode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ldt.c (0)
Location: arch/x86/kernel/ldt.c:570
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__x64_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__x64_sys_modify_ldt
```
**Symbols:**

```
ffffffff81038ba0-ffffffff81038ece: write_ldt (STB_LOCAL)
ffffffff81039220-ffffffff8103923e: write_ldt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int write_ldt(void *ptr, long unsigned int bytecount, int oldmode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ldt.c (0)
Location: arch/x86/kernel/ldt.c:570
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__x64_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__x64_sys_modify_ldt
```
**Symbols:**

```
ffffffff81039420-ffffffff810397f5: write_ldt (STB_LOCAL)
ffffffff81bd3acf-ffffffff81bd3aec: write_ldt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int write_ldt(void *ptr, long unsigned int bytecount, int oldmode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ldt.c (0)
Location: arch/x86/kernel/ldt.c:576
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__x64_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__x64_sys_modify_ldt
```
**Symbols:**

```
ffffffff8103aef0-ffffffff8103b2c2: write_ldt (STB_LOCAL)
ffffffff81bc5f41-ffffffff81bc5f5e: write_ldt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int write_ldt(void *ptr, long unsigned int bytecount, int oldmode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ldt.c (0)
Location: arch/x86/kernel/ldt.c:576
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__x64_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__x64_sys_modify_ldt
```
**Symbols:**

```
ffffffff81040920-ffffffff81040d19: write_ldt (STB_LOCAL)
ffffffff81c98dad-ffffffff81c98e2c: write_ldt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int write_ldt(void *ptr, long unsigned int bytecount, int oldmode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ldt.c (0)
Location: arch/x86/kernel/ldt.c:576
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__x64_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__x64_sys_modify_ldt
```
**Symbols:**

```
ffffffff810482e0-ffffffff81048721: write_ldt (STB_LOCAL)
ffffffff81e4836d-ffffffff81e483d7: write_ldt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int write_ldt(void *ptr, long unsigned int bytecount, int oldmode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ldt.c (0)
Location: arch/x86/kernel/ldt.c:576
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__x64_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__x64_sys_modify_ldt
```
**Symbols:**

```
ffffffff81053040-ffffffff81053481: write_ldt (STB_LOCAL)
ffffffff82052255-ffffffff820522bf: write_ldt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int write_ldt(void *ptr, long unsigned int bytecount, int oldmode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ldt.c (0)
Location: arch/x86/kernel/ldt.c:578
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__x64_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__x64_sys_modify_ldt
```
**Symbols:**

```
ffffffff81054020-ffffffff8105446b: write_ldt (STB_LOCAL)
ffffffff820d076f-ffffffff820d07d9: write_ldt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int write_ldt(void *ptr, long unsigned int bytecount, int oldmode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ldt.c (0)
Location: arch/x86/kernel/ldt.c:578
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__x64_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__x64_sys_modify_ldt
```
**Symbols:**

```
ffffffff8105b250-ffffffff8105b6a4: write_ldt (STB_LOCAL)
ffffffff821ab284-ffffffff821ab2ee: write_ldt.cold (STB_LOCAL)
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
int write_ldt(void *ptr, long unsigned int bytecount, int oldmode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81036df0)
Location: arch/x86/kernel/ldt.c:464
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__x64_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__x64_sys_modify_ldt
```
**Symbols:**

```
ffffffff81036df0-ffffffff810371d8: write_ldt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int write_ldt(void *ptr, long unsigned int bytecount, int oldmode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81026700)
Location: arch/x86/kernel/ldt.c:464
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__x64_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__x64_sys_modify_ldt
```
**Symbols:**

```
ffffffff81026700-ffffffff81026aad: write_ldt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int write_ldt(void *ptr, long unsigned int bytecount, int oldmode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81036c50)
Location: arch/x86/kernel/ldt.c:464
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__x64_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__x64_sys_modify_ldt
```
**Symbols:**

```
ffffffff81036c50-ffffffff81037038: write_ldt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int write_ldt(void *ptr, long unsigned int bytecount, int oldmode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81037c50)
Location: arch/x86/kernel/ldt.c:464
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__x64_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__x64_sys_modify_ldt
```
**Symbols:**

```
ffffffff81037c50-ffffffff81038036: write_ldt (STB_LOCAL)
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
