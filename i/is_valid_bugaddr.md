# Function: <code>is_valid_bugaddr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int is_valid_bugaddr(long unsigned int ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack_64.c (ffffffff81031790)
Location: arch/x86/kernel/dumpstack_64.c:346
Inline: False
Direct callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff81031790-ffffffff810317b6: is_valid_bugaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int is_valid_bugaddr(long unsigned int ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack_64.c (ffffffff810308a0)
Location: arch/x86/kernel/dumpstack_64.c:354
Inline: False
Direct callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff810308a0-ffffffff810308c7: is_valid_bugaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int is_valid_bugaddr(long unsigned int ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack_64.c (ffffffff81030500)
Location: arch/x86/kernel/dumpstack_64.c:181
Inline: False
Direct callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff81030500-ffffffff81030527: is_valid_bugaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int is_valid_bugaddr(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8102c850)
Location: arch/x86/kernel/traps.c:172
Inline: False
Direct callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff8102c850-ffffffff8102c8c4: is_valid_bugaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int is_valid_bugaddr(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8102d9c0)
Location: arch/x86/kernel/traps.c:160
Inline: False
Direct callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff8102d9c0-ffffffff8102da34: is_valid_bugaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int is_valid_bugaddr(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8102e980)
Location: arch/x86/kernel/traps.c:160
Inline: False
Direct callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff8102e980-ffffffff8102e9f4: is_valid_bugaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int is_valid_bugaddr(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8102fb60)
Location: arch/x86/kernel/traps.c:160
Inline: False
Direct callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff8102fb60-ffffffff8102fbd4: is_valid_bugaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int is_valid_bugaddr(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81031930)
Location: arch/x86/kernel/traps.c:161
Inline: False
Direct callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff81031930-ffffffff810319a4: is_valid_bugaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int is_valid_bugaddr(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff810321f0)
Location: arch/x86/kernel/traps.c:161
Inline: False
Direct callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff810321f0-ffffffff81032264: is_valid_bugaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int is_valid_bugaddr(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81bbcb4f)
Location: arch/x86/kernel/traps.c:87
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:handle_bug
Direct callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff810346c0-ffffffff810346f9: is_valid_bugaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int is_valid_bugaddr(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81c3513f)
Location: arch/x86/kernel/traps.c:88
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:handle_bug
Direct callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff81034fb0-ffffffff81034fe9: is_valid_bugaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int is_valid_bugaddr(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81c275df)
Location: arch/x86/kernel/traps.c:88
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:handle_bug
Direct callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff81036a10-ffffffff81036a2c: is_valid_bugaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int is_valid_bugaddr(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81d4562f)
Location: arch/x86/kernel/traps.c:88
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:handle_bug
Direct callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff8103bcb0-ffffffff8103bccc: is_valid_bugaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int is_valid_bugaddr(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81f1382f)
Location: arch/x86/kernel/traps.c:90
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:handle_bug
Direct callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff81042cf0-ffffffff81042d14: is_valid_bugaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int is_valid_bugaddr(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff820ba9ef)
Location: arch/x86/kernel/traps.c:92
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:handle_bug
Direct callers:
  - lib/bug.c:report_bug
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff8104c750-ffffffff8104c774: is_valid_bugaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int is_valid_bugaddr(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8213c0ff)
Location: arch/x86/kernel/traps.c:92
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:handle_bug
Direct callers:
  - lib/bug.c:report_bug
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff8104cfc0-ffffffff8104cfe4: is_valid_bugaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int is_valid_bugaddr(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8221e0ff)
Location: arch/x86/kernel/traps.c:81
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:handle_bug
Direct callers:
  - lib/bug.c:report_bug
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff81054240-ffffffff81054264: is_valid_bugaddr (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int is_valid_bugaddr(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/traps.c (ffff800010095890)
Location: arch/arm64/kernel/traps.c:935
Inline: False
Direct callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffff800010095890-ffff8000100958ac: is_valid_bugaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int is_valid_bugaddr(long unsigned int pc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/traps.c (c030f8a0)
Location: arch/arm/kernel/traps.c:380
Inline: False
Direct callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
c030f8a0-c030f920: is_valid_bugaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int is_valid_bugaddr(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/traps.c (c00000000002e940)
Location: arch/powerpc/kernel/traps.c:1424
Inline: False
Direct callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
c00000000002e940-c00000000002e970: is_valid_bugaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int is_valid_bugaddr(long unsigned int pc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/riscv/kernel/traps.c (ffffffe0000b7116)
Location: arch/riscv/kernel/traps.c:135
Inline: False
Direct callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffe0000b7116-ffffffe0000b7190: is_valid_bugaddr (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int is_valid_bugaddr(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81032350)
Location: arch/x86/kernel/traps.c:161
Inline: False
Direct callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff81032350-ffffffff810323c4: is_valid_bugaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int is_valid_bugaddr(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81021cb0)
Location: arch/x86/kernel/traps.c:161
Inline: False
Direct callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff81021cb0-ffffffff81021d24: is_valid_bugaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int is_valid_bugaddr(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff810321b0)
Location: arch/x86/kernel/traps.c:161
Inline: False
Direct callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff810321b0-ffffffff81032224: is_valid_bugaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int is_valid_bugaddr(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff810330f0)
Location: arch/x86/kernel/traps.c:161
Inline: False
Direct callers:
  - lib/bug.c:report_bug
```
**Symbols:**

```
ffffffff810330f0-ffffffff81033164: is_valid_bugaddr (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int addr</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int ip</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>amd64</code> and <code>armhf</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int pc</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int addr</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>riscv64</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int pc</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int addr</code>
</li>
</ul>
</details>
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
