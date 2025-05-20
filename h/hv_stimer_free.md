# Function: <code>hv_stimer_free</code>

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
void hv_stimer_free();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff818bc880)
Location: drivers/clocksource/hyperv_timer.c:174
Inline: False
Direct callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
```
**Symbols:**

```
ffffffff818bc880-ffffffff818bc8c6: hv_stimer_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void hv_stimer_free();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff818ef380)
Location: drivers/clocksource/hyperv_timer.c:175
Inline: False
Direct callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
```
**Symbols:**

```
ffffffff818ef380-ffffffff818ef3c6: hv_stimer_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void hv_stimer_free();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff819c2f40)
Location: drivers/clocksource/hyperv_timer.c:259
Inline: False
Direct callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
```
**Symbols:**

```
ffffffff819c2f40-ffffffff819c2f9e: hv_stimer_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void hv_stimer_free();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff819c3330)
Location: drivers/clocksource/hyperv_timer.c:259
Inline: False
Direct callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
```
**Symbols:**

```
ffffffff819c3330-ffffffff819c338e: hv_stimer_free (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void hv_stimer_free();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81890750)
Location: drivers/clocksource/hyperv_timer.c:175
Inline: False
Direct callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
```
**Symbols:**

```
ffffffff81890750-ffffffff81890796: hv_stimer_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void hv_stimer_free();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81849980)
Location: drivers/clocksource/hyperv_timer.c:175
Inline: False
Direct callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
  - drivers/hv/vmbus_drv.c:hv_acpi_init
```
**Symbols:**

```
ffffffff81849980-ffffffff818499c6: hv_stimer_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void hv_stimer_free();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff818e41b0)
Location: drivers/clocksource/hyperv_timer.c:175
Inline: False
Direct callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
```
**Symbols:**

```
ffffffff818e41b0-ffffffff818e41f6: hv_stimer_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void hv_stimer_free();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81900e10)
Location: drivers/clocksource/hyperv_timer.c:175
Inline: False
Direct callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
```
**Symbols:**

```
ffffffff81900e10-ffffffff81900e56: hv_stimer_free (STB_GLOBAL)
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
