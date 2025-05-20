# Function: <code>kthread_create_worker</code>

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
struct kthread_worker *kthread_create_worker(unsigned int flags, const char *namefmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a97e0)
Location: kernel/kthread.c:696
Inline: False
```
**Symbols:**

```
ffffffff810a97e0-ffffffff810a9854: kthread_create_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct kthread_worker *kthread_create_worker(unsigned int flags, const char *namefmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a6490)
Location: kernel/kthread.c:702
Inline: False
```
**Symbols:**

```
ffffffff810a6490-ffffffff810a6504: kthread_create_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct kthread_worker *kthread_create_worker(unsigned int flags, const char *namefmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810acac0)
Location: kernel/kthread.c:709
Inline: False
```
**Symbols:**

```
ffffffff810acac0-ffffffff810acb34: kthread_create_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct kthread_worker *kthread_create_worker(unsigned int flags, const char *namefmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810b3510)
Location: kernel/kthread.c:727
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
```
**Symbols:**

```
ffffffff810b3510-ffffffff810b3584: kthread_create_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct kthread_worker *kthread_create_worker(unsigned int flags, const char *namefmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810bc650)
Location: kernel/kthread.c:729
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
```
**Symbols:**

```
ffffffff810bc650-ffffffff810bc6c4: kthread_create_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct kthread_worker *kthread_create_worker(unsigned int flags, const char *namefmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c2570)
Location: kernel/kthread.c:738
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
```
**Symbols:**

```
ffffffff810c2570-ffffffff810c25e4: kthread_create_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct kthread_worker *kthread_create_worker(unsigned int flags, const char *namefmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c8cb0)
Location: kernel/kthread.c:738
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
```
**Symbols:**

```
ffffffff810c8cb0-ffffffff810c8d24: kthread_create_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct kthread_worker *kthread_create_worker(unsigned int flags, const char *namefmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810d0f50)
Location: kernel/kthread.c:774
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
```
**Symbols:**

```
ffffffff810d0f50-ffffffff810d0fc4: kthread_create_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct kthread_worker *kthread_create_worker(unsigned int flags, const char *namefmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810cba00)
Location: kernel/kthread.c:807
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_controller_initialize_queue
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
```
**Symbols:**

```
ffffffff810cba00-ffffffff810cba74: kthread_create_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct kthread_worker *kthread_create_worker(unsigned int flags, const char *namefmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810cd280)
Location: kernel/kthread.c:834
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_register_controller
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
```
**Symbols:**

```
ffffffff810cd280-ffffffff810cd2f4: kthread_create_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct kthread_worker *kthread_create_worker(unsigned int flags, const char *namefmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810e0470)
Location: kernel/kthread.c:834
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_register_controller
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
```
**Symbols:**

```
ffffffff810e0470-ffffffff810e04e4: kthread_create_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct kthread_worker *kthread_create_worker(unsigned int flags, const char *namefmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810fa1b0)
Location: kernel/kthread.c:894
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_register_controller
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
```
**Symbols:**

```
ffffffff810fa1b0-ffffffff810fa23e: kthread_create_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct kthread_worker *kthread_create_worker(unsigned int flags, const char *namefmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff8111cf40)
Location: kernel/kthread.c:895
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_controller_initialize_queue
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
```
**Symbols:**

```
ffffffff8111cf40-ffffffff8111cfce: kthread_create_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct kthread_worker *kthread_create_worker(unsigned int flags, const char *namefmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff8112a060)
Location: kernel/kthread.c:896
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_controller_initialize_queue
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
```
**Symbols:**

```
ffffffff8112a060-ffffffff8112a0ee: kthread_create_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct kthread_worker *kthread_create_worker(unsigned int flags, const char *namefmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff811346f0)
Location: kernel/kthread.c:913
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_init
  - drivers/gpu/drm/drm_vblank_work.c:drm_vblank_worker_init
  - drivers/spi/spi.c:spi_controller_initialize_queue
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
```
**Symbols:**

```
ffffffff811346f0-ffffffff8113477e: kthread_create_worker (STB_GLOBAL)
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
struct kthread_worker *kthread_create_worker(unsigned int flags, const char *namefmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffff800010128338)
Location: kernel/kthread.c:738
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
```
**Symbols:**

```
ffff800010128338-ffff8000101283d4: kthread_create_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct kthread_worker *kthread_create_worker(unsigned int flags, const char *namefmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (c037b280)
Location: kernel/kthread.c:738
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
```
**Symbols:**

```
c037b280-c037b2ec: kthread_create_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct kthread_worker *kthread_create_worker(unsigned int flags, const char *namefmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (c0000000001729b0)
Location: kernel/kthread.c:738
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
```
**Symbols:**

```
c0000000001729b0-c000000000172a10: kthread_create_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct kthread_worker *kthread_create_worker(unsigned int flags, const char *namefmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffe0000df8ce)
Location: kernel/kthread.c:738
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
```
**Symbols:**

```
ffffffe0000df8ce-ffffffe0000df918: kthread_create_worker (STB_GLOBAL)
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
struct kthread_worker *kthread_create_worker(unsigned int flags, const char *namefmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c3030)
Location: kernel/kthread.c:738
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
```
**Symbols:**

```
ffffffff810c3030-ffffffff810c30a4: kthread_create_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct kthread_worker *kthread_create_worker(unsigned int flags, const char *namefmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810b1870)
Location: kernel/kthread.c:738
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
```
**Symbols:**

```
ffffffff810b1870-ffffffff810b18e4: kthread_create_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct kthread_worker *kthread_create_worker(unsigned int flags, const char *namefmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c2580)
Location: kernel/kthread.c:738
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
```
**Symbols:**

```
ffffffff810c2580-ffffffff810c25f4: kthread_create_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct kthread_worker *kthread_create_worker(unsigned int flags, const char *namefmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810cab40)
Location: kernel/kthread.c:738
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
```
**Symbols:**

```
ffffffff810cab40-ffffffff810cabb4: kthread_create_worker (STB_GLOBAL)
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
