# Function: <code>genl_get_cmd</code>

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
In net/netlink/genetlink.c (ffffffff8174f52e)
Location: net/netlink/genetlink.c:127
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
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
In net/netlink/genetlink.c (ffffffff817bb50e)
Location: net/netlink/genetlink.c:127
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
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
In net/netlink/genetlink.c (ffffffff817eaf10)
Location: net/netlink/genetlink.c:109
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
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
In net/netlink/genetlink.c (ffffffff8180ae77)
Location: net/netlink/genetlink.c:109
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
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
In net/netlink/genetlink.c (ffffffff81889dc7)
Location: net/netlink/genetlink.c:110
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
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
In net/netlink/genetlink.c (ffffffff818dec70)
Location: net/netlink/genetlink.c:110
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
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
In net/netlink/genetlink.c (ffffffff8190b630)
Location: net/netlink/genetlink.c:110
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff8196c401)
Location: net/netlink/genetlink.c:110
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff819a2db1)
Location: net/netlink/genetlink.c:110
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81a7c149)
Location: net/netlink/genetlink.c:110
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int genl_get_cmd(u32 cmd, const struct genl_family *family, struct genl_ops *op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81a85410)
Location: net/netlink/genetlink.c:169
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_start
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
**Symbols:**

```
ffffffff81a85410-ffffffff81a854d7: genl_get_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int genl_get_cmd(u32 cmd, const struct genl_family *family, struct genl_ops *op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81a6e4f0)
Location: net/netlink/genetlink.c:169
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_start
  - net/netlink/genetlink.c:genl_rcv_msg
```
**Symbols:**

```
ffffffff81a6e4f0-ffffffff81a6e5b7: genl_get_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int genl_get_cmd(u32 cmd, const struct genl_family *family, struct genl_ops *op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81b27b70)
Location: net/netlink/genetlink.c:161
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_start
  - net/netlink/genetlink.c:genl_rcv_msg
```
**Symbols:**

```
ffffffff81b27b70-ffffffff81b27c37: genl_get_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int genl_get_cmd(u32 cmd, const struct genl_family *family, struct genl_ops *op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81cb0ba0)
Location: net/netlink/genetlink.c:161
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_start
  - net/netlink/genetlink.c:genl_rcv_msg
```
**Symbols:**

```
ffffffff81cb0ba0-ffffffff81cb0cb4: genl_get_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int genl_get_cmd(u32 cmd, u8 flags, const struct genl_family *family, struct genl_split_ops *op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81e6d3e0)
Location: net/netlink/genetlink.c:287
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_start
  - net/netlink/genetlink.c:ctrl_dumppolicy_start
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
**Symbols:**

```
ffffffff81e6d3e0-ffffffff81e6d568: genl_get_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int genl_get_cmd(u32 cmd, u8 flags, const struct genl_family *family, struct genl_split_ops *op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81ec94f0)
Location: net/netlink/genetlink.c:287
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_start
  - net/netlink/genetlink.c:ctrl_dumppolicy_start
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
**Symbols:**

```
ffffffff81ec94f0-ffffffff81ec9678: genl_get_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int genl_get_cmd(u32 cmd, u8 flags, const struct genl_family *family, struct genl_split_ops *op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81f8c5c0)
Location: net/netlink/genetlink.c:300
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy_start
  - net/netlink/genetlink.c:ctrl_dumppolicy_start
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
**Symbols:**

```
ffffffff81f8c5c0-ffffffff81f8c748: genl_get_cmd (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffff800010c50fc4)
Location: net/netlink/genetlink.c:110
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (c0d617d4)
Location: net/netlink/genetlink.c:110
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (c000000000d5177c)
Location: net/netlink/genetlink.c:110
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffe0007bc37c)
Location: net/netlink/genetlink.c:110
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81942c21)
Location: net/netlink/genetlink.c:110
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff818fc711)
Location: net/netlink/genetlink.c:110
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81993db1)
Location: net/netlink/genetlink.c:110
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff819b68b1)
Location: net/netlink/genetlink.c:110
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
</details>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u8 flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>cmd, family, op</code> ➡️ <code>cmd, flags, family, op</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct genl_ops *op</code> ➡️ <code>struct genl_split_ops *op</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
