# Function: <code>do_wait_intr</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int do_wait_intr(wait_queue_head_t *wq, wait_queue_entry_t *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810c9970)
Location: kernel/sched/wait.c:253
Inline: False
```
**Symbols:**

```
ffffffff810c9970-ffffffff810c99f0: do_wait_intr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int do_wait_intr(wait_queue_head_t *wq, wait_queue_entry_t *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810d1190)
Location: kernel/sched/wait.c:308
Inline: False
```
**Symbols:**

```
ffffffff810d1190-ffffffff810d1210: do_wait_intr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int do_wait_intr(wait_queue_head_t *wq, wait_queue_entry_t *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810d96d0)
Location: kernel/sched/wait.c:302
Inline: False
```
**Symbols:**

```
ffffffff810d96d0-ffffffff810d9751: do_wait_intr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int do_wait_intr(wait_queue_head_t *wq, wait_queue_entry_t *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810e31d0)
Location: kernel/sched/wait.c:304
Inline: False
```
**Symbols:**

```
ffffffff810e31d0-ffffffff810e3251: do_wait_intr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int do_wait_intr(wait_queue_head_t *wq, wait_queue_entry_t *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810e9dd0)
Location: kernel/sched/wait.c:301
Inline: False
```
**Symbols:**

```
ffffffff810e9dd0-ffffffff810e9e5c: do_wait_intr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int do_wait_intr(wait_queue_head_t *wq, wait_queue_entry_t *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810f57a0)
Location: kernel/sched/wait.c:301
Inline: False
```
**Symbols:**

```
ffffffff810f57a0-ffffffff810f582c: do_wait_intr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int do_wait_intr(wait_queue_head_t *wq, wait_queue_entry_t *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810ff060)
Location: kernel/sched/wait.c:318
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:lineinfo_watch_read
  - drivers/gpio/gpiolib.c:lineevent_read
```
**Symbols:**

```
ffffffff810ff060-ffffffff810ff0e8: do_wait_intr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_wait_intr(wait_queue_head_t *wq, wait_queue_entry_t *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810fd9a0)
Location: kernel/sched/wait.c:333
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_watch_read
  - drivers/gpio/gpiolib-cdev.c:linereq_read
```
**Symbols:**

```
ffffffff810fd9a0-ffffffff810fda32: do_wait_intr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int do_wait_intr(wait_queue_head_t *wq, wait_queue_entry_t *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810fff30)
Location: kernel/sched/wait.c:338
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_watch_read
  - drivers/gpio/gpiolib-cdev.c:linereq_read
```
**Symbols:**

```
ffffffff810fff30-ffffffff810fffc2: do_wait_intr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int do_wait_intr(wait_queue_head_t *wq, wait_queue_entry_t *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff8111bff0)
Location: kernel/sched/wait.c:346
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_watch_read
  - drivers/gpio/gpiolib-cdev.c:linereq_read
```
**Symbols:**

```
ffffffff8111bff0-ffffffff8111c06f: do_wait_intr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_wait_intr(wait_queue_head_t *wq, wait_queue_entry_t *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff811400b0)
Location: kernel/sched/wait.c:345
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_watch_read
  - drivers/gpio/gpiolib-cdev.c:lineevent_read
  - drivers/gpio/gpiolib-cdev.c:linereq_read
```
**Symbols:**

```
ffffffff811400b0-ffffffff81140144: do_wait_intr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_wait_intr(wait_queue_head_t *wq, wait_queue_entry_t *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8116c310)
Location: kernel/sched/wait.c:349
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_watch_read_unlocked
  - drivers/gpio/gpiolib-cdev.c:lineevent_read_unlocked
  - drivers/gpio/gpiolib-cdev.c:linereq_read_unlocked
```
**Symbols:**

```
ffffffff8116c310-ffffffff8116c3a4: do_wait_intr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_wait_intr(wait_queue_head_t *wq, wait_queue_entry_t *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8117cbd0)
Location: kernel/sched/wait.c:349
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_watch_read_unlocked
  - drivers/gpio/gpiolib-cdev.c:lineevent_read_unlocked
  - drivers/gpio/gpiolib-cdev.c:linereq_read_unlocked
```
**Symbols:**

```
ffffffff8117cbd0-ffffffff8117cc64: do_wait_intr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_wait_intr(wait_queue_head_t *wq, wait_queue_entry_t *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8118a850)
Location: kernel/sched/wait.c:314
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_watch_read
  - drivers/gpio/gpiolib-cdev.c:lineevent_read
  - drivers/gpio/gpiolib-cdev.c:linereq_read
```
**Symbols:**

```
ffffffff8118a850-ffffffff8118a8e4: do_wait_intr (STB_GLOBAL)
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
int do_wait_intr(wait_queue_head_t *wq, wait_queue_entry_t *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffff8000101583b8)
Location: kernel/sched/wait.c:301
Inline: False
```
**Symbols:**

```
ffff8000101583b8-ffff8000101584a8: do_wait_intr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int do_wait_intr(wait_queue_head_t *wq, wait_queue_entry_t *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (c03a5f68)
Location: kernel/sched/wait.c:301
Inline: False
```
**Symbols:**

```
c03a5f68-c03a6048: do_wait_intr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int do_wait_intr(wait_queue_head_t *wq, wait_queue_entry_t *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (c0000000001ad020)
Location: kernel/sched/wait.c:301
Inline: False
```
**Symbols:**

```
c0000000001ad020-c0000000001ad12c: do_wait_intr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int do_wait_intr(wait_queue_head_t *wq, wait_queue_entry_t *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffe0000fef60)
Location: kernel/sched/wait.c:301
Inline: False
```
**Symbols:**

```
ffffffe0000fef60-ffffffe0000ff01c: do_wait_intr (STB_GLOBAL)
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
int do_wait_intr(wait_queue_head_t *wq, wait_queue_entry_t *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810eeba0)
Location: kernel/sched/wait.c:301
Inline: False
```
**Symbols:**

```
ffffffff810eeba0-ffffffff810eec2c: do_wait_intr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int do_wait_intr(wait_queue_head_t *wq, wait_queue_entry_t *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810dec30)
Location: kernel/sched/wait.c:301
Inline: False
```
**Symbols:**

```
ffffffff810dec30-ffffffff810decbc: do_wait_intr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int do_wait_intr(wait_queue_head_t *wq, wait_queue_entry_t *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810ebcd0)
Location: kernel/sched/wait.c:301
Inline: False
```
**Symbols:**

```
ffffffff810ebcd0-ffffffff810ebd5c: do_wait_intr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int do_wait_intr(wait_queue_head_t *wq, wait_queue_entry_t *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810f6d30)
Location: kernel/sched/wait.c:301
Inline: False
```
**Symbols:**

```
ffffffff810f6d30-ffffffff810f6dba: do_wait_intr (STB_GLOBAL)
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
