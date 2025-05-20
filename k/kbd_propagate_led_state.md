# Function: <code>kbd_propagate_led_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void kbd_propagate_led_state(unsigned int old_state, unsigned int new_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/keyboard.c (ffffffff814f1c30)
Location: drivers/tty/vt/keyboard.c:1012
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_bh
```
**Symbols:**

```
ffffffff814f1c30-ffffffff814f1c7f: kbd_propagate_led_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void kbd_propagate_led_state(unsigned int old_state, unsigned int new_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/keyboard.c (ffffffff81542840)
Location: drivers/tty/vt/keyboard.c:1000
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_bh
```
**Symbols:**

```
ffffffff81542840-ffffffff81542896: kbd_propagate_led_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void kbd_propagate_led_state(unsigned int old_state, unsigned int new_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/keyboard.c (ffffffff8156ee80)
Location: drivers/tty/vt/keyboard.c:1000
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_bh
```
**Symbols:**

```
ffffffff8156ee80-ffffffff8156eed6: kbd_propagate_led_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void kbd_propagate_led_state(unsigned int old_state, unsigned int new_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/keyboard.c (ffffffff81583410)
Location: drivers/tty/vt/keyboard.c:1001
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_bh
```
**Symbols:**

```
ffffffff81583410-ffffffff81583466: kbd_propagate_led_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void kbd_propagate_led_state(unsigned int old_state, unsigned int new_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/keyboard.c (ffffffff815e7f10)
Location: drivers/tty/vt/keyboard.c:1002
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_bh
```
**Symbols:**

```
ffffffff815e7f10-ffffffff815e7f66: kbd_propagate_led_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void kbd_propagate_led_state(unsigned int old_state, unsigned int new_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/keyboard.c (ffffffff816211e0)
Location: drivers/tty/vt/keyboard.c:1002
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_bh
```
**Symbols:**

```
ffffffff816211e0-ffffffff81621236: kbd_propagate_led_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void kbd_propagate_led_state(unsigned int old_state, unsigned int new_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/keyboard.c (ffffffff8163e630)
Location: drivers/tty/vt/keyboard.c:1032
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_bh
```
**Symbols:**

```
ffffffff8163e630-ffffffff8163e688: kbd_propagate_led_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void kbd_propagate_led_state(unsigned int old_state, unsigned int new_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/keyboard.c (ffffffff81672b60)
Location: drivers/tty/vt/keyboard.c:1033
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_bh
```
**Symbols:**

```
ffffffff81672b60-ffffffff81672bb1: kbd_propagate_led_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void kbd_propagate_led_state(unsigned int old_state, unsigned int new_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/keyboard.c (ffffffff816952e0)
Location: drivers/tty/vt/keyboard.c:1033
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_bh
```
**Symbols:**

```
ffffffff816952e0-ffffffff81695331: kbd_propagate_led_state (STB_LOCAL)
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
In drivers/tty/vt/keyboard.c (ffffffff81748452)
Location: drivers/tty/vt/keyboard.c:1039
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_bh
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
In drivers/tty/vt/keyboard.c (ffffffff81764152)
Location: drivers/tty/vt/keyboard.c:1052
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_bh
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
In drivers/tty/vt/keyboard.c (ffffffff81747a26)
Location: drivers/tty/vt/keyboard.c:1064
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_bh
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
In drivers/tty/vt/keyboard.c (ffffffff817c8b2f)
Location: drivers/tty/vt/keyboard.c:1064
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_bh
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
In drivers/tty/vt/keyboard.c (ffffffff81905f25)
Location: drivers/tty/vt/keyboard.c:1071
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_bh
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
In drivers/tty/vt/keyboard.c (ffffffff81a60775)
Location: drivers/tty/vt/keyboard.c:1071
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_bh
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
In drivers/tty/vt/keyboard.c (ffffffff81aaae45)
Location: drivers/tty/vt/keyboard.c:1071
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_bh
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
In drivers/tty/vt/keyboard.c (ffffffff81afd905)
Location: drivers/tty/vt/keyboard.c:1071
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_bh
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
void kbd_propagate_led_state(unsigned int old_state, unsigned int new_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/keyboard.c (ffff800010869828)
Location: drivers/tty/vt/keyboard.c:1033
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_bh
```
**Symbols:**

```
ffff800010869828-ffff8000108698a4: kbd_propagate_led_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void kbd_propagate_led_state(unsigned int old_state, unsigned int new_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/keyboard.c (c096ea10)
Location: drivers/tty/vt/keyboard.c:1033
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_bh
```
**Symbols:**

```
c096ea10-c096ea68: kbd_propagate_led_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void kbd_propagate_led_state(unsigned int old_state, unsigned int new_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/keyboard.c (c0000000009095d0)
Location: drivers/tty/vt/keyboard.c:1033
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_bh
```
**Symbols:**

```
c0000000009095d0-c00000000090967c: kbd_propagate_led_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void kbd_propagate_led_state(unsigned int old_state, unsigned int new_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/keyboard.c (ffffffe00053e46c)
Location: drivers/tty/vt/keyboard.c:1033
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_bh
```
**Symbols:**

```
ffffffe00053e46c-ffffffe00053e4d2: kbd_propagate_led_state (STB_LOCAL)
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
In drivers/tty/vt/keyboard.c (ffffffff8165ad54)
Location: drivers/tty/vt/keyboard.c:1089
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_bh
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
In drivers/tty/vt/keyboard.c (ffffffff8163b0d4)
Location: drivers/tty/vt/keyboard.c:1089
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_bh
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void kbd_propagate_led_state(unsigned int old_state, unsigned int new_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/keyboard.c (ffffffff81689120)
Location: drivers/tty/vt/keyboard.c:1033
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_bh
```
**Symbols:**

```
ffffffff81689120-ffffffff81689171: kbd_propagate_led_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void kbd_propagate_led_state(unsigned int old_state, unsigned int new_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/keyboard.c (ffffffff816a3710)
Location: drivers/tty/vt/keyboard.c:1033
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_bh
```
**Symbols:**

```
ffffffff816a3710-ffffffff816a3761: kbd_propagate_led_state (STB_LOCAL)
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
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
