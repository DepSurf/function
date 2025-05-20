# Function: <code>switchdev_port_same_parent_id</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool switchdev_port_same_parent_id(struct net_device *a, struct net_device *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff8188a500)
Location: net/switchdev/switchdev.c:1289
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_port_fwd_mark_get
```
**Symbols:**

```
ffffffff8188a500-ffffffff8188a5db: switchdev_port_same_parent_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool switchdev_port_same_parent_id(struct net_device *a, struct net_device *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff818bea40)
Location: net/switchdev/switchdev.c:1114
Inline: False
```
**Symbols:**

```
ffffffff818bea40-ffffffff818beb0a: switchdev_port_same_parent_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool switchdev_port_same_parent_id(struct net_device *a, struct net_device *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff818e54a0)
Location: net/switchdev/switchdev.c:1096
Inline: False
```
**Symbols:**

```
ffffffff818e54a0-ffffffff818e55a9: switchdev_port_same_parent_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool switchdev_port_same_parent_id(struct net_device *a, struct net_device *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff8196b080)
Location: net/switchdev/switchdev.c:579
Inline: False
```
**Symbols:**

```
ffffffff8196b080-ffffffff8196b189: switchdev_port_same_parent_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
bool switchdev_port_same_parent_id(struct net_device *a, struct net_device *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/switchdev/switchdev.c (0)
Location: net/switchdev/switchdev.c:579
Inline: False
```
**Symbols:**

```
ffffffff819c5550-ffffffff819c555c: switchdev_port_same_parent_id.cold.13 (STB_LOCAL)
ffffffff819c4c00-ffffffff819c4d01: switchdev_port_same_parent_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
bool switchdev_port_same_parent_id(struct net_device *a, struct net_device *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/switchdev/switchdev.c (0)
Location: net/switchdev/switchdev.c:594
Inline: False
```
**Symbols:**

```
ffffffff819fcbba-ffffffff819fcbc6: switchdev_port_same_parent_id.cold.12 (STB_LOCAL)
ffffffff819fc280-ffffffff819fc381: switchdev_port_same_parent_id (STB_GLOBAL)
```
</details>
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
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
</ul>
