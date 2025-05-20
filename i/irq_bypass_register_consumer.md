# Function: <code>irq_bypass_register_consumer</code>

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
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int irq_bypass_register_consumer(struct irq_bypass_consumer *consumer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In virt/lib/irqbypass.c (ffffffff81aad2c0)
Location: virt/lib/irqbypass.c:178
Inline: True
```
**Symbols:**

```
ffffffff81aad2c0-ffffffff81aad408: irq_bypass_register_consumer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int irq_bypass_register_consumer(struct irq_bypass_consumer *consumer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In virt/lib/irqbypass.c (ffffffff81bb4650)
Location: virt/lib/irqbypass.c:179
Inline: False
```
**Symbols:**

```
ffffffff81bb4650-ffffffff81bb477e: irq_bypass_register_consumer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int irq_bypass_register_consumer(struct irq_bypass_consumer *consumer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In virt/lib/irqbypass.c (ffffffff81bc98b0)
Location: virt/lib/irqbypass.c:183
Inline: False
```
**Symbols:**

```
ffffffff81bc98b0-ffffffff81bc99de: irq_bypass_register_consumer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int irq_bypass_register_consumer(struct irq_bypass_consumer *consumer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In virt/lib/irqbypass.c (ffffffff81bbd1e0)
Location: virt/lib/irqbypass.c:179
Inline: False
```
**Symbols:**

```
ffffffff81bbd1e0-ffffffff81bbd30e: irq_bypass_register_consumer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int irq_bypass_register_consumer(struct irq_bypass_consumer *consumer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In virt/lib/irqbypass.c (ffffffff81c8d0d0)
Location: virt/lib/irqbypass.c:179
Inline: False
```
**Symbols:**

```
ffffffff81c8d0d0-ffffffff81c8d1fe: irq_bypass_register_consumer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int irq_bypass_register_consumer(struct irq_bypass_consumer *consumer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In virt/lib/irqbypass.c (ffffffff81e3bf10)
Location: virt/lib/irqbypass.c:179
Inline: False
```
**Symbols:**

```
ffffffff81e3bf10-ffffffff81e3c05e: irq_bypass_register_consumer (STB_GLOBAL)
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int irq_bypass_register_consumer(struct irq_bypass_consumer *consumer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In virt/lib/irqbypass.c (ffff800010d81cd8)
Location: virt/lib/irqbypass.c:178
Inline: True
Direct callers:
  - virt/kvm/eventfd.c:kvm_irqfd_assign
```
**Symbols:**

```
ffff800010d81cd8-ffff800010d81e34: irq_bypass_register_consumer (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int irq_bypass_register_consumer(struct irq_bypass_consumer *consumer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In virt/lib/irqbypass.c (c000000000ec1ea0)
Location: virt/lib/irqbypass.c:178
Inline: True
```
**Symbols:**

```
c000000000ec1ea0-c000000000ec206c: irq_bypass_register_consumer (STB_GLOBAL)
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
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int irq_bypass_register_consumer(struct irq_bypass_consumer *consumer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In virt/lib/irqbypass.c (ffffffff81a09240)
Location: virt/lib/irqbypass.c:178
Inline: True
```
**Symbols:**

```
ffffffff81a09240-ffffffff81a09388: irq_bypass_register_consumer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int irq_bypass_register_consumer(struct irq_bypass_consumer *consumer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In virt/lib/irqbypass.c (ffffffff81ab8500)
Location: virt/lib/irqbypass.c:178
Inline: True
```
**Symbols:**

```
ffffffff81ab8500-ffffffff81ab8648: irq_bypass_register_consumer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int irq_bypass_register_consumer(struct irq_bypass_consumer *consumer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In virt/lib/irqbypass.c (ffffffff81ac4920)
Location: virt/lib/irqbypass.c:178
Inline: True
```
**Symbols:**

```
ffffffff81ac4920-ffffffff81ac4a63: irq_bypass_register_consumer (STB_GLOBAL)
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
