# Function: <code>tty_audit_log</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tty_audit_log(const char *description, int major, int minor, unsigned char *data, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff814ece10)
Location: drivers/tty/tty_audit.c:63
Inline: False
Direct callers:
  - drivers/tty/tty_audit.c:tty_audit_buf_push
  - drivers/tty/tty_audit.c:tty_audit_tiocsti
```
**Symbols:**

```
ffffffff814ece10-ffffffff814ecf3e: tty_audit_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tty_audit_log(const char *description, dev_t dev, unsigned char *data, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff8153de00)
Location: drivers/tty/tty_audit.c:62
Inline: False
Direct callers:
  - drivers/tty/tty_audit.c:tty_audit_tiocsti
  - drivers/tty/tty_audit.c:tty_audit_buf_push
```
**Symbols:**

```
ffffffff8153de00-ffffffff8153df37: tty_audit_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tty_audit_log(const char *description, dev_t dev, unsigned char *data, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff8156a450)
Location: drivers/tty/tty_audit.c:62
Inline: False
Direct callers:
  - drivers/tty/tty_audit.c:tty_audit_tiocsti
  - drivers/tty/tty_audit.c:tty_audit_buf_push
```
**Symbols:**

```
ffffffff8156a450-ffffffff8156a587: tty_audit_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tty_audit_log(const char *description, dev_t dev, unsigned char *data, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff8157ea80)
Location: drivers/tty/tty_audit.c:62
Inline: False
Direct callers:
  - drivers/tty/tty_audit.c:tty_audit_tiocsti
  - drivers/tty/tty_audit.c:tty_audit_buf_push
```
**Symbols:**

```
ffffffff8157ea80-ffffffff8157ebaa: tty_audit_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tty_audit_log(const char *description, dev_t dev, unsigned char *data, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff815e35f0)
Location: drivers/tty/tty_audit.c:60
Inline: False
Direct callers:
  - drivers/tty/tty_audit.c:tty_audit_tiocsti
  - drivers/tty/tty_audit.c:tty_audit_buf_push
```
**Symbols:**

```
ffffffff815e35f0-ffffffff815e371f: tty_audit_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tty_audit_log(const char *description, dev_t dev, unsigned char *data, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff8161c8c0)
Location: drivers/tty/tty_audit.c:60
Inline: False
Direct callers:
  - drivers/tty/tty_audit.c:tty_audit_tiocsti
  - drivers/tty/tty_audit.c:tty_audit_buf_push
```
**Symbols:**

```
ffffffff8161c8c0-ffffffff8161c9f3: tty_audit_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tty_audit_log(const char *description, dev_t dev, unsigned char *data, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff81639b40)
Location: drivers/tty/tty_audit.c:60
Inline: False
Direct callers:
  - drivers/tty/tty_audit.c:tty_audit_tiocsti
  - drivers/tty/tty_audit.c:tty_audit_buf_push
```
**Symbols:**

```
ffffffff81639b40-ffffffff81639c73: tty_audit_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tty_audit_log(const char *description, dev_t dev, unsigned char *data, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff8166de60)
Location: drivers/tty/tty_audit.c:60
Inline: False
Direct callers:
  - drivers/tty/tty_audit.c:tty_audit_tiocsti
  - drivers/tty/tty_audit.c:tty_audit_buf_push
```
**Symbols:**

```
ffffffff8166de60-ffffffff8166df96: tty_audit_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tty_audit_log(const char *description, dev_t dev, unsigned char *data, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff816904d0)
Location: drivers/tty/tty_audit.c:60
Inline: False
Direct callers:
  - drivers/tty/tty_audit.c:tty_audit_tiocsti
  - drivers/tty/tty_audit.c:tty_audit_buf_push
```
**Symbols:**

```
ffffffff816904d0-ffffffff81690606: tty_audit_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tty_audit_log(const char *description, dev_t dev, unsigned char *data, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff81742c10)
Location: drivers/tty/tty_audit.c:60
Inline: False
Direct callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_push
  - drivers/tty/tty_audit.c:tty_audit_tiocsti
  - drivers/tty/tty_audit.c:tty_audit_exit
```
**Symbols:**

```
ffffffff81742c10-ffffffff81742d46: tty_audit_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tty_audit_log(const char *description, dev_t dev, unsigned char *data, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff8175eab0)
Location: drivers/tty/tty_audit.c:60
Inline: False
Direct callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_push
  - drivers/tty/tty_audit.c:tty_audit_tiocsti
  - drivers/tty/tty_audit.c:tty_audit_exit
```
**Symbols:**

```
ffffffff8175eab0-ffffffff8175ebef: tty_audit_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tty_audit_log(const char *description, dev_t dev, unsigned char *data, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff817428f0)
Location: drivers/tty/tty_audit.c:61
Inline: False
Direct callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_push
  - drivers/tty/tty_audit.c:tty_audit_tiocsti
  - drivers/tty/tty_audit.c:tty_audit_exit
```
**Symbols:**

```
ffffffff817428f0-ffffffff81742a2f: tty_audit_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void tty_audit_log(const char *description, dev_t dev, unsigned char *data, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff817c3340)
Location: drivers/tty/tty_audit.c:61
Inline: False
Direct callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_push
  - drivers/tty/tty_audit.c:tty_audit_tiocsti
  - drivers/tty/tty_audit.c:tty_audit_exit
```
**Symbols:**

```
ffffffff817c3340-ffffffff817c347f: tty_audit_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tty_audit_log(const char *description, dev_t dev, unsigned char *data, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff818ffef0)
Location: drivers/tty/tty_audit.c:61
Inline: False
Direct callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_push
  - drivers/tty/tty_audit.c:tty_audit_tiocsti
  - drivers/tty/tty_audit.c:tty_audit_exit
```
**Symbols:**

```
ffffffff818ffef0-ffffffff81900066: tty_audit_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tty_audit_log(const char *description, dev_t dev, unsigned char *data, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff81a59960)
Location: drivers/tty/tty_audit.c:61
Inline: False
Direct callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_push
  - drivers/tty/tty_audit.c:tty_audit_tiocsti
  - drivers/tty/tty_audit.c:tty_audit_exit
```
**Symbols:**

```
ffffffff81a59960-ffffffff81a59ad6: tty_audit_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tty_audit_log(const char *description, dev_t dev, const unsigned char *data, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff81aa3f90)
Location: drivers/tty/tty_audit.c:61
Inline: False
Direct callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_push
  - drivers/tty/tty_audit.c:tty_audit_tiocsti
  - drivers/tty/tty_audit.c:tty_audit_exit
```
**Symbols:**

```
ffffffff81aa3f90-ffffffff81aa4102: tty_audit_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tty_audit_log(const char *description, dev_t dev, const u8 *data, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff81af6950)
Location: drivers/tty/tty_audit.c:61
Inline: False
Direct callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_push
  - drivers/tty/tty_audit.c:tty_audit_tiocsti
  - drivers/tty/tty_audit.c:tty_audit_exit
```
**Symbols:**

```
ffffffff81af6950-ffffffff81af6ac2: tty_audit_log (STB_LOCAL)
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
void tty_audit_log(const char *description, dev_t dev, unsigned char *data, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffff800010863230)
Location: drivers/tty/tty_audit.c:60
Inline: False
Direct callers:
  - drivers/tty/tty_audit.c:tty_audit_tiocsti
  - drivers/tty/tty_audit.c:tty_audit_buf_push
```
**Symbols:**

```
ffff800010863230-ffff800010863374: tty_audit_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tty_audit_log(const char *description, dev_t dev, unsigned char *data, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (c0968f0c)
Location: drivers/tty/tty_audit.c:60
Inline: False
Direct callers:
  - drivers/tty/tty_audit.c:tty_audit_tiocsti
  - drivers/tty/tty_audit.c:tty_audit_buf_push
```
**Symbols:**

```
c0968f0c-c0969078: tty_audit_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tty_audit_log(const char *description, dev_t dev, unsigned char *data, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (c000000000901fc0)
Location: drivers/tty/tty_audit.c:60
Inline: False
Direct callers:
  - drivers/tty/tty_audit.c:tty_audit_tiocsti
  - drivers/tty/tty_audit.c:tty_audit_buf_push
```
**Symbols:**

```
c000000000901fc0-c000000000902158: tty_audit_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tty_audit_log(const char *description, dev_t dev, unsigned char *data, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffe000539d80)
Location: drivers/tty/tty_audit.c:60
Inline: False
Direct callers:
  - drivers/tty/tty_audit.c:tty_audit_tiocsti
  - drivers/tty/tty_audit.c:tty_audit_buf_push
```
**Symbols:**

```
ffffffe000539d80-ffffffe000539e8a: tty_audit_log (STB_LOCAL)
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
void tty_audit_log(const char *description, dev_t dev, unsigned char *data, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff81655f50)
Location: drivers/tty/tty_audit.c:60
Inline: False
Direct callers:
  - drivers/tty/tty_audit.c:tty_audit_tiocsti
  - drivers/tty/tty_audit.c:tty_audit_buf_push
```
**Symbols:**

```
ffffffff81655f50-ffffffff81656086: tty_audit_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tty_audit_log(const char *description, dev_t dev, unsigned char *data, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff816362e0)
Location: drivers/tty/tty_audit.c:60
Inline: False
Direct callers:
  - drivers/tty/tty_audit.c:tty_audit_tiocsti
  - drivers/tty/tty_audit.c:tty_audit_buf_push
```
**Symbols:**

```
ffffffff816362e0-ffffffff81636416: tty_audit_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tty_audit_log(const char *description, dev_t dev, unsigned char *data, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff81684310)
Location: drivers/tty/tty_audit.c:60
Inline: False
Direct callers:
  - drivers/tty/tty_audit.c:tty_audit_tiocsti
  - drivers/tty/tty_audit.c:tty_audit_buf_push
```
**Symbols:**

```
ffffffff81684310-ffffffff81684446: tty_audit_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tty_audit_log(const char *description, dev_t dev, unsigned char *data, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff8169e910)
Location: drivers/tty/tty_audit.c:60
Inline: False
Direct callers:
  - drivers/tty/tty_audit.c:tty_audit_tiocsti
  - drivers/tty/tty_audit.c:tty_audit_buf_push
```
**Symbols:**

```
ffffffff8169e910-ffffffff8169ea59: tty_audit_log (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>dev_t dev</code>
</li>
<li>
<b>Param removed. </b>
<code>int major</code>
</li>
<li>
<b>Param removed. </b>
<code>int minor</code>
</li>
<li>
<b>Param reordered. </b>
<code>description, major, minor, data, size</code> ➡️ <code>description, dev, data, size</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>unsigned char *data</code> ➡️ <code>const unsigned char *data</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const unsigned char *data</code> ➡️ <code>const u8 *data</code>
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
