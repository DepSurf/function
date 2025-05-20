# Function: <code>validate_nla</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int validate_nla(const struct nlattr *nla, int maxtype, const struct nla_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff814155e0)
Location: lib/nlattr.c:30
Inline: False
Direct callers:
  - lib/nlattr.c:nla_validate
  - lib/nlattr.c:nla_parse
```
**Symbols:**

```
ffffffff814155e0-ffffffff81415775: validate_nla (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int validate_nla(const struct nlattr *nla, int maxtype, const struct nla_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8145d300)
Location: lib/nlattr.c:30
Inline: False
Direct callers:
  - lib/nlattr.c:nla_parse
  - lib/nlattr.c:nla_validate
```
**Symbols:**

```
ffffffff8145d300-ffffffff8145d49d: validate_nla (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int validate_nla(const struct nlattr *nla, int maxtype, const struct nla_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8147bde0)
Location: lib/nlattr.c:30
Inline: False
Direct callers:
  - lib/nlattr.c:nla_parse
  - lib/nlattr.c:nla_validate
```
**Symbols:**

```
ffffffff8147bde0-ffffffff8147bf7c: validate_nla (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int validate_nla(const struct nlattr *nla, int maxtype, const struct nla_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81485110)
Location: lib/nlattr.c:30
Inline: False
Direct callers:
  - lib/nlattr.c:nla_parse
  - lib/nlattr.c:nla_validate
```
**Symbols:**

```
ffffffff81485110-ffffffff8148527a: validate_nla (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int validate_nla(const struct nlattr *nla, int maxtype, const struct nla_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff814c1180)
Location: lib/nlattr.c:71
Inline: False
Direct callers:
  - lib/nlattr.c:nla_parse
  - lib/nlattr.c:nla_validate
```
**Symbols:**

```
ffffffff814c1180-ffffffff814c1382: validate_nla (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int validate_nla(const struct nlattr *nla, int maxtype, const struct nla_policy *policy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/nlattr.c (0)
Location: lib/nlattr.c:71
Inline: False
```
**Symbols:**

```
ffffffff814f2050-ffffffff814f224f: validate_nla (STB_LOCAL)
ffffffff814f28e5-ffffffff814f290f: validate_nla.cold.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int validate_nla(const struct nlattr *nla, int maxtype, const struct nla_policy *policy, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/nlattr.c (0)
Location: lib/nlattr.c:156
Inline: False
```
**Symbols:**

```
ffffffff81506410-ffffffff81506987: validate_nla (STB_LOCAL)
ffffffff81506c12-ffffffff81506c44: validate_nla.cold.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int validate_nla(const struct nlattr *nla, int maxtype, const struct nla_policy *policy, unsigned int validate, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/nlattr.c (0)
Location: lib/nlattr.c:157
Inline: False
Direct callers:
  - lib/nlattr.c:__nla_validate_parse
```
**Symbols:**

```
ffffffff81534230-ffffffff81534868: validate_nla (STB_LOCAL)
ffffffff81534e15-ffffffff81534e5f: validate_nla.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int validate_nla(const struct nlattr *nla, int maxtype, const struct nla_policy *policy, unsigned int validate, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/nlattr.c (0)
Location: lib/nlattr.c:157
Inline: False
Direct callers:
  - lib/nlattr.c:__nla_validate_parse
```
**Symbols:**

```
ffffffff81555070-ffffffff8155569b: validate_nla (STB_LOCAL)
ffffffff81555c45-ffffffff81555c77: validate_nla.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int validate_nla(const struct nlattr *nla, int maxtype, const struct nla_policy *policy, unsigned int validate, struct netlink_ext_ack *extack, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/nlattr.c (0)
Location: lib/nlattr.c:297
Inline: False
Direct callers:
  - lib/nlattr.c:__nla_validate_parse
```
**Symbols:**

```
ffffffff815ded10-ffffffff815df211: validate_nla (STB_LOCAL)
ffffffff815df3b7-ffffffff815df3e9: validate_nla.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int validate_nla(const struct nlattr *nla, int maxtype, const struct nla_policy *policy, unsigned int validate, struct netlink_ext_ack *extack, unsigned int depth);
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
  - lib/nlattr.c:__nla_validate_parse
```
**Symbols:**

```
ffffffff815fc470-ffffffff815fca11: validate_nla (STB_LOCAL)
ffffffff81bf461a-ffffffff81bf464c: validate_nla.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int validate_nla(const struct nlattr *nla, int maxtype, const struct nla_policy *policy, unsigned int validate, struct netlink_ext_ack *extack, unsigned int depth);
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
  - lib/nlattr.c:__nla_validate_parse
```
**Symbols:**

```
ffffffff815df110-ffffffff815df758: validate_nla (STB_LOCAL)
ffffffff81be6510-ffffffff81be653f: validate_nla.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int validate_nla(const struct nlattr *nla, int maxtype, const struct nla_policy *policy, unsigned int validate, struct netlink_ext_ack *extack, unsigned int depth);
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
  - lib/nlattr.c:__nla_validate_parse
```
**Symbols:**

```
ffffffff8164ac90-ffffffff8164b394: validate_nla (STB_LOCAL)
ffffffff81cddd85-ffffffff81cdddbc: validate_nla.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int validate_nla(const struct nlattr *nla, int maxtype, const struct nla_policy *policy, unsigned int validate, struct netlink_ext_ack *extack, unsigned int depth);
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
  - lib/nlattr.c:__nla_validate_parse
```
**Symbols:**

```
ffffffff81761650-ffffffff81761dd6: validate_nla (STB_LOCAL)
ffffffff81ea40f4-ffffffff81ea4136: validate_nla.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int validate_nla(const struct nlattr *nla, int maxtype, const struct nla_policy *policy, unsigned int validate, struct netlink_ext_ack *extack, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81890260)
Location: lib/nlattr.c:370
Inline: False
Direct callers:
  - lib/nlattr.c:__nla_validate_parse
```
**Symbols:**

```
ffffffff81890260-ffffffff81890b2d: validate_nla (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int validate_nla(const struct nlattr *nla, int maxtype, const struct nla_policy *policy, unsigned int validate, struct netlink_ext_ack *extack, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff818d26c0)
Location: lib/nlattr.c:370
Inline: False
Direct callers:
  - lib/nlattr.c:__nla_validate_parse
```
**Symbols:**

```
ffffffff818d26c0-ffffffff818d2f22: validate_nla (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int validate_nla(const struct nlattr *nla, int maxtype, const struct nla_policy *policy, unsigned int validate, struct netlink_ext_ack *extack, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff819246a0)
Location: lib/nlattr.c:393
Inline: False
Direct callers:
  - lib/nlattr.c:__nla_validate_parse
```
**Symbols:**

```
ffffffff819246a0-ffffffff81925007: validate_nla (STB_LOCAL)
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
int validate_nla(const struct nlattr *nla, int maxtype, const struct nla_policy *policy, unsigned int validate, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffff800010661438)
Location: lib/nlattr.c:157
Inline: False
Direct callers:
  - lib/nlattr.c:__nla_validate_parse
```
**Symbols:**

```
ffff800010661438-ffff800010661a7c: validate_nla (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int validate_nla(const struct nlattr *nla, int maxtype, const struct nla_policy *policy, unsigned int validate, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (c080a440)
Location: lib/nlattr.c:157
Inline: False
Direct callers:
  - lib/nlattr.c:__nla_validate_parse
```
**Symbols:**

```
c080a440-c080ab4c: validate_nla (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int validate_nla(const struct nlattr *nla, int maxtype, const struct nla_policy *policy, unsigned int validate, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (c000000000815220)
Location: lib/nlattr.c:157
Inline: False
Direct callers:
  - lib/nlattr.c:__nla_validate_parse
```
**Symbols:**

```
c000000000815220-c000000000815b74: validate_nla (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int validate_nla(const struct nlattr *nla, int maxtype, const struct nla_policy *policy, unsigned int validate, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffe00048df1c)
Location: lib/nlattr.c:157
Inline: False
Direct callers:
  - lib/nlattr.c:__nla_validate_parse
```
**Symbols:**

```
ffffffe00048df1c-ffffffe00048e3c8: validate_nla (STB_LOCAL)
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
int validate_nla(const struct nlattr *nla, int maxtype, const struct nla_policy *policy, unsigned int validate, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/nlattr.c (0)
Location: lib/nlattr.c:157
Inline: False
Direct callers:
  - lib/nlattr.c:__nla_validate_parse
```
**Symbols:**

```
ffffffff8154d650-ffffffff8154dc7b: validate_nla (STB_LOCAL)
ffffffff8154e225-ffffffff8154e257: validate_nla.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int validate_nla(const struct nlattr *nla, int maxtype, const struct nla_policy *policy, unsigned int validate, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/nlattr.c (0)
Location: lib/nlattr.c:157
Inline: False
Direct callers:
  - lib/nlattr.c:__nla_validate_parse
```
**Symbols:**

```
ffffffff8153d930-ffffffff8153df5b: validate_nla (STB_LOCAL)
ffffffff8153e505-ffffffff8153e537: validate_nla.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int validate_nla(const struct nlattr *nla, int maxtype, const struct nla_policy *policy, unsigned int validate, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/nlattr.c (0)
Location: lib/nlattr.c:157
Inline: False
Direct callers:
  - lib/nlattr.c:__nla_validate_parse
```
**Symbols:**

```
ffffffff81549390-ffffffff815499bb: validate_nla (STB_LOCAL)
ffffffff81549f65-ffffffff81549f97: validate_nla.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int validate_nla(const struct nlattr *nla, int maxtype, const struct nla_policy *policy, unsigned int validate, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/nlattr.c (0)
Location: lib/nlattr.c:157
Inline: False
Direct callers:
  - lib/nlattr.c:__nla_validate_parse
```
**Symbols:**

```
ffffffff815631e0-ffffffff8156380b: validate_nla (STB_LOCAL)
ffffffff81563db5-ffffffff81563de7: validate_nla.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct netlink_ext_ack *extack</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int validate</code>
</li>
<li>
<b>Param reordered. </b>
<code>nla, maxtype, policy, extack</code> ➡️ <code>nla, maxtype, policy, validate, extack</code>
</li>
</ul>
</details>
</li>
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
