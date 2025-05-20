# Function: <code>thermal_genl_cmd_dumpit</code>

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
int thermal_genl_cmd_dumpit(struct sk_buff *skb, struct netlink_callback *cb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff8195f5a0)
Location: drivers/thermal/thermal_netlink.c:544
Inline: False
```
**Symbols:**

```
ffffffff8195f5a0-ffffffff8195f682: thermal_genl_cmd_dumpit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int thermal_genl_cmd_dumpit(struct sk_buff *skb, struct netlink_callback *cb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff81942b00)
Location: drivers/thermal/thermal_netlink.c:544
Inline: False
```
**Symbols:**

```
ffffffff81942b00-ffffffff81942be1: thermal_genl_cmd_dumpit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int thermal_genl_cmd_dumpit(struct sk_buff *skb, struct netlink_callback *cb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff819e7450)
Location: drivers/thermal/thermal_netlink.c:545
Inline: False
```
**Symbols:**

```
ffffffff819e7450-ffffffff819e7556: thermal_genl_cmd_dumpit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int thermal_genl_cmd_dumpit(struct sk_buff *skb, struct netlink_callback *cb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff81b4cc40)
Location: drivers/thermal/thermal_netlink.c:599
Inline: False
```
**Symbols:**

```
ffffffff81b4cc40-ffffffff81b4cd61: thermal_genl_cmd_dumpit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int thermal_genl_cmd_dumpit(struct sk_buff *skb, struct netlink_callback *cb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff81ce4910)
Location: drivers/thermal/thermal_netlink.c:599
Inline: False
```
**Symbols:**

```
ffffffff81ce4910-ffffffff81ce4a31: thermal_genl_cmd_dumpit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int thermal_genl_cmd_dumpit(struct sk_buff *skb, struct netlink_callback *cb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff81d4cee0)
Location: drivers/thermal/thermal_netlink.c:596
Inline: False
```
**Symbols:**

```
ffffffff81d4cee0-ffffffff81d4d001: thermal_genl_cmd_dumpit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int thermal_genl_cmd_dumpit(struct sk_buff *skb, struct netlink_callback *cb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff81e03be0)
Location: drivers/thermal/thermal_netlink.c:587
Inline: False
```
**Symbols:**

```
ffffffff81e03be0-ffffffff81e03d01: thermal_genl_cmd_dumpit (STB_LOCAL)
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
