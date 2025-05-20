# Function: <code>__lockup_detector_reconfigure</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __lockup_detector_reconfigure();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/watchdog.c (0)
Location: kernel/watchdog.c:540
Inline: False
Direct callers:
  - kernel/watchdog.c:lockup_detector_init
  - kernel/watchdog.c:proc_watchdog_update
  - kernel/watchdog.c:lockup_detector_reconfigure
```
**Symbols:**

```
ffffffff811ffd90-ffffffff811ffee5: __lockup_detector_reconfigure (STB_LOCAL)
ffffffff81e64d73-ffffffff81e64da0: __lockup_detector_reconfigure.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __lockup_detector_reconfigure();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/watchdog.c (0)
Location: kernel/watchdog.c:540
Inline: False
Direct callers:
  - kernel/watchdog.c:lockup_detector_init
  - kernel/watchdog.c:proc_watchdog_update
  - kernel/watchdog.c:lockup_detector_reconfigure
```
**Symbols:**

```
ffffffff81247850-ffffffff812479ce: __lockup_detector_reconfigure (STB_LOCAL)
ffffffff8205c927-ffffffff8205c93c: __lockup_detector_reconfigure.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __lockup_detector_reconfigure();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/watchdog.c (0)
Location: kernel/watchdog.c:623
Inline: False
Direct callers:
  - kernel/watchdog.c:lockup_detector_init
  - kernel/watchdog.c:lockup_detector_delay_init
  - kernel/watchdog.c:proc_watchdog_update
  - kernel/watchdog.c:lockup_detector_reconfigure
```
**Symbols:**

```
ffffffff8125ec70-ffffffff8125edee: __lockup_detector_reconfigure (STB_LOCAL)
ffffffff820db2cd-ffffffff820db2e2: __lockup_detector_reconfigure.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __lockup_detector_reconfigure();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/watchdog.c (0)
Location: kernel/watchdog.c:654
Inline: False
Direct callers:
  - kernel/watchdog.c:lockup_detector_init
  - kernel/watchdog.c:lockup_detector_delay_init
  - kernel/watchdog.c:proc_watchdog_update
  - kernel/watchdog.c:lockup_detector_reconfigure
```
**Symbols:**

```
ffffffff81278c80-ffffffff81278dfe: __lockup_detector_reconfigure (STB_LOCAL)
ffffffff821b6fee-ffffffff821b7003: __lockup_detector_reconfigure.cold (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
