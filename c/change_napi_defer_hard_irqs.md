# Function: <code>change_napi_defer_hard_irqs</code>

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
In net/core/net-sysfs.c (ffffffff81a39b52)
Location: net/core/net-sysfs.c:385
Inline: True
Inline callers:
  - net/core/net-sysfs.c:napi_defer_hard_irqs_store
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
In net/core/net-sysfs.c (ffffffff81a3bed2)
Location: net/core/net-sysfs.c:386
Inline: True
Inline callers:
  - net/core/net-sysfs.c:napi_defer_hard_irqs_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int change_napi_defer_hard_irqs(struct net_device *dev, long unsigned int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff81a207a0)
Location: net/core/net-sysfs.c:386
Inline: False
```
**Symbols:**

```
ffffffff81a207a0-ffffffff81a207b3: change_napi_defer_hard_irqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int change_napi_defer_hard_irqs(struct net_device *dev, long unsigned int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff81ad4be0)
Location: net/core/net-sysfs.c:406
Inline: False
```
**Symbols:**

```
ffffffff81ad4be0-ffffffff81ad4bf3: change_napi_defer_hard_irqs (STB_LOCAL)
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
In net/core/net-sysfs.c (ffffffff81c581ac)
Location: net/core/net-sysfs.c:408
Inline: True
Inline callers:
  - net/core/net-sysfs.c:napi_defer_hard_irqs_store
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
In net/core/net-sysfs.c (ffffffff81e0deec)
Location: net/core/net-sysfs.c:408
Inline: True
Inline callers:
  - net/core/net-sysfs.c:napi_defer_hard_irqs_store
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
In net/core/net-sysfs.c (ffffffff81e8113c)
Location: net/core/net-sysfs.c:408
Inline: True
Inline callers:
  - net/core/net-sysfs.c:napi_defer_hard_irqs_store
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
In net/core/net-sysfs.c (ffffffff81f4210f)
Location: net/core/net-sysfs.c:420
Inline: True
Inline callers:
  - net/core/net-sysfs.c:napi_defer_hard_irqs_store
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
