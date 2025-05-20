# Function: <code>switchdev_port_obj_dump</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int switchdev_port_obj_dump(struct net_device *dev, struct switchdev_obj *obj, switchdev_obj_dump_cb_t *cb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff8188b2e0)
Location: net/switchdev/switchdev.c:550
Inline: True
Direct callers:
  - net/switchdev/switchdev.c:switchdev_port_fdb_dump
  - net/switchdev/switchdev.c:switchdev_port_vlan_fill
```
**Symbols:**

```
ffffffff8188b2e0-ffffffff8188b3ac: switchdev_port_obj_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int switchdev_port_obj_dump(struct net_device *dev, struct switchdev_obj *obj, switchdev_obj_dump_cb_t *cb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff818bf650)
Location: net/switchdev/switchdev.c:547
Inline: True
Direct callers:
  - net/switchdev/switchdev.c:switchdev_port_fdb_dump
  - net/switchdev/switchdev.c:switchdev_port_vlan_fill
```
**Symbols:**

```
ffffffff818bf650-ffffffff818bf71c: switchdev_port_obj_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int switchdev_port_obj_dump(struct net_device *dev, struct switchdev_obj *obj, switchdev_obj_dump_cb_t *cb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/switchdev/switchdev.c (ffffffff818e5f40)
Location: net/switchdev/switchdev.c:547
Inline: True
Direct callers:
  - net/switchdev/switchdev.c:switchdev_port_fdb_dump
  - net/switchdev/switchdev.c:switchdev_port_vlan_fill
```
**Symbols:**

```
ffffffff818e5f40-ffffffff818e600a: switchdev_port_obj_dump (STB_GLOBAL)
```
</details>
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
</ul>
