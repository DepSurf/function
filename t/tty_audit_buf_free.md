# Function: <code>tty_audit_buf_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tty_audit_buf_free(struct tty_audit_buf *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff814ecf90)
Location: drivers/tty/tty_audit.c:50
Inline: False
Direct callers:
  - drivers/tty/tty_audit.c:tty_audit_buf_put
  - drivers/tty/tty_audit.c:tty_audit_add_data
```
**Symbols:**

```
ffffffff814ecf90-ffffffff814ecfcb: tty_audit_buf_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tty_audit_buf_free(struct tty_audit_buf *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff8153df90)
Location: drivers/tty/tty_audit.c:55
Inline: False
Direct callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_exit
```
**Symbols:**

```
ffffffff8153df90-ffffffff8153dfcb: tty_audit_buf_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tty_audit_buf_free(struct tty_audit_buf *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff8156a5e0)
Location: drivers/tty/tty_audit.c:55
Inline: False
Direct callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_exit
```
**Symbols:**

```
ffffffff8156a5e0-ffffffff8156a61b: tty_audit_buf_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tty_audit_buf_free(struct tty_audit_buf *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff8157ec00)
Location: drivers/tty/tty_audit.c:55
Inline: False
Direct callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_exit
```
**Symbols:**

```
ffffffff8157ec00-ffffffff8157ec2c: tty_audit_buf_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tty_audit_buf_free(struct tty_audit_buf *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff815e3770)
Location: drivers/tty/tty_audit.c:53
Inline: False
Direct callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_exit
```
**Symbols:**

```
ffffffff815e3770-ffffffff815e379c: tty_audit_buf_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tty_audit_buf_free(struct tty_audit_buf *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff8161ca50)
Location: drivers/tty/tty_audit.c:53
Inline: False
Direct callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_exit
```
**Symbols:**

```
ffffffff8161ca50-ffffffff8161ca7c: tty_audit_buf_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tty_audit_buf_free(struct tty_audit_buf *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff81639cd0)
Location: drivers/tty/tty_audit.c:53
Inline: False
Direct callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_exit
```
**Symbols:**

```
ffffffff81639cd0-ffffffff81639cfc: tty_audit_buf_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void tty_audit_buf_free(struct tty_audit_buf *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_audit.c (0)
Location: drivers/tty/tty_audit.c:53
Inline: False
Direct callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_exit
```
**Symbols:**

```
ffffffff8166dff0-ffffffff8166e01f: tty_audit_buf_free (STB_LOCAL)
ffffffff8166e3da-ffffffff8166e3ed: tty_audit_buf_free.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tty_audit_buf_free(struct tty_audit_buf *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff81690660)
Location: drivers/tty/tty_audit.c:53
Inline: False
Direct callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_exit
```
**Symbols:**

```
ffffffff81690660-ffffffff8169068f: tty_audit_buf_free (STB_LOCAL)
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
In drivers/tty/tty_audit.c (ffffffff81742e16)
Location: drivers/tty/tty_audit.c:53
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_buf_get
  - drivers/tty/tty_audit.c:tty_audit_exit
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
In drivers/tty/tty_audit.c (ffffffff8175ecb6)
Location: drivers/tty/tty_audit.c:53
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_buf_get
  - drivers/tty/tty_audit.c:tty_audit_exit
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
In drivers/tty/tty_audit.c (ffffffff81742e62)
Location: drivers/tty/tty_audit.c:54
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_exit
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
In drivers/tty/tty_audit.c (ffffffff817c38b2)
Location: drivers/tty/tty_audit.c:54
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_exit
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
In drivers/tty/tty_audit.c (ffffffff819004cd)
Location: drivers/tty/tty_audit.c:54
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_exit
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
In drivers/tty/tty_audit.c (ffffffff81a59f8d)
Location: drivers/tty/tty_audit.c:54
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_exit
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
In drivers/tty/tty_audit.c (ffffffff81aa45bb)
Location: drivers/tty/tty_audit.c:54
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_exit
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
In drivers/tty/tty_audit.c (ffffffff81af6fc1)
Location: drivers/tty/tty_audit.c:54
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_exit
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
void tty_audit_buf_free(struct tty_audit_buf *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffff8000108633d0)
Location: drivers/tty/tty_audit.c:53
Inline: False
Direct callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_exit
```
**Symbols:**

```
ffff8000108633d0-ffff80001086342c: tty_audit_buf_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tty_audit_buf_free(struct tty_audit_buf *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (c09690d8)
Location: drivers/tty/tty_audit.c:53
Inline: False
Direct callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_exit
```
**Symbols:**

```
c09690d8-c096912c: tty_audit_buf_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tty_audit_buf_free(struct tty_audit_buf *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (c000000000902220)
Location: drivers/tty/tty_audit.c:53
Inline: False
Direct callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_exit
```
**Symbols:**

```
c000000000902220-c000000000902280: tty_audit_buf_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tty_audit_buf_free(struct tty_audit_buf *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffe000539ed2)
Location: drivers/tty/tty_audit.c:53
Inline: False
Direct callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_exit
```
**Symbols:**

```
ffffffe000539ed2-ffffffe000539f0e: tty_audit_buf_free (STB_LOCAL)
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
void tty_audit_buf_free(struct tty_audit_buf *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff816560e0)
Location: drivers/tty/tty_audit.c:53
Inline: False
Direct callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_exit
```
**Symbols:**

```
ffffffff816560e0-ffffffff8165610f: tty_audit_buf_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tty_audit_buf_free(struct tty_audit_buf *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff81636470)
Location: drivers/tty/tty_audit.c:53
Inline: False
Direct callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_exit
```
**Symbols:**

```
ffffffff81636470-ffffffff8163649f: tty_audit_buf_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tty_audit_buf_free(struct tty_audit_buf *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff816844a0)
Location: drivers/tty/tty_audit.c:53
Inline: False
Direct callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_exit
```
**Symbols:**

```
ffffffff816844a0-ffffffff816844cf: tty_audit_buf_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tty_audit_buf_free(struct tty_audit_buf *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_audit.c (ffffffff8169eab0)
Location: drivers/tty/tty_audit.c:53
Inline: False
Direct callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_exit
```
**Symbols:**

```
ffffffff8169eab0-ffffffff8169eadf: tty_audit_buf_free (STB_LOCAL)
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
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
