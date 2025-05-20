# Function: <code>__rtnl_unlock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void __rtnl_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8172a004)
Location: net/core/rtnetlink.c:74
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_newlink
Direct callers:
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/sched/ematch.c:tcf_em_tree_validate
```
**Symbols:**

```
ffffffff8172f9e0-ffffffff8172f9f7: __rtnl_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __rtnl_unlock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81799570)
Location: net/core/rtnetlink.c:84
Inline: False
Direct callers:
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/sched/ematch.c:tcf_em_tree_validate
```
**Symbols:**

```
ffffffff81799570-ffffffff817995bc: __rtnl_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __rtnl_unlock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff817c7310)
Location: net/core/rtnetlink.c:84
Inline: False
Direct callers:
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type
  - net/sched/ematch.c:tcf_em_tree_validate
```
**Symbols:**

```
ffffffff817c7310-ffffffff817c735c: __rtnl_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __rtnl_unlock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff817e5b70)
Location: net/core/rtnetlink.c:86
Inline: False
Direct callers:
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_link_unregister
```
**Symbols:**

```
ffffffff817e5b70-ffffffff817e5bbc: __rtnl_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __rtnl_unlock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81860c10)
Location: net/core/rtnetlink.c:86
Inline: False
Direct callers:
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_link_unregister
```
**Symbols:**

```
ffffffff81860c10-ffffffff81860c5c: __rtnl_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __rtnl_unlock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818ac800)
Location: net/core/rtnetlink.c:97
Inline: False
Direct callers:
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type
```
**Symbols:**

```
ffffffff818ac800-ffffffff818ac84c: __rtnl_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __rtnl_unlock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818d09a0)
Location: net/core/rtnetlink.c:97
Inline: False
Direct callers:
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type
```
**Symbols:**

```
ffffffff818d09a0-ffffffff818d09ec: __rtnl_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __rtnl_unlock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8191d810)
Location: net/core/rtnetlink.c:92
Inline: False
Direct callers:
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type
```
**Symbols:**

```
ffffffff8191d810-ffffffff8191d855: __rtnl_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __rtnl_unlock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8194fe40)
Location: net/core/rtnetlink.c:92
Inline: False
Direct callers:
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type
```
**Symbols:**

```
ffffffff8194fe40-ffffffff8194fe85: __rtnl_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __rtnl_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a1d252)
Location: net/core/rtnetlink.c:92
Inline: True
Inline callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_link_unregister
Direct callers:
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_wait_allrefs
  - net/core/dev.c:netdev_wait_allrefs
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type
```
**Symbols:**

```
ffffffff81a21740-ffffffff81a21788: __rtnl_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __rtnl_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a1d752)
Location: net/core/rtnetlink.c:92
Inline: True
Inline callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_link_unregister
Direct callers:
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_wait_allrefs
  - net/core/dev.c:netdev_wait_allrefs
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type
```
**Symbols:**

```
ffffffff81a21b80-ffffffff81a21bc8: __rtnl_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __rtnl_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a04522)
Location: net/core/rtnetlink.c:92
Inline: True
Inline callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_link_unregister
Direct callers:
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type
```
**Symbols:**

```
ffffffff81a08ec0-ffffffff81a08f08: __rtnl_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __rtnl_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81ab6b0e)
Location: net/core/rtnetlink.c:92
Inline: True
Inline callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_link_unregister
Direct callers:
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type
```
**Symbols:**

```
ffffffff81abb420-ffffffff81abb468: __rtnl_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __rtnl_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81c308e3)
Location: net/core/rtnetlink.c:94
Inline: True
Inline callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_link_unregister
Direct callers:
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_wait_allrefs_any
  - net/core/dev.c:netdev_wait_allrefs_any
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type
```
**Symbols:**

```
ffffffff81c35c10-ffffffff81c35c7a: __rtnl_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __rtnl_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81de3c14)
Location: net/core/rtnetlink.c:95
Inline: True
Inline callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_link_unregister
Direct callers:
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_wait_allrefs_any
  - net/core/dev.c:netdev_wait_allrefs_any
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type
```
**Symbols:**

```
ffffffff81de9170-ffffffff81de91da: __rtnl_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __rtnl_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81e550f4)
Location: net/core/rtnetlink.c:98
Inline: True
Inline callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_link_unregister
Direct callers:
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_wait_allrefs_any
  - net/core/dev.c:netdev_wait_allrefs_any
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type
```
**Symbols:**

```
ffffffff81e5a9b0-ffffffff81e5aa1a: __rtnl_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __rtnl_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81f1446d)
Location: net/core/rtnetlink.c:99
Inline: True
Inline callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_link_unregister
Direct callers:
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_wait_allrefs_any
  - net/core/dev.c:netdev_wait_allrefs_any
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type
```
**Symbols:**

```
ffffffff81f19d70-ffffffff81f19dda: __rtnl_unlock (STB_GLOBAL)
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
void __rtnl_unlock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffff800010bf1ac8)
Location: net/core/rtnetlink.c:92
Inline: False
Direct callers:
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type
```
**Symbols:**

```
ffff800010bf1ac8-ffff800010bf1b20: __rtnl_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __rtnl_unlock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c0d0a36c)
Location: net/core/rtnetlink.c:92
Inline: False
Direct callers:
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type
```
**Symbols:**

```
c0d0a36c-c0d0a3c4: __rtnl_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __rtnl_unlock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c000000000cd66b0)
Location: net/core/rtnetlink.c:92
Inline: False
Direct callers:
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type
```
**Symbols:**

```
c000000000cd66b0-c000000000cd6734: __rtnl_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __rtnl_unlock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffe000773774)
Location: net/core/rtnetlink.c:92
Inline: False
Direct callers:
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type
```
**Symbols:**

```
ffffffe000773774-ffffffe0007737ca: __rtnl_unlock (STB_GLOBAL)
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
void __rtnl_unlock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818efe10)
Location: net/core/rtnetlink.c:92
Inline: False
Direct callers:
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type
```
**Symbols:**

```
ffffffff818efe10-ffffffff818efe55: __rtnl_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __rtnl_unlock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818a9c50)
Location: net/core/rtnetlink.c:92
Inline: False
Direct callers:
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type
```
**Symbols:**

```
ffffffff818a9c50-ffffffff818a9c95: __rtnl_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __rtnl_unlock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81940e40)
Location: net/core/rtnetlink.c:92
Inline: False
Direct callers:
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type
```
**Symbols:**

```
ffffffff81940e40-ffffffff81940e85: __rtnl_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __rtnl_unlock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81962750)
Location: net/core/rtnetlink.c:92
Inline: False
Direct callers:
  - net/core/dev.c:default_device_exit_batch
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:netdev_run_todo
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type
```
**Symbols:**

```
ffffffff81962750-ffffffff81962790: __rtnl_unlock (STB_GLOBAL)
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
