# Function: <code>fixup_umip_exception</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool fixup_umip_exception(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/umip.c (ffffffff8106cf90)
Location: arch/x86/kernel/umip.c:313
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_general_protection
```
**Symbols:**

```
ffffffff8106cf90-ffffffff8106d41d: fixup_umip_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
bool fixup_umip_exception(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/umip.c (0)
Location: arch/x86/kernel/umip.c:314
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_general_protection
```
**Symbols:**

```
ffffffff810703be-ffffffff810703ca: fixup_umip_exception.cold.3 (STB_LOCAL)
ffffffff8106fed0-ffffffff8107035f: fixup_umip_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
bool fixup_umip_exception(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/umip.c (0)
Location: arch/x86/kernel/umip.c:308
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_general_protection
```
**Symbols:**

```
ffffffff81076394-ffffffff810763a0: fixup_umip_exception.cold.3 (STB_LOCAL)
ffffffff81075e30-ffffffff81076335: fixup_umip_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
bool fixup_umip_exception(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/umip.c (0)
Location: arch/x86/kernel/umip.c:308
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_general_protection
```
**Symbols:**

```
ffffffff81079f4b-ffffffff81079f57: fixup_umip_exception.cold (STB_LOCAL)
ffffffff81079a30-ffffffff81079eed: fixup_umip_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
bool fixup_umip_exception(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/umip.c (0)
Location: arch/x86/kernel/umip.c:318
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_general_protection
```
**Symbols:**

```
ffffffff8107b03c-ffffffff8107b048: fixup_umip_exception.cold (STB_LOCAL)
ffffffff8107aa80-ffffffff8107afde: fixup_umip_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
bool fixup_umip_exception(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/umip.c (0)
Location: arch/x86/kernel/umip.c:318
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_general_protection
```
**Symbols:**

```
ffffffff8108244a-ffffffff81082456: fixup_umip_exception.cold (STB_LOCAL)
ffffffff81081e90-ffffffff810823ec: fixup_umip_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
bool fixup_umip_exception(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/umip.c (0)
Location: arch/x86/kernel/umip.c:336
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_general_protection
```
**Symbols:**

```
ffffffff81bd835f-ffffffff81bd836b: fixup_umip_exception.cold (STB_LOCAL)
ffffffff81081c10-ffffffff81081f07: fixup_umip_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
bool fixup_umip_exception(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/umip.c (0)
Location: arch/x86/kernel/umip.c:336
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_general_protection
```
**Symbols:**

```
ffffffff81bca19c-ffffffff81bca1a8: fixup_umip_exception.cold (STB_LOCAL)
ffffffff81082a30-ffffffff81082d27: fixup_umip_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool fixup_umip_exception(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/umip.c (0)
Location: arch/x86/kernel/umip.c:336
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_general_protection
```
**Symbols:**

```
ffffffff81c9f503-ffffffff81c9f50f: fixup_umip_exception.cold (STB_LOCAL)
ffffffff81091af0-ffffffff81091df0: fixup_umip_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool fixup_umip_exception(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/umip.c (0)
Location: arch/x86/kernel/umip.c:336
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_general_protection
```
**Symbols:**

```
ffffffff81e4ecae-ffffffff81e4ecba: fixup_umip_exception.cold (STB_LOCAL)
ffffffff810a2ce0-ffffffff810a2ffe: fixup_umip_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool fixup_umip_exception(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/umip.c (ffffffff810bafb0)
Location: arch/x86/kernel/umip.c:336
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_general_protection
```
**Symbols:**

```
ffffffff810bafb0-ffffffff810bb2da: fixup_umip_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool fixup_umip_exception(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/umip.c (ffffffff810be0f0)
Location: arch/x86/kernel/umip.c:336
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_general_protection
```
**Symbols:**

```
ffffffff810be0f0-ffffffff810be417: fixup_umip_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool fixup_umip_exception(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/umip.c (ffffffff810c5270)
Location: arch/x86/kernel/umip.c:336
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_general_protection
```
**Symbols:**

```
ffffffff810c5270-ffffffff810c5597: fixup_umip_exception (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
bool fixup_umip_exception(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/umip.c (0)
Location: arch/x86/kernel/umip.c:318
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_general_protection
```
**Symbols:**

```
ffffffff8107a03c-ffffffff8107a048: fixup_umip_exception.cold (STB_LOCAL)
ffffffff81079a80-ffffffff81079fde: fixup_umip_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
bool fixup_umip_exception(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/umip.c (0)
Location: arch/x86/kernel/umip.c:318
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_general_protection
```
**Symbols:**

```
ffffffff81069771-ffffffff8106977d: fixup_umip_exception.cold (STB_LOCAL)
ffffffff810691f0-ffffffff81069713: fixup_umip_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
bool fixup_umip_exception(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/umip.c (0)
Location: arch/x86/kernel/umip.c:318
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_general_protection
```
**Symbols:**

```
ffffffff81079fec-ffffffff81079ff8: fixup_umip_exception.cold (STB_LOCAL)
ffffffff81079a30-ffffffff81079f8e: fixup_umip_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
bool fixup_umip_exception(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/umip.c (0)
Location: arch/x86/kernel/umip.c:318
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_general_protection
```
**Symbols:**

```
ffffffff8107c0ec-ffffffff8107c0f8: fixup_umip_exception.cold (STB_LOCAL)
ffffffff8107bb30-ffffffff8107c08e: fixup_umip_exception (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
