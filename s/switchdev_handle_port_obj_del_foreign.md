# Function: <code>switchdev_handle_port_obj_del_foreign</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int switchdev_handle_port_obj_del_foreign(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), bool (*foreign_dev_check_cb)(const struct net_device *, const struct net_device *), int (*del_cb)(struct net_device *, const void *, const struct switchdev_obj *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81e0d6e0)
Location: net/switchdev/switchdev.c:741
Inline: False
```
**Symbols:**

```
ffffffff81e0d6e0-ffffffff81e0d707: switchdev_handle_port_obj_del_foreign (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int switchdev_handle_port_obj_del_foreign(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), bool (*foreign_dev_check_cb)(const struct net_device *, const struct net_device *), int (*del_cb)(struct net_device *, const void *, const struct switchdev_obj *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81fe3980)
Location: net/switchdev/switchdev.c:741
Inline: False
```
**Symbols:**

```
ffffffff81fe3980-ffffffff81fe39a7: switchdev_handle_port_obj_del_foreign (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int switchdev_handle_port_obj_del_foreign(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), bool (*foreign_dev_check_cb)(const struct net_device *, const struct net_device *), int (*del_cb)(struct net_device *, const void *, const struct switchdev_obj *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff8205fca0)
Location: net/switchdev/switchdev.c:741
Inline: False
```
**Symbols:**

```
ffffffff8205fca0-ffffffff8205fcc7: switchdev_handle_port_obj_del_foreign (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int switchdev_handle_port_obj_del_foreign(struct net_device *dev, struct switchdev_notifier_port_obj_info *port_obj_info, bool (*check_cb)(const struct net_device *), bool (*foreign_dev_check_cb)(const struct net_device *, const struct net_device *), int (*del_cb)(struct net_device *, const void *, const struct switchdev_obj *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff82132be0)
Location: net/switchdev/switchdev.c:814
Inline: False
```
**Symbols:**

```
ffffffff82132be0-ffffffff82132c07: switchdev_handle_port_obj_del_foreign (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
