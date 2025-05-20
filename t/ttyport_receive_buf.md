# Function: <code>ttyport_receive_buf</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ttyport_receive_buf(struct tty_port *port, const unsigned char *cp, const unsigned char *fp, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff81609f30)
Location: drivers/tty/serdev/serdev-ttyport.c:25
Inline: False
```
**Symbols:**

```
ffffffff81609f30-ffffffff8160a008: ttyport_receive_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ttyport_receive_buf(struct tty_port *port, const unsigned char *cp, const unsigned char *fp, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff81643750)
Location: drivers/tty/serdev/serdev-ttyport.c:25
Inline: False
```
**Symbols:**

```
ffffffff81643750-ffffffff81643826: ttyport_receive_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ttyport_receive_buf(struct tty_port *port, const unsigned char *cp, const unsigned char *fp, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff81661a80)
Location: drivers/tty/serdev/serdev-ttyport.c:25
Inline: False
```
**Symbols:**

```
ffffffff81661a80-ffffffff81661b56: ttyport_receive_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ttyport_receive_buf(struct tty_port *port, const unsigned char *cp, const unsigned char *fp, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff81697630)
Location: drivers/tty/serdev/serdev-ttyport.c:25
Inline: False
```
**Symbols:**

```
ffffffff81697630-ffffffff81697705: ttyport_receive_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ttyport_receive_buf(struct tty_port *port, const unsigned char *cp, const unsigned char *fp, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff816ba1c0)
Location: drivers/tty/serdev/serdev-ttyport.c:25
Inline: False
```
**Symbols:**

```
ffffffff816ba1c0-ffffffff816ba295: ttyport_receive_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ttyport_receive_buf(struct tty_port *port, const unsigned char *cp, const unsigned char *fp, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff8176e990)
Location: drivers/tty/serdev/serdev-ttyport.c:25
Inline: False
```
**Symbols:**

```
ffffffff8176e990-ffffffff8176ea74: ttyport_receive_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ttyport_receive_buf(struct tty_port *port, const unsigned char *cp, const unsigned char *fp, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff81789290)
Location: drivers/tty/serdev/serdev-ttyport.c:25
Inline: False
```
**Symbols:**

```
ffffffff81789290-ffffffff81789374: ttyport_receive_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ttyport_receive_buf(struct tty_port *port, const unsigned char *cp, const unsigned char *fp, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff8176ca10)
Location: drivers/tty/serdev/serdev-ttyport.c:25
Inline: False
```
**Symbols:**

```
ffffffff8176ca10-ffffffff8176caf4: ttyport_receive_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ttyport_receive_buf(struct tty_port *port, const unsigned char *cp, const unsigned char *fp, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serdev/serdev-ttyport.c (0)
Location: drivers/tty/serdev/serdev-ttyport.c:25
Inline: False
```
**Symbols:**

```
ffffffff817f2160-ffffffff817f223d: ttyport_receive_buf (STB_LOCAL)
ffffffff81cfa94b-ffffffff81cfa960: ttyport_receive_buf.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ttyport_receive_buf(struct tty_port *port, const unsigned char *cp, const unsigned char *fp, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serdev/serdev-ttyport.c (0)
Location: drivers/tty/serdev/serdev-ttyport.c:25
Inline: False
```
**Symbols:**

```
ffffffff81932af0-ffffffff81932c1b: ttyport_receive_buf (STB_LOCAL)
ffffffff81ec2bc8-ffffffff81ec2c02: ttyport_receive_buf.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ttyport_receive_buf(struct tty_port *port, const unsigned char *cp, const unsigned char *fp, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serdev/serdev-ttyport.c (0)
Location: drivers/tty/serdev/serdev-ttyport.c:25
Inline: False
```
**Symbols:**

```
ffffffff81a916e0-ffffffff81a9180b: ttyport_receive_buf (STB_LOCAL)
ffffffff820964a0-ffffffff820964da: ttyport_receive_buf.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ttyport_receive_buf(struct tty_port *port, const unsigned char *cp, const unsigned char *fp, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serdev/serdev-ttyport.c (0)
Location: drivers/tty/serdev/serdev-ttyport.c:25
Inline: False
```
**Symbols:**

```
ffffffff81adcf50-ffffffff81add074: ttyport_receive_buf (STB_LOCAL)
ffffffff821173e8-ffffffff82117422: ttyport_receive_buf.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
size_t ttyport_receive_buf(struct tty_port *port, const u8 *cp, const u8 *fp, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serdev/serdev-ttyport.c (0)
Location: drivers/tty/serdev/serdev-ttyport.c:25
Inline: False
```
**Symbols:**

```
ffffffff81b30310-ffffffff81b30472: ttyport_receive_buf (STB_LOCAL)
ffffffff821f514d-ffffffff821f5197: ttyport_receive_buf.cold (STB_LOCAL)
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
int ttyport_receive_buf(struct tty_port *port, const unsigned char *cp, const unsigned char *fp, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/serdev-ttyport.c (ffff8000108aa1b8)
Location: drivers/tty/serdev/serdev-ttyport.c:25
Inline: False
```
**Symbols:**

```
ffff8000108aa1b8-ffff8000108aa2c0: ttyport_receive_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ttyport_receive_buf(struct tty_port *port, const unsigned char *cp, const unsigned char *fp, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/serdev-ttyport.c (c09a66b4)
Location: drivers/tty/serdev/serdev-ttyport.c:25
Inline: False
```
**Symbols:**

```
c09a66b4-c09a67b8: ttyport_receive_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ttyport_receive_buf(struct tty_port *port, const unsigned char *cp, const unsigned char *fp, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/serdev-ttyport.c (c000000000941870)
Location: drivers/tty/serdev/serdev-ttyport.c:25
Inline: False
```
**Symbols:**

```
c000000000941870-c000000000941a0c: ttyport_receive_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ttyport_receive_buf(struct tty_port *port, const unsigned char *cp, const unsigned char *fp, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/serdev-ttyport.c (ffffffe00055f4fc)
Location: drivers/tty/serdev/serdev-ttyport.c:25
Inline: False
```
**Symbols:**

```
ffffffe00055f4fc-ffffffe00055f5c4: ttyport_receive_buf (STB_LOCAL)
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
int ttyport_receive_buf(struct tty_port *port, const unsigned char *cp, const unsigned char *fp, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff8167fc20)
Location: drivers/tty/serdev/serdev-ttyport.c:25
Inline: False
```
**Symbols:**

```
ffffffff8167fc20-ffffffff8167fcf5: ttyport_receive_buf (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ttyport_receive_buf(struct tty_port *port, const unsigned char *cp, const unsigned char *fp, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff816ae000)
Location: drivers/tty/serdev/serdev-ttyport.c:25
Inline: False
```
**Symbols:**

```
ffffffff816ae000-ffffffff816ae0d5: ttyport_receive_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ttyport_receive_buf(struct tty_port *port, const unsigned char *cp, const unsigned char *fp, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff816c8460)
Location: drivers/tty/serdev/serdev-ttyport.c:25
Inline: False
```
**Symbols:**

```
ffffffff816c8460-ffffffff816c8535: ttyport_receive_buf (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const unsigned char *cp</code> ➡️ <code>const u8 *cp</code>
</li>
<li>
<b>Param type changed. </b>
<code>const unsigned char *fp</code> ➡️ <code>const u8 *fp</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>size_t</code>
</li>
</ul>
</details>
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
