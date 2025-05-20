# Function: <code>switchdev_port_obj_notify</code>

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
int switchdev_port_obj_notify(enum switchdev_notifier_type nt, struct net_device *dev, const struct switchdev_obj *obj, struct switchdev_trans *trans, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff819fc4f0)
Location: net/switchdev/switchdev.c:356
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_port_obj_del_deferred
  - net/switchdev/switchdev.c:switchdev_port_obj_add_now
  - net/switchdev/switchdev.c:switchdev_port_obj_add_now
```
**Symbols:**

```
ffffffff819fc4f0-ffffffff819fc57d: switchdev_port_obj_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int switchdev_port_obj_notify(enum switchdev_notifier_type nt, struct net_device *dev, const struct switchdev_obj *obj, struct switchdev_trans *trans, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/switchdev/switchdev.c (0)
Location: net/switchdev/switchdev.c:221
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_port_obj_del_deferred
  - net/switchdev/switchdev.c:switchdev_port_obj_add_now
  - net/switchdev/switchdev.c:switchdev_port_obj_add_now
```
**Symbols:**

```
ffffffff81a6b4c0-ffffffff81a6b558: switchdev_port_obj_notify (STB_LOCAL)
ffffffff81a6bddd-ffffffff81a6bdf0: switchdev_port_obj_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int switchdev_port_obj_notify(enum switchdev_notifier_type nt, struct net_device *dev, const struct switchdev_obj *obj, struct switchdev_trans *trans, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81aa1eb0)
Location: net/switchdev/switchdev.c:221
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_port_obj_del_deferred
  - net/switchdev/switchdev.c:switchdev_port_obj_add_now
  - net/switchdev/switchdev.c:switchdev_port_obj_add_now
```
**Symbols:**

```
ffffffff81aa1eb0-ffffffff81aa1f3d: switchdev_port_obj_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int switchdev_port_obj_notify(enum switchdev_notifier_type nt, struct net_device *dev, const struct switchdev_obj *obj, struct switchdev_trans *trans, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81b9d880)
Location: net/switchdev/switchdev.c:221
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_port_obj_del_deferred
  - net/switchdev/switchdev.c:switchdev_port_obj_add_now
  - net/switchdev/switchdev.c:switchdev_port_obj_add_now
```
**Symbols:**

```
ffffffff81b9d880-ffffffff81b9d907: switchdev_port_obj_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int switchdev_port_obj_notify(enum switchdev_notifier_type nt, struct net_device *dev, const struct switchdev_obj *obj, struct switchdev_trans *trans, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81bad190)
Location: net/switchdev/switchdev.c:221
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_port_obj_del_deferred
  - net/switchdev/switchdev.c:switchdev_port_obj_add_now
  - net/switchdev/switchdev.c:switchdev_port_obj_add_now
```
**Symbols:**

```
ffffffff81bad190-ffffffff81bad217: switchdev_port_obj_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int switchdev_port_obj_notify(enum switchdev_notifier_type nt, struct net_device *dev, const struct switchdev_obj *obj, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81b9c420)
Location: net/switchdev/switchdev.c:193
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_port_obj_del_deferred
  - net/switchdev/switchdev.c:switchdev_port_obj_add_deferred
```
**Symbols:**

```
ffffffff81b9c420-ffffffff81b9c4ad: switchdev_port_obj_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int switchdev_port_obj_notify(enum switchdev_notifier_type nt, struct net_device *dev, const struct switchdev_obj *obj, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/switchdev/switchdev.c (0)
Location: net/switchdev/switchdev.c:193
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_port_obj_del_deferred
  - net/switchdev/switchdev.c:switchdev_port_obj_add_deferred
```
**Symbols:**

```
ffffffff81c696f0-ffffffff81c697a4: switchdev_port_obj_notify (STB_LOCAL)
ffffffff81d42293-ffffffff81d422bc: switchdev_port_obj_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int switchdev_port_obj_notify(enum switchdev_notifier_type nt, struct net_device *dev, const struct switchdev_obj *obj, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/switchdev/switchdev.c (0)
Location: net/switchdev/switchdev.c:194
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_port_obj_del_deferred
  - net/switchdev/switchdev.c:switchdev_port_obj_add_deferred
```
**Symbols:**

```
ffffffff81e0c7c0-ffffffff81e0c87a: switchdev_port_obj_notify (STB_LOCAL)
ffffffff81f0ebf6-ffffffff81f0ec1f: switchdev_port_obj_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int switchdev_port_obj_notify(enum switchdev_notifier_type nt, struct net_device *dev, const struct switchdev_obj *obj, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/switchdev/switchdev.c (0)
Location: net/switchdev/switchdev.c:194
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_port_obj_del_deferred
  - net/switchdev/switchdev.c:switchdev_port_obj_add_deferred
```
**Symbols:**

```
ffffffff81fe2910-ffffffff81fe29ca: switchdev_port_obj_notify (STB_LOCAL)
ffffffff820b57c6-ffffffff820b57ef: switchdev_port_obj_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int switchdev_port_obj_notify(enum switchdev_notifier_type nt, struct net_device *dev, const struct switchdev_obj *obj, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/switchdev/switchdev.c (0)
Location: net/switchdev/switchdev.c:194
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_port_obj_del_deferred
  - net/switchdev/switchdev.c:switchdev_port_obj_add_deferred
```
**Symbols:**

```
ffffffff8205ec30-ffffffff8205eceb: switchdev_port_obj_notify (STB_LOCAL)
ffffffff82136d4f-ffffffff82136d78: switchdev_port_obj_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int switchdev_port_obj_notify(enum switchdev_notifier_type nt, struct net_device *dev, const struct switchdev_obj *obj, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/switchdev/switchdev.c (0)
Location: net/switchdev/switchdev.c:223
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_port_obj_del_deferred
  - net/switchdev/switchdev.c:switchdev_port_obj_add_deferred
```
**Symbols:**

```
ffffffff82131a70-ffffffff82131b2b: switchdev_port_obj_notify (STB_LOCAL)
ffffffff82218b9c-ffffffff82218bc5: switchdev_port_obj_notify.cold (STB_LOCAL)
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
int switchdev_port_obj_notify(enum switchdev_notifier_type nt, struct net_device *dev, const struct switchdev_obj *obj, struct switchdev_trans *trans, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffff800010d733a8)
Location: net/switchdev/switchdev.c:221
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_port_obj_del_deferred
  - net/switchdev/switchdev.c:switchdev_port_obj_add_now
  - net/switchdev/switchdev.c:switchdev_port_obj_add_now
```
**Symbols:**

```
ffff800010d733a8-ffff800010d7346c: switchdev_port_obj_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int switchdev_port_obj_notify(enum switchdev_notifier_type nt, struct net_device *dev, const struct switchdev_obj *obj, struct switchdev_trans *trans, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (c0e703dc)
Location: net/switchdev/switchdev.c:221
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_port_obj_del_deferred
  - net/switchdev/switchdev.c:switchdev_port_obj_add_now
  - net/switchdev/switchdev.c:switchdev_port_obj_add_now
```
**Symbols:**

```
c0e703dc-c0e704ac: switchdev_port_obj_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int switchdev_port_obj_notify(enum switchdev_notifier_type nt, struct net_device *dev, const struct switchdev_obj *obj, struct switchdev_trans *trans, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (c000000000eb2890)
Location: net/switchdev/switchdev.c:221
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_port_obj_del_deferred
  - net/switchdev/switchdev.c:switchdev_port_obj_add_now
  - net/switchdev/switchdev.c:switchdev_port_obj_add_now
```
**Symbols:**

```
c000000000eb2890-c000000000eb295c: switchdev_port_obj_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int switchdev_port_obj_notify(enum switchdev_notifier_type nt, struct net_device *dev, const struct switchdev_obj *obj, struct switchdev_trans *trans, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffe0008a38da)
Location: net/switchdev/switchdev.c:221
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_port_obj_del_deferred
  - net/switchdev/switchdev.c:switchdev_port_obj_add_now
  - net/switchdev/switchdev.c:switchdev_port_obj_add_now
```
**Symbols:**

```
ffffffe0008a38da-ffffffe0008a396a: switchdev_port_obj_notify (STB_LOCAL)
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
int switchdev_port_obj_notify(enum switchdev_notifier_type nt, struct net_device *dev, const struct switchdev_obj *obj, struct switchdev_trans *trans, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81a41240)
Location: net/switchdev/switchdev.c:221
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_port_obj_del_deferred
  - net/switchdev/switchdev.c:switchdev_port_obj_add_now
  - net/switchdev/switchdev.c:switchdev_port_obj_add_now
```
**Symbols:**

```
ffffffff81a41240-ffffffff81a412cd: switchdev_port_obj_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int switchdev_port_obj_notify(enum switchdev_notifier_type nt, struct net_device *dev, const struct switchdev_obj *obj, struct switchdev_trans *trans, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff819fde30)
Location: net/switchdev/switchdev.c:221
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_port_obj_del_deferred
  - net/switchdev/switchdev.c:switchdev_port_obj_add_now
  - net/switchdev/switchdev.c:switchdev_port_obj_add_now
```
**Symbols:**

```
ffffffff819fde30-ffffffff819fdebd: switchdev_port_obj_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int switchdev_port_obj_notify(enum switchdev_notifier_type nt, struct net_device *dev, const struct switchdev_obj *obj, struct switchdev_trans *trans, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81aad0f0)
Location: net/switchdev/switchdev.c:221
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_port_obj_del_deferred
  - net/switchdev/switchdev.c:switchdev_port_obj_add_now
  - net/switchdev/switchdev.c:switchdev_port_obj_add_now
```
**Symbols:**

```
ffffffff81aad0f0-ffffffff81aad17d: switchdev_port_obj_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int switchdev_port_obj_notify(enum switchdev_notifier_type nt, struct net_device *dev, const struct switchdev_obj *obj, struct switchdev_trans *trans, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81ab9460)
Location: net/switchdev/switchdev.c:221
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_port_obj_del_deferred
  - net/switchdev/switchdev.c:switchdev_port_obj_add_now
  - net/switchdev/switchdev.c:switchdev_port_obj_add_now
```
**Symbols:**

```
ffffffff81ab9460-ffffffff81ab94ed: switchdev_port_obj_notify (STB_LOCAL)
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
<b>Param removed. </b>
<code>struct switchdev_trans *trans</code>
</li>
<li>
<b>Param reordered. </b>
<code>nt, dev, obj, trans, extack</code> ➡️ <code>nt, dev, obj, extack</code>
</li>
</ul>
</details>
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
