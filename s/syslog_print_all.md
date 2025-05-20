# Function: <code>syslog_print_all</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int syslog_print_all(char *buf, int size, bool clear);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810d8cb0)
Location: kernel/printk/printk.c:1202
Inline: False
Direct callers:
  - kernel/printk/printk.c:do_syslog
  - kernel/printk/printk.c:do_syslog
```
**Symbols:**

```
ffffffff810d8cb0-ffffffff810d8fba: syslog_print_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int syslog_print_all(char *buf, int size, bool clear);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810dde10)
Location: kernel/printk/printk.c:1339
Inline: False
Direct callers:
  - kernel/printk/printk.c:do_syslog
  - kernel/printk/printk.c:do_syslog
```
**Symbols:**

```
ffffffff810dde10-ffffffff810de12d: syslog_print_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int syslog_print_all(char *buf, int size, bool clear);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810e4420)
Location: kernel/printk/printk.c:1298
Inline: False
Direct callers:
  - kernel/printk/printk.c:do_syslog
  - kernel/printk/printk.c:do_syslog
```
**Symbols:**

```
ffffffff810e4420-ffffffff810e46bc: syslog_print_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int syslog_print_all(char *buf, int size, bool clear);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810e3150)
Location: kernel/printk/printk.c:1348
Inline: False
```
**Symbols:**

```
ffffffff810e3150-ffffffff810e340f: syslog_print_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int syslog_print_all(char *buf, int size, bool clear);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810eb540)
Location: kernel/printk/printk.c:1347
Inline: False
```
**Symbols:**

```
ffffffff810eb540-ffffffff810eb7ff: syslog_print_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int syslog_print_all(char *buf, int size, bool clear);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810f32b0)
Location: kernel/printk/printk.c:1351
Inline: False
```
**Symbols:**

```
ffffffff810f32b0-ffffffff810f3572: syslog_print_all (STB_LOCAL)
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
In kernel/printk/printk.c (ffffffff810fefd6)
Location: kernel/printk/printk.c:1365
Inline: True
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
In kernel/printk/printk.c (ffffffff8110791a)
Location: kernel/printk/printk.c:1409
Inline: True
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
In kernel/printk/printk.c (ffffffff81113cda)
Location: kernel/printk/printk.c:1419
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int syslog_print_all(char *buf, int size, bool clear);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8111e380)
Location: kernel/printk/printk.c:1447
Inline: False
```
**Symbols:**

```
ffffffff8111e380-ffffffff8111e6a8: syslog_print_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int syslog_print_all(char *buf, int size, bool clear);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81118e30)
Location: kernel/printk/printk.c:1492
Inline: False
```
**Symbols:**

```
ffffffff81118e30-ffffffff811190f5: syslog_print_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int syslog_print_all(char *buf, int size, bool clear);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81119650)
Location: kernel/printk/printk.c:1555
Inline: False
```
**Symbols:**

```
ffffffff81119650-ffffffff81119881: syslog_print_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int syslog_print_all(char *buf, int size, bool clear);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:1572
Inline: False
```
**Symbols:**

```
ffffffff811398e0-ffffffff81139aeb: syslog_print_all (STB_LOCAL)
ffffffff81cac19f-ffffffff81cac1b4: syslog_print_all.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int syslog_print_all(char *buf, int size, bool clear);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:1599
Inline: False
Direct callers:
  - kernel/printk/printk.c:do_syslog
```
**Symbols:**

```
ffffffff8115c440-ffffffff8115c69d: syslog_print_all (STB_LOCAL)
ffffffff81e5c675-ffffffff81e5c68a: syslog_print_all.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int syslog_print_all(char *buf, int size, bool clear);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:1680
Inline: False
Direct callers:
  - kernel/printk/printk.c:do_syslog
```
**Symbols:**

```
ffffffff8118ef20-ffffffff8118f17d: syslog_print_all (STB_LOCAL)
ffffffff8205891d-ffffffff82058932: syslog_print_all.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int syslog_print_all(char *buf, int size, bool clear);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:1649
Inline: False
Direct callers:
  - kernel/printk/printk.c:do_syslog
```
**Symbols:**

```
ffffffff811a07c0-ffffffff811a0a13: syslog_print_all (STB_LOCAL)
ffffffff820d71db-ffffffff820d71f0: syslog_print_all.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int syslog_print_all(char *buf, int size, bool clear);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:1646
Inline: False
Direct callers:
  - kernel/printk/printk.c:do_syslog
```
**Symbols:**

```
ffffffff811af880-ffffffff811afb02: syslog_print_all (STB_LOCAL)
ffffffff821b2424-ffffffff821b2439: syslog_print_all.cold (STB_LOCAL)
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
int syslog_print_all(char *buf, int size, bool clear);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffff800010173398)
Location: kernel/printk/printk.c:1419
Inline: False
```
**Symbols:**

```
ffff800010173398-ffff800010173818: syslog_print_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int syslog_print_all(char *buf, int size, bool clear);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (c03c6b28)
Location: kernel/printk/printk.c:1419
Inline: False
```
**Symbols:**

```
c03c6b28-c03c6f44: syslog_print_all (STB_LOCAL)
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
In kernel/printk/printk.c (c0000000001ce134)
Location: kernel/printk/printk.c:1419
Inline: True
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
In kernel/printk/printk.c (ffffffe0001104d6)
Location: kernel/printk/printk.c:1419
Inline: True
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
In kernel/printk/printk.c (ffffffff8110c2ba)
Location: kernel/printk/printk.c:1419
Inline: True
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
In kernel/printk/printk.c (ffffffff810fd0b2)
Location: kernel/printk/printk.c:1419
Inline: True
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
In kernel/printk/printk.c (ffffffff8110a1aa)
Location: kernel/printk/printk.c:1419
Inline: True
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
In kernel/printk/printk.c (ffffffff8111532e)
Location: kernel/printk/printk.c:1419
Inline: True
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
