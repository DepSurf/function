# Function: <code>switchdev_handle_fdb_event_to_device</code>

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
int switchdev_handle_fdb_event_to_device(struct net_device *dev, long unsigned int event, const struct switchdev_notifier_fdb_info *fdb_info, bool (*check_cb)(const struct net_device *), bool (*foreign_dev_check_cb)(const struct net_device *, const struct net_device *), int (*mod_cb)(struct net_device *, struct net_device *, long unsigned int, const void *, const struct switchdev_notifier_fdb_info *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81e0d200)
Location: net/switchdev/switchdev.c:514
Inline: False
```
**Symbols:**

```
ffffffff81e0d200-ffffffff81e0d23c: switchdev_handle_fdb_event_to_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int switchdev_handle_fdb_event_to_device(struct net_device *dev, long unsigned int event, const struct switchdev_notifier_fdb_info *fdb_info, bool (*check_cb)(const struct net_device *), bool (*foreign_dev_check_cb)(const struct net_device *, const struct net_device *), int (*mod_cb)(struct net_device *, struct net_device *, long unsigned int, const void *, const struct switchdev_notifier_fdb_info *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff81fe3440)
Location: net/switchdev/switchdev.c:514
Inline: False
```
**Symbols:**

```
ffffffff81fe3440-ffffffff81fe347c: switchdev_handle_fdb_event_to_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int switchdev_handle_fdb_event_to_device(struct net_device *dev, long unsigned int event, const struct switchdev_notifier_fdb_info *fdb_info, bool (*check_cb)(const struct net_device *), bool (*foreign_dev_check_cb)(const struct net_device *, const struct net_device *), int (*mod_cb)(struct net_device *, struct net_device *, long unsigned int, const void *, const struct switchdev_notifier_fdb_info *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff8205f760)
Location: net/switchdev/switchdev.c:514
Inline: False
```
**Symbols:**

```
ffffffff8205f760-ffffffff8205f79c: switchdev_handle_fdb_event_to_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int switchdev_handle_fdb_event_to_device(struct net_device *dev, long unsigned int event, const struct switchdev_notifier_fdb_info *fdb_info, bool (*check_cb)(const struct net_device *), bool (*foreign_dev_check_cb)(const struct net_device *, const struct net_device *), int (*mod_cb)(struct net_device *, struct net_device *, long unsigned int, const void *, const struct switchdev_notifier_fdb_info *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff821326b0)
Location: net/switchdev/switchdev.c:587
Inline: False
```
**Symbols:**

```
ffffffff821326b0-ffffffff821326ec: switchdev_handle_fdb_event_to_device (STB_GLOBAL)
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
