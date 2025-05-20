# Function: <code>ps2_do_sendbyte</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ps2_do_sendbyte(struct ps2dev *ps2dev, u8 byte, unsigned int timeout, unsigned int max_attempts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff817bbde0)
Location: drivers/input/serio/libps2.c:29
Inline: False
Direct callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_sendbyte
```
**Symbols:**

```
ffffffff817bbde0-ffffffff817bbff8: ps2_do_sendbyte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ps2_do_sendbyte(struct ps2dev *ps2dev, u8 byte, unsigned int timeout, unsigned int max_attempts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff817e3240)
Location: drivers/input/serio/libps2.c:29
Inline: False
Direct callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_sendbyte
```
**Symbols:**

```
ffffffff817e3240-ffffffff817e3458: ps2_do_sendbyte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ps2_do_sendbyte(struct ps2dev *ps2dev, u8 byte, unsigned int timeout, unsigned int max_attempts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff81823bd0)
Location: drivers/input/serio/libps2.c:25
Inline: False
Direct callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_sendbyte
```
**Symbols:**

```
ffffffff81823bd0-ffffffff81823deb: ps2_do_sendbyte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ps2_do_sendbyte(struct ps2dev *ps2dev, u8 byte, unsigned int timeout, unsigned int max_attempts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff81855090)
Location: drivers/input/serio/libps2.c:25
Inline: False
Direct callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_sendbyte
```
**Symbols:**

```
ffffffff81855090-ffffffff818552ab: ps2_do_sendbyte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ps2_do_sendbyte(struct ps2dev *ps2dev, u8 byte, unsigned int timeout, unsigned int max_attempts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff819275b0)
Location: drivers/input/serio/libps2.c:25
Inline: False
Direct callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_sendbyte
```
**Symbols:**

```
ffffffff819275b0-ffffffff819277c4: ps2_do_sendbyte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ps2_do_sendbyte(struct ps2dev *ps2dev, u8 byte, unsigned int timeout, unsigned int max_attempts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff8192eac0)
Location: drivers/input/serio/libps2.c:25
Inline: False
Direct callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_sendbyte
```
**Symbols:**

```
ffffffff8192eac0-ffffffff8192ecd4: ps2_do_sendbyte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ps2_do_sendbyte(struct ps2dev *ps2dev, u8 byte, unsigned int timeout, unsigned int max_attempts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff81911e80)
Location: drivers/input/serio/libps2.c:25
Inline: False
Direct callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_sendbyte
```
**Symbols:**

```
ffffffff81911e80-ffffffff81912094: ps2_do_sendbyte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ps2_do_sendbyte(struct ps2dev *ps2dev, u8 byte, unsigned int timeout, unsigned int max_attempts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff819b3e30)
Location: drivers/input/serio/libps2.c:25
Inline: False
Direct callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_sendbyte
```
**Symbols:**

```
ffffffff819b3e30-ffffffff819b4041: ps2_do_sendbyte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ps2_do_sendbyte(struct ps2dev *ps2dev, u8 byte, unsigned int timeout, unsigned int max_attempts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff81b12d40)
Location: drivers/input/serio/libps2.c:25
Inline: False
Direct callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_sendbyte
```
**Symbols:**

```
ffffffff81b12d40-ffffffff81b12f8e: ps2_do_sendbyte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ps2_do_sendbyte(struct ps2dev *ps2dev, u8 byte, unsigned int timeout, unsigned int max_attempts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff81ca3c20)
Location: drivers/input/serio/libps2.c:26
Inline: False
Direct callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_sendbyte
```
**Symbols:**

```
ffffffff81ca3c20-ffffffff81ca3e6e: ps2_do_sendbyte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ps2_do_sendbyte(struct ps2dev *ps2dev, u8 byte, unsigned int timeout, unsigned int max_attempts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff81d0b2e0)
Location: drivers/input/serio/libps2.c:43
Inline: False
Direct callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_sendbyte
```
**Symbols:**

```
ffffffff81d0b2e0-ffffffff81d0b545: ps2_do_sendbyte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ps2_do_sendbyte(struct ps2dev *ps2dev, u8 byte, unsigned int timeout, unsigned int max_attempts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff81dc0f70)
Location: drivers/input/serio/libps2.c:43
Inline: False
Direct callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_sendbyte
```
**Symbols:**

```
ffffffff81dc0f70-ffffffff81dc11d5: ps2_do_sendbyte (STB_LOCAL)
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
int ps2_do_sendbyte(struct ps2dev *ps2dev, u8 byte, unsigned int timeout, unsigned int max_attempts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffff800010a93d38)
Location: drivers/input/serio/libps2.c:25
Inline: False
Direct callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_sendbyte
```
**Symbols:**

```
ffff800010a93d38-ffff800010a93ff8: ps2_do_sendbyte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ps2_do_sendbyte(struct ps2dev *ps2dev, u8 byte, unsigned int timeout, unsigned int max_attempts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (c0b768c8)
Location: drivers/input/serio/libps2.c:25
Inline: False
Direct callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_sendbyte
```
**Symbols:**

```
c0b768c8-c0b76b30: ps2_do_sendbyte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ps2_do_sendbyte(struct ps2dev *ps2dev, u8 byte, unsigned int timeout, unsigned int max_attempts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (c000000000b72950)
Location: drivers/input/serio/libps2.c:25
Inline: False
Direct callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_sendbyte
```
**Symbols:**

```
c000000000b72950-c000000000b72c9c: ps2_do_sendbyte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ps2_do_sendbyte(struct ps2dev *ps2dev, u8 byte, unsigned int timeout, unsigned int max_attempts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffe0006a5f84)
Location: drivers/input/serio/libps2.c:25
Inline: False
Direct callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_sendbyte
```
**Symbols:**

```
ffffffe0006a5f84-ffffffe0006a61ae: ps2_do_sendbyte (STB_LOCAL)
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
int ps2_do_sendbyte(struct ps2dev *ps2dev, u8 byte, unsigned int timeout, unsigned int max_attempts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff8180a0a0)
Location: drivers/input/serio/libps2.c:25
Inline: False
Direct callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_sendbyte
```
**Symbols:**

```
ffffffff8180a0a0-ffffffff8180a2bb: ps2_do_sendbyte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ps2_do_sendbyte(struct ps2dev *ps2dev, u8 byte, unsigned int timeout, unsigned int max_attempts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff817d1840)
Location: drivers/input/serio/libps2.c:25
Inline: False
Direct callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_sendbyte
```
**Symbols:**

```
ffffffff817d1840-ffffffff817d1a55: ps2_do_sendbyte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ps2_do_sendbyte(struct ps2dev *ps2dev, u8 byte, unsigned int timeout, unsigned int max_attempts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff81849220)
Location: drivers/input/serio/libps2.c:25
Inline: False
Direct callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_sendbyte
```
**Symbols:**

```
ffffffff81849220-ffffffff8184943b: ps2_do_sendbyte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ps2_do_sendbyte(struct ps2dev *ps2dev, u8 byte, unsigned int timeout, unsigned int max_attempts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff818640e0)
Location: drivers/input/serio/libps2.c:25
Inline: False
Direct callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_sendbyte
```
**Symbols:**

```
ffffffff818640e0-ffffffff818642e9: ps2_do_sendbyte (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
