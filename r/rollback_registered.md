# Function: <code>rollback_registered</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void rollback_registered(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817168d0)
Location: net/core/dev.c:6294
Inline: False
Direct callers:
  - net/core/dev.c:register_netdevice
```
**Symbols:**

```
ffffffff817168d0-ffffffff81716931: rollback_registered (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817874c6)
Location: net/core/dev.c:6778
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817b4a86)
Location: net/core/dev.c:6948
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817d365d)
Location: net/core/dev.c:7146
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8184db68)
Location: net/core/dev.c:7318
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8189822b)
Location: net/core/dev.c:7512
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdevice_queue
  - net/core/dev.c:register_netdevice
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818ba68b)
Location: net/core/dev.c:8139
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdevice_queue
  - net/core/dev.c:register_netdevice
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818fcb4b)
Location: net/core/dev.c:8242
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdevice_queue
  - net/core/dev.c:register_netdevice
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81938e5e)
Location: net/core/dev.c:8553
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a0e27b)
Location: net/core/dev.c:9009
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdevice_queue
  - net/core/dev.c:register_netdevice
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
In net/core/dev.c (ffffffff81a05deb)
Location: net/core/dev.c:9623
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdevice_queue
  - net/core/dev.c:register_netdevice
```
</details>
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
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bcbfa8)
Location: net/core/dev.c:8553
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdevice_queue
  - net/core/dev.c:register_netdevice
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0cf2760)
Location: net/core/dev.c:8553
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000cb7780)
Location: net/core/dev.c:8553
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe000760d94)
Location: net/core/dev.c:8553
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818d8e2e)
Location: net/core/dev.c:8553
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81892c6e)
Location: net/core/dev.c:8553
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81929e5e)
Location: net/core/dev.c:8553
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8194b529)
Location: net/core/dev.c:8553
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
