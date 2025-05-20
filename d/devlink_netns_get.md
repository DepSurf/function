# Function: <code>devlink_netns_get</code>

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
struct net *devlink_netns_get(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a52a50)
Location: net/core/devlink.c:2709
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_reload
```
**Symbols:**

```
ffffffff81a52a50-ffffffff81a52b86: devlink_netns_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct net *devlink_netns_get(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a59830)
Location: net/core/devlink.c:3041
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_reload
```
**Symbols:**

```
ffffffff81a59830-ffffffff81a5996c: devlink_netns_get (STB_LOCAL)
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
In net/core/devlink.c (ffffffff81a4a8c6)
Location: net/core/devlink.c:3244
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_reload
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
In net/core/devlink.c (ffffffff81b02aba)
Location: net/core/devlink.c:3806
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_reload
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
In net/core/devlink.c (ffffffff81c8644d)
Location: net/core/devlink.c:4321
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_reload
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
In net/core/devlink.c (ffffffff81e40579)
Location: net/core/devlink.c:4587
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_reload
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
In net/devlink/dev.c (ffffffff82044971)
Location: net/devlink/dev.c:299
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_nl_cmd_reload
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
In net/devlink/dev.c (ffffffff82104231)
Location: net/devlink/dev.c:378
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_nl_reload_doit
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
