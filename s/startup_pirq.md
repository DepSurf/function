# Function: <code>startup_pirq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
unsigned int startup_pirq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff814c8630)
Location: drivers/xen/events/events_base.c:552
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:enable_pirq
```
**Symbols:**

```
ffffffff814c8630-ffffffff814c8643: startup_pirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int startup_pirq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81519156)
Location: drivers/xen/events/events_base.c:563
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:enable_pirq
```
**Symbols:**

```
ffffffff81519130-ffffffff81519143: startup_pirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
unsigned int startup_pirq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81545626)
Location: drivers/xen/events/events_base.c:562
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:enable_pirq
```
**Symbols:**

```
ffffffff81545600-ffffffff81545613: startup_pirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned int startup_pirq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff815594b0)
Location: drivers/xen/events/events_base.c:554
Inline: False
```
**Symbols:**

```
ffffffff815594b0-ffffffff815594c3: startup_pirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int startup_pirq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff815bd8e0)
Location: drivers/xen/events/events_base.c:554
Inline: False
```
**Symbols:**

```
ffffffff815bd8e0-ffffffff815bd8f3: startup_pirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned int startup_pirq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff815f5f60)
Location: drivers/xen/events/events_base.c:554
Inline: False
```
**Symbols:**

```
ffffffff815f5f60-ffffffff815f5f73: startup_pirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int startup_pirq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81611020)
Location: drivers/xen/events/events_base.c:554
Inline: False
```
**Symbols:**

```
ffffffff81611020-ffffffff81611033: startup_pirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned int startup_pirq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81644d90)
Location: drivers/xen/events/events_base.c:555
Inline: False
```
**Symbols:**

```
ffffffff81644d90-ffffffff81644da3: startup_pirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int startup_pirq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81667340)
Location: drivers/xen/events/events_base.c:555
Inline: False
```
**Symbols:**

```
ffffffff81667340-ffffffff81667353: startup_pirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int startup_pirq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff817170d0)
Location: drivers/xen/events/events_base.c:569
Inline: False
```
**Symbols:**

```
ffffffff817170d0-ffffffff817170e3: startup_pirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int startup_pirq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff817347b0)
Location: drivers/xen/events/events_base.c:890
Inline: False
```
**Symbols:**

```
ffffffff817347b0-ffffffff817347c3: startup_pirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int startup_pirq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81718030)
Location: drivers/xen/events/events_base.c:921
Inline: False
```
**Symbols:**

```
ffffffff81718030-ffffffff81718043: startup_pirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned int startup_pirq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81795a20)
Location: drivers/xen/events/events_base.c:921
Inline: False
```
**Symbols:**

```
ffffffff81795a20-ffffffff81795a33: startup_pirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int startup_pirq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff818ce7b0)
Location: drivers/xen/events/events_base.c:921
Inline: False
```
**Symbols:**

```
ffffffff818ce7b0-ffffffff818ce7c9: startup_pirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int startup_pirq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81a1fda0)
Location: drivers/xen/events/events_base.c:923
Inline: False
```
**Symbols:**

```
ffffffff81a1fda0-ffffffff81a1fdb9: startup_pirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int startup_pirq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81a69130)
Location: drivers/xen/events/events_base.c:915
Inline: False
```
**Symbols:**

```
ffffffff81a69130-ffffffff81a69149: startup_pirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int startup_pirq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81aba0f0)
Location: drivers/xen/events/events_base.c:908
Inline: False
```
**Symbols:**

```
ffffffff81aba0f0-ffffffff81aba15f: startup_pirq (STB_LOCAL)
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
unsigned int startup_pirq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffff8000108310b0)
Location: drivers/xen/events/events_base.c:555
Inline: False
```
**Symbols:**

```
ffff8000108310b0-ffff8000108310dc: startup_pirq (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
unsigned int startup_pirq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8162d070)
Location: drivers/xen/events/events_base.c:559
Inline: False
```
**Symbols:**

```
ffffffff8162d070-ffffffff8162d083: startup_pirq (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int startup_pirq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8165b180)
Location: drivers/xen/events/events_base.c:555
Inline: False
```
**Symbols:**

```
ffffffff8165b180-ffffffff8165b193: startup_pirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int startup_pirq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81675770)
Location: drivers/xen/events/events_base.c:555
Inline: False
```
**Symbols:**

```
ffffffff81675770-ffffffff81675783: startup_pirq (STB_LOCAL)
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
