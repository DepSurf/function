# Function: <code>handle_threaded_wake_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
irqreturn_t handle_threaded_wake_irq(int irq, void *_wirq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeirq.c (ffffffff81557fb0)
Location: drivers/base/power/wakeirq.c:137
Inline: False
```
**Symbols:**

```
ffffffff81557fb0-ffffffff81557fec: handle_threaded_wake_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
irqreturn_t handle_threaded_wake_irq(int irq, void *_wirq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeirq.c (ffffffff815aa0c0)
Location: drivers/base/power/wakeirq.c:137
Inline: False
```
**Symbols:**

```
ffffffff815aa0c0-ffffffff815aa0fc: handle_threaded_wake_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
irqreturn_t handle_threaded_wake_irq(int irq, void *_wirq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeirq.c (ffffffff815d8cf0)
Location: drivers/base/power/wakeirq.c:139
Inline: False
```
**Symbols:**

```
ffffffff815d8cf0-ffffffff815d8d2c: handle_threaded_wake_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
irqreturn_t handle_threaded_wake_irq(int irq, void *_wirq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeirq.c (ffffffff815ed900)
Location: drivers/base/power/wakeirq.c:139
Inline: True
```
**Symbols:**

```
ffffffff815ed900-ffffffff815ed960: handle_threaded_wake_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
irqreturn_t handle_threaded_wake_irq(int irq, void *_wirq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeirq.c (ffffffff81654cb0)
Location: drivers/base/power/wakeirq.c:139
Inline: True
```
**Symbols:**

```
ffffffff81654cb0-ffffffff81654d10: handle_threaded_wake_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
irqreturn_t handle_threaded_wake_irq(int irq, void *_wirq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeirq.c (ffffffff81690580)
Location: drivers/base/power/wakeirq.c:138
Inline: True
```
**Symbols:**

```
ffffffff81690580-ffffffff816905e0: handle_threaded_wake_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
irqreturn_t handle_threaded_wake_irq(int irq, void *_wirq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeirq.c (ffffffff816b0d90)
Location: drivers/base/power/wakeirq.c:138
Inline: True
```
**Symbols:**

```
ffffffff816b0d90-ffffffff816b0df0: handle_threaded_wake_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
irqreturn_t handle_threaded_wake_irq(int irq, void *_wirq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeirq.c (ffffffff816eaa77)
Location: drivers/base/power/wakeirq.c:127
Inline: True
```
**Symbols:**

```
ffffffff816eaa40-ffffffff816eaa8b: handle_threaded_wake_irq (STB_LOCAL)
ffffffff816eabb0-ffffffff816eabc6: handle_threaded_wake_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
irqreturn_t handle_threaded_wake_irq(int irq, void *_wirq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeirq.c (ffffffff8170eab7)
Location: drivers/base/power/wakeirq.c:127
Inline: True
```
**Symbols:**

```
ffffffff8170ea80-ffffffff8170eacb: handle_threaded_wake_irq (STB_LOCAL)
ffffffff8170ebf0-ffffffff8170ec06: handle_threaded_wake_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
irqreturn_t handle_threaded_wake_irq(int irq, void *_wirq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeirq.c (ffffffff817ca22a)
Location: drivers/base/power/wakeirq.c:127
Inline: True
```
**Symbols:**

```
ffffffff817ca1f0-ffffffff817ca241: handle_threaded_wake_irq (STB_LOCAL)
ffffffff817ca5f3-ffffffff817ca609: handle_threaded_wake_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
irqreturn_t handle_threaded_wake_irq(int irq, void *_wirq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeirq.c (ffffffff817decca)
Location: drivers/base/power/wakeirq.c:127
Inline: True
```
**Symbols:**

```
ffffffff817dec90-ffffffff817dece1: handle_threaded_wake_irq (STB_LOCAL)
ffffffff81c0ec9e-ffffffff81c0ecb4: handle_threaded_wake_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
irqreturn_t handle_threaded_wake_irq(int irq, void *_wirq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeirq.c (ffffffff817c30ca)
Location: drivers/base/power/wakeirq.c:127
Inline: True
```
**Symbols:**

```
ffffffff817c3090-ffffffff817c30e1: handle_threaded_wake_irq (STB_LOCAL)
ffffffff81c00e20-ffffffff81c00e36: handle_threaded_wake_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
irqreturn_t handle_threaded_wake_irq(int irq, void *_wirq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeirq.c (ffffffff8184d51a)
Location: drivers/base/power/wakeirq.c:124
Inline: True
```
**Symbols:**

```
ffffffff8184d4e0-ffffffff8184d531: handle_threaded_wake_irq (STB_LOCAL)
ffffffff81d038da-ffffffff81d038f0: handle_threaded_wake_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
irqreturn_t handle_threaded_wake_irq(int irq, void *_wirq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeirq.c (ffffffff81992904)
Location: drivers/base/power/wakeirq.c:124
Inline: True
```
**Symbols:**

```
ffffffff819928c0-ffffffff81992922: handle_threaded_wake_irq (STB_LOCAL)
ffffffff81ecc0ab-ffffffff81ecc0c1: handle_threaded_wake_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
irqreturn_t handle_threaded_wake_irq(int irq, void *_wirq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeirq.c (ffffffff81b02db0)
Location: drivers/base/power/wakeirq.c:124
Inline: True
```
**Symbols:**

```
ffffffff81b02db0-ffffffff81b02e34: handle_threaded_wake_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
irqreturn_t handle_threaded_wake_irq(int irq, void *_wirq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeirq.c (ffffffff81b50db0)
Location: drivers/base/power/wakeirq.c:124
Inline: True
```
**Symbols:**

```
ffffffff81b50db0-ffffffff81b50e34: handle_threaded_wake_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
irqreturn_t handle_threaded_wake_irq(int irq, void *_wirq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeirq.c (ffffffff81ba9330)
Location: drivers/base/power/wakeirq.c:124
Inline: True
```
**Symbols:**

```
ffffffff81ba9330-ffffffff81ba93b4: handle_threaded_wake_irq (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
irqreturn_t handle_threaded_wake_irq(int irq, void *_wirq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeirq.c (ffff8000108fea90)
Location: drivers/base/power/wakeirq.c:127
Inline: True
```
**Symbols:**

```
ffff8000108fea90-ffff8000108feb18: handle_threaded_wake_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
irqreturn_t handle_threaded_wake_irq(int irq, void *_wirq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeirq.c (c09e8f30)
Location: drivers/base/power/wakeirq.c:127
Inline: True
```
**Symbols:**

```
c09e8f30-c09e8fa4: handle_threaded_wake_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
irqreturn_t handle_threaded_wake_irq(int irq, void *_wirq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeirq.c (c00000000099ba00)
Location: drivers/base/power/wakeirq.c:127
Inline: True
```
**Symbols:**

```
c00000000099ba00-c00000000099bac0: handle_threaded_wake_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
irqreturn_t handle_threaded_wake_irq(int irq, void *_wirq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeirq.c (ffffffe00058d072)
Location: drivers/base/power/wakeirq.c:127
Inline: True
```
**Symbols:**

```
ffffffe00058d072-ffffffe00058d0da: handle_threaded_wake_irq (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
irqreturn_t handle_threaded_wake_irq(int irq, void *_wirq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeirq.c (ffffffff816d4207)
Location: drivers/base/power/wakeirq.c:127
Inline: True
```
**Symbols:**

```
ffffffff816d41d0-ffffffff816d421b: handle_threaded_wake_irq (STB_LOCAL)
ffffffff816d4340-ffffffff816d4356: handle_threaded_wake_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
irqreturn_t handle_threaded_wake_irq(int irq, void *_wirq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeirq.c (ffffffff816af4a7)
Location: drivers/base/power/wakeirq.c:127
Inline: True
```
**Symbols:**

```
ffffffff816af470-ffffffff816af4bb: handle_threaded_wake_irq (STB_LOCAL)
ffffffff816af5e0-ffffffff816af5f6: handle_threaded_wake_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
irqreturn_t handle_threaded_wake_irq(int irq, void *_wirq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeirq.c (ffffffff81702777)
Location: drivers/base/power/wakeirq.c:127
Inline: True
```
**Symbols:**

```
ffffffff81702740-ffffffff8170278b: handle_threaded_wake_irq (STB_LOCAL)
ffffffff817028b0-ffffffff817028c6: handle_threaded_wake_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
irqreturn_t handle_threaded_wake_irq(int irq, void *_wirq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeirq.c (ffffffff8171cf97)
Location: drivers/base/power/wakeirq.c:127
Inline: True
```
**Symbols:**

```
ffffffff8171cf60-ffffffff8171cfab: handle_threaded_wake_irq (STB_LOCAL)
ffffffff8171d0d0-ffffffff8171d0e6: handle_threaded_wake_irq.cold (STB_LOCAL)
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
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
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
