# Function: <code>watchdog_unpark_threads</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void watchdog_unpark_threads();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff8113ad30)
Location: kernel/watchdog.c:709
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_enable_all_cpus
  - kernel/watchdog.c:lockup_detector_resume
```
**Symbols:**

```
ffffffff8113ad30-ffffffff8113ad89: watchdog_unpark_threads (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void watchdog_unpark_threads();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff81143260)
Location: kernel/watchdog.c:725
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_enable_all_cpus
  - kernel/watchdog.c:lockup_detector_resume
```
**Symbols:**

```
ffffffff81143260-ffffffff811432b2: watchdog_unpark_threads (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void watchdog_unpark_threads();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff8114cd70)
Location: kernel/watchdog.c:494
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_enable_all_cpus
  - kernel/watchdog.c:lockup_detector_resume
```
**Symbols:**

```
ffffffff8114cd70-ffffffff8114cdc2: watchdog_unpark_threads (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void watchdog_unpark_threads();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff8114ecf0)
Location: kernel/watchdog.c:565
Inline: False
Direct callers:
  - kernel/watchdog.c:lockup_detector_resume
  - kernel/watchdog.c:watchdog_enable_all_cpus
```
**Symbols:**

```
ffffffff8114ecf0-ffffffff8114ed42: watchdog_unpark_threads (STB_LOCAL)
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
