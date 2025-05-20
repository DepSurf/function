# Function: <code>hv_remove_stimer0_handler</code>

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
void hv_remove_stimer0_handler();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff8106a380)
Location: arch/x86/kernel/cpu/mshyperv.c:99
Inline: False
Direct callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
```
**Symbols:**

```
ffffffff8106a380-ffffffff8106a396: hv_remove_stimer0_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void hv_remove_stimer0_handler();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81074b40)
Location: arch/x86/kernel/cpu/mshyperv.c:94
Inline: False
Direct callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
  - drivers/clocksource/hyperv_timer.c:hv_stimer_alloc
```
**Symbols:**

```
ffffffff81074b40-ffffffff81074b56: hv_remove_stimer0_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void hv_remove_stimer0_handler();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81083480)
Location: arch/x86/kernel/cpu/mshyperv.c:96
Inline: False
Direct callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
  - drivers/clocksource/hyperv_timer.c:hv_stimer_alloc
```
**Symbols:**

```
ffffffff81083480-ffffffff8108349a: hv_remove_stimer0_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void hv_remove_stimer0_handler();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81096080)
Location: arch/x86/kernel/cpu/mshyperv.c:96
Inline: False
Direct callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
  - drivers/clocksource/hyperv_timer.c:hv_stimer_alloc
```
**Symbols:**

```
ffffffff81096080-ffffffff8109609a: hv_remove_stimer0_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void hv_remove_stimer0_handler();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff810991a0)
Location: arch/x86/kernel/cpu/mshyperv.c:161
Inline: False
Direct callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
  - drivers/clocksource/hyperv_timer.c:hv_stimer_alloc
```
**Symbols:**

```
ffffffff810991a0-ffffffff810991ba: hv_remove_stimer0_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void hv_remove_stimer0_handler();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff810a0800)
Location: arch/x86/kernel/cpu/mshyperv.c:166
Inline: False
Direct callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
  - drivers/clocksource/hyperv_timer.c:hv_stimer_alloc
```
**Symbols:**

```
ffffffff810a0800-ffffffff810a081a: hv_remove_stimer0_handler (STB_GLOBAL)
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
