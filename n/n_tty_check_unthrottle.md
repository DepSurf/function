# Function: <code>n_tty_check_unthrottle</code>

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
In drivers/tty/n_tty.c (ffffffff814e6293)
Location: drivers/tty/n_tty.c:259
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
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
In drivers/tty/n_tty.c (ffffffff81537161)
Location: drivers/tty/n_tty.c:259
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
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
In drivers/tty/n_tty.c (ffffffff81563881)
Location: drivers/tty/n_tty.c:259
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
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
In drivers/tty/n_tty.c (ffffffff81578aac)
Location: drivers/tty/n_tty.c:259
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
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
In drivers/tty/n_tty.c (ffffffff815dd437)
Location: drivers/tty/n_tty.c:257
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
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
In drivers/tty/n_tty.c (ffffffff8161670e)
Location: drivers/tty/n_tty.c:260
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
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
In drivers/tty/n_tty.c (ffffffff8163385e)
Location: drivers/tty/n_tty.c:273
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
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
In drivers/tty/n_tty.c (ffffffff8166664a)
Location: drivers/tty/n_tty.c:275
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
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
In drivers/tty/n_tty.c (ffffffff81688906)
Location: drivers/tty/n_tty.c:275
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void n_tty_check_unthrottle(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff817395b0)
Location: drivers/tty/n_tty.c:275
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
```
**Symbols:**

```
ffffffff817395b0-ffffffff81739677: n_tty_check_unthrottle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void n_tty_check_unthrottle(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff81755aa0)
Location: drivers/tty/n_tty.c:270
Inline: True
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
```
**Symbols:**

```
ffffffff81755aa0-ffffffff81755b67: n_tty_check_unthrottle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void n_tty_check_unthrottle(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff817395a0)
Location: drivers/tty/n_tty.c:271
Inline: True
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
```
**Symbols:**

```
ffffffff817395a0-ffffffff81739667: n_tty_check_unthrottle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void n_tty_check_unthrottle(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff817ba060)
Location: drivers/tty/n_tty.c:271
Inline: True
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
```
**Symbols:**

```
ffffffff817ba060-ffffffff817ba127: n_tty_check_unthrottle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void n_tty_check_unthrottle(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff818f6470)
Location: drivers/tty/n_tty.c:268
Inline: True
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
```
**Symbols:**

```
ffffffff818f6470-ffffffff818f654b: n_tty_check_unthrottle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void n_tty_check_unthrottle(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff81a4ee80)
Location: drivers/tty/n_tty.c:271
Inline: True
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
```
**Symbols:**

```
ffffffff81a4ee80-ffffffff81a4ef5b: n_tty_check_unthrottle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void n_tty_check_unthrottle(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff81a9a100)
Location: drivers/tty/n_tty.c:270
Inline: True
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
```
**Symbols:**

```
ffffffff81a9a100-ffffffff81a9a1db: n_tty_check_unthrottle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void n_tty_check_unthrottle(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff81aebc30)
Location: drivers/tty/n_tty.c:261
Inline: True
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
```
**Symbols:**

```
ffffffff81aebc30-ffffffff81aebcef: n_tty_check_unthrottle (STB_LOCAL)
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
In drivers/tty/n_tty.c (ffff80001085633c)
Location: drivers/tty/n_tty.c:275
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
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
In drivers/tty/n_tty.c (c0960874)
Location: drivers/tty/n_tty.c:275
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
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
In drivers/tty/n_tty.c (c0000000008f7e34)
Location: drivers/tty/n_tty.c:275
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
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
In drivers/tty/n_tty.c (ffffffe00053386e)
Location: drivers/tty/n_tty.c:275
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
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
In drivers/tty/n_tty.c (ffffffff8164e386)
Location: drivers/tty/n_tty.c:275
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
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
In drivers/tty/n_tty.c (ffffffff8162e7d6)
Location: drivers/tty/n_tty.c:275
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
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
In drivers/tty/n_tty.c (ffffffff8167c746)
Location: drivers/tty/n_tty.c:275
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
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
In drivers/tty/n_tty.c (ffffffff81696da6)
Location: drivers/tty/n_tty.c:275
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
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
