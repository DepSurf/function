# Function: <code>vc_uniscr_copy_line</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void vc_uniscr_copy_line(struct vc_data *vc, void *dest, int viewed, unsigned int row, unsigned int col, unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff816468a0)
Location: drivers/tty/vt/vt.c:552
Inline: False
Direct callers:
  - drivers/tty/vt/vc_screen.c:vcs_read
```
**Symbols:**

```
ffffffff816468a0-ffffffff816469db: vc_uniscr_copy_line (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void vc_uniscr_copy_line(struct vc_data *vc, void *dest, int viewed, unsigned int row, unsigned int col, unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8167aeb0)
Location: drivers/tty/vt/vt.c:552
Inline: False
Direct callers:
  - drivers/tty/vt/vc_screen.c:vcs_read
```
**Symbols:**

```
ffffffff8167aeb0-ffffffff8167afea: vc_uniscr_copy_line (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void vc_uniscr_copy_line(struct vc_data *vc, void *dest, int viewed, unsigned int row, unsigned int col, unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8169d6a0)
Location: drivers/tty/vt/vt.c:552
Inline: False
Direct callers:
  - drivers/tty/vt/vc_screen.c:vcs_read
```
**Symbols:**

```
ffffffff8169d6a0-ffffffff8169d7da: vc_uniscr_copy_line (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void vc_uniscr_copy_line(struct vc_data *vc, void *dest, int viewed, unsigned int row, unsigned int col, unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff817504e0)
Location: drivers/tty/vt/vt.c:558
Inline: False
Direct callers:
  - drivers/tty/vt/vc_screen.c:vcs_read
```
**Symbols:**

```
ffffffff817504e0-ffffffff81750615: vc_uniscr_copy_line (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void vc_uniscr_copy_line(const struct vc_data *vc, void *dest, bool viewed, unsigned int row, unsigned int col, unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8176bf10)
Location: drivers/tty/vt/vt.c:551
Inline: False
Direct callers:
  - drivers/tty/vt/vc_screen.c:vcs_read
```
**Symbols:**

```
ffffffff8176bf10-ffffffff8176c045: vc_uniscr_copy_line (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void vc_uniscr_copy_line(const struct vc_data *vc, void *dest, bool viewed, unsigned int row, unsigned int col, unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8174fab0)
Location: drivers/tty/vt/vt.c:551
Inline: False
Direct callers:
  - drivers/tty/vt/vc_screen.c:vcs_read
```
**Symbols:**

```
ffffffff8174fab0-ffffffff8174fbe5: vc_uniscr_copy_line (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void vc_uniscr_copy_line(const struct vc_data *vc, void *dest, bool viewed, unsigned int row, unsigned int col, unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff817d2420)
Location: drivers/tty/vt/vt.c:547
Inline: False
Direct callers:
  - drivers/tty/vt/vc_screen.c:vcs_read
```
**Symbols:**

```
ffffffff817d2420-ffffffff817d2555: vc_uniscr_copy_line (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void vc_uniscr_copy_line(const struct vc_data *vc, void *dest, bool viewed, unsigned int row, unsigned int col, unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81910090)
Location: drivers/tty/vt/vt.c:547
Inline: False
Direct callers:
  - drivers/tty/vt/vc_screen.c:vcs_read
```
**Symbols:**

```
ffffffff81910090-ffffffff819101f8: vc_uniscr_copy_line (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void vc_uniscr_copy_line(const struct vc_data *vc, void *dest, bool viewed, unsigned int row, unsigned int col, unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81a6aee0)
Location: drivers/tty/vt/vt.c:547
Inline: False
Direct callers:
  - drivers/tty/vt/vc_screen.c:vcs_read
```
**Symbols:**

```
ffffffff81a6aee0-ffffffff81a6b048: vc_uniscr_copy_line (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void vc_uniscr_copy_line(const struct vc_data *vc, void *dest, bool viewed, unsigned int row, unsigned int col, unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81ab55e0)
Location: drivers/tty/vt/vt.c:527
Inline: False
Direct callers:
  - drivers/tty/vt/vc_screen.c:vcs_read
```
**Symbols:**

```
ffffffff81ab55e0-ffffffff81ab576b: vc_uniscr_copy_line (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void vc_uniscr_copy_line(const struct vc_data *vc, void *dest, bool viewed, unsigned int row, unsigned int col, unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81b082a0)
Location: drivers/tty/vt/vt.c:526
Inline: False
Direct callers:
  - drivers/tty/vt/vc_screen.c:vcs_read
```
**Symbols:**

```
ffffffff81b082a0-ffffffff81b0842b: vc_uniscr_copy_line (STB_GLOBAL)
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
void vc_uniscr_copy_line(struct vc_data *vc, void *dest, int viewed, unsigned int row, unsigned int col, unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffff800010874e50)
Location: drivers/tty/vt/vt.c:552
Inline: False
Direct callers:
  - drivers/tty/vt/vc_screen.c:vcs_read
```
**Symbols:**

```
ffff800010874e50-ffff800010874f9c: vc_uniscr_copy_line (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void vc_uniscr_copy_line(struct vc_data *vc, void *dest, int viewed, unsigned int row, unsigned int col, unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (c0977c6c)
Location: drivers/tty/vt/vt.c:552
Inline: False
Direct callers:
  - drivers/tty/vt/vc_screen.c:vcs_read
```
**Symbols:**

```
c0977c6c-c0977d78: vc_uniscr_copy_line (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void vc_uniscr_copy_line(struct vc_data *vc, void *dest, int viewed, unsigned int row, unsigned int col, unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (c000000000916430)
Location: drivers/tty/vt/vt.c:552
Inline: False
Direct callers:
  - drivers/tty/vt/vc_screen.c:vcs_read
```
**Symbols:**

```
c000000000916430-c0000000009165fc: vc_uniscr_copy_line (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void vc_uniscr_copy_line(struct vc_data *vc, void *dest, int viewed, unsigned int row, unsigned int col, unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffe000546704)
Location: drivers/tty/vt/vt.c:552
Inline: False
Direct callers:
  - drivers/tty/vt/vc_screen.c:vcs_read
```
**Symbols:**

```
ffffffe000546704-ffffffe000546812: vc_uniscr_copy_line (STB_GLOBAL)
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
void vc_uniscr_copy_line(struct vc_data *vc, void *dest, int viewed, unsigned int row, unsigned int col, unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81663100)
Location: drivers/tty/vt/vt.c:552
Inline: False
Direct callers:
  - drivers/tty/vt/vc_screen.c:vcs_read
```
**Symbols:**

```
ffffffff81663100-ffffffff8166323a: vc_uniscr_copy_line (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void vc_uniscr_copy_line(struct vc_data *vc, void *dest, int viewed, unsigned int row, unsigned int col, unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81643480)
Location: drivers/tty/vt/vt.c:552
Inline: False
Direct callers:
  - drivers/tty/vt/vc_screen.c:vcs_read
```
**Symbols:**

```
ffffffff81643480-ffffffff816435ba: vc_uniscr_copy_line (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void vc_uniscr_copy_line(struct vc_data *vc, void *dest, int viewed, unsigned int row, unsigned int col, unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff816914e0)
Location: drivers/tty/vt/vt.c:552
Inline: False
Direct callers:
  - drivers/tty/vt/vc_screen.c:vcs_read
```
**Symbols:**

```
ffffffff816914e0-ffffffff8169161a: vc_uniscr_copy_line (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void vc_uniscr_copy_line(struct vc_data *vc, void *dest, int viewed, unsigned int row, unsigned int col, unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff816abad0)
Location: drivers/tty/vt/vt.c:552
Inline: False
Direct callers:
  - drivers/tty/vt/vc_screen.c:vcs_read
```
**Symbols:**

```
ffffffff816abad0-ffffffff816abc0a: vc_uniscr_copy_line (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct vc_data *vc</code> ➡️ <code>const struct vc_data *vc</code>
</li>
<li>
<b>Param type changed. </b>
<code>int viewed</code> ➡️ <code>bool viewed</code>
</li>
</ul>
</details>
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
