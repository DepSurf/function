# Function: <code>__sb_tc_pool_bind_get_dumpit</code>

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
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8194e29e)
Location: net/core/devlink.c:1402
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit
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
In net/core/devlink.c (ffffffff81984a9e)
Location: net/core/devlink.c:1404
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __sb_tc_pool_bind_get_dumpit(struct sk_buff *msg, int start, int *p_idx, struct devlink *devlink, struct devlink_sb *devlink_sb, u32 portid, u32 seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a5a470)
Location: net/core/devlink.c:1431
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit
```
**Symbols:**

```
ffffffff81a5a470-ffffffff81a5a5c5: __sb_tc_pool_bind_get_dumpit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __sb_tc_pool_bind_get_dumpit(struct sk_buff *msg, int start, int *p_idx, struct devlink *devlink, struct devlink_sb *devlink_sb, u32 portid, u32 seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a622a0)
Location: net/core/devlink.c:1750
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit
```
**Symbols:**

```
ffffffff81a622a0-ffffffff81a623f5: __sb_tc_pool_bind_get_dumpit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a44b64)
Location: net/core/devlink.c:1953
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81afc50f)
Location: net/core/devlink.c:2488
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c88af1)
Location: net/core/devlink.c:3007
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e42886)
Location: net/core/devlink.c:3277
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/devlink/leftover.c (ffffffff82038b77)
Location: net/devlink/leftover.c:2627
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_nl_cmd_sb_tc_pool_bind_get_dump_one
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/devlink/sb.c (ffffffff82108a6b)
Location: net/devlink/sb.c:760
Inline: True
Inline callers:
  - net/devlink/sb.c:devlink_nl_sb_tc_pool_bind_get_dump_one
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
In net/core/devlink.c (ffff800010c2d080)
Location: net/core/devlink.c:1404
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit
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
In net/core/devlink.c (c0d43fd4)
Location: net/core/devlink.c:1404
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit
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
In net/core/devlink.c (c000000000d21f8c)
Location: net/core/devlink.c:1404
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit
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
In net/core/devlink.c (ffffffe0007a4346)
Location: net/core/devlink.c:1404
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit
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
In net/core/devlink.c (ffffffff8192490e)
Location: net/core/devlink.c:1404
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit
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
In net/core/devlink.c (ffffffff818de6be)
Location: net/core/devlink.c:1404
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit
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
In net/core/devlink.c (ffffffff81975a9e)
Location: net/core/devlink.c:1404
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit
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
In net/core/devlink.c (ffffffff81997f8e)
Location: net/core/devlink.c:1404
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
