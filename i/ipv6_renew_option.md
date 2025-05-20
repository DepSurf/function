# Function: <code>ipv6_renew_option</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int ipv6_renew_option(void *ohdr, struct ipv6_opt_hdr *newopt, int newoptlen, int inherit, struct ipv6_opt_hdr **hdr, char **p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff817f33d0)
Location: net/ipv6/exthdrs.c:736
Inline: True
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
```
**Symbols:**

```
ffffffff817f33d0-ffffffff817f34a8: ipv6_renew_option (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int ipv6_renew_option(void *ohdr, struct ipv6_opt_hdr *newopt, int newoptlen, int inherit, struct ipv6_opt_hdr **hdr, char **p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81862240)
Location: net/ipv6/exthdrs.c:763
Inline: True
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
```
**Symbols:**

```
ffffffff81862240-ffffffff81862335: ipv6_renew_option (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int ipv6_renew_option(void *ohdr, struct ipv6_opt_hdr *newopt, int newoptlen, int inherit, struct ipv6_opt_hdr **hdr, char **p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff818942d0)
Location: net/ipv6/exthdrs.c:979
Inline: True
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
```
**Symbols:**

```
ffffffff818942d0-ffffffff818943c5: ipv6_renew_option (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ipv6_renew_option(void *ohdr, struct ipv6_opt_hdr *newopt, int newoptlen, int inherit, struct ipv6_opt_hdr **hdr, char **p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff818ba4a0)
Location: net/ipv6/exthdrs.c:981
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
```
**Symbols:**

```
ffffffff818ba4a0-ffffffff818ba593: ipv6_renew_option (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ipv6_renew_option(void *ohdr, struct ipv6_opt_hdr *newopt, int newoptlen, int inherit, struct ipv6_opt_hdr **hdr, char **p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff8193d480)
Location: net/ipv6/exthdrs.c:1031
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
```
**Symbols:**

```
ffffffff8193d480-ffffffff8193d573: ipv6_renew_option (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ipv6_renew_option(int renewtype, struct ipv6_opt_hdr **dest, struct ipv6_opt_hdr *old, struct ipv6_opt_hdr *new, int newtype, char **p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81996260)
Location: net/ipv6/exthdrs.c:1018
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
```
**Symbols:**

```
ffffffff81996260-ffffffff819962ca: ipv6_renew_option (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ipv6_renew_option(int renewtype, struct ipv6_opt_hdr **dest, struct ipv6_opt_hdr *old, struct ipv6_opt_hdr *new, int newtype, char **p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff819ccb70)
Location: net/ipv6/exthdrs.c:1018
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
```
**Symbols:**

```
ffffffff819ccb70-ffffffff819ccbda: ipv6_renew_option (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ipv6_renew_option(int renewtype, struct ipv6_opt_hdr **dest, struct ipv6_opt_hdr *old, struct ipv6_opt_hdr *new, int newtype, char **p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81a3b630)
Location: net/ipv6/exthdrs.c:1014
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
```
**Symbols:**

```
ffffffff81a3b630-ffffffff81a3b699: ipv6_renew_option (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ipv6_renew_option(int renewtype, struct ipv6_opt_hdr **dest, struct ipv6_opt_hdr *old, struct ipv6_opt_hdr *new, int newtype, char **p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81a722b0)
Location: net/ipv6/exthdrs.c:1014
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
```
**Symbols:**

```
ffffffff81a722b0-ffffffff81a72319: ipv6_renew_option (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ipv6_renew_option(int renewtype, struct ipv6_opt_hdr **dest, struct ipv6_opt_hdr *old, struct ipv6_opt_hdr *new, int newtype, char **p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81b6bb20)
Location: net/ipv6/exthdrs.c:1211
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
```
**Symbols:**

```
ffffffff81b6bb20-ffffffff81b6bb8b: ipv6_renew_option (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ipv6_renew_option(int renewtype, struct ipv6_opt_hdr **dest, struct ipv6_opt_hdr *old, struct ipv6_opt_hdr *new, int newtype, char **p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81b7a590)
Location: net/ipv6/exthdrs.c:1206
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
```
**Symbols:**

```
ffffffff81b7a590-ffffffff81b7a5fb: ipv6_renew_option (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ipv6_renew_option(int renewtype, struct ipv6_opt_hdr **dest, struct ipv6_opt_hdr *old, struct ipv6_opt_hdr *new, int newtype, char **p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81b68fe0)
Location: net/ipv6/exthdrs.c:1206
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
```
**Symbols:**

```
ffffffff81b68fe0-ffffffff81b69047: ipv6_renew_option (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ipv6_renew_option(int renewtype, struct ipv6_opt_hdr **dest, struct ipv6_opt_hdr *old, struct ipv6_opt_hdr *new, int newtype, char **p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81c30a00)
Location: net/ipv6/exthdrs.c:1254
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
```
**Symbols:**

```
ffffffff81c30a00-ffffffff81c30a67: ipv6_renew_option (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ipv6_renew_option(int renewtype, struct ipv6_opt_hdr **dest, struct ipv6_opt_hdr *old, struct ipv6_opt_hdr *new, int newtype, char **p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81dce1c0)
Location: net/ipv6/exthdrs.c:1255
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
```
**Symbols:**

```
ffffffff81dce1c0-ffffffff81dce239: ipv6_renew_option (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ipv6_renew_option(int renewtype, struct ipv6_opt_hdr **dest, struct ipv6_opt_hdr *old, struct ipv6_opt_hdr *new, int newtype, char **p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81f9fd90)
Location: net/ipv6/exthdrs.c:1255
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
```
**Symbols:**

```
ffffffff81f9fd90-ffffffff81f9fe09: ipv6_renew_option (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ipv6_renew_option(int renewtype, struct ipv6_opt_hdr **dest, struct ipv6_opt_hdr *old, struct ipv6_opt_hdr *new, int newtype, char **p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff82000870)
Location: net/ipv6/exthdrs.c:1222
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
```
**Symbols:**

```
ffffffff82000870-ffffffff820008e9: ipv6_renew_option (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ipv6_renew_option(int renewtype, struct ipv6_opt_hdr **dest, struct ipv6_opt_hdr *old, struct ipv6_opt_hdr *new, int newtype, char **p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff820cf6b0)
Location: net/ipv6/exthdrs.c:1227
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
```
**Symbols:**

```
ffffffff820cf6b0-ffffffff820cf729: ipv6_renew_option (STB_LOCAL)
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
void ipv6_renew_option(int renewtype, struct ipv6_opt_hdr **dest, struct ipv6_opt_hdr *old, struct ipv6_opt_hdr *new, int newtype, char **p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffff800010d3ab28)
Location: net/ipv6/exthdrs.c:1014
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
```
**Symbols:**

```
ffff800010d3ab28-ffff800010d3abb0: ipv6_renew_option (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ipv6_renew_option(int renewtype, struct ipv6_opt_hdr **dest, struct ipv6_opt_hdr *old, struct ipv6_opt_hdr *new, int newtype, char **p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (c0e3d4f4)
Location: net/ipv6/exthdrs.c:1014
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
```
**Symbols:**

```
c0e3d4f4-c0e3d558: ipv6_renew_option (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ipv6_renew_option(int renewtype, struct ipv6_opt_hdr **dest, struct ipv6_opt_hdr *old, struct ipv6_opt_hdr *new, int newtype, char **p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (c000000000e6e250)
Location: net/ipv6/exthdrs.c:1014
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
```
**Symbols:**

```
c000000000e6e250-c000000000e6e2e8: ipv6_renew_option (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ipv6_renew_option(int renewtype, struct ipv6_opt_hdr **dest, struct ipv6_opt_hdr *old, struct ipv6_opt_hdr *new, int newtype, char **p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffe000877a8c)
Location: net/ipv6/exthdrs.c:1014
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
```
**Symbols:**

```
ffffffe000877a8c-ffffffe000877b02: ipv6_renew_option (STB_LOCAL)
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
void ipv6_renew_option(int renewtype, struct ipv6_opt_hdr **dest, struct ipv6_opt_hdr *old, struct ipv6_opt_hdr *new, int newtype, char **p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81a11940)
Location: net/ipv6/exthdrs.c:1014
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
```
**Symbols:**

```
ffffffff81a11940-ffffffff81a119a9: ipv6_renew_option (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ipv6_renew_option(int renewtype, struct ipv6_opt_hdr **dest, struct ipv6_opt_hdr *old, struct ipv6_opt_hdr *new, int newtype, char **p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff819ce700)
Location: net/ipv6/exthdrs.c:1014
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
```
**Symbols:**

```
ffffffff819ce700-ffffffff819ce769: ipv6_renew_option (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ipv6_renew_option(int renewtype, struct ipv6_opt_hdr **dest, struct ipv6_opt_hdr *old, struct ipv6_opt_hdr *new, int newtype, char **p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81a7c3c0)
Location: net/ipv6/exthdrs.c:1014
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
```
**Symbols:**

```
ffffffff81a7c3c0-ffffffff81a7c429: ipv6_renew_option (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ipv6_renew_option(int renewtype, struct ipv6_opt_hdr **dest, struct ipv6_opt_hdr *old, struct ipv6_opt_hdr *new, int newtype, char **p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81a88c10)
Location: net/ipv6/exthdrs.c:1014
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_renew_options
```
**Symbols:**

```
ffffffff81a88c10-ffffffff81a88c79: ipv6_renew_option (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int renewtype</code>
</li>
<li>
<b>Param added. </b>
<code>struct ipv6_opt_hdr **dest</code>
</li>
<li>
<b>Param added. </b>
<code>struct ipv6_opt_hdr *old</code>
</li>
<li>
<b>Param added. </b>
<code>struct ipv6_opt_hdr *new</code>
</li>
<li>
<b>Param added. </b>
<code>int newtype</code>
</li>
<li>
<b>Param removed. </b>
<code>void *ohdr</code>
</li>
<li>
<b>Param removed. </b>
<code>struct ipv6_opt_hdr *newopt</code>
</li>
<li>
<b>Param removed. </b>
<code>int newoptlen</code>
</li>
<li>
<b>Param removed. </b>
<code>int inherit</code>
</li>
<li>
<b>Param removed. </b>
<code>struct ipv6_opt_hdr **hdr</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
