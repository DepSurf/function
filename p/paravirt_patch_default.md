# Function: <code>paravirt_patch_default</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
unsigned int paravirt_patch_default(u8 type, u16 clobbers, void *insnbuf, long unsigned int addr, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81064be0)
Location: arch/x86/kernel/paravirt.c:145
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_patch
  - arch/x86/kernel/paravirt_patch_64.c:native_patch
  - arch/x86/kernel/vsmp_64.c:vsmp_patch
```
**Symbols:**

```
ffffffff81064be0-ffffffff81064cd3: paravirt_patch_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
unsigned int paravirt_patch_default(u8 type, u16 clobbers, void *insnbuf, long unsigned int addr, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81064980)
Location: arch/x86/kernel/paravirt.c:135
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_patch
  - arch/x86/kernel/paravirt_patch_64.c:native_patch
  - arch/x86/kernel/vsmp_64.c:vsmp_patch
```
**Symbols:**

```
ffffffff81064980-ffffffff81064a88: paravirt_patch_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned int paravirt_patch_default(u8 type, u16 clobbers, void *insnbuf, long unsigned int addr, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81067e50)
Location: arch/x86/kernel/paravirt.c:135
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_patch
  - arch/x86/kernel/paravirt_patch_64.c:native_patch
  - arch/x86/kernel/vsmp_64.c:vsmp_patch
```
**Symbols:**

```
ffffffff81067e50-ffffffff81067f58: paravirt_patch_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned int paravirt_patch_default(u8 type, u16 clobbers, void *insnbuf, long unsigned int addr, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810671d0)
Location: arch/x86/kernel/paravirt.c:135
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_patch
  - arch/x86/kernel/paravirt_patch_64.c:native_patch
  - arch/x86/kernel/vsmp_64.c:vsmp_patch
```
**Symbols:**

```
ffffffff810671d0-ffffffff810672b8: paravirt_patch_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int paravirt_patch_default(u8 type, u16 clobbers, void *insnbuf, long unsigned int addr, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8106b410)
Location: arch/x86/kernel/paravirt.c:145
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt_patch_64.c:native_patch
  - arch/x86/kernel/vsmp_64.c:vsmp_patch
```
**Symbols:**

```
ffffffff8106b410-ffffffff8106b4f8: paravirt_patch_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned int paravirt_patch_default(u8 type, u16 clobbers, void *insnbuf, long unsigned int addr, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8106e0d0)
Location: arch/x86/kernel/paravirt.c:151
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt_patch_64.c:native_patch
  - arch/x86/kernel/vsmp_64.c:vsmp_patch
```
**Symbols:**

```
ffffffff8106e0d0-ffffffff8106e1c8: paravirt_patch_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int paravirt_patch_default(u8 type, void *insnbuf, long unsigned int addr, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810740b0)
Location: arch/x86/kernel/paravirt.c:128
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt_patch_64.c:native_patch
```
**Symbols:**

```
ffffffff810740b0-ffffffff81074199: paravirt_patch_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
unsigned int paravirt_patch_default(u8 type, void *insn_buff, long unsigned int addr, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/paravirt.c (0)
Location: arch/x86/kernel/paravirt.c:116
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt_patch.c:native_patch
```
**Symbols:**

```
ffffffff81077e65-ffffffff81077e76: paravirt_patch_default.cold (STB_LOCAL)
ffffffff81077c30-ffffffff81077cf0: paravirt_patch_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
unsigned int paravirt_patch_default(u8 type, void *insn_buff, long unsigned int addr, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/paravirt.c (0)
Location: arch/x86/kernel/paravirt.c:116
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt_patch.c:native_patch
```
**Symbols:**

```
ffffffff81078ed5-ffffffff81078ee6: paravirt_patch_default.cold (STB_LOCAL)
ffffffff81078ca0-ffffffff81078d60: paravirt_patch_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
unsigned int paravirt_patch_default(u8 type, void *insn_buff, long unsigned int addr, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/paravirt.c (0)
Location: arch/x86/kernel/paravirt.c:117
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt_patch.c:native_patch
```
**Symbols:**

```
ffffffff810801c5-ffffffff810801d6: paravirt_patch_default.cold (STB_LOCAL)
ffffffff8107ff90-ffffffff81080050: paravirt_patch_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
unsigned int paravirt_patch_default(u8 type, void *insn_buff, long unsigned int addr, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/paravirt.c (0)
Location: arch/x86/kernel/paravirt.c:117
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt_patch.c:native_patch
```
**Symbols:**

```
ffffffff81bd814a-ffffffff81bd815b: paravirt_patch_default.cold (STB_LOCAL)
ffffffff8107fbb0-ffffffff8107fc70: paravirt_patch_default (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
unsigned int paravirt_patch_default(u8 type, void *insn_buff, long unsigned int addr, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/paravirt.c (0)
Location: arch/x86/kernel/paravirt.c:116
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt_patch.c:native_patch
```
**Symbols:**

```
ffffffff81077ed5-ffffffff81077ee6: paravirt_patch_default.cold (STB_LOCAL)
ffffffff81077ca0-ffffffff81077d60: paravirt_patch_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
unsigned int paravirt_patch_default(u8 type, void *insn_buff, long unsigned int addr, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/paravirt.c (0)
Location: arch/x86/kernel/paravirt.c:116
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt_patch.c:native_patch
```
**Symbols:**

```
ffffffff81067935-ffffffff81067946: paravirt_patch_default.cold (STB_LOCAL)
ffffffff81067810-ffffffff81067870: paravirt_patch_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
unsigned int paravirt_patch_default(u8 type, void *insn_buff, long unsigned int addr, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/paravirt.c (0)
Location: arch/x86/kernel/paravirt.c:116
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt_patch.c:native_patch
```
**Symbols:**

```
ffffffff81077e85-ffffffff81077e96: paravirt_patch_default.cold (STB_LOCAL)
ffffffff81077c50-ffffffff81077d10: paravirt_patch_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
unsigned int paravirt_patch_default(u8 type, void *insn_buff, long unsigned int addr, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/paravirt.c (0)
Location: arch/x86/kernel/paravirt.c:116
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt_patch.c:native_patch
```
**Symbols:**

```
ffffffff81079f85-ffffffff81079f96: paravirt_patch_default.cold (STB_LOCAL)
ffffffff81079d10-ffffffff81079dd0: paravirt_patch_default (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>u16 clobbers</code>
</li>
<li>
<b>Param reordered. </b>
<code>type, clobbers, insnbuf, addr, len</code> ➡️ <code>type, insnbuf, addr, len</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>void *insn_buff</code>
</li>
<li>
<b>Param removed. </b>
<code>void *insnbuf</code>
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
