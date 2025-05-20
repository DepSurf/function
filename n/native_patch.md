# Function: <code>native_patch</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
unsigned int native_patch(u8 type, u16 clobbers, void *ibuf, long unsigned int addr, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt_patch_64.c (ffffffff81064f10)
Location: arch/x86/kernel/paravirt_patch_64.c:42
Inline: False
Direct callers:
  - arch/x86/kernel/vsmp_64.c:vsmp_patch
```
**Symbols:**

```
ffffffff81064f10-ffffffff8106507c: native_patch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
unsigned int native_patch(u8 type, u16 clobbers, void *ibuf, long unsigned int addr, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt_patch_64.c (ffffffff81064cb0)
Location: arch/x86/kernel/paravirt_patch_64.c:40
Inline: False
Direct callers:
  - arch/x86/kernel/vsmp_64.c:vsmp_patch
```
**Symbols:**

```
ffffffff81064cb0-ffffffff81064e09: native_patch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned int native_patch(u8 type, u16 clobbers, void *ibuf, long unsigned int addr, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt_patch_64.c (ffffffff81068180)
Location: arch/x86/kernel/paravirt_patch_64.c:41
Inline: False
Direct callers:
  - arch/x86/kernel/vsmp_64.c:vsmp_patch
```
**Symbols:**

```
ffffffff81068180-ffffffff810682eb: native_patch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned int native_patch(u8 type, u16 clobbers, void *ibuf, long unsigned int addr, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt_patch_64.c (ffffffff810674a0)
Location: arch/x86/kernel/paravirt_patch_64.c:41
Inline: False
Direct callers:
  - arch/x86/kernel/vsmp_64.c:vsmp_patch
```
**Symbols:**

```
ffffffff810674a0-ffffffff8106761d: native_patch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int native_patch(u8 type, u16 clobbers, void *ibuf, long unsigned int addr, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt_patch_64.c (ffffffff8106b6f0)
Location: arch/x86/kernel/paravirt_patch_64.c:41
Inline: False
Direct callers:
  - arch/x86/kernel/vsmp_64.c:vsmp_patch
```
**Symbols:**

```
ffffffff8106b6f0-ffffffff8106b863: native_patch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned int native_patch(u8 type, u16 clobbers, void *ibuf, long unsigned int addr, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt_patch_64.c (ffffffff8106e3c0)
Location: arch/x86/kernel/paravirt_patch_64.c:41
Inline: False
Direct callers:
  - arch/x86/kernel/vsmp_64.c:vsmp_patch
```
**Symbols:**

```
ffffffff8106e3c0-ffffffff8106e53d: native_patch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int native_patch(u8 type, void *ibuf, long unsigned int addr, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt_patch_64.c (ffffffff81074370)
Location: arch/x86/kernel/paravirt_patch_64.c:35
Inline: False
```
**Symbols:**

```
ffffffff81074370-ffffffff8107455e: native_patch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned int native_patch(u8 type, void *insn_buff, long unsigned int addr, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt_patch.c (ffffffff81077ea0)
Location: arch/x86/kernel/paravirt_patch.c:86
Inline: False
```
**Symbols:**

```
ffffffff81077ea0-ffffffff810780b4: native_patch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int native_patch(u8 type, void *insn_buff, long unsigned int addr, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt_patch.c (ffffffff81078f10)
Location: arch/x86/kernel/paravirt_patch.c:86
Inline: False
```
**Symbols:**

```
ffffffff81078f10-ffffffff81079124: native_patch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int native_patch(u8 type, void *insn_buff, long unsigned int addr, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt_patch.c (ffffffff81080200)
Location: arch/x86/kernel/paravirt_patch.c:86
Inline: False
```
**Symbols:**

```
ffffffff81080200-ffffffff81080410: native_patch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int native_patch(u8 type, void *insn_buff, long unsigned int addr, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt_patch.c (ffffffff8107fe10)
Location: arch/x86/kernel/paravirt_patch.c:73
Inline: False
```
**Symbols:**

```
ffffffff8107fe10-ffffffff81080020: native_patch (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
unsigned int native_patch(u8 type, void *insn_buff, long unsigned int addr, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt_patch.c (ffffffff81077f10)
Location: arch/x86/kernel/paravirt_patch.c:86
Inline: False
```
**Symbols:**

```
ffffffff81077f10-ffffffff81078124: native_patch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int native_patch(u8 type, void *insn_buff, long unsigned int addr, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt_patch.c (ffffffff81067950)
Location: arch/x86/kernel/paravirt_patch.c:86
Inline: False
```
**Symbols:**

```
ffffffff81067950-ffffffff810679dd: native_patch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int native_patch(u8 type, void *insn_buff, long unsigned int addr, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt_patch.c (ffffffff81077ec0)
Location: arch/x86/kernel/paravirt_patch.c:86
Inline: False
```
**Symbols:**

```
ffffffff81077ec0-ffffffff810780d4: native_patch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int native_patch(u8 type, void *insn_buff, long unsigned int addr, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt_patch.c (ffffffff81079fc0)
Location: arch/x86/kernel/paravirt_patch.c:86
Inline: False
```
**Symbols:**

```
ffffffff81079fc0-ffffffff8107a1d4: native_patch (STB_GLOBAL)
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
<code>type, clobbers, ibuf, addr, len</code> ➡️ <code>type, ibuf, addr, len</code>
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
<code>void *ibuf</code>
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
