# Function: <code>xen_debug_interrupt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
irqreturn_t xen_debug_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_2l.c (ffffffff814ca360)
Location: drivers/xen/events/events_2l.c:264
Inline: False
```
**Symbols:**

```
ffffffff814ca360-ffffffff814ca758: xen_debug_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
irqreturn_t xen_debug_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_2l.c (ffffffff8151aed0)
Location: drivers/xen/events/events_2l.c:264
Inline: False
```
**Symbols:**

```
ffffffff8151aed0-ffffffff8151b2b8: xen_debug_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
irqreturn_t xen_debug_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_2l.c (ffffffff815473a0)
Location: drivers/xen/events/events_2l.c:264
Inline: False
```
**Symbols:**

```
ffffffff815473a0-ffffffff8154778a: xen_debug_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
irqreturn_t xen_debug_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_2l.c (ffffffff8155b170)
Location: drivers/xen/events/events_2l.c:264
Inline: False
```
**Symbols:**

```
ffffffff8155b170-ffffffff8155b53b: xen_debug_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
irqreturn_t xen_debug_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_2l.c (ffffffff815bf4a0)
Location: drivers/xen/events/events_2l.c:265
Inline: False
```
**Symbols:**

```
ffffffff815bf4a0-ffffffff815bf865: xen_debug_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
irqreturn_t xen_debug_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_2l.c (0)
Location: drivers/xen/events/events_2l.c:265
Inline: False
```
**Symbols:**

```
ffffffff815f7c0e-ffffffff815f7f5d: xen_debug_interrupt.cold.3 (STB_LOCAL)
ffffffff815f7b80-ffffffff815f7c0e: xen_debug_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
irqreturn_t xen_debug_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_2l.c (0)
Location: drivers/xen/events/events_2l.c:265
Inline: False
```
**Symbols:**

```
ffffffff81612d2a-ffffffff81613014: xen_debug_interrupt.cold.4 (STB_LOCAL)
ffffffff81612c30-ffffffff81612d2a: xen_debug_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
irqreturn_t xen_debug_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_2l.c (0)
Location: drivers/xen/events/events_2l.c:265
Inline: False
```
**Symbols:**

```
ffffffff81646aee-ffffffff81646e28: xen_debug_interrupt.cold (STB_LOCAL)
ffffffff81646a60-ffffffff81646aee: xen_debug_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
irqreturn_t xen_debug_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_2l.c (0)
Location: drivers/xen/events/events_2l.c:265
Inline: False
```
**Symbols:**

```
ffffffff81668f8e-ffffffff816692c8: xen_debug_interrupt.cold (STB_LOCAL)
ffffffff81668f00-ffffffff81668f8e: xen_debug_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
irqreturn_t xen_debug_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_2l.c (0)
Location: drivers/xen/events/events_2l.c:265
Inline: False
```
**Symbols:**

```
ffffffff8171905e-ffffffff817193c2: xen_debug_interrupt.cold (STB_LOCAL)
ffffffff81718fd0-ffffffff8171905e: xen_debug_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
irqreturn_t xen_debug_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_2l.c (0)
Location: drivers/xen/events/events_2l.c:264
Inline: False
```
**Symbols:**

```
ffffffff81c05018-ffffffff81c0537c: xen_debug_interrupt.cold (STB_LOCAL)
ffffffff81736540-ffffffff817365ce: xen_debug_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
irqreturn_t xen_debug_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_2l.c (0)
Location: drivers/xen/events/events_2l.c:264
Inline: False
```
**Symbols:**

```
ffffffff81bf6c99-ffffffff81bf6fe2: xen_debug_interrupt.cold (STB_LOCAL)
ffffffff81719f80-ffffffff8171a011: xen_debug_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
irqreturn_t xen_debug_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_2l.c (0)
Location: drivers/xen/events/events_2l.c:264
Inline: False
```
**Symbols:**

```
ffffffff81cf59e7-ffffffff81cf5d5c: xen_debug_interrupt.cold (STB_LOCAL)
ffffffff817983e0-ffffffff817985ab: xen_debug_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
irqreturn_t xen_debug_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_2l.c (0)
Location: drivers/xen/events/events_2l.c:264
Inline: False
```
**Symbols:**

```
ffffffff81ebdb34-ffffffff81ebde3e: xen_debug_interrupt.cold (STB_LOCAL)
ffffffff818d1530-ffffffff818d16ed: xen_debug_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
irqreturn_t xen_debug_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_2l.c (ffffffff81a22f40)
Location: drivers/xen/events/events_2l.c:264
Inline: False
```
**Symbols:**

```
ffffffff81a22f40-ffffffff81a23443: xen_debug_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
irqreturn_t xen_debug_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_2l.c (ffffffff81a6c300)
Location: drivers/xen/events/events_2l.c:264
Inline: False
```
**Symbols:**

```
ffffffff81a6c300-ffffffff81a6c8fd: xen_debug_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
irqreturn_t xen_debug_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_2l.c (ffffffff81abe3c0)
Location: drivers/xen/events/events_2l.c:264
Inline: False
```
**Symbols:**

```
ffffffff81abe3c0-ffffffff81abe9bd: xen_debug_interrupt (STB_GLOBAL)
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
irqreturn_t xen_debug_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_2l.c (ffff8000108330f0)
Location: drivers/xen/events/events_2l.c:265
Inline: False
```
**Symbols:**

```
ffff8000108330f0-ffff800010833570: xen_debug_interrupt (STB_GLOBAL)
```
</details>
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
irqreturn_t xen_debug_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_2l.c (0)
Location: drivers/xen/events/events_2l.c:265
Inline: False
```
**Symbols:**

```
ffffffff8162edfe-ffffffff8162f138: xen_debug_interrupt.cold (STB_LOCAL)
ffffffff8162ed70-ffffffff8162edfe: xen_debug_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
irqreturn_t xen_debug_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_2l.c (0)
Location: drivers/xen/events/events_2l.c:265
Inline: False
```
**Symbols:**

```
ffffffff8165cdce-ffffffff8165d108: xen_debug_interrupt.cold (STB_LOCAL)
ffffffff8165cd40-ffffffff8165cdce: xen_debug_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
irqreturn_t xen_debug_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_2l.c (0)
Location: drivers/xen/events/events_2l.c:265
Inline: False
```
**Symbols:**

```
ffffffff816773de-ffffffff81677718: xen_debug_interrupt.cold (STB_LOCAL)
ffffffff81677350-ffffffff816773de: xen_debug_interrupt (STB_GLOBAL)
```
</details>
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
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
