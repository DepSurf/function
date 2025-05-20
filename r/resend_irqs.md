# Function: <code>resend_irqs</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void resend_irqs(long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/resend.c (ffffffff811260d0)
Location: kernel/irq/resend.c:30
Inline: False
```
**Symbols:**

```
ffffffff811260d0-ffffffff81126141: resend_irqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void resend_irqs(long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/resend.c (ffffffff81121cb0)
Location: kernel/irq/resend.c:30
Inline: False
```
**Symbols:**

```
ffffffff81121cb0-ffffffff81121d21: resend_irqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void resend_irqs(struct tasklet_struct *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/resend.c (ffffffff81122030)
Location: kernel/irq/resend.c:30
Inline: False
```
**Symbols:**

```
ffffffff81122030-ffffffff811220a1: resend_irqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void resend_irqs(struct tasklet_struct *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/resend.c (ffffffff811425e0)
Location: kernel/irq/resend.c:30
Inline: False
```
**Symbols:**

```
ffffffff811425e0-ffffffff81142651: resend_irqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void resend_irqs(struct tasklet_struct *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/resend.c (ffffffff81166130)
Location: kernel/irq/resend.c:30
Inline: False
```
**Symbols:**

```
ffffffff81166130-ffffffff811661ab: resend_irqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void resend_irqs(struct tasklet_struct *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/resend.c (ffffffff8119a280)
Location: kernel/irq/resend.c:30
Inline: False
```
**Symbols:**

```
ffffffff8119a280-ffffffff8119a303: resend_irqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void resend_irqs(struct tasklet_struct *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/resend.c (ffffffff811abe90)
Location: kernel/irq/resend.c:31
Inline: False
```
**Symbols:**

```
ffffffff811abe90-ffffffff811abf37: resend_irqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void resend_irqs(struct tasklet_struct *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/resend.c (ffffffff811bba90)
Location: kernel/irq/resend.c:31
Inline: False
```
**Symbols:**

```
ffffffff811bba90-ffffffff811bbb37: resend_irqs (STB_LOCAL)
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
void resend_irqs(long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/resend.c (ffff80001017d4d8)
Location: kernel/irq/resend.c:30
Inline: False
```
**Symbols:**

```
ffff80001017d4d8-ffff80001017d594: resend_irqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void resend_irqs(long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/resend.c (c03cde78)
Location: kernel/irq/resend.c:30
Inline: False
```
**Symbols:**

```
c03cde78-c03cdef4: resend_irqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void resend_irqs(long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/resend.c (c0000000001d7ff0)
Location: kernel/irq/resend.c:30
Inline: False
```
**Symbols:**

```
c0000000001d7ff0-c0000000001d8128: resend_irqs (STB_LOCAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct tasklet_struct *unused</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int arg</code>
</li>
</ul>
</details>
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
