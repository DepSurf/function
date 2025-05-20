# Function: <code>vcap_enable_lookups</code>

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
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int vcap_enable_lookups(struct vcap_control *vctrl, struct net_device *ndev, int chain_id, long unsigned int cookie, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/ethernet/microchip/vcap/vcap_api.c (ffffffff81bf9510)
Location: drivers/net/ethernet/microchip/vcap/vcap_api.c:2630
Inline: True
```
**Symbols:**

```
ffffffff81bf9510-ffffffff81bf9718: vcap_enable_lookups.part.0 (STB_LOCAL)
ffffffff81bf9730-ffffffff81bf9793: vcap_enable_lookups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int vcap_enable_lookups(struct vcap_control *vctrl, struct net_device *ndev, int src_cid, int dst_cid, long unsigned int cookie, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/ethernet/microchip/vcap/vcap_api.c (ffffffff81c5e340)
Location: drivers/net/ethernet/microchip/vcap/vcap_api.c:3170
Inline: True
```
**Symbols:**

```
ffffffff81c5e340-ffffffff81c5e4f6: vcap_enable_lookups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int vcap_enable_lookups(struct vcap_control *vctrl, struct net_device *ndev, int src_cid, int dst_cid, long unsigned int cookie, bool enable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/ethernet/microchip/vcap/vcap_api.c (ffffffff81d14ca0)
Location: drivers/net/ethernet/microchip/vcap/vcap_api.c:3184
Inline: True
```
**Symbols:**

```
ffffffff81d14ca0-ffffffff81d14e56: vcap_enable_lookups (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int src_cid</code>
</li>
<li>
<b>Param added. </b>
<code>int dst_cid</code>
</li>
<li>
<b>Param removed. </b>
<code>int chain_id</code>
</li>
<li>
<b>Param reordered. </b>
<code>vctrl, ndev, chain_id, cookie, enable</code> ➡️ <code>vctrl, ndev, src_cid, dst_cid, cookie, enable</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
