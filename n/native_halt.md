# Function: <code>native_halt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_halt();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff810528a0)
Location: arch/x86/include/asm/irqflags.h:52
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In arch/x86/kernel/paravirt.c (ffffffff810645f0)
Location: arch/x86/include/asm/irqflags.h:52
Inline: False
```
**Symbols:**

```
ffffffff810645f0-ffffffff810645f7: native_halt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_halt();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff810528ab)
Location: arch/x86/include/asm/irqflags.h:52
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:hlt_play_dead
```
```
In arch/x86/kernel/paravirt.c (ffffffff81064240)
Location: arch/x86/include/asm/irqflags.h:52
Inline: False
```
**Symbols:**

```
ffffffff81064240-ffffffff81064247: native_halt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_halt();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff810551bb)
Location: arch/x86/include/asm/irqflags.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:hlt_play_dead
```
```
In arch/x86/kernel/paravirt.c (ffffffff818d3d70)
Location: arch/x86/include/asm/irqflags.h:56
Inline: False
```
**Symbols:**

```
ffffffff818d3d70-ffffffff818d3d77: native_halt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_halt();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81054abb)
Location: arch/x86/include/asm/irqflags.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:hlt_play_dead
```
```
In arch/x86/kernel/paravirt.c (ffffffff8190aed0)
Location: arch/x86/include/asm/irqflags.h:56
Inline: False
```
**Symbols:**

```
ffffffff8190aed0-ffffffff8190aed7: native_halt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_halt();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81038549)
Location: arch/x86/include/asm/irqflags.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/smpboot.c (ffffffff81058874)
Location: arch/x86/include/asm/irqflags.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:hlt_play_dead
```
```
In arch/x86/kernel/paravirt.c (ffffffff81995240)
Location: arch/x86/include/asm/irqflags.h:57
Inline: False
```
**Symbols:**

```
ffffffff81995240-ffffffff81995247: native_halt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_halt();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81039a69)
Location: arch/x86/include/asm/irqflags.h:60
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/smpboot.c (ffffffff8105b4e4)
Location: arch/x86/include/asm/irqflags.h:60
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:hlt_play_dead
```
```
In arch/x86/kernel/paravirt.c (ffffffff819f17a0)
Location: arch/x86/include/asm/irqflags.h:60
Inline: False
```
**Symbols:**

```
ffffffff819f17a0-ffffffff819f17a7: native_halt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_halt();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103af99)
Location: arch/x86/include/asm/irqflags.h:60
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/smpboot.c (ffffffff81061164)
Location: arch/x86/include/asm/irqflags.h:60
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:hlt_play_dead
```
```
In arch/x86/kernel/paravirt.c (ffffffff81a2cc40)
Location: arch/x86/include/asm/irqflags.h:60
Inline: False
```
**Symbols:**

```
ffffffff81a2cc40-ffffffff81a2cc47: native_halt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_halt();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103d5ab)
Location: arch/x86/include/asm/irqflags.h:63
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/smpboot.c (ffffffff81064814)
Location: arch/x86/include/asm/irqflags.h:63
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:hlt_play_dead
```
```
In arch/x86/kernel/paravirt.c (ffffffff81a9cda0)
Location: arch/x86/include/asm/irqflags.h:63
Inline: False
```
**Symbols:**

```
ffffffff81a9cda0-ffffffff81a9cdae: native_halt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_halt();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103dd67)
Location: arch/x86/include/asm/irqflags.h:63
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/smpboot.c (ffffffff81064e94)
Location: arch/x86/include/asm/irqflags.h:63
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:hlt_play_dead
```
```
In arch/x86/kernel/paravirt.c (ffffffff81ad45f0)
Location: arch/x86/include/asm/irqflags.h:63
Inline: False
```
**Symbols:**

```
ffffffff81ad45f0-ffffffff81ad45fe: native_halt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_halt();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81040e25)
Location: arch/x86/include/asm/irqflags.h:63
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106b5c4)
Location: arch/x86/include/asm/irqflags.h:63
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:hlt_play_dead
```
```
In arch/x86/kernel/paravirt.c (ffffffff81bcc670)
Location: arch/x86/include/asm/irqflags.h:63
Inline: False
```
**Symbols:**

```
ffffffff81bcc670-ffffffff81bcc67e: native_halt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_halt();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81040d85)
Location: arch/x86/include/asm/irqflags.h:63
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106d264)
Location: arch/x86/include/asm/irqflags.h:63
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:hlt_play_dead
```
```
In arch/x86/kernel/paravirt.c (ffffffff81c45220)
Location: arch/x86/include/asm/irqflags.h:63
Inline: False
```
**Symbols:**

```
ffffffff81c45220-ffffffff81c4522e: native_halt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_halt();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81042785)
Location: arch/x86/include/asm/irqflags.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106dcd4)
Location: arch/x86/include/asm/irqflags.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:hlt_play_dead
```
```
In arch/x86/kernel/paravirt.c (ffffffff81c384a0)
Location: arch/x86/include/asm/irqflags.h:54
Inline: False
```
**Symbols:**

```
ffffffff81c384a0-ffffffff81c384ae: native_halt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_halt();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81048ad5)
Location: arch/x86/include/asm/irqflags.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/smpboot.c (ffffffff810794e4)
Location: arch/x86/include/asm/irqflags.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:hlt_play_dead
```
```
In arch/x86/kernel/paravirt.c (ffffffff81d56d50)
Location: arch/x86/include/asm/irqflags.h:54
Inline: False
```
**Symbols:**

```
ffffffff81d56d50-ffffffff81d56d5b: native_halt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_halt();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81051da3)
Location: arch/x86/include/asm/irqflags.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/smpboot.c (ffffffff81088374)
Location: arch/x86/include/asm/irqflags.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:hlt_play_dead
```
```
In arch/x86/kernel/paravirt.c (ffffffff81f29010)
Location: arch/x86/include/asm/irqflags.h:54
Inline: False
```
**Symbols:**

```
ffffffff81f29010-ffffffff81f2901f: native_halt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_halt();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8105f472)
Location: arch/x86/include/asm/irqflags.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/smpboot.c (ffffffff8109be24)
Location: arch/x86/include/asm/irqflags.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:hlt_play_dead
```
```
In arch/x86/kernel/paravirt.c (ffffffff820d4d00)
Location: arch/x86/include/asm/irqflags.h:54
Inline: False
```
**Symbols:**

```
ffffffff820d4d00-ffffffff820d4d0f: native_halt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_halt();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81060b47)
Location: arch/x86/include/asm/irqflags.h:51
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/smpboot.c (ffffffff8109ee9a)
Location: arch/x86/include/asm/irqflags.h:51
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:hlt_play_dead
  - arch/x86/kernel/smpboot.c:mwait_play_dead
```
```
In arch/x86/kernel/paravirt.c (ffffffff810bb060)
Location: arch/x86/include/asm/irqflags.h:51
Inline: False
```
**Symbols:**

```
ffffffff810bb060-ffffffff810bb06f: native_halt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_halt();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81067bf7)
Location: arch/x86/include/asm/irqflags.h:51
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/smpboot.c (ffffffff810a62ca)
Location: arch/x86/include/asm/irqflags.h:51
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:hlt_play_dead
  - arch/x86/kernel/smpboot.c:mwait_play_dead
```
```
In arch/x86/kernel/paravirt.c (ffffffff810c24b0)
Location: arch/x86/include/asm/irqflags.h:51
Inline: False
```
**Symbols:**

```
ffffffff810c24b0-ffffffff810c24bf: native_halt (STB_LOCAL)
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
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_halt();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103dee7)
Location: arch/x86/include/asm/irqflags.h:63
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/smpboot.c (ffffffff81064984)
Location: arch/x86/include/asm/irqflags.h:63
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:hlt_play_dead
```
```
In arch/x86/kernel/paravirt.c (ffffffff81a73460)
Location: arch/x86/include/asm/irqflags.h:63
Inline: False
```
**Symbols:**

```
ffffffff81a73460-ffffffff81a7346e: native_halt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8102d701)
Location: arch/x86/include/asm/irqflags.h:63
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/tboot.c (ffffffff81033448)
Location: arch/x86/include/asm/irqflags.h:63
Inline: True
```
```
In arch/x86/kernel/reboot.c (ffffffff81052aec)
Location: arch/x86/include/asm/irqflags.h:63
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/kernel/smpboot.c (ffffffff81054c76)
Location: arch/x86/include/asm/irqflags.h:63
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:hlt_play_dead
```
```
In arch/x86/kernel/kvm.c (ffffffff81066437)
Location: arch/x86/include/asm/irqflags.h:63
Inline: True
```
```
In arch/x86/mm/extable.c (ffffffff828a626f)
Location: arch/x86/include/asm/irqflags.h:63
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:early_fixup_exception
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_halt();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103dd27)
Location: arch/x86/include/asm/irqflags.h:63
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/smpboot.c (ffffffff81064e34)
Location: arch/x86/include/asm/irqflags.h:63
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:hlt_play_dead
```
```
In arch/x86/kernel/paravirt.c (ffffffff81adf870)
Location: arch/x86/include/asm/irqflags.h:63
Inline: False
```
**Symbols:**

```
ffffffff81adf870-ffffffff81adf87e: native_halt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_halt();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103ee87)
Location: arch/x86/include/asm/irqflags.h:63
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:stop_this_cpu
```
```
In arch/x86/kernel/smpboot.c (ffffffff81066414)
Location: arch/x86/include/asm/irqflags.h:63
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:hlt_play_dead
```
```
In arch/x86/kernel/paravirt.c (ffffffff81aec040)
Location: arch/x86/include/asm/irqflags.h:63
Inline: False
```
**Symbols:**

```
ffffffff81aec040-ffffffff81aec04e: native_halt (STB_LOCAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
