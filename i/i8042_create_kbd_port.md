# Function: <code>i8042_create_kbd_port</code>

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
In drivers/input/serio/i8042.c (ffffffff81fb1862)
Location: drivers/input/serio/i8042.c:1266
Inline: True
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
In drivers/input/serio/i8042.c (ffffffff81fde390)
Location: drivers/input/serio/i8042.c:1266
Inline: True
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
In drivers/input/serio/i8042.c (ffffffff8201bfa7)
Location: drivers/input/serio/i8042.c:1299
Inline: True
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
In drivers/input/serio/i8042.c (ffffffff820fe917)
Location: drivers/input/serio/i8042.c:1307
Inline: True
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
In drivers/input/serio/i8042.c (ffffffff827081bc)
Location: drivers/input/serio/i8042.c:1307
Inline: True
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
In drivers/input/serio/i8042.c (ffffffff82732507)
Location: drivers/input/serio/i8042.c:1307
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_probe
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
In drivers/input/serio/i8042.c (ffffffff828eba18)
Location: drivers/input/serio/i8042.c:1310
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_probe
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
In drivers/input/serio/i8042.c (ffffffff82905fd8)
Location: drivers/input/serio/i8042.c:1303
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_probe
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
In drivers/input/serio/i8042.c (ffffffff8290fa13)
Location: drivers/input/serio/i8042.c:1320
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int i8042_create_kbd_port();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff82d235be)
Location: drivers/input/serio/i8042.c:1322
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_probe
```
**Symbols:**

```
ffffffff82d235be-ffffffff82d23703: i8042_create_kbd_port (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int i8042_create_kbd_port();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff8301140a)
Location: drivers/input/serio/i8042.c:1345
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_probe
```
**Symbols:**

```
ffffffff8301140a-ffffffff8301154f: i8042_create_kbd_port (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int i8042_create_kbd_port();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff8321c3f7)
Location: drivers/input/serio/i8042.c:1345
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_probe
```
**Symbols:**

```
ffffffff8321c3f7-ffffffff8321c53c: i8042_create_kbd_port (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int i8042_create_kbd_port();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:1349
Inline: False
```
**Symbols:**

```
ffffffff819b2060-ffffffff819b21e6: i8042_create_kbd_port (STB_LOCAL)
ffffffff81d228f4-ffffffff81d22936: i8042_create_kbd_port.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int i8042_create_kbd_port();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:1349
Inline: False
```
**Symbols:**

```
ffffffff81b10cb0-ffffffff81b10e3c: i8042_create_kbd_port (STB_LOCAL)
ffffffff81eee4f2-ffffffff81eee534: i8042_create_kbd_port.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int i8042_create_kbd_port();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:1349
Inline: False
```
**Symbols:**

```
ffffffff81ca1620-ffffffff81ca17a2: i8042_create_kbd_port (STB_LOCAL)
ffffffff820a621a-ffffffff820a6244: i8042_create_kbd_port.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int i8042_create_kbd_port();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:1349
Inline: False
```
**Symbols:**

```
ffffffff81d08a40-ffffffff81d08bc2: i8042_create_kbd_port (STB_LOCAL)
ffffffff82127621-ffffffff8212764b: i8042_create_kbd_port.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int i8042_create_kbd_port();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:1349
Inline: False
```
**Symbols:**

```
ffffffff81dbe6a0-ffffffff81dbe851: i8042_create_kbd_port (STB_LOCAL)
ffffffff82208fa2-ffffffff82208fcc: i8042_create_kbd_port.cold (STB_LOCAL)
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
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (c0000000013b367c)
Location: drivers/input/serio/i8042.c:1320
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_probe
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff828f67b2)
Location: drivers/input/serio/i8042.c:1320
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_probe
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
In drivers/input/serio/i8042.c (ffffffff828edc19)
Location: drivers/input/serio/i8042.c:1320
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_probe
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
In drivers/input/serio/i8042.c (ffffffff8290a5aa)
Location: drivers/input/serio/i8042.c:1320
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_probe
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
In drivers/input/serio/i8042.c (ffffffff82910a75)
Location: drivers/input/serio/i8042.c:1320
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_probe
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
