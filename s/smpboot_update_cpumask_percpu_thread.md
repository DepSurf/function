# Function: <code>smpboot_update_cpumask_percpu_thread</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int smpboot_update_cpumask_percpu_thread(struct smp_hotplug_thread *plug_thread, const struct cpumask *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810a3930)
Location: kernel/smpboot.c:339
Inline: False
Direct callers:
  - kernel/watchdog.c:proc_watchdog_cpumask
```
**Symbols:**

```
ffffffff810a3930-ffffffff810a3a7d: smpboot_update_cpumask_percpu_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int smpboot_update_cpumask_percpu_thread(struct smp_hotplug_thread *plug_thread, const struct cpumask *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810a7050)
Location: kernel/smpboot.c:341
Inline: False
Direct callers:
  - kernel/watchdog.c:proc_watchdog_cpumask
```
**Symbols:**

```
ffffffff810a7050-ffffffff810a71a0: smpboot_update_cpumask_percpu_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int smpboot_update_cpumask_percpu_thread(struct smp_hotplug_thread *plug_thread, const struct cpumask *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810ad010)
Location: kernel/smpboot.c:346
Inline: False
Direct callers:
  - kernel/watchdog.c:proc_watchdog_cpumask
```
**Symbols:**

```
ffffffff810ad010-ffffffff810ad180: smpboot_update_cpumask_percpu_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int smpboot_update_cpumask_percpu_thread(struct smp_hotplug_thread *plug_thread, const struct cpumask *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810a9a90)
Location: kernel/smpboot.c:347
Inline: False
Direct callers:
  - kernel/watchdog.c:proc_watchdog_cpumask
```
**Symbols:**

```
ffffffff810a9a90-ffffffff810a9bfc: smpboot_update_cpumask_percpu_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void smpboot_update_cpumask_percpu_thread(struct smp_hotplug_thread *plug_thread, const struct cpumask *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810b0680)
Location: kernel/smpboot.c:347
Inline: False
Direct callers:
  - kernel/watchdog.c:lockup_detector_reconfigure
  - kernel/watchdog.c:lockup_detector_reconfigure
```
**Symbols:**

```
ffffffff810b0680-ffffffff810b07a8: smpboot_update_cpumask_percpu_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void smpboot_update_cpumask_percpu_thread(struct smp_hotplug_thread *plug_thread, const struct cpumask *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810b74a0)
Location: kernel/smpboot.c:347
Inline: False
Direct callers:
  - kernel/watchdog.c:lockup_detector_reconfigure
  - kernel/watchdog.c:lockup_detector_reconfigure
```
**Symbols:**

```
ffffffff810b74a0-ffffffff810b75c3: smpboot_update_cpumask_percpu_thread (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
