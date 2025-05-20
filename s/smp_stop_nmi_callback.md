# Function: <code>smp_stop_nmi_callback</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int smp_stop_nmi_callback(unsigned int val, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smp.c (ffffffff810507f0)
Location: arch/x86/kernel/smp.c:157
Inline: False
```
**Symbols:**

```
ffffffff810507f0-ffffffff8105081e: smp_stop_nmi_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int smp_stop_nmi_callback(unsigned int val, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smp.c (ffffffff810509f0)
Location: arch/x86/kernel/smp.c:157
Inline: False
```
**Symbols:**

```
ffffffff810509f0-ffffffff81050a1e: smp_stop_nmi_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int smp_stop_nmi_callback(unsigned int val, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smp.c (ffffffff81053260)
Location: arch/x86/kernel/smp.c:159
Inline: False
```
**Symbols:**

```
ffffffff81053260-ffffffff8105328e: smp_stop_nmi_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int smp_stop_nmi_callback(unsigned int val, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smp.c (ffffffff81052d90)
Location: arch/x86/kernel/smp.c:160
Inline: True
```
**Symbols:**

```
ffffffff81052d90-ffffffff81052e41: smp_stop_nmi_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int smp_stop_nmi_callback(unsigned int val, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smp.c (ffffffff81056a90)
Location: arch/x86/kernel/smp.c:160
Inline: True
```
**Symbols:**

```
ffffffff81056a90-ffffffff81056b67: smp_stop_nmi_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int smp_stop_nmi_callback(unsigned int val, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smp.c (ffffffff81059900)
Location: arch/x86/kernel/smp.c:160
Inline: True
```
**Symbols:**

```
ffffffff81059900-ffffffff810599d7: smp_stop_nmi_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int smp_stop_nmi_callback(unsigned int val, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smp.c (ffffffff8105f580)
Location: arch/x86/kernel/smp.c:160
Inline: True
```
**Symbols:**

```
ffffffff8105f580-ffffffff8105f657: smp_stop_nmi_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int smp_stop_nmi_callback(unsigned int val, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smp.c (ffffffff81062a10)
Location: arch/x86/kernel/smp.c:158
Inline: True
```
**Symbols:**

```
ffffffff81062a10-ffffffff81062ae7: smp_stop_nmi_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int smp_stop_nmi_callback(unsigned int val, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smp.c (ffffffff81063200)
Location: arch/x86/kernel/smp.c:118
Inline: True
```
**Symbols:**

```
ffffffff81063200-ffffffff810632d7: smp_stop_nmi_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int smp_stop_nmi_callback(unsigned int val, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smp.c (ffffffff810695e0)
Location: arch/x86/kernel/smp.c:119
Inline: True
```
**Symbols:**

```
ffffffff810695e0-ffffffff81069686: smp_stop_nmi_callback.part.0 (STB_LOCAL)
ffffffff81069690-ffffffff810696bc: smp_stop_nmi_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int smp_stop_nmi_callback(unsigned int val, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smp.c (ffffffff8106b1c0)
Location: arch/x86/kernel/smp.c:119
Inline: True
```
**Symbols:**

```
ffffffff8106b1c0-ffffffff8106b266: smp_stop_nmi_callback.part.0 (STB_LOCAL)
ffffffff8106b270-ffffffff8106b29c: smp_stop_nmi_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int smp_stop_nmi_callback(unsigned int val, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smp.c (ffffffff8106ba60)
Location: arch/x86/kernel/smp.c:119
Inline: True
```
**Symbols:**

```
ffffffff8106ba60-ffffffff8106bb1c: smp_stop_nmi_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int smp_stop_nmi_callback(unsigned int val, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smp.c (ffffffff81076530)
Location: arch/x86/kernel/smp.c:119
Inline: True
```
**Symbols:**

```
ffffffff81076530-ffffffff810765ec: smp_stop_nmi_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int smp_stop_nmi_callback(unsigned int val, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smp.c (ffffffff810853a0)
Location: arch/x86/kernel/smp.c:119
Inline: True
```
**Symbols:**

```
ffffffff810853a0-ffffffff81085450: smp_stop_nmi_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int smp_stop_nmi_callback(unsigned int val, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smp.c (ffffffff81098560)
Location: arch/x86/kernel/smp.c:119
Inline: True
```
**Symbols:**

```
ffffffff81098560-ffffffff81098594: smp_stop_nmi_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int smp_stop_nmi_callback(unsigned int val, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smp.c (ffffffff8109b620)
Location: arch/x86/kernel/smp.c:121
Inline: True
```
**Symbols:**

```
ffffffff8109b620-ffffffff8109b654: smp_stop_nmi_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int smp_stop_nmi_callback(unsigned int val, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smp.c (ffffffff810a2be0)
Location: arch/x86/kernel/smp.c:121
Inline: True
```
**Symbols:**

```
ffffffff810a2be0-ffffffff810a2c14: smp_stop_nmi_callback (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int smp_stop_nmi_callback(unsigned int val, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smp.c (ffffffff81062cf0)
Location: arch/x86/kernel/smp.c:118
Inline: True
```
**Symbols:**

```
ffffffff81062cf0-ffffffff81062dc7: smp_stop_nmi_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int smp_stop_nmi_callback(unsigned int val, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smp.c (ffffffff810531a0)
Location: arch/x86/kernel/smp.c:118
Inline: True
```
**Symbols:**

```
ffffffff810531a0-ffffffff81053242: smp_stop_nmi_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int smp_stop_nmi_callback(unsigned int val, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smp.c (ffffffff810631a0)
Location: arch/x86/kernel/smp.c:118
Inline: True
```
**Symbols:**

```
ffffffff810631a0-ffffffff81063277: smp_stop_nmi_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int smp_stop_nmi_callback(unsigned int val, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smp.c (ffffffff81064760)
Location: arch/x86/kernel/smp.c:118
Inline: True
```
**Symbols:**

```
ffffffff81064760-ffffffff81064837: smp_stop_nmi_callback (STB_LOCAL)
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
