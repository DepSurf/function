# Function: <code>netlink_policy_dump_free</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void netlink_policy_dump_free(struct netlink_policy_dump_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/policy.c (ffffffff81a87530)
Location: net/netlink/policy.c:466
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy_done
```
**Symbols:**

```
ffffffff81a87530-ffffffff81a87540: netlink_policy_dump_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void netlink_policy_dump_free(struct netlink_policy_dump_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/policy.c (ffffffff81a70600)
Location: net/netlink/policy.c:466
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy_done
```
**Symbols:**

```
ffffffff81a70600-ffffffff81a70610: netlink_policy_dump_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void netlink_policy_dump_free(struct netlink_policy_dump_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/policy.c (ffffffff81b29d50)
Location: net/netlink/policy.c:466
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy_done
```
**Symbols:**

```
ffffffff81b29d50-ffffffff81b29d60: netlink_policy_dump_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void netlink_policy_dump_free(struct netlink_policy_dump_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/policy.c (ffffffff81cb2d36)
Location: net/netlink/policy.c:476
Inline: True
Inline callers:
  - net/netlink/policy.c:netlink_policy_dump_add_policy
Direct callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy_done
  - net/netlink/genetlink.c:ctrl_dumppolicy_start
```
**Symbols:**

```
ffffffff81cb2f60-ffffffff81cb2f76: netlink_policy_dump_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void netlink_policy_dump_free(struct netlink_policy_dump_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/policy.c (ffffffff81e70d96)
Location: net/netlink/policy.c:476
Inline: True
Inline callers:
  - net/netlink/policy.c:netlink_policy_dump_add_policy
Direct callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy_done
  - net/netlink/genetlink.c:ctrl_dumppolicy_start
```
**Symbols:**

```
ffffffff81e71010-ffffffff81e71026: netlink_policy_dump_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void netlink_policy_dump_free(struct netlink_policy_dump_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/policy.c (ffffffff81ecceb6)
Location: net/netlink/policy.c:476
Inline: True
Inline callers:
  - net/netlink/policy.c:netlink_policy_dump_add_policy
Direct callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy_done
  - net/netlink/genetlink.c:ctrl_dumppolicy_start
```
**Symbols:**

```
ffffffff81ecd130-ffffffff81ecd146: netlink_policy_dump_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void netlink_policy_dump_free(struct netlink_policy_dump_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/policy.c (ffffffff81f906d9)
Location: net/netlink/policy.c:485
Inline: True
Inline callers:
  - net/netlink/policy.c:netlink_policy_dump_add_policy
Direct callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy_done
  - net/netlink/genetlink.c:ctrl_dumppolicy_start
```
**Symbols:**

```
ffffffff81f90960-ffffffff81f90976: netlink_policy_dump_free (STB_GLOBAL)
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
