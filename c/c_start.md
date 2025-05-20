# Function: <code>c_start</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision ⚠️</summary>

```c
void *c_start(struct seq_file *m, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/proc.c (ffffffff81041910)
Location: arch/x86/kernel/cpu/proc.c:140
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/proc.c:c_next
```
```
In fs/proc/consoles.c (ffffffff812822e0)
Location: fs/proc/consoles.c:63
Inline: False
```
```
In crypto/proc.c (ffffffff8139eea0)
Location: crypto/proc.c:25
Inline: False
```
**Symbols:**

```
ffffffff81041910-ffffffff8104195c: c_start (STB_LOCAL)
ffffffff812822e0-ffffffff8128231f: c_start (STB_LOCAL)
ffffffff8139eea0-ffffffff8139eecb: c_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision ⚠️</summary>

```c
void *c_start(struct seq_file *m, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/proc.c (ffffffff81041840)
Location: arch/x86/kernel/cpu/proc.c:140
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/proc.c:c_next
```
```
In fs/proc/consoles.c (ffffffff812af390)
Location: fs/proc/consoles.c:63
Inline: False
```
```
In crypto/proc.c (ffffffff813dbc50)
Location: crypto/proc.c:25
Inline: False
```
**Symbols:**

```
ffffffff81041840-ffffffff8104188c: c_start (STB_LOCAL)
ffffffff812af390-ffffffff812af3cf: c_start (STB_LOCAL)
ffffffff813dbc50-ffffffff813dbc7b: c_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision ⚠️</summary>

```c
void *c_start(struct seq_file *m, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/proc.c (ffffffff81041290)
Location: arch/x86/kernel/cpu/proc.c:140
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/proc.c:c_next
```
```
In fs/proc/consoles.c (ffffffff812c4d60)
Location: fs/proc/consoles.c:63
Inline: False
```
```
In crypto/proc.c (ffffffff813f3530)
Location: crypto/proc.c:25
Inline: False
```
**Symbols:**

```
ffffffff81041290-ffffffff810412de: c_start (STB_LOCAL)
ffffffff812c4d60-ffffffff812c4d9f: c_start (STB_LOCAL)
ffffffff813f3530-ffffffff813f355b: c_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision ⚠️</summary>

```c
void *c_start(struct seq_file *m, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/proc.c (ffffffff8103f3a0)
Location: arch/x86/kernel/cpu/proc.c:133
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/proc.c:c_next
```
```
In fs/proc/consoles.c (ffffffff812d1fa0)
Location: fs/proc/consoles.c:63
Inline: False
```
```
In crypto/proc.c (ffffffff813ff850)
Location: crypto/proc.c:25
Inline: False
```
**Symbols:**

```
ffffffff8103f3a0-ffffffff8103f3ec: c_start (STB_LOCAL)
ffffffff812d1fa0-ffffffff812d1fdf: c_start (STB_LOCAL)
ffffffff813ff850-ffffffff813ff87b: c_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
void *c_start(struct seq_file *m, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/proc.c (ffffffff81042666)
Location: arch/x86/kernel/cpu/proc.c:144
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/proc.c:c_next
```
```
In fs/proc/consoles.c (ffffffff812f67c0)
Location: fs/proc/consoles.c:63
Inline: False
```
```
In crypto/proc.c (ffffffff81427e20)
Location: crypto/proc.c:25
Inline: False
```
**Symbols:**

```
ffffffff81042610-ffffffff81042657: c_start (STB_LOCAL)
ffffffff812f67c0-ffffffff812f67ff: c_start (STB_LOCAL)
ffffffff81427e20-ffffffff81427e4b: c_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision ⚠️</summary>

```c
void *c_start(struct seq_file *m, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/proc.c (ffffffff81044500)
Location: arch/x86/kernel/cpu/proc.c:144
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/proc.c:c_next
```
```
In fs/proc/consoles.c (ffffffff81323c40)
Location: fs/proc/consoles.c:62
Inline: False
```
```
In crypto/proc.c (ffffffff8145ac50)
Location: crypto/proc.c:25
Inline: False
```
**Symbols:**

```
ffffffff81044500-ffffffff81044542: c_start (STB_LOCAL)
ffffffff81323c40-ffffffff81323c7f: c_start (STB_LOCAL)
ffffffff8145ac50-ffffffff8145ac7b: c_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision ⚠️</summary>

```c
void *c_start(struct seq_file *m, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/proc.c (ffffffff81045f00)
Location: arch/x86/kernel/cpu/proc.c:144
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/proc.c:c_next
```
```
In fs/proc/consoles.c (ffffffff8133ad90)
Location: fs/proc/consoles.c:62
Inline: False
```
```
In crypto/proc.c (ffffffff814787c0)
Location: crypto/proc.c:25
Inline: False
```
**Symbols:**

```
ffffffff81045f00-ffffffff81045f42: c_start (STB_LOCAL)
ffffffff8133ad90-ffffffff8133adcf: c_start (STB_LOCAL)
ffffffff814787c0-ffffffff814787eb: c_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision ⚠️</summary>

```c
void *c_start(struct seq_file *m, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/proc.c (ffffffff810489a0)
Location: arch/x86/kernel/cpu/proc.c:144
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/proc.c:c_next
```
```
In fs/proc/consoles.c (ffffffff81362f40)
Location: fs/proc/consoles.c:61
Inline: False
```
```
In crypto/proc.c (ffffffff814a65f0)
Location: crypto/proc.c:20
Inline: False
```
**Symbols:**

```
ffffffff810489a0-ffffffff810489e6: c_start (STB_LOCAL)
ffffffff81362f40-ffffffff81362f7a: c_start (STB_LOCAL)
ffffffff814a65f0-ffffffff814a661b: c_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision ⚠️</summary>

```c
void *c_start(struct seq_file *m, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/proc.c (ffffffff81049270)
Location: arch/x86/kernel/cpu/proc.c:144
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/proc.c:c_next
```
```
In fs/proc/consoles.c (ffffffff8137b1a0)
Location: fs/proc/consoles.c:61
Inline: False
```
```
In crypto/proc.c (ffffffff814c1280)
Location: crypto/proc.c:20
Inline: False
```
**Symbols:**

```
ffffffff81049270-ffffffff810492b6: c_start (STB_LOCAL)
ffffffff8137b1a0-ffffffff8137b1da: c_start (STB_LOCAL)
ffffffff814c1280-ffffffff814c12ab: c_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Selective Inline ⚠️</summary>

```c
void *c_start(struct seq_file *m, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/proc.c (ffffffff8104d44e)
Location: arch/x86/kernel/cpu/proc.c:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/proc.c:c_next
```
```
In fs/proc/consoles.c (ffffffff813c4520)
Location: fs/proc/consoles.c:61
Inline: False
```
```
In crypto/proc.c (ffffffff81521b30)
Location: crypto/proc.c:20
Inline: False
```
**Symbols:**

```
ffffffff8104cf90-ffffffff8104cfd9: c_start (STB_LOCAL)
ffffffff813c4520-ffffffff813c455d: c_start (STB_LOCAL)
ffffffff81521b30-ffffffff81521b5e: c_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Selective Inline ⚠️</summary>

```c
void *c_start(struct seq_file *m, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/proc.c (ffffffff8104c8ae)
Location: arch/x86/kernel/cpu/proc.c:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/proc.c:c_next
```
```
In fs/proc/consoles.c (ffffffff813d6480)
Location: fs/proc/consoles.c:61
Inline: False
```
```
In crypto/proc.c (ffffffff8153e9a0)
Location: crypto/proc.c:20
Inline: False
```
**Symbols:**

```
ffffffff8104c3f0-ffffffff8104c439: c_start (STB_LOCAL)
ffffffff813d6480-ffffffff813d64bd: c_start (STB_LOCAL)
ffffffff8153e9a0-ffffffff8153e9ce: c_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Selective Inline ⚠️</summary>

```c
void *c_start(struct seq_file *m, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/proc.c (ffffffff8104e3ee)
Location: arch/x86/kernel/cpu/proc.c:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/proc.c:c_next
```
```
In fs/proc/consoles.c (ffffffff813dd380)
Location: fs/proc/consoles.c:61
Inline: False
```
```
In crypto/proc.c (ffffffff81547050)
Location: crypto/proc.c:20
Inline: False
```
**Symbols:**

```
ffffffff8104df30-ffffffff8104df75: c_start (STB_LOCAL)
ffffffff813dd380-ffffffff813dd3bd: c_start (STB_LOCAL)
ffffffff81547050-ffffffff8154707e: c_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Selective Inline ⚠️</summary>

```c
void *c_start(struct seq_file *m, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/proc.c (ffffffff81055db4)
Location: arch/x86/kernel/cpu/proc.c:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/proc.c:c_next
```
```
In fs/proc/consoles.c (ffffffff8142eb10)
Location: fs/proc/consoles.c:61
Inline: False
```
```
In crypto/proc.c (ffffffff815a7830)
Location: crypto/proc.c:20
Inline: False
```
**Symbols:**

```
ffffffff81055730-ffffffff810557a1: c_start (STB_LOCAL)
ffffffff8142eb10-ffffffff8142eb4d: c_start (STB_LOCAL)
ffffffff815a7830-ffffffff815a785e: c_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Selective Inline ⚠️</summary>

```c
void *c_start(struct seq_file *m, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/proc.c (ffffffff81061da4)
Location: arch/x86/kernel/cpu/proc.c:154
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/proc.c:c_next
```
```
In fs/proc/consoles.c (ffffffff814a86a0)
Location: fs/proc/consoles.c:61
Inline: False
```
```
In crypto/proc.c (ffffffff8164eb20)
Location: crypto/proc.c:20
Inline: False
```
**Symbols:**

```
ffffffff81061d00-ffffffff81061d7b: c_start (STB_LOCAL)
ffffffff814a86a0-ffffffff814a86e7: c_start (STB_LOCAL)
ffffffff8164eb20-ffffffff8164eb56: c_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
void *c_start(struct seq_file *m, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/proc.c (ffffffff81070770)
Location: arch/x86/kernel/cpu/proc.c:154
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/proc.c:c_next
```
```
In fs/proc/consoles.c (ffffffff8153e050)
Location: fs/proc/consoles.c:70
Inline: False
```
```
In crypto/proc.c (ffffffff81707fd0)
Location: crypto/proc.c:20
Inline: False
```
**Symbols:**

```
ffffffff81070770-ffffffff810707ef: c_start (STB_LOCAL)
ffffffff8153e050-ffffffff8153e0a1: c_start (STB_LOCAL)
ffffffff81707fd0-ffffffff81708006: c_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
void *c_start(struct seq_file *m, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/proc.c (ffffffff81072370)
Location: arch/x86/kernel/cpu/proc.c:154
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/proc.c:c_next
```
```
In fs/proc/consoles.c (ffffffff81576320)
Location: fs/proc/consoles.c:70
Inline: False
```
```
In crypto/proc.c (ffffffff817416f0)
Location: crypto/proc.c:21
Inline: False
```
**Symbols:**

```
ffffffff81072370-ffffffff810723ef: c_start (STB_LOCAL)
ffffffff81576320-ffffffff81576371: c_start (STB_LOCAL)
ffffffff817416f0-ffffffff81741726: c_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
void *c_start(struct seq_file *m, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/proc.c (ffffffff81079b90)
Location: arch/x86/kernel/cpu/proc.c:156
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/proc.c:c_next
```
```
In fs/proc/consoles.c (ffffffff815aec70)
Location: fs/proc/consoles.c:70
Inline: False
```
```
In crypto/proc.c (ffffffff81782590)
Location: crypto/proc.c:21
Inline: False
```
**Symbols:**

```
ffffffff81079b90-ffffffff81079c0f: c_start (STB_LOCAL)
ffffffff815aec70-ffffffff815aecc1: c_start (STB_LOCAL)
ffffffff81782590-ffffffff817825c6: c_start (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision ⚠️</summary>

```c
void *c_start(struct seq_file *m, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/cpuinfo.c (ffff800010097940)
Location: arch/arm64/kernel/cpuinfo.c:185
Inline: False
```
```
In fs/proc/consoles.c (ffff800010447868)
Location: fs/proc/consoles.c:61
Inline: False
```
```
In crypto/proc.c (ffff8000105bb540)
Location: crypto/proc.c:20
Inline: False
```
**Symbols:**

```
ffff800010097940-ffff800010097970: c_start (STB_LOCAL)
ffff800010447868-ffff8000104478bc: c_start (STB_LOCAL)
ffff8000105bb540-ffff8000105bb580: c_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
void *c_start(struct seq_file *m, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/setup.c (c030d4c8)
Location: arch/arm/kernel/setup.c:1305
Inline: False
```
```
In fs/proc/consoles.c (c060c770)
Location: fs/proc/consoles.c:61
Inline: False
```
```
In crypto/proc.c (c07697b4)
Location: crypto/proc.c:20
Inline: False
```
**Symbols:**

```
c030d4c8-c030d4f4: c_start (STB_LOCAL)
c060c770-c060c7dc: c_start (STB_LOCAL)
c07697b4-c07697ec: c_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision ⚠️</summary>

```c
void *c_start(struct seq_file *m, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/setup-common.c (c00000000002fb80)
Location: arch/powerpc/kernel/setup-common.c:346
Inline: False
Direct callers:
  - arch/powerpc/kernel/setup-common.c:c_next
```
```
In fs/proc/consoles.c (c00000000055db80)
Location: fs/proc/consoles.c:61
Inline: False
```
```
In crypto/proc.c (c000000000741dd0)
Location: crypto/proc.c:20
Inline: False
```
**Symbols:**

```
c00000000002fb80-c00000000002fc24: c_start (STB_LOCAL)
c00000000055db80-c00000000055dbf4: c_start (STB_LOCAL)
c000000000741dd0-c000000000741e2c: c_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Selective Inline ⚠️</summary>

```c
void *c_start(struct seq_file *m, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/riscv/kernel/cpu.c (ffffffe0000b5290)
Location: arch/riscv/kernel/cpu.c:110
Inline: True
Inline callers:
  - arch/riscv/kernel/cpu.c:c_next
```
```
In fs/proc/consoles.c (ffffffe0002dd4fc)
Location: fs/proc/consoles.c:61
Inline: False
```
```
In crypto/proc.c (ffffffe000400fd2)
Location: crypto/proc.c:20
Inline: False
```
**Symbols:**

```
ffffffe0002dd4fc-ffffffe0002dd53c: c_start (STB_LOCAL)
ffffffe000400fd2-ffffffe000401014: c_start (STB_LOCAL)
ffffffe0000b522a-ffffffe0000b5278: c_start (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision ⚠️</summary>

```c
void *c_start(struct seq_file *m, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/proc.c (ffffffff810493e0)
Location: arch/x86/kernel/cpu/proc.c:144
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/proc.c:c_next
```
```
In fs/proc/consoles.c (ffffffff81373780)
Location: fs/proc/consoles.c:61
Inline: False
```
```
In crypto/proc.c (ffffffff814b9860)
Location: crypto/proc.c:20
Inline: False
```
**Symbols:**

```
ffffffff810493e0-ffffffff81049426: c_start (STB_LOCAL)
ffffffff81373780-ffffffff813737ba: c_start (STB_LOCAL)
ffffffff814b9860-ffffffff814b988b: c_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision ⚠️</summary>

```c
void *c_start(struct seq_file *m, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/proc.c (ffffffff810387b0)
Location: arch/x86/kernel/cpu/proc.c:144
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/proc.c:c_next
```
```
In fs/proc/consoles.c (ffffffff81364250)
Location: fs/proc/consoles.c:61
Inline: False
```
```
In crypto/proc.c (ffffffff814aa280)
Location: crypto/proc.c:20
Inline: False
```
**Symbols:**

```
ffffffff810387b0-ffffffff810387f6: c_start (STB_LOCAL)
ffffffff81364250-ffffffff8136428a: c_start (STB_LOCAL)
ffffffff814aa280-ffffffff814aa2ab: c_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision ⚠️</summary>

```c
void *c_start(struct seq_file *m, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/proc.c (ffffffff81049220)
Location: arch/x86/kernel/cpu/proc.c:144
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/proc.c:c_next
```
```
In fs/proc/consoles.c (ffffffff81371250)
Location: fs/proc/consoles.c:61
Inline: False
```
```
In crypto/proc.c (ffffffff814b58f0)
Location: crypto/proc.c:20
Inline: False
```
**Symbols:**

```
ffffffff81049220-ffffffff81049266: c_start (STB_LOCAL)
ffffffff81371250-ffffffff8137128a: c_start (STB_LOCAL)
ffffffff814b58f0-ffffffff814b591b: c_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision ⚠️</summary>

```c
void *c_start(struct seq_file *m, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/proc.c (ffffffff8104a630)
Location: arch/x86/kernel/cpu/proc.c:144
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/proc.c:c_next
```
```
In fs/proc/consoles.c (ffffffff81384c30)
Location: fs/proc/consoles.c:61
Inline: False
```
```
In crypto/proc.c (ffffffff814ce390)
Location: crypto/proc.c:20
Inline: False
```
**Symbols:**

```
ffffffff8104a630-ffffffff8104a676: c_start (STB_LOCAL)
ffffffff81384c30-ffffffff81384c6a: c_start (STB_LOCAL)
ffffffff814ce390-ffffffff814ce3bb: c_start (STB_LOCAL)
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
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
