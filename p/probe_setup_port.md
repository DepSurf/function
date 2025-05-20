# Function: <code>probe_setup_port</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff8158890d)
Location: drivers/tty/serial/8250/8250_fintek.c:259
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
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
In drivers/tty/serial/8250/8250_fintek.c (ffffffff8159cd46)
Location: drivers/tty/serial/8250/8250_fintek.c:290
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
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
In drivers/tty/serial/8250/8250_fintek.c (ffffffff81602236)
Location: drivers/tty/serial/8250/8250_fintek.c:384
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
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
In drivers/tty/serial/8250/8250_fintek.c (ffffffff8163b4e5)
Location: drivers/tty/serial/8250/8250_fintek.c:384
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
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
In drivers/tty/serial/8250/8250_fintek.c (ffffffff81659715)
Location: drivers/tty/serial/8250/8250_fintek.c:384
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
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
In drivers/tty/serial/8250/8250_fintek.c (ffffffff8168ebb5)
Location: drivers/tty/serial/8250/8250_fintek.c:385
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
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
In drivers/tty/serial/8250/8250_fintek.c (ffffffff816b13e5)
Location: drivers/tty/serial/8250/8250_fintek.c:385
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int probe_setup_port(struct fintek_8250 *pdata, struct uart_8250_port *uart);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff81764640)
Location: drivers/tty/serial/8250/8250_fintek.c:393
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
```
**Symbols:**

```
ffffffff81764640-ffffffff81764a9a: probe_setup_port (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int probe_setup_port(struct fintek_8250 *pdata, struct uart_8250_port *uart);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff8177f560)
Location: drivers/tty/serial/8250/8250_fintek.c:393
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
```
**Symbols:**

```
ffffffff8177f560-ffffffff8177f9ba: probe_setup_port (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int probe_setup_port(struct fintek_8250 *pdata, struct uart_8250_port *uart);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff81762ea0)
Location: drivers/tty/serial/8250/8250_fintek.c:393
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
```
**Symbols:**

```
ffffffff81762ea0-ffffffff81763300: probe_setup_port (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int probe_setup_port(struct fintek_8250 *pdata, struct uart_8250_port *uart);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff817e70b0)
Location: drivers/tty/serial/8250/8250_fintek.c:374
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
```
**Symbols:**

```
ffffffff817e70b0-ffffffff817e759a: probe_setup_port (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int probe_setup_port(struct fintek_8250 *pdata, struct uart_8250_port *uart);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff81926a50)
Location: drivers/tty/serial/8250/8250_fintek.c:374
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
```
**Symbols:**

```
ffffffff81926a50-ffffffff81926f13: probe_setup_port (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int probe_setup_port(struct fintek_8250 *pdata, struct uart_8250_port *uart);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff81a83880)
Location: drivers/tty/serial/8250/8250_fintek.c:360
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
```
**Symbols:**

```
ffffffff81a83880-ffffffff81a83d43: probe_setup_port (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int probe_setup_port(struct fintek_8250 *pdata, struct uart_8250_port *uart);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff81aceee0)
Location: drivers/tty/serial/8250/8250_fintek.c:360
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
```
**Symbols:**

```
ffffffff81aceee0-ffffffff81acf3ac: probe_setup_port (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int probe_setup_port(struct fintek_8250 *pdata, struct uart_8250_port *uart);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff81b21fa0)
Location: drivers/tty/serial/8250/8250_fintek.c:360
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
```
**Symbols:**

```
ffffffff81b21fa0-ffffffff81b2246c: probe_setup_port (STB_LOCAL)
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
int probe_setup_port(struct fintek_8250 *pdata, struct uart_8250_port *uart);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_fintek.c (ffff80001088c9e0)
Location: drivers/tty/serial/8250/8250_fintek.c:385
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
```
**Symbols:**

```
ffff80001088c9e0-ffff80001088ce34: probe_setup_port (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int probe_setup_port(struct fintek_8250 *pdata, struct uart_8250_port *uart);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_fintek.c (ffffffe000555eb2)
Location: drivers/tty/serial/8250/8250_fintek.c:385
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
```
**Symbols:**

```
ffffffe000555eb2-ffffffe000556344: probe_setup_port (STB_LOCAL)
```
</details>
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
In drivers/tty/serial/8250/8250_fintek.c (ffffffff81676e55)
Location: drivers/tty/serial/8250/8250_fintek.c:385
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
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
In drivers/tty/serial/8250/8250_fintek.c (ffffffff81655f35)
Location: drivers/tty/serial/8250/8250_fintek.c:385
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
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
In drivers/tty/serial/8250/8250_fintek.c (ffffffff816a5225)
Location: drivers/tty/serial/8250/8250_fintek.c:385
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
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
In drivers/tty/serial/8250/8250_fintek.c (ffffffff816bf685)
Location: drivers/tty/serial/8250/8250_fintek.c:385
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
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
<b>Arch</b>
<ul>
</ul>
