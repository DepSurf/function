# Function: <code>smpboot_unpark_threads</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void smpboot_unpark_threads(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810a3e80)
Location: kernel/smpboot.c:229
Inline: False
Direct callers:
  - kernel/cpu.c:smpboot_thread_call
```
**Symbols:**

```
ffffffff810a3e80-ffffffff810a3f06: smpboot_unpark_threads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int smpboot_unpark_threads(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810a75b0)
Location: kernel/smpboot.c:229
Inline: False
```
**Symbols:**

```
ffffffff810a75b0-ffffffff810a7634: smpboot_unpark_threads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int smpboot_unpark_threads(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810ad260)
Location: kernel/smpboot.c:234
Inline: False
```
**Symbols:**

```
ffffffff810ad260-ffffffff810ad2e7: smpboot_unpark_threads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int smpboot_unpark_threads(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810a9e30)
Location: kernel/smpboot.c:235
Inline: False
```
**Symbols:**

```
ffffffff810a9e30-ffffffff810a9eb7: smpboot_unpark_threads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int smpboot_unpark_threads(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810b0560)
Location: kernel/smpboot.c:235
Inline: False
```
**Symbols:**

```
ffffffff810b0560-ffffffff810b05e7: smpboot_unpark_threads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int smpboot_unpark_threads(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810b7380)
Location: kernel/smpboot.c:235
Inline: False
```
**Symbols:**

```
ffffffff810b7380-ffffffff810b7407: smpboot_unpark_threads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int smpboot_unpark_threads(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810c05c0)
Location: kernel/smpboot.c:235
Inline: False
```
**Symbols:**

```
ffffffff810c05c0-ffffffff810c063d: smpboot_unpark_threads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int smpboot_unpark_threads(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810c66b0)
Location: kernel/smpboot.c:236
Inline: False
```
**Symbols:**

```
ffffffff810c66b0-ffffffff810c672d: smpboot_unpark_threads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int smpboot_unpark_threads(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810cf790)
Location: kernel/smpboot.c:236
Inline: False
```
**Symbols:**

```
ffffffff810cf790-ffffffff810cf80d: smpboot_unpark_threads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int smpboot_unpark_threads(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810d9690)
Location: kernel/smpboot.c:236
Inline: False
```
**Symbols:**

```
ffffffff810d9690-ffffffff810d970d: smpboot_unpark_threads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int smpboot_unpark_threads(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810d4840)
Location: kernel/smpboot.c:237
Inline: False
```
**Symbols:**

```
ffffffff810d4840-ffffffff810d48bd: smpboot_unpark_threads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int smpboot_unpark_threads(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810d6460)
Location: kernel/smpboot.c:236
Inline: False
```
**Symbols:**

```
ffffffff810d6460-ffffffff810d64dd: smpboot_unpark_threads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int smpboot_unpark_threads(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/smpboot.c (0)
Location: kernel/smpboot.c:236
Inline: False
```
**Symbols:**

```
ffffffff81ca5917-ffffffff81ca592b: smpboot_unpark_threads.cold (STB_LOCAL)
ffffffff810e9760-ffffffff810e9804: smpboot_unpark_threads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int smpboot_unpark_threads(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/smpboot.c (0)
Location: kernel/smpboot.c:236
Inline: False
```
**Symbols:**

```
ffffffff81e55211-ffffffff81e55225: smpboot_unpark_threads.cold (STB_LOCAL)
ffffffff81104390-ffffffff8110443c: smpboot_unpark_threads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int smpboot_unpark_threads(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/smpboot.c (0)
Location: kernel/smpboot.c:236
Inline: False
```
**Symbols:**

```
ffffffff820568ac-ffffffff820568c0: smpboot_unpark_threads.cold (STB_LOCAL)
ffffffff81129b90-ffffffff81129c3c: smpboot_unpark_threads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int smpboot_unpark_threads(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/smpboot.c (0)
Location: kernel/smpboot.c:236
Inline: False
```
**Symbols:**

```
ffffffff820d4f1b-ffffffff820d4f2f: smpboot_unpark_threads.cold (STB_LOCAL)
ffffffff81137030-ffffffff811370dc: smpboot_unpark_threads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int smpboot_unpark_threads(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/smpboot.c (0)
Location: kernel/smpboot.c:236
Inline: False
```
**Symbols:**

```
ffffffff821afe16-ffffffff821afe2a: smpboot_unpark_threads.cold (STB_LOCAL)
ffffffff81142210-ffffffff811422bc: smpboot_unpark_threads (STB_GLOBAL)
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
int smpboot_unpark_threads(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffff80001012f880)
Location: kernel/smpboot.c:236
Inline: False
```
**Symbols:**

```
ffff80001012f880-ffff80001012f928: smpboot_unpark_threads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int smpboot_unpark_threads(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (c037f44c)
Location: kernel/smpboot.c:236
Inline: False
```
**Symbols:**

```
c037f44c-c037f4e4: smpboot_unpark_threads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int smpboot_unpark_threads(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (c000000000178ea0)
Location: kernel/smpboot.c:236
Inline: False
```
**Symbols:**

```
c000000000178ea0-c000000000178f88: smpboot_unpark_threads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int smpboot_unpark_threads(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffe0000e332a)
Location: kernel/smpboot.c:236
Inline: False
```
**Symbols:**

```
ffffffe0000e332a-ffffffe0000e33c6: smpboot_unpark_threads (STB_GLOBAL)
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
int smpboot_unpark_threads(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810c9b10)
Location: kernel/smpboot.c:236
Inline: False
```
**Symbols:**

```
ffffffff810c9b10-ffffffff810c9b8d: smpboot_unpark_threads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int smpboot_unpark_threads(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810b8330)
Location: kernel/smpboot.c:236
Inline: False
```
**Symbols:**

```
ffffffff810b8330-ffffffff810b83ad: smpboot_unpark_threads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int smpboot_unpark_threads(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810c9040)
Location: kernel/smpboot.c:236
Inline: False
```
**Symbols:**

```
ffffffff810c9040-ffffffff810c90bd: smpboot_unpark_threads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int smpboot_unpark_threads(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810d15b0)
Location: kernel/smpboot.c:236
Inline: False
```
**Symbols:**

```
ffffffff810d15b0-ffffffff810d162d: smpboot_unpark_threads (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
