# Function: <code>tcp_parse_fastopen_option</code>

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
In net/ipv4/tcp_input.c (ffffffff8176c70c)
Location: net/ipv4/tcp_input.c:3676
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_parse_options
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
In net/ipv4/tcp_input.c (ffffffff817d9c9c)
Location: net/ipv4/tcp_input.c:3734
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_parse_options
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void tcp_parse_fastopen_option(int len, const unsigned char *cookie, bool syn, struct tcp_fastopen_cookie *foc, bool exp_opt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff818081b0)
Location: net/ipv4/tcp_input.c:3750
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_parse_options
```
**Symbols:**

```
ffffffff818081b0-ffffffff81808277: tcp_parse_fastopen_option (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void tcp_parse_fastopen_option(int len, const unsigned char *cookie, bool syn, struct tcp_fastopen_cookie *foc, bool exp_opt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81828590)
Location: net/ipv4/tcp_input.c:3706
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_parse_options
```
**Symbols:**

```
ffffffff81828590-ffffffff81828648: tcp_parse_fastopen_option (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void tcp_parse_fastopen_option(int len, const unsigned char *cookie, bool syn, struct tcp_fastopen_cookie *foc, bool exp_opt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff818a79b0)
Location: net/ipv4/tcp_input.c:3655
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_parse_options
```
**Symbols:**

```
ffffffff818a79b0-ffffffff818a7a68: tcp_parse_fastopen_option (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void tcp_parse_fastopen_option(int len, const unsigned char *cookie, bool syn, struct tcp_fastopen_cookie *foc, bool exp_opt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff818fcbf0)
Location: net/ipv4/tcp_input.c:3739
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_parse_options
```
**Symbols:**

```
ffffffff818fcbf0-ffffffff818fcc8b: tcp_parse_fastopen_option (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void tcp_parse_fastopen_option(int len, const unsigned char *cookie, bool syn, struct tcp_fastopen_cookie *foc, bool exp_opt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8192ad60)
Location: net/ipv4/tcp_input.c:3738
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_parse_options
```
**Symbols:**

```
ffffffff8192ad60-ffffffff8192adfb: tcp_parse_fastopen_option (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void tcp_parse_fastopen_option(int len, const unsigned char *cookie, bool syn, struct tcp_fastopen_cookie *foc, bool exp_opt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8198e030)
Location: net/ipv4/tcp_input.c:3753
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_parse_options
```
**Symbols:**

```
ffffffff8198e030-ffffffff8198e090: tcp_parse_fastopen_option (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void tcp_parse_fastopen_option(int len, const unsigned char *cookie, bool syn, struct tcp_fastopen_cookie *foc, bool exp_opt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819c4c00)
Location: net/ipv4/tcp_input.c:3760
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_parse_options
```
**Symbols:**

```
ffffffff819c4c00-ffffffff819c4cbc: tcp_parse_fastopen_option (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void tcp_parse_fastopen_option(int len, const unsigned char *cookie, bool syn, struct tcp_fastopen_cookie *foc, bool exp_opt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ab0210)
Location: net/ipv4/tcp_input.c:3754
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_parse_options
```
**Symbols:**

```
ffffffff81ab0210-ffffffff81ab02c5: tcp_parse_fastopen_option (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void tcp_parse_fastopen_option(int len, const unsigned char *cookie, bool syn, struct tcp_fastopen_cookie *foc, bool exp_opt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81abb2a0)
Location: net/ipv4/tcp_input.c:3880
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_parse_options
```
**Symbols:**

```
ffffffff81abb2a0-ffffffff81abb355: tcp_parse_fastopen_option (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void tcp_parse_fastopen_option(int len, const unsigned char *cookie, bool syn, struct tcp_fastopen_cookie *foc, bool exp_opt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81aa6260)
Location: net/ipv4/tcp_input.c:3887
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_parse_options
```
**Symbols:**

```
ffffffff81aa6260-ffffffff81aa6308: tcp_parse_fastopen_option (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void tcp_parse_fastopen_option(int len, const unsigned char *cookie, bool syn, struct tcp_fastopen_cookie *foc, bool exp_opt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81b62650)
Location: net/ipv4/tcp_input.c:3921
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_parse_options
```
**Symbols:**

```
ffffffff81b62650-ffffffff81b626f8: tcp_parse_fastopen_option (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tcp_parse_fastopen_option(int len, const unsigned char *cookie, bool syn, struct tcp_fastopen_cookie *foc, bool exp_opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81cf0a30)
Location: net/ipv4/tcp_input.c:3939
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_parse_options
```
**Symbols:**

```
ffffffff81cf0a30-ffffffff81cf0af6: tcp_parse_fastopen_option (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tcp_parse_fastopen_option(int len, const unsigned char *cookie, bool syn, struct tcp_fastopen_cookie *foc, bool exp_opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81eb5930)
Location: net/ipv4/tcp_input.c:3952
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_parse_options
```
**Symbols:**

```
ffffffff81eb5930-ffffffff81eb59f6: tcp_parse_fastopen_option (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tcp_parse_fastopen_option(int len, const unsigned char *cookie, bool syn, struct tcp_fastopen_cookie *foc, bool exp_opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81f13d60)
Location: net/ipv4/tcp_input.c:3957
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_parse_options
```
**Symbols:**

```
ffffffff81f13d60-ffffffff81f13e2c: tcp_parse_fastopen_option (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tcp_parse_fastopen_option(int len, const unsigned char *cookie, bool syn, struct tcp_fastopen_cookie *foc, bool exp_opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81fd8240)
Location: net/ipv4/tcp_input.c:4035
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_parse_options
```
**Symbols:**

```
ffffffff81fd8240-ffffffff81fd830c: tcp_parse_fastopen_option (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void tcp_parse_fastopen_option(int len, const unsigned char *cookie, bool syn, struct tcp_fastopen_cookie *foc, bool exp_opt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffff800010c77578)
Location: net/ipv4/tcp_input.c:3760
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_parse_options
```
**Symbols:**

```
ffff800010c77578-ffff800010c77604: tcp_parse_fastopen_option (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void tcp_parse_fastopen_option(int len, const unsigned char *cookie, bool syn, struct tcp_fastopen_cookie *foc, bool exp_opt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c0d85dc4)
Location: net/ipv4/tcp_input.c:3760
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_parse_options
```
**Symbols:**

```
c0d85dc4-c0d85e34: tcp_parse_fastopen_option (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void tcp_parse_fastopen_option(int len, const unsigned char *cookie, bool syn, struct tcp_fastopen_cookie *foc, bool exp_opt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c000000000d7fac0)
Location: net/ipv4/tcp_input.c:3760
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_parse_options
```
**Symbols:**

```
c000000000d7fac0-c000000000d7fb60: tcp_parse_fastopen_option (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void tcp_parse_fastopen_option(int len, const unsigned char *cookie, bool syn, struct tcp_fastopen_cookie *foc, bool exp_opt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffe0007dac70)
Location: net/ipv4/tcp_input.c:3760
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_parse_options
```
**Symbols:**

```
ffffffe0007dac70-ffffffe0007dace0: tcp_parse_fastopen_option (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void tcp_parse_fastopen_option(int len, const unsigned char *cookie, bool syn, struct tcp_fastopen_cookie *foc, bool exp_opt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81964a70)
Location: net/ipv4/tcp_input.c:3760
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_parse_options
```
**Symbols:**

```
ffffffff81964a70-ffffffff81964b2c: tcp_parse_fastopen_option (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void tcp_parse_fastopen_option(int len, const unsigned char *cookie, bool syn, struct tcp_fastopen_cookie *foc, bool exp_opt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8191e560)
Location: net/ipv4/tcp_input.c:3760
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_parse_options
```
**Symbols:**

```
ffffffff8191e560-ffffffff8191e61c: tcp_parse_fastopen_option (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void tcp_parse_fastopen_option(int len, const unsigned char *cookie, bool syn, struct tcp_fastopen_cookie *foc, bool exp_opt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819cf240)
Location: net/ipv4/tcp_input.c:3760
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_parse_options
```
**Symbols:**

```
ffffffff819cf240-ffffffff819cf2fc: tcp_parse_fastopen_option (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void tcp_parse_fastopen_option(int len, const unsigned char *cookie, bool syn, struct tcp_fastopen_cookie *foc, bool exp_opt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819d8dd0)
Location: net/ipv4/tcp_input.c:3760
Inline: True
Direct callers:
  - net/ipv4/tcp_input.c:tcp_parse_options
```
**Symbols:**

```
ffffffff819d8dd0-ffffffff819d8e8c: tcp_parse_fastopen_option (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
