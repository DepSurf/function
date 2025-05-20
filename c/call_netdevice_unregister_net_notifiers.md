# Function: <code>call_netdevice_unregister_net_notifiers</code>

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
In net/core/dev.c (ffffffff81a04d51)
Location: net/core/dev.c:1777
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_notifier_dev_net
  - net/core/dev.c:unregister_netdevice_notifier_net
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
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
In net/core/dev.c (ffffffff81a05371)
Location: net/core/dev.c:1802
Inline: True
Inline callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_notifier_dev_net
  - net/core/dev.c:unregister_netdevice_notifier_net
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
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
In net/core/dev.c (ffffffff819ed78b)
Location: net/core/dev.c:1871
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_notifier_dev_net
  - net/core/dev.c:unregister_netdevice_notifier_net
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
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
In net/core/dev.c (ffffffff81a9e9ab)
Location: net/core/dev.c:1746
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_notifier_dev_net
  - net/core/dev.c:unregister_netdevice_notifier_net
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
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
In net/core/dev.c (ffffffff81c176dd)
Location: net/core/dev.c:1695
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_notifier_dev_net
  - net/core/dev.c:unregister_netdevice_notifier_net
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
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
In net/core/dev.c (ffffffff81dc86e7)
Location: net/core/dev.c:1680
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_notifier_dev_net
  - net/core/dev.c:unregister_netdevice_notifier_net
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
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
In net/core/dev.c (ffffffff81e389d6)
Location: net/core/dev.c:1706
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_notifier_dev_net
  - net/core/dev.c:unregister_netdevice_notifier_net
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
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
In net/core/dev.c (ffffffff81ef6b62)
Location: net/core/dev.c:1710
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_notifier_dev_net
  - net/core/dev.c:unregister_netdevice_notifier_net
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
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
