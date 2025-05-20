# Function: <code>paravirt_patch_jmp</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
unsigned int paravirt_patch_jmp(void *insnbuf, const void *target, long unsigned int addr, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81064bb0)
Location: arch/x86/kernel/paravirt.c:112
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_patch_default
```
**Symbols:**

```
ffffffff81064bb0-ffffffff81064bd4: paravirt_patch_jmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int paravirt_patch_jmp(void *insnbuf, const void *target, long unsigned int addr, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81064a23)
Location: arch/x86/kernel/paravirt.c:103
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_patch_default
```
**Symbols:**

```
ffffffff81064950-ffffffff81064974: paravirt_patch_jmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
unsigned int paravirt_patch_jmp(void *insnbuf, const void *target, long unsigned int addr, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81067ef3)
Location: arch/x86/kernel/paravirt.c:103
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_patch_default
```
**Symbols:**

```
ffffffff81067e20-ffffffff81067e44: paravirt_patch_jmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
unsigned int paravirt_patch_jmp(void *insnbuf, const void *target, long unsigned int addr, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8106725e)
Location: arch/x86/kernel/paravirt.c:103
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_patch_default
```
**Symbols:**

```
ffffffff81067170-ffffffff81067196: paravirt_patch_jmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
unsigned int paravirt_patch_jmp(void *insnbuf, const void *target, long unsigned int addr, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8106b49e)
Location: arch/x86/kernel/paravirt.c:103
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_patch_default
```
**Symbols:**

```
ffffffff8106b3b0-ffffffff8106b3d6: paravirt_patch_jmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
unsigned int paravirt_patch_jmp(void *insnbuf, const void *target, long unsigned int addr, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8106e194)
Location: arch/x86/kernel/paravirt.c:105
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_patch_default
Direct callers:
  - arch/x86/kernel/paravirt.c:paravirt_patch_default
```
**Symbols:**

```
ffffffff8106df20-ffffffff8106df4f: paravirt_patch_jmp.part.9 (STB_LOCAL)
ffffffff8106e070-ffffffff8106e09d: paravirt_patch_jmp (STB_GLOBAL)
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
In arch/x86/kernel/paravirt.c (ffffffff81074142)
Location: arch/x86/kernel/paravirt.c:100
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
In arch/x86/kernel/paravirt.c (ffffffff81077c99)
Location: arch/x86/kernel/paravirt.c:88
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
In arch/x86/kernel/paravirt.c (ffffffff81078d09)
Location: arch/x86/kernel/paravirt.c:88
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
In arch/x86/kernel/paravirt.c (ffffffff8107fff9)
Location: arch/x86/kernel/paravirt.c:89
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
In arch/x86/kernel/paravirt.c (ffffffff8107fc19)
Location: arch/x86/kernel/paravirt.c:89
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_patch_default
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81077d09)
Location: arch/x86/kernel/paravirt.c:88
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_patch_default
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81077cb9)
Location: arch/x86/kernel/paravirt.c:88
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
In arch/x86/kernel/paravirt.c (ffffffff81079d79)
Location: arch/x86/kernel/paravirt.c:88
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
