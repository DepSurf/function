# Function: <code>tty_audit_add_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tty_audit_add_data(struct tty_struct *tty, const void *data, size_t size, unsigned int icanon);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff814ed2d0)
Location: drivers/tty/tty_audit.c:268
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:copy_from_read_buf
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
```
**Symbols:**

```
ffffffff814ed2d0-ffffffff814ed64f: tty_audit_add_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tty_audit_add_data(struct tty_struct *tty, const void *data, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff8153e130)
Location: drivers/tty/tty_audit.c:204
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
```
**Symbols:**

```
ffffffff8153e130-ffffffff8153e397: tty_audit_add_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tty_audit_add_data(struct tty_struct *tty, const void *data, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff8156a780)
Location: drivers/tty/tty_audit.c:204
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
```
**Symbols:**

```
ffffffff8156a780-ffffffff8156a9e7: tty_audit_add_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tty_audit_add_data(struct tty_struct *tty, const void *data, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff8157ed90)
Location: drivers/tty/tty_audit.c:204
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
```
**Symbols:**

```
ffffffff8157ed90-ffffffff8157f018: tty_audit_add_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tty_audit_add_data(struct tty_struct *tty, const void *data, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff815e3900)
Location: drivers/tty/tty_audit.c:202
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
```
**Symbols:**

```
ffffffff815e3900-ffffffff815e3b86: tty_audit_add_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tty_audit_add_data(struct tty_struct *tty, const void *data, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff8161cbe0)
Location: drivers/tty/tty_audit.c:202
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
```
**Symbols:**

```
ffffffff8161cbe0-ffffffff8161ce69: tty_audit_add_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tty_audit_add_data(struct tty_struct *tty, const void *data, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff81639e60)
Location: drivers/tty/tty_audit.c:201
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
```
**Symbols:**

```
ffffffff81639e60-ffffffff8163a0e7: tty_audit_add_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void tty_audit_add_data(struct tty_struct *tty, const void *data, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_audit.c (0)
Location: drivers/tty/tty_audit.c:201
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
```
**Symbols:**

```
ffffffff8166e412-ffffffff8166e41c: tty_audit_add_data.cold (STB_LOCAL)
ffffffff8166e180-ffffffff8166e3da: tty_audit_add_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tty_audit_add_data(struct tty_struct *tty, const void *data, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff81690800)
Location: drivers/tty/tty_audit.c:201
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
```
**Symbols:**

```
ffffffff81690800-ffffffff81690a60: tty_audit_add_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tty_audit_add_data(struct tty_struct *tty, const void *data, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff81743060)
Location: drivers/tty/tty_audit.c:201
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:copy_from_read_buf
  - drivers/tty/n_tty.c:tty_copy_to_user
  - drivers/tty/n_tty.c:tty_copy_to_user
  - drivers/tty/n_tty.c:tty_copy_to_user
```
**Symbols:**

```
ffffffff81743060-ffffffff81743204: tty_audit_add_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tty_audit_add_data(struct tty_struct *tty, const void *data, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff8175eef0)
Location: drivers/tty/tty_audit.c:201
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:copy_from_read_buf
  - drivers/tty/n_tty.c:tty_copy
  - drivers/tty/n_tty.c:tty_copy
```
**Symbols:**

```
ffffffff8175eef0-ffffffff8175f08a: tty_audit_add_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tty_audit_add_data(struct tty_struct *tty, const void *data, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff81742c10)
Location: drivers/tty/tty_audit.c:202
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
  - drivers/tty/n_tty.c:copy_from_read_buf
```
**Symbols:**

```
ffffffff81742c10-ffffffff81742ef8: tty_audit_add_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void tty_audit_add_data(struct tty_struct *tty, const void *data, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff817c3660)
Location: drivers/tty/tty_audit.c:202
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
  - drivers/tty/n_tty.c:copy_from_read_buf
```
**Symbols:**

```
ffffffff817c3660-ffffffff817c3948: tty_audit_add_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tty_audit_add_data(struct tty_struct *tty, const void *data, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff81900270)
Location: drivers/tty/tty_audit.c:202
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:copy_from_read_buf
  - drivers/tty/n_tty.c:tty_copy
  - drivers/tty/n_tty.c:tty_copy
```
**Symbols:**

```
ffffffff81900270-ffffffff81900539: tty_audit_add_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tty_audit_add_data(struct tty_struct *tty, const void *data, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff81a59d30)
Location: drivers/tty/tty_audit.c:202
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:copy_from_read_buf
  - drivers/tty/n_tty.c:tty_copy
  - drivers/tty/n_tty.c:tty_copy
```
**Symbols:**

```
ffffffff81a59d30-ffffffff81a59ff9: tty_audit_add_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void tty_audit_add_data(const struct tty_struct *tty, const void *data, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_audit.c (0)
Location: drivers/tty/tty_audit.c:202
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:copy_from_read_buf
  - drivers/tty/n_tty.c:tty_copy
  - drivers/tty/n_tty.c:tty_copy
```
**Symbols:**

```
ffffffff821161de-ffffffff821161f9: tty_audit_add_data.cold (STB_LOCAL)
ffffffff81aa4360-ffffffff81aa4627: tty_audit_add_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void tty_audit_add_data(const struct tty_struct *tty, const void *data, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_audit.c (0)
Location: drivers/tty/tty_audit.c:202
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:copy_from_read_buf
  - drivers/tty/n_tty.c:tty_copy
  - drivers/tty/n_tty.c:tty_copy
```
**Symbols:**

```
ffffffff821f3ef0-ffffffff821f3f0b: tty_audit_add_data.cold (STB_LOCAL)
ffffffff81af6d20-ffffffff81af7028: tty_audit_add_data (STB_GLOBAL)
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
void tty_audit_add_data(struct tty_struct *tty, const void *data, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffff8000108635e0)
Location: drivers/tty/tty_audit.c:201
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
```
**Symbols:**

```
ffff8000108635e0-ffff800010863848: tty_audit_add_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tty_audit_add_data(struct tty_struct *tty, const void *data, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (c09692f0)
Location: drivers/tty/tty_audit.c:201
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
```
**Symbols:**

```
c09692f0-c0969550: tty_audit_add_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tty_audit_add_data(struct tty_struct *tty, const void *data, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (c000000000902470)
Location: drivers/tty/tty_audit.c:201
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
```
**Symbols:**

```
c000000000902470-c000000000902754: tty_audit_add_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tty_audit_add_data(struct tty_struct *tty, const void *data, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffe00053a07e)
Location: drivers/tty/tty_audit.c:201
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
```
**Symbols:**

```
ffffffe00053a07e-ffffffe00053a274: tty_audit_add_data (STB_GLOBAL)
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
void tty_audit_add_data(struct tty_struct *tty, const void *data, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff81656280)
Location: drivers/tty/tty_audit.c:201
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
```
**Symbols:**

```
ffffffff81656280-ffffffff816564e0: tty_audit_add_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tty_audit_add_data(struct tty_struct *tty, const void *data, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff81636610)
Location: drivers/tty/tty_audit.c:201
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
```
**Symbols:**

```
ffffffff81636610-ffffffff81636870: tty_audit_add_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tty_audit_add_data(struct tty_struct *tty, const void *data, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff81684640)
Location: drivers/tty/tty_audit.c:201
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
```
**Symbols:**

```
ffffffff81684640-ffffffff816848a0: tty_audit_add_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tty_audit_add_data(struct tty_struct *tty, const void *data, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff8169ec50)
Location: drivers/tty/tty_audit.c:201
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
```
**Symbols:**

```
ffffffff8169ec50-ffffffff8169eeb0: tty_audit_add_data (STB_GLOBAL)
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
<b>Param removed. </b>
<code>unsigned int icanon</code>
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
<code>struct tty_struct *tty</code> ➡️ <code>const struct tty_struct *tty</code>
</li>
</ul>
</details>
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
