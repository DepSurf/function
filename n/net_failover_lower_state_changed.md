# Function: <code>net_failover_lower_state_changed</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void net_failover_lower_state_changed(struct net_device *slave_dev, struct net_device *primary_dev, struct net_device *standby_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/net_failover.c (ffffffff81c6f950)
Location: drivers/net/net_failover.c:431
Inline: False
Direct callers:
  - drivers/net/net_failover.c:net_failover_slave_link_change
  - drivers/net/net_failover.c:net_failover_slave_register
  - drivers/net/net_failover.c:net_failover_slave_register
```
**Symbols:**

```
ffffffff81c6f950-ffffffff81c6f9e2: net_failover_lower_state_changed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void net_failover_lower_state_changed(struct net_device *slave_dev, struct net_device *primary_dev, struct net_device *standby_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/net_failover.c (ffffffff81d24200)
Location: drivers/net/net_failover.c:431
Inline: False
Direct callers:
  - drivers/net/net_failover.c:net_failover_slave_link_change
  - drivers/net/net_failover.c:net_failover_slave_register
  - drivers/net/net_failover.c:net_failover_slave_register
```
**Symbols:**

```
ffffffff81d24200-ffffffff81d2429e: net_failover_lower_state_changed (STB_LOCAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
