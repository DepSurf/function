# Function: <code>vcap_is_next_lookup</code>

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
bool vcap_is_next_lookup(struct vcap_control *vctrl, int cur_cid, int next_cid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ethernet/microchip/vcap/vcap_api.c (ffffffff81bf9b20)
Location: drivers/net/ethernet/microchip/vcap/vcap_api.c:1428
Inline: False
```
**Symbols:**

```
ffffffff81bf9b20-ffffffff81bf9cbd: vcap_is_next_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool vcap_is_next_lookup(struct vcap_control *vctrl, int src_cid, int dst_cid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ethernet/microchip/vcap/vcap_api.c (ffffffff81c5dd50)
Location: drivers/net/ethernet/microchip/vcap/vcap_api.c:1663
Inline: False
```
**Symbols:**

```
ffffffff81c5dd50-ffffffff81c5dddf: vcap_is_next_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool vcap_is_next_lookup(struct vcap_control *vctrl, int src_cid, int dst_cid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ethernet/microchip/vcap/vcap_api.c (ffffffff81d14680)
Location: drivers/net/ethernet/microchip/vcap/vcap_api.c:1677
Inline: False
```
**Symbols:**

```
ffffffff81d14680-ffffffff81d1470f: vcap_is_next_lookup (STB_GLOBAL)
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
<code>int cur_cid</code>
</li>
<li>
<b>Param removed. </b>
<code>int next_cid</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
