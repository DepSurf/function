# Function: <code>kthread_should_park</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool kthread_should_park();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a0090)
Location: kernel/kthread.c:96
Inline: False
Direct callers:
  - kernel/smpboot.c:smpboot_thread_fn
```
**Symbols:**

```
ffffffff810a0090-ffffffff810a00b6: kthread_should_park (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool kthread_should_park();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a3780)
Location: kernel/kthread.c:96
Inline: False
Direct callers:
  - kernel/smpboot.c:smpboot_thread_fn
```
**Symbols:**

```
ffffffff810a3780-ffffffff810a37a6: kthread_should_park (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool kthread_should_park();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a8850)
Location: kernel/kthread.c:105
Inline: False
Direct callers:
  - kernel/smpboot.c:smpboot_thread_fn
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
ffffffff810a8850-ffffffff810a8890: kthread_should_park (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool kthread_should_park();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a5690)
Location: kernel/kthread.c:108
Inline: False
Direct callers:
  - kernel/smpboot.c:smpboot_thread_fn
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
ffffffff810a5690-ffffffff810a56bf: kthread_should_park (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool kthread_should_park();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810abd60)
Location: kernel/kthread.c:116
Inline: False
Direct callers:
  - kernel/smpboot.c:smpboot_thread_fn
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
ffffffff810abd60-ffffffff810abd8f: kthread_should_park (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool kthread_should_park();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810b3630)
Location: kernel/kthread.c:115
Inline: False
Direct callers:
  - kernel/smpboot.c:smpboot_thread_fn
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
ffffffff810b3630-ffffffff810b365f: kthread_should_park (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool kthread_should_park();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810bc960)
Location: kernel/kthread.c:115
Inline: False
Direct callers:
  - kernel/smpboot.c:smpboot_thread_fn
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
ffffffff810bc960-ffffffff810bc98f: kthread_should_park (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
bool kthread_should_park();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kthread.c (0)
Location: kernel/kthread.c:124
Inline: False
Direct callers:
  - kernel/smpboot.c:smpboot_thread_fn
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
ffffffff810c330a-ffffffff810c331d: kthread_should_park.cold (STB_LOCAL)
ffffffff810c2880-ffffffff810c28b1: kthread_should_park (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool kthread_should_park();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c7e90)
Location: kernel/kthread.c:124
Inline: False
Direct callers:
  - kernel/smpboot.c:smpboot_thread_fn
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
ffffffff810c7e90-ffffffff810c7ebf: kthread_should_park (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool kthread_should_park();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810d0770)
Location: kernel/kthread.c:131
Inline: False
Direct callers:
  - kernel/smpboot.c:smpboot_thread_fn
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
ffffffff810d0770-ffffffff810d079f: kthread_should_park (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool kthread_should_park();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810cb190)
Location: kernel/kthread.c:132
Inline: False
Direct callers:
  - kernel/smpboot.c:smpboot_thread_fn
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
ffffffff810cb190-ffffffff810cb1bf: kthread_should_park (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool kthread_should_park();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810ccb00)
Location: kernel/kthread.c:157
Inline: False
Direct callers:
  - kernel/smpboot.c:smpboot_thread_fn
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
ffffffff810ccb00-ffffffff810ccb2f: kthread_should_park (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool kthread_should_park();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810df650)
Location: kernel/kthread.c:157
Inline: False
Direct callers:
  - kernel/smpboot.c:smpboot_thread_fn
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
ffffffff810df650-ffffffff810df67f: kthread_should_park (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool kthread_should_park();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810f96a0)
Location: kernel/kthread.c:178
Inline: False
Direct callers:
  - kernel/smpboot.c:smpboot_thread_fn
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
ffffffff810f96a0-ffffffff810f96d3: kthread_should_park (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool kthread_should_park();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff8111c320)
Location: kernel/kthread.c:178
Inline: False
Direct callers:
  - kernel/smpboot.c:smpboot_thread_fn
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
ffffffff8111c320-ffffffff8111c353: kthread_should_park (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool kthread_should_park();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff81129570)
Location: kernel/kthread.c:179
Inline: False
Direct callers:
  - kernel/smpboot.c:smpboot_thread_fn
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
ffffffff81129570-ffffffff811295a3: kthread_should_park (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool kthread_should_park();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff81133bb0)
Location: kernel/kthread.c:178
Inline: False
Direct callers:
  - kernel/smpboot.c:smpboot_thread_fn
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
ffffffff81133bb0-ffffffff81133be3: kthread_should_park (STB_GLOBAL)
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
bool kthread_should_park();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffff800010127158)
Location: kernel/kthread.c:124
Inline: False
Direct callers:
  - kernel/smpboot.c:smpboot_thread_fn
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
ffff800010127158-ffff8000101271a0: kthread_should_park (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool kthread_should_park();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (c0379aec)
Location: kernel/kthread.c:124
Inline: False
Direct callers:
  - kernel/smpboot.c:smpboot_thread_fn
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
c0379aec-c0379b18: kthread_should_park (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool kthread_should_park();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (c000000000172f60)
Location: kernel/kthread.c:124
Inline: False
Direct callers:
  - kernel/smpboot.c:smpboot_thread_fn
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
c000000000172f60-c000000000172f8c: kthread_should_park (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool kthread_should_park();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffe0000de994)
Location: kernel/kthread.c:124
Inline: False
Direct callers:
  - kernel/smpboot.c:smpboot_thread_fn
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
ffffffe0000de994-ffffffe0000de9da: kthread_should_park (STB_GLOBAL)
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
bool kthread_should_park();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c2210)
Location: kernel/kthread.c:124
Inline: False
Direct callers:
  - kernel/smpboot.c:smpboot_thread_fn
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
ffffffff810c2210-ffffffff810c223f: kthread_should_park (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool kthread_should_park();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810b0a60)
Location: kernel/kthread.c:124
Inline: False
Direct callers:
  - kernel/smpboot.c:smpboot_thread_fn
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
ffffffff810b0a60-ffffffff810b0a8f: kthread_should_park (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool kthread_should_park();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c1760)
Location: kernel/kthread.c:124
Inline: False
Direct callers:
  - kernel/smpboot.c:smpboot_thread_fn
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
ffffffff810c1760-ffffffff810c178f: kthread_should_park (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool kthread_should_park();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c9b90)
Location: kernel/kthread.c:124
Inline: False
Direct callers:
  - kernel/smpboot.c:smpboot_thread_fn
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
ffffffff810c9b90-ffffffff810c9bbf: kthread_should_park (STB_GLOBAL)
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
