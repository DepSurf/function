# Function: <code>kthread_parkme</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void kthread_parkme();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a01e0)
Location: kernel/kthread.c:171
Inline: False
Direct callers:
  - kernel/smpboot.c:smpboot_thread_fn
```
**Symbols:**

```
ffffffff810a01e0-ffffffff810a0204: kthread_parkme (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void kthread_parkme();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a38d0)
Location: kernel/kthread.c:171
Inline: False
Direct callers:
  - kernel/smpboot.c:smpboot_thread_fn
```
**Symbols:**

```
ffffffff810a38d0-ffffffff810a38f4: kthread_parkme (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void kthread_parkme();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a8980)
Location: kernel/kthread.c:180
Inline: False
Direct callers:
  - kernel/smpboot.c:smpboot_thread_fn
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
ffffffff810a8980-ffffffff810a89c8: kthread_parkme (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void kthread_parkme();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a57a0)
Location: kernel/kthread.c:183
Inline: False
Direct callers:
  - kernel/smpboot.c:smpboot_thread_fn
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
ffffffff810a57a0-ffffffff810a57d6: kthread_parkme (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void kthread_parkme();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810abeb0)
Location: kernel/kthread.c:191
Inline: False
Direct callers:
  - kernel/smpboot.c:smpboot_thread_fn
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
ffffffff810abeb0-ffffffff810abee6: kthread_parkme (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void kthread_parkme();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810b3660)
Location: kernel/kthread.c:199
Inline: False
Direct callers:
  - kernel/smpboot.c:smpboot_thread_fn
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
ffffffff810b3660-ffffffff810b368a: kthread_parkme (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void kthread_parkme();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810bc900)
Location: kernel/kthread.c:199
Inline: False
Direct callers:
  - kernel/smpboot.c:smpboot_thread_fn
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
ffffffff810bc900-ffffffff810bc92a: kthread_parkme (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void kthread_parkme();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kthread.c (0)
Location: kernel/kthread.c:208
Inline: False
Direct callers:
  - kernel/smpboot.c:smpboot_thread_fn
  - fs/io_uring.c:io_sq_thread
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
ffffffff810c32f7-ffffffff810c330a: kthread_parkme.cold (STB_LOCAL)
ffffffff810c2850-ffffffff810c287c: kthread_parkme (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void kthread_parkme();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c7fc0)
Location: kernel/kthread.c:208
Inline: False
Direct callers:
  - kernel/smpboot.c:smpboot_thread_fn
  - fs/io_uring.c:io_sq_thread
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
ffffffff810c7fc0-ffffffff810c7ff6: kthread_parkme (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void kthread_parkme();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810d0730)
Location: kernel/kthread.c:237
Inline: False
Direct callers:
  - kernel/smpboot.c:smpboot_thread_fn
  - fs/io_uring.c:io_sq_thread
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
ffffffff810d0730-ffffffff810d0766: kthread_parkme (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void kthread_parkme();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810cb120)
Location: kernel/kthread.c:238
Inline: False
Direct callers:
  - kernel/smpboot.c:smpboot_thread_fn
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
ffffffff810cb120-ffffffff810cb156: kthread_parkme (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void kthread_parkme();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810ccac0)
Location: kernel/kthread.c:265
Inline: False
Direct callers:
  - kernel/smpboot.c:smpboot_thread_fn
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
ffffffff810ccac0-ffffffff810ccaf6: kthread_parkme (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void kthread_parkme();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810df770)
Location: kernel/kthread.c:265
Inline: False
Direct callers:
  - kernel/smpboot.c:smpboot_thread_fn
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
ffffffff810df770-ffffffff810df7a6: kthread_parkme (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void kthread_parkme();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810f97d0)
Location: kernel/kthread.c:286
Inline: False
Direct callers:
  - kernel/smpboot.c:smpboot_thread_fn
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
ffffffff810f97d0-ffffffff810f9816: kthread_parkme (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void kthread_parkme();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff8111c490)
Location: kernel/kthread.c:286
Inline: False
Direct callers:
  - kernel/smpboot.c:smpboot_thread_fn
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
ffffffff8111c490-ffffffff8111c4d6: kthread_parkme (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void kthread_parkme();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff811296e0)
Location: kernel/kthread.c:297
Inline: False
Direct callers:
  - kernel/smpboot.c:smpboot_thread_fn
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
ffffffff811296e0-ffffffff81129726: kthread_parkme (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void kthread_parkme();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff81133d20)
Location: kernel/kthread.c:296
Inline: False
Direct callers:
  - kernel/smpboot.c:smpboot_thread_fn
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
ffffffff81133d20-ffffffff81133d66: kthread_parkme (STB_GLOBAL)
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
void kthread_parkme();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffff800010127588)
Location: kernel/kthread.c:208
Inline: False
Direct callers:
  - virt/kvm/kvm_main.c:kvm_vm_worker_thread
  - kernel/smpboot.c:smpboot_thread_fn
  - fs/io_uring.c:io_sq_thread
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
ffff800010127588-ffff8000101275c8: kthread_parkme (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void kthread_parkme();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (c0379c28)
Location: kernel/kthread.c:208
Inline: False
Direct callers:
  - kernel/smpboot.c:smpboot_thread_fn
  - fs/io_uring.c:io_sq_thread
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
c0379c28-c0379c7c: kthread_parkme (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void kthread_parkme();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (c000000000172f90)
Location: kernel/kthread.c:208
Inline: False
Direct callers:
  - kernel/smpboot.c:smpboot_thread_fn
  - fs/io_uring.c:io_sq_thread
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
c000000000172f90-c000000000172fbc: kthread_parkme (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void kthread_parkme();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffe0000deb6a)
Location: kernel/kthread.c:208
Inline: False
Direct callers:
  - kernel/smpboot.c:smpboot_thread_fn
  - fs/io_uring.c:io_sq_thread
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
ffffffe0000deb6a-ffffffe0000debb4: kthread_parkme (STB_GLOBAL)
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
void kthread_parkme();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c2340)
Location: kernel/kthread.c:208
Inline: False
Direct callers:
  - kernel/smpboot.c:smpboot_thread_fn
  - fs/io_uring.c:io_sq_thread
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
ffffffff810c2340-ffffffff810c2376: kthread_parkme (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void kthread_parkme();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810b0b90)
Location: kernel/kthread.c:208
Inline: False
Direct callers:
  - kernel/smpboot.c:smpboot_thread_fn
  - fs/io_uring.c:io_sq_thread
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
ffffffff810b0b90-ffffffff810b0bc6: kthread_parkme (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void kthread_parkme();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c1890)
Location: kernel/kthread.c:208
Inline: False
Direct callers:
  - kernel/smpboot.c:smpboot_thread_fn
  - fs/io_uring.c:io_sq_thread
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
ffffffff810c1890-ffffffff810c18c6: kthread_parkme (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void kthread_parkme();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c9cc0)
Location: kernel/kthread.c:208
Inline: False
Direct callers:
  - kernel/smpboot.c:smpboot_thread_fn
  - fs/io_uring.c:io_sq_thread
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
ffffffff810c9cc0-ffffffff810c9cf6: kthread_parkme (STB_GLOBAL)
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
