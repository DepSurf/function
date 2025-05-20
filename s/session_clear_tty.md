# Function: <code>session_clear_tty</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void session_clear_tty(struct pid *session);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff814e1dd0)
Location: drivers/tty/tty_io.c:569
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
```
**Symbols:**

```
ffffffff814e1dd0-ffffffff814e1e1a: session_clear_tty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void session_clear_tty(struct pid *session);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81533080)
Location: drivers/tty/tty_io.c:576
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
```
**Symbols:**

```
ffffffff81533080-ffffffff815330c8: session_clear_tty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void session_clear_tty(struct pid *session);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8155f7b0)
Location: drivers/tty/tty_io.c:576
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
```
**Symbols:**

```
ffffffff8155f7b0-ffffffff8155f7f8: session_clear_tty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void session_clear_tty(struct pid *session);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff8157d150)
Location: drivers/tty/tty_jobctrl.c:170
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffff8157d150-ffffffff8157d19c: session_clear_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void session_clear_tty(struct pid *session);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff815e1c70)
Location: drivers/tty/tty_jobctrl.c:171
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffff815e1c70-ffffffff815e1cbc: session_clear_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void session_clear_tty(struct pid *session);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff8161af20)
Location: drivers/tty/tty_jobctrl.c:171
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffff8161af20-ffffffff8161af6a: session_clear_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void session_clear_tty(struct pid *session);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff81638190)
Location: drivers/tty/tty_jobctrl.c:171
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffff81638190-ffffffff816381da: session_clear_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void session_clear_tty(struct pid *session);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff8166c460)
Location: drivers/tty/tty_jobctrl.c:171
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffff8166c460-ffffffff8166c49b: session_clear_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void session_clear_tty(struct pid *session);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff8168ead0)
Location: drivers/tty/tty_jobctrl.c:171
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffff8168ead0-ffffffff8168eb0b: session_clear_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void session_clear_tty(struct pid *session);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff81741060)
Location: drivers/tty/tty_jobctrl.c:171
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_jobctrl.c:tiocsctty
```
**Symbols:**

```
ffffffff81741060-ffffffff817410d1: session_clear_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void session_clear_tty(struct pid *session);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff8175cf90)
Location: drivers/tty/tty_jobctrl.c:173
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_jobctrl.c:tiocsctty
```
**Symbols:**

```
ffffffff8175cf90-ffffffff8175d001: session_clear_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void session_clear_tty(struct pid *session);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff81740c50)
Location: drivers/tty/tty_jobctrl.c:175
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffff81740c50-ffffffff81740cc1: session_clear_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void session_clear_tty(struct pid *session);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff817c16b0)
Location: drivers/tty/tty_jobctrl.c:175
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffff817c16b0-ffffffff817c1721: session_clear_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void session_clear_tty(struct pid *session);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff818fe0b0)
Location: drivers/tty/tty_jobctrl.c:175
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffff818fe0b0-ffffffff818fe135: session_clear_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void session_clear_tty(struct pid *session);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff81a578a0)
Location: drivers/tty/tty_jobctrl.c:175
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffff81a578a0-ffffffff81a57925: session_clear_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void session_clear_tty(struct pid *session);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff81aa1ea0)
Location: drivers/tty/tty_jobctrl.c:175
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffff81aa1ea0-ffffffff81aa1f25: session_clear_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void session_clear_tty(struct pid *session);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff81af4900)
Location: drivers/tty/tty_jobctrl.c:175
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffff81af4900-ffffffff81af4985: session_clear_tty (STB_GLOBAL)
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
void session_clear_tty(struct pid *session);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffff800010860308)
Location: drivers/tty/tty_jobctrl.c:171
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffff800010860308-ffff800010860354: session_clear_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void session_clear_tty(struct pid *session);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (c09673c8)
Location: drivers/tty/tty_jobctrl.c:171
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
c09673c8-c0967428: session_clear_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void session_clear_tty(struct pid *session);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (c0000000008ff710)
Location: drivers/tty/tty_jobctrl.c:171
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
c0000000008ff710-c0000000008ff784: session_clear_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void session_clear_tty(struct pid *session);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffe00053824a)
Location: drivers/tty/tty_jobctrl.c:171
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffe00053824a-ffffffe00053828a: session_clear_tty (STB_GLOBAL)
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
void session_clear_tty(struct pid *session);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff81654550)
Location: drivers/tty/tty_jobctrl.c:171
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffff81654550-ffffffff8165458b: session_clear_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void session_clear_tty(struct pid *session);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff81634930)
Location: drivers/tty/tty_jobctrl.c:171
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffff81634930-ffffffff8163496b: session_clear_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void session_clear_tty(struct pid *session);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff81682910)
Location: drivers/tty/tty_jobctrl.c:171
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffff81682910-ffffffff8168294b: session_clear_tty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void session_clear_tty(struct pid *session);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_jobctrl.c (ffffffff8169cf70)
Location: drivers/tty/tty_jobctrl.c:171
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
```
**Symbols:**

```
ffffffff8169cf70-ffffffff8169cfab: session_clear_tty (STB_GLOBAL)
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
