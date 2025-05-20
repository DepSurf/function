# Function: <code>netdev_run_todo</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void netdev_run_todo();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8171ed20)
Location: net/core/dev.c:6907
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_af_register
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/core/rtnetlink.c:rtnl_link_register
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/core/rtnetlink.c:rtnetlink_rcv
```
**Symbols:**

```
ffffffff8171ed20-ffffffff8171f03d: netdev_run_todo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void netdev_run_todo();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81787640)
Location: net/core/dev.c:7416
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_rcv
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/core/rtnetlink.c:rtnl_af_register
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/core/rtnetlink.c:rtnl_link_register
```
**Symbols:**

```
ffffffff81787640-ffffffff81787961: netdev_run_todo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void netdev_run_todo();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817b4c00)
Location: net/core/dev.c:7586
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_rcv
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/core/rtnetlink.c:rtnl_af_register
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/core/rtnetlink.c:rtnl_link_register
```
**Symbols:**

```
ffffffff817b4c00-ffffffff817b4f21: netdev_run_todo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void netdev_run_todo();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817d37a0)
Location: net/core/dev.c:7773
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_rcv
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/core/rtnetlink.c:rtnl_af_register
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/core/rtnetlink.c:rtnl_link_register
```
**Symbols:**

```
ffffffff817d37a0-ffffffff817d3a9f: netdev_run_todo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void netdev_run_todo();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8184dc70)
Location: net/core/dev.c:7952
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/core/rtnetlink.c:rtnl_af_register
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/core/rtnetlink.c:rtnl_link_register
```
**Symbols:**

```
ffffffff8184dc70-ffffffff8184df8d: netdev_run_todo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void netdev_run_todo();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:8218
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/core/rtnetlink.c:rtnl_af_register
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/core/rtnetlink.c:rtnl_link_register
  - net/core/rtnetlink.c:rtnl_register_internal
```
**Symbols:**

```
ffffffff81899254-ffffffff81899293: netdev_run_todo.cold.169 (STB_LOCAL)
ffffffff81898ae0-ffffffff81898d6f: netdev_run_todo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void netdev_run_todo();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:8848
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/core/rtnetlink.c:rtnl_af_register
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/core/rtnetlink.c:rtnl_link_register
  - net/core/rtnetlink.c:rtnl_register_internal
```
**Symbols:**

```
ffffffff818bb70e-ffffffff818bb74d: netdev_run_todo.cold.177 (STB_LOCAL)
ffffffff818baf40-ffffffff818bb1cf: netdev_run_todo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void netdev_run_todo();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:8953
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/core/rtnetlink.c:rtnl_af_register
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/core/rtnetlink.c:rtnl_link_register
  - net/core/rtnetlink.c:rtnl_register_internal
```
**Symbols:**

```
ffffffff81907699-ffffffff8190770b: netdev_run_todo.cold (STB_LOCAL)
ffffffff819068b0-ffffffff81906b21: netdev_run_todo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void netdev_run_todo();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:9291
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/core/rtnetlink.c:rtnl_af_register
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/core/rtnetlink.c:rtnl_link_register
  - net/core/rtnetlink.c:rtnl_register_internal
```
**Symbols:**

```
ffffffff81939c80-ffffffff81939cb9: netdev_run_todo.cold (STB_LOCAL)
ffffffff81938fa0-ffffffff8193922c: netdev_run_todo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void netdev_run_todo();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:9747
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/core/rtnetlink.c:rtnl_af_register
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/core/rtnetlink.c:rtnl_link_register
  - net/core/rtnetlink.c:rtnl_unregister_all
  - net/core/rtnetlink.c:rtnl_unregister_all
  - net/core/rtnetlink.c:rtnl_unregister
  - net/core/rtnetlink.c:rtnl_unregister
  - net/core/rtnetlink.c:rtnl_register_internal
```
**Symbols:**

```
ffffffff81a0f205-ffffffff81a0f221: netdev_run_todo.cold (STB_LOCAL)
ffffffff81a0e4d0-ffffffff81a0e6d9: netdev_run_todo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void netdev_run_todo();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:10379
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/core/rtnetlink.c:rtnl_af_register
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/core/rtnetlink.c:rtnl_link_register
  - net/core/rtnetlink.c:rtnl_unregister_all
  - net/core/rtnetlink.c:rtnl_unregister_all
  - net/core/rtnetlink.c:rtnl_unregister
  - net/core/rtnetlink.c:rtnl_unregister
  - net/core/rtnetlink.c:rtnl_register_internal
```
**Symbols:**

```
ffffffff81c31550-ffffffff81c3156c: netdev_run_todo.cold (STB_LOCAL)
ffffffff81a0f2b0-ffffffff81a0f4b9: netdev_run_todo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void netdev_run_todo();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:10551
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/core/rtnetlink.c:rtnl_af_register
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/core/rtnetlink.c:rtnl_link_register
  - net/core/rtnetlink.c:rtnl_unregister_all
  - net/core/rtnetlink.c:rtnl_unregister_all
  - net/core/rtnetlink.c:rtnl_unregister
  - net/core/rtnetlink.c:rtnl_unregister
  - net/core/rtnetlink.c:rtnl_register_internal
```
**Symbols:**

```
ffffffff81c23835-ffffffff81c23875: netdev_run_todo.cold (STB_LOCAL)
ffffffff819f5fe0-ffffffff819f6328: netdev_run_todo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void netdev_run_todo();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:10558
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/core/rtnetlink.c:rtnl_af_register
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/core/rtnetlink.c:rtnl_link_register
  - net/core/rtnetlink.c:rtnl_unregister_all
  - net/core/rtnetlink.c:rtnl_unregister_all
  - net/core/rtnetlink.c:rtnl_unregister
  - net/core/rtnetlink.c:rtnl_unregister
  - net/core/rtnetlink.c:rtnl_register_internal
```
**Symbols:**

```
ffffffff81d368b7-ffffffff81d3690c: netdev_run_todo.cold (STB_LOCAL)
ffffffff81aa7960-ffffffff81aa7d6b: netdev_run_todo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void netdev_run_todo();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:10305
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/core/rtnetlink.c:rtnl_af_register
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/core/rtnetlink.c:rtnl_link_register
  - net/core/rtnetlink.c:rtnl_unregister_all
  - net/core/rtnetlink.c:rtnl_unregister_all
  - net/core/rtnetlink.c:rtnl_unregister
  - net/core/rtnetlink.c:rtnl_unregister
  - net/core/rtnetlink.c:rtnl_register_internal
```
**Symbols:**

```
ffffffff81f03125-ffffffff81f0314e: netdev_run_todo.cold (STB_LOCAL)
ffffffff81c1f8b0-ffffffff81c1fc58: netdev_run_todo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void netdev_run_todo();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:10294
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/core/rtnetlink.c:rtnl_af_register
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/core/rtnetlink.c:rtnl_link_register
  - net/core/rtnetlink.c:rtnl_unregister_all
  - net/core/rtnetlink.c:rtnl_unregister_all
  - net/core/rtnetlink.c:rtnl_unregister
  - net/core/rtnetlink.c:rtnl_unregister
  - net/core/rtnetlink.c:rtnl_register_internal
```
**Symbols:**

```
ffffffff820ab987-ffffffff820ab9b1: netdev_run_todo.cold (STB_LOCAL)
ffffffff81dd06a0-ffffffff81dd09b8: netdev_run_todo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void netdev_run_todo();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:10306
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/core/rtnetlink.c:rtnl_af_register
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/core/rtnetlink.c:rtnl_link_register
  - net/core/rtnetlink.c:rtnl_unregister_all
  - net/core/rtnetlink.c:rtnl_unregister_all
  - net/core/rtnetlink.c:rtnl_unregister
  - net/core/rtnetlink.c:rtnl_unregister
  - net/core/rtnetlink.c:rtnl_register_internal
```
**Symbols:**

```
ffffffff8212d0c4-ffffffff8212d0ee: netdev_run_todo.cold (STB_LOCAL)
ffffffff81e412a0-ffffffff81e415b8: netdev_run_todo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void netdev_run_todo();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:10498
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/core/rtnetlink.c:rtnl_af_register
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/core/rtnetlink.c:rtnl_link_register
  - net/core/rtnetlink.c:rtnl_unregister_all
  - net/core/rtnetlink.c:rtnl_unregister_all
  - net/core/rtnetlink.c:rtnl_unregister
  - net/core/rtnetlink.c:rtnl_unregister
  - net/core/rtnetlink.c:rtnl_register_internal
```
**Symbols:**

```
ffffffff8220eddc-ffffffff8220ee06: netdev_run_todo.cold (STB_LOCAL)
ffffffff81effbf0-ffffffff81efff38: netdev_run_todo (STB_GLOBAL)
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
void netdev_run_todo();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bd7890)
Location: net/core/dev.c:9291
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/core/rtnetlink.c:rtnl_af_register
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/core/rtnetlink.c:rtnl_link_register
  - net/core/rtnetlink.c:rtnl_register_internal
```
**Symbols:**

```
ffff800010bd7890-ffff800010bd7b40: netdev_run_todo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void netdev_run_todo();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0cf294c)
Location: net/core/dev.c:9291
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/core/rtnetlink.c:rtnl_af_register
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/core/rtnetlink.c:rtnl_link_register
  - net/core/rtnetlink.c:rtnl_register_internal
```
**Symbols:**

```
c0cf294c-c0cf2c40: netdev_run_todo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void netdev_run_todo();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000cb78a0)
Location: net/core/dev.c:9291
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/core/rtnetlink.c:rtnl_af_register
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/core/rtnetlink.c:rtnl_link_register
  - net/core/rtnetlink.c:rtnl_unregister_all
  - net/core/rtnetlink.c:rtnl_unregister_all
  - net/core/rtnetlink.c:rtnl_unregister
  - net/core/rtnetlink.c:rtnl_unregister
  - net/core/rtnetlink.c:rtnl_register_internal
  - net/core/rtnetlink.c:rtnl_register_internal
```
**Symbols:**

```
c000000000cb78a0-c000000000cb7c6c: netdev_run_todo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void netdev_run_todo();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe000760e7c)
Location: net/core/dev.c:9291
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/core/rtnetlink.c:rtnl_af_register
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/core/rtnetlink.c:rtnl_link_register
  - net/core/rtnetlink.c:rtnl_register_internal
```
**Symbols:**

```
ffffffe000760e7c-ffffffe0007610d4: netdev_run_todo (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void netdev_run_todo();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:9291
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/core/rtnetlink.c:rtnl_af_register
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/core/rtnetlink.c:rtnl_link_register
  - net/core/rtnetlink.c:rtnl_register_internal
```
**Symbols:**

```
ffffffff818d9c50-ffffffff818d9c89: netdev_run_todo.cold (STB_LOCAL)
ffffffff818d8f70-ffffffff818d91fc: netdev_run_todo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void netdev_run_todo();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:9291
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/core/rtnetlink.c:rtnl_af_register
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/core/rtnetlink.c:rtnl_link_register
  - net/core/rtnetlink.c:rtnl_register_internal
```
**Symbols:**

```
ffffffff81893a90-ffffffff81893ac9: netdev_run_todo.cold (STB_LOCAL)
ffffffff81892db0-ffffffff8189303c: netdev_run_todo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void netdev_run_todo();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:9291
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/core/rtnetlink.c:rtnl_af_register
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/core/rtnetlink.c:rtnl_link_register
  - net/core/rtnetlink.c:rtnl_register_internal
```
**Symbols:**

```
ffffffff8192ac80-ffffffff8192acb9: netdev_run_todo.cold (STB_LOCAL)
ffffffff81929fa0-ffffffff8192a22c: netdev_run_todo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void netdev_run_todo();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:9291
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_rcv_msg
  - net/core/rtnetlink.c:rtnl_af_unregister
  - net/core/rtnetlink.c:rtnl_af_register
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/core/rtnetlink.c:rtnl_link_register
  - net/core/rtnetlink.c:rtnl_register_internal
```
**Symbols:**

```
ffffffff8194c350-ffffffff8194c389: netdev_run_todo.cold (STB_LOCAL)
ffffffff8194b670-ffffffff8194b8fc: netdev_run_todo (STB_GLOBAL)
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
