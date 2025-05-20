# Function: <code>fintek_8250_enter_key</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff8155c14b)
Location: drivers/tty/serial/8250/8250_fintek.c:52
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff81588915)
Location: drivers/tty/serial/8250/8250_fintek.c:103
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
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
In drivers/tty/serial/8250/8250_fintek.c (ffffffff8159cd80)
Location: drivers/tty/serial/8250/8250_fintek.c:116
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fintek_8250_enter_key(u16 base_port, u8 key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff81601ea0)
Location: drivers/tty/serial/8250/8250_fintek.c:122
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
```
**Symbols:**

```
ffffffff81601ea0-ffffffff81601ef3: fintek_8250_enter_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int fintek_8250_enter_key(u16 base_port, u8 key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff8163b160)
Location: drivers/tty/serial/8250/8250_fintek.c:122
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
```
**Symbols:**

```
ffffffff8163b160-ffffffff8163b1b3: fintek_8250_enter_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int fintek_8250_enter_key(u16 base_port, u8 key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff81659390)
Location: drivers/tty/serial/8250/8250_fintek.c:122
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
```
**Symbols:**

```
ffffffff81659390-ffffffff816593e3: fintek_8250_enter_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int fintek_8250_enter_key(u16 base_port, u8 key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff8168e850)
Location: drivers/tty/serial/8250/8250_fintek.c:122
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
```
**Symbols:**

```
ffffffff8168e850-ffffffff8168e8a3: fintek_8250_enter_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fintek_8250_enter_key(u16 base_port, u8 key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff816b1080)
Location: drivers/tty/serial/8250/8250_fintek.c:122
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
```
**Symbols:**

```
ffffffff816b1080-ffffffff816b10d3: fintek_8250_enter_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff817646ad)
Location: drivers/tty/serial/8250/8250_fintek.c:123
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff8177f5cd)
Location: drivers/tty/serial/8250/8250_fintek.c:123
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff81762f0d)
Location: drivers/tty/serial/8250/8250_fintek.c:123
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff817e7131)
Location: drivers/tty/serial/8250/8250_fintek.c:123
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff81926ac7)
Location: drivers/tty/serial/8250/8250_fintek.c:123
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff81a838f7)
Location: drivers/tty/serial/8250/8250_fintek.c:123
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
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
In drivers/tty/serial/8250/8250_fintek.c (ffffffff81acef57)
Location: drivers/tty/serial/8250/8250_fintek.c:123
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
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
In drivers/tty/serial/8250/8250_fintek.c (ffffffff81b22017)
Location: drivers/tty/serial/8250/8250_fintek.c:123
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
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
int fintek_8250_enter_key(u16 base_port, u8 key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_fintek.c (ffff80001088c5a0)
Location: drivers/tty/serial/8250/8250_fintek.c:122
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
```
**Symbols:**

```
ffff80001088c5a0-ffff80001088c620: fintek_8250_enter_key (STB_LOCAL)
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
int fintek_8250_enter_key(u16 base_port, u8 key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_fintek.c (ffffffe000555e34)
Location: drivers/tty/serial/8250/8250_fintek.c:122
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
```
**Symbols:**

```
ffffffe000555e34-ffffffe000555eb2: fintek_8250_enter_key (STB_LOCAL)
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
int fintek_8250_enter_key(u16 base_port, u8 key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff81676af0)
Location: drivers/tty/serial/8250/8250_fintek.c:122
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
```
**Symbols:**

```
ffffffff81676af0-ffffffff81676b43: fintek_8250_enter_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fintek_8250_enter_key(u16 base_port, u8 key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff81655bd0)
Location: drivers/tty/serial/8250/8250_fintek.c:122
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
```
**Symbols:**

```
ffffffff81655bd0-ffffffff81655c23: fintek_8250_enter_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fintek_8250_enter_key(u16 base_port, u8 key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff816a4ec0)
Location: drivers/tty/serial/8250/8250_fintek.c:122
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
```
**Symbols:**

```
ffffffff816a4ec0-ffffffff816a4f13: fintek_8250_enter_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fintek_8250_enter_key(u16 base_port, u8 key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff816bf320)
Location: drivers/tty/serial/8250/8250_fintek.c:122
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
```
**Symbols:**

```
ffffffff816bf320-ffffffff816bf373: fintek_8250_enter_key (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
