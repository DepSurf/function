# Function: <code>__switchdev_port_attr_set</code>

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
int __switchdev_port_attr_set(struct net_device *dev, const struct switchdev_attr *attr, struct switchdev_trans *trans);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff8188a010)
Location: net/switchdev/switchdev.c:220
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_port_attr_set_now
  - net/switchdev/switchdev.c:switchdev_port_attr_set_now
  - net/switchdev/switchdev.c:__switchdev_port_attr_set
```
**Symbols:**

```
ffffffff8188a010-ffffffff8188a0d7: __switchdev_port_attr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __switchdev_port_attr_set(struct net_device *dev, const struct switchdev_attr *attr, struct switchdev_trans *trans);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff818be820)
Location: net/switchdev/switchdev.c:219
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_port_attr_set_now
  - net/switchdev/switchdev.c:switchdev_port_attr_set_now
  - net/switchdev/switchdev.c:__switchdev_port_attr_set
```
**Symbols:**

```
ffffffff818be820-ffffffff818be8e7: __switchdev_port_attr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __switchdev_port_attr_set(struct net_device *dev, const struct switchdev_attr *attr, struct switchdev_trans *trans);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff818e51b0)
Location: net/switchdev/switchdev.c:219
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_port_attr_set_now
  - net/switchdev/switchdev.c:switchdev_port_attr_set_now
  - net/switchdev/switchdev.c:__switchdev_port_attr_set
```
**Symbols:**

```
ffffffff818e51b0-ffffffff818e5275: __switchdev_port_attr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __switchdev_port_attr_set(struct net_device *dev, const struct switchdev_attr *attr, struct switchdev_trans *trans);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff8196ae60)
Location: net/switchdev/switchdev.c:219
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_port_attr_set_now
  - net/switchdev/switchdev.c:switchdev_port_attr_set_now
  - net/switchdev/switchdev.c:__switchdev_port_attr_set
```
**Symbols:**

```
ffffffff8196ae60-ffffffff8196af28: __switchdev_port_attr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __switchdev_port_attr_set(struct net_device *dev, const struct switchdev_attr *attr, struct switchdev_trans *trans);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff819c4920)
Location: net/switchdev/switchdev.c:219
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_port_attr_set_now
  - net/switchdev/switchdev.c:switchdev_port_attr_set_now
  - net/switchdev/switchdev.c:__switchdev_port_attr_set
```
**Symbols:**

```
ffffffff819c4920-ffffffff819c49ee: __switchdev_port_attr_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __switchdev_port_attr_set(struct net_device *dev, const struct switchdev_attr *attr, struct switchdev_trans *trans);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff819fbdc0)
Location: net/switchdev/switchdev.c:219
Inline: False
Direct callers:
  - net/switchdev/switchdev.c:switchdev_port_attr_set_now
  - net/switchdev/switchdev.c:switchdev_port_attr_set_now
  - net/switchdev/switchdev.c:__switchdev_port_attr_set
```
**Symbols:**

```
ffffffff819fbdc0-ffffffff819fbe8e: __switchdev_port_attr_set (STB_LOCAL)
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
