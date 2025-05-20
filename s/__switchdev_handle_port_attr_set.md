# Function: <code>__switchdev_handle_port_attr_set</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
int __switchdev_handle_port_attr_set(struct net_device *dev, struct switchdev_notifier_port_attr_info *port_attr_info, bool (*check_cb)(const struct net_device *), int (*set_cb)(struct net_device *, const struct switchdev_attr *, struct switchdev_trans *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81a6b8e0)
Location: net/switchdev/switchdev.c:554
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_handle_port_attr_set
  - net/switchdev/switchdev.c:__switchdev_handle_port_attr_set
```
**Symbols:**

```
ffffffff81a6b8e0-ffffffff81a6b9ae: __switchdev_handle_port_attr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __switchdev_handle_port_attr_set(struct net_device *dev, struct switchdev_notifier_port_attr_info *port_attr_info, bool (*check_cb)(const struct net_device *), int (*set_cb)(struct net_device *, const struct switchdev_attr *, struct switchdev_trans *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81aa22c0)
Location: net/switchdev/switchdev.c:554
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_handle_port_attr_set
  - net/switchdev/switchdev.c:__switchdev_handle_port_attr_set
```
**Symbols:**

```
ffffffff81aa22c0-ffffffff81aa238e: __switchdev_handle_port_attr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __switchdev_handle_port_attr_set(struct net_device *dev, struct switchdev_notifier_port_attr_info *port_attr_info, bool (*check_cb)(const struct net_device *), int (*set_cb)(struct net_device *, const struct switchdev_attr *, struct switchdev_trans *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81b9dca0)
Location: net/switchdev/switchdev.c:560
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_handle_port_attr_set
  - net/switchdev/switchdev.c:__switchdev_handle_port_attr_set
```
**Symbols:**

```
ffffffff81b9dca0-ffffffff81b9dd76: __switchdev_handle_port_attr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __switchdev_handle_port_attr_set(struct net_device *dev, struct switchdev_notifier_port_attr_info *port_attr_info, bool (*check_cb)(const struct net_device *), int (*set_cb)(struct net_device *, const struct switchdev_attr *, struct switchdev_trans *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81bad5c0)
Location: net/switchdev/switchdev.c:561
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_handle_port_attr_set
  - net/switchdev/switchdev.c:__switchdev_handle_port_attr_set
```
**Symbols:**

```
ffffffff81bad5c0-ffffffff81bad69b: __switchdev_handle_port_attr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __switchdev_handle_port_attr_set(struct net_device *dev, struct switchdev_notifier_port_attr_info *port_attr_info, bool (*check_cb)(const struct net_device *), int (*set_cb)(struct net_device *, const struct switchdev_attr *, struct netlink_ext_ack *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81b9c7a0)
Location: net/switchdev/switchdev.c:492
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_handle_port_attr_set
  - net/switchdev/switchdev.c:__switchdev_handle_port_attr_set
```
**Symbols:**

```
ffffffff81b9c7a0-ffffffff81b9c87a: __switchdev_handle_port_attr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __switchdev_handle_port_attr_set(struct net_device *dev, struct switchdev_notifier_port_attr_info *port_attr_info, bool (*check_cb)(const struct net_device *), int (*set_cb)(struct net_device *, const void *, const struct switchdev_attr *, struct netlink_ext_ack *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81c694d0)
Location: net/switchdev/switchdev.c:754
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_handle_port_attr_set
  - net/switchdev/switchdev.c:__switchdev_handle_port_attr_set
```
**Symbols:**

```
ffffffff81c694d0-ffffffff81c695ae: __switchdev_handle_port_attr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __switchdev_handle_port_attr_set(struct net_device *dev, struct switchdev_notifier_port_attr_info *port_attr_info, bool (*check_cb)(const struct net_device *), int (*set_cb)(struct net_device *, const void *, const struct switchdev_attr *, struct netlink_ext_ack *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81e0c560)
Location: net/switchdev/switchdev.c:759
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_handle_port_attr_set
  - net/switchdev/switchdev.c:__switchdev_handle_port_attr_set
```
**Symbols:**

```
ffffffff81e0c560-ffffffff81e0c657: __switchdev_handle_port_attr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __switchdev_handle_port_attr_set(struct net_device *dev, struct switchdev_notifier_port_attr_info *port_attr_info, bool (*check_cb)(const struct net_device *), int (*set_cb)(struct net_device *, const void *, const struct switchdev_attr *, struct netlink_ext_ack *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81fe2670)
Location: net/switchdev/switchdev.c:759
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_handle_port_attr_set
  - net/switchdev/switchdev.c:__switchdev_handle_port_attr_set
```
**Symbols:**

```
ffffffff81fe2670-ffffffff81fe2767: __switchdev_handle_port_attr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __switchdev_handle_port_attr_set(struct net_device *dev, struct switchdev_notifier_port_attr_info *port_attr_info, bool (*check_cb)(const struct net_device *), int (*set_cb)(struct net_device *, const void *, const struct switchdev_attr *, struct netlink_ext_ack *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff8205e990)
Location: net/switchdev/switchdev.c:759
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_handle_port_attr_set
  - net/switchdev/switchdev.c:__switchdev_handle_port_attr_set
```
**Symbols:**

```
ffffffff8205e990-ffffffff8205ea87: __switchdev_handle_port_attr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __switchdev_handle_port_attr_set(struct net_device *dev, struct switchdev_notifier_port_attr_info *port_attr_info, bool (*check_cb)(const struct net_device *), int (*set_cb)(struct net_device *, const void *, const struct switchdev_attr *, struct netlink_ext_ack *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff82131670)
Location: net/switchdev/switchdev.c:832
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_handle_port_attr_set
  - net/switchdev/switchdev.c:__switchdev_handle_port_attr_set
```
**Symbols:**

```
ffffffff82131670-ffffffff82131763: __switchdev_handle_port_attr_set (STB_LOCAL)
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
int __switchdev_handle_port_attr_set(struct net_device *dev, struct switchdev_notifier_port_attr_info *port_attr_info, bool (*check_cb)(const struct net_device *), int (*set_cb)(struct net_device *, const struct switchdev_attr *, struct switchdev_trans *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffff800010d73940)
Location: net/switchdev/switchdev.c:554
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_handle_port_attr_set
  - net/switchdev/switchdev.c:__switchdev_handle_port_attr_set
```
**Symbols:**

```
ffff800010d73940-ffff800010d73a38: __switchdev_handle_port_attr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __switchdev_handle_port_attr_set(struct net_device *dev, struct switchdev_notifier_port_attr_info *port_attr_info, bool (*check_cb)(const struct net_device *), int (*set_cb)(struct net_device *, const struct switchdev_attr *, struct switchdev_trans *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (c0e708e4)
Location: net/switchdev/switchdev.c:554
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_handle_port_attr_set
  - net/switchdev/switchdev.c:__switchdev_handle_port_attr_set
```
**Symbols:**

```
c0e708e4-c0e709cc: __switchdev_handle_port_attr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __switchdev_handle_port_attr_set(struct net_device *dev, struct switchdev_notifier_port_attr_info *port_attr_info, bool (*check_cb)(const struct net_device *), int (*set_cb)(struct net_device *, const struct switchdev_attr *, struct switchdev_trans *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (c000000000eb2f40)
Location: net/switchdev/switchdev.c:554
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_handle_port_attr_set
  - net/switchdev/switchdev.c:__switchdev_handle_port_attr_set
```
**Symbols:**

```
c000000000eb2f40-c000000000eb3080: __switchdev_handle_port_attr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __switchdev_handle_port_attr_set(struct net_device *dev, struct switchdev_notifier_port_attr_info *port_attr_info, bool (*check_cb)(const struct net_device *), int (*set_cb)(struct net_device *, const struct switchdev_attr *, struct switchdev_trans *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffe0008a3cdc)
Location: net/switchdev/switchdev.c:554
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_handle_port_attr_set
  - net/switchdev/switchdev.c:__switchdev_handle_port_attr_set
```
**Symbols:**

```
ffffffe0008a3cdc-ffffffe0008a3d7c: __switchdev_handle_port_attr_set (STB_LOCAL)
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
int __switchdev_handle_port_attr_set(struct net_device *dev, struct switchdev_notifier_port_attr_info *port_attr_info, bool (*check_cb)(const struct net_device *), int (*set_cb)(struct net_device *, const struct switchdev_attr *, struct switchdev_trans *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81a41650)
Location: net/switchdev/switchdev.c:554
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_handle_port_attr_set
  - net/switchdev/switchdev.c:__switchdev_handle_port_attr_set
```
**Symbols:**

```
ffffffff81a41650-ffffffff81a4171e: __switchdev_handle_port_attr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __switchdev_handle_port_attr_set(struct net_device *dev, struct switchdev_notifier_port_attr_info *port_attr_info, bool (*check_cb)(const struct net_device *), int (*set_cb)(struct net_device *, const struct switchdev_attr *, struct switchdev_trans *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff819fe240)
Location: net/switchdev/switchdev.c:554
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_handle_port_attr_set
  - net/switchdev/switchdev.c:__switchdev_handle_port_attr_set
```
**Symbols:**

```
ffffffff819fe240-ffffffff819fe30e: __switchdev_handle_port_attr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __switchdev_handle_port_attr_set(struct net_device *dev, struct switchdev_notifier_port_attr_info *port_attr_info, bool (*check_cb)(const struct net_device *), int (*set_cb)(struct net_device *, const struct switchdev_attr *, struct switchdev_trans *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81aad500)
Location: net/switchdev/switchdev.c:554
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_handle_port_attr_set
  - net/switchdev/switchdev.c:__switchdev_handle_port_attr_set
```
**Symbols:**

```
ffffffff81aad500-ffffffff81aad5ce: __switchdev_handle_port_attr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __switchdev_handle_port_attr_set(struct net_device *dev, struct switchdev_notifier_port_attr_info *port_attr_info, bool (*check_cb)(const struct net_device *), int (*set_cb)(struct net_device *, const struct switchdev_attr *, struct switchdev_trans *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81ab9870)
Location: net/switchdev/switchdev.c:554
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_handle_port_attr_set
  - net/switchdev/switchdev.c:__switchdev_handle_port_attr_set
```
**Symbols:**

```
ffffffff81ab9870-ffffffff81ab993e: __switchdev_handle_port_attr_set (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<code>int (*set_cb)(struct net_device *, const struct switchdev_attr *, struct switchdev_trans *)</code> ➡️ <code>int (*set_cb)(struct net_device *, const struct switchdev_attr *, struct netlink_ext_ack *)</code>
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
<code>int (*set_cb)(struct net_device *, const struct switchdev_attr *, struct netlink_ext_ack *)</code> ➡️ <code>int (*set_cb)(struct net_device *, const void *, const struct switchdev_attr *, struct netlink_ext_ack *)</code>
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
