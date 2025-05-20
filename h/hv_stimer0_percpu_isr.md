# Function: <code>hv_stimer0_percpu_isr</code>

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
irqreturn_t hv_stimer0_percpu_isr(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff819a7670)
Location: drivers/clocksource/hyperv_timer.c:70
Inline: False
```
**Symbols:**

```
ffffffff819a7670-ffffffff819a7697: hv_stimer0_percpu_isr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
irqreturn_t hv_stimer0_percpu_isr(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81a54b70)
Location: drivers/clocksource/hyperv_timer.c:70
Inline: False
```
**Symbols:**

```
ffffffff81a54b70-ffffffff81a54b97: hv_stimer0_percpu_isr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
irqreturn_t hv_stimer0_percpu_isr(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81bc4180)
Location: drivers/clocksource/hyperv_timer.c:70
Inline: False
```
**Symbols:**

```
ffffffff81bc4180-ffffffff81bc41ad: hv_stimer0_percpu_isr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
irqreturn_t hv_stimer0_percpu_isr(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81d69890)
Location: drivers/clocksource/hyperv_timer.c:71
Inline: False
```
**Symbols:**

```
ffffffff81d69890-ffffffff81d698bd: hv_stimer0_percpu_isr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
irqreturn_t hv_stimer0_percpu_isr(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81dd4d80)
Location: drivers/clocksource/hyperv_timer.c:71
Inline: False
```
**Symbols:**

```
ffffffff81dd4d80-ffffffff81dd4dad: hv_stimer0_percpu_isr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
irqreturn_t hv_stimer0_percpu_isr(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81e8ced0)
Location: drivers/clocksource/hyperv_timer.c:71
Inline: False
```
**Symbols:**

```
ffffffff81e8ced0-ffffffff81e8cefd: hv_stimer0_percpu_isr (STB_LOCAL)
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
