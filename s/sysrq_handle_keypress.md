# Function: <code>sysrq_handle_keypress</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/sysrq.c (ffffffff814ee00b)
Location: drivers/tty/sysrq.c:757
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/sysrq.c (ffffffff8153ec96)
Location: drivers/tty/sysrq.c:764
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
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
In drivers/tty/sysrq.c (ffffffff8156b2e6)
Location: drivers/tty/sysrq.c:764
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
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
In drivers/tty/sysrq.c (ffffffff8157f928)
Location: drivers/tty/sysrq.c:771
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
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
In drivers/tty/sysrq.c (ffffffff815e44a8)
Location: drivers/tty/sysrq.c:777
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
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
In drivers/tty/sysrq.c (ffffffff8161d617)
Location: drivers/tty/sysrq.c:777
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
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
In drivers/tty/sysrq.c (ffffffff8163a880)
Location: drivers/tty/sysrq.c:771
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
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
In drivers/tty/sysrq.c (ffffffff8166ec1d)
Location: drivers/tty/sysrq.c:777
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
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
In drivers/tty/sysrq.c (ffffffff8169122d)
Location: drivers/tty/sysrq.c:772
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool sysrq_handle_keypress(struct sysrq_state *sysrq, unsigned int code, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/sysrq.c (ffffffff817439e0)
Location: drivers/tty/sysrq.c:787
Inline: False
Direct callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
**Symbols:**

```
ffffffff817439e0-ffffffff81743d7f: sysrq_handle_keypress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool sysrq_handle_keypress(struct sysrq_state *sysrq, unsigned int code, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/sysrq.c (ffffffff8175f880)
Location: drivers/tty/sysrq.c:816
Inline: False
Direct callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
**Symbols:**

```
ffffffff8175f880-ffffffff8175fc6e: sysrq_handle_keypress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool sysrq_handle_keypress(struct sysrq_state *sysrq, unsigned int code, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/sysrq.c (ffffffff817436e0)
Location: drivers/tty/sysrq.c:817
Inline: False
Direct callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
**Symbols:**

```
ffffffff817436e0-ffffffff81743ad1: sysrq_handle_keypress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool sysrq_handle_keypress(struct sysrq_state *sysrq, unsigned int code, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/sysrq.c (0)
Location: drivers/tty/sysrq.c:817
Inline: False
Direct callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
**Symbols:**

```
ffffffff817c42b0-ffffffff817c47b3: sysrq_handle_keypress (STB_LOCAL)
ffffffff81cf90a8-ffffffff81cf91ca: sysrq_handle_keypress.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool sysrq_handle_keypress(struct sysrq_state *sysrq, unsigned int code, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/sysrq.c (0)
Location: drivers/tty/sysrq.c:820
Inline: False
Direct callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
**Symbols:**

```
ffffffff81900fc0-ffffffff8190150a: sysrq_handle_keypress (STB_LOCAL)
ffffffff81ec122c-ffffffff81ec137e: sysrq_handle_keypress.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool sysrq_handle_keypress(struct sysrq_state *sysrq, unsigned int code, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/sysrq.c (0)
Location: drivers/tty/sysrq.c:820
Inline: False
Direct callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
**Symbols:**

```
ffffffff81a5aec0-ffffffff81a5b40a: sysrq_handle_keypress (STB_LOCAL)
ffffffff82095483-ffffffff820955d5: sysrq_handle_keypress.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool sysrq_handle_keypress(struct sysrq_state *sysrq, unsigned int code, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/sysrq.c (0)
Location: drivers/tty/sysrq.c:820
Inline: False
Direct callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
**Symbols:**

```
ffffffff81aa54f0-ffffffff81aa5a3d: sysrq_handle_keypress (STB_LOCAL)
ffffffff821162d2-ffffffff82116424: sysrq_handle_keypress.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool sysrq_handle_keypress(struct sysrq_state *sysrq, unsigned int code, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/sysrq.c (0)
Location: drivers/tty/sysrq.c:819
Inline: False
Direct callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
**Symbols:**

```
ffffffff81af7f40-ffffffff81af848d: sysrq_handle_keypress (STB_LOCAL)
ffffffff821f3fe4-ffffffff821f4136: sysrq_handle_keypress.cold (STB_LOCAL)
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
In drivers/tty/sysrq.c (ffff800010864754)
Location: drivers/tty/sysrq.c:772
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
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
In drivers/tty/sysrq.c (c096a11c)
Location: drivers/tty/sysrq.c:772
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
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
In drivers/tty/sysrq.c (c0000000009038b4)
Location: drivers/tty/sysrq.c:772
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
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
In drivers/tty/sysrq.c (ffffffe00053af22)
Location: drivers/tty/sysrq.c:772
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
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
In drivers/tty/sysrq.c (ffffffff81656cad)
Location: drivers/tty/sysrq.c:772
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
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
In drivers/tty/sysrq.c (ffffffff8163703d)
Location: drivers/tty/sysrq.c:772
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
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
In drivers/tty/sysrq.c (ffffffff8168506d)
Location: drivers/tty/sysrq.c:772
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
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
In drivers/tty/sysrq.c (ffffffff8169f66d)
Location: drivers/tty/sysrq.c:772
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
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
