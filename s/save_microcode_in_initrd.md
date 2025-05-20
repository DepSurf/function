# Function: <code>save_microcode_in_initrd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int save_microcode_in_initrd();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81f6ce7a)
Location: arch/x86/kernel/cpu/microcode/core.c:185
Inline: False
Direct callers:
  - arch/x86/mm/init.c:free_initrd_mem
```
**Symbols:**

```
ffffffff81f6ce7a-ffffffff81f6ceb0: save_microcode_in_initrd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int save_microcode_in_initrd();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81f9518e)
Location: arch/x86/kernel/cpu/microcode/core.c:177
Inline: True
```
**Symbols:**

```
ffffffff81f9518e-ffffffff81f951d3: save_microcode_in_initrd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int save_microcode_in_initrd();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81fd05ca)
Location: arch/x86/kernel/cpu/microcode/core.c:192
Inline: False
```
**Symbols:**

```
ffffffff81fd05ca-ffffffff81fd061a: save_microcode_in_initrd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int save_microcode_in_initrd();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff820b1228)
Location: arch/x86/kernel/cpu/microcode/core.c:221
Inline: True
```
**Symbols:**

```
ffffffff820b1228-ffffffff820b12c8: save_microcode_in_initrd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int save_microcode_in_initrd();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff826b7a3a)
Location: arch/x86/kernel/cpu/microcode/core.c:238
Inline: False
```
**Symbols:**

```
ffffffff826b7a3a-ffffffff826b7ada: save_microcode_in_initrd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int save_microcode_in_initrd();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff826e174c)
Location: arch/x86/kernel/cpu/microcode/core.c:238
Inline: False
```
**Symbols:**

```
ffffffff826e174c-ffffffff826e17e5: save_microcode_in_initrd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int save_microcode_in_initrd();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8289770e)
Location: arch/x86/kernel/cpu/microcode/core.c:238
Inline: False
```
**Symbols:**

```
ffffffff8289770e-ffffffff828977a7: save_microcode_in_initrd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int save_microcode_in_initrd();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff828af2db)
Location: arch/x86/kernel/cpu/microcode/core.c:234
Inline: False
```
**Symbols:**

```
ffffffff828af2db-ffffffff828af374: save_microcode_in_initrd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int save_microcode_in_initrd();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff828b2614)
Location: arch/x86/kernel/cpu/microcode/core.c:234
Inline: False
```
**Symbols:**

```
ffffffff828b2614-ffffffff828b26ad: save_microcode_in_initrd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int save_microcode_in_initrd();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff82cd77c0)
Location: arch/x86/kernel/cpu/microcode/core.c:229
Inline: False
```
**Symbols:**

```
ffffffff82cd77c0-ffffffff82cd7859: save_microcode_in_initrd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int save_microcode_in_initrd();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff82fc3793)
Location: arch/x86/kernel/cpu/microcode/core.c:227
Inline: False
```
**Symbols:**

```
ffffffff82fc3793-ffffffff82fc382c: save_microcode_in_initrd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int save_microcode_in_initrd();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff831cdd75)
Location: arch/x86/kernel/cpu/microcode/core.c:227
Inline: False
```
**Symbols:**

```
ffffffff831cdd75-ffffffff831cde0e: save_microcode_in_initrd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int save_microcode_in_initrd();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff832afed8)
Location: arch/x86/kernel/cpu/microcode/core.c:227
Inline: False
```
**Symbols:**

```
ffffffff832afed8-ffffffff832aff71: save_microcode_in_initrd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int save_microcode_in_initrd();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff83460f39)
Location: arch/x86/kernel/cpu/microcode/core.c:210
Inline: False
```
**Symbols:**

```
ffffffff83460f39-ffffffff83460fef: save_microcode_in_initrd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int save_microcode_in_initrd();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff83e82dd0)
Location: arch/x86/kernel/cpu/microcode/core.c:210
Inline: False
```
**Symbols:**

```
ffffffff83e82dd0-ffffffff83e82e8a: save_microcode_in_initrd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int save_microcode_in_initrd();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff836a6120)
Location: arch/x86/kernel/cpu/microcode/core.c:210
Inline: False
```
**Symbols:**

```
ffffffff836a6120-ffffffff836a61e1: save_microcode_in_initrd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int save_microcode_in_initrd();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff838d6a80)
Location: arch/x86/kernel/cpu/microcode/amd.c:519
Inline: False
```
**Symbols:**

```
ffffffff838d6a80-ffffffff838d6ba0: save_microcode_in_initrd (STB_LOCAL)
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
int save_microcode_in_initrd();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff828a0633)
Location: arch/x86/kernel/cpu/microcode/core.c:234
Inline: False
```
**Symbols:**

```
ffffffff828a0633-ffffffff828a06cc: save_microcode_in_initrd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int save_microcode_in_initrd();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff828985c8)
Location: arch/x86/kernel/cpu/microcode/core.c:234
Inline: False
```
**Symbols:**

```
ffffffff828985c8-ffffffff8289861f: save_microcode_in_initrd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int save_microcode_in_initrd();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff828b35f6)
Location: arch/x86/kernel/cpu/microcode/core.c:234
Inline: False
```
**Symbols:**

```
ffffffff828b35f6-ffffffff828b368f: save_microcode_in_initrd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int save_microcode_in_initrd();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff828b3624)
Location: arch/x86/kernel/cpu/microcode/core.c:234
Inline: False
```
**Symbols:**

```
ffffffff828b3624-ffffffff828b36bd: save_microcode_in_initrd (STB_LOCAL)
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
