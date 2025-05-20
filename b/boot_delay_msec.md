# Function: <code>boot_delay_msec</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810d84e7)
Location: kernel/printk/printk.c:1005
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810dcfa7)
Location: kernel/printk/printk.c:1142
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810e3647)
Location: kernel/printk/printk.c:1123
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
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
In kernel/printk/printk.c (ffffffff810e34c5)
Location: kernel/printk/printk.c:1173
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
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
In kernel/printk/printk.c (ffffffff810eb185)
Location: kernel/printk/printk.c:1172
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
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
In kernel/printk/printk.c (ffffffff810f474a)
Location: kernel/printk/printk.c:1176
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
In kernel/printk/printk.c (ffffffff810ffeda)
Location: kernel/printk/printk.c:1195
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
In kernel/printk/printk.c (ffffffff811086a9)
Location: kernel/printk/printk.c:1217
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
In kernel/printk/printk.c (ffffffff81114a89)
Location: kernel/printk/printk.c:1227
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
void boot_delay_msec(int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8111d6d0)
Location: kernel/printk/printk.c:1255
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_emit
```
**Symbols:**

```
ffffffff8111d6d0-ffffffff8111d74e: boot_delay_msec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void boot_delay_msec(int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81118140)
Location: kernel/printk/printk.c:1207
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_emit
```
**Symbols:**

```
ffffffff81118140-ffffffff811181be: boot_delay_msec (STB_LOCAL)
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
In kernel/printk/printk.c (ffffffff8111b7a7)
Location: kernel/printk/printk.c:1223
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
In kernel/printk/printk.c (ffffffff8113bea7)
Location: kernel/printk/printk.c:1217
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
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
In kernel/printk/printk.c (ffffffff8115eca7)
Location: kernel/printk/printk.c:1233
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
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
In kernel/printk/printk.c (ffffffff81191c07)
Location: kernel/printk/printk.c:1314
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
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
In kernel/printk/printk.c (ffffffff811a34a7)
Location: kernel/printk/printk.c:1283
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff811b2217)
Location: kernel/printk/printk.c:1280
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
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
In kernel/printk/printk.c (ffff800010175a98)
Location: kernel/printk/printk.c:1227
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
In kernel/printk/printk.c (c03c7cdc)
Location: kernel/printk/printk.c:1227
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
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:1254
Inline: True
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
In kernel/printk/printk.c (ffffffe000111246)
Location: kernel/printk/printk.c:1227
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
In kernel/printk/printk.c (ffffffff8110d069)
Location: kernel/printk/printk.c:1227
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
In kernel/printk/printk.c (ffffffff810fde29)
Location: kernel/printk/printk.c:1227
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
In kernel/printk/printk.c (ffffffff8110af59)
Location: kernel/printk/printk.c:1227
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
In kernel/printk/printk.c (ffffffff811163f9)
Location: kernel/printk/printk.c:1227
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
</ul>
