# Function: <code>ps2_handle_response</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int ps2_handle_response(struct ps2dev *ps2dev, unsigned char data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff81665f50)
Location: drivers/input/serio/libps2.c:349
Inline: True
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
ffffffff81665f50-ffffffff81665fe0: ps2_handle_response (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int ps2_handle_response(struct ps2dev *ps2dev, unsigned char data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff816c61d0)
Location: drivers/input/serio/libps2.c:347
Inline: True
Direct callers:
  - drivers/input/serio/libps2.c:ps2_handle_ack
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
ffffffff816c61d0-ffffffff816c6260: ps2_handle_response (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int ps2_handle_response(struct ps2dev *ps2dev, unsigned char data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff816f41f0)
Location: drivers/input/serio/libps2.c:347
Inline: True
Direct callers:
  - drivers/input/serio/libps2.c:ps2_handle_ack
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
ffffffff816f41f0-ffffffff816f4280: ps2_handle_response (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int ps2_handle_response(struct ps2dev *ps2dev, unsigned char data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff81709d50)
Location: drivers/input/serio/libps2.c:347
Inline: True
Direct callers:
  - drivers/input/serio/libps2.c:ps2_handle_ack
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
ffffffff81709d50-ffffffff81709de8: ps2_handle_response (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int ps2_handle_response(struct ps2dev *ps2dev, unsigned char data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff8177af00)
Location: drivers/input/serio/libps2.c:347
Inline: True
Direct callers:
  - drivers/input/serio/libps2.c:ps2_handle_ack
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
ffffffff8177af00-ffffffff8177af98: ps2_handle_response (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool ps2_handle_response(struct ps2dev *ps2dev, u8 data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff817bbbc0)
Location: drivers/input/serio/libps2.c:463
Inline: True
Direct callers:
  - drivers/input/serio/libps2.c:ps2_handle_ack
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
ffffffff817bbbc0-ffffffff817bbc5d: ps2_handle_response (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool ps2_handle_response(struct ps2dev *ps2dev, u8 data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff817e3020)
Location: drivers/input/serio/libps2.c:463
Inline: True
Direct callers:
  - drivers/input/serio/libps2.c:ps2_handle_ack
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
ffffffff817e3020-ffffffff817e30bd: ps2_handle_response (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool ps2_handle_response(struct ps2dev *ps2dev, u8 data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff818239a0)
Location: drivers/input/serio/libps2.c:460
Inline: True
Direct callers:
  - drivers/input/serio/libps2.c:ps2_handle_ack
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
ffffffff818239a0-ffffffff81823a3d: ps2_handle_response (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool ps2_handle_response(struct ps2dev *ps2dev, u8 data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff81854e60)
Location: drivers/input/serio/libps2.c:460
Inline: True
Direct callers:
  - drivers/input/serio/libps2.c:ps2_handle_ack
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
ffffffff81854e60-ffffffff81854efd: ps2_handle_response (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool ps2_handle_response(struct ps2dev *ps2dev, u8 data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff81927320)
Location: drivers/input/serio/libps2.c:460
Inline: False
Direct callers:
  - drivers/input/serio/libps2.c:ps2_handle_ack
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
ffffffff81927320-ffffffff819273c3: ps2_handle_response (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool ps2_handle_response(struct ps2dev *ps2dev, u8 data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff8192e840)
Location: drivers/input/serio/libps2.c:460
Inline: False
Direct callers:
  - drivers/input/serio/libps2.c:ps2_handle_ack
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
ffffffff8192e840-ffffffff8192e8df: ps2_handle_response (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool ps2_handle_response(struct ps2dev *ps2dev, u8 data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff81911c20)
Location: drivers/input/serio/libps2.c:460
Inline: False
Direct callers:
  - drivers/input/serio/libps2.c:ps2_handle_ack
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
ffffffff81911c20-ffffffff81911cbf: ps2_handle_response (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool ps2_handle_response(struct ps2dev *ps2dev, u8 data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff819b3ba0)
Location: drivers/input/serio/libps2.c:460
Inline: False
Direct callers:
  - drivers/input/serio/libps2.c:ps2_handle_ack
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
ffffffff819b3ba0-ffffffff819b3c68: ps2_handle_response (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool ps2_handle_response(struct ps2dev *ps2dev, u8 data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff81b13780)
Location: drivers/input/serio/libps2.c:460
Inline: False
Direct callers:
  - drivers/input/serio/libps2.c:ps2_handle_ack
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
ffffffff81b13780-ffffffff81b13860: ps2_handle_response (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool ps2_handle_response(struct ps2dev *ps2dev, u8 data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff81ca46d0)
Location: drivers/input/serio/libps2.c:463
Inline: False
Direct callers:
  - drivers/input/serio/libps2.c:ps2_handle_ack
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
ffffffff81ca46d0-ffffffff81ca47b0: ps2_handle_response (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ps2_handle_response(struct ps2dev *ps2dev, u8 data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff81d0be40)
Location: drivers/input/serio/libps2.c:479
Inline: False
Direct callers:
  - drivers/input/serio/libps2.c:ps2_interrupt
  - drivers/input/serio/libps2.c:ps2_interrupt
```
**Symbols:**

```
ffffffff81d0be40-ffffffff81d0bf1a: ps2_handle_response (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ps2_handle_response(struct ps2dev *ps2dev, u8 data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff81dc1ad0)
Location: drivers/input/serio/libps2.c:479
Inline: False
Direct callers:
  - drivers/input/serio/libps2.c:ps2_interrupt
  - drivers/input/serio/libps2.c:ps2_interrupt
```
**Symbols:**

```
ffffffff81dc1ad0-ffffffff81dc1baa: ps2_handle_response (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
bool ps2_handle_response(struct ps2dev *ps2dev, u8 data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffff800010a93ae0)
Location: drivers/input/serio/libps2.c:460
Inline: True
Direct callers:
  - drivers/input/serio/libps2.c:ps2_handle_ack
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
ffff800010a93ae0-ffff800010a93ba0: ps2_handle_response (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool ps2_handle_response(struct ps2dev *ps2dev, u8 data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (c0b775cc)
Location: drivers/input/serio/libps2.c:460
Inline: True
Direct callers:
  - drivers/input/serio/libps2.c:ps2_handle_ack
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
c0b775cc-c0b77688: ps2_handle_response (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool ps2_handle_response(struct ps2dev *ps2dev, u8 data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (c000000000b72600)
Location: drivers/input/serio/libps2.c:460
Inline: True
Direct callers:
  - drivers/input/serio/libps2.c:ps2_handle_ack
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
c000000000b72600-c000000000b7271c: ps2_handle_response (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool ps2_handle_response(struct ps2dev *ps2dev, u8 data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffe0006a5d76)
Location: drivers/input/serio/libps2.c:460
Inline: True
Direct callers:
  - drivers/input/serio/libps2.c:ps2_handle_ack
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
ffffffe0006a5d76-ffffffe0006a5e0e: ps2_handle_response (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool ps2_handle_response(struct ps2dev *ps2dev, u8 data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff81809e70)
Location: drivers/input/serio/libps2.c:460
Inline: True
Direct callers:
  - drivers/input/serio/libps2.c:ps2_handle_ack
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
ffffffff81809e70-ffffffff81809f0d: ps2_handle_response (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool ps2_handle_response(struct ps2dev *ps2dev, u8 data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff817d1610)
Location: drivers/input/serio/libps2.c:460
Inline: True
Direct callers:
  - drivers/input/serio/libps2.c:ps2_handle_ack
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
ffffffff817d1610-ffffffff817d16ad: ps2_handle_response (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool ps2_handle_response(struct ps2dev *ps2dev, u8 data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff81848ff0)
Location: drivers/input/serio/libps2.c:460
Inline: True
Direct callers:
  - drivers/input/serio/libps2.c:ps2_handle_ack
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
ffffffff81848ff0-ffffffff8184908d: ps2_handle_response (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool ps2_handle_response(struct ps2dev *ps2dev, u8 data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff81864d30)
Location: drivers/input/serio/libps2.c:460
Inline: True
Direct callers:
  - drivers/input/serio/libps2.c:ps2_handle_ack
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
**Symbols:**

```
ffffffff81864d30-ffffffff81864dcd: ps2_handle_response (STB_GLOBAL)
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
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
