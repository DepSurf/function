# Function: <code>n_tty_receive_char</code>

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
In drivers/tty/n_tty.c (ffffffff814e5dc7)
Location: drivers/tty/n_tty.c:1426
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
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
In drivers/tty/n_tty.c (ffffffff8153788f)
Location: drivers/tty/n_tty.c:1398
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
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
In drivers/tty/n_tty.c (ffffffff81563faf)
Location: drivers/tty/n_tty.c:1398
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
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
In drivers/tty/n_tty.c (ffffffff81576b8e)
Location: drivers/tty/n_tty.c:1398
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
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
In drivers/tty/n_tty.c (ffffffff815db50e)
Location: drivers/tty/n_tty.c:1396
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
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
In drivers/tty/n_tty.c (ffffffff81614bea)
Location: drivers/tty/n_tty.c:1414
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
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
In drivers/tty/n_tty.c (ffffffff8163192a)
Location: drivers/tty/n_tty.c:1427
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
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
In drivers/tty/n_tty.c (ffffffff8166590a)
Location: drivers/tty/n_tty.c:1429
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
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
In drivers/tty/n_tty.c (ffffffff81687f5a)
Location: drivers/tty/n_tty.c:1429
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
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
In drivers/tty/n_tty.c (ffffffff8173ac8f)
Location: drivers/tty/n_tty.c:1429
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
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
In drivers/tty/n_tty.c (ffffffff81756dcf)
Location: drivers/tty/n_tty.c:1425
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
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
In drivers/tty/n_tty.c (ffffffff8173aeaf)
Location: drivers/tty/n_tty.c:1426
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void n_tty_receive_char(struct tty_struct *tty, unsigned char c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/n_tty.c (0)
Location: drivers/tty/n_tty.c:1397
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_standard
```
**Symbols:**

```
ffffffff817bb940-ffffffff817bba79: n_tty_receive_char (STB_LOCAL)
ffffffff81cf8b93-ffffffff81cf8bbd: n_tty_receive_char.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void n_tty_receive_char(struct tty_struct *tty, unsigned char c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/n_tty.c (0)
Location: drivers/tty/n_tty.c:1382
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_standard
```
**Symbols:**

```
ffffffff818f7f10-ffffffff818f805c: n_tty_receive_char (STB_LOCAL)
ffffffff81ec0cca-ffffffff81ec0cf4: n_tty_receive_char.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void n_tty_receive_char(struct tty_struct *tty, unsigned char c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/n_tty.c (0)
Location: drivers/tty/n_tty.c:1406
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_standard
  - drivers/tty/n_tty.c:n_tty_receive_buf_standard
```
**Symbols:**

```
ffffffff81a50ca0-ffffffff81a50dec: n_tty_receive_char (STB_LOCAL)
ffffffff820950da-ffffffff82095104: n_tty_receive_char.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void n_tty_receive_char(struct tty_struct *tty, unsigned char c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/n_tty.c (0)
Location: drivers/tty/n_tty.c:1405
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_standard
  - drivers/tty/n_tty.c:n_tty_receive_buf_standard
```
**Symbols:**

```
ffffffff81a9af80-ffffffff81a9b0c7: n_tty_receive_char (STB_LOCAL)
ffffffff82115ef8-ffffffff82115f22: n_tty_receive_char.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void n_tty_receive_char(struct tty_struct *tty, u8 c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/n_tty.c (0)
Location: drivers/tty/n_tty.c:1423
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_receive_buf_standard
  - drivers/tty/n_tty.c:n_tty_receive_buf_standard
```
**Symbols:**

```
ffffffff81aede00-ffffffff81aedf47: n_tty_receive_char (STB_LOCAL)
ffffffff821f3c0d-ffffffff821f3c37: n_tty_receive_char.cold (STB_LOCAL)
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
In drivers/tty/n_tty.c (ffff800010855270)
Location: drivers/tty/n_tty.c:1429
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
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
In drivers/tty/n_tty.c (c096035c)
Location: drivers/tty/n_tty.c:1429
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
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
In drivers/tty/n_tty.c (c0000000008f55f0)
Location: drivers/tty/n_tty.c:1429
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
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
In drivers/tty/n_tty.c (ffffffe000532006)
Location: drivers/tty/n_tty.c:1429
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
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
In drivers/tty/n_tty.c (ffffffff8164d9da)
Location: drivers/tty/n_tty.c:1429
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
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
In drivers/tty/n_tty.c (ffffffff8162de2a)
Location: drivers/tty/n_tty.c:1429
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
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
In drivers/tty/n_tty.c (ffffffff8167bd9a)
Location: drivers/tty/n_tty.c:1429
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
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
In drivers/tty/n_tty.c (ffffffff816963fa)
Location: drivers/tty/n_tty.c:1429
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_receive_char_lnext
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>unsigned char c</code> ➡️ <code>u8 c</code>
</li>
</ul>
</details>
</li>
</ul>
