# Function: <code>tty_audit_buf_get</code>

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
In drivers/tty/tty_audit.c (ffffffff814ed36a)
Location: drivers/tty/tty_audit.c:219
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
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
In drivers/tty/tty_audit.c (ffffffff8153e1a7)
Location: drivers/tty/tty_audit.c:179
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
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
Location: drivers/tty/tty_audit.c:179
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
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
In drivers/tty/tty_audit.c (ffffffff8157ee0b)
Location: drivers/tty/tty_audit.c:179
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
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
In drivers/tty/tty_audit.c (ffffffff815e397b)
Location: drivers/tty/tty_audit.c:177
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
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
In drivers/tty/tty_audit.c (ffffffff8161cc5b)
Location: drivers/tty/tty_audit.c:177
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
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
In drivers/tty/tty_audit.c (ffffffff81639edb)
Location: drivers/tty/tty_audit.c:176
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
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
In drivers/tty/tty_audit.c (ffffffff8166e1fb)
Location: drivers/tty/tty_audit.c:176
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
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
In drivers/tty/tty_audit.c (ffffffff8169087b)
Location: drivers/tty/tty_audit.c:176
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct tty_audit_buf *tty_audit_buf_get();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff81742d50)
Location: drivers/tty/tty_audit.c:176
Inline: False
Direct callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
```
**Symbols:**

```
ffffffff81742d50-ffffffff81742e78: tty_audit_buf_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct tty_audit_buf *tty_audit_buf_get();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff8175ebf0)
Location: drivers/tty/tty_audit.c:176
Inline: False
Direct callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
```
**Symbols:**

```
ffffffff8175ebf0-ffffffff8175ed18: tty_audit_buf_get (STB_LOCAL)
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
Location: drivers/tty/tty_audit.c:177
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
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
Location: drivers/tty/tty_audit.c:177
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
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
Location: drivers/tty/tty_audit.c:177
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
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
Location: drivers/tty/tty_audit.c:177
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
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
Location: drivers/tty/tty_audit.c:177
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
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
Location: drivers/tty/tty_audit.c:177
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
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
In drivers/tty/tty_audit.c (ffff800010863650)
Location: drivers/tty/tty_audit.c:176
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
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
In drivers/tty/tty_audit.c (c0969368)
Location: drivers/tty/tty_audit.c:176
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
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
In drivers/tty/tty_audit.c (c0000000009024f4)
Location: drivers/tty/tty_audit.c:176
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
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
In drivers/tty/tty_audit.c (ffffffe00053a0dc)
Location: drivers/tty/tty_audit.c:176
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
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
In drivers/tty/tty_audit.c (ffffffff816562fb)
Location: drivers/tty/tty_audit.c:176
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
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
In drivers/tty/tty_audit.c (ffffffff8163668b)
Location: drivers/tty/tty_audit.c:176
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
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
In drivers/tty/tty_audit.c (ffffffff816846bb)
Location: drivers/tty/tty_audit.c:176
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
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
In drivers/tty/tty_audit.c (ffffffff8169eccb)
Location: drivers/tty/tty_audit.c:176
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
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
</ul>
