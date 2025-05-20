# Function: <code>linereq_set_values</code>

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
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff8163bd6e)
Location: drivers/gpio/gpiolib-cdev.c:1100
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_ioctl_compat
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int linereq_set_values(struct linereq *lr, void *ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff8161de90)
Location: drivers/gpio/gpiolib-cdev.c:1100
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_ioctl_compat
```
**Symbols:**

```
ffffffff8161de90-ffffffff8161e03b: linereq_set_values (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff8168e9ee)
Location: drivers/gpio/gpiolib-cdev.c:1100
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_ioctl_compat
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff817ae383)
Location: drivers/gpio/gpiolib-cdev.c:1282
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_ioctl_compat
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff818c7877)
Location: drivers/gpio/gpiolib-cdev.c:1356
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_ioctl_unlocked
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff8190a935)
Location: drivers/gpio/gpiolib-cdev.c:1355
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_ioctl_unlocked
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
long int linereq_set_values(struct linereq *lr, void *ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (0)
Location: drivers/gpio/gpiolib-cdev.c:1412
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_ioctl
```
**Symbols:**

```
ffffffff819504e0-ffffffff819506fc: linereq_set_values (STB_LOCAL)
ffffffff821ec69d-ffffffff821ec6df: linereq_set_values.cold (STB_LOCAL)
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
</ul>
