# Function: <code>devlink_trap_report</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void devlink_trap_report(struct devlink *devlink, struct sk_buff *skb, void *trap_ctx, struct devlink_port *in_devlink_port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8197d1e0)
Location: net/core/devlink.c:7974
Inline: False
```
**Symbols:**

```
ffffffff8197d1e0-ffffffff8197d2b9: devlink_trap_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void devlink_trap_report(struct devlink *devlink, struct sk_buff *skb, void *trap_ctx, struct devlink_port *in_devlink_port, const struct flow_action_cookie *fa_cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a53370)
Location: net/core/devlink.c:8914
Inline: False
```
**Symbols:**

```
ffffffff81a53370-ffffffff81a5345c: devlink_trap_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void devlink_trap_report(struct devlink *devlink, struct sk_buff *skb, void *trap_ctx, struct devlink_port *in_devlink_port, const struct flow_action_cookie *fa_cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a5b070)
Location: net/core/devlink.c:9872
Inline: False
```
**Symbols:**

```
ffffffff81a5b070-ffffffff81a5b1ab: devlink_trap_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void devlink_trap_report(struct devlink *devlink, struct sk_buff *skb, void *trap_ctx, struct devlink_port *in_devlink_port, const struct flow_action_cookie *fa_cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a3df70)
Location: net/core/devlink.c:10136
Inline: False
```
**Symbols:**

```
ffffffff81a3df70-ffffffff81a3e0ab: devlink_trap_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void devlink_trap_report(struct devlink *devlink, struct sk_buff *skb, void *trap_ctx, struct devlink_port *in_devlink_port, const struct flow_action_cookie *fa_cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81af61d0)
Location: net/core/devlink.c:11078
Inline: False
```
**Symbols:**

```
ffffffff81af61d0-ffffffff81af6305: devlink_trap_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void devlink_trap_report(struct devlink *devlink, struct sk_buff *skb, void *trap_ctx, struct devlink_port *in_devlink_port, const struct flow_action_cookie *fa_cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c726c0)
Location: net/core/devlink.c:11674
Inline: False
```
**Symbols:**

```
ffffffff81c726c0-ffffffff81c7281e: devlink_trap_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void devlink_trap_report(struct devlink *devlink, struct sk_buff *skb, void *trap_ctx, struct devlink_port *in_devlink_port, const struct flow_action_cookie *fa_cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e2aab0)
Location: net/core/devlink.c:12529
Inline: False
```
**Symbols:**

```
ffffffff81e2aab0-ffffffff81e2ac0a: devlink_trap_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void devlink_trap_report(struct devlink *devlink, struct sk_buff *skb, void *trap_ctx, struct devlink_port *in_devlink_port, const struct flow_action_cookie *fa_cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/leftover.c (ffffffff8202e9d0)
Location: net/devlink/leftover.c:9124
Inline: False
```
**Symbols:**

```
ffffffff8202e9d0-ffffffff8202eb2a: devlink_trap_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void devlink_trap_report(struct devlink *devlink, struct sk_buff *skb, void *trap_ctx, struct devlink_port *in_devlink_port, const struct flow_action_cookie *fa_cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/trap.c (ffffffff82114800)
Location: net/devlink/trap.c:1491
Inline: False
```
**Symbols:**

```
ffffffff82114800-ffffffff8211495a: devlink_trap_report (STB_GLOBAL)
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
void devlink_trap_report(struct devlink *devlink, struct sk_buff *skb, void *trap_ctx, struct devlink_port *in_devlink_port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c265c8)
Location: net/core/devlink.c:7974
Inline: False
```
**Symbols:**

```
ffff800010c265c8-ffff800010c2670c: devlink_trap_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void devlink_trap_report(struct devlink *devlink, struct sk_buff *skb, void *trap_ctx, struct devlink_port *in_devlink_port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d3beac)
Location: net/core/devlink.c:7974
Inline: False
```
**Symbols:**

```
c0d3beac-c0d3bf88: devlink_trap_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void devlink_trap_report(struct devlink *devlink, struct sk_buff *skb, void *trap_ctx, struct devlink_port *in_devlink_port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d18870)
Location: net/core/devlink.c:7974
Inline: False
```
**Symbols:**

```
c000000000d18870-c000000000d189c8: devlink_trap_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void devlink_trap_report(struct devlink *devlink, struct sk_buff *skb, void *trap_ctx, struct devlink_port *in_devlink_port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe00079cf92)
Location: net/core/devlink.c:7974
Inline: False
```
**Symbols:**

```
ffffffe00079cf92-ffffffe00079d08a: devlink_trap_report (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void devlink_trap_report(struct devlink *devlink, struct sk_buff *skb, void *trap_ctx, struct devlink_port *in_devlink_port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8191d050)
Location: net/core/devlink.c:7974
Inline: False
```
**Symbols:**

```
ffffffff8191d050-ffffffff8191d129: devlink_trap_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void devlink_trap_report(struct devlink *devlink, struct sk_buff *skb, void *trap_ctx, struct devlink_port *in_devlink_port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818d6e00)
Location: net/core/devlink.c:7974
Inline: False
```
**Symbols:**

```
ffffffff818d6e00-ffffffff818d6ed9: devlink_trap_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void devlink_trap_report(struct devlink *devlink, struct sk_buff *skb, void *trap_ctx, struct devlink_port *in_devlink_port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8196e1e0)
Location: net/core/devlink.c:7974
Inline: False
```
**Symbols:**

```
ffffffff8196e1e0-ffffffff8196e2b9: devlink_trap_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void devlink_trap_report(struct devlink *devlink, struct sk_buff *skb, void *trap_ctx, struct devlink_port *in_devlink_port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81990670)
Location: net/core/devlink.c:7974
Inline: False
```
**Symbols:**

```
ffffffff81990670-ffffffff81990747: devlink_trap_report (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct flow_action_cookie *fa_cookie</code>
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
