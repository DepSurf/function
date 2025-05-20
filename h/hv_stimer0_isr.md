# Function: <code>hv_stimer0_isr</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
void hv_stimer0_isr();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff818bc730)
Location: drivers/clocksource/hyperv_timer.c:44
Inline: False
```
**Symbols:**

```
ffffffff818bc730-ffffffff818bc752: hv_stimer0_isr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void hv_stimer0_isr();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff818ef200)
Location: drivers/clocksource/hyperv_timer.c:45
Inline: False
```
**Symbols:**

```
ffffffff818ef200-ffffffff818ef222: hv_stimer0_isr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void hv_stimer0_isr();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff819c2e10)
Location: drivers/clocksource/hyperv_timer.c:55
Inline: False
```
**Symbols:**

```
ffffffff819c2e10-ffffffff819c2e32: hv_stimer0_isr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void hv_stimer0_isr();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff819c3200)
Location: drivers/clocksource/hyperv_timer.c:55
Inline: False
```
**Symbols:**

```
ffffffff819c3200-ffffffff819c3222: hv_stimer0_isr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void hv_stimer0_isr();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff819a7675)
Location: drivers/clocksource/hyperv_timer.c:57
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer0_percpu_isr
```
**Symbols:**

```
ffffffff819a7640-ffffffff819a7662: hv_stimer0_isr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void hv_stimer0_isr();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81a54b75)
Location: drivers/clocksource/hyperv_timer.c:57
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer0_percpu_isr
```
**Symbols:**

```
ffffffff81a54b40-ffffffff81a54b62: hv_stimer0_isr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void hv_stimer0_isr();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81bc4185)
Location: drivers/clocksource/hyperv_timer.c:57
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer0_percpu_isr
```
**Symbols:**

```
ffffffff81bc4150-ffffffff81bc417a: hv_stimer0_isr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void hv_stimer0_isr();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81d69895)
Location: drivers/clocksource/hyperv_timer.c:58
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer0_percpu_isr
```
**Symbols:**

```
ffffffff81d69850-ffffffff81d6987a: hv_stimer0_isr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void hv_stimer0_isr();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81dd4d85)
Location: drivers/clocksource/hyperv_timer.c:58
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer0_percpu_isr
```
**Symbols:**

```
ffffffff81dd4d40-ffffffff81dd4d6a: hv_stimer0_isr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void hv_stimer0_isr();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81e8ced5)
Location: drivers/clocksource/hyperv_timer.c:58
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer0_percpu_isr
```
**Symbols:**

```
ffffffff81e8ce90-ffffffff81e8ceba: hv_stimer0_isr (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void hv_stimer0_isr();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff818905d0)
Location: drivers/clocksource/hyperv_timer.c:45
Inline: False
```
**Symbols:**

```
ffffffff818905d0-ffffffff818905f2: hv_stimer0_isr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void hv_stimer0_isr();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81849890)
Location: drivers/clocksource/hyperv_timer.c:45
Inline: False
Direct callers:
  - drivers/hv/vmbus_drv.c:vmbus_isr
```
**Symbols:**

```
ffffffff81849890-ffffffff818498b2: hv_stimer0_isr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void hv_stimer0_isr();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff818e4030)
Location: drivers/clocksource/hyperv_timer.c:45
Inline: False
```
**Symbols:**

```
ffffffff818e4030-ffffffff818e4052: hv_stimer0_isr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void hv_stimer0_isr();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81900c90)
Location: drivers/clocksource/hyperv_timer.c:45
Inline: False
```
**Symbols:**

```
ffffffff81900c90-ffffffff81900cb2: hv_stimer0_isr (STB_GLOBAL)
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
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
