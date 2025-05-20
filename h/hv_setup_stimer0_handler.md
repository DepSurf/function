# Function: <code>hv_setup_stimer0_handler</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void hv_setup_stimer0_handler(void (*handler)());
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff8106a360)
Location: arch/x86/kernel/cpu/mshyperv.c:94
Inline: False
```
**Symbols:**

```
ffffffff8106a360-ffffffff8106a372: hv_setup_stimer0_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void hv_setup_stimer0_handler(void (*handler)());
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81074b20)
Location: arch/x86/kernel/cpu/mshyperv.c:89
Inline: False
Direct callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_alloc
```
**Symbols:**

```
ffffffff81074b20-ffffffff81074b32: hv_setup_stimer0_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void hv_setup_stimer0_handler(void (*handler)());
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81083460)
Location: arch/x86/kernel/cpu/mshyperv.c:91
Inline: False
Direct callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_alloc
```
**Symbols:**

```
ffffffff81083460-ffffffff81083478: hv_setup_stimer0_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void hv_setup_stimer0_handler(void (*handler)());
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81096050)
Location: arch/x86/kernel/cpu/mshyperv.c:91
Inline: False
Direct callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_alloc
```
**Symbols:**

```
ffffffff81096050-ffffffff81096068: hv_setup_stimer0_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void hv_setup_stimer0_handler(void (*handler)());
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81099170)
Location: arch/x86/kernel/cpu/mshyperv.c:156
Inline: False
Direct callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_alloc
```
**Symbols:**

```
ffffffff81099170-ffffffff81099188: hv_setup_stimer0_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void hv_setup_stimer0_handler(void (*handler)());
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff810a07d0)
Location: arch/x86/kernel/cpu/mshyperv.c:161
Inline: False
Direct callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_alloc
```
**Symbols:**

```
ffffffff810a07d0-ffffffff810a07e8: hv_setup_stimer0_handler (STB_GLOBAL)
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
