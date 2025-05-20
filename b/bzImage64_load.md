# Function: <code>bzImage64_load</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *bzImage64_load(struct kimage *image, char *kernel, long unsigned int kernel_len, char *initrd, long unsigned int initrd_len, char *cmdline, long unsigned int cmdline_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kexec-bzimage64.c (ffffffff8105e1b0)
Location: arch/x86/kernel/kexec-bzimage64.c:327
Inline: False
```
**Symbols:**

```
ffffffff8105e1b0-ffffffff8105eb56: bzImage64_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *bzImage64_load(struct kimage *image, char *kernel, long unsigned int kernel_len, char *initrd, long unsigned int initrd_len, char *cmdline, long unsigned int cmdline_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kexec-bzimage64.c (ffffffff8105e050)
Location: arch/x86/kernel/kexec-bzimage64.c:327
Inline: False
```
**Symbols:**

```
ffffffff8105e050-ffffffff8105e982: bzImage64_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *bzImage64_load(struct kimage *image, char *kernel, long unsigned int kernel_len, char *initrd, long unsigned int initrd_len, char *cmdline, long unsigned int cmdline_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kexec-bzimage64.c (ffffffff810610f0)
Location: arch/x86/kernel/kexec-bzimage64.c:327
Inline: False
```
**Symbols:**

```
ffffffff810610f0-ffffffff81061a3c: bzImage64_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *bzImage64_load(struct kimage *image, char *kernel, long unsigned int kernel_len, char *initrd, long unsigned int initrd_len, char *cmdline, long unsigned int cmdline_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kexec-bzimage64.c (ffffffff810600b0)
Location: arch/x86/kernel/kexec-bzimage64.c:327
Inline: False
```
**Symbols:**

```
ffffffff810600b0-ffffffff810609f2: bzImage64_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *bzImage64_load(struct kimage *image, char *kernel, long unsigned int kernel_len, char *initrd, long unsigned int initrd_len, char *cmdline, long unsigned int cmdline_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kexec-bzimage64.c (ffffffff81064100)
Location: arch/x86/kernel/kexec-bzimage64.c:327
Inline: False
```
**Symbols:**

```
ffffffff81064100-ffffffff81064a42: bzImage64_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void *bzImage64_load(struct kimage *image, char *kernel, long unsigned int kernel_len, char *initrd, long unsigned int initrd_len, char *cmdline, long unsigned int cmdline_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kexec-bzimage64.c (0)
Location: arch/x86/kernel/kexec-bzimage64.c:327
Inline: False
```
**Symbols:**

```
ffffffff81066c30-ffffffff8106754a: bzImage64_load (STB_LOCAL)
ffffffff810675e4-ffffffff81067640: bzImage64_load.cold.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void *bzImage64_load(struct kimage *image, char *kernel, long unsigned int kernel_len, char *initrd, long unsigned int initrd_len, char *cmdline, long unsigned int cmdline_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kexec-bzimage64.c (0)
Location: arch/x86/kernel/kexec-bzimage64.c:330
Inline: False
```
**Symbols:**

```
ffffffff8106cc50-ffffffff8106d58e: bzImage64_load (STB_LOCAL)
ffffffff8106d628-ffffffff8106d684: bzImage64_load.cold.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void *bzImage64_load(struct kimage *image, char *kernel, long unsigned int kernel_len, char *initrd, long unsigned int initrd_len, char *cmdline, long unsigned int cmdline_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kexec-bzimage64.c (0)
Location: arch/x86/kernel/kexec-bzimage64.c:335
Inline: False
```
**Symbols:**

```
ffffffff81070cb0-ffffffff810715cb: bzImage64_load (STB_LOCAL)
ffffffff81071665-ffffffff810716bf: bzImage64_load.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void *bzImage64_load(struct kimage *image, char *kernel, long unsigned int kernel_len, char *initrd, long unsigned int initrd_len, char *cmdline, long unsigned int cmdline_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kexec-bzimage64.c (0)
Location: arch/x86/kernel/kexec-bzimage64.c:335
Inline: False
```
**Symbols:**

```
ffffffff81071cb0-ffffffff810725cb: bzImage64_load (STB_LOCAL)
ffffffff81072665-ffffffff810726bf: bzImage64_load.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void *bzImage64_load(struct kimage *image, char *kernel, long unsigned int kernel_len, char *initrd, long unsigned int initrd_len, char *cmdline, long unsigned int cmdline_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kexec-bzimage64.c (0)
Location: arch/x86/kernel/kexec-bzimage64.c:334
Inline: False
```
**Symbols:**

```
ffffffff81078fd0-ffffffff8107956f: bzImage64_load (STB_LOCAL)
ffffffff8107961f-ffffffff8107967b: bzImage64_load.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void *bzImage64_load(struct kimage *image, char *kernel, long unsigned int kernel_len, char *initrd, long unsigned int initrd_len, char *cmdline, long unsigned int cmdline_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kexec-bzimage64.c (0)
Location: arch/x86/kernel/kexec-bzimage64.c:324
Inline: False
```
**Symbols:**

```
ffffffff81078fc0-ffffffff8107955f: bzImage64_load (STB_LOCAL)
ffffffff81bd7b1c-ffffffff81bd7b78: bzImage64_load.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void *bzImage64_load(struct kimage *image, char *kernel, long unsigned int kernel_len, char *initrd, long unsigned int initrd_len, char *cmdline, long unsigned int cmdline_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kexec-bzimage64.c (0)
Location: arch/x86/kernel/kexec-bzimage64.c:324
Inline: False
```
**Symbols:**

```
ffffffff81079f60-ffffffff8107a4ff: bzImage64_load (STB_LOCAL)
ffffffff81bc9ad2-ffffffff81bc9b2e: bzImage64_load.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void *bzImage64_load(struct kimage *image, char *kernel, long unsigned int kernel_len, char *initrd, long unsigned int initrd_len, char *cmdline, long unsigned int cmdline_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kexec-bzimage64.c (0)
Location: arch/x86/kernel/kexec-bzimage64.c:324
Inline: False
```
**Symbols:**

```
ffffffff810880b0-ffffffff8108864c: bzImage64_load (STB_LOCAL)
ffffffff81c9e972-ffffffff81c9e9ce: bzImage64_load.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void *bzImage64_load(struct kimage *image, char *kernel, long unsigned int kernel_len, char *initrd, long unsigned int initrd_len, char *cmdline, long unsigned int cmdline_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kexec-bzimage64.c (0)
Location: arch/x86/kernel/kexec-bzimage64.c:323
Inline: False
```
**Symbols:**

```
ffffffff81098240-ffffffff810987fd: bzImage64_load (STB_LOCAL)
ffffffff81e4ddae-ffffffff81e4de01: bzImage64_load.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void *bzImage64_load(struct kimage *image, char *kernel, long unsigned int kernel_len, char *initrd, long unsigned int initrd_len, char *cmdline, long unsigned int cmdline_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kexec-bzimage64.c (0)
Location: arch/x86/kernel/kexec-bzimage64.c:385
Inline: False
```
**Symbols:**

```
ffffffff810ae8b0-ffffffff810aef18: bzImage64_load (STB_LOCAL)
ffffffff820540c4-ffffffff8205411d: bzImage64_load.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void *bzImage64_load(struct kimage *image, char *kernel, long unsigned int kernel_len, char *initrd, long unsigned int initrd_len, char *cmdline, long unsigned int cmdline_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kexec-bzimage64.c (0)
Location: arch/x86/kernel/kexec-bzimage64.c:385
Inline: False
```
**Symbols:**

```
ffffffff810b18b0-ffffffff810b1f16: bzImage64_load (STB_LOCAL)
ffffffff820d2671-ffffffff820d26ca: bzImage64_load.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void *bzImage64_load(struct kimage *image, char *kernel, long unsigned int kernel_len, char *initrd, long unsigned int initrd_len, char *cmdline, long unsigned int cmdline_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kexec-bzimage64.c (0)
Location: arch/x86/kernel/kexec-bzimage64.c:390
Inline: False
```
**Symbols:**

```
ffffffff810b8c90-ffffffff810b934b: bzImage64_load (STB_LOCAL)
ffffffff821ad426-ffffffff821ad530: bzImage64_load.cold (STB_LOCAL)
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
void *bzImage64_load(struct kimage *image, char *kernel, long unsigned int kernel_len, char *initrd, long unsigned int initrd_len, char *cmdline, long unsigned int cmdline_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kexec-bzimage64.c (0)
Location: arch/x86/kernel/kexec-bzimage64.c:335
Inline: False
```
**Symbols:**

```
ffffffff81070cb0-ffffffff810715cb: bzImage64_load (STB_LOCAL)
ffffffff81071665-ffffffff810716bf: bzImage64_load.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void *bzImage64_load(struct kimage *image, char *kernel, long unsigned int kernel_len, char *initrd, long unsigned int initrd_len, char *cmdline, long unsigned int cmdline_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kexec-bzimage64.c (0)
Location: arch/x86/kernel/kexec-bzimage64.c:335
Inline: False
```
**Symbols:**

```
ffffffff81060cc0-ffffffff810615db: bzImage64_load (STB_LOCAL)
ffffffff81061675-ffffffff810616cf: bzImage64_load.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void *bzImage64_load(struct kimage *image, char *kernel, long unsigned int kernel_len, char *initrd, long unsigned int initrd_len, char *cmdline, long unsigned int cmdline_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kexec-bzimage64.c (0)
Location: arch/x86/kernel/kexec-bzimage64.c:335
Inline: False
```
**Symbols:**

```
ffffffff81070c60-ffffffff8107157b: bzImage64_load (STB_LOCAL)
ffffffff81071615-ffffffff8107166f: bzImage64_load.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void *bzImage64_load(struct kimage *image, char *kernel, long unsigned int kernel_len, char *initrd, long unsigned int initrd_len, char *cmdline, long unsigned int cmdline_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kexec-bzimage64.c (0)
Location: arch/x86/kernel/kexec-bzimage64.c:335
Inline: False
```
**Symbols:**

```
ffffffff81072cc0-ffffffff810735db: bzImage64_load (STB_LOCAL)
ffffffff81073675-ffffffff810736cf: bzImage64_load.cold (STB_LOCAL)
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
