# Function: <code>netdev_name_node_free</code>

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
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a0dded)
Location: net/core/dev.c:258
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netdev_name_node_alt_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a0ebcd)
Location: net/core/dev.c:261
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:netdev_name_node_alt_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819ec455)
Location: net/core/dev.c:263
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_name_node_alt_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a9d345)
Location: net/core/dev.c:265
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_name_node_alt_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c16b3c)
Location: net/core/dev.c:280
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_name_node_alt_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dd0e2b)
Location: net/core/dev.c:280
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_name_node_alt_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e41a59)
Location: net/core/dev.c:278
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_name_node_alt_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81ef7225)
Location: net/core/dev.c:279
Inline: True
Inline callers:
  - net/core/dev.c:default_device_exit_net
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_name_node_alt_destroy
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
