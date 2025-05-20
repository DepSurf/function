# Function: <code>paravirt_patch_insns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
unsigned int paravirt_patch_insns(void *insnbuf, unsigned int len, const char *start, const char *end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81064c94)
Location: arch/x86/kernel/paravirt.c:181
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_patch_default
Direct callers:
  - arch/x86/xen/enlighten.c:xen_patch
  - arch/x86/kernel/paravirt_patch_64.c:paravirt_patch_ident_32
  - arch/x86/kernel/paravirt_patch_64.c:paravirt_patch_ident_64
  - arch/x86/kernel/paravirt_patch_64.c:native_patch
```
**Symbols:**

```
ffffffff81064ce0-ffffffff81064d0a: paravirt_patch_insns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int paravirt_patch_insns(void *insnbuf, unsigned int len, const char *start, const char *end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81064a4b)
Location: arch/x86/kernel/paravirt.c:166
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_patch_default
Direct callers:
  - arch/x86/xen/enlighten.c:xen_patch
  - arch/x86/kernel/paravirt_patch_64.c:native_patch
  - arch/x86/kernel/paravirt_patch_64.c:paravirt_patch_ident_64
  - arch/x86/kernel/paravirt_patch_64.c:paravirt_patch_ident_32
```
**Symbols:**

```
ffffffff81064a90-ffffffff81064aba: paravirt_patch_insns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
unsigned int paravirt_patch_insns(void *insnbuf, unsigned int len, const char *start, const char *end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81067f1b)
Location: arch/x86/kernel/paravirt.c:166
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_patch_default
Direct callers:
  - arch/x86/xen/enlighten.c:xen_patch
  - arch/x86/kernel/paravirt_patch_64.c:native_patch
  - arch/x86/kernel/paravirt_patch_64.c:paravirt_patch_ident_64
  - arch/x86/kernel/paravirt_patch_64.c:paravirt_patch_ident_32
```
**Symbols:**

```
ffffffff81067f60-ffffffff81067f8a: paravirt_patch_insns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned int paravirt_patch_insns(void *insnbuf, unsigned int len, const char *start, const char *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810671a0)
Location: arch/x86/kernel/paravirt.c:166
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_patch
  - arch/x86/kernel/paravirt.c:paravirt_patch_default
  - arch/x86/kernel/paravirt_patch_64.c:native_patch
  - arch/x86/kernel/paravirt_patch_64.c:paravirt_patch_ident_64
  - arch/x86/kernel/paravirt_patch_64.c:paravirt_patch_ident_32
```
**Symbols:**

```
ffffffff810671a0-ffffffff810671ce: paravirt_patch_insns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int paravirt_patch_insns(void *insnbuf, unsigned int len, const char *start, const char *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8106b3e0)
Location: arch/x86/kernel/paravirt.c:176
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt.c:paravirt_patch_default
  - arch/x86/kernel/paravirt_patch_64.c:native_patch
  - arch/x86/kernel/paravirt_patch_64.c:paravirt_patch_ident_64
  - arch/x86/kernel/paravirt_patch_64.c:paravirt_patch_ident_32
```
**Symbols:**

```
ffffffff8106b3e0-ffffffff8106b40e: paravirt_patch_insns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned int paravirt_patch_insns(void *insnbuf, unsigned int len, const char *start, const char *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8106e0a0)
Location: arch/x86/kernel/paravirt.c:182
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt.c:paravirt_patch_default
  - arch/x86/kernel/paravirt_patch_64.c:native_patch
  - arch/x86/kernel/paravirt_patch_64.c:paravirt_patch_ident_64
  - arch/x86/kernel/paravirt_patch_64.c:paravirt_patch_ident_32
```
**Symbols:**

```
ffffffff8106e0a0-ffffffff8106e0cb: paravirt_patch_insns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int paravirt_patch_insns(void *insnbuf, unsigned int len, const char *start, const char *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81074080)
Location: arch/x86/kernel/paravirt.c:161
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt.c:paravirt_patch_default
  - arch/x86/kernel/paravirt_patch_64.c:native_patch
  - arch/x86/kernel/paravirt_patch_64.c:native_patch
  - arch/x86/kernel/paravirt_patch_64.c:native_patch
  - arch/x86/kernel/paravirt_patch_64.c:native_patch
  - arch/x86/kernel/paravirt_patch_64.c:native_patch
  - arch/x86/kernel/paravirt_patch_64.c:native_patch
  - arch/x86/kernel/paravirt_patch_64.c:native_patch
  - arch/x86/kernel/paravirt_patch_64.c:native_patch
  - arch/x86/kernel/paravirt_patch_64.c:native_patch
  - arch/x86/kernel/paravirt_patch_64.c:native_patch
  - arch/x86/kernel/paravirt_patch_64.c:native_patch
  - arch/x86/kernel/paravirt_patch_64.c:native_patch
  - arch/x86/kernel/paravirt_patch_64.c:paravirt_patch_ident_64
```
**Symbols:**

```
ffffffff81074080-ffffffff810740ab: paravirt_patch_insns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
unsigned int paravirt_patch_insns(void *insn_buff, unsigned int len, const char *start, const char *end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81077c00)
Location: arch/x86/kernel/paravirt.c:149
Inline: True
Direct callers:
  - arch/x86/kernel/paravirt.c:paravirt_patch_default
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:paravirt_patch_ident_64
```
**Symbols:**

```
ffffffff81077c00-ffffffff81077c2a: paravirt_patch_insns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
unsigned int paravirt_patch_insns(void *insn_buff, unsigned int len, const char *start, const char *end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81078c70)
Location: arch/x86/kernel/paravirt.c:149
Inline: True
Direct callers:
  - arch/x86/kernel/paravirt.c:paravirt_patch_default
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:paravirt_patch_ident_64
```
**Symbols:**

```
ffffffff81078c70-ffffffff81078c9a: paravirt_patch_insns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int paravirt_patch_insns(void *insn_buff, unsigned int len, const char *start, const char *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8107ff60)
Location: arch/x86/kernel/paravirt.c:150
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt.c:paravirt_patch_default
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:paravirt_patch_ident_64
```
**Symbols:**

```
ffffffff8107ff60-ffffffff8107ff8d: paravirt_patch_insns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int paravirt_patch_insns(void *insn_buff, unsigned int len, const char *start, const char *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8107fb80)
Location: arch/x86/kernel/paravirt.c:150
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt.c:paravirt_patch_default
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:paravirt_patch_ident_64
```
**Symbols:**

```
ffffffff8107fb80-ffffffff8107fbad: paravirt_patch_insns (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
unsigned int paravirt_patch_insns(void *insn_buff, unsigned int len, const char *start, const char *end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81077c70)
Location: arch/x86/kernel/paravirt.c:149
Inline: True
Direct callers:
  - arch/x86/kernel/paravirt.c:paravirt_patch_default
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:paravirt_patch_ident_64
```
**Symbols:**

```
ffffffff81077c70-ffffffff81077c9a: paravirt_patch_insns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
unsigned int paravirt_patch_insns(void *insn_buff, unsigned int len, const char *start, const char *end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810677e0)
Location: arch/x86/kernel/paravirt.c:149
Inline: True
Direct callers:
  - arch/x86/kernel/paravirt.c:paravirt_patch_default
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
```
**Symbols:**

```
ffffffff810677e0-ffffffff8106780a: paravirt_patch_insns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
unsigned int paravirt_patch_insns(void *insn_buff, unsigned int len, const char *start, const char *end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81077c20)
Location: arch/x86/kernel/paravirt.c:149
Inline: True
Direct callers:
  - arch/x86/kernel/paravirt.c:paravirt_patch_default
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:paravirt_patch_ident_64
```
**Symbols:**

```
ffffffff81077c20-ffffffff81077c4a: paravirt_patch_insns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
unsigned int paravirt_patch_insns(void *insn_buff, unsigned int len, const char *start, const char *end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81079ce0)
Location: arch/x86/kernel/paravirt.c:149
Inline: True
Direct callers:
  - arch/x86/kernel/paravirt.c:paravirt_patch_default
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:native_patch
  - arch/x86/kernel/paravirt_patch.c:paravirt_patch_ident_64
```
**Symbols:**

```
ffffffff81079ce0-ffffffff81079d0a: paravirt_patch_insns (STB_GLOBAL)
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
