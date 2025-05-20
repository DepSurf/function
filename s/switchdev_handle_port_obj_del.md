# Function: <code>switchdev_handle_port_obj_del</code>

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
int switchdev_handle_port_obj_del(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), int (*del_cb)(struct net_device *, const struct switchdev_obj *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff819fc110)
Location: net/switchdev/switchdev.c:704
Inline: False
```
**Symbols:**

```
ffffffff819fc110-ffffffff819fc12b: switchdev_handle_port_obj_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int switchdev_handle_port_obj_del(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), int (*del_cb)(struct net_device *, const struct switchdev_obj *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81a6b8c0)
Location: net/switchdev/switchdev.c:538
Inline: False
```
**Symbols:**

```
ffffffff81a6b8c0-ffffffff81a6b8db: switchdev_handle_port_obj_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int switchdev_handle_port_obj_del(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), int (*del_cb)(struct net_device *, const struct switchdev_obj *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81aa22a0)
Location: net/switchdev/switchdev.c:538
Inline: False
```
**Symbols:**

```
ffffffff81aa22a0-ffffffff81aa22bb: switchdev_handle_port_obj_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int switchdev_handle_port_obj_del(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), int (*del_cb)(struct net_device *, const struct switchdev_obj *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81b9dc80)
Location: net/switchdev/switchdev.c:544
Inline: False
```
**Symbols:**

```
ffffffff81b9dc80-ffffffff81b9dc9b: switchdev_handle_port_obj_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int switchdev_handle_port_obj_del(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), int (*del_cb)(struct net_device *, const struct switchdev_obj *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81bad5a0)
Location: net/switchdev/switchdev.c:545
Inline: False
```
**Symbols:**

```
ffffffff81bad5a0-ffffffff81bad5bb: switchdev_handle_port_obj_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int switchdev_handle_port_obj_del(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), int (*del_cb)(struct net_device *, const struct switchdev_obj *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81b9c780)
Location: net/switchdev/switchdev.c:476
Inline: False
```
**Symbols:**

```
ffffffff81b9c780-ffffffff81b9c798: switchdev_handle_port_obj_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int switchdev_handle_port_obj_del(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), int (*del_cb)(struct net_device *, const void *, const struct switchdev_obj *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81c694b0)
Location: net/switchdev/switchdev.c:738
Inline: False
```
**Symbols:**

```
ffffffff81c694b0-ffffffff81c694c8: switchdev_handle_port_obj_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int switchdev_handle_port_obj_del(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), int (*del_cb)(struct net_device *, const void *, const struct switchdev_obj *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81e0d6b0)
Location: net/switchdev/switchdev.c:721
Inline: False
```
**Symbols:**

```
ffffffff81e0d6b0-ffffffff81e0d6dc: switchdev_handle_port_obj_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int switchdev_handle_port_obj_del(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), int (*del_cb)(struct net_device *, const void *, const struct switchdev_obj *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81fe3940)
Location: net/switchdev/switchdev.c:721
Inline: False
```
**Symbols:**

```
ffffffff81fe3940-ffffffff81fe396c: switchdev_handle_port_obj_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int switchdev_handle_port_obj_del(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), int (*del_cb)(struct net_device *, const void *, const struct switchdev_obj *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff8205fc60)
Location: net/switchdev/switchdev.c:721
Inline: False
```
**Symbols:**

```
ffffffff8205fc60-ffffffff8205fc8c: switchdev_handle_port_obj_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int switchdev_handle_port_obj_del(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), int (*del_cb)(struct net_device *, const void *, const struct switchdev_obj *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff82132ba0)
Location: net/switchdev/switchdev.c:794
Inline: False
```
**Symbols:**

```
ffffffff82132ba0-ffffffff82132bcc: switchdev_handle_port_obj_del (STB_GLOBAL)
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
int switchdev_handle_port_obj_del(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), int (*del_cb)(struct net_device *, const struct switchdev_obj *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffff800010d738e8)
Location: net/switchdev/switchdev.c:538
Inline: False
```
**Symbols:**

```
ffff800010d738e8-ffff800010d7393c: switchdev_handle_port_obj_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int switchdev_handle_port_obj_del(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), int (*del_cb)(struct net_device *, const struct switchdev_obj *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (c0e708c0)
Location: net/switchdev/switchdev.c:538
Inline: False
```
**Symbols:**

```
c0e708c0-c0e708e4: switchdev_handle_port_obj_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int switchdev_handle_port_obj_del(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), int (*del_cb)(struct net_device *, const struct switchdev_obj *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (c000000000eb2f00)
Location: net/switchdev/switchdev.c:538
Inline: False
```
**Symbols:**

```
c000000000eb2f00-c000000000eb2f3c: switchdev_handle_port_obj_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int switchdev_handle_port_obj_del(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), int (*del_cb)(struct net_device *, const struct switchdev_obj *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffe0008a3c90)
Location: net/switchdev/switchdev.c:538
Inline: False
```
**Symbols:**

```
ffffffe0008a3c90-ffffffe0008a3cdc: switchdev_handle_port_obj_del (STB_GLOBAL)
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
int switchdev_handle_port_obj_del(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), int (*del_cb)(struct net_device *, const struct switchdev_obj *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81a41630)
Location: net/switchdev/switchdev.c:538
Inline: False
```
**Symbols:**

```
ffffffff81a41630-ffffffff81a4164b: switchdev_handle_port_obj_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int switchdev_handle_port_obj_del(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), int (*del_cb)(struct net_device *, const struct switchdev_obj *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff819fe220)
Location: net/switchdev/switchdev.c:538
Inline: False
```
**Symbols:**

```
ffffffff819fe220-ffffffff819fe23b: switchdev_handle_port_obj_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int switchdev_handle_port_obj_del(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), int (*del_cb)(struct net_device *, const struct switchdev_obj *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81aad4e0)
Location: net/switchdev/switchdev.c:538
Inline: False
```
**Symbols:**

```
ffffffff81aad4e0-ffffffff81aad4fb: switchdev_handle_port_obj_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int switchdev_handle_port_obj_del(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), int (*del_cb)(struct net_device *, const struct switchdev_obj *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81ab9850)
Location: net/switchdev/switchdev.c:538
Inline: False
```
**Symbols:**

```
ffffffff81ab9850-ffffffff81ab986b: switchdev_handle_port_obj_del (STB_GLOBAL)
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int (*del_cb)(struct net_device *, const struct switchdev_obj *)</code> ➡️ <code>int (*del_cb)(struct net_device *, const void *, const struct switchdev_obj *)</code>
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
