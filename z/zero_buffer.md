# Function: <code>zero_buffer</code>

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
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff81633cad)
Location: drivers/tty/n_tty.c:156
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
```
**Symbols:**

```
ffffffff81630b20-ffffffff81630b35: zero_buffer.isra.5.part.6 (STB_LOCAL)
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
In drivers/tty/n_tty.c (ffffffff81666a8e)
Location: drivers/tty/n_tty.c:158
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
```
**Symbols:**

```
ffffffff81664af0-ffffffff81664b05: zero_buffer.isra.0.part.0 (STB_LOCAL)
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
In drivers/tty/n_tty.c (ffffffff81688da3)
Location: drivers/tty/n_tty.c:158
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
```
**Symbols:**

```
ffffffff81687140-ffffffff81687155: zero_buffer.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff81739480)
Location: drivers/tty/n_tty.c:158
Inline: True
Direct callers:
  - drivers/tty/n_tty.c:copy_from_read_buf
  - drivers/tty/n_tty.c:tty_copy_to_user
  - drivers/tty/n_tty.c:tty_copy_to_user
```
**Symbols:**

```
ffffffff81739480-ffffffff817394a7: zero_buffer.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff81755470)
Location: drivers/tty/n_tty.c:158
Inline: True
Direct callers:
  - drivers/tty/n_tty.c:copy_from_read_buf
  - drivers/tty/n_tty.c:tty_copy
  - drivers/tty/n_tty.c:tty_copy
```
**Symbols:**

```
ffffffff81755470-ffffffff81755497: zero_buffer.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff817391d0)
Location: drivers/tty/n_tty.c:159
Inline: True
Direct callers:
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
  - drivers/tty/n_tty.c:copy_from_read_buf
```
**Symbols:**

```
ffffffff817391d0-ffffffff817391f3: zero_buffer.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff817b9c90)
Location: drivers/tty/n_tty.c:159
Inline: True
Direct callers:
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
  - drivers/tty/n_tty.c:copy_from_read_buf
```
**Symbols:**

```
ffffffff817b9c90-ffffffff817b9cb3: zero_buffer.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff818f5ed0)
Location: drivers/tty/n_tty.c:159
Inline: True
Direct callers:
  - drivers/tty/n_tty.c:copy_from_read_buf
  - drivers/tty/n_tty.c:tty_copy
  - drivers/tty/n_tty.c:tty_copy
```
**Symbols:**

```
ffffffff818f5ed0-ffffffff818f5f0b: zero_buffer.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff81a4e8c0)
Location: drivers/tty/n_tty.c:162
Inline: True
Direct callers:
  - drivers/tty/n_tty.c:copy_from_read_buf
  - drivers/tty/n_tty.c:tty_copy
  - drivers/tty/n_tty.c:tty_copy
```
**Symbols:**

```
ffffffff81a4e8c0-ffffffff81a4e8fb: zero_buffer.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff81a98bc0)
Location: drivers/tty/n_tty.c:161
Inline: True
Direct callers:
  - drivers/tty/n_tty.c:copy_from_read_buf
  - drivers/tty/n_tty.c:tty_copy
  - drivers/tty/n_tty.c:tty_copy
```
**Symbols:**

```
ffffffff81a98bc0-ffffffff81a98bfd: zero_buffer.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void zero_buffer(const struct tty_struct *tty, u8 *buffer, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff81aeb220)
Location: drivers/tty/n_tty.c:161
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:copy_from_read_buf
  - drivers/tty/n_tty.c:tty_copy
  - drivers/tty/n_tty.c:tty_copy
```
**Symbols:**

```
ffffffff81aeb220-ffffffff81aeb25c: zero_buffer (STB_LOCAL)
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
In drivers/tty/n_tty.c (ffff8000108565bc)
Location: drivers/tty/n_tty.c:158
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
```
**Symbols:**

```
ffff8000108548a0-ffff8000108548d8: zero_buffer.isra.0.part.0 (STB_LOCAL)
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
In drivers/tty/n_tty.c (c0960ca8)
Location: drivers/tty/n_tty.c:158
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
```
**Symbols:**

```
c095f168-c095f18c: zero_buffer.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/n_tty.c (c0000000008f80e8)
Location: drivers/tty/n_tty.c:158
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
```
**Symbols:**

```
c0000000008f3f70-c0000000008f3fac: zero_buffer.part.0 (STB_LOCAL)
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
In drivers/tty/n_tty.c (ffffffe000533a8e)
Location: drivers/tty/n_tty.c:158
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
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
In drivers/tty/n_tty.c (ffffffff8164e823)
Location: drivers/tty/n_tty.c:158
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
```
**Symbols:**

```
ffffffff8164cbc0-ffffffff8164cbd5: zero_buffer.isra.0.part.0 (STB_LOCAL)
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
In drivers/tty/n_tty.c (ffffffff8162ec73)
Location: drivers/tty/n_tty.c:158
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
```
**Symbols:**

```
ffffffff8162d010-ffffffff8162d025: zero_buffer.isra.0.part.0 (STB_LOCAL)
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
In drivers/tty/n_tty.c (ffffffff8167cbe3)
Location: drivers/tty/n_tty.c:158
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
```
**Symbols:**

```
ffffffff8167af80-ffffffff8167af95: zero_buffer.isra.0.part.0 (STB_LOCAL)
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
In drivers/tty/n_tty.c (ffffffff81697243)
Location: drivers/tty/n_tty.c:158
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
```
**Symbols:**

```
ffffffff816955e0-ffffffff816955f5: zero_buffer.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
