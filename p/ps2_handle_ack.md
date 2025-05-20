# Function: <code>ps2_handle_ack</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int ps2_handle_ack(struct ps2dev *ps2dev, unsigned char data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff81665fe0)
Location: drivers/input/serio/libps2.c:291
Inline: True
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
ffffffff81665fe0-ffffffff8166611e: ps2_handle_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ps2_handle_ack(struct ps2dev *ps2dev, unsigned char data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff816c6260)
Location: drivers/input/serio/libps2.c:289
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
ffffffff816c6260-ffffffff816c639e: ps2_handle_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ps2_handle_ack(struct ps2dev *ps2dev, unsigned char data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff816f4280)
Location: drivers/input/serio/libps2.c:289
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
ffffffff816f4280-ffffffff816f43be: ps2_handle_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ps2_handle_ack(struct ps2dev *ps2dev, unsigned char data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff81709df0)
Location: drivers/input/serio/libps2.c:289
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
ffffffff81709df0-ffffffff81709f2e: ps2_handle_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ps2_handle_ack(struct ps2dev *ps2dev, unsigned char data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff8177afa0)
Location: drivers/input/serio/libps2.c:289
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
ffffffff8177afa0-ffffffff8177b0de: ps2_handle_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool ps2_handle_ack(struct ps2dev *ps2dev, u8 data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff817bbc60)
Location: drivers/input/serio/libps2.c:394
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
ffffffff817bbc60-ffffffff817bbde0: ps2_handle_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool ps2_handle_ack(struct ps2dev *ps2dev, u8 data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff817e30c0)
Location: drivers/input/serio/libps2.c:394
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
ffffffff817e30c0-ffffffff817e3240: ps2_handle_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool ps2_handle_ack(struct ps2dev *ps2dev, u8 data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff81823a40)
Location: drivers/input/serio/libps2.c:390
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
ffffffff81823a40-ffffffff81823bc4: ps2_handle_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool ps2_handle_ack(struct ps2dev *ps2dev, u8 data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff81854f00)
Location: drivers/input/serio/libps2.c:390
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
ffffffff81854f00-ffffffff81855084: ps2_handle_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool ps2_handle_ack(struct ps2dev *ps2dev, u8 data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff819273d0)
Location: drivers/input/serio/libps2.c:390
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
ffffffff819273d0-ffffffff81927554: ps2_handle_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool ps2_handle_ack(struct ps2dev *ps2dev, u8 data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff8192e8e0)
Location: drivers/input/serio/libps2.c:390
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
ffffffff8192e8e0-ffffffff8192ea64: ps2_handle_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool ps2_handle_ack(struct ps2dev *ps2dev, u8 data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff81911cc0)
Location: drivers/input/serio/libps2.c:390
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
ffffffff81911cc0-ffffffff81911e2d: ps2_handle_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool ps2_handle_ack(struct ps2dev *ps2dev, u8 data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff819b3c70)
Location: drivers/input/serio/libps2.c:390
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
ffffffff819b3c70-ffffffff819b3ddd: ps2_handle_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool ps2_handle_ack(struct ps2dev *ps2dev, u8 data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff81b13860)
Location: drivers/input/serio/libps2.c:390
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
ffffffff81b13860-ffffffff81b139cd: ps2_handle_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool ps2_handle_ack(struct ps2dev *ps2dev, u8 data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff81ca47c0)
Location: drivers/input/serio/libps2.c:393
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
ffffffff81ca47c0-ffffffff81ca492d: ps2_handle_ack (STB_GLOBAL)
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
In drivers/input/serio/libps2.c (ffffffff81d0c011)
Location: drivers/input/serio/libps2.c:501
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:ps2_interrupt
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
In drivers/input/serio/libps2.c (ffffffff81dc1ca1)
Location: drivers/input/serio/libps2.c:501
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:ps2_interrupt
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
bool ps2_handle_ack(struct ps2dev *ps2dev, u8 data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffff800010a93ba0)
Location: drivers/input/serio/libps2.c:390
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
ffff800010a93ba0-ffff800010a93d34: ps2_handle_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool ps2_handle_ack(struct ps2dev *ps2dev, u8 data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (c0b77688)
Location: drivers/input/serio/libps2.c:390
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
c0b77688-c0b77818: ps2_handle_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool ps2_handle_ack(struct ps2dev *ps2dev, u8 data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (c000000000b72720)
Location: drivers/input/serio/libps2.c:390
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
c000000000b72720-c000000000b72944: ps2_handle_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool ps2_handle_ack(struct ps2dev *ps2dev, u8 data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffe0006a5e0e)
Location: drivers/input/serio/libps2.c:390
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
ffffffe0006a5e0e-ffffffe0006a5f84: ps2_handle_ack (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
bool ps2_handle_ack(struct ps2dev *ps2dev, u8 data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff81809f10)
Location: drivers/input/serio/libps2.c:390
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
ffffffff81809f10-ffffffff8180a094: ps2_handle_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool ps2_handle_ack(struct ps2dev *ps2dev, u8 data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff817d16b0)
Location: drivers/input/serio/libps2.c:390
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
ffffffff817d16b0-ffffffff817d1834: ps2_handle_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool ps2_handle_ack(struct ps2dev *ps2dev, u8 data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff81849090)
Location: drivers/input/serio/libps2.c:390
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
ffffffff81849090-ffffffff81849214: ps2_handle_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool ps2_handle_ack(struct ps2dev *ps2dev, u8 data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff81864dd0)
Location: drivers/input/serio/libps2.c:390
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
ffffffff81864dd0-ffffffff81864f54: ps2_handle_ack (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>unsigned char data</code> ➡️ <code>u8 data</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
