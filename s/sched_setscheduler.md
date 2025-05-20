# Function: <code>sched_setscheduler</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int sched_setscheduler(struct task_struct *p, int policy, const struct sched_param *param);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810aa0c0)
Location: kernel/sched/core.c:4053
Inline: True
Inline callers:
  - kernel/sched/core.c:do_sched_setscheduler
Direct callers:
  - kernel/watchdog.c:watchdog_disable
  - kernel/watchdog.c:watchdog_enable
  - drivers/spi/spi.c:spi_register_master
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
```
**Symbols:**

```
ffffffff810aa0c0-ffffffff810aa0d5: sched_setscheduler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int sched_setscheduler(struct task_struct *p, int policy, const struct sched_param *param);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810acdba)
Location: kernel/sched/core.c:4303
Inline: True
Inline callers:
  - kernel/sched/core.c:do_sched_setscheduler
Direct callers:
  - kernel/watchdog.c:watchdog_disable
  - kernel/watchdog.c:watchdog_enable
  - drivers/spi/spi.c:spi_register_master
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
```
**Symbols:**

```
ffffffff810acd40-ffffffff810acd55: sched_setscheduler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int sched_setscheduler(struct task_struct *p, int policy, const struct sched_param *param);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b2e4a)
Location: kernel/sched/core.c:4340
Inline: True
Inline callers:
  - kernel/sched/core.c:do_sched_setscheduler
Direct callers:
  - kernel/watchdog.c:watchdog_disable
  - kernel/watchdog.c:watchdog_enable
  - drivers/spi/spi.c:spi_register_master
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
```
**Symbols:**

```
ffffffff810b2dd0-ffffffff810b2de5: sched_setscheduler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int sched_setscheduler(struct task_struct *p, int policy, const struct sched_param *param);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810aed65)
Location: kernel/sched/core.c:4240
Inline: True
Inline callers:
  - kernel/sched/core.c:do_sched_setscheduler
Direct callers:
  - kernel/watchdog.c:watchdog_disable
  - kernel/watchdog.c:watchdog_enable
  - drivers/spi/spi.c:spi_register_controller
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
```
**Symbols:**

```
ffffffff810aecf0-ffffffff810aed05: sched_setscheduler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int sched_setscheduler(struct task_struct *p, int policy, const struct sched_param *param);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b5fa5)
Location: kernel/sched/core.c:4284
Inline: True
Inline callers:
  - kernel/sched/core.c:do_sched_setscheduler
Direct callers:
  - kernel/watchdog.c:watchdog_disable
  - kernel/watchdog.c:watchdog_enable
  - drivers/spi/spi.c:spi_register_controller
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
```
**Symbols:**

```
ffffffff810b5f30-ffffffff810b5f45: sched_setscheduler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int sched_setscheduler(struct task_struct *p, int policy, const struct sched_param *param);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bdc05)
Location: kernel/sched/core.c:4414
Inline: True
Inline callers:
  - kernel/sched/core.c:do_sched_setscheduler
Direct callers:
  - kernel/watchdog.c:watchdog_disable
  - kernel/watchdog.c:watchdog_enable
  - drivers/spi/spi.c:spi_register_controller
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
```
**Symbols:**

```
ffffffff810bdb90-ffffffff810bdba5: sched_setscheduler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int sched_setscheduler(struct task_struct *p, int policy, const struct sched_param *param);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c6db5)
Location: kernel/sched/core.c:4399
Inline: True
Inline callers:
  - kernel/sched/core.c:do_sched_setscheduler
Direct callers:
  - drivers/spi/spi.c:spi_register_controller
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/powercap/idle_inject.c:idle_inject_setup
```
**Symbols:**

```
ffffffff810c6d40-ffffffff810c6d55: sched_setscheduler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int sched_setscheduler(struct task_struct *p, int policy, const struct sched_param *param);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cd30d)
Location: kernel/sched/core.c:4836
Inline: True
Inline callers:
  - kernel/sched/core.c:do_sched_setscheduler
Direct callers:
  - drivers/spi/spi.c:spi_set_thread_rt
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/powercap/idle_inject.c:idle_inject_setup
```
**Symbols:**

```
ffffffff810cd290-ffffffff810cd2a5: sched_setscheduler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int sched_setscheduler(struct task_struct *p, int policy, const struct sched_param *param);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d6d15)
Location: kernel/sched/core.c:5051
Inline: True
Inline callers:
  - kernel/sched/core.c:do_sched_setscheduler
Direct callers:
  - drivers/spi/spi.c:spi_set_thread_rt
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/powercap/idle_inject.c:idle_inject_setup
```
**Symbols:**

```
ffffffff810d6c80-ffffffff810d6c95: sched_setscheduler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int sched_setscheduler(struct task_struct *p, int policy, const struct sched_param *param);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e1609)
Location: kernel/sched/core.c:5284
Inline: True
Inline callers:
  - kernel/sched/core.c:do_sched_setscheduler
Direct callers:
  - drivers/spi/spi.c:spi_set_thread_rt
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/powercap/idle_inject.c:idle_inject_setup
```
**Symbols:**

```
ffffffff810e1760-ffffffff810e17f0: sched_setscheduler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int sched_setscheduler(struct task_struct *p, int policy, const struct sched_param *param);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810de992)
Location: kernel/sched/core.c:6061
Inline: True
Inline callers:
  - kernel/sched/core.c:do_sched_setscheduler
```
**Symbols:**

```
ffffffff810e2fd0-ffffffff810e3060: sched_setscheduler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int sched_setscheduler(struct task_struct *p, int policy, const struct sched_param *param);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e0582)
Location: kernel/sched/core.c:6362
Inline: True
Inline callers:
  - kernel/sched/core.c:do_sched_setscheduler
```
**Symbols:**

```
ffffffff810e5170-ffffffff810e5200: sched_setscheduler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int sched_setscheduler(struct task_struct *p, int policy, const struct sched_param *param);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810f57f2)
Location: kernel/sched/core.c:7525
Inline: True
Inline callers:
  - kernel/sched/core.c:do_sched_setscheduler
```
**Symbols:**

```
ffffffff810fc150-ffffffff810fc1e0: sched_setscheduler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int sched_setscheduler(struct task_struct *p, int policy, const struct sched_param *param);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff811122b9)
Location: kernel/sched/core.c:7633
Inline: True
Inline callers:
  - kernel/sched/core.c:do_sched_setscheduler
```
**Symbols:**

```
ffffffff811186a0-ffffffff81118742: sched_setscheduler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int sched_setscheduler(struct task_struct *p, int policy, const struct sched_param *param);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff811392e9)
Location: kernel/sched/core.c:7775
Inline: True
Inline callers:
  - kernel/sched/core.c:do_sched_setscheduler
```
**Symbols:**

```
ffffffff8113fd70-ffffffff8113fe12: sched_setscheduler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int sched_setscheduler(struct task_struct *p, int policy, const struct sched_param *param);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81148559)
Location: kernel/sched/core.c:7884
Inline: True
Inline callers:
  - kernel/sched/core.c:do_sched_setscheduler
```
**Symbols:**

```
ffffffff8114c240-ffffffff8114c2e2: sched_setscheduler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int sched_setscheduler(struct task_struct *p, int policy, const struct sched_param *param);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81153c89)
Location: kernel/sched/core.c:7945
Inline: True
Inline callers:
  - kernel/sched/core.c:do_sched_setscheduler
```
**Symbols:**

```
ffffffff81157f00-ffffffff81157fa2: sched_setscheduler (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int sched_setscheduler(struct task_struct *p, int policy, const struct sched_param *param);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff800010137534)
Location: kernel/sched/core.c:5051
Inline: True
Inline callers:
  - kernel/sched/core.c:do_sched_setscheduler
Direct callers:
  - drivers/spi/spi.c:spi_set_thread_rt
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/powercap/idle_inject.c:idle_inject_setup
```
**Symbols:**

```
ffff800010137480-ffff8000101374c8: sched_setscheduler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int sched_setscheduler(struct task_struct *p, int policy, const struct sched_param *param);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c03864c0)
Location: kernel/sched/core.c:5051
Inline: True
Inline callers:
  - kernel/sched/core.c:do_sched_setscheduler
Direct callers:
  - drivers/spi/spi.c:spi_set_thread_rt
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/powercap/idle_inject.c:idle_inject_setup
```
**Symbols:**

```
c03863d8-c03863f8: sched_setscheduler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int sched_setscheduler(struct task_struct *p, int policy, const struct sched_param *param);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c000000000182b30)
Location: kernel/sched/core.c:5051
Inline: True
Inline callers:
  - kernel/sched/core.c:do_sched_setscheduler
Direct callers:
  - drivers/spi/spi.c:spi_set_thread_rt
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/powercap/idle_inject.c:idle_inject_setup
```
**Symbols:**

```
c000000000182a80-c000000000182a9c: sched_setscheduler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int sched_setscheduler(struct task_struct *p, int policy, const struct sched_param *param);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe0000e7c72)
Location: kernel/sched/core.c:5051
Inline: True
Inline callers:
  - kernel/sched/core.c:do_sched_setscheduler
Direct callers:
  - drivers/spi/spi.c:spi_set_thread_rt
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
```
**Symbols:**

```
ffffffe0000e7bea-ffffffe0000e7c28: sched_setscheduler (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int sched_setscheduler(struct task_struct *p, int policy, const struct sched_param *param);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d12e5)
Location: kernel/sched/core.c:5051
Inline: True
Inline callers:
  - kernel/sched/core.c:do_sched_setscheduler
Direct callers:
  - drivers/spi/spi.c:spi_set_thread_rt
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
```
**Symbols:**

```
ffffffff810d1250-ffffffff810d1265: sched_setscheduler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int sched_setscheduler(struct task_struct *p, int policy, const struct sched_param *param);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bf655)
Location: kernel/sched/core.c:5051
Inline: True
Inline callers:
  - kernel/sched/core.c:do_sched_setscheduler
Direct callers:
  - drivers/spi/spi.c:spi_set_thread_rt
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
```
**Symbols:**

```
ffffffff810bf5c0-ffffffff810bf5d5: sched_setscheduler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int sched_setscheduler(struct task_struct *p, int policy, const struct sched_param *param);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cf3a5)
Location: kernel/sched/core.c:5051
Inline: True
Inline callers:
  - kernel/sched/core.c:do_sched_setscheduler
Direct callers:
  - drivers/spi/spi.c:spi_set_thread_rt
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/powercap/idle_inject.c:idle_inject_setup
```
**Symbols:**

```
ffffffff810cf310-ffffffff810cf325: sched_setscheduler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int sched_setscheduler(struct task_struct *p, int policy, const struct sched_param *param);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d89ca)
Location: kernel/sched/core.c:5051
Inline: True
Inline callers:
  - kernel/sched/core.c:do_sched_setscheduler
Direct callers:
  - drivers/spi/spi.c:spi_set_thread_rt
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/powercap/idle_inject.c:idle_inject_setup
```
**Symbols:**

```
ffffffff810d8930-ffffffff810d8945: sched_setscheduler (STB_GLOBAL)
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
