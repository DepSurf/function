# Function: <code>tty_port_default_lookahead_buf</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tty_port_default_lookahead_buf(struct tty_port *port, const unsigned char *p, const unsigned char *f, unsigned int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff81a55390)
Location: drivers/tty/tty_port.c:46
Inline: False
```
**Symbols:**

```
ffffffff81a55390-ffffffff81a55411: tty_port_default_lookahead_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tty_port_default_lookahead_buf(struct tty_port *port, const unsigned char *p, const unsigned char *f, unsigned int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff81a9f970)
Location: drivers/tty/tty_port.c:46
Inline: False
```
**Symbols:**

```
ffffffff81a9f970-ffffffff81a9f9f1: tty_port_default_lookahead_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tty_port_default_lookahead_buf(struct tty_port *port, const u8 *p, const u8 *f, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff81af23b0)
Location: drivers/tty/tty_port.c:44
Inline: False
```
**Symbols:**

```
ffffffff81af23b0-ffffffff81af2431: tty_port_default_lookahead_buf (STB_LOCAL)
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
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const unsigned char *p</code> ➡️ <code>const u8 *p</code>
</li>
<li>
<b>Param type changed. </b>
<code>const unsigned char *f</code> ➡️ <code>const u8 *f</code>
</li>
<li>
<b>Param type changed. </b>
<code>unsigned int count</code> ➡️ <code>size_t count</code>
</li>
</ul>
</details>
</li>
</ul>
