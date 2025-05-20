# Function: <code>add_policy</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int add_policy(struct nl_policy_dump **statep, const struct nla_policy *policy, unsigned int maxtype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/policy.c (ffffffff81a7d6d0)
Location: net/netlink/policy.c:27
Inline: False
Direct callers:
  - net/netlink/policy.c:netlink_policy_dump_start
  - net/netlink/policy.c:netlink_policy_dump_start
```
**Symbols:**

```
ffffffff81a7d6d0-ffffffff81a7d7cc: add_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int add_policy(struct netlink_policy_dump_state **statep, const struct nla_policy *policy, unsigned int maxtype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/policy.c (ffffffff81a86bf0)
Location: net/netlink/policy.c:27
Inline: False
Direct callers:
  - net/netlink/policy.c:netlink_policy_dump_add_policy
  - net/netlink/policy.c:netlink_policy_dump_add_policy
```
**Symbols:**

```
ffffffff81a86bf0-ffffffff81a86cf2: add_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int add_policy(struct netlink_policy_dump_state **statep, const struct nla_policy *policy, unsigned int maxtype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/policy.c (ffffffff81a6fcd0)
Location: net/netlink/policy.c:27
Inline: False
Direct callers:
  - net/netlink/policy.c:netlink_policy_dump_add_policy
  - net/netlink/policy.c:netlink_policy_dump_add_policy
```
**Symbols:**

```
ffffffff81a6fcd0-ffffffff81a6fdd3: add_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int add_policy(struct netlink_policy_dump_state **statep, const struct nla_policy *policy, unsigned int maxtype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/policy.c (ffffffff81b29420)
Location: net/netlink/policy.c:27
Inline: False
Direct callers:
  - net/netlink/policy.c:netlink_policy_dump_add_policy
  - net/netlink/policy.c:netlink_policy_dump_add_policy
```
**Symbols:**

```
ffffffff81b29420-ffffffff81b29523: add_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int add_policy(struct netlink_policy_dump_state **statep, const struct nla_policy *policy, unsigned int maxtype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/policy.c (ffffffff81cb2580)
Location: net/netlink/policy.c:27
Inline: False
Direct callers:
  - net/netlink/policy.c:netlink_policy_dump_add_policy
  - net/netlink/policy.c:netlink_policy_dump_add_policy
```
**Symbols:**

```
ffffffff81cb2580-ffffffff81cb268a: add_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int add_policy(struct netlink_policy_dump_state **statep, const struct nla_policy *policy, unsigned int maxtype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/policy.c (ffffffff81e705b0)
Location: net/netlink/policy.c:27
Inline: False
Direct callers:
  - net/netlink/policy.c:netlink_policy_dump_add_policy
  - net/netlink/policy.c:netlink_policy_dump_add_policy
```
**Symbols:**

```
ffffffff81e705b0-ffffffff81e706ba: add_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int add_policy(struct netlink_policy_dump_state **statep, const struct nla_policy *policy, unsigned int maxtype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/policy.c (ffffffff81ecc6c0)
Location: net/netlink/policy.c:27
Inline: False
Direct callers:
  - net/netlink/policy.c:netlink_policy_dump_add_policy
  - net/netlink/policy.c:netlink_policy_dump_add_policy
```
**Symbols:**

```
ffffffff81ecc6c0-ffffffff81ecc7e3: add_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int add_policy(struct netlink_policy_dump_state **statep, const struct nla_policy *policy, unsigned int maxtype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/policy.c (ffffffff81f8fe90)
Location: net/netlink/policy.c:27
Inline: False
Direct callers:
  - net/netlink/policy.c:netlink_policy_dump_add_policy
  - net/netlink/policy.c:netlink_policy_dump_add_policy
```
**Symbols:**

```
ffffffff81f8fe90-ffffffff81f8ffb3: add_policy (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct nl_policy_dump **statep</code> ➡️ <code>struct netlink_policy_dump_state **statep</code>
</li>
</ul>
</details>
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
