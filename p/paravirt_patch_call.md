# Function: <code>paravirt_patch_call</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
unsigned int paravirt_patch_call(void *insnbuf, const void *target, u16 tgt_clobbers, long unsigned int addr, u16 site_clobbers, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81064b70)
Location: arch/x86/kernel/paravirt.c:92
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_patch_default
```
**Symbols:**

```
ffffffff81064b70-ffffffff81064ba7: paravirt_patch_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int paravirt_patch_call(void *insnbuf, const void *target, u16 tgt_clobbers, long unsigned int addr, u16 site_clobbers, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810649e4)
Location: arch/x86/kernel/paravirt.c:83
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_patch_default
```
**Symbols:**

```
ffffffff81064910-ffffffff81064947: paravirt_patch_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
unsigned int paravirt_patch_call(void *insnbuf, const void *target, u16 tgt_clobbers, long unsigned int addr, u16 site_clobbers, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81067eb4)
Location: arch/x86/kernel/paravirt.c:83
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_patch_default
```
**Symbols:**

```
ffffffff81067de0-ffffffff81067e17: paravirt_patch_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
unsigned int paravirt_patch_call(void *insnbuf, const void *target, u16 tgt_clobbers, long unsigned int addr, u16 site_clobbers, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81067231)
Location: arch/x86/kernel/paravirt.c:83
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_patch_default
```
**Symbols:**

```
ffffffff81067130-ffffffff8106716b: paravirt_patch_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
unsigned int paravirt_patch_call(void *insnbuf, const void *target, u16 tgt_clobbers, long unsigned int addr, u16 site_clobbers, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8106b471)
Location: arch/x86/kernel/paravirt.c:83
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_patch_default
```
**Symbols:**

```
ffffffff8106b370-ffffffff8106b3ab: paravirt_patch_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
unsigned int paravirt_patch_call(void *insnbuf, const void *target, u16 tgt_clobbers, long unsigned int addr, u16 site_clobbers, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8106e12c)
Location: arch/x86/kernel/paravirt.c:83
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_patch_default
Direct callers:
  - arch/x86/kernel/paravirt.c:paravirt_patch_default
```
**Symbols:**

```
ffffffff8106def0-ffffffff8106df1f: paravirt_patch_call.part.8 (STB_LOCAL)
ffffffff8106e040-ffffffff8106e06f: paravirt_patch_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810740f9)
Location: arch/x86/kernel/paravirt.c:73
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_patch_default
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81077c73)
Location: arch/x86/kernel/paravirt.c:61
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_patch_default
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81078ce3)
Location: arch/x86/kernel/paravirt.c:61
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_patch_default
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8107ffd3)
Location: arch/x86/kernel/paravirt.c:62
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_patch_default
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8107fbf3)
Location: arch/x86/kernel/paravirt.c:62
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_patch_default
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81080cbe)
Location: arch/x86/kernel/paravirt.c:66
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_patch
  - arch/x86/kernel/paravirt.c:paravirt_patch
Direct callers:
  - arch/x86/kernel/paravirt.c:paravirt_patch
```
**Symbols:**

```
ffffffff81bc9f69-ffffffff81bc9f83: paravirt_patch_call.part.0 (STB_LOCAL)
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
In arch/x86/kernel/paravirt.c (ffffffff8108fc36)
Location: arch/x86/kernel/paravirt.c:66
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_patch
  - arch/x86/kernel/paravirt.c:paravirt_patch
  - arch/x86/kernel/paravirt.c:paravirt_patch
  - arch/x86/kernel/paravirt.c:paravirt_patch
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
In arch/x86/kernel/paravirt.c (ffffffff810a0a74)
Location: arch/x86/kernel/paravirt.c:74
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_patch
  - arch/x86/kernel/paravirt.c:paravirt_patch
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
In arch/x86/kernel/paravirt.c (ffffffff810b8784)
Location: arch/x86/kernel/paravirt.c:57
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_patch
  - arch/x86/kernel/paravirt.c:paravirt_patch
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
In arch/x86/kernel/paravirt.c (ffffffff810bb954)
Location: arch/x86/kernel/paravirt.c:58
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_patch
  - arch/x86/kernel/paravirt.c:paravirt_patch
```
</details>
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81077ce3)
Location: arch/x86/kernel/paravirt.c:61
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_patch_default
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8106783a)
Location: arch/x86/kernel/paravirt.c:61
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_patch_default
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81077c93)
Location: arch/x86/kernel/paravirt.c:61
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_patch_default
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81079d53)
Location: arch/x86/kernel/paravirt.c:61
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_patch_default
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
</ul>
