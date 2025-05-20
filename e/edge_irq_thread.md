# Function: <code>edge_irq_thread</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
irqreturn_t edge_irq_thread(int irq, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff8163b8e0)
Location: drivers/gpio/gpiolib-cdev.c:549
Inline: False
```
**Symbols:**

```
ffffffff8163b8e0-ffffffff8163ba19: edge_irq_thread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
irqreturn_t edge_irq_thread(int irq, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff8161f7c0)
Location: drivers/gpio/gpiolib-cdev.c:549
Inline: False
```
**Symbols:**

```
ffffffff8161f7c0-ffffffff8161f8f8: edge_irq_thread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
irqreturn_t edge_irq_thread(int irq, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff8168ed50)
Location: drivers/gpio/gpiolib-cdev.c:549
Inline: False
```
**Symbols:**

```
ffffffff8168ed50-ffffffff8168ee88: edge_irq_thread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
irqreturn_t edge_irq_thread(int irq, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff817ae410)
Location: drivers/gpio/gpiolib-cdev.c:662
Inline: False
```
**Symbols:**

```
ffffffff817ae410-ffffffff817ae56e: edge_irq_thread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
irqreturn_t edge_irq_thread(int irq, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff818c4db0)
Location: drivers/gpio/gpiolib-cdev.c:770
Inline: False
```
**Symbols:**

```
ffffffff818c4db0-ffffffff818c4ef9: edge_irq_thread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
irqreturn_t edge_irq_thread(int irq, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff81907e80)
Location: drivers/gpio/gpiolib-cdev.c:769
Inline: False
```
**Symbols:**

```
ffffffff81907e80-ffffffff81907fcc: edge_irq_thread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
irqreturn_t edge_irq_thread(int irq, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff8194f6a0)
Location: drivers/gpio/gpiolib-cdev.c:858
Inline: False
```
**Symbols:**

```
ffffffff8194f6a0-ffffffff8194f7da: edge_irq_thread (STB_LOCAL)
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
