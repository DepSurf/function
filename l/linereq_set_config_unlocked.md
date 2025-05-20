# Function: <code>linereq_set_config_unlocked</code>

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
long int linereq_set_config_unlocked(struct linereq *lr, struct gpio_v2_line_config *lc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff8163aa10)
Location: drivers/gpio/gpiolib-cdev.c:1117
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_set_config
```
**Symbols:**

```
ffffffff8163aa10-ffffffff8163ae2f: linereq_set_config_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int linereq_set_config_unlocked(struct linereq *lr, struct gpio_v2_line_config *lc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff8161ed30)
Location: drivers/gpio/gpiolib-cdev.c:1117
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_set_config
```
**Symbols:**

```
ffffffff8161ed30-ffffffff8161f14e: linereq_set_config_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int linereq_set_config_unlocked(struct linereq *lr, struct gpio_v2_line_config *lc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff8168db60)
Location: drivers/gpio/gpiolib-cdev.c:1117
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_set_config
```
**Symbols:**

```
ffffffff8168db60-ffffffff8168de91: linereq_set_config_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int linereq_set_config_unlocked(struct linereq *lr, struct gpio_v2_line_config *lc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff817ac440)
Location: drivers/gpio/gpiolib-cdev.c:1299
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_set_config
```
**Symbols:**

```
ffffffff817ac440-ffffffff817ac6d4: linereq_set_config_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int linereq_set_config_unlocked(struct linereq *lr, struct gpio_v2_line_config *lc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff818c5420)
Location: drivers/gpio/gpiolib-cdev.c:1373
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_set_config
```
**Symbols:**

```
ffffffff818c5420-ffffffff818c5667: linereq_set_config_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int linereq_set_config_unlocked(struct linereq *lr, struct gpio_v2_line_config *lc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff819084d0)
Location: drivers/gpio/gpiolib-cdev.c:1372
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_set_config
```
**Symbols:**

```
ffffffff819084d0-ffffffff8190871a: linereq_set_config_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
</ul>
