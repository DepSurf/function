# Function: <code>kbd_keycode</code>

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
In drivers/tty/vt/keyboard.c (ffffffff814f395a)
Location: drivers/tty/vt/keyboard.c:1327
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
In drivers/tty/vt/keyboard.c (ffffffff8154456a)
Location: drivers/tty/vt/keyboard.c:1315
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
In drivers/tty/vt/keyboard.c (ffffffff81570baa)
Location: drivers/tty/vt/keyboard.c:1315
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
In drivers/tty/vt/keyboard.c (ffffffff81584de3)
Location: drivers/tty/vt/keyboard.c:1315
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
In drivers/tty/vt/keyboard.c (ffffffff815e98e3)
Location: drivers/tty/vt/keyboard.c:1316
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
In drivers/tty/vt/keyboard.c (ffffffff81622ab8)
Location: drivers/tty/vt/keyboard.c:1316
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
In drivers/tty/vt/keyboard.c (ffffffff8163ff54)
Location: drivers/tty/vt/keyboard.c:1346
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void kbd_keycode(unsigned int keycode, int down, int hw_raw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/keyboard.c (0)
Location: drivers/tty/vt/keyboard.c:1347
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_event
```
**Symbols:**

```
ffffffff81674320-ffffffff81674dd9: kbd_keycode (STB_LOCAL)
ffffffff81676423-ffffffff81676444: kbd_keycode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void kbd_keycode(unsigned int keycode, int down, int hw_raw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/keyboard.c (0)
Location: drivers/tty/vt/keyboard.c:1347
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_event
```
**Symbols:**

```
ffffffff81696a80-ffffffff81697539: kbd_keycode (STB_LOCAL)
ffffffff81698bc3-ffffffff81698be4: kbd_keycode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void kbd_keycode(unsigned int keycode, int down, int hw_raw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/keyboard.c (0)
Location: drivers/tty/vt/keyboard.c:1353
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_event
```
**Symbols:**

```
ffffffff81748b30-ffffffff8174915f: kbd_keycode (STB_LOCAL)
ffffffff8174af33-ffffffff8174af5c: kbd_keycode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void kbd_keycode(unsigned int keycode, int down, bool hw_raw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/keyboard.c (0)
Location: drivers/tty/vt/keyboard.c:1375
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_event
```
**Symbols:**

```
ffffffff81764850-ffffffff81764e9d: kbd_keycode (STB_LOCAL)
ffffffff81c07923-ffffffff81c0794c: kbd_keycode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void kbd_keycode(unsigned int keycode, int down, bool hw_raw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/keyboard.c (0)
Location: drivers/tty/vt/keyboard.c:1385
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_event
```
**Symbols:**

```
ffffffff81748210-ffffffff817487f1: kbd_keycode (STB_LOCAL)
ffffffff81bf955d-ffffffff81bf9586: kbd_keycode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void kbd_keycode(unsigned int keycode, int down, bool hw_raw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/keyboard.c (0)
Location: drivers/tty/vt/keyboard.c:1385
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_event
```
**Symbols:**

```
ffffffff817c9740-ffffffff817c9e3a: kbd_keycode (STB_LOCAL)
ffffffff81cf943c-ffffffff81cf947b: kbd_keycode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void kbd_keycode(unsigned int keycode, int down, bool hw_raw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/keyboard.c (0)
Location: drivers/tty/vt/keyboard.c:1397
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_event
```
**Symbols:**

```
ffffffff81906cc0-ffffffff81907408: kbd_keycode (STB_LOCAL)
ffffffff81ec1616-ffffffff81ec1655: kbd_keycode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void kbd_keycode(unsigned int keycode, int down, bool hw_raw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/keyboard.c (0)
Location: drivers/tty/vt/keyboard.c:1397
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_event
```
**Symbols:**

```
ffffffff81a61330-ffffffff81a61886: kbd_keycode (STB_LOCAL)
ffffffff8209586c-ffffffff82095891: kbd_keycode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void kbd_keycode(unsigned int keycode, int down, bool hw_raw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/keyboard.c (0)
Location: drivers/tty/vt/keyboard.c:1397
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_event
```
**Symbols:**

```
ffffffff81aab9f0-ffffffff81aabfba: kbd_keycode (STB_LOCAL)
ffffffff821166b7-ffffffff821166dc: kbd_keycode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void kbd_keycode(unsigned int keycode, int down, bool hw_raw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/keyboard.c (0)
Location: drivers/tty/vt/keyboard.c:1397
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_event
```
**Symbols:**

```
ffffffff81afe590-ffffffff81afeb5a: kbd_keycode (STB_LOCAL)
ffffffff821f43dd-ffffffff821f4402: kbd_keycode.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/keyboard.c (ffff80001086bbd0)
Location: drivers/tty/vt/keyboard.c:1347
Inline: True
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_event
```
**Symbols:**

```
ffff80001086bbd0-ffff80001086c1ac: kbd_keycode.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void kbd_keycode(unsigned int keycode, int down, int hw_raw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/keyboard.c (c09705bc)
Location: drivers/tty/vt/keyboard.c:1347
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_event
```
**Symbols:**

```
c09705bc-c0971070: kbd_keycode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void kbd_keycode(unsigned int keycode, int down, int hw_raw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/keyboard.c (c00000000090bf10)
Location: drivers/tty/vt/keyboard.c:1347
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_event
```
**Symbols:**

```
c00000000090bf10-c00000000090ccb8: kbd_keycode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/keyboard.c (ffffffe000540114)
Location: drivers/tty/vt/keyboard.c:1347
Inline: True
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_event
```
**Symbols:**

```
ffffffe000540114-ffffffe000540636: kbd_keycode.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void kbd_keycode(unsigned int keycode, int down, int hw_raw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/keyboard.c (0)
Location: drivers/tty/vt/keyboard.c:1347
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_event
```
**Symbols:**

```
ffffffff8165c4e0-ffffffff8165cf99: kbd_keycode (STB_LOCAL)
ffffffff8165e623-ffffffff8165e644: kbd_keycode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void kbd_keycode(unsigned int keycode, int down, int hw_raw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/keyboard.c (0)
Location: drivers/tty/vt/keyboard.c:1347
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_event
```
**Symbols:**

```
ffffffff8163c860-ffffffff8163d319: kbd_keycode (STB_LOCAL)
ffffffff8163e9a3-ffffffff8163e9c4: kbd_keycode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void kbd_keycode(unsigned int keycode, int down, int hw_raw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/keyboard.c (0)
Location: drivers/tty/vt/keyboard.c:1347
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_event
```
**Symbols:**

```
ffffffff8168a8c0-ffffffff8168b379: kbd_keycode (STB_LOCAL)
ffffffff8168ca03-ffffffff8168ca24: kbd_keycode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void kbd_keycode(unsigned int keycode, int down, int hw_raw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/keyboard.c (0)
Location: drivers/tty/vt/keyboard.c:1347
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_event
```
**Symbols:**

```
ffffffff816a4ec0-ffffffff816a5979: kbd_keycode (STB_LOCAL)
ffffffff816a7003-ffffffff816a7024: kbd_keycode.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int hw_raw</code> ➡️ <code>bool hw_raw</code>
</li>
</ul>
</details>
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
