# Function: <code>watchdog_park_threads</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int watchdog_park_threads();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff8113a7c0)
Location: kernel/watchdog.c:690
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_enable_all_cpus
  - kernel/watchdog.c:lockup_detector_suspend
```
**Symbols:**

```
ffffffff8113a7c0-ffffffff8113a81f: watchdog_park_threads (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int watchdog_park_threads();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff81142cf0)
Location: kernel/watchdog.c:706
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_enable_all_cpus
  - kernel/watchdog.c:lockup_detector_suspend
```
**Symbols:**

```
ffffffff81142cf0-ffffffff81142d48: watchdog_park_threads (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int watchdog_park_threads();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff8114cae0)
Location: kernel/watchdog.c:471
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_enable_all_cpus
  - kernel/watchdog.c:lockup_detector_suspend
```
**Symbols:**

```
ffffffff8114cae0-ffffffff8114cb4c: watchdog_park_threads (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int watchdog_park_threads();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff8114ea60)
Location: kernel/watchdog.c:542
Inline: False
Direct callers:
  - kernel/watchdog.c:lockup_detector_suspend
  - kernel/watchdog.c:watchdog_enable_all_cpus
```
**Symbols:**

```
ffffffff8114ea60-ffffffff8114eacc: watchdog_park_threads (STB_LOCAL)
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
