# Function: <code>append_elf_note</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u32 *append_elf_note(u32 *buf, char *name, unsigned int type, void *data, size_t data_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff8110c4d0)
Location: kernel/kexec_core.c:950
Inline: False
Direct callers:
  - kernel/kexec_core.c:update_vmcoreinfo_note
  - kernel/kexec_core.c:crash_save_cpu
```
**Symbols:**

```
ffffffff8110c4d0-ffffffff8110c586: append_elf_note (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u32 *append_elf_note(u32 *buf, char *name, unsigned int type, void *data, size_t data_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff81113d50)
Location: kernel/kexec_core.c:997
Inline: False
Direct callers:
  - kernel/kexec_core.c:update_vmcoreinfo_note
  - kernel/kexec_core.c:crash_save_cpu
```
**Symbols:**

```
ffffffff81113d50-ffffffff81113e00: append_elf_note (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u32 *append_elf_note(u32 *buf, char *name, unsigned int type, void *data, size_t data_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff8111b460)
Location: kernel/kexec_core.c:999
Inline: False
Direct callers:
  - kernel/kexec_core.c:update_vmcoreinfo_note
  - kernel/kexec_core.c:crash_save_cpu
```
**Symbols:**

```
ffffffff8111b460-ffffffff8111b510: append_elf_note (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
Elf64_Word *append_elf_note(Elf64_Word *buf, char *name, unsigned int type, void *data, size_t data_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff8111cfb0)
Location: kernel/crash_core.c:296
Inline: False
Direct callers:
  - kernel/crash_core.c:update_vmcoreinfo_note
  - kernel/kexec_core.c:crash_save_cpu
```
**Symbols:**

```
ffffffff8111cfb0-ffffffff8111d02b: append_elf_note (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
Elf64_Word *append_elf_note(Elf64_Word *buf, char *name, unsigned int type, void *data, size_t data_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff811286a0)
Location: kernel/crash_core.c:297
Inline: False
Direct callers:
  - kernel/crash_core.c:update_vmcoreinfo_note
  - kernel/kexec_core.c:crash_save_cpu
```
**Symbols:**

```
ffffffff811286a0-ffffffff8112871b: append_elf_note (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
Elf64_Word *append_elf_note(Elf64_Word *buf, char *name, unsigned int type, void *data, size_t data_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff81136620)
Location: kernel/crash_core.c:297
Inline: False
Direct callers:
  - kernel/crash_core.c:update_vmcoreinfo_note
  - kernel/kexec_core.c:crash_save_cpu
```
**Symbols:**

```
ffffffff81136620-ffffffff811366a5: append_elf_note (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
Elf64_Word *append_elf_note(Elf64_Word *buf, char *name, unsigned int type, void *data, size_t data_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff81141db0)
Location: kernel/crash_core.c:297
Inline: False
Direct callers:
  - kernel/crash_core.c:update_vmcoreinfo_note
  - kernel/kexec_core.c:crash_save_cpu
```
**Symbols:**

```
ffffffff81141db0-ffffffff81141e35: append_elf_note (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
Elf64_Word *append_elf_note(Elf64_Word *buf, char *name, unsigned int type, void *data, size_t data_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff8114d160)
Location: kernel/crash_core.c:295
Inline: False
Direct callers:
  - kernel/crash_core.c:update_vmcoreinfo_note
  - kernel/kexec_core.c:crash_save_cpu
```
**Symbols:**

```
ffffffff8114d160-ffffffff8114d1e5: append_elf_note (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
Elf64_Word *append_elf_note(Elf64_Word *buf, char *name, unsigned int type, void *data, size_t data_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff81158e30)
Location: kernel/crash_core.c:295
Inline: False
Direct callers:
  - kernel/crash_core.c:update_vmcoreinfo_note
  - kernel/kexec_core.c:crash_save_cpu
```
**Symbols:**

```
ffffffff81158e30-ffffffff81158eb5: append_elf_note (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
Elf64_Word *append_elf_note(Elf64_Word *buf, char *name, unsigned int type, void *data, size_t data_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff81169a00)
Location: kernel/crash_core.c:295
Inline: False
Direct callers:
  - kernel/crash_core.c:update_vmcoreinfo_note
  - kernel/kexec_core.c:crash_save_cpu
```
**Symbols:**

```
ffffffff81169a00-ffffffff81169a84: append_elf_note (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
Elf64_Word *append_elf_note(Elf64_Word *buf, char *name, unsigned int type, void *data, size_t data_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff81166150)
Location: kernel/crash_core.c:297
Inline: False
Direct callers:
  - kernel/crash_core.c:update_vmcoreinfo_note
  - kernel/kexec_core.c:crash_save_cpu
```
**Symbols:**

```
ffffffff81166150-ffffffff811661d4: append_elf_note (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
Elf64_Word *append_elf_note(Elf64_Word *buf, char *name, unsigned int type, void *data, size_t data_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff81166ef0)
Location: kernel/crash_core.c:297
Inline: False
Direct callers:
  - kernel/crash_core.c:update_vmcoreinfo_note
  - kernel/kexec_core.c:crash_save_cpu
```
**Symbols:**

```
ffffffff81166ef0-ffffffff81166f75: append_elf_note (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
Elf64_Word *append_elf_note(Elf64_Word *buf, char *name, unsigned int type, void *data, size_t data_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff8118c6b0)
Location: kernel/crash_core.c:309
Inline: False
Direct callers:
  - kernel/crash_core.c:update_vmcoreinfo_note
  - kernel/kexec_core.c:crash_save_cpu
```
**Symbols:**

```
ffffffff8118c6b0-ffffffff8118c735: append_elf_note (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
Elf64_Word *append_elf_note(Elf64_Word *buf, char *name, unsigned int type, void *data, size_t data_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff811bbb30)
Location: kernel/crash_core.c:305
Inline: False
Direct callers:
  - kernel/crash_core.c:crash_save_vmcoreinfo
  - kernel/kexec_core.c:crash_save_cpu
```
**Symbols:**

```
ffffffff811bbb30-ffffffff811bbbc4: append_elf_note (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
Elf64_Word *append_elf_note(Elf64_Word *buf, char *name, unsigned int type, void *data, size_t data_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff811fd9e0)
Location: kernel/crash_core.c:317
Inline: False
Direct callers:
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo
  - kernel/kexec_core.c:crash_save_cpu
```
**Symbols:**

```
ffffffff811fd9e0-ffffffff811fda74: append_elf_note (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
Elf64_Word *append_elf_note(Elf64_Word *buf, char *name, unsigned int type, void *data, size_t data_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff81212b60)
Location: kernel/crash_core.c:317
Inline: False
Direct callers:
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo
  - kernel/kexec_core.c:crash_save_cpu
```
**Symbols:**

```
ffffffff81212b60-ffffffff81212bf4: append_elf_note (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
Elf64_Word *append_elf_note(Elf64_Word *buf, char *name, unsigned int type, void *data, size_t data_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff8122a9c0)
Location: kernel/crash_core.c:636
Inline: False
Direct callers:
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo
  - kernel/kexec_core.c:crash_save_cpu
```
**Symbols:**

```
ffffffff8122a9c0-ffffffff8122aa54: append_elf_note (STB_GLOBAL)
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
Elf64_Word *append_elf_note(Elf64_Word *buf, char *name, unsigned int type, void *data, size_t data_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffff8000101c8418)
Location: kernel/crash_core.c:295
Inline: False
Direct callers:
  - kernel/crash_core.c:update_vmcoreinfo_note
  - kernel/kexec_core.c:crash_save_cpu
```
**Symbols:**

```
ffff8000101c8418-ffff8000101c84ac: append_elf_note (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
Elf32_Word *append_elf_note(Elf32_Word *buf, char *name, unsigned int type, void *data, size_t data_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (c040f398)
Location: kernel/crash_core.c:295
Inline: False
Direct callers:
  - kernel/crash_core.c:update_vmcoreinfo_note
  - kernel/kexec_core.c:crash_save_cpu
```
**Symbols:**

```
c040f398-c040f414: append_elf_note (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
Elf64_Word *append_elf_note(Elf64_Word *buf, char *name, unsigned int type, void *data, size_t data_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (c000000000230a20)
Location: kernel/crash_core.c:295
Inline: False
Direct callers:
  - arch/powerpc/kernel/fadump.c:fadump_regs_to_elf_notes
  - kernel/crash_core.c:update_vmcoreinfo_note
  - kernel/kexec_core.c:crash_save_cpu
```
**Symbols:**

```
c000000000230a20-c000000000230af0: append_elf_note (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
Elf64_Word *append_elf_note(Elf64_Word *buf, char *name, unsigned int type, void *data, size_t data_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffe0001482b0)
Location: kernel/crash_core.c:295
Inline: False
Direct callers:
  - kernel/crash_core.c:update_vmcoreinfo_note
```
**Symbols:**

```
ffffffe0001482b0-ffffffe00014833c: append_elf_note (STB_GLOBAL)
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
Elf64_Word *append_elf_note(Elf64_Word *buf, char *name, unsigned int type, void *data, size_t data_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff81151450)
Location: kernel/crash_core.c:295
Inline: False
Direct callers:
  - kernel/crash_core.c:update_vmcoreinfo_note
  - kernel/kexec_core.c:crash_save_cpu
```
**Symbols:**

```
ffffffff81151450-ffffffff811514d5: append_elf_note (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
Elf64_Word *append_elf_note(Elf64_Word *buf, char *name, unsigned int type, void *data, size_t data_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff81144730)
Location: kernel/crash_core.c:295
Inline: False
Direct callers:
  - kernel/crash_core.c:update_vmcoreinfo_note
  - kernel/kexec_core.c:crash_save_cpu
```
**Symbols:**

```
ffffffff81144730-ffffffff811447b5: append_elf_note (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
Elf64_Word *append_elf_note(Elf64_Word *buf, char *name, unsigned int type, void *data, size_t data_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff8114f300)
Location: kernel/crash_core.c:295
Inline: False
Direct callers:
  - kernel/crash_core.c:update_vmcoreinfo_note
  - kernel/kexec_core.c:crash_save_cpu
```
**Symbols:**

```
ffffffff8114f300-ffffffff8114f385: append_elf_note (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
Elf64_Word *append_elf_note(Elf64_Word *buf, char *name, unsigned int type, void *data, size_t data_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff8115c120)
Location: kernel/crash_core.c:295
Inline: False
Direct callers:
  - kernel/crash_core.c:update_vmcoreinfo_note
  - kernel/kexec_core.c:crash_save_cpu
```
**Symbols:**

```
ffffffff8115c120-ffffffff8115c1a5: append_elf_note (STB_GLOBAL)
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
<b>Param type changed. </b>
<code>u32 *buf</code> ➡️ <code>Elf64_Word *buf</code>
</li>
<li>
<b>Return type changed. </b>
<code>u32 *</code> ➡️ <code>Elf64_Word *</code>
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
<b>Param type changed. </b>
<code>Elf64_Word *buf</code> ➡️ <code>Elf32_Word *buf</code>
</li>
<li>
<b>Return type changed. </b>
<code>Elf64_Word *</code> ➡️ <code>Elf32_Word *</code>
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
