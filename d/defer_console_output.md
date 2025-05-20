# Function: <code>defer_console_output</code>

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
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void defer_console_output();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810f4b42)
Location: kernel/printk/printk.c:2890
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_deferred
Direct callers:
  - kernel/printk/printk_safe.c:vprintk_func
```
**Symbols:**

```
ffffffff810f4af0-ffffffff810f4b17: defer_console_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void defer_console_output();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff811002f2)
Location: kernel/printk/printk.c:2902
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_deferred
Direct callers:
  - kernel/printk/printk_safe.c:vprintk_func
```
**Symbols:**

```
ffffffff811002a0-ffffffff811002c7: defer_console_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void defer_console_output();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81108ad4)
Location: kernel/printk/printk.c:2967
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_deferred
Direct callers:
  - kernel/printk/printk_safe.c:vprintk_func
```
**Symbols:**

```
ffffffff81108a80-ffffffff81108aa7: defer_console_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void defer_console_output();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81114eb4)
Location: kernel/printk/printk.c:2977
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_deferred
Direct callers:
  - kernel/printk/printk_safe.c:vprintk_func
```
**Symbols:**

```
ffffffff81114e60-ffffffff81114e87: defer_console_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void defer_console_output();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8112085b)
Location: kernel/printk/printk.c:3042
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_deferred
  - kernel/printk/printk.c:vprintk_deferred
Direct callers:
  - kernel/printk/printk_safe.c:vprintk_func
```
**Symbols:**

```
ffffffff811207f0-ffffffff81120821: defer_console_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void defer_console_output();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8111b7f9)
Location: kernel/printk/printk.c:3121
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_deferred
  - kernel/printk/printk.c:vprintk_deferred
Direct callers:
  - kernel/printk/printk_safe.c:vprintk_func
```
**Symbols:**

```
ffffffff8111b790-ffffffff8111b7c1: defer_console_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void defer_console_output();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8111beb9)
Location: kernel/printk/printk.c:3185
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_deferred
  - kernel/printk/printk.c:vprintk_deferred
Direct callers:
  - kernel/printk/printk_safe.c:vprintk
```
**Symbols:**

```
ffffffff8111be50-ffffffff8111be81: defer_console_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void defer_console_output();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff8113c2da)
Location: kernel/printk/printk.c:3244
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_deferred
  - kernel/printk/printk.c:vprintk_deferred
  - kernel/printk/printk.c:printk_trigger_flush
  - kernel/printk/printk.c:printk_trigger_flush
Direct callers:
  - kernel/printk/printk_safe.c:vprintk
```
**Symbols:**

```
ffffffff81cac5da-ffffffff81cac5ee: defer_console_output.cold (STB_LOCAL)
ffffffff8113c210-ffffffff8113c251: defer_console_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void defer_console_output();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff8115f44a)
Location: kernel/printk/printk.c:3502
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_deferred
  - kernel/printk/printk.c:printk_trigger_flush
Direct callers:
  - kernel/printk/printk_safe.c:vprintk
```
**Symbols:**

```
ffffffff81e5cb34-ffffffff81e5cb48: defer_console_output.cold (STB_LOCAL)
ffffffff8115f3a0-ffffffff8115f3d7: defer_console_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void defer_console_output();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff81192719)
Location: kernel/printk/printk.c:3765
Inline: True
Inline callers:
  - kernel/printk/printk.c:_printk_deferred
  - kernel/printk/printk.c:printk_trigger_flush
Direct callers:
  - kernel/printk/printk_safe.c:vprintk
```
**Symbols:**

```
ffffffff82058bad-ffffffff82058bc1: defer_console_output.cold (STB_LOCAL)
ffffffff81192590-ffffffff811925c7: defer_console_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void defer_console_output();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff811a3fb9)
Location: kernel/printk/printk.c:3806
Inline: True
Inline callers:
  - kernel/printk/printk.c:_printk_deferred
  - kernel/printk/printk.c:printk_trigger_flush
Direct callers:
  - kernel/printk/printk_safe.c:vprintk
```
**Symbols:**

```
ffffffff820d7445-ffffffff820d7459: defer_console_output.cold (STB_LOCAL)
ffffffff811a3e30-ffffffff811a3e67: defer_console_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void defer_console_output();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff811b3535)
Location: kernel/printk/printk.c:3929
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_trigger_flush
  - kernel/printk/printk.c:vprintk_emit
```
**Symbols:**

```
ffffffff821b26f0-ffffffff821b2704: defer_console_output.cold (STB_LOCAL)
ffffffff811b34e0-ffffffff811b3517: defer_console_output (STB_GLOBAL)
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
void defer_console_output();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffff800010175fa0)
Location: kernel/printk/printk.c:2977
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_deferred
  - kernel/printk/printk_safe.c:vprintk_func
```
**Symbols:**

```
ffff800010175fa0-ffff800010175fe0: defer_console_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void defer_console_output();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (c03c81f8)
Location: kernel/printk/printk.c:2977
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_deferred
  - kernel/printk/printk_safe.c:vprintk_func
```
**Symbols:**

```
c03c81f8-c03c8238: defer_console_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void defer_console_output();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (c0000000001cfa10)
Location: kernel/printk/printk.c:2977
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_deferred
  - kernel/printk/printk_safe.c:vprintk_func
```
**Symbols:**

```
c0000000001cfa10-c0000000001cfa68: defer_console_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void defer_console_output();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffe0001115ea)
Location: kernel/printk/printk.c:2977
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_deferred
  - kernel/printk/printk_safe.c:vprintk_func
```
**Symbols:**

```
ffffffe0001115ea-ffffffe000111644: defer_console_output (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void defer_console_output();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8110d494)
Location: kernel/printk/printk.c:2977
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_deferred
Direct callers:
  - kernel/printk/printk_safe.c:vprintk_func
```
**Symbols:**

```
ffffffff8110d440-ffffffff8110d467: defer_console_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void defer_console_output();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810fe214)
Location: kernel/printk/printk.c:2977
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_deferred
Direct callers:
  - kernel/printk/printk_safe.c:vprintk_func
```
**Symbols:**

```
ffffffff810fe1c0-ffffffff810fe1e7: defer_console_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void defer_console_output();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8110b384)
Location: kernel/printk/printk.c:2977
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_deferred
Direct callers:
  - kernel/printk/printk_safe.c:vprintk_func
```
**Symbols:**

```
ffffffff8110b330-ffffffff8110b357: defer_console_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void defer_console_output();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81116800)
Location: kernel/printk/printk.c:2977
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_deferred
  - kernel/printk/printk_safe.c:vprintk_func
```
**Symbols:**

```
ffffffff81116800-ffffffff8111683e: defer_console_output (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
