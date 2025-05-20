# Function: <code>console_trylock_spinning</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810f484f)
Location: kernel/printk/printk.c:1636
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
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
In kernel/printk/printk.c (ffffffff810fffff)
Location: kernel/printk/printk.c:1655
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
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
In kernel/printk/printk.c (ffffffff811087c7)
Location: kernel/printk/printk.c:1699
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
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
In kernel/printk/printk.c (ffffffff81114ba7)
Location: kernel/printk/printk.c:1709
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int console_trylock_spinning();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8111e9b0)
Location: kernel/printk/printk.c:1737
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_emit
```
**Symbols:**

```
ffffffff8111e9b0-ffffffff8111ea7e: console_trylock_spinning (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int console_trylock_spinning();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81119400)
Location: kernel/printk/printk.c:1769
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_emit
```
**Symbols:**

```
ffffffff81119400-ffffffff811194ce: console_trylock_spinning (STB_LOCAL)
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
In kernel/printk/printk.c (ffffffff8111b8a6)
Location: kernel/printk/printk.c:1845
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
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
In kernel/printk/printk.c (ffffffff8113bf60)
Location: kernel/printk/printk.c:1836
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int console_trylock_spinning();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:1863
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_emit
```
**Symbols:**

```
ffffffff8115d9e0-ffffffff8115dafc: console_trylock_spinning (STB_LOCAL)
ffffffff81e5c8df-ffffffff81e5c907: console_trylock_spinning.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int console_trylock_spinning();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:1951
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_emit
```
**Symbols:**

```
ffffffff8118fd10-ffffffff8118fe30: console_trylock_spinning (STB_LOCAL)
ffffffff82058a0e-ffffffff82058a36: console_trylock_spinning.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int console_trylock_spinning();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:1920
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_emit
```
**Symbols:**

```
ffffffff811a1cd0-ffffffff811a1df0: console_trylock_spinning (STB_LOCAL)
ffffffff820d72f8-ffffffff820d7320: console_trylock_spinning.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int console_trylock_spinning();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:1916
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_emit
```
**Symbols:**

```
ffffffff811b0030-ffffffff811b015d: console_trylock_spinning (STB_LOCAL)
ffffffff821b249e-ffffffff821b24c6: console_trylock_spinning.cold (STB_LOCAL)
```
</details>
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
In kernel/printk/printk.c (ffff800010175bf4)
Location: kernel/printk/printk.c:1709
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
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
In kernel/printk/printk.c (c03c7e5c)
Location: kernel/printk/printk.c:1709
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
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
In kernel/printk/printk.c (c0000000001cf5a0)
Location: kernel/printk/printk.c:1709
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
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
In kernel/printk/printk.c (ffffffe00011137e)
Location: kernel/printk/printk.c:1709
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
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
In kernel/printk/printk.c (ffffffff8110d187)
Location: kernel/printk/printk.c:1709
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
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
In kernel/printk/printk.c (ffffffff810fdf33)
Location: kernel/printk/printk.c:1709
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
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
In kernel/printk/printk.c (ffffffff8110b077)
Location: kernel/printk/printk.c:1709
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
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
In kernel/printk/printk.c (ffffffff8111651c)
Location: kernel/printk/printk.c:1709
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
