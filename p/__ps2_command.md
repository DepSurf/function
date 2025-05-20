# Function: <code>__ps2_command</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __ps2_command(struct ps2dev *ps2dev, unsigned char *param, int command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff816663b0)
Location: drivers/input/serio/libps2.c:183
Inline: False
Direct callers:
  - drivers/input/serio/libps2.c:ps2_command
```
**Symbols:**

```
ffffffff816663b0-ffffffff81666857: __ps2_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __ps2_command(struct ps2dev *ps2dev, unsigned char *param, int command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff816c6650)
Location: drivers/input/serio/libps2.c:181
Inline: False
Direct callers:
  - drivers/input/serio/libps2.c:ps2_command
```
**Symbols:**

```
ffffffff816c6650-ffffffff816c6ae3: __ps2_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __ps2_command(struct ps2dev *ps2dev, unsigned char *param, int command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff816f4660)
Location: drivers/input/serio/libps2.c:181
Inline: False
Direct callers:
  - drivers/input/serio/libps2.c:ps2_command
```
**Symbols:**

```
ffffffff816f4660-ffffffff816f4ae8: __ps2_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __ps2_command(struct ps2dev *ps2dev, unsigned char *param, int command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff8170a210)
Location: drivers/input/serio/libps2.c:181
Inline: False
Direct callers:
  - drivers/input/serio/libps2.c:ps2_command
```
**Symbols:**

```
ffffffff8170a210-ffffffff8170a65f: __ps2_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __ps2_command(struct ps2dev *ps2dev, unsigned char *param, int command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff8177b3c0)
Location: drivers/input/serio/libps2.c:181
Inline: False
Direct callers:
  - drivers/input/serio/libps2.c:ps2_command
```
**Symbols:**

```
ffffffff8177b3c0-ffffffff8177b80f: __ps2_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __ps2_command(struct ps2dev *ps2dev, u8 *param, unsigned int command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff817bc1e0)
Location: drivers/input/serio/libps2.c:230
Inline: False
Direct callers:
  - drivers/input/serio/libps2.c:ps2_sliced_command
  - drivers/input/serio/libps2.c:ps2_sliced_command
  - drivers/input/serio/libps2.c:ps2_command
```
**Symbols:**

```
ffffffff817bc1e0-ffffffff817bc7a2: __ps2_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __ps2_command(struct ps2dev *ps2dev, u8 *param, unsigned int command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff817e3640)
Location: drivers/input/serio/libps2.c:230
Inline: False
Direct callers:
  - drivers/input/serio/libps2.c:ps2_sliced_command
  - drivers/input/serio/libps2.c:ps2_sliced_command
  - drivers/input/serio/libps2.c:ps2_command
```
**Symbols:**

```
ffffffff817e3640-ffffffff817e3c02: __ps2_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int __ps2_command(struct ps2dev *ps2dev, u8 *param, unsigned int command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/libps2.c (0)
Location: drivers/input/serio/libps2.c:226
Inline: False
Direct callers:
  - drivers/input/serio/libps2.c:ps2_sliced_command
  - drivers/input/serio/libps2.c:ps2_sliced_command
  - drivers/input/serio/libps2.c:ps2_command
```
**Symbols:**

```
ffffffff81824759-ffffffff8182478d: __ps2_command.cold (STB_LOCAL)
ffffffff81823fd0-ffffffff818245c7: __ps2_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __ps2_command(struct ps2dev *ps2dev, u8 *param, unsigned int command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff81855490)
Location: drivers/input/serio/libps2.c:226
Inline: False
Direct callers:
  - drivers/input/serio/libps2.c:ps2_sliced_command
  - drivers/input/serio/libps2.c:ps2_sliced_command
  - drivers/input/serio/libps2.c:ps2_command
```
**Symbols:**

```
ffffffff81855490-ffffffff81855a91: __ps2_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __ps2_command(struct ps2dev *ps2dev, u8 *param, unsigned int command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff819279b0)
Location: drivers/input/serio/libps2.c:226
Inline: False
Direct callers:
  - drivers/input/serio/libps2.c:ps2_sliced_command
  - drivers/input/serio/libps2.c:ps2_sliced_command
  - drivers/input/serio/libps2.c:ps2_command
```
**Symbols:**

```
ffffffff819279b0-ffffffff81927fb1: __ps2_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __ps2_command(struct ps2dev *ps2dev, u8 *param, unsigned int command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff8192eec0)
Location: drivers/input/serio/libps2.c:226
Inline: False
Direct callers:
  - drivers/input/serio/libps2.c:ps2_sliced_command
  - drivers/input/serio/libps2.c:ps2_sliced_command
  - drivers/input/serio/libps2.c:ps2_command
```
**Symbols:**

```
ffffffff8192eec0-ffffffff8192f4c1: __ps2_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __ps2_command(struct ps2dev *ps2dev, u8 *param, unsigned int command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff81912280)
Location: drivers/input/serio/libps2.c:226
Inline: False
Direct callers:
  - drivers/input/serio/libps2.c:ps2_sliced_command
  - drivers/input/serio/libps2.c:ps2_sliced_command
  - drivers/input/serio/libps2.c:ps2_command
```
**Symbols:**

```
ffffffff81912280-ffffffff81912846: __ps2_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __ps2_command(struct ps2dev *ps2dev, u8 *param, unsigned int command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff819b4230)
Location: drivers/input/serio/libps2.c:226
Inline: False
Direct callers:
  - drivers/input/serio/libps2.c:ps2_sliced_command
  - drivers/input/serio/libps2.c:ps2_sliced_command
  - drivers/input/serio/libps2.c:ps2_command
```
**Symbols:**

```
ffffffff819b4230-ffffffff819b4896: __ps2_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __ps2_command(struct ps2dev *ps2dev, u8 *param, unsigned int command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff81b130c0)
Location: drivers/input/serio/libps2.c:226
Inline: False
Direct callers:
  - drivers/input/serio/libps2.c:ps2_sliced_command
  - drivers/input/serio/libps2.c:ps2_sliced_command
  - drivers/input/serio/libps2.c:ps2_command
```
**Symbols:**

```
ffffffff81b130c0-ffffffff81b1371b: __ps2_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __ps2_command(struct ps2dev *ps2dev, u8 *param, unsigned int command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff81ca3ff0)
Location: drivers/input/serio/libps2.c:227
Inline: False
Direct callers:
  - drivers/input/serio/libps2.c:ps2_sliced_command
  - drivers/input/serio/libps2.c:ps2_sliced_command
  - drivers/input/serio/libps2.c:ps2_command
```
**Symbols:**

```
ffffffff81ca3ff0-ffffffff81ca464b: __ps2_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __ps2_command(struct ps2dev *ps2dev, u8 *param, unsigned int command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff81d0b6d0)
Location: drivers/input/serio/libps2.c:265
Inline: False
Direct callers:
  - drivers/input/serio/libps2.c:ps2_sliced_command
  - drivers/input/serio/libps2.c:ps2_sliced_command
  - drivers/input/serio/libps2.c:ps2_command
```
**Symbols:**

```
ffffffff81d0b6d0-ffffffff81d0bda8: __ps2_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __ps2_command(struct ps2dev *ps2dev, u8 *param, unsigned int command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff81dc1360)
Location: drivers/input/serio/libps2.c:265
Inline: False
Direct callers:
  - drivers/input/serio/libps2.c:ps2_sliced_command
  - drivers/input/serio/libps2.c:ps2_sliced_command
  - drivers/input/serio/libps2.c:ps2_command
```
**Symbols:**

```
ffffffff81dc1360-ffffffff81dc1a38: __ps2_command (STB_GLOBAL)
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
int __ps2_command(struct ps2dev *ps2dev, u8 *param, unsigned int command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffff800010a942b0)
Location: drivers/input/serio/libps2.c:226
Inline: False
Direct callers:
  - drivers/input/serio/libps2.c:ps2_sliced_command
  - drivers/input/serio/libps2.c:ps2_sliced_command
  - drivers/input/serio/libps2.c:ps2_command
```
**Symbols:**

```
ffff800010a942b0-ffff800010a948d4: __ps2_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __ps2_command(struct ps2dev *ps2dev, u8 *param, unsigned int command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (c0b76e08)
Location: drivers/input/serio/libps2.c:226
Inline: False
Direct callers:
  - drivers/input/serio/libps2.c:ps2_sliced_command
  - drivers/input/serio/libps2.c:ps2_sliced_command
  - drivers/input/serio/libps2.c:ps2_command
```
**Symbols:**

```
c0b76e08-c0b773b4: __ps2_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __ps2_command(struct ps2dev *ps2dev, u8 *param, unsigned int command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (c000000000b72fe0)
Location: drivers/input/serio/libps2.c:226
Inline: False
Direct callers:
  - drivers/input/serio/libps2.c:ps2_sliced_command
  - drivers/input/serio/libps2.c:ps2_sliced_command
  - drivers/input/serio/libps2.c:ps2_command
  - drivers/input/serio/libps2.c:ps2_command
```
**Symbols:**

```
c000000000b72fe0-c000000000b736fc: __ps2_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __ps2_command(struct ps2dev *ps2dev, u8 *param, unsigned int command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffe0006a63bc)
Location: drivers/input/serio/libps2.c:226
Inline: False
Direct callers:
  - drivers/input/serio/libps2.c:ps2_sliced_command
  - drivers/input/serio/libps2.c:ps2_sliced_command
  - drivers/input/serio/libps2.c:ps2_command
```
**Symbols:**

```
ffffffe0006a63bc-ffffffe0006a6868: __ps2_command (STB_GLOBAL)
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
int __ps2_command(struct ps2dev *ps2dev, u8 *param, unsigned int command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff8180a4a0)
Location: drivers/input/serio/libps2.c:226
Inline: False
Direct callers:
  - drivers/input/serio/libps2.c:ps2_sliced_command
  - drivers/input/serio/libps2.c:ps2_sliced_command
  - drivers/input/serio/libps2.c:ps2_command
```
**Symbols:**

```
ffffffff8180a4a0-ffffffff8180aaa1: __ps2_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __ps2_command(struct ps2dev *ps2dev, u8 *param, unsigned int command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff817d1c30)
Location: drivers/input/serio/libps2.c:226
Inline: False
Direct callers:
  - drivers/input/serio/libps2.c:ps2_sliced_command
  - drivers/input/serio/libps2.c:ps2_sliced_command
  - drivers/input/serio/libps2.c:ps2_command
```
**Symbols:**

```
ffffffff817d1c30-ffffffff817d2219: __ps2_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __ps2_command(struct ps2dev *ps2dev, u8 *param, unsigned int command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff81849620)
Location: drivers/input/serio/libps2.c:226
Inline: False
Direct callers:
  - drivers/input/serio/libps2.c:ps2_sliced_command
  - drivers/input/serio/libps2.c:ps2_sliced_command
  - drivers/input/serio/libps2.c:ps2_command
```
**Symbols:**

```
ffffffff81849620-ffffffff81849c21: __ps2_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __ps2_command(struct ps2dev *ps2dev, u8 *param, unsigned int command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff81864550)
Location: drivers/input/serio/libps2.c:226
Inline: False
Direct callers:
  - drivers/input/serio/libps2.c:ps2_sliced_command
  - drivers/input/serio/libps2.c:ps2_sliced_command
  - drivers/input/serio/libps2.c:ps2_command
```
**Symbols:**

```
ffffffff81864550-ffffffff81864b15: __ps2_command (STB_GLOBAL)
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
<code>unsigned char *param</code> ➡️ <code>u8 *param</code>
</li>
<li>
<b>Param type changed. </b>
<code>int command</code> ➡️ <code>unsigned int command</code>
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
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
