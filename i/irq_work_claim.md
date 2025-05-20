# Function: <code>irq_work_claim</code>

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
In kernel/irq_work.c (ffffffff81170d6a)
Location: kernel/irq_work.c:29
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
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
In kernel/irq_work.c (ffffffff8117e45f)
Location: kernel/irq_work.c:29
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
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
In kernel/irq_work.c (ffffffff8118a06f)
Location: kernel/irq_work.c:29
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
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
In kernel/irq_work.c (ffffffff8118cbc2)
Location: kernel/irq_work.c:29
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
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
In kernel/irq_work.c (ffffffff8119a7e7)
Location: kernel/irq_work.c:29
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
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
In kernel/irq_work.c (ffffffff811b0227)
Location: kernel/irq_work.c:29
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
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
In kernel/irq_work.c (ffffffff811be83b)
Location: kernel/irq_work.c:29
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
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
In kernel/irq_work.c (ffffffff811ce3d9)
Location: kernel/irq_work.c:30
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
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
In kernel/irq_work.c (ffffffff811da9f9)
Location: kernel/irq_work.c:30
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool irq_work_claim(struct irq_work *work);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff811f7350)
Location: kernel/irq_work.c:30
Inline: True
Direct callers:
  - kernel/irq_work.c:irq_work_queue_on
```
**Symbols:**

```
ffffffff811f7350-ffffffff811f736c: irq_work_claim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool irq_work_claim(struct irq_work *work);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff811f5ec0)
Location: kernel/irq_work.c:30
Inline: True
Direct callers:
  - kernel/irq_work.c:irq_work_queue_on
```
**Symbols:**

```
ffffffff811f5ec0-ffffffff811f5edc: irq_work_claim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool irq_work_claim(struct irq_work *work);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff811f6db0)
Location: kernel/irq_work.c:30
Inline: True
Direct callers:
  - kernel/irq_work.c:irq_work_queue_on
```
**Symbols:**

```
ffffffff811f6db0-ffffffff811f6dcc: irq_work_claim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool irq_work_claim(struct irq_work *work);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff81228380)
Location: kernel/irq_work.c:30
Inline: True
Direct callers:
  - kernel/irq_work.c:irq_work_queue_on
```
**Symbols:**

```
ffffffff81228380-ffffffff8122839c: irq_work_claim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool irq_work_claim(struct irq_work *work);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff81269310)
Location: kernel/irq_work.c:55
Inline: True
Direct callers:
  - kernel/irq_work.c:irq_work_queue_on
```
**Symbols:**

```
ffffffff81269310-ffffffff81269336: irq_work_claim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool irq_work_claim(struct irq_work *work);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff812be140)
Location: kernel/irq_work.c:55
Inline: True
Direct callers:
  - kernel/irq_work.c:irq_work_queue_on
```
**Symbols:**

```
ffffffff812be140-ffffffff812be166: irq_work_claim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool irq_work_claim(struct irq_work *work);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff812e4d00)
Location: kernel/irq_work.c:57
Inline: True
Direct callers:
  - kernel/irq_work.c:irq_work_queue_on
```
**Symbols:**

```
ffffffff812e4d00-ffffffff812e4d28: irq_work_claim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool irq_work_claim(struct irq_work *work);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff81302db0)
Location: kernel/irq_work.c:57
Inline: True
Direct callers:
  - kernel/irq_work.c:irq_work_queue_on
```
**Symbols:**

```
ffffffff81302db0-ffffffff81302dd8: irq_work_claim (STB_LOCAL)
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
bool irq_work_claim(struct irq_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffff80001025afb0)
Location: kernel/irq_work.c:30
Inline: False
Direct callers:
  - kernel/irq_work.c:irq_work_queue_on
```
**Symbols:**

```
ffff80001025afb0-ffff80001025b008: irq_work_claim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool irq_work_claim(struct irq_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (c048e194)
Location: kernel/irq_work.c:30
Inline: False
Direct callers:
  - kernel/irq_work.c:irq_work_queue_on
```
**Symbols:**

```
c048e194-c048e224: irq_work_claim (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool irq_work_claim(struct irq_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (c0000000002feb10)
Location: kernel/irq_work.c:30
Inline: False
Direct callers:
  - kernel/irq_work.c:irq_work_queue_on
```
**Symbols:**

```
c0000000002feb10-c0000000002feba8: irq_work_claim (STB_LOCAL)
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
In kernel/irq_work.c (ffffffe00019a24a)
Location: kernel/irq_work.c:30
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
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
In kernel/irq_work.c (ffffffff811d3019)
Location: kernel/irq_work.c:30
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
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
In kernel/irq_work.c (ffffffff811c5dd9)
Location: kernel/irq_work.c:30
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
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
In kernel/irq_work.c (ffffffff811d0de9)
Location: kernel/irq_work.c:30
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
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
In kernel/irq_work.c (ffffffff811df0c9)
Location: kernel/irq_work.c:30
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
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
