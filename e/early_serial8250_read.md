# Function: <code>early_serial8250_read</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int early_serial8250_read(struct console *console, char *s, unsigned int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_early.c (ffffffff81767960)
Location: drivers/tty/serial/8250/8250_early.c:113
Inline: False
```
**Symbols:**

```
ffffffff81767960-ffffffff817679d6: early_serial8250_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int early_serial8250_read(struct console *console, char *s, unsigned int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_early.c (ffffffff817826c0)
Location: drivers/tty/serial/8250/8250_early.c:113
Inline: False
```
**Symbols:**

```
ffffffff817826c0-ffffffff81782736: early_serial8250_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int early_serial8250_read(struct console *console, char *s, unsigned int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_early.c (ffffffff81765fc0)
Location: drivers/tty/serial/8250/8250_early.c:113
Inline: False
```
**Symbols:**

```
ffffffff81765fc0-ffffffff81766036: early_serial8250_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int early_serial8250_read(struct console *console, char *s, unsigned int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_early.c (ffffffff817ea930)
Location: drivers/tty/serial/8250/8250_early.c:113
Inline: False
```
**Symbols:**

```
ffffffff817ea930-ffffffff817ea9a6: early_serial8250_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int early_serial8250_read(struct console *console, char *s, unsigned int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_early.c (ffffffff8192a6e0)
Location: drivers/tty/serial/8250/8250_early.c:113
Inline: False
```
**Symbols:**

```
ffffffff8192a6e0-ffffffff8192a763: early_serial8250_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int early_serial8250_read(struct console *console, char *s, unsigned int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_early.c (ffffffff81a87b20)
Location: drivers/tty/serial/8250/8250_early.c:111
Inline: False
```
**Symbols:**

```
ffffffff81a87b20-ffffffff81a87ba3: early_serial8250_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int early_serial8250_read(struct console *console, char *s, unsigned int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_early.c (ffffffff81ad2ee0)
Location: drivers/tty/serial/8250/8250_early.c:104
Inline: False
```
**Symbols:**

```
ffffffff81ad2ee0-ffffffff81ad2f63: early_serial8250_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int early_serial8250_read(struct console *console, char *s, unsigned int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_early.c (ffffffff81b22920)
Location: drivers/tty/serial/8250/8250_early.c:103
Inline: False
```
**Symbols:**

```
ffffffff81b22920-ffffffff81b229a3: early_serial8250_read (STB_LOCAL)
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
