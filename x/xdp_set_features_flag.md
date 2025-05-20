# Function: <code>xdp_set_features_flag</code>

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
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void xdp_set_features_flag(struct net_device *dev, xdp_features_t val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81e7906b)
Location: net/core/xdp.c:776
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_features_clear_redirect_target
  - net/core/xdp.c:xdp_features_clear_redirect_target
  - net/core/xdp.c:xdp_features_set_redirect_target
  - net/core/xdp.c:xdp_features_set_redirect_target
```
**Symbols:**

```
ffffffff81e784f0-ffffffff81e78537: xdp_set_features_flag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void xdp_set_features_flag(struct net_device *dev, xdp_features_t val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81f38f3b)
Location: net/core/xdp.c:807
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_features_clear_redirect_target
  - net/core/xdp.c:xdp_features_clear_redirect_target
  - net/core/xdp.c:xdp_features_set_redirect_target
  - net/core/xdp.c:xdp_features_set_redirect_target
```
**Symbols:**

```
ffffffff81f384b0-ffffffff81f384f7: xdp_set_features_flag (STB_GLOBAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
