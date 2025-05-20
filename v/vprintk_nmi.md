# Function: <code>vprintk_nmi</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int vprintk_nmi(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/nmi.c (ffffffff810df2b0)
Location: kernel/printk/nmi.c:61
Inline: True
```
**Symbols:**

```
ffffffff810df2b0-ffffffff810df35d: vprintk_nmi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int vprintk_nmi(const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/nmi.c (ffffffff810e58a0)
Location: kernel/printk/nmi.c:61
Inline: True
```
**Symbols:**

```
ffffffff810e58a0-ffffffff810e594d: vprintk_nmi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff810e503f)
Location: kernel/printk/printk_safe.c:302
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:vprintk_func
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
In kernel/printk/printk_safe.c (ffffffff810ed29f)
Location: kernel/printk/printk_safe.c:299
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:vprintk_func
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
In kernel/printk/printk_safe.c (ffffffff810f5546)
Location: kernel/printk/printk_safe.c:302
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:vprintk_func
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
In kernel/printk/printk_safe.c (ffffffff81100ce6)
Location: kernel/printk/printk_safe.c:302
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:vprintk_func
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
In kernel/printk/printk_safe.c (ffffffff81109488)
Location: kernel/printk/printk_safe.c:290
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:vprintk_func
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff81115858)
Location: kernel/printk/printk_safe.c:290
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:vprintk_func
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff81121212)
Location: kernel/printk/printk_safe.c:291
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:vprintk_func
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff8111be92)
Location: kernel/printk/printk_safe.c:299
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:vprintk_func
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff8111c18b)
Location: kernel/printk/printk_safe.c:291
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:vprintk
```
</details>
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffff800010177114)
Location: kernel/printk/printk_safe.c:290
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:vprintk_func
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (c03c8d8c)
Location: kernel/printk/printk_safe.c:290
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:vprintk_func
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (c0000000001d09fc)
Location: kernel/printk/printk_safe.c:290
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:vprintk_func
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (0)
Location: kernel/printk/printk_safe.c:330
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff8110de38)
Location: kernel/printk/printk_safe.c:290
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:vprintk_func
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff810feb98)
Location: kernel/printk/printk_safe.c:290
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:vprintk_func
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff8110bd28)
Location: kernel/printk/printk_safe.c:290
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:vprintk_func
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/printk/printk_safe.c (ffffffff811172ca)
Location: kernel/printk/printk_safe.c:290
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:vprintk_func
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
