# Function: <code>scsi_format_opcode_name</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
size_t scsi_format_opcode_name(char *buffer, size_t buf_len, const unsigned char *cdbp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff815b7f10)
Location: drivers/scsi/scsi_logging.c:148
Inline: False
Direct callers:
  - drivers/scsi/scsi_logging.c:__scsi_format_command
  - drivers/scsi/scsi_logging.c:scsi_print_command
```
**Symbols:**

```
ffffffff815b7f10-ffffffff815b80fa: scsi_format_opcode_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
size_t scsi_format_opcode_name(char *buffer, size_t buf_len, const unsigned char *cdbp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff81610790)
Location: drivers/scsi/scsi_logging.c:148
Inline: False
Direct callers:
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:__scsi_format_command
```
**Symbols:**

```
ffffffff81610790-ffffffff8161096b: scsi_format_opcode_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
size_t scsi_format_opcode_name(char *buffer, size_t buf_len, const unsigned char *cdbp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff81640020)
Location: drivers/scsi/scsi_logging.c:148
Inline: False
Direct callers:
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:__scsi_format_command
```
**Symbols:**

```
ffffffff81640020-ffffffff816401fb: scsi_format_opcode_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
size_t scsi_format_opcode_name(char *buffer, size_t buf_len, const unsigned char *cdbp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff81654a60)
Location: drivers/scsi/scsi_logging.c:148
Inline: False
Direct callers:
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:__scsi_format_command
```
**Symbols:**

```
ffffffff81654a60-ffffffff81654c1d: scsi_format_opcode_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
size_t scsi_format_opcode_name(char *buffer, size_t buf_len, const unsigned char *cdbp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff816bdfb0)
Location: drivers/scsi/scsi_logging.c:148
Inline: False
Direct callers:
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:__scsi_format_command
```
**Symbols:**

```
ffffffff816bdfb0-ffffffff816be16d: scsi_format_opcode_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
size_t scsi_format_opcode_name(char *buffer, size_t buf_len, const unsigned char *cdbp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff816fa560)
Location: drivers/scsi/scsi_logging.c:148
Inline: False
Direct callers:
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:__scsi_format_command
```
**Symbols:**

```
ffffffff816fa560-ffffffff816fa722: scsi_format_opcode_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
size_t scsi_format_opcode_name(char *buffer, size_t buf_len, const unsigned char *cdbp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff8171cfa0)
Location: drivers/scsi/scsi_logging.c:148
Inline: False
Direct callers:
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:__scsi_format_command
```
**Symbols:**

```
ffffffff8171cfa0-ffffffff8171d162: scsi_format_opcode_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
size_t scsi_format_opcode_name(char *buffer, size_t buf_len, const unsigned char *cdbp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_logging.c (0)
Location: drivers/scsi/scsi_logging.c:147
Inline: False
Direct callers:
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:__scsi_format_command
```
**Symbols:**

```
ffffffff81758550-ffffffff81758706: scsi_format_opcode_name (STB_LOCAL)
ffffffff817590c0-ffffffff817590e6: scsi_format_opcode_name.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
size_t scsi_format_opcode_name(char *buffer, size_t buf_len, const unsigned char *cdbp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff8177c420)
Location: drivers/scsi/scsi_logging.c:105
Inline: False
Direct callers:
  - drivers/scsi/scsi_logging.c:__scsi_format_command
```
**Symbols:**

```
ffffffff8177c420-ffffffff8177c5e4: scsi_format_opcode_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
size_t scsi_format_opcode_name(char *buffer, size_t buf_len, const unsigned char *cdbp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff8183f770)
Location: drivers/scsi/scsi_logging.c:105
Inline: False
Direct callers:
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:__scsi_format_command
```
**Symbols:**

```
ffffffff8183f770-ffffffff8183f934: scsi_format_opcode_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
size_t scsi_format_opcode_name(char *buffer, size_t buf_len, const unsigned char *cdbp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff8184fdd0)
Location: drivers/scsi/scsi_logging.c:105
Inline: False
Direct callers:
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:__scsi_format_command
```
**Symbols:**

```
ffffffff8184fdd0-ffffffff8184ff94: scsi_format_opcode_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
size_t scsi_format_opcode_name(char *buffer, size_t buf_len, const unsigned char *cdbp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff81833050)
Location: drivers/scsi/scsi_logging.c:105
Inline: False
Direct callers:
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:__scsi_format_command
```
**Symbols:**

```
ffffffff81833050-ffffffff81833213: scsi_format_opcode_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
size_t scsi_format_opcode_name(char *buffer, size_t buf_len, const unsigned char *cdbp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff818bf0a0)
Location: drivers/scsi/scsi_logging.c:106
Inline: False
Direct callers:
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:__scsi_format_command
```
**Symbols:**

```
ffffffff818bf0a0-ffffffff818bf263: scsi_format_opcode_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
size_t scsi_format_opcode_name(char *buffer, size_t buf_len, const unsigned char *cdbp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff81a0b4e0)
Location: drivers/scsi/scsi_logging.c:108
Inline: False
Direct callers:
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:__scsi_format_command
```
**Symbols:**

```
ffffffff81a0b4e0-ffffffff81a0b6aa: scsi_format_opcode_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t scsi_format_opcode_name(char *buffer, size_t buf_len, const unsigned char *cdbp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff81b8aef0)
Location: drivers/scsi/scsi_logging.c:108
Inline: False
Direct callers:
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:__scsi_format_command
```
**Symbols:**

```
ffffffff81b8aef0-ffffffff81b8b0ba: scsi_format_opcode_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t scsi_format_opcode_name(char *buffer, size_t buf_len, const unsigned char *cdbp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff81bdef00)
Location: drivers/scsi/scsi_logging.c:108
Inline: False
Direct callers:
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:__scsi_format_command
```
**Symbols:**

```
ffffffff81bdef00-ffffffff81bdf0ca: scsi_format_opcode_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t scsi_format_opcode_name(char *buffer, size_t buf_len, const unsigned char *cdbp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff81c33df0)
Location: drivers/scsi/scsi_logging.c:108
Inline: False
Direct callers:
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:__scsi_format_command
```
**Symbols:**

```
ffffffff81c33df0-ffffffff81c33fba: scsi_format_opcode_name (STB_LOCAL)
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
size_t scsi_format_opcode_name(char *buffer, size_t buf_len, const unsigned char *cdbp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffff800010982450)
Location: drivers/scsi/scsi_logging.c:105
Inline: False
Direct callers:
  - drivers/scsi/scsi_logging.c:__scsi_format_command
```
**Symbols:**

```
ffff800010982450-ffff800010982620: scsi_format_opcode_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
size_t scsi_format_opcode_name(char *buffer, size_t buf_len, const unsigned char *cdbp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (c0a54e9c)
Location: drivers/scsi/scsi_logging.c:105
Inline: False
Direct callers:
  - drivers/scsi/scsi_logging.c:__scsi_format_command
```
**Symbols:**

```
c0a54e9c-c0a55088: scsi_format_opcode_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
size_t scsi_format_opcode_name(char *buffer, size_t buf_len, const unsigned char *cdbp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (c000000000a3ea60)
Location: drivers/scsi/scsi_logging.c:105
Inline: False
Direct callers:
  - drivers/scsi/scsi_logging.c:__scsi_format_command
```
**Symbols:**

```
c000000000a3ea60-c000000000a3ecb8: scsi_format_opcode_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
size_t scsi_format_opcode_name(char *buffer, size_t buf_len, const unsigned char *cdbp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffe0005e7d68)
Location: drivers/scsi/scsi_logging.c:105
Inline: False
Direct callers:
  - drivers/scsi/scsi_logging.c:__scsi_format_command
```
**Symbols:**

```
ffffffe0005e7d68-ffffffe0005e7ed0: scsi_format_opcode_name (STB_LOCAL)
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
size_t scsi_format_opcode_name(char *buffer, size_t buf_len, const unsigned char *cdbp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff81730b10)
Location: drivers/scsi/scsi_logging.c:105
Inline: False
Direct callers:
  - drivers/scsi/scsi_logging.c:__scsi_format_command
```
**Symbols:**

```
ffffffff81730b10-ffffffff81730cd4: scsi_format_opcode_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
size_t scsi_format_opcode_name(char *buffer, size_t buf_len, const unsigned char *cdbp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff81709f30)
Location: drivers/scsi/scsi_logging.c:105
Inline: False
Direct callers:
  - drivers/scsi/scsi_logging.c:__scsi_format_command
```
**Symbols:**

```
ffffffff81709f30-ffffffff8170a0f4: scsi_format_opcode_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
size_t scsi_format_opcode_name(char *buffer, size_t buf_len, const unsigned char *cdbp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff8176f8e0)
Location: drivers/scsi/scsi_logging.c:105
Inline: False
Direct callers:
  - drivers/scsi/scsi_logging.c:__scsi_format_command
```
**Symbols:**

```
ffffffff8176f8e0-ffffffff8176faa4: scsi_format_opcode_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
size_t scsi_format_opcode_name(char *buffer, size_t buf_len, const unsigned char *cdbp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff8178b080)
Location: drivers/scsi/scsi_logging.c:105
Inline: False
Direct callers:
  - drivers/scsi/scsi_logging.c:__scsi_format_command
```
**Symbols:**

```
ffffffff8178b080-ffffffff8178b244: scsi_format_opcode_name (STB_LOCAL)
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
