# Function: <code>tomoyo_write_control</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t tomoyo_write_control(struct tomoyo_io_buffer *head, const char *buffer, const int buffer_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff8136b330)
Location: security/tomoyo/common.c:2583
Inline: False
Direct callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write
```
**Symbols:**

```
ffffffff8136b330-ffffffff8136b9ab: tomoyo_write_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t tomoyo_write_control(struct tomoyo_io_buffer *head, const char *buffer, const int buffer_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff813a1550)
Location: security/tomoyo/common.c:2583
Inline: False
Direct callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write
```
**Symbols:**

```
ffffffff813a1550-ffffffff813a1bc3: tomoyo_write_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t tomoyo_write_control(struct tomoyo_io_buffer *head, const char *buffer, const int buffer_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff813b80d0)
Location: security/tomoyo/common.c:2583
Inline: False
Direct callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write
```
**Symbols:**

```
ffffffff813b80d0-ffffffff813b8743: tomoyo_write_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t tomoyo_write_control(struct tomoyo_io_buffer *head, const char *buffer, const int buffer_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff813ce980)
Location: security/tomoyo/common.c:2583
Inline: False
Direct callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write
```
**Symbols:**

```
ffffffff813ce980-ffffffff813cefff: tomoyo_write_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t tomoyo_write_control(struct tomoyo_io_buffer *head, const char *buffer, const int buffer_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff813f4e30)
Location: security/tomoyo/common.c:2584
Inline: False
Direct callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write
```
**Symbols:**

```
ffffffff813f4e30-ffffffff813f54ab: tomoyo_write_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
ssize_t tomoyo_write_control(struct tomoyo_io_buffer *head, const char *buffer, const int buffer_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/common.c (0)
Location: security/tomoyo/common.c:2584
Inline: False
Direct callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write
```
**Symbols:**

```
ffffffff814264f8-ffffffff81426525: tomoyo_write_control.cold.19 (STB_LOCAL)
ffffffff81425da0-ffffffff814263e5: tomoyo_write_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
ssize_t tomoyo_write_control(struct tomoyo_io_buffer *head, const char *buffer, const int buffer_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/common.c (0)
Location: security/tomoyo/common.c:2585
Inline: False
Direct callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write
```
**Symbols:**

```
ffffffff81442bf8-ffffffff81442c16: tomoyo_write_control.cold.20 (STB_LOCAL)
ffffffff81442490-ffffffff81442ae3: tomoyo_write_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
ssize_t tomoyo_write_control(struct tomoyo_io_buffer *head, const char *buffer, const int buffer_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/common.c (0)
Location: security/tomoyo/common.c:2656
Inline: False
Direct callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write
```
**Symbols:**

```
ffffffff81470805-ffffffff81470827: tomoyo_write_control.cold (STB_LOCAL)
ffffffff81470050-ffffffff814706a6: tomoyo_write_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
ssize_t tomoyo_write_control(struct tomoyo_io_buffer *head, const char *buffer, const int buffer_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/common.c (0)
Location: security/tomoyo/common.c:2655
Inline: False
Direct callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write
```
**Symbols:**

```
ffffffff8148a59f-ffffffff8148a5c1: tomoyo_write_control.cold (STB_LOCAL)
ffffffff81489e20-ffffffff8148a46a: tomoyo_write_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t tomoyo_write_control(struct tomoyo_io_buffer *head, const char *buffer, const int buffer_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff814e1320)
Location: security/tomoyo/common.c:2655
Inline: False
Direct callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write
```
**Symbols:**

```
ffffffff814e1320-ffffffff814e15fb: tomoyo_write_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t tomoyo_write_control(struct tomoyo_io_buffer *head, const char *buffer, const int buffer_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff814fe750)
Location: security/tomoyo/common.c:2655
Inline: False
Direct callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write
```
**Symbols:**

```
ffffffff814fe750-ffffffff814fea2b: tomoyo_write_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
ssize_t tomoyo_write_control(struct tomoyo_io_buffer *head, const char *buffer, const int buffer_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/common.c (0)
Location: security/tomoyo/common.c:2655
Inline: False
Direct callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write
```
**Symbols:**

```
ffffffff81be34fd-ffffffff81be3520: tomoyo_write_control.cold (STB_LOCAL)
ffffffff81505310-ffffffff815056cd: tomoyo_write_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t tomoyo_write_control(struct tomoyo_io_buffer *head, const char *buffer, const int buffer_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff81562220)
Location: security/tomoyo/common.c:2655
Inline: False
Direct callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write
```
**Symbols:**

```
ffffffff81562220-ffffffff815624e5: tomoyo_write_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t tomoyo_write_control(struct tomoyo_io_buffer *head, const char *buffer, const int buffer_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff815fd2e0)
Location: security/tomoyo/common.c:2646
Inline: False
Direct callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write
```
**Symbols:**

```
ffffffff815fd2e0-ffffffff815fd5b2: tomoyo_write_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t tomoyo_write_control(struct tomoyo_io_buffer *head, const char *buffer, const int buffer_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff816ae0b0)
Location: security/tomoyo/common.c:2646
Inline: False
Direct callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write
```
**Symbols:**

```
ffffffff816ae0b0-ffffffff816ae385: tomoyo_write_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t tomoyo_write_control(struct tomoyo_io_buffer *head, const char *buffer, const int buffer_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff816e6ad0)
Location: security/tomoyo/common.c:2646
Inline: False
Direct callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write
```
**Symbols:**

```
ffffffff816e6ad0-ffffffff816e6db3: tomoyo_write_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t tomoyo_write_control(struct tomoyo_io_buffer *head, const char *buffer, const int buffer_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff817237e0)
Location: security/tomoyo/common.c:2647
Inline: False
Direct callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write
```
**Symbols:**

```
ffffffff817237e0-ffffffff81723ac3: tomoyo_write_control (STB_GLOBAL)
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
ssize_t tomoyo_write_control(struct tomoyo_io_buffer *head, const char *buffer, const int buffer_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffff80001057d108)
Location: security/tomoyo/common.c:2655
Inline: False
Direct callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write
```
**Symbols:**

```
ffff80001057d108-ffff80001057d86c: tomoyo_write_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t tomoyo_write_control(struct tomoyo_io_buffer *head, const char *buffer, const int buffer_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (c072f778)
Location: security/tomoyo/common.c:2655
Inline: False
Direct callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write
```
**Symbols:**

```
c072f778-c072fe00: tomoyo_write_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t tomoyo_write_control(struct tomoyo_io_buffer *head, const char *buffer, const int buffer_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (c0000000006e8790)
Location: security/tomoyo/common.c:2655
Inline: False
Direct callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write
```
**Symbols:**

```
c0000000006e8790-c0000000006e95c8: tomoyo_write_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t tomoyo_write_control(struct tomoyo_io_buffer *head, const char *buffer, const int buffer_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffe0003ce6d6)
Location: security/tomoyo/common.c:2655
Inline: False
Direct callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write
```
**Symbols:**

```
ffffffe0003ce6d6-ffffffe0003cec08: tomoyo_write_control (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
ssize_t tomoyo_write_control(struct tomoyo_io_buffer *head, const char *buffer, const int buffer_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/common.c (0)
Location: security/tomoyo/common.c:2655
Inline: False
Direct callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write
```
**Symbols:**

```
ffffffff81482b7f-ffffffff81482ba1: tomoyo_write_control.cold (STB_LOCAL)
ffffffff81482400-ffffffff81482a4a: tomoyo_write_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
ssize_t tomoyo_write_control(struct tomoyo_io_buffer *head, const char *buffer, const int buffer_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/common.c (0)
Location: security/tomoyo/common.c:2655
Inline: False
Direct callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write
```
**Symbols:**

```
ffffffff8147359f-ffffffff814735c1: tomoyo_write_control.cold (STB_LOCAL)
ffffffff81472e20-ffffffff8147346a: tomoyo_write_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
ssize_t tomoyo_write_control(struct tomoyo_io_buffer *head, const char *buffer, const int buffer_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/common.c (0)
Location: security/tomoyo/common.c:2655
Inline: False
Direct callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write
```
**Symbols:**

```
ffffffff8147ec1f-ffffffff8147ec41: tomoyo_write_control.cold (STB_LOCAL)
ffffffff8147e4a0-ffffffff8147eaea: tomoyo_write_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
ssize_t tomoyo_write_control(struct tomoyo_io_buffer *head, const char *buffer, const int buffer_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/common.c (0)
Location: security/tomoyo/common.c:2655
Inline: False
Direct callers:
  - security/tomoyo/securityfs_if.c:tomoyo_write
```
**Symbols:**

```
ffffffff8149674f-ffffffff81496771: tomoyo_write_control.cold (STB_LOCAL)
ffffffff81495fb0-ffffffff81496613: tomoyo_write_control (STB_GLOBAL)
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
