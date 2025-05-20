# Function: <code>reset_buffer_flags</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void reset_buffer_flags(struct n_tty_data *ldata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff814e44a0)
Location: drivers/tty/n_tty.c:322
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:n_tty_open
  - drivers/tty/n_tty.c:n_tty_flush_buffer
```
**Symbols:**

```
ffffffff814e44a0-ffffffff814e4539: reset_buffer_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void reset_buffer_flags(struct n_tty_data *ldata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff815357a0)
Location: drivers/tty/n_tty.c:318
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_open
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:n_tty_flush_buffer
```
**Symbols:**

```
ffffffff815357a0-ffffffff81535839: reset_buffer_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void reset_buffer_flags(struct n_tty_data *ldata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff81561ec0)
Location: drivers/tty/n_tty.c:318
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_open
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:n_tty_flush_buffer
```
**Symbols:**

```
ffffffff81561ec0-ffffffff81561f59: reset_buffer_flags (STB_LOCAL)
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
In drivers/tty/n_tty.c (ffffffff81577074)
Location: drivers/tty/n_tty.c:318
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_open
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:n_tty_flush_buffer
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
In drivers/tty/n_tty.c (ffffffff815db9f4)
Location: drivers/tty/n_tty.c:316
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_open
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:n_tty_flush_buffer
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
In drivers/tty/n_tty.c (ffffffff8161431f)
Location: drivers/tty/n_tty.c:319
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:n_tty_flush_buffer
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
In drivers/tty/n_tty.c (ffffffff816315cf)
Location: drivers/tty/n_tty.c:332
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:n_tty_flush_buffer
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
In drivers/tty/n_tty.c (ffffffff816655c0)
Location: drivers/tty/n_tty.c:334
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:n_tty_flush_buffer
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
In drivers/tty/n_tty.c (ffffffff81687c10)
Location: drivers/tty/n_tty.c:334
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:n_tty_flush_buffer
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
In drivers/tty/n_tty.c (ffffffff81739854)
Location: drivers/tty/n_tty.c:334
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:n_tty_flush_buffer
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
In drivers/tty/n_tty.c (ffffffff81755d44)
Location: drivers/tty/n_tty.c:329
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:n_tty_flush_buffer
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
In drivers/tty/n_tty.c (ffffffff81739a74)
Location: drivers/tty/n_tty.c:330
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:n_tty_flush_buffer
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
In drivers/tty/n_tty.c (ffffffff817ba524)
Location: drivers/tty/n_tty.c:330
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:n_tty_flush_buffer
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
In drivers/tty/n_tty.c (ffffffff818f6aa1)
Location: drivers/tty/n_tty.c:327
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:n_tty_flush_buffer
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
In drivers/tty/n_tty.c (ffffffff81a4f5c1)
Location: drivers/tty/n_tty.c:330
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:n_tty_flush_buffer
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
In drivers/tty/n_tty.c (ffffffff81a997d1)
Location: drivers/tty/n_tty.c:329
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:n_tty_flush_buffer
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
In drivers/tty/n_tty.c (ffffffff81aec431)
Location: drivers/tty/n_tty.c:318
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:n_tty_flush_buffer
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
In drivers/tty/n_tty.c (ffff800010854fac)
Location: drivers/tty/n_tty.c:334
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:n_tty_flush_buffer
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
In drivers/tty/n_tty.c (c095fc40)
Location: drivers/tty/n_tty.c:334
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:n_tty_flush_buffer
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
In drivers/tty/n_tty.c (c0000000008f5144)
Location: drivers/tty/n_tty.c:334
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:n_tty_flush_buffer
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
In drivers/tty/n_tty.c (ffffffe000531090)
Location: drivers/tty/n_tty.c:334
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:n_tty_flush_buffer
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
In drivers/tty/n_tty.c (ffffffff8164d690)
Location: drivers/tty/n_tty.c:334
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:n_tty_flush_buffer
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
In drivers/tty/n_tty.c (ffffffff8162dae0)
Location: drivers/tty/n_tty.c:334
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:n_tty_flush_buffer
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
In drivers/tty/n_tty.c (ffffffff8167ba50)
Location: drivers/tty/n_tty.c:334
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:n_tty_flush_buffer
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
In drivers/tty/n_tty.c (ffffffff816960b0)
Location: drivers/tty/n_tty.c:334
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:n_tty_flush_buffer
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
