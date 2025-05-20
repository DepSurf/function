# Function: <code>tomoyo_print_condition</code>

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
In security/tomoyo/common.c (ffffffff81369539)
Location: security/tomoyo/common.c:1200
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_print_entry
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
In security/tomoyo/common.c (ffffffff8139f452)
Location: security/tomoyo/common.c:1200
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_print_entry
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
In security/tomoyo/common.c (ffffffff813b5fef)
Location: security/tomoyo/common.c:1200
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_print_entry
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
In security/tomoyo/common.c (ffffffff813cc4ba)
Location: security/tomoyo/common.c:1200
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_print_entry
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
In security/tomoyo/common.c (ffffffff813f295a)
Location: security/tomoyo/common.c:1201
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_print_entry
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
In security/tomoyo/common.c (ffffffff8142377c)
Location: security/tomoyo/common.c:1201
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_print_entry
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
In security/tomoyo/common.c (ffffffff81440292)
Location: security/tomoyo/common.c:1201
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_print_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool tomoyo_print_condition(struct tomoyo_io_buffer *head, const struct tomoyo_condition *cond);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff8146dd20)
Location: security/tomoyo/common.c:1230
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_print_entry
```
**Symbols:**

```
ffffffff8146dd20-ffffffff8146e165: tomoyo_print_condition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool tomoyo_print_condition(struct tomoyo_io_buffer *head, const struct tomoyo_condition *cond);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff81487b20)
Location: security/tomoyo/common.c:1232
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_print_entry
```
**Symbols:**

```
ffffffff81487b20-ffffffff81487f65: tomoyo_print_condition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool tomoyo_print_condition(struct tomoyo_io_buffer *head, const struct tomoyo_condition *cond);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff814df4e0)
Location: security/tomoyo/common.c:1232
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_print_entry
```
**Symbols:**

```
ffffffff814df4e0-ffffffff814dfce8: tomoyo_print_condition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool tomoyo_print_condition(struct tomoyo_io_buffer *head, const struct tomoyo_condition *cond);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff814fc910)
Location: security/tomoyo/common.c:1232
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_print_entry
```
**Symbols:**

```
ffffffff814fc910-ffffffff814fd118: tomoyo_print_condition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool tomoyo_print_condition(struct tomoyo_io_buffer *head, const struct tomoyo_condition *cond);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff815034e0)
Location: security/tomoyo/common.c:1232
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_print_entry
```
**Symbols:**

```
ffffffff815034e0-ffffffff81503cdf: tomoyo_print_condition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool tomoyo_print_condition(struct tomoyo_io_buffer *head, const struct tomoyo_condition *cond);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/common.c (0)
Location: security/tomoyo/common.c:1232
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_print_entry
```
**Symbols:**

```
ffffffff8155f140-ffffffff8155fd1b: tomoyo_print_condition (STB_LOCAL)
ffffffff81cd58df-ffffffff81cd591e: tomoyo_print_condition.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool tomoyo_print_condition(struct tomoyo_io_buffer *head, const struct tomoyo_condition *cond);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/common.c (0)
Location: security/tomoyo/common.c:1223
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_print_entry
```
**Symbols:**

```
ffffffff815fa2d0-ffffffff815faecb: tomoyo_print_condition (STB_LOCAL)
ffffffff81e886e9-ffffffff81e88728: tomoyo_print_condition.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool tomoyo_print_condition(struct tomoyo_io_buffer *head, const struct tomoyo_condition *cond);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/common.c (0)
Location: security/tomoyo/common.c:1223
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_print_entry
```
**Symbols:**

```
ffffffff816ab000-ffffffff816abbfb: tomoyo_print_condition (STB_LOCAL)
ffffffff82074278-ffffffff820742b7: tomoyo_print_condition.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool tomoyo_print_condition(struct tomoyo_io_buffer *head, const struct tomoyo_condition *cond);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/common.c (0)
Location: security/tomoyo/common.c:1223
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_print_entry
```
**Symbols:**

```
ffffffff816e3a40-ffffffff816e4650: tomoyo_print_condition (STB_LOCAL)
ffffffff820f3e01-ffffffff820f3e40: tomoyo_print_condition.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool tomoyo_print_condition(struct tomoyo_io_buffer *head, const struct tomoyo_condition *cond);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/common.c (0)
Location: security/tomoyo/common.c:1224
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_print_entry
```
**Symbols:**

```
ffffffff817206f0-ffffffff81721300: tomoyo_print_condition (STB_LOCAL)
ffffffff821d1246-ffffffff821d1285: tomoyo_print_condition.cold (STB_LOCAL)
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
bool tomoyo_print_condition(struct tomoyo_io_buffer *head, const struct tomoyo_condition *cond);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffff80001057a4a0)
Location: security/tomoyo/common.c:1232
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_print_entry
```
**Symbols:**

```
ffff80001057a4a0-ffff80001057a938: tomoyo_print_condition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool tomoyo_print_condition(struct tomoyo_io_buffer *head, const struct tomoyo_condition *cond);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (c072d9d0)
Location: security/tomoyo/common.c:1232
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_print_entry
```
**Symbols:**

```
c072d9d0-c072de48: tomoyo_print_condition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool tomoyo_print_condition(struct tomoyo_io_buffer *head, const struct tomoyo_condition *cond);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (c0000000006e4cd0)
Location: security/tomoyo/common.c:1232
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_print_entry
```
**Symbols:**

```
c0000000006e4cd0-c0000000006e52fc: tomoyo_print_condition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool tomoyo_print_condition(struct tomoyo_io_buffer *head, const struct tomoyo_condition *cond);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffe0003cc36e)
Location: security/tomoyo/common.c:1232
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_print_entry
```
**Symbols:**

```
ffffffe0003cc36e-ffffffe0003cc786: tomoyo_print_condition (STB_LOCAL)
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
bool tomoyo_print_condition(struct tomoyo_io_buffer *head, const struct tomoyo_condition *cond);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff81480100)
Location: security/tomoyo/common.c:1232
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_print_entry
```
**Symbols:**

```
ffffffff81480100-ffffffff81480545: tomoyo_print_condition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool tomoyo_print_condition(struct tomoyo_io_buffer *head, const struct tomoyo_condition *cond);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff81470b20)
Location: security/tomoyo/common.c:1232
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_print_entry
```
**Symbols:**

```
ffffffff81470b20-ffffffff81470f65: tomoyo_print_condition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool tomoyo_print_condition(struct tomoyo_io_buffer *head, const struct tomoyo_condition *cond);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff8147c1a0)
Location: security/tomoyo/common.c:1232
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_print_entry
```
**Symbols:**

```
ffffffff8147c1a0-ffffffff8147c5e5: tomoyo_print_condition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool tomoyo_print_condition(struct tomoyo_io_buffer *head, const struct tomoyo_condition *cond);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff814942b0)
Location: security/tomoyo/common.c:1232
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_print_entry
```
**Symbols:**

```
ffffffff814942b0-ffffffff814946f5: tomoyo_print_condition (STB_LOCAL)
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
