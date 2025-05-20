# Function: <code>switchdev_handle_port_attr_set</code>

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
int switchdev_handle_port_attr_set(struct net_device *dev, struct switchdev_notifier_port_attr_info *port_attr_info, bool (*check_cb)(const struct net_device *), int (*set_cb)(struct net_device *, const struct switchdev_attr *, struct switchdev_trans *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81a6b9b0)
Location: net/switchdev/switchdev.c:588
Inline: False
```
**Symbols:**

```
ffffffff81a6b9b0-ffffffff81a6b9cb: switchdev_handle_port_attr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int switchdev_handle_port_attr_set(struct net_device *dev, struct switchdev_notifier_port_attr_info *port_attr_info, bool (*check_cb)(const struct net_device *), int (*set_cb)(struct net_device *, const struct switchdev_attr *, struct switchdev_trans *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81aa2390)
Location: net/switchdev/switchdev.c:588
Inline: False
```
**Symbols:**

```
ffffffff81aa2390-ffffffff81aa23ab: switchdev_handle_port_attr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int switchdev_handle_port_attr_set(struct net_device *dev, struct switchdev_notifier_port_attr_info *port_attr_info, bool (*check_cb)(const struct net_device *), int (*set_cb)(struct net_device *, const struct switchdev_attr *, struct switchdev_trans *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81b9dd80)
Location: net/switchdev/switchdev.c:597
Inline: False
```
**Symbols:**

```
ffffffff81b9dd80-ffffffff81b9dd9b: switchdev_handle_port_attr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int switchdev_handle_port_attr_set(struct net_device *dev, struct switchdev_notifier_port_attr_info *port_attr_info, bool (*check_cb)(const struct net_device *), int (*set_cb)(struct net_device *, const struct switchdev_attr *, struct switchdev_trans *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81bad6a0)
Location: net/switchdev/switchdev.c:599
Inline: False
```
**Symbols:**

```
ffffffff81bad6a0-ffffffff81bad6bb: switchdev_handle_port_attr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int switchdev_handle_port_attr_set(struct net_device *dev, struct switchdev_notifier_port_attr_info *port_attr_info, bool (*check_cb)(const struct net_device *), int (*set_cb)(struct net_device *, const struct switchdev_attr *, struct netlink_ext_ack *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81b9c880)
Location: net/switchdev/switchdev.c:533
Inline: False
```
**Symbols:**

```
ffffffff81b9c880-ffffffff81b9c898: switchdev_handle_port_attr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int switchdev_handle_port_attr_set(struct net_device *dev, struct switchdev_notifier_port_attr_info *port_attr_info, bool (*check_cb)(const struct net_device *), int (*set_cb)(struct net_device *, const void *, const struct switchdev_attr *, struct netlink_ext_ack *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81c695b0)
Location: net/switchdev/switchdev.c:796
Inline: False
```
**Symbols:**

```
ffffffff81c695b0-ffffffff81c695c8: switchdev_handle_port_attr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int switchdev_handle_port_attr_set(struct net_device *dev, struct switchdev_notifier_port_attr_info *port_attr_info, bool (*check_cb)(const struct net_device *), int (*set_cb)(struct net_device *, const void *, const struct switchdev_attr *, struct netlink_ext_ack *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81e0c660)
Location: net/switchdev/switchdev.c:801
Inline: False
```
**Symbols:**

```
ffffffff81e0c660-ffffffff81e0c684: switchdev_handle_port_attr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int switchdev_handle_port_attr_set(struct net_device *dev, struct switchdev_notifier_port_attr_info *port_attr_info, bool (*check_cb)(const struct net_device *), int (*set_cb)(struct net_device *, const void *, const struct switchdev_attr *, struct netlink_ext_ack *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81fe2780)
Location: net/switchdev/switchdev.c:801
Inline: False
```
**Symbols:**

```
ffffffff81fe2780-ffffffff81fe27a4: switchdev_handle_port_attr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int switchdev_handle_port_attr_set(struct net_device *dev, struct switchdev_notifier_port_attr_info *port_attr_info, bool (*check_cb)(const struct net_device *), int (*set_cb)(struct net_device *, const void *, const struct switchdev_attr *, struct netlink_ext_ack *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff8205eaa0)
Location: net/switchdev/switchdev.c:801
Inline: False
```
**Symbols:**

```
ffffffff8205eaa0-ffffffff8205eac4: switchdev_handle_port_attr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int switchdev_handle_port_attr_set(struct net_device *dev, struct switchdev_notifier_port_attr_info *port_attr_info, bool (*check_cb)(const struct net_device *), int (*set_cb)(struct net_device *, const void *, const struct switchdev_attr *, struct netlink_ext_ack *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff82131780)
Location: net/switchdev/switchdev.c:874
Inline: False
```
**Symbols:**

```
ffffffff82131780-ffffffff821317a4: switchdev_handle_port_attr_set (STB_GLOBAL)
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
int switchdev_handle_port_attr_set(struct net_device *dev, struct switchdev_notifier_port_attr_info *port_attr_info, bool (*check_cb)(const struct net_device *), int (*set_cb)(struct net_device *, const struct switchdev_attr *, struct switchdev_trans *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffff800010d73a38)
Location: net/switchdev/switchdev.c:588
Inline: False
```
**Symbols:**

```
ffff800010d73a38-ffff800010d73a8c: switchdev_handle_port_attr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int switchdev_handle_port_attr_set(struct net_device *dev, struct switchdev_notifier_port_attr_info *port_attr_info, bool (*check_cb)(const struct net_device *), int (*set_cb)(struct net_device *, const struct switchdev_attr *, struct switchdev_trans *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (c0e709cc)
Location: net/switchdev/switchdev.c:588
Inline: False
```
**Symbols:**

```
c0e709cc-c0e709f0: switchdev_handle_port_attr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int switchdev_handle_port_attr_set(struct net_device *dev, struct switchdev_notifier_port_attr_info *port_attr_info, bool (*check_cb)(const struct net_device *), int (*set_cb)(struct net_device *, const struct switchdev_attr *, struct switchdev_trans *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (c000000000eb3080)
Location: net/switchdev/switchdev.c:588
Inline: False
```
**Symbols:**

```
c000000000eb3080-c000000000eb30bc: switchdev_handle_port_attr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int switchdev_handle_port_attr_set(struct net_device *dev, struct switchdev_notifier_port_attr_info *port_attr_info, bool (*check_cb)(const struct net_device *), int (*set_cb)(struct net_device *, const struct switchdev_attr *, struct switchdev_trans *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffe0008a3d7c)
Location: net/switchdev/switchdev.c:588
Inline: False
```
**Symbols:**

```
ffffffe0008a3d7c-ffffffe0008a3dc8: switchdev_handle_port_attr_set (STB_GLOBAL)
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
int switchdev_handle_port_attr_set(struct net_device *dev, struct switchdev_notifier_port_attr_info *port_attr_info, bool (*check_cb)(const struct net_device *), int (*set_cb)(struct net_device *, const struct switchdev_attr *, struct switchdev_trans *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81a41720)
Location: net/switchdev/switchdev.c:588
Inline: False
```
**Symbols:**

```
ffffffff81a41720-ffffffff81a4173b: switchdev_handle_port_attr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int switchdev_handle_port_attr_set(struct net_device *dev, struct switchdev_notifier_port_attr_info *port_attr_info, bool (*check_cb)(const struct net_device *), int (*set_cb)(struct net_device *, const struct switchdev_attr *, struct switchdev_trans *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff819fe310)
Location: net/switchdev/switchdev.c:588
Inline: False
```
**Symbols:**

```
ffffffff819fe310-ffffffff819fe32b: switchdev_handle_port_attr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int switchdev_handle_port_attr_set(struct net_device *dev, struct switchdev_notifier_port_attr_info *port_attr_info, bool (*check_cb)(const struct net_device *), int (*set_cb)(struct net_device *, const struct switchdev_attr *, struct switchdev_trans *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81aad5d0)
Location: net/switchdev/switchdev.c:588
Inline: False
```
**Symbols:**

```
ffffffff81aad5d0-ffffffff81aad5eb: switchdev_handle_port_attr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int switchdev_handle_port_attr_set(struct net_device *dev, struct switchdev_notifier_port_attr_info *port_attr_info, bool (*check_cb)(const struct net_device *), int (*set_cb)(struct net_device *, const struct switchdev_attr *, struct switchdev_trans *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81ab9940)
Location: net/switchdev/switchdev.c:588
Inline: False
```
**Symbols:**

```
ffffffff81ab9940-ffffffff81ab995b: switchdev_handle_port_attr_set (STB_GLOBAL)
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
