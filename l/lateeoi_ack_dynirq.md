# Function: <code>lateeoi_ack_dynirq</code>

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
void lateeoi_ack_dynirq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81733570)
Location: drivers/xen/events/events_base.c:1849
Inline: False
```
**Symbols:**

```
ffffffff81733570-ffffffff81733614: lateeoi_ack_dynirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void lateeoi_ack_dynirq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81716f10)
Location: drivers/xen/events/events_base.c:1891
Inline: False
```
**Symbols:**

```
ffffffff81716f10-ffffffff81716fbb: lateeoi_ack_dynirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void lateeoi_ack_dynirq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff817942b0)
Location: drivers/xen/events/events_base.c:1897
Inline: False
```
**Symbols:**

```
ffffffff817942b0-ffffffff8179437e: lateeoi_ack_dynirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void lateeoi_ack_dynirq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff818ccea0)
Location: drivers/xen/events/events_base.c:1897
Inline: False
```
**Symbols:**

```
ffffffff818ccea0-ffffffff818ccf8a: lateeoi_ack_dynirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void lateeoi_ack_dynirq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81a1e550)
Location: drivers/xen/events/events_base.c:1899
Inline: False
```
**Symbols:**

```
ffffffff81a1e550-ffffffff81a1e63a: lateeoi_ack_dynirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void lateeoi_ack_dynirq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81a67750)
Location: drivers/xen/events/events_base.c:1896
Inline: False
```
**Symbols:**

```
ffffffff81a67750-ffffffff81a6783a: lateeoi_ack_dynirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void lateeoi_ack_dynirq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81abace0)
Location: drivers/xen/events/events_base.c:1876
Inline: False
```
**Symbols:**

```
ffffffff81abace0-ffffffff81abadca: lateeoi_ack_dynirq (STB_LOCAL)
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
