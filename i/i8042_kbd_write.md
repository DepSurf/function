# Function: <code>i8042_kbd_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int i8042_kbd_write(struct serio *port, unsigned char c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff816649e0)
Location: drivers/input/serio/i8042.c:328
Inline: False
```
**Symbols:**

```
ffffffff816649e0-ffffffff81664a55: i8042_kbd_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int i8042_kbd_write(struct serio *port, unsigned char c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff816c4bf0)
Location: drivers/input/serio/i8042.c:328
Inline: False
```
**Symbols:**

```
ffffffff816c4bf0-ffffffff816c4c65: i8042_kbd_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int i8042_kbd_write(struct serio *port, unsigned char c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff816f2c10)
Location: drivers/input/serio/i8042.c:358
Inline: False
```
**Symbols:**

```
ffffffff816f2c10-ffffffff816f2c85: i8042_kbd_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int i8042_kbd_write(struct serio *port, unsigned char c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff81708540)
Location: drivers/input/serio/i8042.c:360
Inline: False
```
**Symbols:**

```
ffffffff81708540-ffffffff817085b5: i8042_kbd_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int i8042_kbd_write(struct serio *port, unsigned char c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff81779730)
Location: drivers/input/serio/i8042.c:360
Inline: False
```
**Symbols:**

```
ffffffff81779730-ffffffff817797a5: i8042_kbd_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int i8042_kbd_write(struct serio *port, unsigned char c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:360
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_probe
```
**Symbols:**

```
ffffffff817ba450-ffffffff817ba4aa: i8042_kbd_write (STB_LOCAL)
ffffffff817bb5ea-ffffffff817bb60c: i8042_kbd_write.cold.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int i8042_kbd_write(struct serio *port, unsigned char c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:360
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_probe
```
**Symbols:**

```
ffffffff817e1870-ffffffff817e18ca: i8042_kbd_write (STB_LOCAL)
ffffffff817e2a5a-ffffffff817e2a7c: i8042_kbd_write.cold.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int i8042_kbd_write(struct serio *port, unsigned char c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:356
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_probe
```
**Symbols:**

```
ffffffff81822170-ffffffff818221ca: i8042_kbd_write (STB_LOCAL)
ffffffff818233d9-ffffffff818233fa: i8042_kbd_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int i8042_kbd_write(struct serio *port, unsigned char c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:356
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_probe
```
**Symbols:**

```
ffffffff818535e0-ffffffff8185363a: i8042_kbd_write (STB_LOCAL)
ffffffff81854899-ffffffff818548ba: i8042_kbd_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int i8042_kbd_write(struct serio *port, unsigned char c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:358
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_check_aux
```
**Symbols:**

```
ffffffff819257a0-ffffffff81925833: i8042_kbd_write (STB_LOCAL)
ffffffff81926be1-ffffffff81926c03: i8042_kbd_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int i8042_kbd_write(struct serio *port, unsigned char c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:381
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_check_aux
```
**Symbols:**

```
ffffffff8192e080-ffffffff8192e113: i8042_kbd_write (STB_LOCAL)
ffffffff81c23028-ffffffff81c2304a: i8042_kbd_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int i8042_kbd_write(struct serio *port, unsigned char c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:381
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_check_aux
```
**Symbols:**

```
ffffffff81911470-ffffffff8191150a: i8042_kbd_write (STB_LOCAL)
ffffffff81c15151-ffffffff81c15173: i8042_kbd_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int i8042_kbd_write(struct serio *port, unsigned char c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:385
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_check_aux
```
**Symbols:**

```
ffffffff819b2be0-ffffffff819b2c86: i8042_kbd_write (STB_LOCAL)
ffffffff81d22c5c-ffffffff81d22c92: i8042_kbd_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int i8042_kbd_write(struct serio *port, unsigned char c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:385
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_check_aux
```
**Symbols:**

```
ffffffff81b110d0-ffffffff81b1117d: i8042_kbd_write (STB_LOCAL)
ffffffff81eee696-ffffffff81eee6cc: i8042_kbd_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int i8042_kbd_write(struct serio *port, unsigned char c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:385
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_check_aux
```
**Symbols:**

```
ffffffff81ca1b20-ffffffff81ca1be8: i8042_kbd_write (STB_LOCAL)
ffffffff820a62e5-ffffffff820a62f9: i8042_kbd_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int i8042_kbd_write(struct serio *port, unsigned char c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:385
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_check_aux
```
**Symbols:**

```
ffffffff81d08f40-ffffffff81d09008: i8042_kbd_write (STB_LOCAL)
ffffffff821276ec-ffffffff82127700: i8042_kbd_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int i8042_kbd_write(struct serio *port, unsigned char c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:385
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_check_aux
```
**Symbols:**

```
ffffffff81dbebd0-ffffffff81dbec98: i8042_kbd_write (STB_LOCAL)
ffffffff8220906d-ffffffff82209081: i8042_kbd_write.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int i8042_kbd_write(struct serio *port, unsigned char c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (c000000000b706e0)
Location: drivers/input/serio/i8042.c:356
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_probe
```
**Symbols:**

```
c000000000b706e0-c000000000b70830: i8042_kbd_write (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int i8042_kbd_write(struct serio *port, unsigned char c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:356
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_probe
```
**Symbols:**

```
ffffffff818086c0-ffffffff8180871a: i8042_kbd_write (STB_LOCAL)
ffffffff818098a9-ffffffff818098ca: i8042_kbd_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int i8042_kbd_write(struct serio *port, unsigned char c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:356
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_probe
```
**Symbols:**

```
ffffffff817cfda0-ffffffff817cfdfa: i8042_kbd_write (STB_LOCAL)
ffffffff817d1049-ffffffff817d106a: i8042_kbd_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int i8042_kbd_write(struct serio *port, unsigned char c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:356
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_probe
```
**Symbols:**

```
ffffffff81847770-ffffffff818477ca: i8042_kbd_write (STB_LOCAL)
ffffffff81848a29-ffffffff81848a4a: i8042_kbd_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int i8042_kbd_write(struct serio *port, unsigned char c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:356
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_probe
```
**Symbols:**

```
ffffffff818629b0-ffffffff81862a0a: i8042_kbd_write (STB_LOCAL)
ffffffff81863c49-ffffffff81863c6a: i8042_kbd_write.cold (STB_LOCAL)
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
