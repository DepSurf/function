# Function: <code>srcu_read_lock_held</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (0)
Location: include/linux/srcu.h:103
Inline: True
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
In fs/notify/mark.c (0)
Location: include/linux/srcu.h:104
Inline: True
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
In fs/notify/mark.c (0)
Location: include/linux/srcu.h:138
Inline: True
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
In fs/notify/mark.c (0)
Location: include/linux/srcu.h:138
Inline: True
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
In fs/notify/mark.c (0)
Location: include/linux/srcu.h:91
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (0)
Location: include/linux/srcu.h:91
Inline: True
```
```
In drivers/base/core.c (0)
Location: include/linux/srcu.h:91
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (0)
Location: include/linux/srcu.h:91
Inline: True
```
```
In drivers/base/core.c (0)
Location: include/linux/srcu.h:91
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (0)
Location: include/linux/srcu.h:91
Inline: True
```
```
In drivers/base/core.c (0)
Location: include/linux/srcu.h:91
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (0)
Location: include/linux/srcu.h:94
Inline: True
```
```
In drivers/base/core.c (0)
Location: include/linux/srcu.h:94
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (0)
Location: include/linux/srcu.h:100
Inline: True
```
```
In drivers/base/core.c (0)
Location: include/linux/srcu.h:100
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (0)
Location: include/linux/srcu.h:100
Inline: True
```
```
In drivers/base/core.c (0)
Location: include/linux/srcu.h:100
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (0)
Location: include/linux/srcu.h:107
Inline: True
```
```
In fs/notify/mark.c (0)
Location: include/linux/srcu.h:107
Inline: True
```
```
In drivers/base/core.c (0)
Location: include/linux/srcu.h:107
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (0)
Location: include/linux/srcu.h:133
Inline: True
```
```
In fs/notify/mark.c (0)
Location: include/linux/srcu.h:133
Inline: True
```
```
In drivers/base/core.c (0)
Location: include/linux/srcu.h:133
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (0)
Location: include/linux/srcu.h:133
Inline: True
```
```
In fs/notify/mark.c (0)
Location: include/linux/srcu.h:133
Inline: True
```
```
In drivers/base/core.c (0)
Location: include/linux/srcu.h:133
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (0)
Location: include/linux/srcu.h:91
Inline: True
```
```
In drivers/base/core.c (0)
Location: include/linux/srcu.h:91
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (0)
Location: include/linux/srcu.h:91
Inline: True
```
```
In drivers/base/core.c (0)
Location: include/linux/srcu.h:91
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (0)
Location: include/linux/srcu.h:91
Inline: True
```
```
In drivers/base/core.c (0)
Location: include/linux/srcu.h:91
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (0)
Location: include/linux/srcu.h:91
Inline: True
```
```
In drivers/base/core.c (0)
Location: include/linux/srcu.h:91
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (0)
Location: include/linux/srcu.h:91
Inline: True
```
```
In drivers/base/core.c (0)
Location: include/linux/srcu.h:91
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (0)
Location: include/linux/srcu.h:91
Inline: True
```
```
In drivers/base/core.c (0)
Location: include/linux/srcu.h:91
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (0)
Location: include/linux/srcu.h:91
Inline: True
```
```
In drivers/base/core.c (0)
Location: include/linux/srcu.h:91
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (0)
Location: include/linux/srcu.h:91
Inline: True
```
```
In drivers/base/core.c (0)
Location: include/linux/srcu.h:91
Inline: True
```
</details>
</li>
</ul>

## Differences
