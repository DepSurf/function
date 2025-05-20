# Function: <code>smpboot_register_percpu_thread_cpumask</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int smpboot_register_percpu_thread_cpumask(struct smp_hotplug_thread *plug_thread, const struct cpumask *cpumask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810a3c90)
Location: kernel/smpboot.c:282
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_enable_all_cpus
```
**Symbols:**

```
ffffffff810a3c90-ffffffff810a3daa: smpboot_register_percpu_thread_cpumask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int smpboot_register_percpu_thread_cpumask(struct smp_hotplug_thread *plug_thread, const struct cpumask *cpumask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810a73b0)
Location: kernel/smpboot.c:284
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_threads_init
  - kernel/watchdog.c:watchdog_enable_all_cpus
```
**Symbols:**

```
ffffffff810a73b0-ffffffff810a74c6: smpboot_register_percpu_thread_cpumask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int smpboot_register_percpu_thread_cpumask(struct smp_hotplug_thread *plug_thread, const struct cpumask *cpumask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810acec0)
Location: kernel/smpboot.c:289
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_threads_init
  - kernel/watchdog.c:watchdog_enable_all_cpus
```
**Symbols:**

```
ffffffff810acec0-ffffffff810ad001: smpboot_register_percpu_thread_cpumask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int smpboot_register_percpu_thread_cpumask(struct smp_hotplug_thread *plug_thread, const struct cpumask *cpumask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810a9c00)
Location: kernel/smpboot.c:290
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_threads_init
  - kernel/watchdog.c:watchdog_enable_all_cpus
```
**Symbols:**

```
ffffffff810a9c00-ffffffff810a9d3c: smpboot_register_percpu_thread_cpumask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int smpboot_register_percpu_thread_cpumask(struct smp_hotplug_thread *plug_thread, const struct cpumask *cpumask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810b0330)
Location: kernel/smpboot.c:290
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_threads_init
  - kernel/watchdog.c:lockup_detector_init
```
**Symbols:**

```
ffffffff810b0330-ffffffff810b0462: smpboot_register_percpu_thread_cpumask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int smpboot_register_percpu_thread_cpumask(struct smp_hotplug_thread *plug_thread, const struct cpumask *cpumask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810b7150)
Location: kernel/smpboot.c:290
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_threads_init
  - kernel/softirq.c:spawn_ksoftirqd
  - kernel/stop_machine.c:cpu_stop_init
  - kernel/watchdog.c:lockup_detector_init
```
**Symbols:**

```
ffffffff810b7150-ffffffff810b7282: smpboot_register_percpu_thread_cpumask (STB_GLOBAL)
```
</details>
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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
</ul>
