# Function: <code>watchdog_enable_all_cpus</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int watchdog_enable_all_cpus();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff8113ad90)
Location: kernel/watchdog.c:781
Inline: False
Direct callers:
  - kernel/watchdog.c:proc_watchdog_update
  - kernel/watchdog.c:lockup_detector_init
```
**Symbols:**

```
ffffffff8113ad90-ffffffff8113ae2c: watchdog_enable_all_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int watchdog_enable_all_cpus();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff811432c0)
Location: kernel/watchdog.c:797
Inline: False
Direct callers:
  - kernel/watchdog.c:lockup_detector_init
  - kernel/watchdog.c:proc_watchdog_update
```
**Symbols:**

```
ffffffff811432c0-ffffffff8114335d: watchdog_enable_all_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int watchdog_enable_all_cpus();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff8114cdd0)
Location: kernel/watchdog.c:566
Inline: False
Direct callers:
  - kernel/watchdog.c:lockup_detector_init
  - kernel/watchdog.c:proc_watchdog_update
```
**Symbols:**

```
ffffffff8114cdd0-ffffffff8114ce6d: watchdog_enable_all_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int watchdog_enable_all_cpus();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff8114ed50)
Location: kernel/watchdog.c:586
Inline: False
Direct callers:
  - kernel/watchdog.c:lockup_detector_init
  - kernel/watchdog.c:proc_watchdog_update
```
**Symbols:**

```
ffffffff8114ed50-ffffffff8114edea: watchdog_enable_all_cpus (STB_LOCAL)
```
</details>
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
</ul>
