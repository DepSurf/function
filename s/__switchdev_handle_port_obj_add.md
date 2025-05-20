# Function: <code>__switchdev_handle_port_obj_add</code>

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
int __switchdev_handle_port_obj_add(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), int (*add_cb)(struct net_device *, const struct switchdev_obj *, struct switchdev_trans *, struct netlink_ext_ack *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff819fbf50)
Location: net/switchdev/switchdev.c:614
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_handle_port_obj_add
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
```
**Symbols:**

```
ffffffff819fbf50-ffffffff819fc020: __switchdev_handle_port_obj_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __switchdev_handle_port_obj_add(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), int (*add_cb)(struct net_device *, const struct switchdev_obj *, struct switchdev_trans *, struct netlink_ext_ack *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81a6b6f0)
Location: net/switchdev/switchdev.c:448
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_handle_port_obj_add
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
```
**Symbols:**

```
ffffffff81a6b6f0-ffffffff81a6b7c5: __switchdev_handle_port_obj_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __switchdev_handle_port_obj_add(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), int (*add_cb)(struct net_device *, const struct switchdev_obj *, struct switchdev_trans *, struct netlink_ext_ack *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81aa20d0)
Location: net/switchdev/switchdev.c:448
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_handle_port_obj_add
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
```
**Symbols:**

```
ffffffff81aa20d0-ffffffff81aa21a5: __switchdev_handle_port_obj_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __switchdev_handle_port_obj_add(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), int (*add_cb)(struct net_device *, const struct switchdev_obj *, struct switchdev_trans *, struct netlink_ext_ack *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81b9daa0)
Location: net/switchdev/switchdev.c:448
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_handle_port_obj_add
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
```
**Symbols:**

```
ffffffff81b9daa0-ffffffff81b9db7d: __switchdev_handle_port_obj_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __switchdev_handle_port_obj_add(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), int (*add_cb)(struct net_device *, const struct switchdev_obj *, struct switchdev_trans *, struct netlink_ext_ack *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81bad3b0)
Location: net/switchdev/switchdev.c:447
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_handle_port_obj_add
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
```
**Symbols:**

```
ffffffff81bad3b0-ffffffff81bad492: __switchdev_handle_port_obj_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __switchdev_handle_port_obj_add(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), int (*add_cb)(struct net_device *, const struct switchdev_obj *, struct netlink_ext_ack *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81b9c5a0)
Location: net/switchdev/switchdev.c:381
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_handle_port_obj_add
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
```
**Symbols:**

```
ffffffff81b9c5a0-ffffffff81b9c67a: __switchdev_handle_port_obj_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __switchdev_handle_port_obj_add(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), int (*add_cb)(struct net_device *, const void *, const struct switchdev_obj *, struct netlink_ext_ack *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81c692d0)
Location: net/switchdev/switchdev.c:641
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_handle_port_obj_add
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
```
**Symbols:**

```
ffffffff81c692d0-ffffffff81c693ae: __switchdev_handle_port_obj_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __switchdev_handle_port_obj_add(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), bool (*foreign_dev_check_cb)(const struct net_device *, const struct net_device *), int (*add_cb)(struct net_device *, const void *, const struct switchdev_obj *, struct netlink_ext_ack *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81e0d240)
Location: net/switchdev/switchdev.c:535
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_handle_port_obj_add_foreign
  - net/switchdev/switchdev.c:switchdev_handle_port_obj_add
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
```
**Symbols:**

```
ffffffff81e0d240-ffffffff81e0d448: __switchdev_handle_port_obj_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __switchdev_handle_port_obj_add(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), bool (*foreign_dev_check_cb)(const struct net_device *, const struct net_device *), int (*add_cb)(struct net_device *, const void *, const struct switchdev_obj *, struct netlink_ext_ack *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81fe3490)
Location: net/switchdev/switchdev.c:535
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_handle_port_obj_add_foreign
  - net/switchdev/switchdev.c:switchdev_handle_port_obj_add
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
```
**Symbols:**

```
ffffffff81fe3490-ffffffff81fe3698: __switchdev_handle_port_obj_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __switchdev_handle_port_obj_add(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), bool (*foreign_dev_check_cb)(const struct net_device *, const struct net_device *), int (*add_cb)(struct net_device *, const void *, const struct switchdev_obj *, struct netlink_ext_ack *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff8205f7b0)
Location: net/switchdev/switchdev.c:535
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_handle_port_obj_add_foreign
  - net/switchdev/switchdev.c:switchdev_handle_port_obj_add
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
```
**Symbols:**

```
ffffffff8205f7b0-ffffffff8205f9b8: __switchdev_handle_port_obj_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __switchdev_handle_port_obj_add(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), bool (*foreign_dev_check_cb)(const struct net_device *, const struct net_device *), int (*add_cb)(struct net_device *, const void *, const struct switchdev_obj *, struct netlink_ext_ack *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff82132700)
Location: net/switchdev/switchdev.c:608
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_handle_port_obj_add_foreign
  - net/switchdev/switchdev.c:switchdev_handle_port_obj_add
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
```
**Symbols:**

```
ffffffff82132700-ffffffff82132900: __switchdev_handle_port_obj_add (STB_LOCAL)
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
int __switchdev_handle_port_obj_add(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), int (*add_cb)(struct net_device *, const struct switchdev_obj *, struct switchdev_trans *, struct netlink_ext_ack *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffff800010d73698)
Location: net/switchdev/switchdev.c:448
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_handle_port_obj_add
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
```
**Symbols:**

```
ffff800010d73698-ffff800010d73798: __switchdev_handle_port_obj_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __switchdev_handle_port_obj_add(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), int (*add_cb)(struct net_device *, const struct switchdev_obj *, struct switchdev_trans *, struct netlink_ext_ack *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (c0e706c8)
Location: net/switchdev/switchdev.c:448
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_handle_port_obj_add
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
```
**Symbols:**

```
c0e706c8-c0e707b8: __switchdev_handle_port_obj_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __switchdev_handle_port_obj_add(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), int (*add_cb)(struct net_device *, const struct switchdev_obj *, struct switchdev_trans *, struct netlink_ext_ack *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (c000000000eb2c30)
Location: net/switchdev/switchdev.c:448
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_handle_port_obj_add
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
```
**Symbols:**

```
c000000000eb2c30-c000000000eb2d80: __switchdev_handle_port_obj_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __switchdev_handle_port_obj_add(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), int (*add_cb)(struct net_device *, const struct switchdev_obj *, struct switchdev_trans *, struct netlink_ext_ack *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffe0008a3b02)
Location: net/switchdev/switchdev.c:448
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_handle_port_obj_add
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
```
**Symbols:**

```
ffffffe0008a3b02-ffffffe0008a3ba8: __switchdev_handle_port_obj_add (STB_LOCAL)
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
int __switchdev_handle_port_obj_add(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), int (*add_cb)(struct net_device *, const struct switchdev_obj *, struct switchdev_trans *, struct netlink_ext_ack *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81a41460)
Location: net/switchdev/switchdev.c:448
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_handle_port_obj_add
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
```
**Symbols:**

```
ffffffff81a41460-ffffffff81a41535: __switchdev_handle_port_obj_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __switchdev_handle_port_obj_add(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), int (*add_cb)(struct net_device *, const struct switchdev_obj *, struct switchdev_trans *, struct netlink_ext_ack *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff819fe050)
Location: net/switchdev/switchdev.c:448
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_handle_port_obj_add
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
```
**Symbols:**

```
ffffffff819fe050-ffffffff819fe125: __switchdev_handle_port_obj_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __switchdev_handle_port_obj_add(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), int (*add_cb)(struct net_device *, const struct switchdev_obj *, struct switchdev_trans *, struct netlink_ext_ack *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81aad310)
Location: net/switchdev/switchdev.c:448
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_handle_port_obj_add
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
```
**Symbols:**

```
ffffffff81aad310-ffffffff81aad3e5: __switchdev_handle_port_obj_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __switchdev_handle_port_obj_add(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), int (*add_cb)(struct net_device *, const struct switchdev_obj *, struct switchdev_trans *, struct netlink_ext_ack *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81ab9680)
Location: net/switchdev/switchdev.c:448
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_handle_port_obj_add
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_add
```
**Symbols:**

```
ffffffff81ab9680-ffffffff81ab9755: __switchdev_handle_port_obj_add (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool (*foreign_dev_check_cb)(const struct net_device *, const struct net_device *)</code>
</li>
<li>
<b>Param reordered. </b>
<code>dev, port_obj_info, check_cb, add_cb</code> ➡️ <code>dev, port_obj_info, check_cb, foreign_dev_check_cb, add_cb</code>
</li>
</ul>
</details>
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
