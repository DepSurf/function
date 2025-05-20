# Function: <code>kexec_add_buffer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int kexec_add_buffer(struct kimage *image, char *buffer, long unsigned int bufsz, long unsigned int memsz, long unsigned int buf_align, long unsigned int buf_min, long unsigned int buf_max, bool top_down, long unsigned int *load_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8110e8f0)
Location: kernel/kexec_file.c:482
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - kernel/kexec_file.c:kexec_load_purgatory
```
**Symbols:**

```
ffffffff8110e8f0-ffffffff8110ea81: kexec_add_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int kexec_add_buffer(struct kimage *image, char *buffer, long unsigned int bufsz, long unsigned int memsz, long unsigned int buf_align, long unsigned int buf_min, long unsigned int buf_max, bool top_down, long unsigned int *load_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff81115f90)
Location: kernel/kexec_file.c:435
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - kernel/kexec_file.c:kexec_load_purgatory
```
**Symbols:**

```
ffffffff81115f90-ffffffff81116124: kexec_add_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int kexec_add_buffer(struct kexec_buf *kbuf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8111d740)
Location: kernel/kexec_file.c:483
Inline: True
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - kernel/kexec_file.c:kexec_load_purgatory
```
**Symbols:**

```
ffffffff8111d740-ffffffff8111d813: kexec_add_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int kexec_add_buffer(struct kexec_buf *kbuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8111f340)
Location: kernel/kexec_file.c:484
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - kernel/kexec_file.c:kexec_load_purgatory
```
**Symbols:**

```
ffffffff8111f340-ffffffff8111f405: kexec_add_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int kexec_add_buffer(struct kexec_buf *kbuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8112aae0)
Location: kernel/kexec_file.c:486
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - kernel/kexec_file.c:kexec_load_purgatory
```
**Symbols:**

```
ffffffff8112aae0-ffffffff8112aba2: kexec_add_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int kexec_add_buffer(struct kexec_buf *kbuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff811390b0)
Location: kernel/kexec_file.c:552
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - kernel/kexec_file.c:kexec_load_purgatory
```
**Symbols:**

```
ffffffff811390b0-ffffffff81139172: kexec_add_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int kexec_add_buffer(struct kexec_buf *kbuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff81144980)
Location: kernel/kexec_file.c:610
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - kernel/kexec_file.c:kexec_load_purgatory
```
**Symbols:**

```
ffffffff81144980-ffffffff81144a4b: kexec_add_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int kexec_add_buffer(struct kexec_buf *kbuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kexec_file.c (0)
Location: kernel/kexec_file.c:656
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - kernel/kexec_file.c:kexec_load_purgatory
```
**Symbols:**

```
ffffffff81150f74-ffffffff81150f8c: kexec_add_buffer.cold (STB_LOCAL)
ffffffff8114fd80-ffffffff8114fe46: kexec_add_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int kexec_add_buffer(struct kexec_buf *kbuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8115ba10)
Location: kernel/kexec_file.c:661
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - kernel/kexec_file.c:kexec_load_purgatory
```
**Symbols:**

```
ffffffff8115ba10-ffffffff8115bade: kexec_add_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int kexec_add_buffer(struct kexec_buf *kbuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8116cb40)
Location: kernel/kexec_file.c:648
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - kernel/kexec_file.c:kexec_purgatory_setup_kbuf
```
**Symbols:**

```
ffffffff8116cb40-ffffffff8116cc11: kexec_add_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kexec_add_buffer(struct kexec_buf *kbuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff811691d0)
Location: kernel/kexec_file.c:667
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - kernel/kexec_file.c:kexec_purgatory_setup_kbuf
```
**Symbols:**

```
ffffffff811691d0-ffffffff81169293: kexec_add_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int kexec_add_buffer(struct kexec_buf *kbuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff81169ea0)
Location: kernel/kexec_file.c:667
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - kernel/kexec_file.c:kexec_load_purgatory
```
**Symbols:**

```
ffffffff81169ea0-ffffffff81169f55: kexec_add_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int kexec_add_buffer(struct kexec_buf *kbuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8118fa30)
Location: kernel/kexec_file.c:667
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - kernel/kexec_file.c:kexec_load_purgatory
```
**Symbols:**

```
ffffffff8118fa30-ffffffff8118fb17: kexec_add_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kexec_add_buffer(struct kexec_buf *kbuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff811bf1b0)
Location: kernel/kexec_file.c:626
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - kernel/kexec_file.c:kexec_load_purgatory
```
**Symbols:**

```
ffffffff811bf1b0-ffffffff811bf2be: kexec_add_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kexec_add_buffer(struct kexec_buf *kbuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff81201450)
Location: kernel/kexec_file.c:630
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - kernel/kexec_file.c:kexec_load_purgatory
  - security/integrity/ima/ima_kexec.c:ima_add_kexec_buffer
```
**Symbols:**

```
ffffffff81201450-ffffffff8120155e: kexec_add_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kexec_add_buffer(struct kexec_buf *kbuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff81216820)
Location: kernel/kexec_file.c:633
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - kernel/kexec_file.c:kexec_load_purgatory
  - security/integrity/ima/ima_kexec.c:ima_add_kexec_buffer
```
**Symbols:**

```
ffffffff81216820-ffffffff8121692e: kexec_add_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kexec_add_buffer(struct kexec_buf *kbuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8122e700)
Location: kernel/kexec_file.c:643
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - kernel/kexec_file.c:kexec_load_purgatory
  - security/integrity/ima/ima_kexec.c:ima_add_kexec_buffer
```
**Symbols:**

```
ffffffff8122e700-ffffffff8122e80e: kexec_add_buffer (STB_GLOBAL)
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
int kexec_add_buffer(struct kexec_buf *kbuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffff8000101cb248)
Location: kernel/kexec_file.c:661
Inline: False
Direct callers:
  - arch/arm64/kernel/machine_kexec_file.c:load_other_segments
  - arch/arm64/kernel/machine_kexec_file.c:load_other_segments
```
**Symbols:**

```
ffff8000101cb248-ffff8000101cb328: kexec_add_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int kexec_add_buffer(struct kexec_buf *kbuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (c000000000233fc0)
Location: kernel/kexec_file.c:661
Inline: False
Direct callers:
  - arch/powerpc/kernel/kexec_elf_64.c:elf64_load
  - arch/powerpc/kernel/kexec_elf_64.c:elf64_load
  - kernel/kexec_file.c:kexec_load_purgatory
  - kernel/kexec_elf.c:kexec_elf_load
  - security/integrity/ima/ima_kexec.c:ima_add_kexec_buffer
```
**Symbols:**

```
c000000000233fc0-c000000000234100: kexec_add_buffer (STB_GLOBAL)
```
</details>
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
int kexec_add_buffer(struct kexec_buf *kbuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff81154030)
Location: kernel/kexec_file.c:661
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - kernel/kexec_file.c:kexec_load_purgatory
```
**Symbols:**

```
ffffffff81154030-ffffffff811540fe: kexec_add_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int kexec_add_buffer(struct kexec_buf *kbuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff81147350)
Location: kernel/kexec_file.c:661
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - kernel/kexec_file.c:kexec_load_purgatory
```
**Symbols:**

```
ffffffff81147350-ffffffff8114741e: kexec_add_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int kexec_add_buffer(struct kexec_buf *kbuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff81151e10)
Location: kernel/kexec_file.c:661
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - kernel/kexec_file.c:kexec_load_purgatory
```
**Symbols:**

```
ffffffff81151e10-ffffffff81151ede: kexec_add_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int kexec_add_buffer(struct kexec_buf *kbuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8115ed00)
Location: kernel/kexec_file.c:661
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - kernel/kexec_file.c:kexec_load_purgatory
```
**Symbols:**

```
ffffffff8115ed00-ffffffff8115edce: kexec_add_buffer (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct kexec_buf *kbuf</code>
</li>
<li>
<b>Param removed. </b>
<code>struct kimage *image</code>
</li>
<li>
<b>Param removed. </b>
<code>char *buffer</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int bufsz</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int memsz</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int buf_align</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int buf_min</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int buf_max</code>
</li>
<li>
<b>Param removed. </b>
<code>bool top_down</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int *load_addr</code>
</li>
</ul>
</details>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
