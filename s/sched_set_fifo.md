# Function: <code>sched_set_fifo</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void sched_set_fifo(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dec50)
Location: kernel/sched/core.c:6114
Inline: True
Direct callers:
  - kernel/irq/manage.c:setup_irq_thread
  - drivers/spi/spi.c:spi_set_thread_rt
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
  - drivers/powercap/idle_inject.c:idle_inject_setup
```
**Symbols:**

```
ffffffff810dec50-ffffffff810decc4: sched_set_fifo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void sched_set_fifo(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e08c0)
Location: kernel/sched/core.c:6415
Inline: True
Direct callers:
  - kernel/irq/manage.c:setup_irq_thread
  - drivers/spi/spi.c:spi_set_thread_rt
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
  - drivers/powercap/idle_inject.c:idle_inject_setup
```
**Symbols:**

```
ffffffff810e08c0-ffffffff810e0934: sched_set_fifo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sched_set_fifo(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810f5940)
Location: kernel/sched/core.c:7579
Inline: False
Direct callers:
  - kernel/irq/manage.c:setup_irq_thread
  - drivers/spi/spi.c:spi_set_thread_rt
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
  - drivers/powercap/idle_inject.c:idle_inject_setup
```
**Symbols:**

```
ffffffff810f5940-ffffffff810f59b4: sched_set_fifo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sched_set_fifo(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81112470)
Location: kernel/sched/core.c:7687
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_thread
  - drivers/spi/spi.c:spi_set_thread_rt
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
  - drivers/powercap/idle_inject.c:idle_inject_setup
```
**Symbols:**

```
ffffffff81112470-ffffffff811124f5: sched_set_fifo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sched_set_fifo(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff811394f0)
Location: kernel/sched/core.c:7829
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_thread
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_controller_initialize_queue
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
  - drivers/powercap/idle_inject.c:idle_inject_setup
```
**Symbols:**

```
ffffffff811394f0-ffffffff81139575: sched_set_fifo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sched_set_fifo(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81148760)
Location: kernel/sched/core.c:7938
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_thread
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_controller_initialize_queue
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
  - drivers/powercap/idle_inject.c:idle_inject_setup
```
**Symbols:**

```
ffffffff81148760-ffffffff811487e5: sched_set_fifo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sched_set_fifo(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff811540c0)
Location: kernel/sched/core.c:7999
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_thread
  - drivers/gpu/drm/drm_vblank_work.c:drm_vblank_worker_init
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_controller_initialize_queue
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
  - drivers/powercap/idle_inject.c:idle_inject_setup
```
**Symbols:**

```
ffffffff811540c0-ffffffff81154145: sched_set_fifo (STB_GLOBAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
