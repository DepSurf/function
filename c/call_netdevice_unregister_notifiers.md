# Function: <code>call_netdevice_unregister_notifiers</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
void call_netdevice_unregister_notifiers(struct notifier_block *nb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819fd820)
Location: net/core/dev.c:1747
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_notifier_dev_net
  - net/core/dev.c:unregister_netdevice_notifier_net
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
  - net/core/dev.c:call_netdevice_register_net_notifiers
```
**Symbols:**

```
ffffffff819fd820-ffffffff819fd8c8: call_netdevice_unregister_notifiers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void call_netdevice_unregister_notifiers(struct notifier_block *nb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819fd3f0)
Location: net/core/dev.c:1772
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_notifier_dev_net
  - net/core/dev.c:unregister_netdevice_notifier_net
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
  - net/core/dev.c:call_netdevice_register_net_notifiers
```
**Symbols:**

```
ffffffff819fd3f0-ffffffff819fd49a: call_netdevice_unregister_notifiers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void call_netdevice_unregister_notifiers(struct notifier_block *nb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819e3c60)
Location: net/core/dev.c:1841
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_notifier_dev_net
  - net/core/dev.c:unregister_netdevice_notifier_net
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
  - net/core/dev.c:call_netdevice_register_net_notifiers
```
**Symbols:**

```
ffffffff819e3c60-ffffffff819e3d0a: call_netdevice_unregister_notifiers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void call_netdevice_unregister_notifiers(struct notifier_block *nb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a94500)
Location: net/core/dev.c:1716
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_notifier_dev_net
  - net/core/dev.c:unregister_netdevice_notifier_net
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
  - net/core/dev.c:call_netdevice_register_net_notifiers
```
**Symbols:**

```
ffffffff81a94500-ffffffff81a945aa: call_netdevice_unregister_notifiers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void call_netdevice_unregister_notifiers(struct notifier_block *nb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c0a900)
Location: net/core/dev.c:1665
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_notifier_dev_net
  - net/core/dev.c:unregister_netdevice_notifier_net
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
  - net/core/dev.c:call_netdevice_register_net_notifiers
```
**Symbols:**

```
ffffffff81c0a900-ffffffff81c0a9b4: call_netdevice_unregister_notifiers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void call_netdevice_unregister_notifiers(struct notifier_block *nb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dba7b0)
Location: net/core/dev.c:1650
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_notifier_dev_net
  - net/core/dev.c:unregister_netdevice_notifier_net
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
  - net/core/dev.c:call_netdevice_register_net_notifiers
```
**Symbols:**

```
ffffffff81dba7b0-ffffffff81dba864: call_netdevice_unregister_notifiers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void call_netdevice_unregister_notifiers(struct notifier_block *nb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e2af90)
Location: net/core/dev.c:1676
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_notifier_dev_net
  - net/core/dev.c:unregister_netdevice_notifier_net
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
  - net/core/dev.c:call_netdevice_register_net_notifiers
```
**Symbols:**

```
ffffffff81e2af90-ffffffff81e2b044: call_netdevice_unregister_notifiers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void call_netdevice_unregister_notifiers(struct notifier_block *nb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81ee9010)
Location: net/core/dev.c:1680
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_notifier_dev_net
  - net/core/dev.c:unregister_netdevice_notifier_net
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
  - net/core/dev.c:call_netdevice_register_net_notifiers
```
**Symbols:**

```
ffffffff81ee9010-ffffffff81ee90c4: call_netdevice_unregister_notifiers (STB_LOCAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
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
