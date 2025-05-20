# Function: <code>__switchdev_handle_port_obj_del</code>

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
int __switchdev_handle_port_obj_del(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), int (*del_cb)(struct net_device *, const struct switchdev_obj *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff819fc040)
Location: net/switchdev/switchdev.c:671
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
```
**Symbols:**

```
ffffffff819fc040-ffffffff819fc103: __switchdev_handle_port_obj_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __switchdev_handle_port_obj_del(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), int (*del_cb)(struct net_device *, const struct switchdev_obj *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81a6b7f0)
Location: net/switchdev/switchdev.c:505
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
```
**Symbols:**

```
ffffffff81a6b7f0-ffffffff81a6b8ba: __switchdev_handle_port_obj_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __switchdev_handle_port_obj_del(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), int (*del_cb)(struct net_device *, const struct switchdev_obj *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81aa21d0)
Location: net/switchdev/switchdev.c:505
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
```
**Symbols:**

```
ffffffff81aa21d0-ffffffff81aa229a: __switchdev_handle_port_obj_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __switchdev_handle_port_obj_del(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), int (*del_cb)(struct net_device *, const struct switchdev_obj *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81b9dba0)
Location: net/switchdev/switchdev.c:508
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
```
**Symbols:**

```
ffffffff81b9dba0-ffffffff81b9dc72: __switchdev_handle_port_obj_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __switchdev_handle_port_obj_del(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), int (*del_cb)(struct net_device *, const struct switchdev_obj *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81bad4c0)
Location: net/switchdev/switchdev.c:508
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
```
**Symbols:**

```
ffffffff81bad4c0-ffffffff81bad598: __switchdev_handle_port_obj_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __switchdev_handle_port_obj_del(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), int (*del_cb)(struct net_device *, const struct switchdev_obj *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81b9c6a0)
Location: net/switchdev/switchdev.c:439
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
```
**Symbols:**

```
ffffffff81b9c6a0-ffffffff81b9c776: __switchdev_handle_port_obj_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __switchdev_handle_port_obj_del(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), int (*del_cb)(struct net_device *, const void *, const struct switchdev_obj *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81c693d0)
Location: net/switchdev/switchdev.c:700
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
```
**Symbols:**

```
ffffffff81c693d0-ffffffff81c694a7: __switchdev_handle_port_obj_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __switchdev_handle_port_obj_del(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), bool (*foreign_dev_check_cb)(const struct net_device *, const struct net_device *), int (*del_cb)(struct net_device *, const void *, const struct switchdev_obj *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81e0d4b0)
Location: net/switchdev/switchdev.c:650
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_handle_port_obj_del_foreign
  - net/switchdev/switchdev.c:switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
```
**Symbols:**

```
ffffffff81e0d4b0-ffffffff81e0d6b0: __switchdev_handle_port_obj_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __switchdev_handle_port_obj_del(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), bool (*foreign_dev_check_cb)(const struct net_device *, const struct net_device *), int (*del_cb)(struct net_device *, const void *, const struct switchdev_obj *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81fe3730)
Location: net/switchdev/switchdev.c:650
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_handle_port_obj_del_foreign
  - net/switchdev/switchdev.c:switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
```
**Symbols:**

```
ffffffff81fe3730-ffffffff81fe3930: __switchdev_handle_port_obj_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __switchdev_handle_port_obj_del(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), bool (*foreign_dev_check_cb)(const struct net_device *, const struct net_device *), int (*del_cb)(struct net_device *, const void *, const struct switchdev_obj *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff8205fa50)
Location: net/switchdev/switchdev.c:650
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_handle_port_obj_del_foreign
  - net/switchdev/switchdev.c:switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
```
**Symbols:**

```
ffffffff8205fa50-ffffffff8205fc50: __switchdev_handle_port_obj_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __switchdev_handle_port_obj_del(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), bool (*foreign_dev_check_cb)(const struct net_device *, const struct net_device *), int (*del_cb)(struct net_device *, const void *, const struct switchdev_obj *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff82132990)
Location: net/switchdev/switchdev.c:723
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_handle_port_obj_del_foreign
  - net/switchdev/switchdev.c:switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
```
**Symbols:**

```
ffffffff82132990-ffffffff82132b88: __switchdev_handle_port_obj_del (STB_LOCAL)
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
int __switchdev_handle_port_obj_del(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), int (*del_cb)(struct net_device *, const struct switchdev_obj *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffff800010d737f0)
Location: net/switchdev/switchdev.c:505
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
```
**Symbols:**

```
ffff800010d737f0-ffff800010d738e8: __switchdev_handle_port_obj_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __switchdev_handle_port_obj_del(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), int (*del_cb)(struct net_device *, const struct switchdev_obj *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (c0e707dc)
Location: net/switchdev/switchdev.c:505
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
```
**Symbols:**

```
c0e707dc-c0e708c0: __switchdev_handle_port_obj_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __switchdev_handle_port_obj_del(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), int (*del_cb)(struct net_device *, const struct switchdev_obj *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (c000000000eb2dc0)
Location: net/switchdev/switchdev.c:505
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
```
**Symbols:**

```
c000000000eb2dc0-c000000000eb2f00: __switchdev_handle_port_obj_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __switchdev_handle_port_obj_del(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), int (*del_cb)(struct net_device *, const struct switchdev_obj *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffe0008a3bf4)
Location: net/switchdev/switchdev.c:505
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
```
**Symbols:**

```
ffffffe0008a3bf4-ffffffe0008a3c90: __switchdev_handle_port_obj_del (STB_LOCAL)
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
int __switchdev_handle_port_obj_del(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), int (*del_cb)(struct net_device *, const struct switchdev_obj *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81a41560)
Location: net/switchdev/switchdev.c:505
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
```
**Symbols:**

```
ffffffff81a41560-ffffffff81a4162a: __switchdev_handle_port_obj_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __switchdev_handle_port_obj_del(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), int (*del_cb)(struct net_device *, const struct switchdev_obj *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff819fe150)
Location: net/switchdev/switchdev.c:505
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
```
**Symbols:**

```
ffffffff819fe150-ffffffff819fe21a: __switchdev_handle_port_obj_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __switchdev_handle_port_obj_del(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), int (*del_cb)(struct net_device *, const struct switchdev_obj *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81aad410)
Location: net/switchdev/switchdev.c:505
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
```
**Symbols:**

```
ffffffff81aad410-ffffffff81aad4da: __switchdev_handle_port_obj_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __switchdev_handle_port_obj_del(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), int (*del_cb)(struct net_device *, const struct switchdev_obj *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81ab9780)
Location: net/switchdev/switchdev.c:505
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_handle_port_obj_del
  - net/switchdev/switchdev.c:__switchdev_handle_port_obj_del
```
**Symbols:**

```
ffffffff81ab9780-ffffffff81ab984a: __switchdev_handle_port_obj_del (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool (*foreign_dev_check_cb)(const struct net_device *, const struct net_device *)</code>
</li>
<li>
<b>Param reordered. </b>
<code>dev, port_obj_info, check_cb, del_cb</code> ➡️ <code>dev, port_obj_info, check_cb, foreign_dev_check_cb, del_cb</code>
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
