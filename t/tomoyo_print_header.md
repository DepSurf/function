# Function: <code>tomoyo_print_header</code>

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
In security/tomoyo/audit.c (ffffffff81366b52)
Location: security/tomoyo/audit.c:147
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_init_log
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
In security/tomoyo/audit.c (ffffffff8139cbf2)
Location: security/tomoyo/audit.c:147
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_init_log
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
In security/tomoyo/audit.c (ffffffff813b37d2)
Location: security/tomoyo/audit.c:147
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_init_log
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
In security/tomoyo/audit.c (ffffffff813ca1a2)
Location: security/tomoyo/audit.c:147
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_init_log
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
In security/tomoyo/audit.c (ffffffff813f0642)
Location: security/tomoyo/audit.c:148
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_init_log
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
In security/tomoyo/audit.c (ffffffff81421599)
Location: security/tomoyo/audit.c:148
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_init_log
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
In security/tomoyo/audit.c (ffffffff8143dc19)
Location: security/tomoyo/audit.c:148
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_init_log
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
char *tomoyo_print_header(struct tomoyo_request_info *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/audit.c (ffffffff8146b770)
Location: security/tomoyo/audit.c:150
Inline: False
Direct callers:
  - security/tomoyo/audit.c:tomoyo_init_log
```
**Symbols:**

```
ffffffff8146b770-ffffffff8146bd5c: tomoyo_print_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
char *tomoyo_print_header(struct tomoyo_request_info *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/audit.c (ffffffff81485550)
Location: security/tomoyo/audit.c:150
Inline: False
Direct callers:
  - security/tomoyo/audit.c:tomoyo_init_log
```
**Symbols:**

```
ffffffff81485550-ffffffff81485b3c: tomoyo_print_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
char *tomoyo_print_header(struct tomoyo_request_info *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/audit.c (ffffffff814db720)
Location: security/tomoyo/audit.c:150
Inline: False
Direct callers:
  - security/tomoyo/audit.c:tomoyo_init_log
```
**Symbols:**

```
ffffffff814db720-ffffffff814dbd15: tomoyo_print_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
char *tomoyo_print_header(struct tomoyo_request_info *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/audit.c (ffffffff814f8b90)
Location: security/tomoyo/audit.c:150
Inline: False
Direct callers:
  - security/tomoyo/audit.c:tomoyo_init_log
```
**Symbols:**

```
ffffffff814f8b90-ffffffff814f9168: tomoyo_print_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
char *tomoyo_print_header(struct tomoyo_request_info *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/audit.c (ffffffff814ff920)
Location: security/tomoyo/audit.c:150
Inline: False
Direct callers:
  - security/tomoyo/audit.c:tomoyo_init_log
```
**Symbols:**

```
ffffffff814ff920-ffffffff814ffeb8: tomoyo_print_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
char *tomoyo_print_header(struct tomoyo_request_info *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/audit.c (0)
Location: security/tomoyo/audit.c:150
Inline: False
Direct callers:
  - security/tomoyo/audit.c:tomoyo_init_log
```
**Symbols:**

```
ffffffff8155a990-ffffffff8155affa: tomoyo_print_header (STB_LOCAL)
ffffffff81cd562b-ffffffff81cd567b: tomoyo_print_header.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
char *tomoyo_print_header(struct tomoyo_request_info *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/audit.c (0)
Location: security/tomoyo/audit.c:150
Inline: False
Direct callers:
  - security/tomoyo/audit.c:tomoyo_init_log
```
**Symbols:**

```
ffffffff815f5750-ffffffff815f5e02: tomoyo_print_header (STB_LOCAL)
ffffffff81e8843a-ffffffff81e88486: tomoyo_print_header.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
char *tomoyo_print_header(struct tomoyo_request_info *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/audit.c (0)
Location: security/tomoyo/audit.c:150
Inline: False
Direct callers:
  - security/tomoyo/audit.c:tomoyo_init_log
```
**Symbols:**

```
ffffffff816a6250-ffffffff816a6902: tomoyo_print_header (STB_LOCAL)
ffffffff82073fe6-ffffffff82074032: tomoyo_print_header.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
char *tomoyo_print_header(struct tomoyo_request_info *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/audit.c (0)
Location: security/tomoyo/audit.c:150
Inline: False
Direct callers:
  - security/tomoyo/audit.c:tomoyo_init_log
```
**Symbols:**

```
ffffffff816dec30-ffffffff816df258: tomoyo_print_header (STB_LOCAL)
ffffffff820f3b7c-ffffffff820f3bc8: tomoyo_print_header.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
char *tomoyo_print_header(struct tomoyo_request_info *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/audit.c (0)
Location: security/tomoyo/audit.c:150
Inline: False
Direct callers:
  - security/tomoyo/audit.c:tomoyo_init_log
```
**Symbols:**

```
ffffffff8171b800-ffffffff8171be71: tomoyo_print_header (STB_LOCAL)
ffffffff821d0fb4-ffffffff821d100d: tomoyo_print_header.cold (STB_LOCAL)
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
char *tomoyo_print_header(struct tomoyo_request_info *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/audit.c (ffff800010577a80)
Location: security/tomoyo/audit.c:150
Inline: False
Direct callers:
  - security/tomoyo/audit.c:tomoyo_init_log
```
**Symbols:**

```
ffff800010577a80-ffff800010577f74: tomoyo_print_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
char *tomoyo_print_header(struct tomoyo_request_info *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/audit.c (c072a8c0)
Location: security/tomoyo/audit.c:150
Inline: False
Direct callers:
  - security/tomoyo/audit.c:tomoyo_init_log
```
**Symbols:**

```
c072a8c0-c072aee8: tomoyo_print_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
char *tomoyo_print_header(struct tomoyo_request_info *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/audit.c (c0000000006e11f0)
Location: security/tomoyo/audit.c:150
Inline: False
Direct callers:
  - security/tomoyo/audit.c:tomoyo_init_log
```
**Symbols:**

```
c0000000006e11f0-c0000000006e18e4: tomoyo_print_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
char *tomoyo_print_header(struct tomoyo_request_info *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/audit.c (ffffffe0003c9f3c)
Location: security/tomoyo/audit.c:150
Inline: False
Direct callers:
  - security/tomoyo/audit.c:tomoyo_init_log
```
**Symbols:**

```
ffffffe0003c9f3c-ffffffe0003ca3f0: tomoyo_print_header (STB_LOCAL)
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
char *tomoyo_print_header(struct tomoyo_request_info *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/audit.c (ffffffff8147db30)
Location: security/tomoyo/audit.c:150
Inline: False
Direct callers:
  - security/tomoyo/audit.c:tomoyo_init_log
```
**Symbols:**

```
ffffffff8147db30-ffffffff8147e11c: tomoyo_print_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
char *tomoyo_print_header(struct tomoyo_request_info *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/audit.c (ffffffff8146e550)
Location: security/tomoyo/audit.c:150
Inline: False
Direct callers:
  - security/tomoyo/audit.c:tomoyo_init_log
```
**Symbols:**

```
ffffffff8146e550-ffffffff8146eb3c: tomoyo_print_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
char *tomoyo_print_header(struct tomoyo_request_info *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/audit.c (ffffffff81479bd0)
Location: security/tomoyo/audit.c:150
Inline: False
Direct callers:
  - security/tomoyo/audit.c:tomoyo_init_log
```
**Symbols:**

```
ffffffff81479bd0-ffffffff8147a1bc: tomoyo_print_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
char *tomoyo_print_header(struct tomoyo_request_info *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/audit.c (ffffffff81491680)
Location: security/tomoyo/audit.c:150
Inline: False
Direct callers:
  - security/tomoyo/audit.c:tomoyo_init_log
```
**Symbols:**

```
ffffffff81491680-ffffffff81491c76: tomoyo_print_header (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
