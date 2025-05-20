# Function: <code>perf_event_init_all_cpus</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81f86344)
Location: kernel/events/core.c:9262
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81fafa62)
Location: kernel/events/core.c:10452
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81fec0dc)
Location: kernel/events/core.c:10724
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff820cd08f)
Location: kernel/events/core.c:10991
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff826d5acd)
Location: kernel/events/core.c:11023
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff826ffd64)
Location: kernel/events/core.c:11575
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff828b6dce)
Location: kernel/events/core.c:11618
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff828d03e1)
Location: kernel/events/core.c:11983
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff828d881e)
Location: kernel/events/core.c:12100
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void perf_event_init_all_cpus();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff82cf7c28)
Location: kernel/events/core.c:12703
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init
```
**Symbols:**

```
ffffffff82cf7c28-ffffffff82cf7d11: perf_event_init_all_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void perf_event_init_all_cpus();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff82fe4921)
Location: kernel/events/core.c:12986
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init
```
**Symbols:**

```
ffffffff82fe4921-ffffffff82fe4a0a: perf_event_init_all_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff831ef0ec)
Location: kernel/events/core.c:13179
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff832d472e)
Location: kernel/events/core.c:13300
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff83488dd2)
Location: kernel/events/core.c:13270
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff83eb93ec)
Location: kernel/events/core.c:13497
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff836dea1c)
Location: kernel/events/core.c:13539
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8391105c)
Location: kernel/events/core.c:13637
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
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
void perf_event_init_all_cpus();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff800011451240)
Location: kernel/events/core.c:12100
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init
```
**Symbols:**

```
ffff800011451240-ffff800011451344: perf_event_init_all_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c152bd34)
Location: kernel/events/core.c:12100
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c000000001378cb4)
Location: kernel/events/core.c:12100
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe000010e7e)
Location: kernel/events/core.c:12100
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff828c16cf)
Location: kernel/events/core.c:12100
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff828b9d6f)
Location: kernel/events/core.c:12100
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff828d4452)
Location: kernel/events/core.c:12100
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff828d9873)
Location: kernel/events/core.c:12100
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
