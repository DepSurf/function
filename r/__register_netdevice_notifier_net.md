# Function: <code>__register_netdevice_notifier_net</code>

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
int __register_netdevice_notifier_net(struct net *net, struct notifier_block *nb, bool ignore_call_fail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819ff160)
Location: net/core/dev.c:1871
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:register_netdevice_notifier_dev_net
  - net/core/dev.c:register_netdevice_notifier_net
```
**Symbols:**

```
ffffffff819ff160-ffffffff819ff1cf: __register_netdevice_notifier_net (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __register_netdevice_notifier_net(struct net *net, struct notifier_block *nb, bool ignore_call_fail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819feeb0)
Location: net/core/dev.c:1896
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:register_netdevice_notifier_dev_net
  - net/core/dev.c:register_netdevice_notifier_net
```
**Symbols:**

```
ffffffff819feeb0-ffffffff819fef1f: __register_netdevice_notifier_net (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __register_netdevice_notifier_net(struct net *net, struct notifier_block *nb, bool ignore_call_fail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819e5750)
Location: net/core/dev.c:1965
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:register_netdevice_notifier_dev_net
  - net/core/dev.c:register_netdevice_notifier_net
```
**Symbols:**

```
ffffffff819e5750-ffffffff819e57bf: __register_netdevice_notifier_net (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __register_netdevice_notifier_net(struct net *net, struct notifier_block *nb, bool ignore_call_fail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a95c00)
Location: net/core/dev.c:1840
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:register_netdevice_notifier_dev_net
  - net/core/dev.c:register_netdevice_notifier_net
```
**Symbols:**

```
ffffffff81a95c00-ffffffff81a95c6f: __register_netdevice_notifier_net (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __register_netdevice_notifier_net(struct net *net, struct notifier_block *nb, bool ignore_call_fail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c0c5f0)
Location: net/core/dev.c:1789
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:register_netdevice_notifier_dev_net
  - net/core/dev.c:register_netdevice_notifier_net
```
**Symbols:**

```
ffffffff81c0c5f0-ffffffff81c0c669: __register_netdevice_notifier_net (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __register_netdevice_notifier_net(struct net *net, struct notifier_block *nb, bool ignore_call_fail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dbc3c0)
Location: net/core/dev.c:1774
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:register_netdevice_notifier_dev_net
  - net/core/dev.c:register_netdevice_notifier_net
```
**Symbols:**

```
ffffffff81dbc3c0-ffffffff81dbc439: __register_netdevice_notifier_net (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __register_netdevice_notifier_net(struct net *net, struct notifier_block *nb, bool ignore_call_fail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e2cbd0)
Location: net/core/dev.c:1800
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:register_netdevice_notifier_dev_net
  - net/core/dev.c:register_netdevice_notifier_net
```
**Symbols:**

```
ffffffff81e2cbd0-ffffffff81e2cc49: __register_netdevice_notifier_net (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __register_netdevice_notifier_net(struct net *net, struct notifier_block *nb, bool ignore_call_fail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81eeae40)
Location: net/core/dev.c:1804
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:register_netdevice_notifier_dev_net
  - net/core/dev.c:register_netdevice_notifier_net
```
**Symbols:**

```
ffffffff81eeae40-ffffffff81eeaeb9: __register_netdevice_notifier_net (STB_LOCAL)
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
