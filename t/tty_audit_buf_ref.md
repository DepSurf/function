# Function: <code>tty_audit_buf_ref</code>

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
In drivers/tty/tty_audit.c (ffffffff8153e1a7)
Location: drivers/tty/tty_audit.c:24
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_push
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
In drivers/tty/tty_audit.c (ffffffff8156a7f7)
Location: drivers/tty/tty_audit.c:24
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_push
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff8157ee0b)
Location: drivers/tty/tty_audit.c:24
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_push
Direct callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_push
```
**Symbols:**

```
ffffffff8157ec30-ffffffff8157ec3d: tty_audit_buf_ref.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff815e397b)
Location: drivers/tty/tty_audit.c:22
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_push
Direct callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_push
```
**Symbols:**

```
ffffffff815e37a0-ffffffff815e37ad: tty_audit_buf_ref.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff8161cc5b)
Location: drivers/tty/tty_audit.c:22
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_push
Direct callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_push
```
**Symbols:**

```
ffffffff8161ca80-ffffffff8161ca8d: tty_audit_buf_ref.part.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff81639edb)
Location: drivers/tty/tty_audit.c:22
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_push
Direct callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_push
```
**Symbols:**

```
ffffffff81639d00-ffffffff81639d0d: tty_audit_buf_ref.part.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff8166e1fb)
Location: drivers/tty/tty_audit.c:22
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_push
Direct callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_push
```
**Symbols:**

```
ffffffff8166e3ed-ffffffff8166e406: tty_audit_buf_ref.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff8169087b)
Location: drivers/tty/tty_audit.c:22
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_push
Direct callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_push
```
**Symbols:**

```
ffffffff81690690-ffffffff8169069d: tty_audit_buf_ref.part.0 (STB_LOCAL)
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
In drivers/tty/tty_audit.c (ffffffff81742d55)
Location: drivers/tty/tty_audit.c:22
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_buf_get
  - drivers/tty/tty_audit.c:tty_audit_buf_get
  - drivers/tty/tty_audit.c:tty_audit_buf_get
  - drivers/tty/tty_audit.c:tty_audit_push
  - drivers/tty/tty_audit.c:tty_audit_push
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
In drivers/tty/tty_audit.c (ffffffff8175ebf5)
Location: drivers/tty/tty_audit.c:22
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_buf_get
  - drivers/tty/tty_audit.c:tty_audit_buf_get
  - drivers/tty/tty_audit.c:tty_audit_buf_get
  - drivers/tty/tty_audit.c:tty_audit_push
  - drivers/tty/tty_audit.c:tty_audit_push
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
In drivers/tty/tty_audit.c (ffffffff81742c8b)
Location: drivers/tty/tty_audit.c:23
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_push
  - drivers/tty/tty_audit.c:tty_audit_push
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
In drivers/tty/tty_audit.c (ffffffff817c36db)
Location: drivers/tty/tty_audit.c:23
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_push
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
In drivers/tty/tty_audit.c (ffffffff819002e7)
Location: drivers/tty/tty_audit.c:23
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_push
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
In drivers/tty/tty_audit.c (ffffffff81a59da7)
Location: drivers/tty/tty_audit.c:23
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_push
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
In drivers/tty/tty_audit.c (ffffffff81aa43d7)
Location: drivers/tty/tty_audit.c:23
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_push
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
In drivers/tty/tty_audit.c (ffffffff81af6d97)
Location: drivers/tty/tty_audit.c:23
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_push
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_audit.c (ffff800010863650)
Location: drivers/tty/tty_audit.c:22
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_push
Direct callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_push
```
**Symbols:**

```
ffff800010863430-ffff80001086344c: tty_audit_buf_ref.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_audit.c (c0969368)
Location: drivers/tty/tty_audit.c:22
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_push
Direct callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_push
```
**Symbols:**

```
c096912c-c096915c: tty_audit_buf_ref.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct tty_audit_buf *tty_audit_buf_ref();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (c0000000009021f0)
Location: drivers/tty/tty_audit.c:22
Inline: False
Direct callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_push
```
**Symbols:**

```
c0000000009021f0-c000000000902218: tty_audit_buf_ref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffe00053a0dc)
Location: drivers/tty/tty_audit.c:22
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_push
Direct callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_push
```
**Symbols:**

```
ffffffe000539f0e-ffffffe000539f2a: tty_audit_buf_ref.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff816562fb)
Location: drivers/tty/tty_audit.c:22
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_push
Direct callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_push
```
**Symbols:**

```
ffffffff81656110-ffffffff8165611d: tty_audit_buf_ref.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff8163668b)
Location: drivers/tty/tty_audit.c:22
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_push
Direct callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_push
```
**Symbols:**

```
ffffffff816364a0-ffffffff816364ad: tty_audit_buf_ref.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff816846bb)
Location: drivers/tty/tty_audit.c:22
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_push
Direct callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_push
```
**Symbols:**

```
ffffffff816844d0-ffffffff816844dd: tty_audit_buf_ref.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff8169eccb)
Location: drivers/tty/tty_audit.c:22
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_push
Direct callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_push
```
**Symbols:**

```
ffffffff8169eae0-ffffffff8169eaed: tty_audit_buf_ref.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
