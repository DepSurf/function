# Function: <code>__nla_validate_parse</code>

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
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int __nla_validate_parse(const struct nlattr *head, int len, int maxtype, const struct nla_policy *policy, unsigned int validate, struct netlink_ext_ack *extack, struct nlattr **tb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/nlattr.c (0)
Location: lib/nlattr.c:357
Inline: False
Direct callers:
  - lib/nlattr.c:__nla_parse
  - lib/nlattr.c:validate_nla
```
**Symbols:**

```
ffffffff81534870-ffffffff815349a8: __nla_validate_parse (STB_LOCAL)
ffffffff81534e5f-ffffffff81534e83: __nla_validate_parse.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int __nla_validate_parse(const struct nlattr *head, int len, int maxtype, const struct nla_policy *policy, unsigned int validate, struct netlink_ext_ack *extack, struct nlattr **tb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/nlattr.c (0)
Location: lib/nlattr.c:357
Inline: False
Direct callers:
  - lib/nlattr.c:__nla_parse
  - lib/nlattr.c:validate_nla
```
**Symbols:**

```
ffffffff815556a0-ffffffff815557d8: __nla_validate_parse (STB_LOCAL)
ffffffff81555c77-ffffffff81555c9b: __nla_validate_parse.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int __nla_validate_parse(const struct nlattr *head, int len, int maxtype, const struct nla_policy *policy, unsigned int validate, struct netlink_ext_ack *extack, struct nlattr **tb, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/nlattr.c (0)
Location: lib/nlattr.c:503
Inline: False
Direct callers:
  - lib/nlattr.c:__nla_parse
  - lib/nlattr.c:__nla_validate
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
```
**Symbols:**

```
ffffffff815df220-ffffffff815df379: __nla_validate_parse (STB_LOCAL)
ffffffff815df3e9-ffffffff815df40d: __nla_validate_parse.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int __nla_validate_parse(const struct nlattr *head, int len, int maxtype, const struct nla_policy *policy, unsigned int validate, struct netlink_ext_ack *extack, struct nlattr **tb, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/nlattr.c (0)
Location: lib/nlattr.c:558
Inline: False
Direct callers:
  - lib/nlattr.c:__nla_parse
  - lib/nlattr.c:__nla_validate
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
```
**Symbols:**

```
ffffffff815fca20-ffffffff815fcb84: __nla_validate_parse (STB_LOCAL)
ffffffff81bf464c-ffffffff81bf4670: __nla_validate_parse.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int __nla_validate_parse(const struct nlattr *head, int len, int maxtype, const struct nla_policy *policy, unsigned int validate, struct netlink_ext_ack *extack, struct nlattr **tb, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/nlattr.c (0)
Location: lib/nlattr.c:558
Inline: False
Direct callers:
  - lib/nlattr.c:__nla_parse
  - lib/nlattr.c:__nla_validate
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
```
**Symbols:**

```
ffffffff815df760-ffffffff815df8f8: __nla_validate_parse (STB_LOCAL)
ffffffff81be653f-ffffffff81be6563: __nla_validate_parse.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __nla_validate_parse(const struct nlattr *head, int len, int maxtype, const struct nla_policy *policy, unsigned int validate, struct netlink_ext_ack *extack, struct nlattr **tb, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/nlattr.c (0)
Location: lib/nlattr.c:558
Inline: False
Direct callers:
  - lib/nlattr.c:__nla_parse
  - lib/nlattr.c:__nla_validate
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
```
**Symbols:**

```
ffffffff8164b3a0-ffffffff8164b538: __nla_validate_parse (STB_LOCAL)
ffffffff81cdddbc-ffffffff81cddde0: __nla_validate_parse.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __nla_validate_parse(const struct nlattr *head, int len, int maxtype, const struct nla_policy *policy, unsigned int validate, struct netlink_ext_ack *extack, struct nlattr **tb, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/nlattr.c (0)
Location: lib/nlattr.c:558
Inline: False
Direct callers:
  - lib/nlattr.c:__nla_parse
  - lib/nlattr.c:__nla_validate
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
```
**Symbols:**

```
ffffffff81761de0-ffffffff81761f69: __nla_validate_parse (STB_LOCAL)
ffffffff81ea4136-ffffffff81ea4159: __nla_validate_parse.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __nla_validate_parse(const struct nlattr *head, int len, int maxtype, const struct nla_policy *policy, unsigned int validate, struct netlink_ext_ack *extack, struct nlattr **tb, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81890b40)
Location: lib/nlattr.c:572
Inline: False
Direct callers:
  - lib/nlattr.c:__nla_parse
  - lib/nlattr.c:__nla_validate
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
```
**Symbols:**

```
ffffffff81890b40-ffffffff81890d19: __nla_validate_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __nla_validate_parse(const struct nlattr *head, int len, int maxtype, const struct nla_policy *policy, unsigned int validate, struct netlink_ext_ack *extack, struct nlattr **tb, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff818d2f40)
Location: lib/nlattr.c:572
Inline: False
Direct callers:
  - lib/nlattr.c:__nla_parse
  - lib/nlattr.c:__nla_validate
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
```
**Symbols:**

```
ffffffff818d2f40-ffffffff818d3111: __nla_validate_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __nla_validate_parse(const struct nlattr *head, int len, int maxtype, const struct nla_policy *policy, unsigned int validate, struct netlink_ext_ack *extack, struct nlattr **tb, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81925020)
Location: lib/nlattr.c:604
Inline: False
Direct callers:
  - lib/nlattr.c:__nla_parse
  - lib/nlattr.c:__nla_validate
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
```
**Symbols:**

```
ffffffff81925020-ffffffff819251f1: __nla_validate_parse (STB_LOCAL)
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
int __nla_validate_parse(const struct nlattr *head, int len, int maxtype, const struct nla_policy *policy, unsigned int validate, struct netlink_ext_ack *extack, struct nlattr **tb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffff800010661a80)
Location: lib/nlattr.c:357
Inline: False
Direct callers:
  - lib/nlattr.c:__nla_parse
  - lib/nlattr.c:validate_nla
```
**Symbols:**

```
ffff800010661a80-ffff800010661c00: __nla_validate_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __nla_validate_parse(const struct nlattr *head, int len, int maxtype, const struct nla_policy *policy, unsigned int validate, struct netlink_ext_ack *extack, struct nlattr **tb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (c080ab4c)
Location: lib/nlattr.c:357
Inline: False
Direct callers:
  - lib/nlattr.c:__nla_parse
  - lib/nlattr.c:validate_nla
```
**Symbols:**

```
c080ab4c-c080acd4: __nla_validate_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __nla_validate_parse(const struct nlattr *head, int len, int maxtype, const struct nla_policy *policy, unsigned int validate, struct netlink_ext_ack *extack, struct nlattr **tb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (c000000000815b80)
Location: lib/nlattr.c:357
Inline: False
Direct callers:
  - lib/nlattr.c:__nla_parse
  - lib/nlattr.c:validate_nla
```
**Symbols:**

```
c000000000815b80-c000000000815dd8: __nla_validate_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __nla_validate_parse(const struct nlattr *head, int len, int maxtype, const struct nla_policy *policy, unsigned int validate, struct netlink_ext_ack *extack, struct nlattr **tb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffe00048e3c8)
Location: lib/nlattr.c:357
Inline: False
Direct callers:
  - lib/nlattr.c:__nla_parse
  - lib/nlattr.c:validate_nla
```
**Symbols:**

```
ffffffe00048e3c8-ffffffe00048e502: __nla_validate_parse (STB_LOCAL)
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
int __nla_validate_parse(const struct nlattr *head, int len, int maxtype, const struct nla_policy *policy, unsigned int validate, struct netlink_ext_ack *extack, struct nlattr **tb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/nlattr.c (0)
Location: lib/nlattr.c:357
Inline: False
Direct callers:
  - lib/nlattr.c:__nla_parse
  - lib/nlattr.c:validate_nla
```
**Symbols:**

```
ffffffff8154dc80-ffffffff8154ddb8: __nla_validate_parse (STB_LOCAL)
ffffffff8154e257-ffffffff8154e27b: __nla_validate_parse.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int __nla_validate_parse(const struct nlattr *head, int len, int maxtype, const struct nla_policy *policy, unsigned int validate, struct netlink_ext_ack *extack, struct nlattr **tb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/nlattr.c (0)
Location: lib/nlattr.c:357
Inline: False
Direct callers:
  - lib/nlattr.c:__nla_parse
  - lib/nlattr.c:validate_nla
```
**Symbols:**

```
ffffffff8153df60-ffffffff8153e098: __nla_validate_parse (STB_LOCAL)
ffffffff8153e537-ffffffff8153e55b: __nla_validate_parse.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int __nla_validate_parse(const struct nlattr *head, int len, int maxtype, const struct nla_policy *policy, unsigned int validate, struct netlink_ext_ack *extack, struct nlattr **tb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/nlattr.c (0)
Location: lib/nlattr.c:357
Inline: False
Direct callers:
  - lib/nlattr.c:__nla_parse
  - lib/nlattr.c:validate_nla
```
**Symbols:**

```
ffffffff815499c0-ffffffff81549af8: __nla_validate_parse (STB_LOCAL)
ffffffff81549f97-ffffffff81549fbb: __nla_validate_parse.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int __nla_validate_parse(const struct nlattr *head, int len, int maxtype, const struct nla_policy *policy, unsigned int validate, struct netlink_ext_ack *extack, struct nlattr **tb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/nlattr.c (0)
Location: lib/nlattr.c:357
Inline: False
Direct callers:
  - lib/nlattr.c:__nla_parse
  - lib/nlattr.c:validate_nla
```
**Symbols:**

```
ffffffff81563810-ffffffff81563948: __nla_validate_parse (STB_LOCAL)
ffffffff81563de7-ffffffff81563e0b: __nla_validate_parse.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int depth</code>
</li>
</ul>
</details>
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
