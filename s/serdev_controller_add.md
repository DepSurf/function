# Function: <code>serdev_controller_add</code>

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
int serdev_controller_add(struct serdev_controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff81609900)
Location: drivers/tty/serdev/core.c:495
Inline: False
Direct callers:
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register
```
**Symbols:**

```
ffffffff81609900-ffffffff81609a3c: serdev_controller_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int serdev_controller_add(struct serdev_controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff81643120)
Location: drivers/tty/serdev/core.c:538
Inline: False
Direct callers:
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register
```
**Symbols:**

```
ffffffff81643120-ffffffff81643250: serdev_controller_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int serdev_controller_add(struct serdev_controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff81661410)
Location: drivers/tty/serdev/core.c:630
Inline: False
Direct callers:
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register
```
**Symbols:**

```
ffffffff81661410-ffffffff81661558: serdev_controller_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int serdev_controller_add(struct serdev_controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serdev/core.c (0)
Location: drivers/tty/serdev/core.c:630
Inline: False
Direct callers:
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register
```
**Symbols:**

```
ffffffff81697436-ffffffff8169744f: serdev_controller_add.cold (STB_LOCAL)
ffffffff81696e40-ffffffff81696f82: serdev_controller_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int serdev_controller_add(struct serdev_controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff816b99d0)
Location: drivers/tty/serdev/core.c:640
Inline: False
Direct callers:
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register
```
**Symbols:**

```
ffffffff816b99d0-ffffffff816b9b28: serdev_controller_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int serdev_controller_add(struct serdev_controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serdev/core.c (0)
Location: drivers/tty/serdev/core.c:739
Inline: False
Direct callers:
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register
```
**Symbols:**

```
ffffffff8176e441-ffffffff8176e455: serdev_controller_add.cold (STB_LOCAL)
ffffffff8176dd80-ffffffff8176deb0: serdev_controller_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int serdev_controller_add(struct serdev_controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serdev/core.c (0)
Location: drivers/tty/serdev/core.c:739
Inline: False
Direct callers:
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register
```
**Symbols:**

```
ffffffff81c0843f-ffffffff81c08453: serdev_controller_add.cold (STB_LOCAL)
ffffffff81788740-ffffffff81788870: serdev_controller_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int serdev_controller_add(struct serdev_controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serdev/core.c (0)
Location: drivers/tty/serdev/core.c:739
Inline: False
Direct callers:
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register
```
**Symbols:**

```
ffffffff81bfa004-ffffffff81bfa018: serdev_controller_add.cold (STB_LOCAL)
ffffffff8176c090-ffffffff8176c1c0: serdev_controller_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int serdev_controller_add(struct serdev_controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serdev/core.c (0)
Location: drivers/tty/serdev/core.c:759
Inline: False
Direct callers:
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register
```
**Symbols:**

```
ffffffff81cfa89f-ffffffff81cfa8c8: serdev_controller_add.cold (STB_LOCAL)
ffffffff817f1850-ffffffff817f198c: serdev_controller_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int serdev_controller_add(struct serdev_controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serdev/core.c (0)
Location: drivers/tty/serdev/core.c:770
Inline: False
Direct callers:
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register
```
**Symbols:**

```
ffffffff81ec2b0d-ffffffff81ec2b4a: serdev_controller_add.cold (STB_LOCAL)
ffffffff81931f30-ffffffff819320be: serdev_controller_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int serdev_controller_add(struct serdev_controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serdev/core.c (0)
Location: drivers/tty/serdev/core.c:770
Inline: False
Direct callers:
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register
```
**Symbols:**

```
ffffffff82096462-ffffffff8209648b: serdev_controller_add.cold (STB_LOCAL)
ffffffff81a90990-ffffffff81a90b27: serdev_controller_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int serdev_controller_add(struct serdev_controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serdev/core.c (0)
Location: drivers/tty/serdev/core.c:781
Inline: False
Direct callers:
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register
```
**Symbols:**

```
ffffffff821173aa-ffffffff821173d3: serdev_controller_add.cold (STB_LOCAL)
ffffffff81adc1a0-ffffffff81adc337: serdev_controller_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int serdev_controller_add(struct serdev_controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serdev/core.c (0)
Location: drivers/tty/serdev/core.c:774
Inline: False
Direct callers:
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register
```
**Symbols:**

```
ffffffff821f510f-ffffffff821f5138: serdev_controller_add.cold (STB_LOCAL)
ffffffff81b2f480-ffffffff81b2f61d: serdev_controller_add (STB_GLOBAL)
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
int serdev_controller_add(struct serdev_controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffff8000108a99c0)
Location: drivers/tty/serdev/core.c:640
Inline: False
Direct callers:
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register
```
**Symbols:**

```
ffff8000108a99c0-ffff8000108a9c78: serdev_controller_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int serdev_controller_add(struct serdev_controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (c09a6048)
Location: drivers/tty/serdev/core.c:640
Inline: False
Direct callers:
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register
```
**Symbols:**

```
c09a6048-c09a621c: serdev_controller_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int serdev_controller_add(struct serdev_controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (c000000000941390)
Location: drivers/tty/serdev/core.c:640
Inline: False
Direct callers:
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register
```
**Symbols:**

```
c000000000941390-c000000000941604: serdev_controller_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int serdev_controller_add(struct serdev_controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffe00055f1f8)
Location: drivers/tty/serdev/core.c:640
Inline: False
Direct callers:
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register
```
**Symbols:**

```
ffffffe00055f1f8-ffffffe00055f3a0: serdev_controller_add (STB_GLOBAL)
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
int serdev_controller_add(struct serdev_controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff8167f430)
Location: drivers/tty/serdev/core.c:640
Inline: False
Direct callers:
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register
```
**Symbols:**

```
ffffffff8167f430-ffffffff8167f588: serdev_controller_add (STB_GLOBAL)
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
int serdev_controller_add(struct serdev_controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff816ad810)
Location: drivers/tty/serdev/core.c:640
Inline: False
Direct callers:
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register
```
**Symbols:**

```
ffffffff816ad810-ffffffff816ad968: serdev_controller_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int serdev_controller_add(struct serdev_controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff816c7c70)
Location: drivers/tty/serdev/core.c:640
Inline: False
Direct callers:
  - drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register
```
**Symbols:**

```
ffffffff816c7c70-ffffffff816c7dc8: serdev_controller_add (STB_GLOBAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
