# Function: <code>hv_stimer_init</code>

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
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void hv_stimer_init(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff818bc9f0)
Location: drivers/clocksource/hyperv_timer.c:104
Inline: True
```
**Symbols:**

```
ffffffff818bc9f0-ffffffff818bca87: hv_stimer_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void hv_stimer_init(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff818ef460)
Location: drivers/clocksource/hyperv_timer.c:105
Inline: True
```
**Symbols:**

```
ffffffff818ef460-ffffffff818ef4f7: hv_stimer_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int hv_stimer_init(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff819c2e80)
Location: drivers/clocksource/hyperv_timer.c:115
Inline: False
Direct callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_legacy_init
```
**Symbols:**

```
ffffffff819c2e80-ffffffff819c2f15: hv_stimer_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int hv_stimer_init(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff819c3270)
Location: drivers/clocksource/hyperv_timer.c:115
Inline: False
Direct callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_legacy_init
```
**Symbols:**

```
ffffffff819c3270-ffffffff819c3305: hv_stimer_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int hv_stimer_init(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff819a76e0)
Location: drivers/clocksource/hyperv_timer.c:128
Inline: False
Direct callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_legacy_init
```
**Symbols:**

```
ffffffff819a76e0-ffffffff819a7775: hv_stimer_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int hv_stimer_init(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81a54be0)
Location: drivers/clocksource/hyperv_timer.c:128
Inline: False
Direct callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_legacy_init
```
**Symbols:**

```
ffffffff81a54be0-ffffffff81a54cc7: hv_stimer_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int hv_stimer_init(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81bc41f0)
Location: drivers/clocksource/hyperv_timer.c:128
Inline: False
Direct callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_legacy_init
```
**Symbols:**

```
ffffffff81bc41f0-ffffffff81bc42dd: hv_stimer_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int hv_stimer_init(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81d69960)
Location: drivers/clocksource/hyperv_timer.c:129
Inline: False
Direct callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_legacy_init
```
**Symbols:**

```
ffffffff81d69960-ffffffff81d69a4d: hv_stimer_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int hv_stimer_init(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81dd4fd0)
Location: drivers/clocksource/hyperv_timer.c:129
Inline: False
Direct callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_legacy_init
```
**Symbols:**

```
ffffffff81dd4fd0-ffffffff81dd50bd: hv_stimer_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int hv_stimer_init(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81e8d120)
Location: drivers/clocksource/hyperv_timer.c:129
Inline: False
Direct callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_legacy_init
```
**Symbols:**

```
ffffffff81e8d120-ffffffff81e8d20d: hv_stimer_init (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void hv_stimer_init(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81890830)
Location: drivers/clocksource/hyperv_timer.c:105
Inline: True
```
**Symbols:**

```
ffffffff81890830-ffffffff818908c7: hv_stimer_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void hv_stimer_init(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81849a30)
Location: drivers/clocksource/hyperv_timer.c:105
Inline: True
Direct callers:
  - drivers/hv/hv.c:hv_synic_init
```
**Symbols:**

```
ffffffff81849a30-ffffffff81849ac7: hv_stimer_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void hv_stimer_init(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff818e4290)
Location: drivers/clocksource/hyperv_timer.c:105
Inline: True
```
**Symbols:**

```
ffffffff818e4290-ffffffff818e4327: hv_stimer_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void hv_stimer_init(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81900ef0)
Location: drivers/clocksource/hyperv_timer.c:105
Inline: True
```
**Symbols:**

```
ffffffff81900ef0-ffffffff81900f87: hv_stimer_init (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
