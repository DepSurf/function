# Function: <code>netlink_policy_dump_loop</code>

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
bool netlink_policy_dump_loop(long unsigned int *_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/policy.c (ffffffff81a7d900)
Location: net/netlink/policy.c:143
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
```
**Symbols:**

```
ffffffff81a7d900-ffffffff81a7d94b: netlink_policy_dump_loop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool netlink_policy_dump_loop(struct netlink_policy_dump_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/policy.c (ffffffff81a87320)
Location: net/netlink/policy.c:194
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy
```
**Symbols:**

```
ffffffff81a87320-ffffffff81a87346: netlink_policy_dump_loop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool netlink_policy_dump_loop(struct netlink_policy_dump_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/policy.c (ffffffff81a703f0)
Location: net/netlink/policy.c:194
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy
```
**Symbols:**

```
ffffffff81a703f0-ffffffff81a70416: netlink_policy_dump_loop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool netlink_policy_dump_loop(struct netlink_policy_dump_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/policy.c (ffffffff81b29b40)
Location: net/netlink/policy.c:194
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy
```
**Symbols:**

```
ffffffff81b29b40-ffffffff81b29b66: netlink_policy_dump_loop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool netlink_policy_dump_loop(struct netlink_policy_dump_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/policy.c (ffffffff81cb2d50)
Location: net/netlink/policy.c:204
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy
```
**Symbols:**

```
ffffffff81cb2d50-ffffffff81cb2d7b: netlink_policy_dump_loop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool netlink_policy_dump_loop(struct netlink_policy_dump_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/policy.c (ffffffff81e70dc0)
Location: net/netlink/policy.c:204
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
```
**Symbols:**

```
ffffffff81e70dc0-ffffffff81e70deb: netlink_policy_dump_loop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool netlink_policy_dump_loop(struct netlink_policy_dump_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/policy.c (ffffffff81eccee0)
Location: net/netlink/policy.c:204
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
```
**Symbols:**

```
ffffffff81eccee0-ffffffff81eccf0b: netlink_policy_dump_loop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool netlink_policy_dump_loop(struct netlink_policy_dump_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/policy.c (ffffffff81f90710)
Location: net/netlink/policy.c:205
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
```
**Symbols:**

```
ffffffff81f90710-ffffffff81f9073b: netlink_policy_dump_loop (STB_GLOBAL)
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
<b>Param added. </b>
<code>struct netlink_policy_dump_state *state</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int *_state</code>
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
