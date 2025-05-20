# Function: <code>emulate_raw</code>

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
In drivers/tty/vt/keyboard.c (ffffffff814f39fe)
Location: drivers/tty/vt/keyboard.c:1245
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_event
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
In drivers/tty/vt/keyboard.c (ffffffff81544613)
Location: drivers/tty/vt/keyboard.c:1233
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_event
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
In drivers/tty/vt/keyboard.c (ffffffff81570c53)
Location: drivers/tty/vt/keyboard.c:1233
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_event
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
In drivers/tty/vt/keyboard.c (ffffffff81584e83)
Location: drivers/tty/vt/keyboard.c:1233
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_event
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
In drivers/tty/vt/keyboard.c (ffffffff815e9983)
Location: drivers/tty/vt/keyboard.c:1234
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_event
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
In drivers/tty/vt/keyboard.c (ffffffff81622b46)
Location: drivers/tty/vt/keyboard.c:1234
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_event
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
In drivers/tty/vt/keyboard.c (ffffffff81640193)
Location: drivers/tty/vt/keyboard.c:1264
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_event
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
In drivers/tty/vt/keyboard.c (ffffffff816743d9)
Location: drivers/tty/vt/keyboard.c:1265
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_keycode
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
In drivers/tty/vt/keyboard.c (ffffffff81696b39)
Location: drivers/tty/vt/keyboard.c:1265
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_keycode
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
In drivers/tty/vt/keyboard.c (ffffffff81748e42)
Location: drivers/tty/vt/keyboard.c:1271
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_keycode
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
In drivers/tty/vt/keyboard.c (ffffffff81764900)
Location: drivers/tty/vt/keyboard.c:1290
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_keycode
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
In drivers/tty/vt/keyboard.c (ffffffff817482ca)
Location: drivers/tty/vt/keyboard.c:1300
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_keycode
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
In drivers/tty/vt/keyboard.c (ffffffff817c995d)
Location: drivers/tty/vt/keyboard.c:1300
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_keycode
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
In drivers/tty/vt/keyboard.c (ffffffff81906f6e)
Location: drivers/tty/vt/keyboard.c:1312
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_keycode
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int emulate_raw(struct vc_data *vc, unsigned int keycode, unsigned char up_flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/keyboard.c (ffffffff81a609e0)
Location: drivers/tty/vt/keyboard.c:1312
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_keycode
```
**Symbols:**

```
ffffffff81a609e0-ffffffff81a60b47: emulate_raw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int emulate_raw(struct vc_data *vc, unsigned int keycode, unsigned char up_flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/keyboard.c (ffffffff81aab0a0)
Location: drivers/tty/vt/keyboard.c:1312
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_keycode
```
**Symbols:**

```
ffffffff81aab0a0-ffffffff81aab207: emulate_raw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int emulate_raw(struct vc_data *vc, unsigned int keycode, unsigned char up_flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/keyboard.c (ffffffff81afdc40)
Location: drivers/tty/vt/keyboard.c:1312
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_keycode
```
**Symbols:**

```
ffffffff81afdc40-ffffffff81afdda7: emulate_raw (STB_LOCAL)
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
In drivers/tty/vt/keyboard.c (ffff80001086bc90)
Location: drivers/tty/vt/keyboard.c:1328
Inline: True
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
In drivers/tty/vt/keyboard.c (c09706a4)
Location: drivers/tty/vt/keyboard.c:1265
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_keycode
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
In drivers/tty/vt/keyboard.c (c00000000090c450)
Location: drivers/tty/vt/keyboard.c:1265
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_keycode
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
In drivers/tty/vt/keyboard.c (ffffffe000540468)
Location: drivers/tty/vt/keyboard.c:1328
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
In drivers/tty/vt/keyboard.c (ffffffff8165c599)
Location: drivers/tty/vt/keyboard.c:1265
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_keycode
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
In drivers/tty/vt/keyboard.c (ffffffff8163c919)
Location: drivers/tty/vt/keyboard.c:1265
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_keycode
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
In drivers/tty/vt/keyboard.c (ffffffff8168a979)
Location: drivers/tty/vt/keyboard.c:1265
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_keycode
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
In drivers/tty/vt/keyboard.c (ffffffff816a4f79)
Location: drivers/tty/vt/keyboard.c:1265
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_keycode
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
