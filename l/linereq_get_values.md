# Function: <code>linereq_get_values</code>

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
long int linereq_get_values(struct linereq *lr, void *ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff8163ba20)
Location: drivers/gpio/gpiolib-cdev.c:997
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_ioctl_compat
```
**Symbols:**

```
ffffffff8163ba20-ffffffff8163bc12: linereq_get_values (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int linereq_get_values(struct linereq *lr, void *ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff8161f200)
Location: drivers/gpio/gpiolib-cdev.c:997
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_ioctl_compat
```
**Symbols:**

```
ffffffff8161f200-ffffffff8161f3ff: linereq_get_values (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long int linereq_get_values(struct linereq *lr, void *ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (0)
Location: drivers/gpio/gpiolib-cdev.c:997
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_ioctl_compat
```
**Symbols:**

```
ffffffff8168e660-ffffffff8168e89d: linereq_get_values (STB_LOCAL)
ffffffff81ce24a9-ffffffff81ce2528: linereq_get_values.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long int linereq_get_values(struct linereq *lr, void *ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (0)
Location: drivers/gpio/gpiolib-cdev.c:1179
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_ioctl_compat
```
**Symbols:**

```
ffffffff817adfa0-ffffffff817ae21b: linereq_get_values (STB_LOCAL)
ffffffff81ea8eb2-ffffffff81ea8f2c: linereq_get_values.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
long int linereq_get_values(struct linereq *lr, void *ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (0)
Location: drivers/gpio/gpiolib-cdev.c:1253
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_ioctl_unlocked
```
**Symbols:**

```
ffffffff818c7550-ffffffff818c77de: linereq_get_values (STB_LOCAL)
ffffffff8208e795-ffffffff8208e80f: linereq_get_values.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
long int linereq_get_values(struct linereq *lr, void *ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (0)
Location: drivers/gpio/gpiolib-cdev.c:1252
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_ioctl_unlocked
```
**Symbols:**

```
ffffffff8190a5f0-ffffffff8190a88a: linereq_get_values (STB_LOCAL)
ffffffff8210ea8b-ffffffff8210eb0e: linereq_get_values.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
long int linereq_get_values(struct linereq *lr, void *ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (0)
Location: drivers/gpio/gpiolib-cdev.c:1340
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_ioctl
```
**Symbols:**

```
ffffffff819523e0-ffffffff8195267f: linereq_get_values (STB_LOCAL)
ffffffff821ec6df-ffffffff821ec750: linereq_get_values.cold (STB_LOCAL)
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
