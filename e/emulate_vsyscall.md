# Function: <code>emulate_vsyscall</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool emulate_vsyscall(struct pt_regs *regs, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004790)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:123
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff81004790-ffffffff81004b40: emulate_vsyscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool emulate_vsyscall(struct pt_regs *regs, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff810048a0)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:123
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff810048a0-ffffffff81004ca4: emulate_vsyscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool emulate_vsyscall(struct pt_regs *regs, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004920)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:123
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff81004920-ffffffff81004d20: emulate_vsyscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool emulate_vsyscall(struct pt_regs *regs, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004790)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:125
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff81004790-ffffffff81004ba9: emulate_vsyscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool emulate_vsyscall(struct pt_regs *regs, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004a00)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:127
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff81004a00-ffffffff81004e00: emulate_vsyscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool emulate_vsyscall(struct pt_regs *regs, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81005130)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:123
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff81005130-ffffffff81005549: emulate_vsyscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool emulate_vsyscall(struct pt_regs *regs, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81005030)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:116
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
```
**Symbols:**

```
ffffffff81005030-ffffffff81005449: emulate_vsyscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool emulate_vsyscall(long unsigned int error_code, struct pt_regs *regs, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff810050f0)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:120
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
**Symbols:**

```
ffffffff810050f0-ffffffff810054f9: emulate_vsyscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool emulate_vsyscall(long unsigned int error_code, struct pt_regs *regs, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81005170)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:120
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
**Symbols:**

```
ffffffff81005170-ffffffff81005579: emulate_vsyscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool emulate_vsyscall(long unsigned int error_code, struct pt_regs *regs, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81006040)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:120
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
**Symbols:**

```
ffffffff81006040-ffffffff810063f1: emulate_vsyscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool emulate_vsyscall(long unsigned int error_code, struct pt_regs *regs, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81005270)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:120
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
**Symbols:**

```
ffffffff81005270-ffffffff810055fc: emulate_vsyscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool emulate_vsyscall(long unsigned int error_code, struct pt_regs *regs, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81005190)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:120
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
**Symbols:**

```
ffffffff81005190-ffffffff8100555c: emulate_vsyscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool emulate_vsyscall(long unsigned int error_code, struct pt_regs *regs, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff810057a0)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:120
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
**Symbols:**

```
ffffffff810057a0-ffffffff81005b9b: emulate_vsyscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool emulate_vsyscall(long unsigned int error_code, struct pt_regs *regs, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004960)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:120
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
**Symbols:**

```
ffffffff81004960-ffffffff81004da0: emulate_vsyscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool emulate_vsyscall(long unsigned int error_code, struct pt_regs *regs, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff810053d0)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:120
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
**Symbols:**

```
ffffffff810053d0-ffffffff81005813: emulate_vsyscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool emulate_vsyscall(long unsigned int error_code, struct pt_regs *regs, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004bf0)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:120
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
**Symbols:**

```
ffffffff81004bf0-ffffffff81004fcc: emulate_vsyscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool emulate_vsyscall(long unsigned int error_code, struct pt_regs *regs, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81007500)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:120
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
**Symbols:**

```
ffffffff81007500-ffffffff810078dc: emulate_vsyscall (STB_GLOBAL)
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
bool emulate_vsyscall(long unsigned int error_code, struct pt_regs *regs, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81005170)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:120
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
**Symbols:**

```
ffffffff81005170-ffffffff81005579: emulate_vsyscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool emulate_vsyscall(long unsigned int error_code, struct pt_regs *regs, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81003850)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:120
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
**Symbols:**

```
ffffffff81003850-ffffffff81003c59: emulate_vsyscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool emulate_vsyscall(long unsigned int error_code, struct pt_regs *regs, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81005130)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:120
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
**Symbols:**

```
ffffffff81005130-ffffffff81005539: emulate_vsyscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool emulate_vsyscall(long unsigned int error_code, struct pt_regs *regs, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81005270)
Location: arch/x86/entry/vsyscall/vsyscall_64.c:120
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
**Symbols:**

```
ffffffff81005270-ffffffff81005692: emulate_vsyscall (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int error_code</code>
</li>
<li>
<b>Param reordered. </b>
<code>regs, address</code> ➡️ <code>error_code, regs, address</code>
</li>
</ul>
</details>
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
