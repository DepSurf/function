# Function: <code>irq_bypass_unregister_consumer</code>

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
void irq_bypass_unregister_consumer(struct irq_bypass_consumer *consumer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In virt/lib/irqbypass.c (ffffffff81aad410)
Location: virt/lib/irqbypass.c:229
Inline: True
```
**Symbols:**

```
ffffffff81aad410-ffffffff81aad4d5: irq_bypass_unregister_consumer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void irq_bypass_unregister_consumer(struct irq_bypass_consumer *consumer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In virt/lib/irqbypass.c (ffffffff81bb4850)
Location: virt/lib/irqbypass.c:231
Inline: True
```
**Symbols:**

```
ffffffff81bb4850-ffffffff81bb491b: irq_bypass_unregister_consumer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void irq_bypass_unregister_consumer(struct irq_bypass_consumer *consumer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In virt/lib/irqbypass.c (ffffffff81bc9ab0)
Location: virt/lib/irqbypass.c:235
Inline: True
```
**Symbols:**

```
ffffffff81bc9ab0-ffffffff81bc9b7b: irq_bypass_unregister_consumer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void irq_bypass_unregister_consumer(struct irq_bypass_consumer *consumer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In virt/lib/irqbypass.c (ffffffff81bbd3e0)
Location: virt/lib/irqbypass.c:231
Inline: True
```
**Symbols:**

```
ffffffff81bbd3e0-ffffffff81bbd4ab: irq_bypass_unregister_consumer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void irq_bypass_unregister_consumer(struct irq_bypass_consumer *consumer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In virt/lib/irqbypass.c (ffffffff81c8d2d0)
Location: virt/lib/irqbypass.c:231
Inline: True
```
**Symbols:**

```
ffffffff81c8d2d0-ffffffff81c8d39b: irq_bypass_unregister_consumer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void irq_bypass_unregister_consumer(struct irq_bypass_consumer *consumer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In virt/lib/irqbypass.c (ffffffff81e3c160)
Location: virt/lib/irqbypass.c:231
Inline: True
```
**Symbols:**

```
ffffffff81e3c160-ffffffff81e3c252: irq_bypass_unregister_consumer (STB_GLOBAL)
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
void irq_bypass_unregister_consumer(struct irq_bypass_consumer *consumer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In virt/lib/irqbypass.c (ffff800010d81e38)
Location: virt/lib/irqbypass.c:229
Inline: True
Direct callers:
  - virt/kvm/eventfd.c:irqfd_shutdown
```
**Symbols:**

```
ffff800010d81e38-ffff800010d81f3c: irq_bypass_unregister_consumer (STB_GLOBAL)
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
void irq_bypass_unregister_consumer(struct irq_bypass_consumer *consumer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In virt/lib/irqbypass.c (c000000000ec2070)
Location: virt/lib/irqbypass.c:229
Inline: True
```
**Symbols:**

```
c000000000ec2070-c000000000ec21dc: irq_bypass_unregister_consumer (STB_GLOBAL)
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
void irq_bypass_unregister_consumer(struct irq_bypass_consumer *consumer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In virt/lib/irqbypass.c (ffffffff81a09390)
Location: virt/lib/irqbypass.c:229
Inline: True
```
**Symbols:**

```
ffffffff81a09390-ffffffff81a09455: irq_bypass_unregister_consumer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void irq_bypass_unregister_consumer(struct irq_bypass_consumer *consumer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In virt/lib/irqbypass.c (ffffffff81ab8650)
Location: virt/lib/irqbypass.c:229
Inline: True
```
**Symbols:**

```
ffffffff81ab8650-ffffffff81ab8715: irq_bypass_unregister_consumer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void irq_bypass_unregister_consumer(struct irq_bypass_consumer *consumer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In virt/lib/irqbypass.c (ffffffff81ac4a70)
Location: virt/lib/irqbypass.c:229
Inline: True
```
**Symbols:**

```
ffffffff81ac4a70-ffffffff81ac4b30: irq_bypass_unregister_consumer (STB_GLOBAL)
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
