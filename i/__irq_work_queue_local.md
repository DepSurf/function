# Function: <code>__irq_work_queue_local</code>

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
void __irq_work_queue_local(struct irq_work *work);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff811ce310)
Location: kernel/irq_work.c:61
Inline: True
Direct callers:
  - kernel/irq_work.c:irq_work_queue_on
```
**Symbols:**

```
ffffffff811ce310-ffffffff811ce36d: __irq_work_queue_local (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __irq_work_queue_local(struct irq_work *work);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff811da930)
Location: kernel/irq_work.c:61
Inline: True
Direct callers:
  - kernel/irq_work.c:irq_work_queue_on
```
**Symbols:**

```
ffffffff811da930-ffffffff811da98d: __irq_work_queue_local (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __irq_work_queue_local(struct irq_work *work);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff811f7380)
Location: kernel/irq_work.c:53
Inline: True
Direct callers:
  - kernel/irq_work.c:irq_work_queue_on
```
**Symbols:**

```
ffffffff811f7380-ffffffff811f73d5: __irq_work_queue_local (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __irq_work_queue_local(struct irq_work *work);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff811f5ef0)
Location: kernel/irq_work.c:53
Inline: True
Direct callers:
  - kernel/irq_work.c:irq_work_queue_on
```
**Symbols:**

```
ffffffff811f5ef0-ffffffff811f5f45: __irq_work_queue_local (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __irq_work_queue_local(struct irq_work *work);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff811f6de0)
Location: kernel/irq_work.c:53
Inline: True
Direct callers:
  - kernel/irq_work.c:irq_work_queue_on
```
**Symbols:**

```
ffffffff811f6de0-ffffffff811f6e35: __irq_work_queue_local (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __irq_work_queue_local(struct irq_work *work);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff812283b0)
Location: kernel/irq_work.c:53
Inline: True
Direct callers:
  - kernel/irq_work.c:irq_work_queue_on
```
**Symbols:**

```
ffffffff812283b0-ffffffff81228405: __irq_work_queue_local (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __irq_work_queue_local(struct irq_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff812693c0)
Location: kernel/irq_work.c:78
Inline: False
Direct callers:
  - kernel/irq_work.c:irq_work_queue_on
```
**Symbols:**

```
ffffffff812693c0-ffffffff81269424: __irq_work_queue_local (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __irq_work_queue_local(struct irq_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff812be220)
Location: kernel/irq_work.c:78
Inline: False
Direct callers:
  - kernel/irq_work.c:irq_work_queue_on
```
**Symbols:**

```
ffffffff812be220-ffffffff812be284: __irq_work_queue_local (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __irq_work_queue_local(struct irq_work *work);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff812e4de0)
Location: kernel/irq_work.c:88
Inline: True
Direct callers:
  - kernel/irq_work.c:irq_work_queue_on
```
**Symbols:**

```
ffffffff812e4de0-ffffffff812e4ec4: __irq_work_queue_local (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __irq_work_queue_local(struct irq_work *work);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff81302e90)
Location: kernel/irq_work.c:88
Inline: True
Direct callers:
  - kernel/irq_work.c:irq_work_queue_on
```
**Symbols:**

```
ffffffff81302e90-ffffffff81302f74: __irq_work_queue_local (STB_LOCAL)
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
void __irq_work_queue_local(struct irq_work *work);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffff80001025b110)
Location: kernel/irq_work.c:61
Inline: True
Direct callers:
  - kernel/irq_work.c:irq_work_queue_on
```
**Symbols:**

```
ffff80001025b110-ffff80001025b18c: __irq_work_queue_local (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void __irq_work_queue_local(struct irq_work *work);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (c048e234)
Location: kernel/irq_work.c:61
Inline: True
Direct callers:
  - kernel/irq_work.c:irq_work_queue_on
```
**Symbols:**

```
c048e234-c048e2b0: __irq_work_queue_local (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void __irq_work_queue_local(struct irq_work *work);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (c0000000002fed50)
Location: kernel/irq_work.c:61
Inline: True
Direct callers:
  - kernel/irq_work.c:irq_work_queue_on
```
**Symbols:**

```
c0000000002fed50-c0000000002fee10: __irq_work_queue_local (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void __irq_work_queue_local(struct irq_work *work);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffe00019a124)
Location: kernel/irq_work.c:61
Inline: True
Direct callers:
  - kernel/irq_work.c:irq_work_queue_on
```
**Symbols:**

```
ffffffe00019a124-ffffffe00019a1b4: __irq_work_queue_local (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void __irq_work_queue_local(struct irq_work *work);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff811d2f50)
Location: kernel/irq_work.c:61
Inline: True
Direct callers:
  - kernel/irq_work.c:irq_work_queue_on
```
**Symbols:**

```
ffffffff811d2f50-ffffffff811d2fad: __irq_work_queue_local (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __irq_work_queue_local(struct irq_work *work);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff811c5d10)
Location: kernel/irq_work.c:61
Inline: True
Direct callers:
  - kernel/irq_work.c:irq_work_queue_on
```
**Symbols:**

```
ffffffff811c5d10-ffffffff811c5d6d: __irq_work_queue_local (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __irq_work_queue_local(struct irq_work *work);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff811d0d20)
Location: kernel/irq_work.c:61
Inline: True
Direct callers:
  - kernel/irq_work.c:irq_work_queue_on
```
**Symbols:**

```
ffffffff811d0d20-ffffffff811d0d7d: __irq_work_queue_local (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __irq_work_queue_local(struct irq_work *work);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff811defe0)
Location: kernel/irq_work.c:61
Inline: True
Direct callers:
  - kernel/irq_work.c:irq_work_queue_on
```
**Symbols:**

```
ffffffff811defe0-ffffffff811df03d: __irq_work_queue_local (STB_LOCAL)
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
