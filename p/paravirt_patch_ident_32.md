# Function: <code>paravirt_patch_ident_32</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
unsigned int paravirt_patch_ident_32(void *insnbuf, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt_patch_64.c (ffffffff81064ed0)
Location: arch/x86/kernel/paravirt_patch_64.c:28
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt.c:paravirt_patch_default
```
**Symbols:**

```
ffffffff81064ed0-ffffffff81064eee: paravirt_patch_ident_32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
unsigned int paravirt_patch_ident_32(void *insnbuf, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt_patch_64.c (ffffffff81064c70)
Location: arch/x86/kernel/paravirt_patch_64.c:26
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt.c:paravirt_patch_default
```
**Symbols:**

```
ffffffff81064c70-ffffffff81064c8e: paravirt_patch_ident_32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned int paravirt_patch_ident_32(void *insnbuf, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt_patch_64.c (ffffffff81068140)
Location: arch/x86/kernel/paravirt_patch_64.c:26
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt.c:paravirt_patch_default
```
**Symbols:**

```
ffffffff81068140-ffffffff8106815e: paravirt_patch_ident_32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned int paravirt_patch_ident_32(void *insnbuf, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt_patch_64.c (ffffffff81067460)
Location: arch/x86/kernel/paravirt_patch_64.c:26
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt.c:paravirt_patch_default
```
**Symbols:**

```
ffffffff81067460-ffffffff8106747e: paravirt_patch_ident_32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int paravirt_patch_ident_32(void *insnbuf, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt_patch_64.c (ffffffff8106b6b0)
Location: arch/x86/kernel/paravirt_patch_64.c:26
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt.c:paravirt_patch_default
```
**Symbols:**

```
ffffffff8106b6b0-ffffffff8106b6ce: paravirt_patch_ident_32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned int paravirt_patch_ident_32(void *insnbuf, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt_patch_64.c (ffffffff8106e380)
Location: arch/x86/kernel/paravirt_patch_64.c:26
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt.c:paravirt_patch_default
```
**Symbols:**

```
ffffffff8106e380-ffffffff8106e39e: paravirt_patch_ident_32 (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
