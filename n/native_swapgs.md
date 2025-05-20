# Function: <code>native_swapgs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void native_swapgs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81064640)
Location: arch/x86/include/asm/processor.h:454
Inline: False
```
**Symbols:**

```
ffffffff81064640-ffffffff81064649: native_swapgs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void native_swapgs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81064290)
Location: arch/x86/include/asm/processor.h:472
Inline: False
```
**Symbols:**

```
ffffffff81064290-ffffffff81064299: native_swapgs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void native_swapgs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81067760)
Location: arch/x86/include/asm/processor.h:514
Inline: False
```
**Symbols:**

```
ffffffff81067760-ffffffff81067769: native_swapgs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void native_swapgs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81066a20)
Location: arch/x86/include/asm/processor.h:525
Inline: False
```
**Symbols:**

```
ffffffff81066a20-ffffffff81066a29: native_swapgs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void native_swapgs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8106abe0)
Location: arch/x86/include/asm/processor.h:542
Inline: False
```
**Symbols:**

```
ffffffff8106abe0-ffffffff8106abe9: native_swapgs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void native_swapgs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8106d8a0)
Location: arch/x86/include/asm/processor.h:558
Inline: False
```
**Symbols:**

```
ffffffff8106d8a0-ffffffff8106d8a9: native_swapgs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void native_swapgs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81073a40)
Location: arch/x86/include/asm/processor.h:553
Inline: False
```
**Symbols:**

```
ffffffff81073a40-ffffffff81073a49: native_swapgs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void native_swapgs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810775a0)
Location: arch/x86/include/asm/processor.h:543
Inline: False
```
**Symbols:**

```
ffffffff810775a0-ffffffff810775a4: native_swapgs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void native_swapgs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81078610)
Location: arch/x86/include/asm/processor.h:543
Inline: False
```
**Symbols:**

```
ffffffff81078610-ffffffff81078614: native_swapgs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void native_swapgs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8107fa10)
Location: arch/x86/include/asm/processor.h:578
Inline: False
```
**Symbols:**

```
ffffffff8107fa10-ffffffff8107fa14: native_swapgs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_swapgs();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81c350f0)
Location: arch/x86/include/asm/processor.h:561
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__wrgsbase_inactive
  - arch/x86/kernel/process_64.c:__wrgsbase_inactive
  - arch/x86/kernel/process_64.c:__rdgsbase_inactive
  - arch/x86/kernel/process_64.c:__rdgsbase_inactive
```
```
In arch/x86/kernel/paravirt.c (ffffffff8107f640)
Location: arch/x86/include/asm/processor.h:561
Inline: False
```
**Symbols:**

```
ffffffff8107f640-ffffffff8107f644: native_swapgs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81c27590)
Location: arch/x86/include/asm/processor.h:543
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__wrgsbase_inactive
  - arch/x86/kernel/process_64.c:__wrgsbase_inactive
  - arch/x86/kernel/process_64.c:__rdgsbase_inactive
  - arch/x86/kernel/process_64.c:__rdgsbase_inactive
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81d455e0)
Location: arch/x86/include/asm/processor.h:555
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__wrgsbase_inactive
  - arch/x86/kernel/process_64.c:__wrgsbase_inactive
  - arch/x86/kernel/process_64.c:__rdgsbase_inactive
  - arch/x86/kernel/process_64.c:__rdgsbase_inactive
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
In arch/x86/kernel/process_64.c (ffffffff81f13799)
Location: arch/x86/include/asm/processor.h:555
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__wrgsbase_inactive
  - arch/x86/kernel/process_64.c:__wrgsbase_inactive
  - arch/x86/kernel/process_64.c:__rdgsbase_inactive
  - arch/x86/kernel/process_64.c:__rdgsbase_inactive
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
In arch/x86/kernel/process_64.c (ffffffff820ba939)
Location: arch/x86/include/asm/processor.h:500
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__wrgsbase_inactive
  - arch/x86/kernel/process_64.c:__wrgsbase_inactive
  - arch/x86/kernel/process_64.c:__rdgsbase_inactive
  - arch/x86/kernel/process_64.c:__rdgsbase_inactive
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
In arch/x86/kernel/process_64.c (ffffffff8213c049)
Location: arch/x86/include/asm/processor.h:500
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__wrgsbase_inactive
  - arch/x86/kernel/process_64.c:__wrgsbase_inactive
  - arch/x86/kernel/process_64.c:__rdgsbase_inactive
  - arch/x86/kernel/process_64.c:__rdgsbase_inactive
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
In arch/x86/kernel/process_64.c (ffffffff8221e049)
Location: arch/x86/include/asm/processor.h:522
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__wrgsbase_inactive
  - arch/x86/kernel/process_64.c:__wrgsbase_inactive
  - arch/x86/kernel/process_64.c:__rdgsbase_inactive
  - arch/x86/kernel/process_64.c:__rdgsbase_inactive
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
void native_swapgs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81077610)
Location: arch/x86/include/asm/processor.h:543
Inline: False
```
**Symbols:**

```
ffffffff81077610-ffffffff81077614: native_swapgs (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void native_swapgs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810775c0)
Location: arch/x86/include/asm/processor.h:543
Inline: False
```
**Symbols:**

```
ffffffff810775c0-ffffffff810775c4: native_swapgs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void native_swapgs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81079660)
Location: arch/x86/include/asm/processor.h:543
Inline: False
```
**Symbols:**

```
ffffffff81079660-ffffffff81079664: native_swapgs (STB_LOCAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
