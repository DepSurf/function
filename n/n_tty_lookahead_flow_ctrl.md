# Function: <code>n_tty_lookahead_flow_ctrl</code>

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
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void n_tty_lookahead_flow_ctrl(struct tty_struct *tty, const unsigned char *cp, const unsigned char *fp, unsigned int count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff81a4f410)
Location: drivers/tty/n_tty.c:1484
Inline: True
```
**Symbols:**

```
ffffffff81a4f410-ffffffff81a4f4c0: n_tty_lookahead_flow_ctrl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void n_tty_lookahead_flow_ctrl(struct tty_struct *tty, const unsigned char *cp, const unsigned char *fp, unsigned int count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff81a99620)
Location: drivers/tty/n_tty.c:1483
Inline: True
```
**Symbols:**

```
ffffffff81a99620-ffffffff81a996d0: n_tty_lookahead_flow_ctrl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void n_tty_lookahead_flow_ctrl(struct tty_struct *tty, const u8 *cp, const u8 *fp, size_t count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff81aec260)
Location: drivers/tty/n_tty.c:1501
Inline: True
```
**Symbols:**

```
ffffffff81aec260-ffffffff81aec322: n_tty_lookahead_flow_ctrl (STB_LOCAL)
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
<code>const unsigned char *cp</code> ➡️ <code>const u8 *cp</code>
</li>
<li>
<b>Param type changed. </b>
<code>const unsigned char *fp</code> ➡️ <code>const u8 *fp</code>
</li>
<li>
<b>Param type changed. </b>
<code>unsigned int count</code> ➡️ <code>size_t count</code>
</li>
</ul>
</details>
</li>
</ul>
