# Function: <code>mv_chan_start_new_chain</code>

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
<summary>In <code>arm64</code>: ✅</summary>

```c
void mv_chan_start_new_chain(struct mv_xor_chan *mv_chan, struct mv_xor_desc_slot *sw_desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/mv_xor.c (ffff800010805cf0)
Location: drivers/dma/mv_xor.c:178
Inline: False
Direct callers:
  - drivers/dma/mv_xor.c:mv_xor_tx_submit
  - drivers/dma/mv_xor.c:mv_chan_slot_cleanup
  - drivers/dma/mv_xor.c:mv_chan_slot_cleanup
```
**Symbols:**

```
ffff800010805cf0-ffff800010805d90: mv_chan_start_new_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mv_chan_start_new_chain(struct mv_xor_chan *mv_chan, struct mv_xor_desc_slot *sw_desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/mv_xor.c (c0923f28)
Location: drivers/dma/mv_xor.c:178
Inline: False
Direct callers:
  - drivers/dma/mv_xor.c:mv_xor_tx_submit
  - drivers/dma/mv_xor.c:mv_chan_slot_cleanup
  - drivers/dma/mv_xor.c:mv_chan_slot_cleanup
  - drivers/dma/mv_xor.c:mv_chan_slot_cleanup
```
**Symbols:**

```
c0923f28-c0923fc8: mv_chan_start_new_chain (STB_LOCAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
