# Function: <code>devlink_fmsg_put_value</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int devlink_fmsg_put_value(struct devlink_fmsg *fmsg, const void *value, u16 value_len, u8 value_nla_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8194f160)
Location: net/core/devlink.c:4205
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_fmsg_string_put
```
**Symbols:**

```
ffffffff8194f160-ffffffff8194f234: devlink_fmsg_put_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int devlink_fmsg_put_value(struct devlink_fmsg *fmsg, const void *value, u16 value_len, u8 value_nla_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81985ed0)
Location: net/core/devlink.c:4259
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_fmsg_string_put
```
**Symbols:**

```
ffffffff81985ed0-ffffffff81985fa4: devlink_fmsg_put_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_put_value(struct devlink_fmsg *fmsg, const void *value, u16 value_len, u8 value_nla_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a55909)
Location: net/core/devlink.c:4745
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_fmsg_string_put
```
**Symbols:**

```
ffffffff81a55af0-ffffffff81a55bc9: devlink_fmsg_put_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_put_value(struct devlink_fmsg *fmsg, const void *value, u16 value_len, u8 value_nla_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a5ccf2)
Location: net/core/devlink.c:5434
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_fmsg_string_put
```
**Symbols:**

```
ffffffff81a5ced0-ffffffff81a5cfa9: devlink_fmsg_put_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int devlink_fmsg_put_value(struct devlink_fmsg *fmsg, const void *value, u16 value_len, u8 value_nla_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a3dc20)
Location: net/core/devlink.c:5637
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_fmsg_string_put
```
**Symbols:**

```
ffffffff81a3dc20-ffffffff81a3dcf9: devlink_fmsg_put_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int devlink_fmsg_put_value(struct devlink_fmsg *fmsg, const void *value, u16 value_len, u8 value_nla_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81af4170)
Location: net/core/devlink.c:6250
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_fmsg_string_put
```
**Symbols:**

```
ffffffff81af4170-ffffffff81af4249: devlink_fmsg_put_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int devlink_fmsg_put_value(struct devlink_fmsg *fmsg, const void *value, u16 value_len, u8 value_nla_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c784c0)
Location: net/core/devlink.c:6745
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_fmsg_string_put
```
**Symbols:**

```
ffffffff81c784c0-ffffffff81c785ac: devlink_fmsg_put_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int devlink_fmsg_put_value(struct devlink_fmsg *fmsg, const void *value, u16 value_len, u8 value_nla_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e31780)
Location: net/core/devlink.c:7300
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_fmsg_string_put
```
**Symbols:**

```
ffffffff81e31780-ffffffff81e3186c: devlink_fmsg_put_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int devlink_fmsg_put_value(struct devlink_fmsg *fmsg, const void *value, u16 value_len, u8 value_nla_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/health.c (ffffffff82046480)
Location: net/devlink/health.c:817
Inline: False
Direct callers:
  - net/devlink/health.c:devlink_fmsg_string_put
```
**Symbols:**

```
ffffffff82046480-ffffffff8204656c: devlink_fmsg_put_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void devlink_fmsg_put_value(struct devlink_fmsg *fmsg, const void *value, u16 value_len, u8 value_nla_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/health.c (ffffffff82112070)
Location: net/devlink/health.c:797
Inline: False
Direct callers:
  - net/devlink/health.c:devlink_fmsg_binary_pair_put
  - net/devlink/health.c:devlink_fmsg_u64_pair_put
  - net/devlink/health.c:devlink_fmsg_u32_pair_put
  - net/devlink/health.c:devlink_fmsg_u8_pair_put
  - net/devlink/health.c:devlink_fmsg_bool_pair_put
  - net/devlink/health.c:devlink_fmsg_string_put
```
**Symbols:**

```
ffffffff82112070-ffffffff82112191: devlink_fmsg_put_value (STB_LOCAL)
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
int devlink_fmsg_put_value(struct devlink_fmsg *fmsg, const void *value, u16 value_len, u8 value_nla_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c25700)
Location: net/core/devlink.c:4259
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_fmsg_string_put
```
**Symbols:**

```
ffff800010c25700-ffff800010c257a4: devlink_fmsg_put_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int devlink_fmsg_put_value(struct devlink_fmsg *fmsg, const void *value, u16 value_len, u8 value_nla_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d406f0)
Location: net/core/devlink.c:4259
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_fmsg_string_put
```
**Symbols:**

```
c0d406f0-c0d40780: devlink_fmsg_put_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int devlink_fmsg_put_value(struct devlink_fmsg *fmsg, const void *value, u16 value_len, u8 value_nla_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d25bf0)
Location: net/core/devlink.c:4259
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_fmsg_string_put
```
**Symbols:**

```
c000000000d25bf0-c000000000d25cc0: devlink_fmsg_put_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int devlink_fmsg_put_value(struct devlink_fmsg *fmsg, const void *value, u16 value_len, u8 value_nla_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe00079f1fe)
Location: net/core/devlink.c:4259
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_fmsg_string_put
```
**Symbols:**

```
ffffffe00079f1fe-ffffffe00079f28a: devlink_fmsg_put_value (STB_LOCAL)
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
int devlink_fmsg_put_value(struct devlink_fmsg *fmsg, const void *value, u16 value_len, u8 value_nla_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81925d40)
Location: net/core/devlink.c:4259
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_fmsg_string_put
```
**Symbols:**

```
ffffffff81925d40-ffffffff81925e14: devlink_fmsg_put_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int devlink_fmsg_put_value(struct devlink_fmsg *fmsg, const void *value, u16 value_len, u8 value_nla_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818dfaf0)
Location: net/core/devlink.c:4259
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_fmsg_string_put
```
**Symbols:**

```
ffffffff818dfaf0-ffffffff818dfbc4: devlink_fmsg_put_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int devlink_fmsg_put_value(struct devlink_fmsg *fmsg, const void *value, u16 value_len, u8 value_nla_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81976ed0)
Location: net/core/devlink.c:4259
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_fmsg_string_put
```
**Symbols:**

```
ffffffff81976ed0-ffffffff81976fa4: devlink_fmsg_put_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int devlink_fmsg_put_value(struct devlink_fmsg *fmsg, const void *value, u16 value_len, u8 value_nla_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff819993c0)
Location: net/core/devlink.c:4259
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_fmsg_string_put
```
**Symbols:**

```
ffffffff819993c0-ffffffff81999494: devlink_fmsg_put_value (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
