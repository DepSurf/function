# Function: <code>switchdev_handle_port_obj_add</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int switchdev_handle_port_obj_add(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), int (*add_cb)(struct net_device *, const struct switchdev_obj *, struct switchdev_trans *, struct netlink_ext_ack *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff819fc020)
Location: net/switchdev/switchdev.c:653
Inline: False
```
**Symbols:**

```
ffffffff819fc020-ffffffff819fc03b: switchdev_handle_port_obj_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int switchdev_handle_port_obj_add(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), int (*add_cb)(struct net_device *, const struct switchdev_obj *, struct switchdev_trans *, struct netlink_ext_ack *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81a6b7d0)
Location: net/switchdev/switchdev.c:487
Inline: False
```
**Symbols:**

```
ffffffff81a6b7d0-ffffffff81a6b7eb: switchdev_handle_port_obj_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int switchdev_handle_port_obj_add(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), int (*add_cb)(struct net_device *, const struct switchdev_obj *, struct switchdev_trans *, struct netlink_ext_ack *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81aa21b0)
Location: net/switchdev/switchdev.c:487
Inline: False
```
**Symbols:**

```
ffffffff81aa21b0-ffffffff81aa21cb: switchdev_handle_port_obj_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int switchdev_handle_port_obj_add(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), int (*add_cb)(struct net_device *, const struct switchdev_obj *, struct switchdev_trans *, struct netlink_ext_ack *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81b9db80)
Location: net/switchdev/switchdev.c:490
Inline: False
```
**Symbols:**

```
ffffffff81b9db80-ffffffff81b9db9b: switchdev_handle_port_obj_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int switchdev_handle_port_obj_add(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), int (*add_cb)(struct net_device *, const struct switchdev_obj *, struct switchdev_trans *, struct netlink_ext_ack *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81bad4a0)
Location: net/switchdev/switchdev.c:490
Inline: False
```
**Symbols:**

```
ffffffff81bad4a0-ffffffff81bad4bb: switchdev_handle_port_obj_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int switchdev_handle_port_obj_add(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), int (*add_cb)(struct net_device *, const struct switchdev_obj *, struct netlink_ext_ack *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81b9c680)
Location: net/switchdev/switchdev.c:422
Inline: False
```
**Symbols:**

```
ffffffff81b9c680-ffffffff81b9c698: switchdev_handle_port_obj_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int switchdev_handle_port_obj_add(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), int (*add_cb)(struct net_device *, const void *, const struct switchdev_obj *, struct netlink_ext_ack *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81c693b0)
Location: net/switchdev/switchdev.c:683
Inline: False
```
**Symbols:**

```
ffffffff81c693b0-ffffffff81c693c8: switchdev_handle_port_obj_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int switchdev_handle_port_obj_add(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), int (*add_cb)(struct net_device *, const void *, const struct switchdev_obj *, struct netlink_ext_ack *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81e0d450)
Location: net/switchdev/switchdev.c:610
Inline: False
```
**Symbols:**

```
ffffffff81e0d450-ffffffff81e0d47c: switchdev_handle_port_obj_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int switchdev_handle_port_obj_add(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), int (*add_cb)(struct net_device *, const void *, const struct switchdev_obj *, struct netlink_ext_ack *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81fe36b0)
Location: net/switchdev/switchdev.c:610
Inline: False
```
**Symbols:**

```
ffffffff81fe36b0-ffffffff81fe36dc: switchdev_handle_port_obj_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int switchdev_handle_port_obj_add(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), int (*add_cb)(struct net_device *, const void *, const struct switchdev_obj *, struct netlink_ext_ack *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff8205f9d0)
Location: net/switchdev/switchdev.c:610
Inline: False
```
**Symbols:**

```
ffffffff8205f9d0-ffffffff8205f9fc: switchdev_handle_port_obj_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int switchdev_handle_port_obj_add(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), int (*add_cb)(struct net_device *, const void *, const struct switchdev_obj *, struct netlink_ext_ack *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff82132910)
Location: net/switchdev/switchdev.c:683
Inline: False
```
**Symbols:**

```
ffffffff82132910-ffffffff8213293c: switchdev_handle_port_obj_add (STB_GLOBAL)
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
int switchdev_handle_port_obj_add(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), int (*add_cb)(struct net_device *, const struct switchdev_obj *, struct switchdev_trans *, struct netlink_ext_ack *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffff800010d73798)
Location: net/switchdev/switchdev.c:487
Inline: False
```
**Symbols:**

```
ffff800010d73798-ffff800010d737ec: switchdev_handle_port_obj_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int switchdev_handle_port_obj_add(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), int (*add_cb)(struct net_device *, const struct switchdev_obj *, struct switchdev_trans *, struct netlink_ext_ack *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (c0e707b8)
Location: net/switchdev/switchdev.c:487
Inline: False
```
**Symbols:**

```
c0e707b8-c0e707dc: switchdev_handle_port_obj_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int switchdev_handle_port_obj_add(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), int (*add_cb)(struct net_device *, const struct switchdev_obj *, struct switchdev_trans *, struct netlink_ext_ack *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (c000000000eb2d80)
Location: net/switchdev/switchdev.c:487
Inline: False
```
**Symbols:**

```
c000000000eb2d80-c000000000eb2dbc: switchdev_handle_port_obj_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int switchdev_handle_port_obj_add(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), int (*add_cb)(struct net_device *, const struct switchdev_obj *, struct switchdev_trans *, struct netlink_ext_ack *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffe0008a3ba8)
Location: net/switchdev/switchdev.c:487
Inline: False
```
**Symbols:**

```
ffffffe0008a3ba8-ffffffe0008a3bf4: switchdev_handle_port_obj_add (STB_GLOBAL)
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
int switchdev_handle_port_obj_add(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), int (*add_cb)(struct net_device *, const struct switchdev_obj *, struct switchdev_trans *, struct netlink_ext_ack *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81a41540)
Location: net/switchdev/switchdev.c:487
Inline: False
```
**Symbols:**

```
ffffffff81a41540-ffffffff81a4155b: switchdev_handle_port_obj_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int switchdev_handle_port_obj_add(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), int (*add_cb)(struct net_device *, const struct switchdev_obj *, struct switchdev_trans *, struct netlink_ext_ack *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff819fe130)
Location: net/switchdev/switchdev.c:487
Inline: False
```
**Symbols:**

```
ffffffff819fe130-ffffffff819fe14b: switchdev_handle_port_obj_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int switchdev_handle_port_obj_add(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), int (*add_cb)(struct net_device *, const struct switchdev_obj *, struct switchdev_trans *, struct netlink_ext_ack *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81aad3f0)
Location: net/switchdev/switchdev.c:487
Inline: False
```
**Symbols:**

```
ffffffff81aad3f0-ffffffff81aad40b: switchdev_handle_port_obj_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int switchdev_handle_port_obj_add(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), int (*add_cb)(struct net_device *, const struct switchdev_obj *, struct switchdev_trans *, struct netlink_ext_ack *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81ab9760)
Location: net/switchdev/switchdev.c:487
Inline: False
```
**Symbols:**

```
ffffffff81ab9760-ffffffff81ab977b: switchdev_handle_port_obj_add (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int (*add_cb)(struct net_device *, const struct switchdev_obj *, struct switchdev_trans *, struct netlink_ext_ack *)</code> ➡️ <code>int (*add_cb)(struct net_device *, const struct switchdev_obj *, struct netlink_ext_ack *)</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int (*add_cb)(struct net_device *, const struct switchdev_obj *, struct netlink_ext_ack *)</code> ➡️ <code>int (*add_cb)(struct net_device *, const void *, const struct switchdev_obj *, struct netlink_ext_ack *)</code>
</li>
</ul>
</details>
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
