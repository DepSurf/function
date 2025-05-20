# Function: <code>speculation_ctrl_update</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void speculation_ctrl_update(long unsigned int tif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103a710)
Location: arch/x86/kernel/process.c:466
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_current
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
```
**Symbols:**

```
ffffffff8103a710-ffffffff8103a8e0: speculation_ctrl_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void speculation_ctrl_update(long unsigned int tif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103cc90)
Location: arch/x86/kernel/process.c:480
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_current
  - arch/x86/kernel/process.c:arch_setup_new_exec
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
```
**Symbols:**

```
ffffffff8103cc90-ffffffff8103ce72: speculation_ctrl_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void speculation_ctrl_update(long unsigned int tif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103d450)
Location: arch/x86/kernel/process.c:480
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_current
  - arch/x86/kernel/process.c:arch_setup_new_exec
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
```
**Symbols:**

```
ffffffff8103d450-ffffffff8103d632: speculation_ctrl_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void speculation_ctrl_update(long unsigned int tif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff810405c0)
Location: arch/x86/kernel/process.c:576
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_current
  - arch/x86/kernel/process.c:arch_setup_new_exec
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
```
**Symbols:**

```
ffffffff810405c0-ffffffff810407a2: speculation_ctrl_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void speculation_ctrl_update(long unsigned int tif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81040510)
Location: arch/x86/kernel/process.c:578
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_current
  - arch/x86/kernel/process.c:arch_setup_new_exec
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
```
**Symbols:**

```
ffffffff81040510-ffffffff810406f2: speculation_ctrl_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void speculation_ctrl_update(long unsigned int tif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81041ee0)
Location: arch/x86/kernel/process.c:590
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_current
  - arch/x86/kernel/process.c:arch_setup_new_exec
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
```
**Symbols:**

```
ffffffff81041ee0-ffffffff810420e3: speculation_ctrl_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void speculation_ctrl_update(long unsigned int tif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81048240)
Location: arch/x86/kernel/process.c:607
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_current
  - arch/x86/kernel/process.c:arch_setup_new_exec
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
```
**Symbols:**

```
ffffffff81048240-ffffffff81048440: speculation_ctrl_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void speculation_ctrl_update(long unsigned int tif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81051570)
Location: arch/x86/kernel/process.c:623
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_current
  - arch/x86/kernel/process.c:arch_setup_new_exec
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
```
**Symbols:**

```
ffffffff81051570-ffffffff8105173e: speculation_ctrl_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void speculation_ctrl_update(long unsigned int tif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8105ebb0)
Location: arch/x86/kernel/process.c:623
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_current
  - arch/x86/kernel/process.c:arch_setup_new_exec
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
```
**Symbols:**

```
ffffffff8105ebb0-ffffffff8105ed83: speculation_ctrl_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void speculation_ctrl_update(long unsigned int tif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff810602a0)
Location: arch/x86/kernel/process.c:651
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_current
  - arch/x86/kernel/process.c:arch_setup_new_exec
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
```
**Symbols:**

```
ffffffff810602a0-ffffffff81060473: speculation_ctrl_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void speculation_ctrl_update(long unsigned int tif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81067320)
Location: arch/x86/kernel/process.c:663
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_current
  - arch/x86/kernel/process.c:arch_setup_new_exec
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
```
**Symbols:**

```
ffffffff81067320-ffffffff810674f3: speculation_ctrl_update (STB_GLOBAL)
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
void speculation_ctrl_update(long unsigned int tif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103d5d0)
Location: arch/x86/kernel/process.c:480
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_current
  - arch/x86/kernel/process.c:arch_setup_new_exec
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
```
**Symbols:**

```
ffffffff8103d5d0-ffffffff8103d7b2: speculation_ctrl_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void speculation_ctrl_update(long unsigned int tif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8102cc60)
Location: arch/x86/kernel/process.c:480
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_current
  - arch/x86/kernel/process.c:arch_setup_new_exec
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
```
**Symbols:**

```
ffffffff8102cc60-ffffffff8102cea5: speculation_ctrl_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void speculation_ctrl_update(long unsigned int tif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103d410)
Location: arch/x86/kernel/process.c:480
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_current
  - arch/x86/kernel/process.c:arch_setup_new_exec
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
```
**Symbols:**

```
ffffffff8103d410-ffffffff8103d5f2: speculation_ctrl_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void speculation_ctrl_update(long unsigned int tif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103e510)
Location: arch/x86/kernel/process.c:480
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_current
  - arch/x86/kernel/process.c:arch_setup_new_exec
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
```
**Symbols:**

```
ffffffff8103e510-ffffffff8103e6ee: speculation_ctrl_update (STB_GLOBAL)
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
