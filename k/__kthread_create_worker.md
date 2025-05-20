# Function: <code>__kthread_create_worker</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct kthread_worker *__kthread_create_worker(int cpu, unsigned int flags, const char *namefmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a96b0)
Location: kernel/kthread.c:652
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_create_worker_on_cpu
  - kernel/kthread.c:kthread_create_worker
```
**Symbols:**

```
ffffffff810a96b0-ffffffff810a97d2: __kthread_create_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct kthread_worker *__kthread_create_worker(int cpu, unsigned int flags, const char *namefmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a6370)
Location: kernel/kthread.c:658
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_create_worker_on_cpu
  - kernel/kthread.c:kthread_create_worker
```
**Symbols:**

```
ffffffff810a6370-ffffffff810a6483: __kthread_create_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct kthread_worker *__kthread_create_worker(int cpu, unsigned int flags, const char *namefmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810ac9a0)
Location: kernel/kthread.c:665
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_create_worker_on_cpu
  - kernel/kthread.c:kthread_create_worker
```
**Symbols:**

```
ffffffff810ac9a0-ffffffff810acab3: __kthread_create_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct kthread_worker *__kthread_create_worker(int cpu, unsigned int flags, const char *namefmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810b33f0)
Location: kernel/kthread.c:683
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_create_worker_on_cpu
  - kernel/kthread.c:kthread_create_worker
```
**Symbols:**

```
ffffffff810b33f0-ffffffff810b350f: __kthread_create_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct kthread_worker *__kthread_create_worker(int cpu, unsigned int flags, const char *namefmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810bc530)
Location: kernel/kthread.c:685
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_create_worker_on_cpu
  - kernel/kthread.c:kthread_create_worker
```
**Symbols:**

```
ffffffff810bc530-ffffffff810bc64f: __kthread_create_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct kthread_worker *__kthread_create_worker(int cpu, unsigned int flags, const char *namefmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c2450)
Location: kernel/kthread.c:694
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_create_worker_on_cpu
  - kernel/kthread.c:kthread_create_worker
```
**Symbols:**

```
ffffffff810c2450-ffffffff810c2563: __kthread_create_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct kthread_worker *__kthread_create_worker(int cpu, unsigned int flags, const char *namefmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c8b90)
Location: kernel/kthread.c:694
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_create_worker_on_cpu
  - kernel/kthread.c:kthread_create_worker
```
**Symbols:**

```
ffffffff810c8b90-ffffffff810c8ca3: __kthread_create_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct kthread_worker *__kthread_create_worker(int cpu, unsigned int flags, const char *namefmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810d0e20)
Location: kernel/kthread.c:730
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_create_worker_on_cpu
  - kernel/kthread.c:kthread_create_worker
```
**Symbols:**

```
ffffffff810d0e20-ffffffff810d0f46: __kthread_create_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct kthread_worker *__kthread_create_worker(int cpu, unsigned int flags, const char *namefmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810cb8d0)
Location: kernel/kthread.c:763
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_create_worker_on_cpu
  - kernel/kthread.c:kthread_create_worker
```
**Symbols:**

```
ffffffff810cb8d0-ffffffff810cb9f6: __kthread_create_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct kthread_worker *__kthread_create_worker(int cpu, unsigned int flags, const char *namefmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810cd150)
Location: kernel/kthread.c:790
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_create_worker_on_cpu
  - kernel/kthread.c:kthread_create_worker
```
**Symbols:**

```
ffffffff810cd150-ffffffff810cd276: __kthread_create_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct kthread_worker *__kthread_create_worker(int cpu, unsigned int flags, const char *namefmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810e0320)
Location: kernel/kthread.c:790
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_create_worker_on_cpu
  - kernel/kthread.c:kthread_create_worker
```
**Symbols:**

```
ffffffff810e0320-ffffffff810e0465: __kthread_create_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct kthread_worker *__kthread_create_worker(int cpu, unsigned int flags, const char *namefmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810fa060)
Location: kernel/kthread.c:850
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_create_worker_on_cpu
  - kernel/kthread.c:kthread_create_worker
```
**Symbols:**

```
ffffffff810fa060-ffffffff810fa1a4: __kthread_create_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct kthread_worker *__kthread_create_worker(int cpu, unsigned int flags, const char *namefmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff8111cde0)
Location: kernel/kthread.c:851
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_create_worker_on_cpu
  - kernel/kthread.c:kthread_create_worker
```
**Symbols:**

```
ffffffff8111cde0-ffffffff8111cf24: __kthread_create_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct kthread_worker *__kthread_create_worker(int cpu, unsigned int flags, const char *namefmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff81129f00)
Location: kernel/kthread.c:852
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_create_worker_on_cpu
  - kernel/kthread.c:kthread_create_worker
```
**Symbols:**

```
ffffffff81129f00-ffffffff8112a044: __kthread_create_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct kthread_worker *__kthread_create_worker(int cpu, unsigned int flags, const char *namefmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff81134570)
Location: kernel/kthread.c:869
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_create_worker_on_cpu
  - kernel/kthread.c:kthread_create_worker
```
**Symbols:**

```
ffffffff81134570-ffffffff811346e0: __kthread_create_worker (STB_LOCAL)
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
struct kthread_worker *__kthread_create_worker(int cpu, unsigned int flags, const char *namefmt, va_list args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffff8000101281e8)
Location: kernel/kthread.c:694
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_create_worker_on_cpu
  - kernel/kthread.c:kthread_create_worker
```
**Symbols:**

```
ffff8000101281e8-ffff800010128338: __kthread_create_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct kthread_worker *__kthread_create_worker(int cpu, unsigned int flags, const char *namefmt, va_list args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (c037b178)
Location: kernel/kthread.c:694
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_create_worker_on_cpu
  - kernel/kthread.c:kthread_create_worker
```
**Symbols:**

```
c037b178-c037b280: __kthread_create_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct kthread_worker *__kthread_create_worker(int cpu, unsigned int flags, const char *namefmt, va_list args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (c000000000172800)
Location: kernel/kthread.c:694
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_create_worker_on_cpu
  - kernel/kthread.c:kthread_create_worker
```
**Symbols:**

```
c000000000172800-c0000000001729ac: __kthread_create_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct kthread_worker *__kthread_create_worker(int cpu, unsigned int flags, const char *namefmt, va_list args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffe0000df7cc)
Location: kernel/kthread.c:694
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_create_worker_on_cpu
  - kernel/kthread.c:kthread_create_worker
```
**Symbols:**

```
ffffffe0000df7cc-ffffffe0000df8ce: __kthread_create_worker (STB_LOCAL)
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
struct kthread_worker *__kthread_create_worker(int cpu, unsigned int flags, const char *namefmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c2f10)
Location: kernel/kthread.c:694
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_create_worker_on_cpu
  - kernel/kthread.c:kthread_create_worker
```
**Symbols:**

```
ffffffff810c2f10-ffffffff810c3023: __kthread_create_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct kthread_worker *__kthread_create_worker(int cpu, unsigned int flags, const char *namefmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810b1750)
Location: kernel/kthread.c:694
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_create_worker_on_cpu
  - kernel/kthread.c:kthread_create_worker
```
**Symbols:**

```
ffffffff810b1750-ffffffff810b1863: __kthread_create_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct kthread_worker *__kthread_create_worker(int cpu, unsigned int flags, const char *namefmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c2460)
Location: kernel/kthread.c:694
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_create_worker_on_cpu
  - kernel/kthread.c:kthread_create_worker
```
**Symbols:**

```
ffffffff810c2460-ffffffff810c2573: __kthread_create_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct kthread_worker *__kthread_create_worker(int cpu, unsigned int flags, const char *namefmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810caa20)
Location: kernel/kthread.c:694
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_create_worker_on_cpu
  - kernel/kthread.c:kthread_create_worker
```
**Symbols:**

```
ffffffff810caa20-ffffffff810cab33: __kthread_create_worker (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>amd64</code> and <code>arm64</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag *args</code> ➡️ <code>va_list args</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>armhf</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag *args</code> ➡️ <code>va_list args</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>ppc64el</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag *args</code> ➡️ <code>va_list args</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>riscv64</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag *args</code> ➡️ <code>va_list args</code>
</li>
</ul>
</details>
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
