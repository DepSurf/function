# Function: <code>ltc2952_poweroff_timer_trigger</code>

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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
enum hrtimer_restart ltc2952_poweroff_timer_trigger(struct hrtimer *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/reset/ltc2952-poweroff.c (ffff800010ac9d60)
Location: drivers/power/reset/ltc2952-poweroff.c:118
Inline: False
```
**Symbols:**

```
ffff800010ac9d60-ffff800010ac9db4: ltc2952_poweroff_timer_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
enum hrtimer_restart ltc2952_poweroff_timer_trigger(struct hrtimer *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/reset/ltc2952-poweroff.c (c0baaa30)
Location: drivers/power/reset/ltc2952-poweroff.c:118
Inline: False
```
**Symbols:**

```
c0baaa30-c0baaa90: ltc2952_poweroff_timer_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
enum hrtimer_restart ltc2952_poweroff_timer_trigger(struct hrtimer *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/reset/ltc2952-poweroff.c (c000000000baba30)
Location: drivers/power/reset/ltc2952-poweroff.c:118
Inline: False
```
**Symbols:**

```
c000000000baba30-c000000000babaa4: ltc2952_poweroff_timer_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
enum hrtimer_restart ltc2952_poweroff_timer_trigger(struct hrtimer *timer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/reset/ltc2952-poweroff.c (ffffffe0006c7ba2)
Location: drivers/power/reset/ltc2952-poweroff.c:118
Inline: False
```
**Symbols:**

```
ffffffe0006c7ba2-ffffffe0006c7bf2: ltc2952_poweroff_timer_trigger (STB_LOCAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
