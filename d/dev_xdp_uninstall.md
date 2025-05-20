# Function: <code>dev_xdp_uninstall</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dev_xdp_uninstall(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81897cb0)
Location: net/core/dev.c:7319
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffffffff81897cb0-ffffffff81897d94: dev_xdp_uninstall (STB_LOCAL)
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
In net/core/dev.c (ffffffff818ba374)
Location: net/core/dev.c:7935
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
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
In net/core/dev.c (ffffffff818fc829)
Location: net/core/dev.c:8032
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
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
In net/core/dev.c (ffffffff8192ee57)
Location: net/core/dev.c:8331
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dev_xdp_uninstall(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a0d3e0)
Location: net/core/dev.c:8761
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffffffff81a0d3e0-ffffffff81a0d5d1: dev_xdp_uninstall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dev_xdp_uninstall(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819ffde0)
Location: net/core/dev.c:9133
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffffffff819ffde0-ffffffff819ffedc: dev_xdp_uninstall (STB_LOCAL)
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
In net/core/dev.c (ffffffff819ec333)
Location: net/core/dev.c:9392
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdevice_many
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
In net/core/dev.c (ffffffff81a9d220)
Location: net/core/dev.c:9383
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdevice_many
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
In net/core/dev.c (ffffffff81c16990)
Location: net/core/dev.c:9121
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdevice_many
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
In net/core/dev.c (ffffffff81dd0c8d)
Location: net/core/dev.c:9108
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdevice_many_notify
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
In net/core/dev.c (ffffffff81e4188d)
Location: net/core/dev.c:9116
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdevice_many_notify
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
In net/core/dev.c (ffffffff81f002a2)
Location: net/core/dev.c:9234
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdevice_many_notify
```
</details>
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
In net/core/dev.c (ffff800010bcbcb4)
Location: net/core/dev.c:8331
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
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
In net/core/dev.c (c0ce9c7c)
Location: net/core/dev.c:8331
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
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
In net/core/dev.c (c000000000ca8610)
Location: net/core/dev.c:8331
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
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
In net/core/dev.c (ffffffe000759556)
Location: net/core/dev.c:8331
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
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
In net/core/dev.c (ffffffff818cee57)
Location: net/core/dev.c:8331
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
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
In net/core/dev.c (ffffffff81888f77)
Location: net/core/dev.c:8331
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
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
In net/core/dev.c (ffffffff8191fe57)
Location: net/core/dev.c:8331
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
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
In net/core/dev.c (ffffffff81941bb7)
Location: net/core/dev.c:8331
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
