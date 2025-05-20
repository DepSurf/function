# Function: <code>get_net_ns_by_fd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct net *get_net_ns_by_fd(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff8170fc40)
Location: net/core/net_namespace.c:466
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_getid
```
**Symbols:**

```
ffffffff8170fc40-ffffffff8170fc8b: get_net_ns_by_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct net *get_net_ns_by_fd(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81777570)
Location: net/core/net_namespace.c:466
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
**Symbols:**

```
ffffffff81777570-ffffffff817775c4: get_net_ns_by_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct net *get_net_ns_by_fd(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff817a45f0)
Location: net/core/net_namespace.c:497
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
**Symbols:**

```
ffffffff817a45f0-ffffffff817a464a: get_net_ns_by_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct net *get_net_ns_by_fd(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff817c2790)
Location: net/core/net_namespace.c:536
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
**Symbols:**

```
ffffffff817c2790-ffffffff817c27e4: get_net_ns_by_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct net *get_net_ns_by_fd(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff8183c0d0)
Location: net/core/net_namespace.c:537
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
**Symbols:**

```
ffffffff8183c0d0-ffffffff8183c124: get_net_ns_by_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct net *get_net_ns_by_fd(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81886890)
Location: net/core/net_namespace.c:599
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
**Symbols:**

```
ffffffff81886890-ffffffff818868e1: get_net_ns_by_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct net *get_net_ns_by_fd(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff818a6f80)
Location: net/core/net_namespace.c:599
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
**Symbols:**

```
ffffffff818a6f80-ffffffff818a6fd1: get_net_ns_by_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct net *get_net_ns_by_fd(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff818f2680)
Location: net/core/net_namespace.c:643
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
```
**Symbols:**

```
ffffffff818f2680-ffffffff818f26dd: get_net_ns_by_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct net *get_net_ns_by_fd(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff819245e0)
Location: net/core/net_namespace.c:646
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
```
**Symbols:**

```
ffffffff819245e0-ffffffff8192463d: get_net_ns_by_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct net *get_net_ns_by_fd(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff819f8ed0)
Location: net/core/net_namespace.c:652
Inline: False
Direct callers:
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_prog_query
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/devlink.c:devlink_netns_get
```
**Symbols:**

```
ffffffff819f8ed0-ffffffff819f8f5b: get_net_ns_by_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct net *get_net_ns_by_fd(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff819f89b0)
Location: net/core/net_namespace.c:653
Inline: False
Direct callers:
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_prog_query
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/devlink.c:devlink_netns_get
```
**Symbols:**

```
ffffffff819f89b0-ffffffff819f8a3b: get_net_ns_by_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct net *get_net_ns_by_fd(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff819df140)
Location: net/core/net_namespace.c:656
Inline: False
Direct callers:
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_prog_query
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/devlink.c:devlink_nl_cmd_reload
```
**Symbols:**

```
ffffffff819df140-ffffffff819df1cb: get_net_ns_by_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct net *get_net_ns_by_fd(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81a8f520)
Location: net/core/net_namespace.c:658
Inline: False
Direct callers:
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_prog_query
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/devlink.c:devlink_nl_cmd_reload
```
**Symbols:**

```
ffffffff81a8f520-ffffffff81a8f5ab: get_net_ns_by_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct net *get_net_ns_by_fd(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81c053b0)
Location: net/core/net_namespace.c:658
Inline: False
Direct callers:
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_prog_query
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/devlink.c:devlink_nl_cmd_reload
```
**Symbols:**

```
ffffffff81c053b0-ffffffff81c0546b: get_net_ns_by_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct net *get_net_ns_by_fd(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81db4c60)
Location: net/core/net_namespace.c:677
Inline: False
Direct callers:
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_prog_query
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/devlink.c:devlink_nl_cmd_reload
```
**Symbols:**

```
ffffffff81db4c60-ffffffff81db4d1b: get_net_ns_by_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct net *get_net_ns_by_fd(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81e23880)
Location: net/core/net_namespace.c:678
Inline: False
Direct callers:
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_prog_query
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/devlink/dev.c:devlink_nl_cmd_reload
```
**Symbols:**

```
ffffffff81e23880-ffffffff81e2395e: get_net_ns_by_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct net *get_net_ns_by_fd(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81ee17e0)
Location: net/core/net_namespace.c:682
Inline: False
Direct callers:
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_prog_query
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/devlink/dev.c:devlink_nl_reload_doit
```
**Symbols:**

```
ffffffff81ee17e0-ffffffff81ee18be: get_net_ns_by_fd (STB_GLOBAL)
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
struct net *get_net_ns_by_fd(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffff800010bbffb0)
Location: net/core/net_namespace.c:646
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
```
**Symbols:**

```
ffff800010bbffb0-ffff800010bc0038: get_net_ns_by_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct net *get_net_ns_by_fd(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (c0cdbae8)
Location: net/core/net_namespace.c:646
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
```
**Symbols:**

```
c0cdbae8-c0cdbb58: get_net_ns_by_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct net *get_net_ns_by_fd(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (c000000000c994e0)
Location: net/core/net_namespace.c:646
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
```
**Symbols:**

```
c000000000c994e0-c000000000c9959c: get_net_ns_by_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct net *get_net_ns_by_fd(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffe00074d860)
Location: net/core/net_namespace.c:646
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
```
**Symbols:**

```
ffffffe00074d860-ffffffe00074d8ce: get_net_ns_by_fd (STB_GLOBAL)
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
struct net *get_net_ns_by_fd(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff818c45e0)
Location: net/core/net_namespace.c:646
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
```
**Symbols:**

```
ffffffff818c45e0-ffffffff818c463d: get_net_ns_by_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct net *get_net_ns_by_fd(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff8187e520)
Location: net/core/net_namespace.c:646
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
```
**Symbols:**

```
ffffffff8187e520-ffffffff8187e57d: get_net_ns_by_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct net *get_net_ns_by_fd(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff819155e0)
Location: net/core/net_namespace.c:646
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
```
**Symbols:**

```
ffffffff819155e0-ffffffff8191563d: get_net_ns_by_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct net *get_net_ns_by_fd(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff819367c0)
Location: net/core/net_namespace.c:646
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
```
**Symbols:**

```
ffffffff819367c0-ffffffff8193681d: get_net_ns_by_fd (STB_GLOBAL)
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
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
