# Function: <code>devlink_nl_selftests_fill</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int devlink_nl_selftests_fill(struct sk_buff *msg, struct devlink *devlink, u32 portid, u32 seq, int flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e32ab0)
Location: net/core/devlink.c:5126
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_selftests_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_selftests_get_doit
```
**Symbols:**

```
ffffffff81e32ab0-ffffffff81e32bfe: devlink_nl_selftests_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int devlink_nl_selftests_fill(struct sk_buff *msg, struct devlink *devlink, u32 portid, u32 seq, int flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/dev.c (ffffffff820435e0)
Location: net/devlink/dev.c:1167
Inline: False
Direct callers:
  - net/devlink/dev.c:devlink_nl_cmd_selftests_get_doit
```
**Symbols:**

```
ffffffff820435e0-ffffffff8204377e: devlink_nl_selftests_fill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int devlink_nl_selftests_fill(struct sk_buff *msg, struct devlink *devlink, u32 portid, u32 seq, int flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/dev.c (ffffffff82102a20)
Location: net/devlink/dev.c:1268
Inline: False
Direct callers:
  - net/devlink/dev.c:devlink_nl_selftests_get_doit
```
**Symbols:**

```
ffffffff82102a20-ffffffff82102bbe: devlink_nl_selftests_fill (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
