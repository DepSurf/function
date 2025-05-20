# Function: <code>vcap_port_debugfs</code>

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
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void vcap_port_debugfs(struct device *dev, struct dentry *parent, struct vcap_control *vctrl, struct net_device *ndev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c (ffffffff81bf3560)
Location: drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c:359
Inline: False
```
**Symbols:**

```
ffffffff81bf3560-ffffffff81bf35ed: vcap_port_debugfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void vcap_port_debugfs(struct device *dev, struct dentry *parent, struct vcap_control *vctrl, struct net_device *ndev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c (ffffffff81c568a0)
Location: drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c:386
Inline: False
```
**Symbols:**

```
ffffffff81c568a0-ffffffff81c5692d: vcap_port_debugfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void vcap_port_debugfs(struct device *dev, struct dentry *parent, struct vcap_control *vctrl, struct net_device *ndev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c (ffffffff81d0d030)
Location: drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c:386
Inline: False
```
**Symbols:**

```
ffffffff81d0d030-ffffffff81d0d0d0: vcap_port_debugfs (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
