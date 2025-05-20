# Function: <code>final_note</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff8110c5d4)
Location: kernel/kexec_core.c:968
Inline: True
Inline callers:
  - kernel/kexec_core.c:update_vmcoreinfo_note
  - kernel/kexec_core.c:crash_save_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff81113e44)
Location: kernel/kexec_core.c:1015
Inline: True
Inline callers:
  - kernel/kexec_core.c:update_vmcoreinfo_note
  - kernel/kexec_core.c:crash_save_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff8111b554)
Location: kernel/kexec_core.c:1017
Inline: True
Inline callers:
  - kernel/kexec_core.c:update_vmcoreinfo_note
  - kernel/kexec_core.c:crash_save_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void final_note(Elf64_Word *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff8111d030)
Location: kernel/crash_core.c:313
Inline: False
Direct callers:
  - kernel/crash_core.c:update_vmcoreinfo_note
  - kernel/kexec_core.c:crash_save_cpu
```
**Symbols:**

```
ffffffff8111d030-ffffffff8111d049: final_note (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void final_note(Elf64_Word *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff81128720)
Location: kernel/crash_core.c:314
Inline: False
Direct callers:
  - kernel/crash_core.c:update_vmcoreinfo_note
  - kernel/kexec_core.c:crash_save_cpu
```
**Symbols:**

```
ffffffff81128720-ffffffff81128739: final_note (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void final_note(Elf64_Word *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff811366b0)
Location: kernel/crash_core.c:314
Inline: False
Direct callers:
  - kernel/crash_core.c:update_vmcoreinfo_note
  - kernel/kexec_core.c:crash_save_cpu
```
**Symbols:**

```
ffffffff811366b0-ffffffff811366c9: final_note (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void final_note(Elf64_Word *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff81141e40)
Location: kernel/crash_core.c:314
Inline: False
Direct callers:
  - kernel/crash_core.c:update_vmcoreinfo_note
  - kernel/kexec_core.c:crash_save_cpu
```
**Symbols:**

```
ffffffff81141e40-ffffffff81141e59: final_note (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void final_note(Elf64_Word *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff8114d1f0)
Location: kernel/crash_core.c:312
Inline: False
Direct callers:
  - kernel/crash_core.c:update_vmcoreinfo_note
  - kernel/kexec_core.c:crash_save_cpu
```
**Symbols:**

```
ffffffff8114d1f0-ffffffff8114d209: final_note (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void final_note(Elf64_Word *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff81158ec0)
Location: kernel/crash_core.c:312
Inline: False
Direct callers:
  - kernel/crash_core.c:update_vmcoreinfo_note
  - kernel/kexec_core.c:crash_save_cpu
```
**Symbols:**

```
ffffffff81158ec0-ffffffff81158ed9: final_note (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void final_note(Elf64_Word *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff81169ac2)
Location: kernel/crash_core.c:312
Inline: True
Inline callers:
  - kernel/crash_core.c:update_vmcoreinfo_note
Direct callers:
  - kernel/kexec_core.c:crash_save_cpu
```
**Symbols:**

```
ffffffff81169ae0-ffffffff81169af9: final_note (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void final_note(Elf64_Word *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff81166212)
Location: kernel/crash_core.c:314
Inline: True
Inline callers:
  - kernel/crash_core.c:update_vmcoreinfo_note
Direct callers:
  - kernel/kexec_core.c:crash_save_cpu
```
**Symbols:**

```
ffffffff81166230-ffffffff81166249: final_note (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void final_note(Elf64_Word *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff81166fb2)
Location: kernel/crash_core.c:314
Inline: True
Inline callers:
  - kernel/crash_core.c:update_vmcoreinfo_note
Direct callers:
  - kernel/kexec_core.c:crash_save_cpu
```
**Symbols:**

```
ffffffff81166fd0-ffffffff81166fe9: final_note (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void final_note(Elf64_Word *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff8118c772)
Location: kernel/crash_core.c:326
Inline: True
Inline callers:
  - kernel/crash_core.c:update_vmcoreinfo_note
Direct callers:
  - kernel/kexec_core.c:crash_save_cpu
```
**Symbols:**

```
ffffffff8118c790-ffffffff8118c7a9: final_note (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void final_note(Elf64_Word *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff811bbbd0)
Location: kernel/crash_core.c:322
Inline: True
Direct callers:
  - kernel/crash_core.c:crash_save_vmcoreinfo
  - kernel/kexec_core.c:crash_save_cpu
```
**Symbols:**

```
ffffffff811bbbd0-ffffffff811bbbef: final_note (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void final_note(Elf64_Word *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff811fda90)
Location: kernel/crash_core.c:334
Inline: False
Direct callers:
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo
  - kernel/kexec_core.c:crash_save_cpu
```
**Symbols:**

```
ffffffff811fda90-ffffffff811fdaaf: final_note (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void final_note(Elf64_Word *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff81212c10)
Location: kernel/crash_core.c:334
Inline: False
Direct callers:
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo
  - kernel/kexec_core.c:crash_save_cpu
```
**Symbols:**

```
ffffffff81212c10-ffffffff81212c2f: final_note (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void final_note(Elf64_Word *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff8122aa70)
Location: kernel/crash_core.c:653
Inline: False
Direct callers:
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo
  - kernel/kexec_core.c:crash_save_cpu
```
**Symbols:**

```
ffffffff8122aa70-ffffffff8122aa8f: final_note (STB_GLOBAL)
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
void final_note(Elf64_Word *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffff8000101c84b0)
Location: kernel/crash_core.c:312
Inline: False
Direct callers:
  - kernel/crash_core.c:update_vmcoreinfo_note
  - kernel/kexec_core.c:crash_save_cpu
```
**Symbols:**

```
ffff8000101c84b0-ffff8000101c84dc: final_note (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void final_note(Elf32_Word *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (c040f414)
Location: kernel/crash_core.c:312
Inline: False
Direct callers:
  - kernel/crash_core.c:update_vmcoreinfo_note
  - kernel/kexec_core.c:crash_save_cpu
```
**Symbols:**

```
c040f414-c040f43c: final_note (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void final_note(Elf64_Word *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (c000000000230af0)
Location: kernel/crash_core.c:312
Inline: False
Direct callers:
  - arch/powerpc/platforms/powernv/opal-fadump.c:opal_fadump_build_cpu_notes
  - kernel/crash_core.c:update_vmcoreinfo_note
  - kernel/kexec_core.c:crash_save_cpu
```
**Symbols:**

```
c000000000230af0-c000000000230b08: final_note (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void final_note(Elf64_Word *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffe00014837a)
Location: kernel/crash_core.c:312
Inline: True
Inline callers:
  - kernel/crash_core.c:update_vmcoreinfo_note
```
**Symbols:**

```
ffffffe0001483b2-ffffffe000148402: final_note (STB_GLOBAL)
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
void final_note(Elf64_Word *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff811514e0)
Location: kernel/crash_core.c:312
Inline: False
Direct callers:
  - kernel/crash_core.c:update_vmcoreinfo_note
  - kernel/kexec_core.c:crash_save_cpu
```
**Symbols:**

```
ffffffff811514e0-ffffffff811514f9: final_note (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void final_note(Elf64_Word *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff811447c0)
Location: kernel/crash_core.c:312
Inline: False
Direct callers:
  - kernel/crash_core.c:update_vmcoreinfo_note
  - kernel/kexec_core.c:crash_save_cpu
```
**Symbols:**

```
ffffffff811447c0-ffffffff811447d9: final_note (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void final_note(Elf64_Word *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff8114f390)
Location: kernel/crash_core.c:312
Inline: False
Direct callers:
  - kernel/crash_core.c:update_vmcoreinfo_note
  - kernel/kexec_core.c:crash_save_cpu
```
**Symbols:**

```
ffffffff8114f390-ffffffff8114f3a9: final_note (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void final_note(Elf64_Word *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff8115c1b0)
Location: kernel/crash_core.c:312
Inline: False
Direct callers:
  - kernel/crash_core.c:update_vmcoreinfo_note
  - kernel/kexec_core.c:crash_save_cpu
```
**Symbols:**

```
ffffffff8115c1b0-ffffffff8115c1c9: final_note (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<b>Param type changed. </b>
<code>Elf64_Word *buf</code> ➡️ <code>Elf32_Word *buf</code>
</li>
</ul>
</details>
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
