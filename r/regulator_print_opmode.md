# Function: <code>regulator_print_opmode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
ssize_t regulator_print_opmode(char *buf, int mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff814db790)
Location: drivers/regulator/core.c:382
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_suspend_disk_mode_show
  - drivers/regulator/core.c:regulator_suspend_mem_mode_show
  - drivers/regulator/core.c:regulator_suspend_standby_mode_show
  - drivers/regulator/core.c:regulator_opmode_show
```
**Symbols:**

```
ffffffff814db790-ffffffff814db81f: regulator_print_opmode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t regulator_print_opmode(char *buf, int mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8152ace0)
Location: drivers/regulator/core.c:358
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_suspend_standby_mode_show
  - drivers/regulator/core.c:regulator_suspend_disk_mode_show
  - drivers/regulator/core.c:regulator_suspend_mem_mode_show
  - drivers/regulator/core.c:regulator_opmode_show
```
**Symbols:**

```
ffffffff8152ace0-ffffffff8152ad6f: regulator_print_opmode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
ssize_t regulator_print_opmode(char *buf, int mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff815572e0)
Location: drivers/regulator/core.c:359
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_suspend_standby_mode_show
  - drivers/regulator/core.c:regulator_suspend_disk_mode_show
  - drivers/regulator/core.c:regulator_suspend_mem_mode_show
  - drivers/regulator/core.c:regulator_opmode_show
```
**Symbols:**

```
ffffffff815572e0-ffffffff8155736f: regulator_print_opmode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
ssize_t regulator_print_opmode(char *buf, int mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8156b9b0)
Location: drivers/regulator/core.c:359
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_suspend_standby_mode_show
  - drivers/regulator/core.c:regulator_suspend_disk_mode_show
  - drivers/regulator/core.c:regulator_suspend_mem_mode_show
  - drivers/regulator/core.c:regulator_opmode_show
```
**Symbols:**

```
ffffffff8156b9b0-ffffffff8156ba3f: regulator_print_opmode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
ssize_t regulator_print_opmode(char *buf, int mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff815cfbe0)
Location: drivers/regulator/core.c:359
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_suspend_standby_mode_show
  - drivers/regulator/core.c:regulator_suspend_disk_mode_show
  - drivers/regulator/core.c:regulator_suspend_mem_mode_show
  - drivers/regulator/core.c:regulator_opmode_show
```
**Symbols:**

```
ffffffff815cfbe0-ffffffff815cfc6f: regulator_print_opmode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
ssize_t regulator_print_opmode(char *buf, int mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff8160a100)
Location: drivers/regulator/core.c:429
Inline: True
Direct callers:
  - drivers/regulator/core.c:regulator_suspend_standby_mode_show
  - drivers/regulator/core.c:regulator_suspend_disk_mode_show
  - drivers/regulator/core.c:regulator_suspend_mem_mode_show
  - drivers/regulator/core.c:regulator_opmode_show
```
**Symbols:**

```
ffffffff8160a100-ffffffff8160a18f: regulator_print_opmode (STB_LOCAL)
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
In drivers/regulator/core.c (ffffffff816224e5)
Location: drivers/regulator/core.c:628
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_suspend_standby_mode_show
  - drivers/regulator/core.c:regulator_suspend_disk_mode_show
  - drivers/regulator/core.c:regulator_suspend_mem_mode_show
  - drivers/regulator/core.c:regulator_opmode_show
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
In drivers/regulator/core.c (ffffffff81654f45)
Location: drivers/regulator/core.c:610
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_suspend_standby_mode_show
  - drivers/regulator/core.c:regulator_suspend_disk_mode_show
  - drivers/regulator/core.c:regulator_suspend_mem_mode_show
  - drivers/regulator/core.c:regulator_opmode_show
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
In drivers/regulator/core.c (ffffffff81677475)
Location: drivers/regulator/core.c:616
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_suspend_standby_mode_show
  - drivers/regulator/core.c:regulator_suspend_disk_mode_show
  - drivers/regulator/core.c:regulator_suspend_mem_mode_show
  - drivers/regulator/core.c:regulator_opmode_show
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
In drivers/regulator/core.c (ffffffff81728735)
Location: drivers/regulator/core.c:619
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_suspend_standby_mode_show
  - drivers/regulator/core.c:regulator_suspend_disk_mode_show
  - drivers/regulator/core.c:regulator_suspend_mem_mode_show
  - drivers/regulator/core.c:regulator_opmode_show
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
In drivers/regulator/core.c (ffffffff8174529c)
Location: drivers/regulator/core.c:642
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_suspend_standby_mode_show
  - drivers/regulator/core.c:regulator_suspend_disk_mode_show
  - drivers/regulator/core.c:regulator_suspend_mem_mode_show
  - drivers/regulator/core.c:regulator_opmode_show
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
In drivers/regulator/core.c (ffffffff81728c8c)
Location: drivers/regulator/core.c:643
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_suspend_standby_mode_show
  - drivers/regulator/core.c:regulator_suspend_disk_mode_show
  - drivers/regulator/core.c:regulator_suspend_mem_mode_show
  - drivers/regulator/core.c:regulator_opmode_show
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
In drivers/regulator/core.c (ffffffff817a7eec)
Location: drivers/regulator/core.c:633
Inline: True
Inline callers:
  - drivers/regulator/core.c:suspend_standby_mode_show
  - drivers/regulator/core.c:suspend_disk_mode_show
  - drivers/regulator/core.c:suspend_mem_mode_show
  - drivers/regulator/core.c:opmode_show
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
In drivers/regulator/core.c (ffffffff818e27bc)
Location: drivers/regulator/core.c:634
Inline: True
Inline callers:
  - drivers/regulator/core.c:suspend_standby_mode_show
  - drivers/regulator/core.c:suspend_disk_mode_show
  - drivers/regulator/core.c:suspend_mem_mode_show
  - drivers/regulator/core.c:opmode_show
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
In drivers/regulator/core.c (ffffffff81a3784c)
Location: drivers/regulator/core.c:634
Inline: True
Inline callers:
  - drivers/regulator/core.c:suspend_standby_mode_show
  - drivers/regulator/core.c:suspend_disk_mode_show
  - drivers/regulator/core.c:suspend_mem_mode_show
  - drivers/regulator/core.c:opmode_show
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
In drivers/regulator/core.c (ffffffff81a8147c)
Location: drivers/regulator/core.c:700
Inline: True
Inline callers:
  - drivers/regulator/core.c:suspend_standby_mode_show
  - drivers/regulator/core.c:suspend_disk_mode_show
  - drivers/regulator/core.c:suspend_mem_mode_show
  - drivers/regulator/core.c:opmode_show
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
In drivers/regulator/core.c (ffffffff81ad3a2c)
Location: drivers/regulator/core.c:702
Inline: True
Inline callers:
  - drivers/regulator/core.c:suspend_standby_mode_show
  - drivers/regulator/core.c:suspend_disk_mode_show
  - drivers/regulator/core.c:suspend_mem_mode_show
  - drivers/regulator/core.c:opmode_show
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffff8000108404e4)
Location: drivers/regulator/core.c:616
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_suspend_standby_mode_show
  - drivers/regulator/core.c:regulator_suspend_disk_mode_show
  - drivers/regulator/core.c:regulator_suspend_mem_mode_show
  - drivers/regulator/core.c:regulator_opmode_show
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c0949c78)
Location: drivers/regulator/core.c:616
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_suspend_standby_mode_show
  - drivers/regulator/core.c:regulator_suspend_disk_mode_show
  - drivers/regulator/core.c:regulator_suspend_mem_mode_show
  - drivers/regulator/core.c:regulator_opmode_show
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (c0000000008da26c)
Location: drivers/regulator/core.c:616
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_suspend_standby_mode_show
  - drivers/regulator/core.c:regulator_suspend_disk_mode_show
  - drivers/regulator/core.c:regulator_suspend_mem_mode_show
  - drivers/regulator/core.c:regulator_opmode_show
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffe00052243a)
Location: drivers/regulator/core.c:616
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_suspend_standby_mode_show
  - drivers/regulator/core.c:regulator_suspend_disk_mode_show
  - drivers/regulator/core.c:regulator_suspend_mem_mode_show
  - drivers/regulator/core.c:regulator_opmode_show
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
In drivers/regulator/core.c (ffffffff8163d165)
Location: drivers/regulator/core.c:616
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_suspend_standby_mode_show
  - drivers/regulator/core.c:regulator_suspend_disk_mode_show
  - drivers/regulator/core.c:regulator_suspend_mem_mode_show
  - drivers/regulator/core.c:regulator_opmode_show
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
In drivers/regulator/core.c (ffffffff8161d355)
Location: drivers/regulator/core.c:616
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_suspend_standby_mode_show
  - drivers/regulator/core.c:regulator_suspend_disk_mode_show
  - drivers/regulator/core.c:regulator_suspend_mem_mode_show
  - drivers/regulator/core.c:regulator_opmode_show
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
In drivers/regulator/core.c (ffffffff8166b2b5)
Location: drivers/regulator/core.c:616
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_suspend_standby_mode_show
  - drivers/regulator/core.c:regulator_suspend_disk_mode_show
  - drivers/regulator/core.c:regulator_suspend_mem_mode_show
  - drivers/regulator/core.c:regulator_opmode_show
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
In drivers/regulator/core.c (ffffffff81685875)
Location: drivers/regulator/core.c:616
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_suspend_standby_mode_show
  - drivers/regulator/core.c:regulator_suspend_disk_mode_show
  - drivers/regulator/core.c:regulator_suspend_mem_mode_show
  - drivers/regulator/core.c:regulator_opmode_show
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
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
