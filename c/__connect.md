# Function: <code>__connect</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __connect(struct irq_bypass_producer *prod, struct irq_bypass_consumer *cons);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In virt/lib/irqbypass.c (ffffffff81aacfa0)
Location: virt/lib/irqbypass.c:30
Inline: False
```
**Symbols:**

```
ffffffff81aacfa0-ffffffff81aad04b: __connect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __connect(struct irq_bypass_producer *prod, struct irq_bypass_consumer *cons);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In virt/lib/irqbypass.c (ffffffff81bb4410)
Location: virt/lib/irqbypass.c:30
Inline: False
Direct callers:
  - virt/lib/irqbypass.c:irq_bypass_register_consumer
  - virt/lib/irqbypass.c:irq_bypass_register_producer
```
**Symbols:**

```
ffffffff81bb4410-ffffffff81bb44bb: __connect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __connect(struct irq_bypass_producer *prod, struct irq_bypass_consumer *cons);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In virt/lib/irqbypass.c (ffffffff81bc9670)
Location: virt/lib/irqbypass.c:30
Inline: False
Direct callers:
  - virt/lib/irqbypass.c:irq_bypass_register_consumer
  - virt/lib/irqbypass.c:irq_bypass_register_producer
```
**Symbols:**

```
ffffffff81bc9670-ffffffff81bc9719: __connect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __connect(struct irq_bypass_producer *prod, struct irq_bypass_consumer *cons);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In virt/lib/irqbypass.c (ffffffff81bbcfa0)
Location: virt/lib/irqbypass.c:30
Inline: False
Direct callers:
  - virt/lib/irqbypass.c:irq_bypass_register_consumer
  - virt/lib/irqbypass.c:irq_bypass_register_producer
```
**Symbols:**

```
ffffffff81bbcfa0-ffffffff81bbd04b: __connect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __connect(struct irq_bypass_producer *prod, struct irq_bypass_consumer *cons);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In virt/lib/irqbypass.c (ffffffff81c8ce90)
Location: virt/lib/irqbypass.c:30
Inline: False
Direct callers:
  - virt/lib/irqbypass.c:irq_bypass_register_consumer
  - virt/lib/irqbypass.c:irq_bypass_register_producer
```
**Symbols:**

```
ffffffff81c8ce90-ffffffff81c8cf3b: __connect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __connect(struct irq_bypass_producer *prod, struct irq_bypass_consumer *cons);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In virt/lib/irqbypass.c (ffffffff81e3bca0)
Location: virt/lib/irqbypass.c:30
Inline: False
Direct callers:
  - virt/lib/irqbypass.c:irq_bypass_register_consumer
  - virt/lib/irqbypass.c:irq_bypass_register_producer
```
**Symbols:**

```
ffffffff81e3bca0-ffffffff81e3bd51: __connect (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int __connect(struct irq_bypass_producer *prod, struct irq_bypass_consumer *cons);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In virt/lib/irqbypass.c (ffff800010d81940)
Location: virt/lib/irqbypass.c:30
Inline: False
```
**Symbols:**

```
ffff800010d81940-ffff800010d81a00: __connect (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __connect(struct irq_bypass_producer *prod, struct irq_bypass_consumer *cons);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In virt/lib/irqbypass.c (c000000000ec1950)
Location: virt/lib/irqbypass.c:30
Inline: False
```
**Symbols:**

```
c000000000ec1950-c000000000ec1a84: __connect (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __connect(struct irq_bypass_producer *prod, struct irq_bypass_consumer *cons);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In virt/lib/irqbypass.c (ffffffff81a08f20)
Location: virt/lib/irqbypass.c:30
Inline: False
```
**Symbols:**

```
ffffffff81a08f20-ffffffff81a08fcb: __connect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __connect(struct irq_bypass_producer *prod, struct irq_bypass_consumer *cons);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In virt/lib/irqbypass.c (ffffffff81ab81e0)
Location: virt/lib/irqbypass.c:30
Inline: False
```
**Symbols:**

```
ffffffff81ab81e0-ffffffff81ab828b: __connect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __connect(struct irq_bypass_producer *prod, struct irq_bypass_consumer *cons);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In virt/lib/irqbypass.c (ffffffff81ac4600)
Location: virt/lib/irqbypass.c:30
Inline: False
```
**Symbols:**

```
ffffffff81ac4600-ffffffff81ac46ab: __connect (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
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
