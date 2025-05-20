# Function: <code>ps2_drain</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ps2_drain(struct ps2dev *ps2dev, int maxbytes, int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff81666120)
Location: drivers/input/serio/libps2.c:80
Inline: False
```
**Symbols:**

```
ffffffff81666120-ffffffff8166625d: ps2_drain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ps2_drain(struct ps2dev *ps2dev, int maxbytes, int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff816c63a0)
Location: drivers/input/serio/libps2.c:78
Inline: False
```
**Symbols:**

```
ffffffff816c63a0-ffffffff816c64fe: ps2_drain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ps2_drain(struct ps2dev *ps2dev, int maxbytes, int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff816f43c0)
Location: drivers/input/serio/libps2.c:78
Inline: False
```
**Symbols:**

```
ffffffff816f43c0-ffffffff816f4512: ps2_drain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ps2_drain(struct ps2dev *ps2dev, int maxbytes, int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff81709f30)
Location: drivers/input/serio/libps2.c:78
Inline: False
```
**Symbols:**

```
ffffffff81709f30-ffffffff8170a081: ps2_drain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ps2_drain(struct ps2dev *ps2dev, int maxbytes, int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff8177b260)
Location: drivers/input/serio/libps2.c:78
Inline: False
```
**Symbols:**

```
ffffffff8177b260-ffffffff8177b3b1: ps2_drain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ps2_drain(struct ps2dev *ps2dev, size_t maxbytes, unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff817bc090)
Location: drivers/input/serio/libps2.c:126
Inline: False
```
**Symbols:**

```
ffffffff817bc090-ffffffff817bc1dc: ps2_drain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ps2_drain(struct ps2dev *ps2dev, size_t maxbytes, unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff817e34f0)
Location: drivers/input/serio/libps2.c:126
Inline: False
```
**Symbols:**

```
ffffffff817e34f0-ffffffff817e363c: ps2_drain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void ps2_drain(struct ps2dev *ps2dev, size_t maxbytes, unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/libps2.c (0)
Location: drivers/input/serio/libps2.c:122
Inline: False
```
**Symbols:**

```
ffffffff81824740-ffffffff81824759: ps2_drain.cold (STB_LOCAL)
ffffffff81823e80-ffffffff81823fc1: ps2_drain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ps2_drain(struct ps2dev *ps2dev, size_t maxbytes, unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff81855340)
Location: drivers/input/serio/libps2.c:122
Inline: False
```
**Symbols:**

```
ffffffff81855340-ffffffff81855485: ps2_drain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ps2_drain(struct ps2dev *ps2dev, size_t maxbytes, unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff81927860)
Location: drivers/input/serio/libps2.c:122
Inline: False
```
**Symbols:**

```
ffffffff81927860-ffffffff819279a5: ps2_drain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ps2_drain(struct ps2dev *ps2dev, size_t maxbytes, unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff8192ed70)
Location: drivers/input/serio/libps2.c:122
Inline: False
```
**Symbols:**

```
ffffffff8192ed70-ffffffff8192eeb5: ps2_drain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ps2_drain(struct ps2dev *ps2dev, size_t maxbytes, unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff81912130)
Location: drivers/input/serio/libps2.c:122
Inline: False
```
**Symbols:**

```
ffffffff81912130-ffffffff81912275: ps2_drain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ps2_drain(struct ps2dev *ps2dev, size_t maxbytes, unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff819b40e0)
Location: drivers/input/serio/libps2.c:122
Inline: False
```
**Symbols:**

```
ffffffff819b40e0-ffffffff819b4225: ps2_drain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ps2_drain(struct ps2dev *ps2dev, size_t maxbytes, unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff81b13bc0)
Location: drivers/input/serio/libps2.c:122
Inline: False
```
**Symbols:**

```
ffffffff81b13bc0-ffffffff81b13d42: ps2_drain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ps2_drain(struct ps2dev *ps2dev, size_t maxbytes, unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff81ca4b60)
Location: drivers/input/serio/libps2.c:123
Inline: False
```
**Symbols:**

```
ffffffff81ca4b60-ffffffff81ca4ce2: ps2_drain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ps2_drain(struct ps2dev *ps2dev, size_t maxbytes, unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff81d0c290)
Location: drivers/input/serio/libps2.c:156
Inline: False
```
**Symbols:**

```
ffffffff81d0c290-ffffffff81d0c412: ps2_drain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ps2_drain(struct ps2dev *ps2dev, size_t maxbytes, unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff81dc1f20)
Location: drivers/input/serio/libps2.c:156
Inline: False
```
**Symbols:**

```
ffffffff81dc1f20-ffffffff81dc20a2: ps2_drain (STB_GLOBAL)
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
void ps2_drain(struct ps2dev *ps2dev, size_t maxbytes, unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffff800010a940f0)
Location: drivers/input/serio/libps2.c:122
Inline: False
```
**Symbols:**

```
ffff800010a940f0-ffff800010a942b0: ps2_drain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ps2_drain(struct ps2dev *ps2dev, size_t maxbytes, unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (c0b76c40)
Location: drivers/input/serio/libps2.c:122
Inline: False
```
**Symbols:**

```
c0b76c40-c0b76dd4: ps2_drain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ps2_drain(struct ps2dev *ps2dev, size_t maxbytes, unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (c000000000b72db0)
Location: drivers/input/serio/libps2.c:122
Inline: False
```
**Symbols:**

```
c000000000b72db0-c000000000b72fd4: ps2_drain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ps2_drain(struct ps2dev *ps2dev, size_t maxbytes, unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffe0006a6278)
Location: drivers/input/serio/libps2.c:122
Inline: False
```
**Symbols:**

```
ffffffe0006a6278-ffffffe0006a63bc: ps2_drain (STB_GLOBAL)
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
void ps2_drain(struct ps2dev *ps2dev, size_t maxbytes, unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff8180a350)
Location: drivers/input/serio/libps2.c:122
Inline: False
```
**Symbols:**

```
ffffffff8180a350-ffffffff8180a495: ps2_drain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ps2_drain(struct ps2dev *ps2dev, size_t maxbytes, unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff817d1af0)
Location: drivers/input/serio/libps2.c:122
Inline: False
```
**Symbols:**

```
ffffffff817d1af0-ffffffff817d1c2f: ps2_drain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ps2_drain(struct ps2dev *ps2dev, size_t maxbytes, unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff818494d0)
Location: drivers/input/serio/libps2.c:122
Inline: False
```
**Symbols:**

```
ffffffff818494d0-ffffffff81849615: ps2_drain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ps2_drain(struct ps2dev *ps2dev, size_t maxbytes, unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/libps2.c (ffffffff818643e0)
Location: drivers/input/serio/libps2.c:122
Inline: False
```
**Symbols:**

```
ffffffff818643e0-ffffffff81864514: ps2_drain (STB_GLOBAL)
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
<code>int maxbytes</code> ➡️ <code>size_t maxbytes</code>
</li>
<li>
<b>Param type changed. </b>
<code>int timeout</code> ➡️ <code>unsigned int timeout</code>
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
